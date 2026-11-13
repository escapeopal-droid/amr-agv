# AMR AGV

스마트팩토리 공정설계 — AMR·AGV 물류 공정 웹 프레젠테이션 (중간 · 기말).

- 첫 화면: https://escapeopal-droid.github.io/amr-agv/
- 중간발표: https://escapeopal-droid.github.io/amr-agv/mid/
- 기말발표 미리보기: https://escapeopal-droid.github.io/amr-agv/final/
- 로봇 제작 중간발표: https://escapeopal-droid.github.io/amr-agv/make/

## Mid-term (`mid/`)

- `mid/index.html` 한 파일에 CSS·JS 포함, 이미지는 `mid/img/`
- 방향키 · 스페이스로 장 넘김, F 또는 PRESENT 버튼으로 발표 모드

## Final presentation preview (`final/`)

- 주소: https://escapeopal-droid.github.io/amr-agv/final/
- `final/index.html` 한 파일에 CSS · 슬라이드 · 3D 코드가 모두 들어 있습니다. 이미지는 `final/img/`.
- 3D는 three.js(CDN), 장 전환 애니메이션은 GSAP(CDN)을 씁니다. 3D는 코드로 만든 목업이며 팀 모델 완성 후 GLB로 교체 예정.
- 휠 · 키보드 ↓ / ↑ 로 한 장씩 이동, I 또는 오른쪽 위 INDEX로 페이지 목록, ESC로 3D 조작·패널 닫기, PRESENT = 전체화면.

## Robot build mid review (`make/`)

- 주소: https://escapeopal-droid.github.io/amr-agv/make/
- `make/index.html` 한 파일에 CSS · 슬라이드 · 3D 코드가 들어 있습니다. 3D는 three.js(CDN)로 그리며, 모델은 `*-model.js`(GLB를 base64로 담은 파일)에서 읽습니다.
  - `amr-model.js` · `amr-model-lite.js`: MMP.00 레퍼런스 플랫폼 (STEP 80 MB → GLB 1.8 MB)
  - `team-model.js` · `team-model-lite.js`: 팀 제작 모델 ver04
  - `parts-model.js`: 리프트 · HC-SR04 브라켓 · 모터 브라켓 L/R
- 6장 구성: Overview · Hardware Concept · System Architecture · Exploded View · Lift Module · Brackets. 스크롤하면 한 장씩 스냅됩니다.
- 오른쪽 위 PRESENT 버튼 = 전체화면 발표 모드. 발표 중에는 방향키 · 스페이스로 한 장씩 이동, ESC로 종료.
