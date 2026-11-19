# inspection
기술종류 조사사항

개발환경
- 개발언어: Go, TypeScript, SQL
- 사용 프레임워크·라이브러리: Gin, React, React Native, Expo
- 개발방법론: 애자일
- 로컬 판단 모델: JEVOS
- 서버 프로세서: Go 기반 HTTP 서버(Gin), Nginx
- 문서 검색용 임베딩 모델 — 초기 개발 : BGE Small EN v1.5 / 추후 구현 과정에서 성능비교 후보 : Arctic Embed S
- DB: PostgreSQL + pgvector
- 로그 수집 도구: Fluent Bit
- 외부 API 및 서비스: NVD API, LLM API, Expo Push Service
- 웹 실시간 알림: SSE
- 운영 환경: Linux, Docker


최종결과물
(Software)  백엔드: 로그 수집 및 정규화 모듈, 규칙 기반 탐지 및 경보 생성 모듈, CVE·보안 권고문 검색 모듈, JEVOS 기반 경보 점검 모듈, AI 대응 안내·질의응답 API / 웹 : 실시간 토스트 알림, 경보 목록 화면, 경보 상세 화면(근거 로그·관련 CVE·보안 권고문·초기 대응 안내), 경보별 AI 질의응답 화면 / 모바일: 푸시 알림 및 대응 안내 조회
