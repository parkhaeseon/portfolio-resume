# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 프로젝트 개요
이 저장소는 Claude Code 학습용 연습 프로젝트입니다. Git 워크플로우와 협업 방식을 연습하는 목적으로 사용됩니다.

## 언어 및 커뮤니케이션 규칙

### 기본 응답 언어
- **Claude의 모든 응답**: 한국어로 작성
- **사용자와의 모든 커뮤니케이션**: 한국어

### 코드 및 문서
- **코드 주석**: 한국어로 작성
- **커밋 메시지**: 한국어로 작성
- **문서화 (README, CLAUDE.md 등)**: 한국어로 작성
- **변수명/함수명**: 영어로 작성 (코드 표준 준수)

## Git 워크플로우

### 브랜치 구조
- `master`: 프로덕션 브랜치 (안정화된 코드)
- `develop`: 개발 브랜치 (통합 지점)
- `hotfix/*`: 긴급 버그 수정 브랜치 (예: `hotfix/결제-오류`)

### 머지 절차
- 핫픽스 작업: `hotfix/*` → `master` 로 직접 머지
- 일반 개발: `develop` 에서 작업 후 `develop` → `master` 로 머지

## 주요 커밋 메시지 컨벤션
- 버그 수정: `버그 수정: [설명]`
- 기능 추가: `기능 추가: [설명]`
- 리팩토링: `리팩토링: [설명]`
- 긴급 패치: `긴급 패치: [설명]`
