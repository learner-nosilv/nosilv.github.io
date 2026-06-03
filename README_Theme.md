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

  이 테마는 깔끔하고 **반응형**[^1]이면서 다양한 기능이 들어있는 **Jekyll 테마**[^2]로, 기술 블로그[^3]에 잘 어울립니다.

[^1]: **반응형 디자인(Responsive Design)**: 화면 크기에 **반응**하여 웹 페이지의 형태가 자동으로 조정되도록 하는 디자인 기법. 제대로 구현하면 다양한 환경에서 최적의 사용자 경험을 제공함. _(예) 가로가 1920px면 모든 요소 다 보이게 배치하고, 600px면 글만 보이게 하고 나머지는 다 접어두자_ 　[정보통신용어사전](https://terms.tta.or.kr/dictionary/dictionaryView.do?word_seq=054426-12)

[^2]: **Jekyll (지킬, 지킬박사 이름에서 따옴)**: 정적 사이트 생성기　[내가 쓴 글:Markdown] → `변환기:Jekyll` → [정적웹사이트파일:HTML/CSS/JS/···] <br>
-파일의 행방: [GitHub에 저장] → [GitHub Pages가 배포] → [인터넷 브라우저가 받아서 그 기기에서 사이트 구현]<br>
-의의: Markdown파일은 원래 브라우저가 읽을 수 없음 → Jekyll이 브라우저가 읽을 수 있는 형태(HTML,···)로 바꿔줌<br>
① 내가 **Markdown파일**을 **Jekyll**에게 먹이면<br>
② **Jekyll**은 이 글 내용이 반영된 그리고 `내가 설정한 사이트 테마`가 적용된 HTML, CSS, JS 등의 **정적 웹사이트 파일 세트**를 만들어줌<br>
③ 나는 이 파일 세트를 **GitHub**에 올림<br>
④ 어느 날, 누군가 인터넷 브라우저에 내 사이트 URL을 입력하면<br>
⑤ 그 브라우저가 GitHub Pages에게 내 사이트 파일을 요청함<br>
⑥ 상시대기하던 정적 사이트 전용 호스팅 서비스 **GitHub Pages**는 그 브라우저에게 내 사이트 파일을 전달함<br>
⑦ 브라우저는 내 사이트 파일을 읽고, 화면에 사이트를 실제 구현함

[^3]: theme for technical writing / 감상, 에세이보다는 정보를 명확하게 전달하는 것에 목적을 두는 글쓰기에 어울리는 테마. _(예: 개발 인사이트, 학습기록, 가이드, 기술 리뷰 등)_


  [![CI][badge-ci]][ci]&nbsp;
  [![Codacy Badge][badge-codacy]][codacy]&nbsp;
  [![GitHub license][badge-license]][license]&nbsp;
  [![Gem Version][badge-gem]][gem]&nbsp;
  [![Open in Dev Containers][badge-open-container]][open-container]

  [**실제 작동중인 데모 사이트**(ctrl+클릭) →][demo]

  [![Devices Mockup](https://chirpy-img.netlify.app/commons/devices-mockup.png)][demo]

</div>

## Features

- **Design & UX** - Responsive layout, Dark/Light modes, Localized UI language,
  and Dark mode images.
- **Content Management** - Pinned posts, Hierarchical categories, Trending tags,
  Auto-generated Table of Contents, and Last modified dates.
- **Rich Text Support** - Syntax highlighting, Mathematical expressions, Mermaid
  diagrams & flowcharts, and Embedded media.
- **Interactivity & Outreach** - Built-in search, Multiple comment systems, and
  Atom feeds.
- **System & Optimization** - PWA support, integrated Web analytics, and
  advanced SEO performance.

## Documentation

To learn how to use, develop, and upgrade the project, please refer to the
[Wiki][wiki].

## Contributing

Contributions (_pull requests_, _issues_, and _discussions_) are what make the
open-source community such an amazing place to learn, inspire, and create. Any
contributions you make are greatly appreciated.
For details, please refer to our [Contributing Guidelines][contribute-guide].

## Credits

This project is built on the [Jekyll][jekyllrb] ecosystem and integrates a
collection of [excellent libraries][lib]. Its avatar and favicon are sourced
from [ClipartMAX][clipartmax].

Furthermore, thanks to everyone who contributed to the development of this project!

[![all-contributors][contributors-avatar]][contributors]

## License

This project is licensed under the [MIT License][license].

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
[license]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/LICENSE
[open-container]: https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/cotes2020/jekyll-theme-chirpy
[jekyllrb]: https://jekyllrb.com/
[clipartmax]: https://www.clipartmax.com/middle/m2i8b1m2K9Z5m2K9_ant-clipart-childrens-ant-cute/
[demo]: https://cotes2020.github.io/chirpy-demo/
[wiki]: https://github.com/cotes2020/jekyll-theme-chirpy/wiki
[contribute-guide]: https://github.com/cotes2020/jekyll-theme-chirpy/blob/master/docs/CONTRIBUTING.md
[contributors]: https://github.com/cotes2020/jekyll-theme-chirpy/graphs/contributors
[contributors-avatar]: https://contrib.rocks/image?repo=cotes2020/jekyll-theme-chirpy&columns=16&max=112
[lib]: https://github.com/cotes2020/chirpy-static-assets
