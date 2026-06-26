> [!WARNING]
> 이 문서는 공식 번역이 아닌, 스스로 작성한 한국어 번역본입니다.  
> **원본**: [Chirpy Jekyll Theme README.md][chirpy-readme]  
> **버전**: 2026년 5월 15일 커밋 기준 ([커밋 히스토리][chirpy-readme-commit-history])
> 
> This is an unofficial, self-translated Korean version.  
> **Original**: [README.md][chirpy-readme] of [Chirpy Jekyll Theme][chirpy]  
> **Version**: Based on the commit from May 15, 2026 ([commit history][chirpy-readme-commit-history])  

<!-- markdownlint-disable-next-line -->
<div align="center">

  <!-- markdownlint-disable-next-line -->
  # Chirpy Jekyll Theme

  기술 문서 작성(Technical Writing)[^1]을 위한, 최소한의 디자인(minimal), 반응형(responsive)[^2], 그리고 다양한 기능(feature-rich)을 갖춘 Jekyll 테마[^3]

[^1]: theme for technical writing / 감상, 에세이보다는 정보를 명확하게 전달하는 것에 목적을 두는 글쓰기에 어울리는 테마. _(예: 개발 인사이트, 학습기록, 가이드, 기술 리뷰 등)_

[^2]: **반응형 디자인(Responsive Design)**: 화면 크기에 **반응**하여 웹 페이지의 형태가 자동으로 조정되도록 하는 디자인 기법. 제대로 구현하면 다양한 환경에서 최적의 사용자 경험을 제공함. _(예) 가로가 1920px면 모든 요소 다 보이게 배치하고, 600px면 글만 보이게 하고 나머지는 다 접어두자_ 　[정보통신용어사전](https://terms.tta.or.kr/dictionary/dictionaryView.do?word_seq=054426-12)

[^3]: **Jekyll (지킬, 지킬박사 이름에서 따옴)**: 정적 사이트 생성기　[내가 쓴 글:Markdown] → `변환기:Jekyll` → [정적웹사이트파일:HTML/CSS/JS/···] <br>
-파일의 행방: [GitHub에 저장] → [GitHub Pages가 배포] → [인터넷 브라우저가 받아서 그 기기에서 사이트 구현]<br>
-의의: Markdown파일은 원래 브라우저가 읽을 수 없음 → Jekyll이 브라우저가 읽을 수 있는 형태(HTML,···)로 바꿔줌<br>
① 내가 **Markdown파일**을 **Jekyll**에게 먹이면<br>
② **Jekyll**은 이 글 내용이 반영된 그리고 `내가 설정한 사이트 테마`가 적용된 HTML, CSS, JS 등의 **정적 웹사이트 파일 세트**를 만들어줌<br>
③ 나는 이 파일 세트를 **GitHub**에 올림<br>
④ 어느 날, 누군가 인터넷 브라우저에 내 사이트 URL을 입력하면<br>
⑤ 그 브라우저가 GitHub Pages에게 내 사이트 파일을 요청함<br>
⑥ 상시대기하던 정적 사이트 전용 호스팅 서비스 **GitHub Pages**는 그 브라우저에게 내 사이트 파일을 전달함<br>
⑦ 브라우저는 내 사이트 파일을 읽고, 화면에 사이트를 실제 구현함




  [![CI][badge-ci]][ci]&nbsp;
  [![Codacy Badge][badge-codacy]][codacy]&nbsp;
  [![GitHub license][badge-license]][license]&nbsp;
  [![Gem Version][badge-gem]][gem]&nbsp;
  [![Open in Dev Containers][badge-open-container]][open-container]

  [**실제 작동중인 데모 사이트**(ctrl+클릭) →][demo]

  [![Devices Mockup](https://chirpy-img.netlify.app/commons/devices-mockup.png)][demo]

</div>

## 기능(Features)

- **디자인 & 사용자 경험(UX)**
  1. 반응형 레이아웃
  2. 다크/라이트모드 지원 & 다크모드용 이미지를 따로 지정 가능
  3. UI언어 현지화 지원(한국어 메뉴도 가능)
- **콘텐츠 관리기능**
  1. 포스트 상단 고정 기능
  2. 계층형 카테고리 기능
  3. 많이 쓰는 태그 자동 표시 기능
  4. TOC(목차) 자동 생성 기능
  5. 포스트 수정 시 마지막 수정 날짜 자동 표시 기능
- **다양한 문서 표현 지원**
  1. 코드 하이라이팅` ``` `
  2. LaTeX 수식 문법`$$`
  3. Mermaid diagrams & flowcharts ` ```mermaid `
  4. 미디어 삽입(Gif, Youtube 등)
- **상호작용 기능**
  1. 블로그 내부 검색 기능
  2. 댓글 시스템
  3. Atom feeds(블로그 새 글 알림 시스템)
- **시스템 & 최적화**
  1. PWA[^4] 지원
  2. 방문자 분석 기능
  3. 강화된 SEO(검색엔진 최적화)

[^4]: **Progressive Web App(PWA)** : 웹사이트를 앱처럼 보이게 하는 기능으로 ① 홈 화면에 앱 아이콘 생성 기능, ② 캐시 사용으로 방문한 페이지는 더 빨리 열리는 기능 등을 지원 

## 문서(Documentation)

프로젝트 사용법, 개발방법, 업데이트 방법을 배우고 싶다면 [Wiki][wiki] 를 참조하세요.

## 기여방법 (Contributing)

_pull requests_, _issues_, and _discussions_ 같은 기여는 오픈소스 커뮤니티를 누군가 배우기에, 영감을 얻기에, 창조를 하기에 더 놀라운 공간으로 만듭니다. 당신의 모든 기여는 대단히 감사받을 것입니다. 자세히 알고 싶다면 우리의 [Contributing Guidelines][contribute-guide] 을 참조하세요. → 프로젝트 개선에 참여해주세요 :)

## 기여자 (Credits)

이 프로젝트는 [Jekyll][jekyllrb] 생태계를 기반으로 만들어졌으며, 여러 [우수한 오픈소스 라이브러리들][lib] 이 조합되어있습니다. 아바타와 파비콘은 [ClipartMAX][clipartmax]에서 가져왔습니다.

더 나아가, 이 프로젝트의 발전에 기여한 모든 개발자들에게 감사드립니다.

[![all-contributors][contributors-avatar]][contributors]

## License

이 프로젝트는 [MIT License][license] 를 따릅니다.

[chirpy]: https://github.com/cotes2020/jekyll-theme-chirpy
[chirpy-readme]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/README.md
[chirpy-readme-commit-history]: https://github.com/cotes2020/jekyll-theme-chirpy/commits/master/README.md
[badge-ci]: https://img.shields.io/github/actions/workflow/status/cotes2020/jekyll-theme-chirpy/ci.yml?logo=github
[badge-codacy]: https://img.shields.io/codacy/grade/4e556876a3c54d5e8f2d2857c4f43894?logo=codacy
[badge-license]: https://img.shields.io/github/license/cotes2020/jekyll-theme-chirpy?color=goldenrod
[badge-gem]: https://img.shields.io/gem/v/jekyll-theme-chirpy?&logo=RubyGems&logoColor=ghostwhite&label=gem&color=orange
[badge-open-container]: https://img.shields.io/badge/Dev_Containers-Open-deepskyblue?logo=linuxcontainers
[gem]: https://rubygems.org/gems/jekyll-theme-chirpy
[ci]: https://github.com/cotes2020/jekyll-theme-chirpy/actions/workflows/ci.yml?query=event%3Apush+branch%3Amaster
[codacy]: https://app.codacy.com/gh/cotes2020/jekyll-theme-chirpy/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade
[license]: https://github.com/learner-nosilv/nosilv.github.io/blob/main/LICENSE

[open-container]: https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/cotes2020/jekyll-theme-chirpy
[jekyllrb]: https://jekyllrb.com/
[clipartmax]: https://www.clipartmax.com/middle/m2i8b1m2K9Z5m2K9_ant-clipart-childrens-ant-cute/
[demo]: https://cotes2020.github.io/chirpy-demo/
[wiki]: https://github.com/cotes2020/jekyll-theme-chirpy/wiki
[contribute-guide]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/docs/CONTRIBUTING.md
[contributors]: https://github.com/cotes2020/jekyll-theme-chirpy/graphs/contributors
[contributors-avatar]: https://contrib.rocks/image?repo=cotes2020/jekyll-theme-chirpy&columns=16&max=112
[lib]: https://github.com/cotes2020/chirpy-static-assets
