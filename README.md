# System-Programming
### 프로젝트 명
오목 게임
### 프로젝트 멤버
공진우

### 프로젝트 소개 및 개발 내용 소개
1. ncurses라이브러리를 사용해 게임판과 커서 이동을 구현하였습니다.
2. Server는 클라이언트의 접속과 진행을 관리합니다.
3. Client는 각자 번갈아가며 게임을 진행하며 5개의 돌을 연속적으로 배치하면 게임이 끝납니다.

### 프로젝트 개발 결과물 소개 (다이어그램)
<div>
  
  1. Server는 클라이언트가 접속할때 까지 대기<br>
  
  <img width="399" alt="스크린샷 2020-12-09 오전 9 07 32" src="https://user-images.githubusercontent.com/56913260/101556434-2f1f7800-39fe-11eb-9abf-ae0826575ce2.png"><br>
  
  2. 2명의 Client 접속<br>
  
  <img width="799" alt="스크린샷 2020-12-09 오전 9 13 59" src="https://user-images.githubusercontent.com/56913260/101556745-e6b48a00-39fe-11eb-9ad3-3a001c54147f.png"><br>
  
  3. Server에서 Client를 Accept<br>
  
  <img width="401" alt="스크린샷 2020-12-09 오전 9 15 08" src="https://user-images.githubusercontent.com/56913260/101556837-0d72c080-39ff-11eb-96d8-fa1e6bf7ae47.png"><br>
  
  4. Client는 ID를 입력하고 게임에 접속<br>
  
  <img width="325" alt="스크린샷 2020-12-09 오전 9 16 38" src="https://user-images.githubusercontent.com/56913260/101556993-68a4b300-39ff-11eb-8e3a-f6064cd31570.png"><br>
  <img width="325" alt="스크린샷 2020-12-09 오전 9 16 43" src="https://user-images.githubusercontent.com/56913260/101556996-6a6e7680-39ff-11eb-9ffe-6ced9b887dea.png"><br>
  
  <img src = "https://user-images.githubusercontent.com/56913260/101560994-d3f28300-3a07-11eb-94a7-d2b109e28865.png"><br>
</div>

### 개발 결과물을 사용하는 방법 소개 (프로그램 구동 화면 스크린 샷 첨부)
<div>
  
  1. 각 클라이언트의 ID입력<br>
  
  <img width="600" alt="스크린샷 2020-12-09 오전 10 22 27" src="https://user-images.githubusercontent.com/56913260/101561480-c4276e80-3a08-11eb-9495-8279c6936067.png"><br>
  
  2. 게임 초기 화면<br>
  
  <img width="600" alt="스크린샷 2020-12-09 오전 10 22 46" src="https://user-images.githubusercontent.com/56913260/101561496-cbe71300-3a08-11eb-85dd-719661f26d25.png"><br>
  
  3. AAA 클라이언트 입력<br>
  
  <img width="600" alt="스크린샷 2020-12-09 오전 10 23 05" src="https://user-images.githubusercontent.com/56913260/101561503-cd184000-3a08-11eb-861d-01f05ea835f9.png"><br>
  
  4. BBB 클라이언트 입력<br>
  
  <img width="600" alt="스크린샷 2020-12-09 오전 10 23 18" src="https://user-images.githubusercontent.com/56913260/101561507-ce496d00-3a08-11eb-9b84-bebea89807a1.png"><br>
  
  5. [3]-[4] 반복<br>
  
  6. 5개의 돌이 연결되면 게임 종료<br>
  
  <img width="600" alt="스크린샷 2020-12-09 오전 10 24 13" src="https://user-images.githubusercontent.com/56913260/101561514-d0133080-3a08-11eb-8c9b-40e58f3f9be8.png"><br>
</div>

### 개발 결과물의 필요성 및 활용방안
1. 오목 게임 외의 다양한 게임 제작이 가능하다.
2. 더 나아가 서버를 통해 원하는 게임(또는 작업)을 선택하고 즐길 수 있는 프로그램을 만들 수 있다.
