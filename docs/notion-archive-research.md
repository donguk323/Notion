# notion-archive 개정 근거 — BLUF·PREP·육하원칙을 노션 저장에 적용

> **결론** — 노션 저장 페이지를 '훑기 · 결정 · 검산' 3층으로 나눈다. 맨 위에 BLUF(결론·다음 행동·기한), 그 아래 육하원칙 맥락 줄, 본문은 소제목마다 PREP, 검산 자료는 토글에 둔다.<br>기준일 2026-09-29 · 검증: 일부 미확인(아래 「출처 확인 수준」 참고)

**맥락** 대상은 `notion-archive` 스킬, 저장소는 `donguk323/notion`이다. 저장 위치는 🗂️ ChatGPT 아카이브 DB이고, 읽는 사람은 6개월 뒤의 본인이다. 기존 스킬의 뼈대(결론 인용 블록 → 핵심 → 본문 → 확인 필요 → 출처)는 유지하고, 사용자 요청에 따라 BLUF·PREP·육하원칙을 규칙으로 명시했다.

## 📌 핵심

1. **앞에 둔 결론과 맥락은 이해와 기억을 돕는다.** 제목·개요 같은 신호와 사전 맥락의 효과는 인지심리 연구에서 반복 확인됐다. → BLUF 결론 블록, 맥락 줄
2. **사람은 읽지 않고 훑는다.** 소제목이 내용을 담고 있으면 소제목만 따라 내려간다. → 소제목 = 그 블록의 결론(PREP의 P)
3. **다시 찾기는 검색어가 좌우한다.** 같은 대상을 두 사람이 같은 단어로 부를 확률은 20% 미만이다. → 제목 앞에 명사, 키워드에 동의어·영문
4. **판단의 이력이 남아야 같은 조사를 반복하지 않는다.** 결정 기록(ADR)은 결론을 덮어쓰지 않고 대체 이력을 남긴다. → 변경 줄, 뺀 것 토글
5. **육하원칙은 양식이 아니라 점검표로 쓴다.** 한국 공문서 작성 지침은 육하원칙으로 내용을 구체화하고, 돈이 걸리면 '얼마'를 더하라고 권한다(5W2H). → W를 결론 블록·맥락 줄·근거에 나눠 배치

## 🧩 원칙별 근거와 스킬 반영

