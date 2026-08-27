# OBS 치지직 신청 대기열

치지직 채팅의 `!노래 가수 - 곡명`, `!시참` 명령어를 받아 OBS 브라우저 소스에 표시하는 Railway용 앱입니다.

## 환경변수

`.env.example`의 모든 값을 Railway에 등록합니다. `ADMIN_SECRET`, `OBS_SECRET`, `SESSION_SECRET`은 서로 다른 긴 임의 문자열을 사용합니다.

치지직 개발자센터 애플리케이션의 로그인 리디렉션 URL은 아래와 같습니다.

`https://배포주소/api/chzzk/callback`

API Scope는 `채팅 메시지 조회`가 필요합니다.

## 사용 주소

- 관리자: `https://배포주소/`
- OBS: `https://배포주소/?view=overlay&key=OBS_SECRET`

## 명령어

- `!노래 가수 - 곡명`
- `!시참`
