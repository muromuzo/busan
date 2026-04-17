# 부산현대미술관 SNS 콘텐츠 리뉴얼 제안서

A Proposal for Busan Museum of Contemporary Art
by 689COMPANY · 2026

## 배포 방법

### 방법 1. Vercel (추천 · 가장 빠름)
1. https://vercel.com 접속 후 로그인
2. "Add New..." → "Project" 클릭
3. 이 폴더를 통째로 드래그 & 드롭
4. Deploy 버튼 클릭 → 30초 후 URL 발급

### 방법 2. Netlify
1. https://app.netlify.com/drop 접속
2. 이 폴더를 브라우저에 드래그 & 드롭
3. 즉시 URL 발급

### 방법 3. GitHub Pages
1. GitHub에 새 레포지토리 생성
2. 이 파일들 업로드
3. Settings → Pages → Branch: main 선택
4. 발급된 URL로 접속

### 방법 4. 로컬에서 확인만
`index.html` 파일을 더블클릭하면 브라우저에서 바로 열립니다.

## 파일 구조
- `index.html` — 메인 랜딩페이지 (단일 파일, 약 145KB)
  - CSS, JS, 폰트 모두 CDN 및 인라인으로 처리되어 별도 파일 없음

## 외부 의존성 (CDN 자동 로드)
- Pretendard Variable (jsDelivr)
- JetBrains Mono (Google Fonts)
- GSAP 3.12.5 + ScrollTrigger (Cloudflare CDN)
- Lenis 1.1.14 (unpkg CDN)

배포된 사이트는 인터넷 연결이 있어야 정상 렌더링됩니다.

## 호환성
- 권장: Chrome, Edge, Safari, Firefox 최신 버전
- 데스크톱 1440px 이상 최적화
- 모바일 반응형 대응 (커스텀 커서 등 일부 효과 자동 비활성화)

© 2026 689COMPANY Holdings
