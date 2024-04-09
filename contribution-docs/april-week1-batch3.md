# 3차 과제 (마감: ~4/9 화)

* 아래 과제 가이드라인은 p5.js 프로젝트 리드 치안치안 예(Qianqian Ye)님 제공 원문을 한국어 스튜어드가 번역, 가공한 것입니다. 원문은 announcement > Discussion > [이 Discussion 포스트 (private)](https://github.com/orgs/p5-js-KO-Translation/discussions/8) 상에서 확인 가능합니다.

* 전체 번역 마감일이 4월 10일(수)이라 부득이하게 촉박한 일정으로 진행되는 점에 대해 재단측에서 양해를 구해왔습니다 ;)

* 4차 과제 관련: 4월 중순경 남은 번역을 마무리를 위한 소규모의 최종 4차 과제가 있을 수 있다고합니다! 자세한 정보는 재단에서 곧 공유할 예정입니다.


## 번역에 앞서

* 2024 > Discussions > ⭐[[p5.js KO] 음차 번역 표기, 어조 등 기준 제안](https://github.com/p5-js-KO-Translation/2024/discussions/6)⭐상 3월 2주차 연습과제상에서의 논의를 토대로 음차 번역 표기, 어조 등에 대해 정리해보았습니다. 이 디스커션 포스트는 프로젝트 기간 내내 지속될 예정이니 계속해서 댓글에서 의견 공유해요 :)!


## 기여자 문서 번역 (성함 표기: ~4/6 오늘)


기여자님들은 아래의 과제 할당 사항을 둘러보시고, 표에 ⭐성함을 오늘중(4/6)⭐으로 작성해주세요! 


### 1. p5.js 웹사이트 메뉴, About 페이지, Index 페이지 번역 (기여자님 1명 - "장윤영")

| PR | 1차 리뷰 | 2차 리뷰 | Approve | Merge |
|------|---|---|---|---|
| [p5.js 웹 번역 - 윤영님](https://github.com/bocoup/p5.js-website/pull/173) | 염인화 | 오세진 | | |

* 기존 [p5.js 웹사이트](https://p5js.org/ko) 번역을 유지, 수정하면 됩니다.

`github.com/bocoup/p5.js-website>...>content>ui` > [ko.yaml](https://github.com/bocoup/p5.js-website/tree/main/src/content/ui) 파일 수정, 번역
 
`github.com/bocoup/p5.js-website>...>text-detail>ko` > [about.mdx](https://github.com/bocoup/p5.js-website/tree/main/src/content/text-detail/ko) 파일 수정, 번역
 
`github.com/bocoup/p5.js-website>...>text-detail>ko` > [index.mdx](https://github.com/bocoup/p5.js-website/tree/main/src/content/text-detail/ko) 파일 수정, 번역 (index.mdx 파일 번역 범위: 11, 25, 29번째 줄만. 이 중 11번째 줄은 about.mdx의 11번째 줄과 동일합니다.)




### 2. 예제 Examples (기여자님 3명 - "이현우", "장예원","박민욱")

| PR | 1차 리뷰 | 2차 리뷰 | Approve | Merge |
|------|---|---|---|---|
| [예제 01 ~ 05 번역 - 현우님](https://github.com/bocoup/p5.js-website/pull/144) | 염인화 | 오세진 | ✅ | ✅ |
| [예제 06 ~ 10 번역 - 예원님](https://github.com/bocoup/p5.js-website/pull/167) | 염인화 | 오세진 | ✅ |  |
| [예제 11 ~ 15 번역 - 민욱님](https://github.com/bocoup/p5.js-website/pull/166) | 오세진 | 염인화 |  | |

 * 기존 [p5.js 웹사이트 예제](https://p5js.org/ko/examples) 번역을 유지, 수정하면 됩니다.
 * 번역 범위: 제목 title, 한줄 설명 one-line-description, 긴 설명 long description.

`github.com/bocoup/p5.js-website>...>` [examples>ko](https://github.com/bocoup/p5.js-website/tree/main/src/content/examples/ko) > 총 15개 폴더 내 `description.mdx` 파일들 수정, 번역

* "이현우" - `examples>ko` > 01 ~ 05 넘버링된 총 9개 폴더 내 `description.mdx` 파일들 수정, 번역

* "장예원" - `examples>ko` > 6 ~ 10 넘버링된 총 8개 폴더 내 `description.mdx` 파일들 수정, 번역

* "박민욱" - `examples>ko` > 11 ~ 15 넘버링된 총 8개 폴더 내 `description.mdx` 파일들 수정, 번역



### 3. 기존 번역한 `기여자 문서` 추가 작업 (기여자님 1명 - "박성훈")

| PR | 1차 리뷰 | 2차 리뷰 | Approve | Merge |
|------|---|---|---|---|
| [기여자 문서 추가 번역 - 성훈님](https://github.com/processing/p5.js/pull/6951) | 오세진 | 염인화 | | |

`github.com/processing` >...> [contributor_docs > ko](https://github.com/processing/p5.js/tree/main/contributor_docs/ko) 폴더 > [access.md](https://github.com/processing/p5.js/blob/main/contributor_docs/access.md) 전체 파일 복제, 번역 (* 기존 1차 과제와 동일한 깃허브 경로인 점 유의하세요!)

`github.com/processing` >...> [contributor_docs > ko](https://github.com/processing/p5.js/tree/main/contributor_docs/ko) 폴더 > 기존 번역한 아래 문서 4개 각각 1번째 줄에 <! --주석 처리 -->로 추가된 1줄 번역 (주석은 수정 모드에서 보입니다!) 
  * Contributor Guidelines
  * Steward Guidelines
  * Contributing to the p5.js Reference
  * WebGL Contribution Guide

    

## 위 문서 번역 기여 방법

* 동일 Org 내 커밋들에 한해 가능한 1개의 PR로 묶어주시면 좋겠습니다 :) PR 제목에 [p5.js KO] 헤딩 꼭 달아주세요! (없으면 풀리퀘 게시판에서 찾기 헷갈립니다😅)

* [풀 리퀘스트 및 리뷰 과정 안내](https://github.com/p5-js-KO-Translation/2024/discussions/7) 참고하셔서 진행하시면 됩니다.

* 과제 완료후 [우리 Org > Discussion> 8시간 달성 포스트](https://github.com/p5-js-KO-Translation/2024/discussions/10)에 업무 시간 로깅 댓글 꼭 달아주세요!

* 충분한 수정과 검토 작업을 거치는 한, 초벌 단계에서는 ChatGPT, 구글/파파고 번역기 등 활용 가능합니다.
