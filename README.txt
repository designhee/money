월급 계산기 모바일 웹앱(PWA)

구성 파일
- index.html: 계산기
- manifest.json: 홈 화면 설치 설정
- service-worker.js: 오프라인 캐시
- icon.svg: 앱 아이콘

휴대폰에서 앱처럼 사용하려면 이 파일들을 HTTPS를 지원하는 웹 호스팅에 올려야 합니다.
예: GitHub Pages 같은 정적 호스팅. 업로드 후 사이트를 휴대폰 브라우저에서 열고:
- iPhone(Safari): 공유 버튼 → 홈 화면에 추가
- Android(Chrome): 메뉴(⋮) → 앱 설치 또는 홈 화면에 추가

단순히 index.html 파일만 휴대폰에서 여는 것도 가능하지만, 홈 화면 설치와 오프라인 기능은 HTTPS 호스팅에서 가장 잘 작동합니다.
