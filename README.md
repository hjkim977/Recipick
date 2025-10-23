# 🍽️ Recipick - 레시피 공유 플랫폼 🍽️
### 🖥️ 냉장고에 있는 재료로 만드는 음식 레시피 공유 사이트

<br>

- 제일 먼저 보이는 화면
![image](https://github.com/user-attachments/assets/f5d28c72-996e-49f0-b5a2-610e3b66ff92)
<br>

- 로그인을 했을 때 보이는 화면
![image](https://github.com/user-attachments/assets/5ff0bf6d-a23c-4959-98cc-afaddf5dd735)
<br><br/>


## 프로젝트 소개
- **요리 보기** : 자신의 레시피를 업로드하고 공유하는 공간
- **재료 무료 나눔** : 남는 재료를 무료로 나눔하며 나눔을 원하는 사람은 채팅하기 버튼을 눌러 나눔자와 채팅하고 재료를 나눔 받는 공간
- **요리 실험 일지** : 일반 레시피 보다는 색다른 음식들을 만들어 일기 형태로 공유하는 공간
- **요리 지식인** : 요리에 관하여 궁금한 점이 있으면 물어보고 댓글을 통해 답변을 받아 동일한 궁금증을 갖고 있는 분들에게 도움을 주는 공간
- **AI 추천 레시피** : 최대 5개까지 재료를 넣을 수 있고 입력 받은 재료를 통해 AI가 색다른 레시피를 추천해주는 공간
- 저희 사이트는 로그인을 해야 모든 기능을 이용할 수 있습니다.
<br><br/>


## 팀원 구성
|이은택|김혜지|
|---|---|
|![image](https://github.com/user-attachments/assets/3cea9f8f-c401-412b-9ca3-7d7cb82a1ef6)|![image](https://github.com/user-attachments/assets/855687a1-4765-4492-abca-119cca7fe9af)|
|[@hoya9802](https://github.com/hoya9802)|[@hjkim977](https://github.com/hjkim977)|

<br><br/>


## ERD
![image](https://github.com/user-attachments/assets/42ba3db3-7c21-4ce2-9b15-e9ebfcc406fb)
<br><br/>


## WBS
![image](https://github.com/user-attachments/assets/a5e34e62-f3c6-4488-8399-257d74553cb0)
<br><br/>

## 개발 환경
![image](https://github.com/user-attachments/assets/195b709a-6936-440c-adaf-65aa005e8070)

- Front-end : Vue.js, HTML, CSS, Bootstrap
- Back-end : Python, Django, drf
- 환경 : docker
- 데이터베이스 : postgresql
- 협업 툴 : Git, Discord
<br><br/>

## 개발 방식
### 1. TDD
![tdd-ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/aed017e2-f78e-406b-bf24-b6daf94c93b1)

- 거의 모든 곳에 TDD를 작성하였다. TDD를 통해 새로 만든 기능이 기존에 있는 기능을 해치지 않는지 현재 만든 기능에는 오류가 없는지 등을 확인한다.
<br><br/>

### 2. Flake8
![image](https://github.com/user-attachments/assets/bbfd30d7-dd39-427e-aa44-0e2185513ccc)

- 코딩 스타일이 서로 다르기 때문에 하나로 통일 시키기 위해 flake8을 사용했다. flake8을 하면 git action에서 알아서 테스트를 해주며 오류가 난 부분과 메세지를 알려준다.
<br><br/>

### 3. Git
#### Trunk-based 방식
![image](https://github.com/user-attachments/assets/aaff0010-c28f-48c2-bd2e-83d8f913ae72)

- main브랜치를 두고 main브랜치로부터 각 기능에 맞는 브랜치를 따로 생성한다. 생성한 브랜치로 작업을 진행하고 작업한 내용을 pr하면 팀원이 pr 내용을 확인하고 main브랜치에 merge한다. 다른 팀원은 merge된 main브랜치로부터 다른 기능을 담은 브랜치를 만들어 위 단계를 반복한다.
<br><br/>

### 4. Swagger
![swagger-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/e95e2495-0004-4bd0-b203-0c61214d2826)
- api를 한눈에 볼 수 있고 프론트 작업에서 매우 유용하게 사용 되었다.
<br><br/>

## 향후 계획
- 배포 진행 예정
- 아쉬운 부분은 꾸준히 수정 예정