<table header-row="true">
<tr><td>원칙</td><td>근거</td><td>스킬 반영</td></tr>
<tr><td>결론·요구·기한을 맨 앞에(BLUF)</td><td>미 육군 서신 규정 AR 25-50, HBR Sehgal(2016)의 [ACTION]/[INFO] 제목 태그</td><td>4절 결론 블록: 결론 + 다음 행동 + 기한 + 기준일 + 검증</td></tr>
<tr><td>맥락을 먼저 주면 이해·회상이 는다</td><td>Bransford & Johnson(1972): 주제를 글보다 먼저 알려준 조건에서만 이해·회상이 높았다</td><td>5절 맥락 줄: 누가·어디서·왜를 결론 바로 아래에</td></tr>
<tr><td>제목·개요·요약 같은 신호는 신호받은 내용의 기억을 높인다</td><td>Lorch(1989) 리뷰: 대부분의 신호 장치가 신호한 정보의 기억을 높이고, 신호하지 않은 정보에는 영향이 적다</td><td>결론 블록, 📌 핵심, 소제목에 결론을 싣기</td></tr>
<tr><td>소제목은 회상·검색·재탐색을 돕는다</td><td>Hartley & Trueman(1985) 9개 실험: 소제목이 회상·검색·재탐색을 도왔고, 질문형과 서술형의 차이는 대체로 없었다</td><td>6절 소제목 = 결론 서술문(질문형 강제 안 함)</td></tr>
<tr><td>구조가 약하면 F자로, 소제목이 좋으면 층층이 훑는다</td><td>NN/g 시선추적: F-pattern(2006, 2017 재검토), layer-cake pattern</td><td>소제목 앞머리에 핵심 명사, 소제목만 읽어도 논리가 이어지는지 점검(11절 5번)</td></tr>
<tr><td>주장 → 이유 → 근거 → 재주장(PREP), 결론 정점의 피라미드</td><td>Minto, The Pyramid Principle(1985). SCQA와 MECE</td><td>6절 P·R·E, MECE 소제목, 재진술은 조건이 바뀔 때만</td></tr>
<tr><td>정보 냄새가 강해야 들어온다</td><td>Pirolli & Card(1999) Information Foraging</td><td>제목 `주제 — 결론 조각`, 한 줄 결론은 비우지 않음</td></tr>
<tr><td>어휘 불일치</td><td>Furnas 외(1987): 두 사람이 같은 용어를 고를 확률 0.20 미만, 단일 용어 접근은 80~90% 실패</td><td>8절 키워드 5~15개, 동의어·영문·약어·고유명사</td></tr>
<tr><td>정리보다 검색이 재발견에 효율적</td><td>Whittaker 외(2011, CHI) 345명 이메일 재발견 현장연구: 복잡한 폴더 정리는 재발견 성공을 높이지 못했고 검색·스레드가 더 효과적</td><td>분류는 가볍게(태그 1~2개), 검색 신호(제목·키워드·한 줄 결론)에 공을 들인다</td></tr>
<tr><td>개인 정보관리는 '미래의 나를 위한 큐레이션'</td><td>Bergman & Whittaker(2016) 사용자 주관 접근</td><td>독자를 '6개월 뒤의 나'로 고정</td></tr>
<tr><td>미래의 나에게 표지판을 남긴다</td><td>Forte, Progressive Summarization: 미래의 나를 위한 신호와 발견 가능성</td><td>3층 구조, 토글로 검산층 분리</td></tr>
<tr><td>제목은 API처럼</td><td>Matuschak, Evergreen notes: 잘 지은 제목이 노트 전체의 손잡이가 된다</td><td>제목에 결론을 싣는 규칙 유지</td></tr>
<tr><td>결정은 덮어쓰지 않고 대체한다</td><td>Nygard(2011) ADR: Status, Superseded, Context, Consequences</td><td>2절 변경 줄, 7절 뺀 것</td></tr>
<tr><td>육하원칙 + 얼마(5W2H)</td><td>국내 공문서 작성 지침(교육청 공문서 작성법 등): 육하원칙으로 구체화, 비용은 HOW MUCH 추가</td><td>5절 W 배치표, '얼마' 라벨</td></tr>
</table>

## 🧩 다른 스킬 조사 — 가져온 것과 두고 온 것

<table header-row="true">
<tr><td>스킬</td><td>가져온 것</td><td>두고 온 것</td></tr>
<tr><td>Notion 공식 knowledge-capture (makenotion/notion-cookbook)</td><td>내용 유형 분류(개념·방법·결정·FAQ·회고), 유형별 골격</td><td>허브·인덱스 페이지 갱신 — 이 아카이브는 DB 보기와 프로젝트 관계로 대신한다</td></tr>
<tr><td>Notion 공식 research-documentation</td><td>요약 먼저, 출처를 원문에 연결, 공백과 불일치 표시</td><td>독립 페이지 기본값 — 여기선 아카이브 DB가 기본</td></tr>
<tr><td>Anthropic internal-comms</td><td>유형별 예시 파일을 따로 두는 구조</td><td>회사 커뮤니케이션 톤</td></tr>
<tr><td>Obsidian 계열 second-brain 스킬(claude-obsidian 등)</td><td>새 자료를 따로 쌓지 않고 기존 지식에 연결해 정리한다는 방향</td><td>자동 링크 그래프·정기 에이전트 — 노션 DB 구조와 맞지 않는다</td></tr>
<tr><td>사용자 스킬 kakao-memo</td><td>3층(훑기·결정·검산), 기준일≠기한, 없음≠미확인, 뺀 것 보존, 판단을 대신했으면 밝히기</td><td>순수 텍스트·20자 줄 제한 — 노션은 렌더링된다</td></tr>
<tr><td>Anthropic 스킬 작성 모범사례</td><td>본문 500줄 이하, 참조 파일은 한 단계, 체크리스트, 평가 3개</td><td>—</td></tr>
</table>

