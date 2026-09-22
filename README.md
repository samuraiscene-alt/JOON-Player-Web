# JOON Player Web

JOON Player의 **Web/PWA 실행용 저장소**입니다.

- 실제 iPhone Safari / 홈 화면 추가 테스트는 이 저장소에서 진행합니다.
- Native iOS/iPadOS Swift + VLCKit 코드는 별도 저장소 `samuraiscene-alt/JOON-Player`에 그대로 보존합니다.
- 웹에서 제한되는 MKV 코덱 호환성, security-scoped bookmark, 프레임 이동, 오디오 EQ/싱크, FFmpeg 자르기·복구 등은 삭제하지 않고 Native backlog로 유지합니다.

## 현재 Web 1차 기능

- 로컬 동영상 여러 개 선택
- 서버 업로드 없이 브라우저 Object URL로 재생
- 재생 / 일시정지 / ±10초
- 진행바 / 현재 시간 / 전체 시간
- 음소거
- 전체화면 fallback
- 웹 PiP 가능 범위
- 세션 재생목록
- 이전 / 다음
- 전체 반복 / 한 곡 반복 / 셔플
- 재생 속도
- 화면비율
- A-B 반복
- 취침 타이머
- 외부 SRT
- 자막 싱크 / 크기 / 위치
- 더블 탭 ±10초
- 수평 드래그 탐색
- 길게 누르는 동안 2배속
- 영상 밝기 오버레이
- 컨트롤 잠금
- 이어보기 localStorage
- PWA manifest / service worker

## 배포

GitHub Pages를 **GitHub Actions** 방식으로 한 번만 활성화하면 이후 `main` 변경 시 자동 배포됩니다.

웹앱 주소는 Pages 활성화 후:

`https://samuraiscene-alt.github.io/JOON-Player-Web/`

을 사용합니다.
