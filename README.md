# WHO ARE ME? — GitHub Pages용 뿡치 콘텐츠 맞히기

`index.html`, `style.css`, `game.js`, `data.json`을 같은 폴더에 올리면 됩니다.

GitHub 저장소 → Settings → Pages → Deploy from a branch → `main` / `/ (root)` 선택.

`data.json`의 name, category, type, date, format, url, thumbnail을 원하는 콘텐츠 데이터로 교체하세요. 정답 팝업에서 url은 SOOP 바로가기, thumbnail은 썸네일 이미지로 사용됩니다.

현재 통계는 서버 없이 브라우저 localStorage에 저장됩니다. 모든 사용자에게 동일한 일일 문제, 서버 통계, 로그인, 관리자 데이터 등록 등을 넣으려면 다음 단계에서 Firebase/Supabase 같은 백엔드를 붙이면 됩니다.
