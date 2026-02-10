# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 개요

개발자 웹 이력서 사이트. HTML, CSS, JavaScript, TailwindCSS를 사용한 정적 싱글 페이지 웹 프로젝트.

## 기술 스택

- HTML5, CSS3, JavaScript (ES6+)
- TailwindCSS (CDN 사용)
- 별도 빌드 도구 없음 — 브라우저에서 index.html을 직접 열어 확인

## 프로젝트 구조

```
/
├── index.html          # 메인 이력서 페이지 (싱글 페이지)
├── css/
│   └── style.css       # TailwindCSS 외 커스텀 스타일
├── js/
│   └── main.js         # 스크롤 애니메이션, 네비게이션 등 인터랙션
└── assets/
    └── images/         # 프로필 사진, 프로젝트 이미지
```

## 개발 방식

- 싱글 페이지 구성: 헤더, 자기소개, 기술 스택, 경력, 프로젝트, 학력, 푸터
- 모바일 반응형 필수 적용
- 배포: GitHub Pages

## 언어 규칙

- 기본 응답 언어: 한국어
- 코드 주석: 한국어
- 커밋 메시지: 한국어
- 문서화: 한국어
- 변수명/함수명: 영어 (코드 표준 준수)
