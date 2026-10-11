# 여름 텃밭

밀짚모자 친구와 함께 콩을 기르는 HTML PWA 게임.

## GitHub Pages로 올리기
1. 이 폴더의 파일을 저장소 루트에 올리기
2. Settings → Pages → Branch: `main` / `(root)` 저장
3. `https://<아이디>.github.io/<저장소>/` 접속 → 브라우저 메뉴에서 "홈 화면에 추가"

## 구성
- `index.html` 게임 전체 (시작 화면 + 텃밭)
- `assets/bg.webp` 마당(시작 장면), `assets/bg2.webp` 텃밭(오른쪽 끝으로 가면 나오는 장면) — 품질 95
- `assets/{chiikawa,hachiware,usagi}.webp` 캐릭터(무손실, 배경 투명)
- `sw.js` 오프라인 캐시 — 이미지를 바꾸면 `CACHE` 버전 숫자를 올려주세요
