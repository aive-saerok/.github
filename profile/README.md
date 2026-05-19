# AI-ve — 새록 (Saerok)

> 자연이 싹트는 순간, 당신 곁에서.

공공 생태 데이터와 AI 에이전트를 연결해 **위치·연령 맞춤형 생태 교육**을 제공하는 서비스.
검색하지 않아도, 예약하지 않아도 — 지금 서 있는 그 자리에서 스스로 찾아옵니다.

생태·자연도 1등급 구역에 발을 들이는 순간, 5세 아이부터 시니어까지 각자의 눈높이에 맞는 생태 해설이 자동으로 시작됩니다.

---

## 레포지토리

| 레포 | 설명 |
|------|------|
| [Saerok-FE](https://github.com/aive-saerok/Saerok-FE) | React Native (Expo) 클라이언트 |
| [Saerok-BE](https://github.com/aive-saerok/Saerok-BE) | Spring Boot 백엔드 |
| [Saerok-AI](https://github.com/aive-saerok/Saerok-AI) | LangGraph + FastAPI AI 에이전트 |

---

## 브랜치 전략

- `main` — 배포 가능한 상태만 유지. 직접 push 금지
- 작업은 Jira 이슈 기반 브랜치에서 진행 (`AIVE-{번호}-{설명}`)
- 완료 후 PR → 리뷰 1명 이상 승인 후 머지

---

## 커밋 컨벤션

```
<type>: <제목>
```

| type | 설명 |
|------|------|
| `feat` | 기능 개발 |
| `fix` | 버그 수정 |
| `refactor` | 리팩토링 |
| `chore` | 자잘한 수정·설정 변경 |

---

## 팀

**AI-ve** · KT AIVLE School 6기 · 접수번호 120262211
