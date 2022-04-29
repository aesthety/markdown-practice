# 제목(HEADER)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록 
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세

# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**-이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록  
    1. 순서가 필요한 목록
1. 순서가 필요한 목록


- 순서가 필요한 목록
- 순서가 필요한 목록
- 순서가 필요한 목록
    - 순서가 필요한 목록
    - 순서가 필요한 목록
- 순서가 필요한 목록

# 링크(Anchor)
<a href="https://www.google.com">구글</a>  
[구글](https://www.google.com)

<a href="https://www.google.com" title ="google로 이동">구글</a>  
[구글](https://www.google.com "google로 이동")  
target속성은 안되므로 <a>태그 사용  

# 이미지(img)

![logo](logo.svg)  
  
이미지에 링크  :  
[![logo](logo.svg)](https://www.google.com)
 


# 인용문(Blockquote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네니버 국어 사전)

> 인용문을 작성합니다. 
>> 중첩된 인용문  
>>> 중첩된 인용문1  
>>> 중첩된 인용문2

# 인라인(inline) 코드 강조

css에서 `background` 혹은 `background-image`      속성으로  
요소에 배경 이미지를 삽입할 수 있습니다. 


# 블록(Block) 코드 강조

```html
<a href="https://www.google.com">구글</a>
```


```css
body {
    font-family: 'Nanum Gothic', sans-serif;
    font-size: 16px;
    font-weight: 400;
    line-height: 1.4;
    color: #333;
  }
```

```javascript
const searchEl = document.querySelector('.search')
const searchInputEl = searchEl.querySelector('input')
// 검색창 요소를 클릭하면 실행.
searchEl.addEventListener('click', function () {
  searchInputEl.focus()
})
```

```git
$ git init
```

# 표(Table)
하이픈 두개와 버티컬바로 만듬
정렬방법 기본은 왼쪽정렬,   
가운데 정렬 :--:  
우측정렬 --:  

position 속성  

값 | 의미 | 기본값
--|:--:|--:
static | 없음 | O
relative | 요소 자신 | X
absolute | 위치상 부모요소 | X
fixed | 뷰포트 | X


# 원시HTML(RAW HTML)
<u>html의 문법</u>을 그대로 사용  
<span style="text-decoration:underline">줄바꿈은 띄어쓰기 두번</span>한다. (동작안할수도 있음. ), 원시태그작성해야함. <br />

target, width 속성 등은 적용되지 않으므로 원시html로 작성  


# 수평선(Horizontal Rule)

---

***

___

위의 기호 모두 각 세번씩작성한것. 가능