## 🧩 현재 아카이브 진단 — 좋은 페이지는 이미 3층이었다

- **갤럭시 사진 공유 가이드(2026-09-23)**: 결론·지금 할 일·주의를 콜아웃 셋으로 두고 반대 근거·출처를 토글로 내렸다. 새 규칙의 원형이다. 다만 '결론' 라벨이라 AI 추천인지 사용자 결정인지는 구분되지 않는다.
- **신혼집 인터넷·IPTV(2026-09-05)**: 결론 블록은 좋다. 그러나 다음 행동이 맨 아래 「다음 수」에만 있고, 누가·어디서·왜가 본문 중간 문단에 흩어져 있다. 25개 시나리오 표와 로컬 경로·해시가 첫 화면 흐름 안에 있다. 새 규칙에서는 다음 행동을 결론 블록으로 올리고, 맥락 줄을 신설하고, 계산 표와 작업 기록은 토글로 보낸다.
- 기존 SKILL.md는 "콜아웃 문법에 의존하지 않는다"고 했다. 그러나 실제 좋은 페이지는 콜아웃을 썼고, Notion MCP 문법도 콜아웃·토글을 공식 지원한다. 개정판은 콜아웃을 쓰고, 지원하지 않는 클라이언트용 대체(인용 블록 + `<br>`)를 적었다.

## 🧩 채택하지 않은 것

- **제텔카스텐식 원자 노트**: 대화 하나에 페이지 하나라는 운영 원칙과 맞지 않는다. 연결은 `연결 프로젝트`와 mention으로 한다.
- **질문형 소제목 강제**: Hartley & Trueman에서 질문형과 서술형의 일반적인 차이는 없었다. 결론을 싣기 쉬운 서술형을 기본으로 한다.
- **Progressive Summarization의 단계별 굵게·형광펜**: 반복해서 다시 열 때 층을 쌓는 기법이다. 저장 시점에 AI가 한 번에 형광펜을 칠하면 강조가 과해진다. 형광펜은 결론 문장 하나까지만 쓴다.
- **육하원칙 표**: 모든 문서에 6칸을 두면 빈칸 압박으로 값이 지어지기 쉽다(E 슬롯 문제와 같은 구조). 필요한 W만 제자리에 둔다.

## ⚠️ 확인 필요

<table header-row="true">
<tr><td>항목</td><td>왜 미확인인가</td><td>확인 방법</td></tr>
<tr><td>연구 원문 수치</td><td>이 세션의 네트워크 정책이 nngroup.com, 대학·학회 PDF 등을 차단해 검색 요약으로만 확인했다</td><td>원문 PDF에서 Bransford 실험 2의 조건별 점수, Whittaker의 검색·폴더 시간 비교를 대조</td></tr>
<tr><td>국내 공문서 지침 원문</td><td>교육청 PDF 접근이 차단돼 검색 요약만 봤다</td><td>행정안전부 「행정업무운영 편람」 원문에서 육하원칙·5W2H 문구 확인</td></tr>
<tr><td>새 규칙의 실제 효과</td><td>평가(evals/evals.json) 3개를 정의만 했고 아직 실행하지 않았다</td><td>세 프롬프트로 실제 저장해 보고, 11절 점검표 통과 여부 기록</td></tr>
<tr><td>ChatGPT 쪽 동명 스킬</td><td>이 저장소 밖에 있다</td><td>이 SKILL.md에 맞춰 동기화(skill-porter 활용)</td></tr>
</table>

<details>
<summary>🧾 출처 확인 수준</summary>

