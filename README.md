# 제목(Header)

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

-space 2번 or br

동해물과 백두산이 마르고 닳도록  
(띄어쓰기 두번하면 줄바꿈이 됨)  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br />
대한 사람 대한으로 길이 보전하세  

# 강조(Emphasis)

_이텔릭_   
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u> < html에서는 안쓰는 문법>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록  
숫자 1번만 하더라도 1,2,3 차례로 됨.
1. 순서가 필요한 목록 
    1. 순서가 필요한 목록 -sub목록. Tab 2
    1. 순서가 필요한 목록 
1. 순서가 필요한 목록 

- 순서가 필요하지 않은 항목
- 순서가 필요하지 않은 항목
- 순서가 필요하지 않은 항목
    - 순서가 필요하지 않은 항목 Tab 2
    - 순서가 필요하지 않은 항목
- 순서가 필요하지 않은 항목
- 순서가 필요하지 않은 항목

# 링크(Links)

<a href="https://google.com">HTML방식의 LINK</a>  
[MARKDOWN방식의 LINK](https://google.com) 

마우스를 네이버 글자 위로 올리면 뜨는 title 있는 link 
<a href= "https://naver.com" title="NAVER로 이동!">HTML방식의 TITLE 있는 LINK</a>  
[MARKDOWN방식의 TITLE 있는 LINK]("https://naver.com" "NAVER로 이동!")  

현재 페이지에 링크를 변경하는 건, HTML a Tag로만 가능함(MARKDOWN 기능에는 없음)=
<a href="https://naver.com" title="NAVER 로 이동!!" target="_blank">NAVER</a>  

# 이미지(Image)

```plaintext
![img이름](igm 주소)
```
![site](https://heropy.blog/css/images/logo.png)

```plaintext
[![img이름](img주소)](img click시 이동하는 사이트 주소)
```
[![site](https://heropy.blog/css/images/logo.png) ](https://heropy.blog/)

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 똔는  
간접으로 따온 문장.  
>(네이버 국어 사전)

> 인용문을 작성하세요!  
>> 중첩된 인용문!  
>>> 중중첩된 인용문1  
>>> 중중첩된 인용문2  
>>> 중중첩된 인용문3  

# 인라인(inline) 코드 강조
 
CSS에서 `background` 혹은  
`background-emage` 속성으로 요소에 배경이미지를  
삽입할 수 있습니다.!!

# 블록(block) 코드 강조

```html  
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>

```
```css
.list > li {
  position: absolute;
  top: 40px;
}
```
```javascript
function func(){
  var a='AAA';
  return a;
}
```
```bash
$ git commit -m 'Study Markdown' <터미널내용>
```
```plaintext
소스코드 아닌 일반 문장은  
이걸로 나타냅니다.
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | View포트 | X

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration:underline;">백두산</span>이 마르고 닳도록 <br/>
하느님이 보우하사 우리 나라 만세  

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a><br/>  
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY"/>

# 수평선(Horizontal Rule)

---

***

___


