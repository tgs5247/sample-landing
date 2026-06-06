# sample-landing

범용 1페이지 랜딩 샘플 사이트 (정적 사이트, HTML/CSS/JS 단일 파일).

## 구성
- `index.html` — Hero / 서비스 / 소개 / 공지 / 오시는길(카카오맵 자리) / 문의폼 / 푸터 + 오른쪽 수정 사이드바
- 정적 사이트라 별도 빌드 불필요 → Cloudflare Pages에 그대로 배포

## 배포 (Cloudflare Pages)
- Framework preset: **None**
- Build command: (비움)
- Build output directory: **/** (루트)

## 운영 메모
- 문의폼: 현재는 데모. 운영 시 Tally 임베드 또는 EmailJS로 교체 (공통 부품)
- 카카오맵: 카카오 JavaScript 키 발급 후 `#map` 영역에 연결
- 수정 사이드바: 고객 미리보기/문구 확인용. 확정 문구는 코드에 반영 후 재배포
