<div style="width: 100%; display: flex; justify-content: center;">
  <img src="/experiences/viva-republica/cover.jpeg" alt="Toss" style="width: 100%; max-width: 400px; margin-bottom: 24px;">
</div>

토스는 월 1300만 이상의 유저가 사용하는 핀테크 슈퍼앱으로, 이 곳에서의 제 역할은:

- 만 7세 ~ 만 18세 유저를 타겟하는 Teens Team에서 일했습니다.
  - 월 170만명 이상의 유저들이 사용하는 웹 제품 전체를 혼자서 개발 및 유지보수 했습니다.
  - 제품 디자인에 대해 기술적인, 그리고 유저 경험과 관련된 피드백을 적극적으로 제공했습니다.
  - 제품 내에서 기술적인 개선 포인트를 주도적으로 찾아 해결했습니다.
  - 팀 전체의 업무 생산성 향상을 위한 개선 포인트를 주도적으로 찾아 해결했습니다.
  - 팀 목표, 제품 개발 방향성 등 비즈니스 레벨의 피드백을 적극적으로 제공했습니다.
- 팀 업무 바깥으로 전사적인 개발자 생산성 향상에 기여했습니다.
  - 새로운 지식 또는 문제 해결 과정에 대해서 적극적으로 문서화하여 공유했습니다.
  - 100명이 넘는 프론트엔드 개발자들이 사용하는 공용 라이브러리 전체의 운영에 기여했습니다.
  - 조직 내에서 기술적으로 통일되지 못한 것들에 대한 표준 확립을 리드했습니다.

# 기술적인 기여

