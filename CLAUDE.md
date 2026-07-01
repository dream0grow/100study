# CLAUDE.md — 100study

## 한국어 윤문 스킬 — 제3자 노출 문구는 무조건 적용 (필수)

제3자에게 보여주는 **모든 한국어 문구**를 작성·수정했다면, 발행·커밋 전에 반드시 아래 윤문 스킬을 거친다.
대상 예시: 스레드 글, 카드뉴스, 뉴스레터, 영상 스크립트, 강의 스크립트, 홈페이지·랜딩 카피라이팅,
앱 화면 텍스트(버튼·안내·오류 메시지 등 UI 문구), 상세페이지, SNS 게시물.
제외: 코드 주석, 내부 문서, 커밋 메시지 등 사용자 본인만 보는 텍스트.

- **기본**: `/im-not-strange-ai` — Sunny 문장 규칙 포함 (`.claude/skills/im-not-strange-ai`)
- **대안**: `/humanize-korean` 또는 `/humanize` (`.claude/skills/humanize-korean`)
- 8,000자 초과·정밀 검증이 필요하면 `--strict` (5인 파이프라인)
- 원칙: 의미·사실·수치는 한 글자도 바꾸지 않고 문체·리듬·표현만 다듬는다

스킬·에이전트는 이 저장소 `.claude/skills/`·`.claude/agents/`에 동봉되어 있다.
출처: https://github.com/epoko77-ai/im-not-ai · https://github.com/itssosunny/im-not-strange-ai
