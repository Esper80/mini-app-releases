# mini-app-releases

미니 시리즈 Windows 앱의 공식 다운로드 및 자동 업데이트 배포 저장소입니다. 각 앱의 본체 소스는 기존 비공개 저장소에서 관리합니다.

## 공개 저장소 사용 방법

게시·업데이트 작업자는 [공통 배포 절차](docs/PUBLISHING.md)를 먼저 읽으세요. 앱별 릴리스 구분, 실행파일 이름, 안정 채널 목록, 검증·게시 순서와 복구 방법을 설명합니다.

실행파일은 이 저장소의 Git 기록이 아닌 **GitHub Releases 첨부 자산**으로 배포합니다. 앱별로 독립된 릴리스를 사용하며 저장소 전체의 latest를 특정 앱의 최신 버전으로 간주하지 않습니다.

## 대상 앱

| 앱 | 앱 ID | 전환 목표 EXE |
| --- | --- | --- |
| Mini Audio | mini-audio | MiniAudio.exe |
| Mini Monitor | mini-resource-monitor | MiniMonitor.exe |
| Mini Capture | mini-capture | MiniCapture.exe |
| Mini MP3 Maker | mini-mp3-maker | MiniMP3Maker.exe |
| MiniTV Link PC | mini-tv-link | MiniTVLink.exe |

## 전환 상태

이 안내는 공통 배포처와 사용 방법을 기록한 것입니다. 문서 생성만으로 기존 앱에 자동 업데이트가 생기거나 기존 릴리스·파일명·CI가 전환되지는 않습니다. 실제 공개 파일과 업데이트 지원 여부는 각 릴리스 안내를 확인하세요. 활성 업데이트 목록은 검증된 구현·게시 준비 후 별도로 제공합니다.

앱 본체 소스, 사용자 설정·로그·계정 정보·토큰은 이곳에 게시하지 않습니다. 필요한 구성요소 고지·배포 자료는 각 앱의 기존 요구사항을 유지합니다.
