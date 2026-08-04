# legacy — S3에서 옮겨온 옛 페이지 (2026-08-04)

원래 S3 버킷 `seoul-tour-crm` 에만 있던 파일들. 버킷을 정리하면서 이쪽으로 통합했다.

| 파일 | 성격 |
|---|---|
| `itinerary-es.html` | 손님용 스페인어 일정표 **템플릿** (쿼리스트링으로 이름·날짜 전달). 지금은 `../itinerarios/` 방식으로 대체됨 |
| `recibo-es.html` | 손님용 스페인어 영수증 템플릿 |
| `gracias.html` | 예약 후 감사 페이지 |
| `report.html` | 손님용 아님 — 개발 진행 보고서 문서 |

옛 S3 주소를 가리키던 링크는 전부 GitHub Pages 주소로 바꿔놓았다.

**여기 없는 것**: 6월판 CRM 복사본 3개(`index.html`, `tour-crm_2.html`, `tour-crm_v2.html`)는
localStorage에만 저장하는 죽은 버전이라 일부러 안 올렸다. 열어서 입력하면 데이터가 유실되기 때문.
원본은 로컬 백업 `/home/coreano/aws-ops/backup/seoul-tour-crm-20260804/` 에 있다.

현재 운영본은 저장소 루트의 `../index.html` (https://gyulo.github.io/tour-crm/).
