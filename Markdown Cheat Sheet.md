# GitHub Flavored Markdown (GFM) Cheat Sheet 

- [요약본](#요약본)
- [자세히](#자세히)
- [1. Heading (제목)](#1-heading-제목)
- [H2 ─ 굵게 \& 밑줄](#h2--굵게--밑줄)
  - [H3 ─ 굵게](#h3--굵게)
    - [H4 ─ 일반 본문의 볼드체와 동일하여 효용↓](#h4--일반-본문의-볼드체와-동일하여-효용)
      - [H5 ─ 본문보다 작음](#h5--본문보다-작음)
        - [H6 ─ 엷은 회색](#h6--엷은-회색)
- [2. Text formatting](#2-text-formatting)
- [3. List](#3-list)
  - [1) Bullet list (Unordered list)](#1-bullet-list-unordered-list)
  - [2) Numbered list (Ordered list)](#2-numbered-list-ordered-list)
  - [3) Task list (GFM 추가 기능 ⭐)](#3-task-list-gfm-추가-기능-)
- [4. Code block (핵심 중 핵심)](#4-code-block-핵심-중-핵심)
- [5. Quote, Callout](#5-quote-callout)
  - [1) Blockquote(기본 기능)](#1-blockquote기본-기능)
  - [2) Callout(GFM 추가 기능⭐)](#2-calloutgfm-추가-기능)
- [6. 링크 Link, 이미지 Image, 뱃지 Badge](#6-링크-link-이미지-image-뱃지-badge)
  - [1) 링크 Link](#1-링크-link)
  - [2) 이미지 Image, 뱃지 Badge](#2-이미지-image-뱃지-badge)
  - [3) 링크가 있는 이미지 Image, 뱃지 Badge](#3-링크가-있는-이미지-image-뱃지-badge)
- [7. 표 Table (GFM 추가 기능⭐)](#7-표-table-gfm-추가-기능)
- [8. 구분선 Horizontal line](#8-구분선-horizontal-line)
- [9. 접히는 블록 Collapsible section (GFM 추가 기능⭐)](#9-접히는-블록-collapsible-section-gfm-추가-기능)
- [10. Emoji](#10-emoji)
- [11. HTML 혼용 가능 ⭐](#11-html-혼용-가능-)
- [12. 각주 Footnote](#12-각주-footnote)

---

> [!NOTE]
> 요약본보다가 모르겠으면, 아래 읽어보기

## 요약본

1. Heading `#1~6`　`**굵** ` → **굵**　`*기울*` → *기울*　`~~취소~~` → ~~취소~~　구분선 `---`
2. Code `` `code` ``　` ```언어명 ```  `
3. 불렛:`-`　순서:`1.`　체크:`- [ ]`, `- [x]`
4. Quote, Callout `>`　`> [!NOTE]ℹ️파`　`> [!TIP]💡초`　`> [!IMPORTANT]🗨️보`　`> [!WARNING]⚠️노`　`> [!CAUTION]🛑빨`
5. Link, Image, Badge
    - Link: `[text](Link URL)`
    - Image: `![IMG alt](IMG URL)`
    - Linked image: `[ ![IMG alt](IMG URL) ] (Link URL)`
    - Reference-style link: `(URL)→[Variable]` `[Variable]: URL`
    - 뱃지 URL 형식: `https://img.shields.io/badge/왼쪽칸-오른쪽칸-색깔?logo=로고이름&logoColor=로고색`
    - 뱃지 URL 빌더: https://shields.io/badges/static-badge
    - 로고이름, 색 참고 사이트: https://simpleicons.org/
    - `![Python](https://img.shields.io/badge/Python-3.12-blue)` → ![Python](https://img.shields.io/badge/Python-3.12-blue)
    - `![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)` → ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
    - `![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)` → ![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)
6. 표 Table
    ```
    | 카테고리1 | 카테고리 2 | 카테고리 3 |
    |---|:---:|---:|
    |짜장면|♥♥♥♡♡|간짜장은 함춘원|
    ```
  
    | 카테고리1 | 카테고리 2 | 카테고리 3 |
    |---|:---:|---:|
    |짜장면|♥♥♥♡♡|간짜장은 함춘원|
7. 접히는 블록 Collapsible section (GFM 추가 기능⭐)
    ```
    <details>
    <summary>나를 눌러보세요</summary>
    
    짜잔
    
    </details>
    ```
    <details>
    <summary>나를 눌러보세요</summary>
    
    짜잔
    
    </details>
8. Emoji `:이름:` 📁🎯💡⚠️⛔💥🚨🐛🔥✅✔️🔒🔑
9. HTML 혼용가능
    ```html
    <div align="center">
      정말 가운데 정렬을 하고 싶다면!
    </div>
    ```
    - 개행은 `<br>`
    - 공백은 `&nbsp;`
10. 각주 Footnote
```
ABC[^1]가나다123

[^1]: ABC: 영어입니다.
```

---
## 자세히
## 1. Heading (제목)

TOC(목차) 생성의 핵심이 되는 태그

```md
# H1 ─ 굵게 & 밑줄
## H2 ─ 굵게 & 밑줄
### H3 ─ 굵게
#### H4 ─ 일반 본문의 볼드체와 동일하여 효용↓
**H4 일반 본문의 볼드체**
##### H5 ─ 본문보다 작음
###### H6 ─ 엷은 회색
```

# H1 ─ 굵게 & 밑줄
## H2 ─ 굵게 & 밑줄
### H3 ─ 굵게
#### H4 ─ 일반 본문의 볼드체와 동일하여 효용↓
**H4 일반 본문의 볼드체**
##### H5 ─ 본문보다 작음
###### H6 ─ 엷은 회색


## 2. Text formatting

- 굵게 ` **bold** ` → **bold**
- 기울임 ` *italic* ` → *italic*
- 취소선 ` ~~deprecated~~ ` → ~~deprecated~~
- 인라인 코드 `` `code` `` 혹은 ` ``backtick이 들어간 code`` ` → `code`


## 3. List
1. 불렛: `- `, `* `  
    ● → ○ → ■ → ■ → ··· (3번째부터 기호반복)
2. 순서: `1. `  
　1. → ⅰ. → a. → a. → ··· (3번째부터 기호반복)
3. 체크: `- [ ] `, `- [x] ` (GFM 추가 기능⭐)
- 세 종류의 리스트를 섞어쓸 수 있음
- 들여쓰기: `스페이스 4칸`이 안정적
- 3번째 들여쓰기부터 기호 반복

### 1) Bullet list (Unordered list)

```md
- 첫번째 item Lv.1
  - nested item Lv.2
    - nested item Lv.3
      - nested item Lv.4
* - 대신 *으로 해도 됨
```

▶ 결과
- 첫번째 item Lv.1
  - nested item Lv.2
    - nested item Lv.3
      - nested item Lv.4
* - 대신 *으로 해도 됨


### 2) Numbered list (Ordered list)

```md
1. 첫번째 item Lv.1
    1. nested item Lv.2
        1. nested item Lv.3
            1. nested item Lv.4
1. 두번째 item Lv.1
```

▶ 결과
1. 첫번째 item Lv.1
    1. nested item Lv.2
        1. nested item Lv.3
            1. nested item Lv.4
1. 두번째 item Lv.1


### 3) Task list (GFM 추가 기능 ⭐)
```md
- 6월 13일
  - [x] 마크다운 공부하기
    - [ ] Markdown Cheat Sheet 제작
  - [ ] 대학물리(1) 시험공부
    - [ ] 4~8p
    - [ ] 외우기
```

- 6월 13일
  - [x] 마크다운 공부하기
    - [ ] Markdown Cheat Sheet 제작
  - [ ] 대학물리(1) 시험공부
    - [ ] 4~8p
    - [ ] 외우기

## 4. Code block (핵심 중 핵심)
언어별로 syntax highlighting(문법 하이라이트) 지원  
(예) `md` `bash` `yaml` `python` `json` `javascript` `html` `sql` ···

``````
```python
print("hello")
```
``````

▶ 결과
```python
print("hello")
```


## 5. Quote, Callout
- 여러 줄에 걸쳐서 할꺼면, 끝에 `스페이스 2칸` 후 개행

### 1) Blockquote(기본 기능)

```
> 인용--
> 합니--
> 다.
```

▶ 결과
> 인용  
> 합니  
> 다.

### 2) Callout(GFM 추가 기능⭐)

```
> [!NOTE]
> (파랑) 단순메모, 개념정리, 참고사항, 배경설명 등 information

> [!TIP]
> (초록) 배운 팁, SHORTCUT

> [!IMPORTANT]
> (보라) 핵심개념 Key point

> [!WARNING]
> (노랑) 주의사항, 헷갈리거나 실수했던 것 (~하면, ~한 이슈가 생긴다)

> [!CAUTION]
> (빨강) 절대 하지말 것 serious warning
```

> [!NOTE]
> (파랑) 단순메모, 개념정리, 참고사항, 배경설명 등 information

> [!TIP]
> (초록) 배운 팁, SHORTCUT

> [!IMPORTANT]
> (보라) 핵심개념 Key point

> [!WARNING]
> (노랑) 주의사항, 헷갈리거나 실수했던 것 (~하면, ~한 이슈가 생긴다)

> [!CAUTION]
> (빨강) 절대 하지말 것 serious warning

## 6. 링크 Link, 이미지 Image, 뱃지 Badge

### 1) 링크 Link
- 링크: `[text](URL)`
- 링크가 너무 길다면 reference-style link: 링크를 변수처럼 관리  
  `[text][변수명]`  
  `[변수명]: 링크주소`

```
[우리집(ctrl+클릭)](https://github.com/learner-nosilv/nosilv.github.io)
```
▶ 결과: [우리집(ctrl+클릭)](https://github.com/learner-nosilv/nosilv.github.io)


```
[우리집(ctrl+클릭)][nosilv-github]

[nosilv-github](https://github.com/learner-nosilv/nosilv.github.io)
```

▶ 결과: [우리집(ctrl+클릭)][nosilv-github]

[nosilv-github]: https://github.com/learner-nosilv/nosilv.github.io


### 2) 이미지 Image, 뱃지 Badge
- 이미지, 뱃지: `![alt, badge text](Image, Badge URL)`

```
![예시사진-강미나](https://i.namu.wiki/i/IeZUIIr_Vft-Fkn_p0plEn8PkUQy7CQmhl2TASbsrfJ8en6ToCZhxBd7nb95uNDYEslqlJgQIrNAaMz2BItSNiHmbx2pKUPY1f1lb4qijE5bpKvXoQLJHzrjztzsdSVP8-zjgV4awdkPMaTqxi6jJA.webp)
```

▶ 결과:

![예시사진-강미나](https://i.namu.wiki/i/IeZUIIr_Vft-Fkn_p0plEn8PkUQy7CQmhl2TASbsrfJ8en6ToCZhxBd7nb95uNDYEslqlJgQIrNAaMz2BItSNiHmbx2pKUPY1f1lb4qijE5bpKvXoQLJHzrjztzsdSVP8-zjgV4awdkPMaTqxi6jJA.webp)


- 뱃지 URL 형식: `https://img.shields.io/badge/왼쪽칸-오른쪽칸-색깔?logo=로고이름&logoColor=로고색`
- 뱃지 URL 빌더: https://shields.io/badges/static-badge
- 로고이름, 색 참고 사이트: https://simpleicons.org/

예시  
`![Python](https://img.shields.io/badge/Python-3.12-blue)`  
→ ![Python](https://img.shields.io/badge/Python-3.12-blue)

`![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)`  
→ ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

`![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)`  
→ ![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)

`![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)`  
→ ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

`![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)`  
→ ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

`![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)`  
→ ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

`![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)`  
→ ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

`![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)`  
→ ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)

`![VSCode](https://img.shields.io/badge/VS_Code-007ACC?logo=visualstudiocode&logoColor=white)`  
→ ![VSCode](https://img.shields.io/badge/VS_Code-007ACC?logo=visualstudiocode&logoColor=white)

`![License](https://img.shields.io/badge/License-MIT-green)`  
→ ![License](https://img.shields.io/badge/License-MIT-green)

`![Deployed](https://img.shields.io/badge/Deployed-Live-success)`  
→ ![Deployed](https://img.shields.io/badge/Deployed-Live-success)

`![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-black)`  
→ ![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-black)

`![Version](https://img.shields.io/badge/version-1.0.0-blue)`  
→ ![Version](https://img.shields.io/badge/version-1.0.0-blue)


### 3) 링크가 있는 이미지 Image, 뱃지 Badge
- 링크: `[text](URL)`
- 링크가 있는 이미지나 뱃지:
    1. 링크 문법: [`text 대신 이미지`](이미지 누르면 뜰 링크)
    2. text 대신 이미지: [`![alt, badge text](이미지 링크)`](이미지 누르면 뜰 링크)
    3. 변수로 가독성 챙기기: [`![alt, badge text][이미지 링크 변수]`][누르면 뜰 링크 변수]

```
[![alt니까 메모처럼 활용][이미지 링크 변수]][이미지를 누르면 뜰 링크 변수]

[![CI][badge-ci]][ci]
[![Codacy Badge][badge-codacy]][codacy]
[![GitHub license][badge-license]][license]
[![Gem Version][badge-gem]][gem]
[![Open in Dev Containers][badge-open-container]][open-container]
```  

▶ 결과:
[![CI][badge-ci]][ci]
[![Codacy Badge][badge-codacy]][codacy]
[![GitHub license][badge-license]][license]
[![Gem Version][badge-gem]][gem]
[![Open in Dev Containers][badge-open-container]][open-container]

[badge-ci]: https://img.shields.io/github/actions/workflow/status/cotes2020/jekyll-theme-chirpy/ci.yml?logo=github
[badge-codacy]: https://img.shields.io/codacy/grade/4e556876a3c54d5e8f2d2857c4f43894?logo=codacy
[badge-license]: https://img.shields.io/github/license/cotes2020/jekyll-theme-chirpy?color=goldenrod
[badge-gem]: https://img.shields.io/gem/v/jekyll-theme-chirpy?&logo=RubyGems&logoColor=ghostwhite&label=gem&color=orange
[badge-open-container]: https://img.shields.io/badge/Dev_Containers-Open-deepskyblue?logo=linuxcontainers
[ci]: https://github.com/cotes2020/jekyll-theme-chirpy/actions/workflows/ci.yml?query=event%3Apush+branch%3Amaster
[codacy]: https://app.codacy.com/gh/cotes2020/jekyll-theme-chirpy/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade
[license]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE
[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[open-container]: https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/cotes2020/jekyll-theme-chirpy




## 7. 표 Table (GFM 추가 기능⭐)
표 정렬 규칙
- `|:----|`   left
- `|:---:|`   center
- `|----:|`   right

```
| 카테고리1 | 카테고리 2 | 카테고리 3 |
|---|:---:|---:|
|짜장면|♥♥♥♡♡|간짜장은 함춘원|
|짬뽕|♥♥♥♥♥|짬뽕은 뽕사부|
```

▶ 결과:
| 카테고리1 | 카테고리 2 | 카테고리 3 |
|---|:---:|---:|
|짜장면|♥♥♥♡♡|간짜장은 함춘원|
|짬뽕|♥♥♥♥♥|짬뽕은 뽕사부|


## 8. 구분선 Horizontal line
구분선: `---`

---


## 9. 접히는 블록 Collapsible section (GFM 추가 기능⭐)

```
<details>
<summary>나를 눌러보세요</summary>

짜잔

</details>
```

<details>
<summary>나를 눌러보세요</summary>

짜잔

</details>

## 10. Emoji
`:dart:`       🎯 goal  
`:bulb:`      💡 idea  
`:warning:`    ⚠️ warning  
`:no_entry:`   ⛔ do not  
`:boom: `      💥 bug/problem  
`:rotating_light:` 🚨 critical  
`:bug:`        🐛 debugging  
`:fire:`       🔥 hot issue  
`:white_check_mark:` ✅ done  
`:heavy_check_mark:` ✔️ completed  
`:file_folder:` 📁 folder  
`:lock:`        🔒 security  
`:key:`         🔑 authentication  

## 11. HTML 혼용 가능 ⭐

```html
<div align="center">
  정말 가운데 정렬을 하고 싶다면!
</div>
```

<div align="center">
  정말 가운데 정렬을 하고 싶다면!
</div>

- 개행은 `<br>`
- 공백은 `&nbsp;`


## 12. 각주 Footnote
```
ABC[^1]가나다123

[^1]: ABC: 영어입니다.
```

▶ 결과: 
ABC[^1]가나다123

[^1]: ABC: 영어입니다.
