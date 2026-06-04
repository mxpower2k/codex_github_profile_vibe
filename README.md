# 김한수 Developer Portfolio

GitHub Pages에 바로 배포할 수 있는 정적 1페이지 개발자 포트폴리오입니다.

## 수정할 항목

- `YOUR_EMAIL@example.com`
- `YOUR_GITHUB_URL`
- `YOUR_LINKEDIN_OR_BLOG_URL`
- `YOUR_PROJECT_NAME`
- `YOUR_PROJECT_URL`
- 프로젝트 설명, 기술 스택, 경력/활동 내용

## 로컬에서 확인하기

브라우저에서 `index.html`을 열면 바로 확인할 수 있습니다.

## GitHub Pages 배포

1. 이 파일들을 GitHub 저장소의 `main` 브랜치 루트에 올립니다.
2. GitHub 저장소에서 `Settings`로 이동합니다.
3. `Pages` 메뉴를 엽니다.
4. `Build and deployment`의 `Source`를 `GitHub Actions`로 선택합니다.
5. `main` 브랜치에 push하면 `.github/workflows/deploy-pages.yml`이 실행됩니다.
6. 배포가 끝나면 Actions 로그의 `github-pages` URL에서 사이트를 확인합니다.

## 파일 구조

```text
.
├── index.html
├── styles.css
├── script.js
├── README.md
├── .nojekyll
├── assets/
│   └── hero-workspace.png
└── .github/
    └── workflows/
        └── deploy-pages.yml
```
