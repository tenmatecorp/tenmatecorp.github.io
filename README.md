# tenmatecorp.github.io

TenMate(텐메이트) 앱 안내 사이트. GitHub Pages로 게시한다.

| 파일 | 주소 | 용도 |
|---|---|---|
| `index.html` | https://tenmatecorp.github.io/ | 첫 화면(앱 이름, 한 줄 소개, 링크). 스토어 등록정보의 "웹사이트" 칸 주소 |
| `privacy.html` | https://tenmatecorp.github.io/privacy.html | 「큰글씨 초성퀴즈 - 하루 열 문제」 개인정보처리방침. Play Console 방침 칸 + 앱 안 링크 |
| `privacy.html#delete` | https://tenmatecorp.github.io/privacy.html#delete | 개인정보 삭제 요청 방법(데이터 보안 양식이 주소를 물을 때) |
| `.nojekyll` | - | Jekyll 변환을 끄고 파일을 그대로 게시 |
| `app-ads.txt` | https://tenmatecorp.github.io/app-ads.txt | **아직 없음** - 아래 참고 |

## app-ads.txt (아직 만들지 않음)

- 애드몹 앱 등록(2026-11-04 예정) 뒤, 애드몹 화면 [앱] → [모든 앱 보기] → app-ads.txt 안내에 나오는 **한 줄을 그대로 복사해서** 이 저장소 맨 위에 `app-ads.txt` 파일로 추가한다.
- 줄 모양은 `google.com, pub-<게시자 ID 16자리>, DIRECT, <애드몹 화면에 나오는 값>`이다. **게시자 ID는 애드몹 화면에서만 가져오고 추측해서 쓰지 않는다.**
- 애드몹은 스토어 등록정보의 "개발자 웹사이트"(https://tenmatecorp.github.io) 맨 위에서 이 파일을 찾는다(https://support.google.com/admob/answer/9363762). 인식 여부는 앱이 스토어에 공개되고 애드몹에 연결된 뒤 애드몹 화면에서 확인한다.

## 게시 전 확인 (운영 메모)

1. `privacy.html`에서 `[대표 실명]`, `[시행일]`을 채웠는지 - 대괄호 `[`가 남아 있으면 게시하지 않는다.
2. 방침을 고치면 회사 문서(`출시/261005_개인정보처리방침_초안.md`)도 같이 고치고, 시행일·"이전 버전" 줄을 갱신한다(이전 내용은 커밋 기록으로 남는다).
3. 게시 후 휴대폰 크롬으로 두 주소를 열어 본다(밝은/어두운 모드, 큰 글씨, 표가 세로 카드로 보이는지).
4. 외부 스크립트·글꼴·분석 도구를 넣지 않는다(방침의 "분석 도구 없음"과 맞춤).
