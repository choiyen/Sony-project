## 📖 Sony Fage 리뉴얼 프로젝트

- 배포 주소

---

![코딩온 웹 14기 팀플(웹 개척단)](https://github.com/user-attachments/assets/4d1c6184-c46a-4ff6-9c73-48ef38c6085d)

### 프로젝트 소개 및 주제 선정 이유
---
-  소니의 뿌리 사입은 음향기기 산업인데 반해, 홈페이지가 너무 많은 것을 담고 있어, 하나의 카테고리만을 전문적으로 다루는 웹페이지를 만들고자 했습니다.
-  소니라는 회사의 일대기 및 음향제품이 개발되어 온 일대기를 알 수 있습니다.
-  HTML과 CSS, JAVAScrpt의 기본기를 익히기엔 홈페이지 리뉴얼이 제격일 것 같아 선택하게 되었습니다.

### 팀원 구성
---
![image](https://github.com/user-attachments/assets/7b4f1e5b-4c7c-431e-b767-e8361e60fc35)

### 1. 게발 환경
---
- 사용한 언어 : HTML, CSS, JQuery, Javascript
- 디자인 툴 : Photoshop, Figma
- 사용한 라이브러리 : SWiper.js

### 2. 채택한 개발 기술 및 사용에 대한 반성
---
#### JavaScript
   - 키보드의 자판이나 마우스의 움직임에 따라 간단하게 화면을 변화시키는 방법을 배움.
   - 홈페이지 개발 당시, 2년의 공백기 후 다시 잡은지 한달 쯤 되던 시기라 사용에 미숙했던 부분이 보이는 것 같아 아쉽다.
   - 각각 테그들의 이름이나, 변수 명을 이해하기 쉽게 바꿔야 할 것 같다.
#### Swiper js
  - 자바스크립트에서 쉽게 슬라이더를 구현할 수 있도록 만들어진 라이브러리 중 하나이다.
  - 개발을 진행할 당시, 촉박한 개발 시간과 2년의 공백으로 인한 감각 저하로 인해 바닐라 코딩으론 슬라이더를 구현하기 어려워 라이브러리를 쓰고자했다.
  - 수많은 라이브러리 중에 꼭 Swiper js를 사용한 이유
     - Swiper js는 현재 실존하는 슬라이더 라이브러리 중 가장 오래되고, 사용하는 방법을 찾기 가장 쉬운 라이브러리이다.
     -  다양한 메소드 및 설정을 지원하기에 사용하기 편하다.
     -  react나 vue js 등 다양한 javacript에서 파생된 언어에서도 사용을 지원하기에 배워두면 좋을 것 같아서 선택했다.
#### 브랜치 전략
- main 브랜치과 개발자 별로 브랜치를 나누어 개발을 진행하였습니다.
- main 브랜치는 최종 결과물을 배포하기 위한 브렌치입니다.
- 각각의 develop 브렌치 들은 개발 단계에서 git-flow의 main 역할을 하는 브렌치입니다. 
- 브렌치 보호 룰을 설정하여, 다른 개발자의 동의 없이 main에 merge할 수 없도록 처리하였습니다.

---
### 3. 프로젝트 구조
![image](https://github.com/user-attachments/assets/6a17b543-53d9-44dc-9e93-f73000c2227e)

---
###  4. 내가 맡았던 역할
-  UI
   - 페이지 : 소니의 일대기, 소니의 제품별 연혁
- 기능
   - sWiper js를 사용한 슬라이더, 스크롤 시 연혁표의 화살표가 내려가는 기능, 연도 버튼 클릭시 이미지와 내용이 바뀌는 기능, 자세한 설명을 위한 모달창

 ---
 ### 5. 개발 기간 및 작업 관리
 
 #### 개발 기간
    - 전체 개발 기간 : 2024.09.27 ~ 2024.10.5(1주일)
    - 기획과 디자인 : 2024.09.27 ~ 2024.09.30(3일)
    - 1차 구현 : 2024.10.1 ~ 2024.10.2
    - 2차 구현 : 2024.10.3 ~ 2024.10.4
    - 반응형 구현 : 2024.10.5
###  작업 관리
- notion과 slack을 활용하여 개발 진행 상황을 공유했습니다.
- 매일 개발이 끝나기 30분 전에 현재의 개발 방향에 대한 고미을 나누고 그 내용을 notion에 기록하며, 개발을 진행했습니다.

### 6. 신경 썼던 부분 및 느낀점
내가 담당했던 연혁 페이지에서 가장 중요했던 건 슬라이더였다. 
사실 처음엔 바닐라 코딩으로 슬라이더를 먼저 만들었다. 
하지만, 만든 슬라이더를 넣은 이미지를 상상해봤을 때, 너무 기능적으로 단조롭다는 생각이 들었다. 
그래서 시간 관계상 라이브러리를 사용하기로 했던 것이다.
그렇게 해서 프로젝트를 만들고 보니, 생각보다 슬라이더를 정지시키고 사용자가 슬라이드 부분으로 마치 기차가 정거장에 섰다가 출발하는 것처럼 중간에 멈추게끔 구현하는 게 어렵진 않았을 거란 생각이 들었다.  
만들어 놓고 반응형을 하다가, 함수가 떠올랐다ㅠㅠㅠㅠㅠ 
처음부터 알고 있던 지식을 바탕으로 개발을 진행한 건 나쁘지 않았지만, 머리로 개발할 수 있었을 텐데, "라이브러리"를 쎴던 건 좋았다고 생각하진 않는다.
왜냐하면 지금은 퇴사 후 처음으로 프로젝트를 만드는 상황이었기에 직접 만들어보는 편이 훨씬 나았을 거라 아쉬움이 남았다.
내가 아무래도 소프트웨어 QA를 1년이상 경험했다보니, 은연중에 에러 코드가 발생할 만한 상황을 스스로 안만들지 않았을까? 솔직히 프로토타임을 개발하는데 있어, 함수가 생각과 달리 동작하는 에러는 어느정도 따올텐데 말이다.

---
### 7. 페이지별 기능

#### [메인화면] 
![메인페이지](https://github.com/user-attachments/assets/aaa570e2-4e41-445a-9e41-14a9214ce814)

- 메인페이지의 헤드폰이 스크롤 시 두번째 색션까지 따라와서 배치될 수 있도록 구현
- 메인 카테고리의 상품을 클릭 할 시 장바구니에 제품이 담기는 기능 구현

### [회사페이지] - 본인 담당

![연도표](https://github.com/user-attachments/assets/689b9aab-af12-4319-90c2-6f4842a6f448)

https://github.com/user-attachments/assets/2bd63b19-76c7-406e-80da-d8886803ed90

- 코드의 재사용성을 높이기 위해서 탭 버튼 부분과 이미지 슬라이드 부분 등 공통된 부분은 최대한 통일성을 가지도록 개발하였습니다.
- 이미지 슬라이드의 유동적인 방향과 속도를 구현하기 위해 Swiper JS 라이브러리 함수를 참조함.
- 이미지 교체 시 이미지 설명이 변경될 수 있도록 배열을 만들어 관리하였습니다.
- 제이쿼리를 사용하여, 이미지를 클릭했을 떄, 그림에 대한 설명이 alt에 추가되도록 구현


### [기술페이지]

https://github.com/user-attachments/assets/7dba47f1-a235-463d-b768-c5300d9132c4

- JS와 DOM을 최대한 활용하여, 이미지 컨텐츠가 스크롤 방향에 따라서 나타나고 사라지도록 구현
- 호환 가능한 어플들 아이콘에 마우스를 올리면 크기가 커지며 클릭 시 페이지 이동이 가능함.
    
---
### 8. 트러블 슈팅 및 어려웠던 점
- 연혁표의 반응형 구현
  연혁표를 모바일에 맞춰 화면을 줄여나갈 떄, 오른쪽에 있어야 할 그림이 연대표에 위치한 화살표 선을 넘어 영역을 침범하는 문제와, 화면의 크기를 줄였을 때 연혁표의 표시선 길이가 제대로 조절되지 않는 문제가 있었다.

https://github.com/user-attachments/assets/6a8c8079-2fa2-4a69-b012-7da9dcf04912

- 해결 방법
  다시 개발자 교육을 받은지 3주 정도 된 상황이어서, CSS를 작성할 때 px 단위로 정적으로 설정했던 게 문제였다. 화면의 크기가 변화함에 따라, 크기가 줄어들도록 하니 문제가 해결되었다.
 

---
### 9. 개선 목표
- 로그인 기능의 도입 : node js나 스프링을 사용하여 장바구니 기능에 한하여 
- 상품 결제 기능 : 실제 결제되면 안되겠지만, 장바구니가 구현되어 있는 만큼, 실제로 결제까지 진행되도록 만들 예정.
- 연혁표의 반응형 구현 : 연혁표 화면을 줄이면 그림이 균일하게 줄어들지 않음.
- 코드 간결화 : ejs를 사용해 반복이 가능한 부분은 줄일 예정.

### 10. 프로젝트 후기
- [1차 프로젝트 중간 후기] https://storys03.tistory.com/24
- [1차 프로젝트 최종 후기] https://storys03.tistory.com/25




    
    