- **본문을 직접 읽음**: Anthropic 스킬 작성 모범사례, Notion 공식 knowledge-capture·research-documentation SKILL.md, Notion MCP enhanced markdown 사양, 사용자 노션의 「PREP / BLUF」·「전역프롬프트 수정」·「경량 PARA 운영 가이드」·아카이브 페이지 2건
- **검색 결과 요약만 확인**: NN/g, Whittaker 외, Furnas 외, Pirolli & Card, Bransford & Johnson, Hartley & Trueman, Lorch, Minto, Forte, Matuschak, Nygard, Bergman & Whittaker, 국내 공문서 작성 지침, Obsidian 계열 스킬
</details>

## 🔗 출처

- [Skill authoring best practices](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/best-practices) — Anthropic
- [knowledge-capture SKILL.md](https://github.com/makenotion/notion-cookbook/tree/main/skills/claude/knowledge-capture) — Notion(makenotion)
- [research-documentation SKILL.md](https://github.com/makenotion/notion-cookbook/tree/main/skills/claude/research-documentation) — Notion(makenotion)
- [claude-code-notion-plugin](https://github.com/makenotion/claude-code-notion-plugin) — Notion(makenotion)
- [internal-comms SKILL.md](https://github.com/anthropics/skills/tree/main/skills/internal-comms) — Anthropic
- [F-Shaped Pattern of Reading: Misunderstood, But Still Relevant](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/) — Nielsen Norman Group
- [The Layer-Cake Pattern of Scanning Content on the Web](https://www.nngroup.com/articles/layer-cake-pattern-scanning/) — Nielsen Norman Group
- [Contextual prerequisites for understanding](https://psycnet.apa.org/record/1973-20178-001) — Bransford & Johnson, JVLVB 11(1972)
- [Text-signaling devices and their effects on reading and memory processes](https://link.springer.com/article/10.1007/BF01320135) — Lorch, Educational Psychology Review 1(1989)
- [A research strategy for text designers: The role of headings](https://link.springer.com/article/10.1007/BF00052394) — Hartley & Trueman, Instructional Science(1985)
- [The vocabulary problem in human-system communication](https://dl.acm.org/doi/10.1145/32206.32212) — Furnas 외, CACM 30(11)(1987)
- [Information Foraging](https://philpapers.org/rec/PIRIF) — Pirolli & Card, Psychological Review(1999)
- [Am I wasting my time organizing email?](https://dl.acm.org/doi/10.1145/1978942.1979457) — Whittaker 외, CHI(2011)
- [The Science of Managing Our Digital Stuff](https://mitpress.mit.edu/9780262035170/the-science-of-managing-our-digital-stuff/) — Bergman & Whittaker, MIT Press(2016)
- [Barbara Minto: MECE](https://www.mckinsey.com/alumni/news-and-events/global-news/alumni-news/barbara-minto-mece-i-invented-it-so-i-get-to-say-how-to-pronounce-it) — McKinsey Alumni
- [Progressive Summarization](https://fortelabs.com/blog/progressive-summarization-a-practical-technique-for-designing-discoverable-notes/) — Forte Labs
- [Evergreen note titles are like APIs](https://notes.andymatuschak.org/Evergreen_note_titles_are_like_APIs) — Andy Matuschak
- [ADR template by Michael Nygard](https://github.com/joelparkerhenderson/architecture-decision-record/tree/main/locales/en/templates/decision-record-template-by-michael-nygard) — Nygard(2011)
- [AR 25-50 Preparing and Managing Correspondence](https://armypubs.army.mil/epubs/DR_pubs/DR_a/ARN42124-AR_25-50-007-WEB-13.pdf) — 미 육군(2020)
- [How to Write Email with Military Precision](https://hbr.org/2016/11/how-to-write-email-with-military-precision) — HBR, Sehgal(2016)
- [한 곳에 정리한 공문서 작성법](https://www.goe.go.kr/resource/old/BBSMSTR_000000000028/BBS_202410150153084250.pdf) — 경기도교육청
- [claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian) — AgriciDaniel
