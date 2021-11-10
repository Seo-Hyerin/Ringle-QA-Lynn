# Ringle QA - *Tutor&Student Issue Cases*


### 1. iPad 기종 Zoom 화면 띄워놓고 세션 진행하기 - Tutor / Student

- 테스트 케이스<br/>
(1) 튜터 or 학생이 iPad를 통해 수업 입장<br/>
(2) Zoom 입장<br/>
(3) 세션 진행<br/>
(4) 세션 종료<br/>

- Issue Point<br/>
iPad 기종을 사용할 경우 Zoom 화면 최소화 하여도 수업창과 동시에 확인 불가

### 2. 세션 예약 후 예정된 세션 일정이 이전에 수업 및 줌 미팅 진행

- 테스트 케이스<br/>
(1) 세션 예약 및 확정 완료<br/>
(2) 예정된 일자와 시간 이전에 학생과 튜터의 수업 입장<br/>
(3) 수업용 google doc 및 zoom기능 사용<br/>
(4) 세션 종료<br/>

- Issue Point<br/>
정규 세션 시간이 아닌 때에 수업창에 진입 가능

- 개선방안<br/>
오직 세션 시작 전 10분 전부터 해당 세션의 수업창으로 진입할 수 있도록 제한

### 3. Notice

- 테스트 케이스<br/>
[Sign in]-[Menu Bar]-[Notice]-[Main Page]

- Issue Point<br/>
별도 조건 없이 로그인 후 [Notice] 탭 접근 시 에러화면 전환, 메인 시작 화면으로 이동<br/>

- 개선방안<br/>
현재도 로그아웃 되는 상황이 아니므로 [Home] 화면으로 연결<br/>

<img width="200" alt="Tutor_Notice_Issue" src="https://user-images.githubusercontent.com/93983402/140917691-d440bdbd-df56-44ba-92ee-c44ce8e2279a.png">  <img width="450" alt="Tutor_Notice_Home_Isuue" src="https://user-images.githubusercontent.com/93983402/140917717-2f917790-cbd7-4511-9cc5-3d86b3d03782.png" >


### 4. Session 진행 중 줌 및 수업진행 페이지를 나갔을 때 해당 수업에 대한 수업권 처리 및 리뷰/피드백 제공 이슈

- 테스트 케이스<br/>
(1) 세션 시작 예정시간에 맞춰 튜터와 학생 수업 입장<br/>
(2) 20분 세션 진행 도중 튜터가 줌 종료 & 수업에서 나가기 처리<br/>
(3) 튜터가 줌 미팅 및 수업을 나간 후 학생이 줌 종료 & 수업에서 나가기 처리<br/>
(4) 해당 수업에 대한 수업권 미차감/리뷰 작성, 튜터 수업 정산/피드백 남기기가 작동<br/> 

- Issue Case<br/>
(1) 20분을 다 채우기 전에 이와 같은 프로세스에 의해 수업이 종료되었을 때, 학생의 해당 수업은 날짜가 바뀌기 전까지 '예정된 수업'으로 계속해서 떠있음<br/>
(2) 수업 당일이 지난 경우 학생의 수업권은 차감되어있으나 [1:1 Lessons]-[Review]에서 수업 내역 확인 불가, 수업중 작성된 코멘트, 수업 후 작성가능한 리뷰 활성화 되지 않음<br/>
(2-1) 수업 당일이 지난 경우 튜터의 [Past Lesson] 혹은 [Upcoming Lessons] 모두 존재하지 않음<br/>

- 개선방안<br/>
수업 중간 나가게 될 경우 하단 사항과 같은 처리 필요<br/>
(1)수업 재입장 알림 팝업을 통한 재입장 유도 or 실제 수업이 끝남 처리<br/>
(2)5분 내 재입장하지 않을 경우 먼저 수업 종료한 대상에게 disadvantage<br/>
(3)재입장 불가처리<br/>
