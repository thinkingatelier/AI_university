# Agent University — UBERMENSCH Protocol v4.0

AI 에이전트를 "기계를 만드는 기계"로 훈련시키는 Claude Code 스킬팩입니다.

> "한 번 하는 일은 기록하고, 두 번 하는 일은 문서화하고, 세 번 하는 일은 자동화한다."

## 이게 뭔가요?

이 스킬팩을 설치하면, Claude가 자동으로 **7단계 훈련 코스**를 따라 에이전트를 훈련시킵니다.

- **STAGE 1** (기본 훈련 7레슨): 고통 발견 → SOP 작성 → 제안서 → 프로토타입 → MVP → 운영
- **STAGE 2** (전공 실습 6모듈): YouTube, Blog, Seller, Business, Dev, Remotion
- **STAGE 3** (졸업 프로젝트): 실데이터 기반 수익화 증명

## 설치 방법

### 방법 1: 직접 복사

```bash
# 저장소 클론
git clone https://github.com/thinkingatelier/AI_university.git

# 스킬팩을 프로젝트의 .claude/skills/ 폴더에 복사
cp -r AI_university/ YOUR_PROJECT/.claude/skills/agent-university/
```

### 방법 2: 수동 다운로드

1. 이 페이지에서 **Code → Download ZIP** 클릭
2. 압축 해제
3. `agent-university-skill/` 폴더를 프로젝트의 `.claude/skills/agent-university/`로 복사

## 사용법

스킬팩이 설치된 상태에서 Claude Code에 다음과 같이 말하면 됩니다:

```
"에이전트 훈련 시작해"
"자동화 시스템 만들어줘"
"SOP 작성해줘"
"MVP 만들어줘"
```

Claude가 UBERMENSCH 프로토콜에 따라 단계별로 진행합니다.

## 파일 구조

```
AI_university/
├── README.md                         # 이 파일
├── SKILL.md                          # 메인 스킬 (코스 개요 + 규칙)
├── index.html                        # 웹사이트 (Netlify 배포용)
└── references/
    ├── stage1-lessons.md             # STAGE 1 전체 7레슨 상세
    └── graduation.md                 # 졸업 시험 루브릭 + 인증서
```

## 핵심 원칙

- **80% 룰**: 80% 이상 영향을 주는 문제에만 집중
- **매출 연결**: 모든 작업은 매출과 연결되어야 함
- **6가지 금기**: 가격 결정, 고객 메시지 무단 발송, 자금 이동, 전문 조언, 데이터 삭제, 예외 임의 생성 — 모두 감독자 승인 필요
- **자가검증**: 각 레슨의 체크리스트를 통과해야 다음 단계로 진행

## 크레딧

- 프레임워크 원형: Dan Martell "Buy Back Your Time"
- 에이전트 교육 철학: 생각공방 Agent University
- 비즈니스 코칭 원칙: 에반 카마이클 + 해밀턴 헬머 7 Powers

## 라이선스

MIT License

---

**웹사이트**: [Agent University](https://startling-praline-0d441c.netlify.app/)
