## Hi, I'm Jinhyoung Ahn 👋

Gachon University — Smart Security (Double Major)
Breaking things to understand how they work: exploitation, cryptography, on-chain security.

- 🔐 Wargame — exploring [Dreamhack](https://dreamhack.io): binary exploitation, cryptography, reverse engineering, smart contract security
- 🧮 Competitive programming — [BOJ](https://www.acmicpc.net), mainly in Lua, also C++

   [![Solved.ac 프로필](https://mazassumnida.wtf/api/v2/generate_badge?boj=aunps)](https://solved.ac/profile/aunps)

- ⛓️ Research — Celestia DA, zkVM, on-chain IP licensing → [`Articles`](https://github.com/hyper-cloud10/Articles)
- 📄 [`pdf-reflux`](https://github.com/hyper-cloud10/pdf-reflux) — 논문 PDF 자동 분류·아카이빙 시스템
  - 감지: Windows `PowerShell FileSystemWatcher` → `wsl -d Ubuntu -- bash -c`로 분류 스크립트 호출. WSL2가 `/mnt/c` 변경에 대한 inotify 이벤트를 못 받는 구조적 한계 때문에 감시 자체는 Windows 네이티브에서 수행
  - 분류: 사용자 정의 YAML(카테고리 목록 + 경계 규칙)로 시스템 프롬프트를 런타임에 동적 생성, Claude API(Haiku)로 분류해 `{category, confidence, reason}` JSON 구조화 응답을 받음
  - 데이터: SQLite로 구현(Supabase/Postgres 마이그레이션 예정). SHA-256 파일 해시로 경로가 달라져도 재다운로드 중복 탐지, API 실패/저확신 미분류를 `error_type`으로 구분해 기록
  - 안전장치: PreToolUse 훅으로 파일 이동 목적지를 화이트리스트 경로로 강제, PDF 파서(pdfminer.six) CVE 회피용 의존성 버전 하한선 고정
- 🏫 Gairos — Gachon University Blockchain Society

📫 X: [@unsafe_rust](https://x.com/unsafe_rust)

### Languages
[![hyper-cloud10 Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=hyper-cloud10&layout=compact&theme=nord&hide_border=true)](https://github.com/hyper-cloud10)
