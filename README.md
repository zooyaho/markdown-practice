# 제목(Header)

# 제목 1 - h1태그
## 제목 2 - h2태그
### 제목 3 - h3태그
#### 제목 4 - h4태그
##### 제목 5 - h5태그
###### 제목 6 - h6태그


# 문장(paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세   
: < p > 태그  

# 줄바꿈(Line Breaks)  

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세 <br>
무궁화 삼천리 화려 강산<br>
대한 사람 대한으로 길이 보전하세   
: (띄어쓰기 2번) or < br />

# 강조(Emphasis)  

_이텔릭_  
**두껍게**  
**_이텔릭+두껍게_**  
~~취소선~~  
<u>밑줄</u>  

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록  
    1. 순서가 필요한 목록
1. 순서가 필요한 목록  

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>  

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동~!">NAVER</a>  

[NAVER](https://naver.com "NAVER로 이동~!")

<a href="https://naver.com" title="NAVER로 이동~!" target="_blank">NAVER</a>  -> target="_blank"는 < a >를 이용해야 함

# 이미지(Images)

![HEROPY](https://cdn.pixabay.com/photo/2018/05/11/08/11/pet-3389729_960_720.jpg)

[![HEROPY](https://cdn.pixabay.com/photo/2018/05/11/08/11/pet-3389729_960_720.jpg)](https://heropy.blog/)

# 인용문(BlochQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)
> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중첩된 인용문1  
>>> 중첩된 인용문2  
>>> 중첩된 인용문3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은
`background-image` 속성으로   
요소에 배경 이미지를 삽입할 수 있습니다.  
백틱(`): option + ~

# 블록(block) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>  
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript 
function func {
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성
값 | 의미 | 기본값  
--|--|--
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

position 속성(align 적용)
값 | 의미 | 기본값  
:--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

```plaintext
MarkDown은 브라우저에서 출력하기 때문에 표준 HTML로 변환됨.  
하지만 변환될 때 사용되는 플랫폼에 따라서 조금씩 다르게 변환될 수 있음.  
-> MarkDown은 표준이 없기 때문  
```

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br /> 하느님이 보우하사 우리나라 만세   

<a href="https://naver.com" title="NAVER로 이동~!" target="_blank">NAVER</a>  

<img width="70" src="https://cdn.pixabay.com/photo/2022/03/06/05/30/clouds-7050884_960_720.jpg"  alt="HEROPY">

# 수평선(Horizontal Rule)

---

***

___