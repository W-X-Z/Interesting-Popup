# Interesting-Popup · 관심그룹 팝업 빠른 종목정보 프로토타입

토스·카카오페이의 "10초 요약 / 왜 움직였을까" 컨셉을 관심그룹 팝업에 적용한 아이디어·인터랙션 프로토타입 모음입니다.

## 🔗 데모 (GitHub Pages)

- 허브: https://w-x-z.github.io/Interesting-Popup/
- v3 · 최근 소식 카드(최신): https://w-x-z.github.io/Interesting-Popup/v3/
- v2 · ①왜 움직였을까 / ②10초 요약: https://w-x-z.github.io/Interesting-Popup/v2/
- v1 · 아이디어 13종 탐색: https://w-x-z.github.io/Interesting-Popup/v1/

## 버전

| 버전 | 설명 |
|------|------|
| **v3** | 기존 앱 룩앤필 그대로 + 팝업 내 `최근 소식` 카드만 자연스러운 접힘/펼침으로 개발. 펼치면 차트가 실제로 아래로 밀리고, 항목별 근거가 2단 아코디언으로 열림. |
| **v2** | `①왜 움직였을까` `②10초 요약` 두 아이디어 완성본. 카드/행 탭 인터랙션 + 실제 캡처 겹쳐보기(키보드 `C`)로 영역 정합 확인. |
| **v1** | 아이디어 13종을 한 화면에서 비교하는 탐색용 프로토타입. |

## 구조

```
index.html      # 버전 탐색 허브
v1/index.html   # 13 아이디어
v2/index.html   # 1·2번 인터랙션 (+ v2/assets/screen.png)
v3/index.html   # 최근 소식 카드 (최신)
```

레퍼런스(이노테크 469610) 기반 더미 데이터입니다. 모든 페이지는 빌드 과정 없이 정적 HTML/CSS/JS로 동작합니다.