- 토스 내부에서 사용하는 라이브러리를 오픈소스화한 [Slash](https://github.com/toss/slash) 프로젝트의 메인테이너로 기여했습니다.
  - [기여한 PR 및 Issue 목록](https://github.com/toss/slash/issues?q=involves%3Ahoseungme)
- 코드를 작성하며 좋은 아이디어가 생기면 프론트엔드 공통 라이브러리에 추가하고, 기존의 라이브러리에서 불편한 부분은 수정하여 개발 생산성에 기여했습니다.
  - [@toss/storage](https://github.com/toss/slash/tree/main/packages/common/storage) ([문서](https://slash.page/ko/libraries/common/storage/README.i18n))
- 기술 수준과 생산성을 높히기 위한 지식들을 정리하여 공유했습니다.
  - [CommonJS와 ESM에 모두 대응하는 라이브러리 개발하기: exports field](https://toss.tech/article/commonjs-esm-exports-field)
    - 토스에서는 개발 생산성 극대화를 위해 수많은 코드를 라이브러리로 만들어 관리하고 있습니다.
    - 이때 라이브러리가 정상적으로 동작하기 위해서, 더 나아가 프론트엔드 퍼포먼스를 위해서도 가장 중요한 Node.js의 모듈 시스템에 대한 지식을 공유했습니다.
  - [라이브러리 번들링 개선 과정: 커맨드 한 줄로 번들링 끝내기](https://blog.hoseung.me/2023-07-22-improve-library-bundling)
    - 지금까지 수많은 라이브러리를 만들며 얻은 번들링에 대한 경험을 공유했습니다.
    - 특정 번들링 방식의 한계와 개선 과정이 담겨 있습니다.
  - [Next.js가 서버 사이드에서 모듈을 읽는 방식](https://github.com/hoseungme/wiki/blob/b16bad3a6736091ed80752edb6fa9dca6c0cb9be/front-end/nextjs/server-side-module-resolution/ko.md)
    - 회사에서 개발하던 중 겪은 문제의 원인을 깊게 파악한 과정을 공유했습니다.
    - 해당 문제와 관련된 Next.js와 Webpack 코드를 전부 읽는 과정이 담겨있습니다.
  - [transform: rotate() + filter: blur() 퍼포먼스 개선 (feat. 레이어, 합성)](https://github.com/hoseungme/wiki/blob/b16bad3a6736091ed80752edb6fa9dca6c0cb9be/front-end/css/improve-transform-rotate-filter-blur-performance/ko.md)
    - 사이드 프로젝트를 하면서 겪은 브라우저 렌더링 퍼포먼스 문제를 개선한 과정을 공유했습니다.
    - 모던 브라우저의 레이어, 합성에 대한 지식이 담겨있습니다.
  - [Date는 어떻게 주고 받는게 바람직할까요?](https://blog.hoseung.me/2023-03-23-how-to-transfer-date)
    - 토스 대부분의 서버에서 Date를 응답할 때 타임존 정보가 누락되어 있었습니다.
    - 타임존을 명시하지 않아서 생긴 조직 내의 사례, 타임존을 명시하지 않았을 때 생기는 문제점들, 타임존을 지키면 얻을 수 있는 것들을 정리하여 공유했습니다.
    - 각 팀별로 새로운 API에 대해서는 타임존을 명시하는 방향으로 점진적인 개선이 시작되었습니다.
  - ...

# Teens Team

## 해냄 저금통/덕질 저금통

- 목표를 설정하고 그 목표를 위해 돈을 모으는 제품입니다. 단순히 목표만 설정하고 돈을 모으는 해냄 저금통과, 좋아하는 아이돌, 스포츠 선수, 웹툰, 애니메이션 등을 위해 저금을 하는 덕질 저금통으로 종류가 나뉩니다.
- 해냄 저금통 대표 이미지 생성 스크립트를 개발했습니다.
  - 해냄 저금통을 생성할 때에는 이모지와 배경색을 선택하여 저금통의 대표 이미지를 만들게 됩니다.
  - 그 대표 이미지는 하나의 이미지 파일로 만들어져 있는 것이 아닌, 배경을 렌더링하고 그 위에 이모지를 렌더링하는 방식이었습니다.
  - 이때, 토스 앱 홈의 계좌 섹션에서 유저가 가진 해냄 저금통의 목록을 보여줘야 하는 요구사항이 있었습니다.
    - 홈은 Server Driven UI에 기반하고 있었고, 계좌 목록은 각 계좌의 대표 이미지 URL을 받는 스펙으로 구현되어 있었습니다.
    - 즉, 홈 팀(외부 팀)에서 새로운 스펙 개발이 필요했고, 그에 따른 앱 버전 분기도 필요했습니다.
  - 따라서 대표 이미지를 생성하여 S3에 업로드하는 작업을 하게 되었습니다.
    - 이모지는 약 3000개 정도이고, 선택 가능한 대표 이미지의 배경 색은 8개로 고정되어 있으므로, 동적으로 생성할 필요 없이 로컬에서 전부 생성하여 업로드하여도 충분한 양이었습니다.
    - 토스는 자체 이모지인 [토스페이스](https://toss.im/tossface)를 사용하고 있어서, 토스페이스 이미지 파일과 배경색 이미지를 합성하도록 스크립트를 작성했습니다.
    - 이모지를 토스페이스 이미지의 파일명으로 변환하는 과정에서 [이모지가 유니코드로 표현되는 방식](https://blog.hoseung.me/2022-08-25-emoji-and-unicode)에 대해 배웠고, 이미지 합성에는 [sharp](https://sharp.pixelplumbing.com) 라이브러리를 사용했습니다.
- 브라우저 버그로 인해 디자인 요구사항을 충족하지 못하고 타협할 수도 있었지만, 끝까지 해결 방법을 찾아내 일정에 맞추어 구현했습니다.
  - 실시간 채팅 메시지 같은 느낌을 주기 위해 스크롤 방향을 거꾸로 해야하는 요구사항이 있었습니다.
  - 이때 Safari에서 `flex-direction: column-reverse`인 경우 생기는 심각한 렌더링 버그가 있었지만, [끊임없이 렌더링 버그를 우회할 방법을 탐구하여 해결](https://github.com/hoseungme/wiki/blob/main/front-end/browser/safari-flex-direction-column-reverse-scroll-and-rendering-issue/ko.md)했습니다.
  - 하지만 위의 방법으로 해결하고 나니 터치가 끝나면 스크롤이 바로 멈춰버려 부자연스러운 문제가 있었습니다.
  - 따라서 이후 CSS Transform을 사용한 터치 스크롤러 오픈소스인 [flickable-scroll](https://github.com/hoseungme/flickable-scroll)을 직접 개발하여 서비스에 적용했습니다.

<div style="width: 100%; display: flex; flex-flow: row wrap; justify-content: center">
  <div style="position: relative; min-width: 300px; width: 50%; height: 315px">
    <div style="width: 100%; height: 100%; background-color: black"></div>
    <iframe src="https://www.youtube.com/embed/Lo-si7UopVQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; width: 100%; height: 100%"></iframe>
  </div>
  <div style="position: relative; min-width: 300px; width: 50%; height: 315px">
    <div style="width: 100%; height: 100%; background-color: black"></div>
    <iframe src="https://www.youtube.com/embed/OfK0HXn7hRo"  title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; width: 100%; height: 100%"></iframe>
  </div>
</div>

## 토스유스카드 3D 리소스 용량 92% 개선

- 토스유스카드 발급 화면에서는 `three.js`를 사용해 카드를 3D로 렌더링하여 유저에게 실제로 카드를 보면서 고르는 경험을 주고 있습니다.
  - **카드는 단순한 평면이라는 특징**에 무색하게 토스유스카드 3D 모델 파일의 용량은 심각하게 큰 문제가 있었습니다.
    - 토스유스카드는 5종류로 이루어져 있는데, 각각의 모델 용량은 2MB ~ 7MB 사이로, **총합하면 21.5MB 였습니다**.
  - 따라서 리서치를 통해 [Draco](https://github.com/google/draco)라는 구글에서 개발한 3D 모델 압축기를 찾아 사용하게 되었습니다.
    - 여러 번의 테스트를 거쳐 3D 모델 외관이 손상되지 않는 선에서의 최저점을 찾아 압축했습니다.
  - 결과적으로 토스유스카드 3D 모델 파일들의 총합 용량이 **21.5MB (22016KB) -> 1820KB 로 대단히 개선**되었고, 즉 유저들의 **네트워크 비용을 약 92% 가까이 절약**해줄 수 있었습니다.
  - 압축된 모델 적용 이후 전후 비교를 해보았을 때, 외관도 손상되지 않고 그대로 유지된 것을 확인했습니다.

<div style="width: 100%; display: flex; flex-flow: row wrap; justify-content: center">
  <div style="position: relative; min-width: 300px; max-width: 560px; width: 50%; height: 315px">
    <div style="width: 100%; height: 100%; background-color: black"></div>
    <iframe src="https://www.youtube.com/embed/A7M6lioKRMI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; width: 100%; height: 100%"></iframe>
  </div>
  <div style="position: relative; min-width: 300px; max-width: 560px; width: 50%; height: 315px">
    <div style="width: 100%; height: 100%; background-color: black"></div>
    <iframe src="https://www.youtube.com/embed/ddGYG_xyirI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; width: 100%; height: 100%"></iframe>
  </div>
</div>

## 토스 모의 주식 투자

- 증권 서비스를 사용할 수 없는 10대를 위해, 주식 투자를 간략하게 만들어 제공한 제품입니다.
- **첫 매수 전환율**을 올리기 위한 이터레이션을 성공적으로 마무리했습니다.
  - 기존에는 처음 들어온 유저에게 첫 매수를 유도하면서, 모든 종목을 보여주었습니다.
  - 다만 처음 들어오기도 했고, 주식을 어려워할 가능성도 높은 유저에게 **무턱대고 너무 많은 선택지를 주고 있어 이탈할 가능성이 높다**는 문제가 있었습니다.
  - 따라서 **유저가 관심 분야를 선택하면, 그 분야와 관련된 종목을 추천해주는 방식으로 개선**하였고, 결과적으로 **첫 매수 전환율이 17% 증가**하는 큰 성공을 이루었습니다.
- [숫자가 올라가는 애니메이션을 직접 구현](https://github.com/hoseungme/wiki/blob/main/front-end/uiux/implement-rolling-number-component-in-react/ko.md)하여 실시간 주가 제공에 알맞는 생동감 있는 UX를 제공했습니다.

<div style="width: 100%; display: flex; justify-content: center">
  <div style="position: relative; max-width: 560px; width: 100%; height: 315px">
    <div style="width: 100%; height: 100%; background-color: black"></div>
    <iframe src="https://www.youtube.com/embed/uxJIEwMhCb0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; width: 100%; height: 100%"></iframe>
  </div>
</div>

## 편의점 택배 예약하기

- 토스앱 내에서 GS25, CU 편의점 택배를 예약할 수 있는 제품입니다.
- 일정 금액을 할인해주는 프로모션을 매달 진행했는데, 이때 생기는 비효율적인 상황을 개선했습니다.
  - 초기에는 프로모션이 어떤 형태로 진행될지에 대해 예측이 가지 않아 프론트엔드 코드에 하드코딩 하는 방식으로 진행했습니다.
  - 다만 프로모션을 여러번 진행하며 어느 정도 동일한 형태를 띄게 되었고, 매번 요청을 받아 하드코딩하여 배포하는 작업이 비효율적으로 느껴졌습니다.
  - 따라서 디자인을 고정하여 템플릿화 하고, 해당 템플릿을 채워넣는 JSON 데이터 포맷을 정해 에디터에서 누구나 수정할 수 있도록 만들었습니다.
  - 이로써 프로모션 세팅에 프론트엔드 배포가 필요하지 않게 되었고, 팀원들이 다른 작업에 더욱 집중할 수 있게 되어 생산성이 증가했습니다.

## 토스 치킨 대회

- 입사 후 처음 개발한 제품으로, 만 7세 ~ 만 18세 유저들의 신규 가입과 리텐션 증가를 유도하기 위한 이벤트 제품입니다.
- 기술적으로는 [데이터 응답을 적절한 형태로 정규화](https://blog.hoseung.me/2022-06-02-normalization-for-intuitive-component/)하는 등, 직관적으로 이해되는 코드를 작성하기 위해 노력했습니다.
- 기본적으로 10대가 서로 단합할 수 있는 제품에 반응이 크다는 점을 공략하여, 수많은 신규 유저를 데려올 수 있었던 제품입니다.
- 반응이 워낙 좋다 보니 여러번 오픈하여 진행하게 되었는데, 유저가 재미를 잃지 않도록 점수를 쌓는 방식을 계속 바꾸어 갔습니다.
  - 가장 마지막 토스 치킨 대회는 포켓몬 고에서 영감을 받아, 아래와 같이 눈덩이를 던져 박을 터뜨려 점수를 얻는 게임을 구현했습니다.
  - 순수 자바스크립트 로직으로 구현하였고, 투사체가 날아가는 것이 최대한 자연스럽게 보이도록 아래와 같은 기준을 세워 수많은 테스트를 거쳤습니다.
    - 어느 정도 속도로 touch move가 일어났을 때 투사체가 던져진 것으로 판단할 것인지
    - 투사체가 던져진 방향이 얼마나 벗어나야 목표물에서 빗나갔다고 판단할 것인지
    - 목표물을 향해 투사체가 잘 던져진 경우, 어느 정도 속도로 자연스럽게 이동시킬 것인지, 포물선을 그릴 것인지
    - ...

<div style="width: 100%; display: flex; justify-content: center">
  <div style="position: relative; max-width: 560px; width: 100%; height: 315px">
    <div style="width: 100%; height: 100%; background-color: black"></div>
    <iframe src="https://www.youtube.com/embed/kJXQZrcpNMw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; width: 100%; height: 100%"></iframe>
  </div>
</div>
