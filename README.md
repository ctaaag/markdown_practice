# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산 </br>
대한 사람 대한으로 길이 보전하세

# Markdown

## 제목, 문장, 줄바꿈

#### 제목짓기

```
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
```

> 제목은 # 숫자 만큼 크기를 결정할 수 있음

#### 문장짓기 + 줄바꿈

```
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
무궁화 삼천리 화려강산 </br>
대한 사람 대한으로 길이 보전하세
```

그냥 텍스트를 입력하면 문장을 지을 수 있음
줄바꿈은 spacebar 2번 입력 혹은 </br을 입력하면 줄바꿈 가능

## 강조, 줄바꿈

#### 서식

> _이탤릭_
> **두껍게**
> **_이탤릭 + 두껍게_**
> ~~취소선~~
> <u>밑줄</u>

![](https://velog.velcdn.com/images/ctaaag/post/24ce112b-78a7-4fdc-855e-902c9e5e362e/image.png)

#### 목록(List)

```git
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
```

![](https://velog.velcdn.com/images/ctaaag/post/f56b0a09-9367-42c0-90d2-80b9dc19b9ba/image.png)

#### 링크(Links)

<a href="https://google.com"> Google </a>
[Google](https://google.com)
<a href="https://naver.com"
   title="Naver로 이동!">Naver</a>
[NAVER](https://naver.com "Naver로 이동!")

#### 이미지로 이동

```
<!--
![파일이름](링크)
[파일이름](링크)
-->
```

[image](https://brunch.co.kr/@samsamvet/17)
![image](https://brunch.co.kr/@samsamvet/17)

#### 인용문

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> (네이버 국어 사전)

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문 1
> > > 중중첩된 인용문 2
> > > 중중첩된 인용문 3

#### 인라인(inline) 코드 강조

css에서 `backgroind` 혹은 `background.image` 속성으로 요소에 배경이미지 삽입

#### 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">google</a>
```

```css
.list > li {
  positon: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = "aaa";
  return a;
}
```

```zsh
$ git commit 'study Markdown'
```

#### 표(Table)

position 속성

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      O |
| relative |     요소 자산     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

#### 원시 HTML

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 <span style="text-decoration: underline;">우리나라</span> 만세

---

<a href="https://www.google.co.kr/"
   target="_blank">google</a>

---

<img width="70" src="https://brunch.co.kr/@samsamvet/17"
     alt="bonobono" />

#### 수평선

---

---

---
