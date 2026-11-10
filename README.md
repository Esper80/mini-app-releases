# 미니 시리즈 다운로드

Windows x64 앱의 공식 배포 저장소입니다. 실행파일 이름은 버전 없이 유지하고 버전은 앱 정보·EXE 속성·릴리스에서 관리합니다.

| 앱 | 버전 | 다운로드 | 안내 |
| --- | --- | --- | --- |
| Mini Audio | 1.0.11 | [MiniAudio.exe](https://github.com/Esper80/mini-app-releases/releases/download/mini-audio/v1.0.11/MiniAudio.exe) | [릴리스·필수 자료](https://github.com/Esper80/mini-app-releases/releases/tag/mini-audio/v1.0.11) |
| Mini Monitor | 1.8 | [MiniMonitor.exe](https://github.com/Esper80/mini-app-releases/releases/download/mini-resource-monitor/v1.8/MiniMonitor.exe) | [릴리스·필수 자료](https://github.com/Esper80/mini-app-releases/releases/tag/mini-resource-monitor/v1.8) |
| Mini Capture | 1.2 | [MiniCapture.exe](https://github.com/Esper80/mini-app-releases/releases/download/mini-capture/v1.2/MiniCapture.exe) | [릴리스·필수 자료](https://github.com/Esper80/mini-app-releases/releases/tag/mini-capture/v1.2) |
| Mini MP3 Maker | 1.2.7 | [MiniMP3Maker.exe](https://github.com/Esper80/mini-app-releases/releases/download/mini-mp3-maker/v1.2.7/MiniMP3Maker.exe) | [릴리스·필수 자료](https://github.com/Esper80/mini-app-releases/releases/tag/mini-mp3-maker/v1.2.7) |
| MiniTV Link PC | 1.2.2 | [MiniTVLink.exe](https://github.com/Esper80/mini-app-releases/releases/download/mini-tv-link/v1.2.2/MiniTVLink.exe) | [릴리스·필수 자료](https://github.com/Esper80/mini-app-releases/releases/tag/mini-tv-link/v1.2.2) |

위 버전은 정식 게시와 익명 다운로드 검증을 마쳤습니다. 공개 업데이트는 `updates/stable.json`의 서명된 앱별 안정 목록을 사용합니다. 생성·만료 시각과 검증 내역은 [운영 기록](docs/ACTIVATION.md)을 확인하세요.

기존 updater 미지원 버전에서는 이번 지원 버전을 한 번 수동으로 내려받아야 합니다. 기존 바로가기·Windows 자동 실행이 이전 버전 파일을 가리키면 새 EXE 경로로 변경하세요. 이후 업데이트는 현재 실행 경로를 유지합니다.

앱에서 시작 시 확인 여부와 자동 다운로드·설치를 선택할 수 있습니다. 시작 시 확인은 기본 켬, 자동 설치는 기본 끔입니다. 수동 확인도 지원합니다. 네트워크 오류나 검증 실패 시 기존 앱을 계속 사용합니다. 검증한 같은 EXE는 다운로드 완료 후 1시간 동안 재사용합니다.

Audio의 LGPL 라이브러리 교체 자료와 MP3 Maker의 구성요소 원본 소스·빌드 자료는 해당 릴리스에서 함께 제공합니다. Capture 릴리스 첨부는 EXE 하나이며 고지는 앱에 내장됩니다. TV Link는 PC 앱 배포이며 기기 펌웨어를 자동 설치하지 않습니다.

본체 소스·개인 설정·로그·인증 정보·서명 비밀키는 이 공개 저장소에 게시하지 않습니다. [공통 배포 절차](docs/PUBLISHING.md)를 먼저 읽으세요. 공동 저장소의 `releases/latest`를 앱별 최신 버전 판정에 사용하지 않습니다.

Mini Monitor 1.5·1.6은 URL 검사 오류 때문에 새 EXE를 내려받지 못합니다. 앱을 Exit로 종료하고 현재 경로의 MiniMonitor.exe만 1.8로 한 번 수동 교체하세요. 설정·인증 폴더는 유지합니다. 1.8은 다른 앱·임의 URL을 허용하지 않고 Rust 다운로드 URL의 인코딩 검사를 수정합니다.

Mini Monitor 1.8의 Disconnect는 확인 후 이 앱 전용 Codex 로그인 정보를 초기화합니다. 연결되지 않은 상태에서도 사용할 수 있습니다. 업데이트 자체는 로그인·창 좌표·일반 설정을 유지합니다.
