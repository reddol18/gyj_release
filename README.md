# gyj_release

모바일 SRPG **후삼국궁예전**(안드로이드)의 **업데이트 배포 전용** 저장소입니다.
게임 소스는 이 저장소에 없습니다.

## 무엇이 있나

[Releases](https://github.com/reddol18/gyj_release/releases)의 첨부 파일만 씁니다.

| 파일 | 뜻 |
|---|---|
| `bundle-<version>.zip` | 앱이 내려받아 다음 실행 때 갈아 끼우는 웹 내용물 |
| `version.json` | 최신 판의 매니페스트 — 버전 · zip 주소 · SHA-256 · 요구 APK versionCode |

앱은 `https://github.com/reddol18/gyj_release/releases/latest/download/version.json`을
읽어 지금보다 새로운 판이면 zip을 받습니다. 네이티브가 바뀐 판은 새 APK로만 냅니다.

APK 자체는 itch.io에서 배포합니다.
