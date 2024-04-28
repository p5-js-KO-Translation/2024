# 4차 과제 (마감: ~4/30 화)

* 아래 과제 가이드라인은 p5.js 프로젝트 리드 치안치안 예(Qianqian Ye)님 제공 원문을 한국어 스튜어드가 번역, 가공한 것입니다. 원문은 announcement > Discussion > [이 Discussion 포스트 (private)](https://github.com/orgs/p5-js-KO-Translation/discussions/9) 상에서 확인 가능합니다.

## 번역에 앞서

* 2024 > Discussions > ⭐[[p5.js KO] 음차 번역 표기, 어조 등 기준 제안](https://github.com/p5-js-KO-Translation/2024/discussions/6)⭐ 이 디스커션 포스트에서 계속해서 댓글에서 의견 공유해요 :)



## 레퍼런스 문서 번역 (성함 표기: ~4/27 오늘)

* 해당 레퍼런스 리스트는 이 [스프레드 시트](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=1518816676)의 6개의 탭에서 확인하실 수 있습니다.
  1. Shape (28개)
  2. Events (31개)
  3. Foundation (11개)
  4. 3D (58개)
  5. Constants (7개)
  6. Transform (10개)
  
* 주의사항은 이 스프레드 시트에 없는 레퍼런스는 번역하지 않는 것입니다.(아직 스프레드 시트에 존재하지 않는 레퍼런스는 업데이트가 되지 않음)
  
* 총 128개의 레퍼런스를 기여자 5분에 맞게 탭 기준 각각 약 28개씩 나누어 아래 표에 기재하였습니다.

|시트 탭 기준 (범위)| 기여자 | PR 링크| 리뷰 | Approve |
|------------------|------------|------------|------------|------------|
| **기여자 1** <br> [Shape](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=1518816676) (28개) | 장윤영 | [PR](https://github.com/processing/p5.js-website/pull/287/commits) |  |  |
| **기여자 2** <br> [Events](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=1034791071)  (31개) | 박민욱 |  |  |  |
| **기여자 3** <br> [Foundation](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=1397595777) (11개) <br> [3D](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=1991454505) `처음부터 textureMode()까지` (18개) |  |  |  |  |
| **기여자 4** <br> [3D](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=1991454505) `textureWrap()부터 p5.Camera.perspective()까지` (28개) | 이현우 |  |  |  |
| **기여자 5** <br> [3D](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=1991454505) `p5.Camera.ortho()부터 끝까지` (10개) <br> [Constants](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=1444848743) (7개) <br> [Transform](https://docs.google.com/spreadsheets/d/1DolS86mQox2EHDEhihVCEoAvWB1Ti_6PP6CltFmx4wA/edit#gid=330392233) (10개)  |  |  |  |  |

* 기여자님들은 위의 범위들을 둘러보시고, 표에 ⭐성함을 오늘중(4/27)⭐으로 작성해주세요! (한 범위당 희망자가 2명 이상일 경우, 스튜어드가 별도 조정할 예정입니다.)

* 표 내 별도 링크(a tag)는 PC, 모바일 인터넷 환경상 확인 가능합니다. (모바일 깃허브앱만 안되네요 ㅠㅠ)

* Constants 탭의 레퍼런스는 [p5/constants](https://github.com/processing/p5.js-website/tree/main/src/content/reference/ko/p5/constants)에 위치합니다. - 주황색 하이라이트

* p5.Camera.XXX 레퍼런스와 p5.Shader.XXX 레퍼런스는 각각 [p5.Camera](https://github.com/processing/p5.js-website/tree/main/src/content/reference/ko/p5.Camera), [p5.Shader](https://github.com/processing/p5.js-website/tree/main/src/content/reference/ko/p5.Shader) - 초록색 하이라이트


## 위 문서 번역 기여 방법

* 각자 할당된 과제는 1개의 PR로 묶어주시면 좋겠습니다 :) PR 제목에 [p5.js KO] 헤딩 꼭 달아주세요! (없으면 풀리퀘 게시판에서 찾기 헷갈립니다😅)

* [풀 리퀘스트 및 리뷰 과정 안내](https://github.com/p5-js-KO-Translation/2024/discussions/7) 참고하셔서 진행하시면 됩니다.

* 번역 및 리뷰 진행 순서: 번역 작업(각자 할당된 mdx파일 번역 후 리뷰 요청) > 스튜어드 리뷰 및 코멘트 > 스튜어드 코멘트 및 수정 확인 후 승인 

* 빠른 번역을 위한 기존 p5.js 레퍼런스 페이지 번역문 재활용/수정 권장 참고자료: 
  1. [p5.js 한국어 레퍼런스 사이트](https://p5js.org/ko/reference)
  2. [한국어 색인 스프레드시트](https://docs.google.com/spreadsheets/d/1-MtLGTderpkHrWBLYVrGxprnquuvSH71a9u_TsU6uGc/edit#gid=0)

* 과제 완료후 [우리 Org > Discussion> 8시간 달성 포스트](https://github.com/p5-js-KO-Translation/2024/discussions/10)에 업무 시간 로깅 댓글 꼭 달아주세요!
  
* 충분한 수정과 검토 작업을 거치는 한, 초벌 단계에서는 ChatGPT, 구글/파파고 번역기 등 활용 가능합니다.

