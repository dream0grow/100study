# CLAUDE.md — 100study

이 저장소는 **「100시간 공부」 뽀모도로 앱** 단독 저장소입니다. 저장소 루트가 곧 웹앱 루트예요.

- **먼저 `AGENTS.md`를 읽으세요** — 구조·데이터 모델·원칙·배포·백로그가 전부 거기 있습니다.
- 웹앱: 루트의 `index.html`·`js/`·`css/` (빌드 없음, 순수 HTML/JS)
- 아이폰 네이티브 포장: `ios-app/` (Capacitor) — 절차는 `ios-app/README.md`
- 코드를 바꾸면 `sw.js`의 `CACHE` 버전을 한 단계 올릴 것
- 새 브랜치 → PR로 작업 (main 직접 커밋 금지). 배포는 main 머지 시 GitHub Pages 자동
- 개발자는 코딩 학습 중인 현직 교사 — 친절한 한국어 주석 필수

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
