# ja01001.github.io

[Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) 테마를 사용한 기술 블로그입니다.

## 글 쓰기

`_posts/YYYY-MM-DD-제목.md` 파일을 만들고 아래 머리말을 붙입니다.

```yaml
---
title: 글 제목
date: 2026-11-05 10:00:00 +0900
categories: [대분류, 소분류]
tags: [태그1, 태그2]
---
```

## 로컬 실행

```bash
bundle install
bundle exec jekyll serve
```

## 배포

`main` 브랜치에 푸시하면 GitHub Actions(`.github/workflows/pages-deploy.yml`)가 빌드 후 GitHub Pages에 배포합니다.
저장소 **Settings → Pages → Source**는 **GitHub Actions**로 설정해야 합니다.
