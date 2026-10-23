# Wiki Operation Log (작업 로그)

> 이 문서는 LLM Wiki에서 수행된 모든 작업(Ingest, Query, Report, Lint)을 시계열로 기록하는 Append-only 로그입니다.
> 파싱 규약: `## [YYYY-MM-DD HH:mm] <작업종류> | <제목> | <대상/경로>`

---

## [2026-10-23 12:15] init | LLM Wiki 초기 환경 구축 | Vault Root
- 디렉토리 구조 생성: `00_raw/`, `01_wiki/`, `02_reports/`
- 스키마 헌법 정의: `[[AGENTS]]`
- 중앙 색인 및 로그 파일 생성: `[[index]]`, `[[log]]`
- IT PM & 서비스 개발자 듀얼 롤 맞춤형 메타데이터 규약 수립
