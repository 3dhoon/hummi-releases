# Music Player Releases

Music Player 데스크톱 앱의 **배포 전용** 저장소입니다. 소스 코드는 여기에 없습니다.

## 설치

[Releases](https://github.com/3dhoon/hmm-player-releases/releases/latest)에서 `hmm-player_<버전>_x64-setup.exe`를 받아 설치하세요. Windows(x86_64)만 지원합니다.

설치 후에는 앱이 시작할 때 새 버전을 자동으로 확인합니다. `설정 → 고급 → 앱 업데이트`에서 직접 확인하거나 설치할 수도 있습니다.

## 릴리스에 포함된 파일

| 파일 | 용도 |
| --- | --- |
| `hmm-player_<버전>_x64-setup.exe` | 설치 파일. 직접 내려받을 때도, 앱이 자동 업데이트할 때도 같은 파일을 사용합니다. |
| `latest.json` | 앱이 최신 버전을 확인하는 매니페스트 |

설치 파일은 minisign으로 서명되어 있으며, 앱에 포함된 공개키로 서명을 검증한 뒤에만 자동 설치됩니다.

## 참고

코드 서명 인증서를 사용하지 않으므로 설치할 때 Windows SmartScreen 경고가 표시될 수 있습니다. `추가 정보 → 실행`으로 진행하세요.
