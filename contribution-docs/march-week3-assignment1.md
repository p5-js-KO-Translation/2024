# 1차 과제 (마감: ~3/20 수)

* 아래 과제 가이드라인은 p5.js 프로젝트 리드 치안치안 예(Qianqian Ye)님 제공 원문을 한국어 스튜어드가 번역, 가공한 것입니다. 원문은 announcement > Discussion > [이 Discussion 포스트 (private)](https://github.com/orgs/p5-js-KO-Translation/discussions/6) 상에서 확인 가능합니다.

## 번역에 앞서

* 2024 > Discussions > ⭐[[p5.js KO] 음차 번역 표기, 어조 등 기준 제안](https://github.com/p5-js-KO-Translation/2024/discussions/6)⭐상 3월 2주차 연습과제상에서의 논의를 토대로 음차 번역 표기, 어조 등에 대해 정리해보았습니다. 이 디스커션 포스트는 프로젝트 기간 내내 지속될 예정이니 계속해서 댓글에서 의견 공유해요 :)!


## 기여자 문서 번역 (성함 표기: ~3/14 오늘)

* 프로세싱 재단 Github Organization인 `processing > p5.js > contributor_docs` 는 p5.js 기여자 문서(Contributor Docs) 모음 폴더입니다. 말그대로, p5.js repo상 기여할 수 있는 방법을 안내하는 문서들입니다. 현재 기여자 문서는 contributor_docs의 하위 폴더에서 스페인어(es), 힌두어(hi), 중국어(zh), 슬로바키아어(sk), 한국어(ko) 등으로 번역되어있고, 거의 모든 문서는 MD파일로 작성됩니다.
  
* 그 중, 우리가 작업할 폴더는 당연히⭐[contributor_docs > ko 폴더](https://github.com/processing/p5.js/tree/main/contributor_docs/ko)⭐입니다. 폴더에 현존하는 문서 대다수는 2020년 이소은 [@mojosoeun](https://github.com/mojosoeun)님이 번역한 바 있습니다. 

* 2024년 한국어 번역 기여자님 5명은 올해 새로 추가된 총 4개의 원문 MD파일을 나누어 번역합니다:
  * [Contributor Guidelines](https://github.com/processing/p5.js/blob/main/contributor_docs/contributor_guidelines.md) (5239 단어)
  * [Steward Guidelines](https://github.com/processing/p5.js/blob/main/contributor_docs/steward_guidelines.md) (4194 단어)
  * [Contributing to the p5.js Reference](https://github.com/processing/p5.js/blob/main/contributor_docs/contributing_to_the_p5.js_reference.md) (2549 단어)
  * [WebGL Contribution Guide](https://github.com/processing/p5.js/blob/main/contributor_docs/webgl_contribution_guide.md)  (1250 단어)

* 기여자님들은 위의 파일 4개를 둘러보시고, 아래의 표에 ⭐성함을 오늘중(3/14)⭐을 작성해주세요! (한 문서당 희망자가 2명 이상일 경우, 스튜어드가 별도 조정할 예정입니다.)
  
|파일명(범위)| 번역 희망 기여자 성함 |
|---------|---|
|Contributor Guidelines (처음 ~ [Using GitHub Desktop](https://github.com/processing/p5.js/blob/main/contributor_docs/contributor_guidelines.md#using-github-desktop) 블록까지) (약 2619 단어)| (장윤영) 1명       |
|Contributor Guidelines ( [Using the git command line interface](https://github.com/processing/p5.js/blob/main/contributor_docs/contributor_guidelines.md#using-the-git-command-line-interface) 블록 ~ 문서 끝까지) (약 2619 단어)| (장예원) 1명      |
|Steward Guidelines (처음 ~ [Main build task](https://github.com/processing/p5.js/blob/main/contributor_docs/steward_guidelines.md#main-build-task) 블록 중 코드 `connect:server` 직전까지) (약 2722 단어)| (박성훈) 1명      |
|Steward Guidelines ([Main build task](https://github.com/processing/p5.js/blob/main/contributor_docs/steward_guidelines.md#main-build-task) 블록 중 코드 `connect:server` 다음 문장 ~ 끝까지) + WebGL Contribution Guide (전체) (약 2722 단어)| (이현우) 1명    |
|Contributing to the p5.js Reference (전체) (2549 단어)| (성함) 1명    |

* 표 내 별도 링크(a tag)는 PC상 확인 가능합니다.

* 오늘(3/14)까지 작성된 성함 표기를 토대로 할당한 뒤, 추가 안내드리겠습니다!
  
* 형평성을 위해, 이번 주차에 다른 분들에 비해 조금 더 많은 분량을 번역하신 기여자님들에게는 다음주차에 적은 분량의 글 번역이 우선 권장됩니다~~^^ 기여자님별 번역 단어 카운팅은 우리 Google Drive Folder > [이 스프레드 시트](https://docs.google.com/spreadsheets/d/1ZOFNFKoJa8uLTPz2se3VxikT9q735q3U3-rxGlMkZjo/edit#gid=0)에 별도 기록하겠습니다!  

## 위 문서 번역 기여 방법

* 번역 범위: 제목(headings), 본문 텍스트만 입니다. (* 코드와 코드 블록, 이미지 대체 텍스트(alt text) 제외)

* 이번 과제는 상기된 프로세싱 재단 Github Organization인 `processing > ... > contributor_doc > ko`에 ⭐여러분이 직접 새로운 MD파일을 생성, 풀 리퀘스트(Pull Request)⭐하는 식으로 진행됩니다. (* 우리 Org가 아닙니다!)

* 하나의 MD 파일을 2인이상 번역하는 경우

  * 해당 파일 앞부분을 번역하시는 분이 아래의 가이드라인에 따라 MD 파일을 먼저 생성, 영어 원문을 복붙후 커밋합니다.
  * 1차 커밋 완료후 나머지 번역은 추가 커밋으로 진행해주시면 됩니다.

* 자세한건 우리 Github Organization > 2024 > Discussions > ⭐[[p5.js KO] 풀 리퀘스트(Pull Request) 및 리뷰 과정 안내](https://github.com/p5-js-KO-Translation/2024/discussions/7)⭐ 상의 기여 방법을 참고하시고, 전체 번역 PR과 리뷰는 3/20(수)까지 진행합니다! 질문은 언제든 스튜어드에게 공유해주세요😊

* 충분한 수정과 검토 작업을 거치는 한, 초벌 단계에서는 ChatGPT, 구글/파파고 번역기 등 활용 가능합니다.

