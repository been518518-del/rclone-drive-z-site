# rclone-drive-z 안내 사이트

Google OAuth 화면에 등록할 앱 홈페이지와 개인정보처리방침입니다.

- 홈페이지: https://been518518-del.github.io/rclone-drive-z-site/
- 개인정보처리방침: https://been518518-del.github.io/rclone-drive-z-site/privacy.html

## GitHub Pages 게시

저장소의 **Settings → Pages**에서 다음을 설정하세요.

- **Build and deployment**: Deploy from a branch
- **Branch**: main
- **Folder**: /(root)

저장 후 GitHub Pages 배포가 완료되면 위 두 주소를 브라우저에서 열어 로그인 없이 볼 수 있는지 확인하고, Google Cloud의 OAuth **Branding** 화면에 각각 입력하세요. 앱 도메인으로 요청되면 호스트명 `been518518-del.github.io`를 사용하세요.

## 권한 및 데이터

rclone은 Windows PC에서 Google Drive API에 직접 연결합니다. `drive` OAuth 범위는 Z:에 마운트한 폴더 하나보다 넓으며, 승인한 계정의 Drive 전체에 접근할 수 있는 권한을 허용할 수 있습니다. 페이지에 이 점을 명시했습니다. Drive 파일과 OAuth 토큰은 이 안내 웹사이트에 업로드하지 않습니다.

## 참고

- [rclone Google Drive 설정 안내](https://rclone.org/drive/#making-your-own-client-id)
- [Google OAuth 앱 홈페이지 요구사항](https://support.google.com/cloud/answer/13807376?hl=en)
