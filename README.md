# 소프트웨어공학 18조 - 과제1 Requirement Capturing

> 온라인 설문조사 플랫폼 Requirement Capturing 프로젝트

## 📋 프로젝트 개요

회원들이 다양한 주제에 대한 의견과 응답을 수집하고 분석할 수 있는 **온라인 설문조사 플랫폼**의 요구사항 분석 단계를 수행합니다.

### 산출물
1. Requirement List (functional requirement)
2. UI 화면 (Figma)
3. Use Case Diagram
4. Use Case Descriptions (step by step)

---

## 🌿 브랜치 전략

- `main` 브랜치에 **직접 push 금지**
- 각자 브랜치를 파서 작업 후 **Pull Request**로 merge
- merge 완료된 브랜치는 삭제

### 브랜치 네이밍 규칙

```
<이름>/<타입>
```

- `junseo/docs` — 문서 작업
- `junseo/ui` — UI 화면 작업
- `junseo/diagram` — Use Case Diagram 작업
- `junseo/fix` — 오류 수정

> 같은 작업을 여러 명이 진행해 비교해야 하는 경우 이름이 앞에 들어가 있어 충돌 없이 병렬 작업이 가능합니다.

---

## 💬 커밋 메시지 규칙

> ⚠️ `log_output.txt`로 제출되어 채점자에게 노출되므로 깔끔하게 작성

### 형식

```
<타입>: <작업 내용>
```

### 타입 종류

- `docs` — 문서 작성/수정 (requirement, description 등)
- `ui` — UI 화면 추가/수정
- `diagram` — Use Case Diagram 작업
- `fix` — 오류 수정
- `chore` — 기타 잡무

### 예시

```
docs: 회원가입 use case description 작성
ui: 로그인 화면 Figma 캡처 추가
diagram: 관리자 actor 부분 통합
fix: extend 화살표 방향 수정
```