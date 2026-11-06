# 에이또팀 홈페이지

팀원을 위한 작업계획서 작성 요청 **입력 체험** 홈페이지입니다. 사용자가 제공한 디자인 MD의 사진 중심 구성, 큰 제목, 검정·흰색·옅은 회색 UI, 둥근 검정 버튼을 반영했습니다.

## 열기

- 비공개 게시 주소: [에이또팀 홈페이지](https://eitto-team-workplan-1106.sk-telecom-k-3129.chatgpt.site). 소유자의 ChatGPT 로그인이 필요합니다.
- 로컬에서 열기: 이 폴더의 `index.html`을 브라우저로 엽니다. `images/`와 `fonts/` 폴더를 함께 유지하세요.

## 체험하기

1. **요청 체험하기**로 이동합니다.
2. 닉네임·작업명·가상 작업구역·작업 예정일을 입력합니다. 빈 폼에서 **예시로 채워보기**를 눌러 시작할 수도 있습니다.
3. **내용 확인**에서 입력 내용을 검토하고 **수정하기**로 고칩니다.
4. **체험 완료**로 마친 뒤 **다시 작성하기**로 초기화합니다.

입력은 현재 화면에서만 유지되고 새로고침하면 사라집니다. 실제 담당자에게 요청을 전달하지 않습니다.

## 제작 파일

| 파일 | 용도 |
|---|---|
| [index.html](index.html) | CSS·JavaScript가 포함된 홈페이지 |
| [images/logo.png](images/logo.png) | 에이또팀 로고 |
| [images/hero-workplan.png](images/hero-workplan.png) | 가상의 작업계획서 준비 장면을 담은 생성 사진 |
| [logo-prompt.md](logo-prompt.md) | 내장 image_gen으로 생성한 로고의 최종 프롬프트 |
| [image-prompt.md](image-prompt.md) | 내장 image_gen으로 생성한 히어로 사진의 최종 프롬프트 |
| [prd.md](prd.md) / [build-plan.md](build-plan.md) | 기획과 구현 계획 |
| [verification.md](verification.md) | 데스크톱·모바일 확인 내용과 게시 결과 |
| [fonts/LICENSE.txt](fonts/LICENSE.txt) | 로컬 Pretendard 글꼴의 SIL OFL 라이선스 |

게시용 소스는 `site/`, 게시 아카이브는 `site-deploy.tar.gz`에 보관했습니다. 로고와 사진은 내장 이미지 생성 도구로 만든 자산이며 실제 팀원이나 실제 사업장 사진을 사용하지 않았습니다.
