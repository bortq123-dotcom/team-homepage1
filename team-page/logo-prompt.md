# 에이또팀 로고 제작 프롬프트

## 1. 기본 프롬프트

```text
에이또팀 팀의 로고를 만들어 줘.
차콜 글자와 절제된 틸 포인트, 단순한 아이콘 + 팀 이름,
흰 배경, 정사각형.
아이콘은 접힌 문서와 체크 표시를 간결한 도형으로 표현해 줘.
글자는 정확히 "에이또팀"으로 넣어 줘. 에 / 이 / 또 / 팀 네 글자야.
문서 아이콘 왼쪽, 팀 이름 오른쪽으로 가로 배치해 줘.
작은 크기에서도 읽히는 깔끔한 한글 글꼴을 써 줘.
추가 문구, 영문 표기, 인증 마크, 입체 효과는 넣지 말아 줘.
```

세부 색은 사용자가 선택한 '깔끔한 느낌'을 바탕으로 정한 디자인 가정이다. 차콜 `#182126`, 틸 `#0F766E`, 흰색 `#FFFFFF`를 사용한다.

## 2. 아이콘 아이디어

| # | 아이디어 | 이유 | 적용 |
|---|---|---|---|
| 1 | 접힌 문서 + 체크 표시 | 서류를 정리하고 요청을 확인하는 팀의 성격을 표현 | 이번 로고에 사용 |
| 2 | 나란히 정돈한 문서 두 장 | 서류 작업의 일관성과 협업을 표현 | 대안 |
| 3 | 문서 모서리를 감싼 열린 프레임 | 요청 내용을 빠짐없이 담는다는 인상을 표현 | 대안 |

## 3. 다시 만들 때 쓸 문장

- "문서 아이콘을 더 단순하게 하고 선 두께를 통일해 줘."
- "아이콘만 따로, 글자 없이 만들어 줘."
- "팀 이름은 정확히 에이또팀으로 유지하고 글자 굵기를 조금 줄여 줘."
- "흰 배경과 같은 배치를 유지하고 포인트 색만 바꿔 줘."

## 4. 생성 결과

- 생성일: 2026-11-06
- 생성 방식: 내장 `image_gen` 도구로 신규 이미지 생성
- 최종 파일: `images/logo.png`
- 형식: 흰 배경의 정사각형 PNG, 문서·체크 아이콘과 '에이또팀' 한글 워드마크
- 확인: 생성 이미지를 보고 팀 이름 표기와 아이콘 구성을 확인했다.
- 사용 위치: 제작 승인 후 홈페이지 헤더와 소개 영역에 사용한다. 정사각형 파일의 여백을 고려해 원본 비율을 보존한다.
- 참고 화면: 제공되지 않아 PRD의 디자인 가이드를 따른다.

이미 로고를 생성해 저장했으므로 별도 이미지 업로드는 필요하지 않다. 홈페이지 `index.html`은 기획 검토와 제작 확인을 받은 뒤 만든다.

## 5. 실제 생성에 사용한 최종 프롬프트

아래 내용 전체를 내장 이미지 생성 도구에 전달했다. 배경 투명도 옵션은 `false`였다.

```text
Use case: logo-brand. Create a finished, clean logo for a Korean team that helps its members request work-plan document preparation. Asset type: website brand logo, a single square logo artwork, not a mockup or a sheet of variations. Exact Korean text, verbatim: "에이또팀". Spell it exactly 에 이 또 팀, with no spaces in the final text. Style: minimalist, flat, precise vector-like shapes, simple dark charcoal Korean sans-serif wordmark, medium-weight readable lettering. One small distinctive icon combining a folded document page and a neat check mark, expressing well-organized documents, not an official certification seal. Color palette: charcoal #182126 with a restrained teal #0F766E icon accent, pure white background. Composition: one centered compact horizontal lockup, icon to the left and the exact Korean team name to the right; balanced proportions and generous whitespace around the lockup. Strong legibility at small sizes. No English text, no tagline, no extra text, no gradients, no 3D, no shadows, no texture, no watermark.
```
