# Nosilv blog memo
블로그를 만들고 있는 **과거의 내가  
미래의 나를 구하기 위해** 작성하는 메모장

- 내 블로그 구조
- 내가 사용한 리눅스 문법 정리
- 내가 사용할 마크다운 문법 정리

## Table of Contents
- [Nosilv blog memo](#nosilv-blog-memo)
  - [Table of Contents](#table-of-contents)
  - [Blog Structure](#blog-structure)
  - [Linux memo](#linux-memo)


## Blog Structure
Jekyll 엔진 위에 Chirpy 테마를 씌운 GitHub 블로그

- `Jekyll` : **Markdown →  Static site**  
**A static site genarator** that transforms Markdown files into web pages.

사용자가 Markdown으로 포스트를 작성
브라우저가 Markdown을 그대로 읽을 수 없기 때문에, 읽을 수 있는 형태인 HTML 웹페이지(글, 목차, 카테고리)로 변환해주는 Jekyll이 중간에 필요하다.
![From Markdown to a Live Website: How Jekyll and GitHub Pages Work](<How Jekyll and GitHub Pages Work.png>)


**Jekyll (지킬, 지킬박사 이름에서 따옴)**: 정적 사이트 생성기　[내가 쓴 글:Markdown] → `변환기:Jekyll` → [정적웹사이트파일:HTML/CSS/JS/···] <br>
-파일의 행방: [GitHub에 저장] → [GitHub Pages가 배포] → [인터넷 브라우저가 받아서 그 기기에서 사이트 구현]<br>
-의의: Markdown파일은 원래 브라우저가 읽을 수 없음 → Jekyll이 브라우저가 읽을 수 있는 형태(HTML,···)로 바꿔줌<br>
① 내가 **Markdown파일**을 **Jekyll**에게 먹이면<br>
② **Jekyll**은 이 글 내용이 반영된 그리고 `내가 설정한 사이트 테마`가 적용된 HTML, CSS, JS 등의 **정적 웹사이트 파일 세트**를 만들어줌<br>
③ 나는 이 파일 세트를 **GitHub**에 올림<br>
④ 어느 날, 누군가 인터넷 브라우저에 내 사이트 URL을 입력하면<br>
⑤ 그 브라우저가 GitHub Pages에게 내 사이트 파일을 요청함<br>
⑥ 상시대기하던 정적 사이트 전용 호스팅 서비스 **GitHub Pages**는 그 브라우저에게 내 사이트 파일을 전달함<br>
⑦ 브라우저는 내 사이트 파일을 읽고, 화면에 사이트를 실제 구현함

- ``



```
Markdown.md
```


## Linux memo
