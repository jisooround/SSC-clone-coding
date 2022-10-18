# Slow Steady Club 클론 코딩

#### 선정 이유와 느낀 점
이 사이트는 레이아웃도 다양해서 CSS 학습에 도움이 될 것 같았고, 깔끔한 디자인이 마음에 들어 클론 코딩 주제로 선정하였습니다. HTML, CSS가 익숙하지 않았는데 `<footer>`로 가까워 질수록 다루는 실력이 조금 올라간 저를 발견했습니다. 🤭 그치만 아직도 부족한 부분이 많고, 해결하지 못한 부분도 많아 추후 실력이 더 높아진다면 수정을 하도록 하겠습니다. (JS 구현)

## 사이트
### 원본 사이트
https://slowsteadyclub.com

### 클론 사이트

---
## 작업 기간
2022년 10월 8일 ~ 10월 18일

---
## 기술 스택
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/SASS-CC6699?style=flat&logo=SASS&logoColor=white"/>

---
## 어려웠던 점 & 아쉬웠던 점
**메뉴 아이콘과 이미지 교차축 정렬**<br />
header .menu의 `search`,`brand` 텍스트와 아이콘을 교차축으로 중앙 정렬 하고싶었는데 `flex`로 `align-items: center;`를 하면 `cursor pointer`가 옆의 영역까지 활성화 되어 position으로 위치시켰습니다. flex로 정렬 시키고 싶었는데 안 되어서 이 부분에서 시간을 많이 지체했습니다.

![](https://velog.velcdn.com/images/mudidu/post/6d8c9289-7b8d-4f86-af61-2854f06c5fb4/image.png)

**달력 호버할 때 레이아웃 움직임**<br />
원본은 달력에 호버를 하면 레이아웃은 그대로인 상태로 파란 원형이 생기고 텍스트 크기가 커집니다. 제가 작업한 사이트에서는 호버할 때마다 레이아웃이 움직여집니다. 해결방법을 찾지 못해 결국 구현하지 못했습니다. 
![](https://velog.velcdn.com/images/mudidu/post/7de251ed-a6d9-474f-bdb0-0d41bcd780bb/image.png)

**오타로 인한 npm dev run 오류**<br />
npm 서버를 열어서 작업을 해보려고 parcel-bundler를 설치하고 서버를 열었는데 아래와 같은 오류가 나타났습니다. html문서에 제가 테스트해본다고 스타일을 적용시켰던 것이 지워지지 않은 상태여서 오류가 났습니다. 스타일을 제거하니 다시 정상적으로 작동되었습니다. 오타로 인해서 자주 문제가 발생했습니다. 😥
![](https://velog.velcdn.com/images/mudidu/post/9561cac6-6ec5-4811-ac94-35e6b4e11f06/image.png)

**SCSS**<br />
SCSS는 아직 다루기가 어려워서 그나마 익숙한 CSS로 먼저 작업을 한 후, 다시 SCSS로 변환하는 과정을 거쳤습니다. 역시나 어려워서 SCSS의 함수, 변수 같은 기능은 사용하지 못하고 중첩 작성법 위주로 사용하였습니다. 시간이 많이 걸렸지만 그래도 이 과정을 거치면서 중첩 작성이 조금 익숙해졌고, 옮기면서 불필요한 CSS 스타일 제거도하고, 필요 이상으로 길게 작성 된 class명을 수정하는 시간이 되었습니다.

---
## 리뷰해 주셨으면 하는 점
**불필요한 html 구조**<br />
대부분의 박스에 이미지와 텍스트가 들어가서 웬만하면 div태그로 감쌌는데 하다보니 너무 불필요한 부분도 감싸고있는거 아닌가? 라는 생각이 들었습니다. 불필요한 구조가 눈에 띄면 피드백 주시면 감사드리겠습니다!

**class명**<br />
class명도 내용에 관련되게 지어야하는데 가끔 너무 길어지거나 아니면 너무 함축되었을까봐 작성하면서도 걱정이 되었습니다. 이 부분 한번 확인해주시면 감사드리겠습니다.

**grid**<br />
저는 주로 배치를 할 때 flex와 position을 활용하였습니다. grid를 사용하지 않았는데 혹시 grid를 사용하면 더 좋았을 레이아웃이 있는지 알려주시면 감사드리겠습니다.
+추가로 position과 flex도 알맞게 잘 사용했는지 궁금합니다!

**가독성, 주석 부족한 점**<br />
전체적으로 가독성을 해치는 부분이 있는지와 주석도 부족한 점이 없는지 확인주시면 감사드리겠습니다! 🙇🏻‍♀️

