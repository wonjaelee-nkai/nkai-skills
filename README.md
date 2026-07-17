# N-KAI Skills · 한국 소상공인을 위한 무료 AI 에이전트 스킬

매장 사장님과 1인 사업자가 매일 하는 일(SNS 게시물, 리뷰 답글, 블로그, 가격 점검, 신상품 검증)을 AI 에이전트에게 제대로 시키기 위한 작업 설명서 모음입니다. Claude Code, Codex, Cursor 등 SKILL.md 표준을 지원하는 에이전트 어디서나 동작합니다.

장식적인 프롬프트가 아니라 실제 매장 운영 자동화에서 쓰는 절차를 공개용으로 정리했습니다. 작고, 고치기 쉽고, 조합해 쓸 수 있게 만들었습니다.

## 빠른 시작

1. 이 저장소를 클론하거나 ZIP으로 내려받습니다.
2. 원하는 스킬 폴더를 에이전트의 스킬 디렉터리에 복사합니다.
   - Claude Code: `~/.claude/skills/` 또는 프로젝트의 `.claude/skills/`
   - 기타 에이전트: 해당 하네스의 skills 디렉터리
3. 에이전트에게 스킬 이름을 부르거나, 해당 업무를 요청하면 됩니다.

## 스킬 목록

| 스킬 | 하는 일 |
|---|---|
| [store-sns-post](./skills/store-sns-post/SKILL.md) | 매장 SNS 게시물을 훅, 해결, 증거, 행동유도 4구조로 작성 |
| [review-reply](./skills/review-reply/SKILL.md) | 유형별 리뷰 답글을 매장 톤으로 작성 (악성 리뷰 대응 포함) |
| [naver-blog-post](./skills/naver-blog-post/SKILL.md) | 네이버 검색에 잘 걸리는 매장 블로그 글 작성 |
| [menu-price-check](./skills/menu-price-check/SKILL.md) | 메뉴, 상품 가격을 원가와 시장가 두 축으로 점검 |
| [market-first-7steps](./skills/market-first-7steps/SKILL.md) | 신메뉴, 신상품을 출시 전에 시장조사부터 검증하는 7단계 |

## 이 스킬들의 원칙

- 추측 대신 실측: 시장가, 검색어, 경쟁 매장을 먼저 확인하고 만든다.
- 결론 우선: 손님이 3초 안에 알아볼 수 있게 쓴다.
- 반복 가능: 한 번 성공한 포맷은 버리지 않고 변주한다.
- 한 산출물에 행동유도(CTA)는 1개만.

## 만든 곳

뉴린카이로스에이아이 주식회사가 만들고 운영합니다. 우리는 매장과 사람의 데이터를 융합해 다음 행동을 예측하는 초개인화 AI 엔진을 개발합니다.

- 웹사이트: https://www.neurinkairosai.ai
- 매장 자동화(SNS, 광고, 리포트)를 통째로 맡기고 싶다면: https://www.neurinkairosai.ai/inquiry?source=github_skills

## 라이선스

MIT. 자유롭게 쓰고 고치고 재배포하세요.
