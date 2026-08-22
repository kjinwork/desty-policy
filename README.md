# desty-policy

Desty 모바일 앱의 개인정보처리방침(Privacy Policy)을 호스팅하는 저장소입니다.

- **개인정보처리방침 URL:** https://kjinwork.github.io/desty-policy/
- 앱: Desty (`com.desty.desty`)
- 페이지 소스: [`index.html`](index.html) — 한국어/영어, 브라우저 언어에 따라 기본 표시

GitHub Pages는 이미 켜져 있습니다 (`main` 브랜치 / 루트). `index.html`을 고쳐서
푸시하면 잠시 뒤 위 URL에 반영됩니다.

## 이 URL을 넣는 곳

- **App Store Connect** — 앱 정보 → 개인정보 처리방침 URL
- **Google Play Console** — 앱 콘텐츠 → 개인정보처리방침

## 내용을 고칠 때

방침은 앱이 실제로 하는 일과 일치해야 합니다. 특히 App Store Connect의 App Privacy
설문, Play Console의 데이터 안전 섹션과 어긋나면 심사에서 문제가 됩니다.
현재 문서가 전제하고 있는 앱 동작은 이렇습니다.

| 항목 | iOS | Android |
| --- | --- | --- |
| 광고 | 없음 (SDK 미초기화) | Google AdMob 배너 |
| 클라우드 사본 | 사용자의 iCloud 키-값 저장소 | 사용자의 구글 계정 (Auto Backup) |
| 앱 삭제 후 | 클라우드 사본은 남음 (재설치 시 복원) | 동일 |
| 개발자 서버 | 없음 | 없음 |
| 자체 네트워크 요청 | `maps.app.goo.gl` 단축 링크 펼치기 하나 | 동일 |

앱 쪽에서 위 표에 해당하는 동작이 바뀌면 이 문서도 같이 고쳐야 합니다.
