---
layout: post
title: 주니어 프론트엔드 개발자의 채용 프로세스 참여 후기
description: 주니어 프론트엔드 개발자가 함께 일할 파트너를 구하기 위한 여정에 대해 소개합니다.
image: /images/front/post/2021-07-01-zum-front-recurit-review/0-thumbnail.png
introduction: 주니어 개발자인 필자가 함께 일하게 될 신입 개발자 분들을 모시는 과정에 대해 소개하는 글입니다.
category: portal/tech
tag: [프론트엔드, 채용, recurit, javascript]
author: junilhwang
---

> 본 포스트는 기술적인 내용이 아닌, 주니어 개발자인 필자가 함께 일하게 될 신입 개발자 분들을 모시는 과정에 대해 소개하는 글입니다.

<p style="text-align: right">
  <img style="margin: 0; display: inline-block;" src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fzuminternet.github.io%2Fzum-front-recurit-review%2F&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=%EC%A1%B0%ED%9A%8C%EC%88%98&edge_flat=true" alt="조회수" />
</p>

## 1. 변화, 그리고 모집

올해 들어 줌인터넷에는 굉장히 많은 변화가 있었습니다. 먼저 [줌 닷컴](https://zum.com)의 대대적인 개편이 있었습니다. `Spring Boot` 로 작성 된 레거시 프로젝트를 버리고, `nodejs` + `vuejs` 를 적용하면서 거의 모든 것을 갈아엎었습니다.

- 개편 전 줌닷컴

![1](/images/front/post/2021-07-01-zum-front-recurit-review/1.png)

- 현재 줌 닷컴

![2](/images/front/post/2021-07-01-zum-front-recurit-review/2.png)

그리고 줌 닷컴의 개편을 시작으로 [뉴스줌](https://news.zum)도 개편하여 6월에 오픈했고, 이어서 `쇼핑줌`, `허브줌`도 개편 예정입니다. 뿐만 아니라 현재 `테크핀 서비스`도 만드는 중입니다.

문제는 개편에 참여할 수 있는 프론트엔드 개발자가 없었습니다. 줌인터넷엔 `필자`와 필자의 `사수`만 전문적인 프론트엔드 업무를 수행하고 있었기 때문입니다.

**팀장님에서 CTO가 되어버린 개발실장님**과 상의하여 신입/경력 구분하지 않고 모든 지원서를 받기로 결정하였고, 3월 초에 `프론트엔드 개발자 채용 공고`를 올렸습니다. 포털개발팀에서 이렇게 **프론트엔드 개발자를 모집 하는 경우가 처음**이었기 때문에 무척 설렜습니다.

그런데 문제는 생각보다 이력서가 굉장히 많이 들어왔습니다.

- 글을 쓰면서 정리해보니 한 달도 안 되는 기간 동안 대략 200명 정도 지원해주셨습니다.

이력서를 보는 것 자체가 하루 업무가 될 정도로 너무 많이 들어와서 고민이 커졌습니다. 일단 1차적으로 실장님이 이력서를 보고 괜찮다 싶으면 저에게 토스해주셨고, 제가 봐도 괜찮은 이력서라면 다시 실장님께 전달하여 통과하는 형태로 진행했습니다.

## 2. 고민

그런데 무수히 많은 이력서를 보면서 든 생각은 `아쉬움` 이었습니다. 요즘 교육기관도 무척 많다보니 대부분의 이력서 기술스택이 획일적으로 통일되었는데 이력서만으로 괜찮은 파트너가 되리라 판단하는 것 자체가 어려웠습니다. 지원자 입장에서도 이렇게 획일적으로 통일되어가는 이력서들 속에서 자신이 작성한 이력서가 정말 괜찮은 이력서인지 판단이 될까요?

### (1) 기술스택의 통일

대부분의 이력서에는 다음과 같은 기술 스택이 적혀져있습니다.

- React
- React Hooks
- Next.js
- Typescript
- Redux, Redux-saga, Mobx, Recoil 등의 상태관리 프레임워크 사용
- scss
- webpack, babel

### (2) 학원 혹은 교육기관

대부분의 신입 개발자들은 `교육기관(혹은 학원)`에서 진행한 `팀프로젝트` 를 포트폴리오와 개인적으로 진행한 **TodoList 수준**의 포트폴리오 첨부했습니다. 이러한 경우 실력을 판단하기가 정말 쉽지 않습니다.

거의 대부분의 이력서가 비슷한 양상을 띄고 있기 때문에 면접을 봐도 다 똑같을 것 같은 느낌이 들었습니다.

### (3) 실장님의 인재상

그런데 실장님이 원하는 수준의 개발자는 ~~(절대 제가 원하는 개발자가 아닙니다!)~~ 다음 조건을 충족해야 합니다.

- 전공자거나 전공자 수준의 CS 지식을 갖춰야 함
  - 알고리즘은 엄청 잘하지 않아도 상관 없음
  - 네트워크나 운영체제 관련 지식이 어느 정도는 있어야 함
- 기술에 대한 거부감이 없어야 함
  - FrontEnd와 BackEnd를 구분 하지 않고 서비스 개발을 위해 필요한 기술을 바로 바로 습득할 수 있어야 함
- 실무적인 능력(구현 능력)이 좋아야 함
  - 이론만 빠삭한 사람을 너무 많이 봐서 못미더움
  - 따라서 구현 능력도 당연히 필요해야 함
  - 구현이 느린 경우는 팀에 적응할 수 없음
- 멘탈이 강한 사람
  - 장애가 발생했을 때 당황하지 않고 원인을 빠르게 탐색할 줄 알아야 함
  - 장애가 오래 지속되더라도 침착함을 유지해야 함
- 커뮤니케이션 능력이 좋아야 함
  - 사실 요즘 개발자들이 갖춰야 하는 기본적인 서브 스킬
- ~~마지막으로 관상~~

~~**실장님, 이 자리를 빌어 말씀드립니다. 그런 사람은 이미 네카라쿠배로 다 갔어요!!**~~

그런데 아무리 봐도, 지금 들어오는 이력서를 토대로 면접까지 갔을 때 구직자 분들과 실무진 모두 실망할 일이 너무 많을 것 같다는 느낌이 들었습니다.

## 4. 채용 과제

앞선 고민을 토대로 `채용과제`를 만들면 어떨까? 생각하게 되었고, 실장님도 좋다고 하여 빠르게 과제를 구성했습니다.

채용 과제를 통해 판단하고자 하는 역량은 다음과 같습니다.

- Javascript를 얼마나 깊게 알고 있는가.
- 프레임워크의 내부적인 동작을 정확하게 이해하고 있는가.
- 간단한 프레임워크를 만들 수 있는 수준인가.
- Single Page Application의 개념에 대해 이해하고 있는가.
- Webpack, babel, typescript 등을 사용하기 위한 환경을 혼자서 구축할 수 있는가.
- Webpack, babel, typescript를 사용하는 목적에 대해 알고 있는가.
- NodeJS로 간단한 API를 구축할 수 있는가.
- Network에 대해 조금이나마 이해하고 있는가.
- 도구를 선택하는데 조사를 하는가.

이러한 역량을 판단하기 위해선 먼저 프레임워크를 버려야했습니다.
우리가 사용하는 프레임워크는 무척 편리하지만, **그만큼 핵심적인 내용을 제대로 파악할 시간까지 단축해주기 때문**입니다.
그래서 프레임워크를 제대로 이해하기 위해 제일 좋은 방법은, 직접 프레임워크를 따라 만들어 보는 것이라고 생각했습니다.

다음은 과제 내용의 일부입니다.

> **(1) 필수 요구사항**
> - Front-End
>   - **구현에 필요한 프레임워크 및 라이브러리 절대 사용 금지**
>   - webpack + babel를 이용하여 개발환경 구축하기
>   - 컴포넌트 기반 설계
>     - **본인이 직접 할 것. 타인의 코드 사용 금지. 타인의 코드를 사용할 경우 배점 없음.**
>     - Core를 만든 후에, 이를 사용하는 형태로 작성할 것
>     - 상태(State)를 기반으로 렌더링하는 형태로 작성할 것
>       ![10](/images/front/post/2021-07-01-zum-front-recurit-review/10.jpg)
>     - 설계는 자신 있는 형태(객체지향 or 함수지향)로 해주세요!
>   - SPA(Single Page Application)기반
>     - **페이지간에 이동이 발생할 때 새로고침이 발생하지 않도록 한다.**
>     - Router 만들어서 사용해보기
>     - 새로고침을 했을 경우에도 현재 페이지의 내용을 유지해야 한다.
>   - 전역 상태관리를 위한 Store 만들기: Vuex 혹은 Redux 등과 같은 상태관리 프레임워크 직접 만들어서 사용해보기
>   - 이벤트 최적화
>     - 불필요한 이벤트는 해제하기
>     - [이벤트 위임](https://ko.javascript.info/event-delegation) 사용하기
>   - XHR(ajax) 관련: API **요청중(loading)/실패(fail)** 등에 대한 UI 처리
>   - localstorage 사용: 즐겨찾기 데이터는 localstorage에 저장한다.

과제를 만들면서 다시 고민이 생겼습니다.

- 과제의 내용이 신입 지원자에겐 무척 어렵습니다.
  - 친구들에게 의견을 구했더니 **그럴꺼면 너네회사를 왜 지원하냐?** 라는 이야기를 듣고 납득했습니다.
  - 하지만 선택의 여지가 없었습니다.
  - 다시 이 자리를 빌어 지원해주신 모든 분들께 감사인사를 전합니다 🙇‍♂️
- 과제를 열심히 풀이하여 제출하고 탈락했을 때의 **상실감 + 허탈감**
  - 단순히 알고리즘 테스트라면 적게는 1시간, 많게는 3시간 정도만 투자하면 되지만 이러한 종류의 과제는 **생각보다 더 많은 시간이 소요**됩니다.
  - 그렇게 시간을 투자해서 떨어졌을 경우 회사의 갑질로 느껴질 수 있고 좋지 않은 인상을 줄 수 있습니다.

저는 채용 프로세스에 참여하는 모든 분들을 만족시킬 순 없겠으나, **적어도 이 회사에 지원하길 잘했다라는 생각을 하게 하고 싶었습니다.**

그래서 과감하게 **모든 지원자에게 상세한 코드리뷰**를 하기로 다짐했습니다.

![3](/images/front/post/2021-07-01-zum-front-recurit-review/3.png){:style="border: 1px solid #000"}

## 5. 과제 안내 및 채점

과제를 만들기 이전에는 이력서 하나를 두고 무척 고민했으나, 과제를 만든 후에는 역량이 있어 보이는 분들에게 특별한 고민 없이 과제 안내 메일을 보냈습니다. 앞서 언급한 200명의 지원자 중 **총 35명**에게 메일을 보냈고, 그 중 **15명이 과제를 제출**했으며, **20명은 포기**했습니다. 아무래도 과제 자체의 난이도가 있기 때문에 **(아마 신입을 뽑는 회사 중 제일 어렵지 않았을까요?)** 포기하는 사람이 반 절이 넘은게 아닌가 싶습니다.

제가 경험했던 채용 과제들은 대체로 피드백이 빈약하거나 왜 합격했고 왜 떨어졌는지 알 길이 없었습니다. 면접까지 가더라도 과제에 대해 물어본 경험이 없었기 때문에 실망스러웠던 적이 무척 많았습니다.

그래서 필자는 줌인터넷에 지원하는 분들에게 **구체적인 피드백을 드리기 위해 채점표를 만들었습니다.**

![4](/images/front/post/2021-07-01-zum-front-recurit-review/4.png)

이렇게 채점표를 만들고나니 오히려 지원자의 역량을 객관적인 지표로 나타낼 수 있어서 빠르게 필터링이 가능했습니다.

![5](/images/front/post/2021-07-01-zum-front-recurit-review/5.png)

대체로 40점 이상의 점수를 받은 분들의 경우 기본 지식이 탄탄하게 잡혀 있었다고 생각합니다.

![6](/images/front/post/2021-07-01-zum-front-recurit-review/6.png)

비고에 채점 항목에 대한 간단한 코멘트를 남겼으며,

![7](/images/front/post/2021-07-01-zum-front-recurit-review/7.png)

어떤 분들은 과제의 난이도를 고려해서 참고 링크로 달아놓은 포스트의 코드를 그대로 복사하여 사용하기도 했습니다.

확실한건 채점표 덕분에 지원자 분들의 역량을 객관적인 지표로 나타낼 수 있었다는 점입니다. 그리고 과제를 제출한 지원자 분들에게 직접 채점표를 전달하여 스스로 부족한 부분을 판단할 수 있도록 안내했습니다.

## 6. 코드리뷰

채점을 완료한 후에 코드리뷰를 진행했습니다. 코드리뷰를 어떤 방식으로 진행할까 고민하다가 그냥 github에 올렸습니다.

먼저 main branch는 비어있는 형태로 만들고, 지원한 순서대로 비번호를 부여하여 branch를 만들어서 전체 코드를 push했습니다. 그 다음에 PR을 올려 전체 코드에 대해 리뷰를 남겼습니다.

![8](/images/front/post/2021-07-01-zum-front-recurit-review/8.png)

최대한 꼼꼼하게 리뷰를 남기려고 노력했고, 코드 뿐만 아니라 설계나 개발환경에 대해 한 층 더 고민할 수 있도록 피드백을 남겼습니다.

대체로 과제 하나를 리뷰할 때 1시간 ~ 2시간 정도 걸렸습니다. 리뷰가 쌓여갈수록 나름 리뷰하는 속도가 붙어서 크게 어렵진 않았습니다. 다만 채용을 진행할 당시에 일이 그냥 너무 많아서 힘들었을 뿐.. ~~다시는 돌아가고 싶지 않은 어드민 지옥~~

그리고 과제를 제출한 지원자분들에게 이메일로 **코드리뷰 링크**와 **채점표**를 전달했습니다.

![9](/images/front/post/2021-07-01-zum-front-recurit-review/9.png)

## 7. 면접

과제를 어느 정도 잘 풀이한 분들은 바로 실무진 면접을 진행했습니다. 면접 과정은 다음과 같습니다.

### (1) 자기소개

- 먼저 실무진에 대해 소개했습니다.
- 그리고 지원자의 짧은 자기소개를 들었습니다.

### (2) 라이브 알고리즘 테스트

- 자기소개가 끝난 후 긴장하지 않는다면 쉽게 풀이할 수 있는 알고리즘 문제를 소개했습니다.
- 그리고 지원자분이 실시간으로 알고리즘 문제를 풀이하는 과정을 지켜봤습니다.

### (3) 풀이한 과제를 토대로 한 기술 질문

- 알고리즘 테스트가 끝나면, 풀이한 과제에 대해 간단하게 리뷰를 진행했습니다.
- 과제에 적용한 설계 기법이나 혹은 개선이 필요한 부분 등에 대해 질문하는 형태로 진행했습니다.

### (4) 기술면접

- 먼저 면접에서 물어볼만한 체크리스트를 쭉 정리했습니다.
- 지원자가 공부했을 법한 것들 위주로 질문했습니다.
- 다양하게 많이 알고 있는 것을 평가하기보단, 한 가지라도 제대로 공부했는가를 유심히 살폈습니다.
- 그래서 꼬리물기 형태의 질문을 많이 했습니다.

### (5) 인성면접

- 인성 면접은 실장님이 진행해주셨는데, 이 부분은 대외비이므로 생략하겠습니다.

면접 과정에서 아쉬웠던 점은, 앞선 과제 채점표처럼 면접 질문에 대한 체크리스트를 만들어서 점수를 매기는 형태가 아니다보니 **객관적인 지표를 만들진 못했습니다.** 지금 돌이켜 생각해보면 지원자분에게 불합격 결과를 안내할 때 기술면접과 관련된 부분도 어느 정도 피드백을 주면 어땠을까 생각해봅니다.

그러나 이러한 피드백이 오히려 안 좋을 수 있다는 시니어 개발자분의 말도 동시에 생각납니다. **우리는 평가를 하는 것이지 교육을 하는게 아니다** 라고 하셨는데 이 부분도 무척 와닿는 말이었습니다. 어느 정도의 선이 적당할까요? 저도 주니어 개발자이기 때문에 계속 고민이 필요함을 느낍니다.

## 8. 최후의 3인

실장님이 제일 먼저 눈여겨본 지원자가 있었는데, 과제는 잘 풀이 했으나 산업기능요원이라서 면접까진 가지 못했습니다. 줌인터넷의 경우 병역특례업체긴 하지만, 전문연구요원만 가능하고 이스트소프트로 가야 산업기능요원이 가능했습니다. 함께할 수 있었다면 좋아겠으나.. 인연이 아니었나봅니다.

각설하고, 현재 줌인터넷으로 모시게 된 세 분의 면접 과정에 대해 소개합니다.

차례대로 `A님`, `B님`, `C님` 이라고 명칭하겠습니다.

### (1) 비전공 + 장교 + 또래 보다 늦은 데뷔

- A님의 경우 30대 초반에 개발을 시작했다고 들었습니다.
- 면접 때 정말 많이 공부한게 느껴졌습니다.
- 질문한 것들에 대해 대체로 상세하게 답변해 주셨고, 꼬리물기식 질문에도 당황하지 않고 명확하게 답변주셨습니다. 앞선 면접 과정에선 느낄 수 없었던 희열을 느꼈습니다.
- 만약 나였다면 A님 처럼 열심히 할 수 있었을까? 하는 고민을 면접을 진행하는 내내 했던 것 같습니다.
- 면접 내용도 좋았지만, A님이 과제를 풀이하면서 정리한 내용도 좋았습니다. 기술에 대해 확실하게 조사하고 선택하는 모습이 인상적이었습니다.

저는 A님 정도의 실력이라면 여기 보다 더 좋은 곳으로 갈 수 있었다고 생각합니다. 그런데 생각보다 나이가 벽이 되는 경우가 많았다고 들어서 안타까웠습니다.

### (2) 비전공 + 면접을 즐기는 자

- B님의 경우 이력서부터 아이덴티티가 느껴졌습니다.
- 과제를 취업 때문에 풀었다는 느낌보단 재밌어서 풀었다는 느낌을 받았습니다.
- 면접 질문에 대해 오히려 역으로 질문을 해주시는(?) 특이한 경험을 했습니다.
- 거의 스터디가 아닐까 싶을 정도로 면접을 즐기는 모습이 인상적이었습니다.
- 사실 면접 질문에 대해 확실하게 대답하지 못한 부분들이 조금 있었으나, 이를 상쇄할 정도로 기술에 대한 흥미도가 높은게 느껴졌습니다.
- 어쩌다보니 다른 분들과의 면접은 1시간이 걸렸는데, B님과는 1시간 30분이 걸렸습니다.

B님은 항상 긍정적인 에너지가 뿜뿜 넘쳐 흐르는게 느껴집니다. 이런 분과 같이 일하면 즐거울 것 같아서 좋았습니다.

### (3) 디자인 복수전공 + 경력 같은 신입

- C님의 경우 신입이라고 생각할 수 없을 정도로 기술적인 역량이 뛰어났습니다.
- 본 전공은 디자인인데, 복수전공으로 CS를 이수하셨습니다.
- 그래서 UX/UI에 대한 감각이 좋은 편입니다.
- 모든 면접 질문에 군더더기 없이 답변했고, 항상 침착하고 안정적인 느낌을 받았습니다.
- 과제 점수가 제일 높았습니다.

C님이야 말로 실장님이 찾던 인재상이라고 생각합니다. ~~네카라쿠배님들 감사합니다.~~ 프론트엔드 뿐만 아니라 그냥 개발을 잘 하고 즐기는 분인게 느껴집니다.

---

이렇게 좋은 분들을 줌인터넷으로 모실 수 있어서 참 다행이라고 생각합니다.

세 분이 1주일 간격으로 입사를 했고, 줌인터넷 최초로 세 분이 콜라보레이션 파일럿 프로젝트를 진행했습니다. 조만간 파일럿 프로젝트 관련 포스팅도 올라올 예정이니 기대해주세요!

프로젝트 코드 미리보기 → [https://github.com/zuminternet/investing-app-clone](https://github.com/zuminternet/investing-app-clone)

## 9. 끝맺으며

### (1) 채용 프로세스에 참여하면서 다짐했던 것

저는 모든 지원자분이 채용 과정에서 항상 존중 받고 있다고 느끼게 하고 싶었습니다.
제가 일면이 없는 지원자 분들에게 해드릴 수 있는 최선은,
한 회사의 직원이 아닌 개발에 몸을 담고 있는 한 사람으로서,
먼저 개발을 시작한 선배로서,
적어도 채용 과제에 대해서는 디테일 하게 평가하고 더불어 디테일한 피드백을 전달하는 것이라고 생각했습니다.

그리고 결국 내가 원하는 팀, 내가 원하는 문화는 스스로 만들어 가는 것이라고 생각합니다.
문화를 만들어갈 사람들이 필요하고, 이에 대한 시작점이 채용이라고 생각했습니다.
그래서 비록 힘든 과정이었지만, 과제도 만들고, 채점도 하고, 코드리뷰도 하고, 이렇게 포스팅까지 하고 있는 것이지요.
장기적으로 봤을 때 이러한 과정들이 결국 좋은 팀을 만들어가는 과정이라고 생각합니다.

저는 제가 근무하고 있는 이 팀이 무척 좋습니다.
그래서 더 좋은 문화를 만들어가고 싶고,
서로에게 긍정적인 영향을 줄 수 있는 분들을 모시고 싶었습니다.

### (2) 아쉬웠던 점

사실 특별하게 아쉬운 점은 없었습니다. 이런 채용 프로세스를 통해서 좋은 분들을 모실 수 있었고, 저 또한 성장할 수 있었습니다. 굳이 한 가지를 뽑자면, 기술면접이 일관성이 없었다는 것 정도?

다음 기술면접은 조금 더 일관성 있게 평가하고, 면접 결과와 관계 없이 지원자에게 피드백을 줄 수 있을 정도로 면접 내용을 잘 정리하여 전달하고자 합니다. 결국 지원자 전체의 역량이 높아질수록 이 업계에 더 활력이 생기는게 아닐까요?

### (3) 다음을 기대하며

현재 프론트엔드 개발자가 더 필요한 상황이라서 이러한 채용 프로세스를 다시 진행중입니다. 이번에도 꼭 좋은 분을 모실 수 있도록 노력 중이랍니다.

그리고 언제가될지 모르겠으나 **채용공고는 빠른 시일 내에 열릴 예정**입니다. 

긴 글 읽어주셔서 감사합니다 🙇‍♂️