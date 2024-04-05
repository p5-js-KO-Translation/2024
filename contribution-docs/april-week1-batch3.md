# 3차 과제 (마감: ~4/9 화)

* 아래 과제 가이드라인은 p5.js 프로젝트 리드 치안치안 예(Qianqian Ye)님 제공 원문을 한국어 스튜어드가 번역, 가공한 것입니다. 원문은 announcement > Discussion > [이 Discussion 포스트 (private)](https://github.com/orgs/p5-js-KO-Translation/discussions/8) 상에서 확인 가능합니다.

* 전체 번역 마감일이 4월 10일(수)이라 부득이하게 촉박한 일정으로 진행되는 점에 대해 재단측에서 양해를 구해왔습니다 ;)

* 4월 중순경 남은 번역을 마무리를 위한 소규모의 최종 4차 과제가 있을 수 있다고합니다! 자세한 정보는 재단에서 곧 공유할 예정입니다.


## 번역에 앞서

* 2024 > Discussions > ⭐[[p5.js KO] 음차 번역 표기, 어조 등 기준 제안](https://github.com/p5-js-KO-Translation/2024/discussions/6)⭐상 3월 2주차 연습과제상에서의 논의를 토대로 음차 번역 표기, 어조 등에 대해 정리해보았습니다. 이 디스커션 포스트는 프로젝트 기간 내내 지속될 예정이니 계속해서 댓글에서 의견 공유해요 :)!


## 기여자 문서 번역 (성함 표기: ~4/6 오늘)


1. p5.js 웹사이트 메뉴, About 페이지, Index 페이지 번역 (기여자님 1명 - "성함A")
* 기존 [p5.js 웹사이트](https://p5js.org/ko) 번역을 유지, 수정하면 됩니다.

1) `github.com/bocoup/p5.js-website>...>content>ui` > [ko.yaml](https://github.com/bocoup/p5.js-website/tree/main/src/content/ui) 파일 수정, 번역

2) `github.com/bocoup/p5.js-website>...>text-detail>ko` > [about.mdx](https://github.com/bocoup/p5.js-website/tree/main/src/content/text-detail/ko) 파일 수정, 번역

3) `github.com/bocoup/p5.js-website>...>text-detail>ko` > [index.mdx](https://github.com/bocoup/p5.js-website/tree/main/src/content/text-detail/ko) 파일 수정, 번역
* index.mdx 파일 번역 범위: 11, 25, 29번째 줄만. 이 중 11번째 줄은 about.mdx의 11번째 줄과 동일합니다.

* "성함A" 기여자님은 아래 3번도 함께 진행하시면 됩니다! 

2. 예제 Examples (기여자님 3명 - "성함B", "성함C", "성함D")

1) `github.com/bocoup/p5.js-website>...>` [examples>ko](https://github.com/bocoup/p5.js-website/tree/main/src/content/examples/ko) 폴더 내 총 15개 파일 수정, 번역
* 기존 [p5.js 웹사이트 예제](https://p5js.org/ko/examples) 번역을 유지, 수정하면 됩니다.
* 번역 범위: 제목 title, 한줄 설명 one-line-description, 긴 설명 long description.

2) "성함B" - 01 ~ 05 총 6개 폴더 내 파일 수정, 번역
3) "성함C" - 06 ~ 10 총 6개 폴더 내 파일 수정, 번역
4) "성함D" - 11 ~ 15 총 6개 폴더 내 파일 수정, 번역

3. 기존 번역한 `기여자 문서` 추가 작업 (기여자님 1명 - "성함A")

1) `github.com/processing` >...> [contributor_docs > ko](https://github.com/processing/p5.js/tree/main/contributor_docs/ko) 폴더 > [access.md](https://github.com/processing/p5.js/blob/main/contributor_docs/access.md) 파일 복제, 번역 (* 기존 1차 과제와 동일한 깃허브 경로인 점 유의하세요!)

2) `github.com/processing` >...> [contributor_docs > ko](https://github.com/processing/p5.js/tree/main/contributor_docs/ko) 폴더 > 기존 번역한 아래 문서 4개 각각 1번째 줄에 <! --주석 처리 -->로 추가된 1줄 번역 (주석은 수정 모드에서 보입니다!) 
  * Contributor Guidelines
  * Steward Guidelines
  * Contributing to the p5.js Reference
  * WebGL Contribution Guide 
  
* 기여자님들은 위의 범위들을 둘러보시고, 표에 ⭐성함을 오늘중(4/6)⭐으로 작성해주세요! (한 범위당 희망자가 2명 이상일 경우, 스튜어드가 별도 조정할 예정입니다.)
  
* 형평성을 위해, 지난 주차에 다른 분들에 비해 조금 더 많은 분량을 번역하신 기여자님들에게는 이번주차에 적은 분량의 글 번역이 우선 권장됩니다~~^^ 기여자님별 번역 단어 카운팅은 우리 Google Drive Folder > [이 스프레드 시트](https://docs.google.com/spreadsheets/d/1ZOFNFKoJa8uLTPz2se3VxikT9q735q3U3-rxGlMkZjo/edit#gid=0)에 별도 기록해두었습니다!

## 위 문서 번역 기여 방법

* [풀 리퀘스트 및 리뷰 과정 안내](https://github.com/p5-js-KO-Translation/2024/discussions/7) 참고하셔서 진행하시면 됩니다.

* PR 제목에 [p5.js KO] 헤딩 꼭 달아주세요! (없으면 풀리퀘 게시판에서 찾기 헷갈립니다😅)

* 충분한 수정과 검토 작업을 거치는 한, 초벌 단계에서는 ChatGPT, 구글/파파고 번역기 등 활용 가능합니다.

## 4차 과제 (예정)

 Please note that we might have an additional small final 4th batch to wrap up some left-over translation around mid April, which we will share more info soon.
