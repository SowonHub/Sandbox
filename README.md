# 🧪 Sandbox

> Sowon’s reusable GitHub template kit  
> “구조는 단단하게, 시작은 가볍게.”

---

## 🌱 About

Sandbox는 회사형 Git workflow를 연습하고 재사용하기 위한  
**Template Repository**입니다.

새 프로젝트를 시작할 때 이 레포를 복제하여  
동일한 브랜치 전략, PR 흐름, 템플릿 구조로 시작합니다.

---

## 🏗 Branch Strategy
feature/* → dev → main

### 🔹 main
- Production branch (protected)
- Direct push ❌
- PR only
- Squash merge
- Linear history
- Force push blocked

### 🔹 dev (default)
- Integration branch
- PR required
- Linear history
- Force push blocked

### 🔹 feature/*
- 작업 브랜치
- 네이밍 규칙: `type/issueNumber-short-slug`
- 예시:
  - `feat/23-login-ui`
  - `fix/31-submit-error`
  - `refactor/39-clean-routing`

---

## 🔁 Workflow

1. Issue 생성
2. 브랜치 생성  3. PR → `dev`
4. 안정화 후 PR → `main`

---

## 🧾 Commit Convention

- feat: 새로운 기능
- fix: 버그 수정
- refactor: 구조 개선
- style: UI/포맷 수정
- docs: 문서 수정
- chore: 설정/환경 정리

예시:
- feat: add wishlist toggle (#39)
- fix: prevent unintended form submit (#41)
- refactor: simplify routing structure (#52)

---

## 📂 Templates Included

- PR Template (`.github/pull_request_template.md`)
- Issue Templates (`.github/ISSUE_TEMPLATE/`)
- Default Labels
- Protected Branch Rules

---

## 💛 Philosophy

> 완벽하게 시작하려고 하지 않는다.  
> 구조만 단단히 만들어두고,  
> 나머지는 실행하면서 채운다.

---

## 🚀 How to Use

1. Click **Use this template**
2. Name your new repository
3. Start building ✨

---

Made by Sowon 🐰
