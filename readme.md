# Windows Version
## 설치
https://rubyinstaller.org/

## 참고
http://jekyllrb-ko.github.io/docs/windows/

## Quick Start
1. RubyInstaller 다운로드 페이지에서 Ruby+Devkit 버전을 다운로드 받아 설치
2. 시작 메뉴에서 명령 프롬프트 창을 열고, 환경변수 PATH 를 적절히 설정하세요. Jekyll 과 Bundler 를 설치합니다: 
```bash
gem install jekyll bundler
```
3. Jekyll 이 올바르게 설치되었는지 확인합니다: 
```bash
jekyll -v
```
4. 기본테마 블로그 생성
```bash
jekyll new jekyll-website
```

## 루비 설치
```bash
   1 - MSYS2 base installation
   2 - MSYS2 system update (optional)
   3 - MSYS2 and MINGW development toolchain

Which components shall be installed? If unsure press ENTER [1,2,3] 1
```

## RubyInstaller - windows
윈도우즈 기반으로 루비 언어와 실행 환경, 중요 문서 등을 포함하고 있습니다. 여기서는 RubyInstaller-2.4 또는 그 이상의 버전을 다루고 있으며, 예전 버전은 따로 Devkit 설치를 필요로 합니다.
설치할때 옵션 체크 조심

## 마지막

실행시켜보기
```bash
// 설치된 ruby 버전 및 패스 설정 ok확인
ruby -v
// jekyll 실행
jekyll new [만들폴더이름]
// 미리보기 서버 빌드
bundle exec jekyll serve
// 테썹
http://localhost:4000
```