# Ringle QA - *Tutor&Student Issue Cases*


### 1. iPad 기종 Zoom 화면 띄워놓고 세션 진행하기 - Tutor / Student

- 테스트 케이스<br/>
(1) 튜터 or 학생이 iPad를 통해 수업 입장<br/>
(2) Zoom 실행<br/>
(3) 세션 진행<br/>
(4) 세션 종료<br/>

- Issue Point<br/>
iPad 기종을 사용할 경우 Zoom 화면 최소화 하여도 수업창과 동시에 화면확인 불가

### 2. 세션 예약 후 예정된 세션 일정 이전에 수업페이지 진입 및 줌 미팅 진행하기

- 테스트 케이스<br/>
(1) 세션 예약 및 확정 완료<br/>
(2) 예정된 일자와 시간 이전에 학생과 튜터 모두 수업페이지로 입장<br/>
(3) 수업용 google doc 및 zoom기능 사용<br/>
(4) 세션 종료<br/>

- Issue Point<br/>
정규 세션 시간이 아닌 때에 수업창에 진입 가능<br/>
[학습활동] 탭에서는 정규 세션 시간이 아닌, 그 이전에 진행한 날로 활동 로그가 남음<br/>

- 개선방안<br/>
오직 세션 시작 전 10분 전부터 해당 세션의 수업창으로 진입할 수 있도록 제한

### 3. Tutor - Notice

- 테스트 케이스<br/>
[Sign in]-[Menu Bar]-[Notice]-[Main Page]

- Issue Point<br/>
별도 조건 없이 로그인 후 [Notice] 탭 접근 시 에러화면 전환, 메인 시작 화면으로 이동<br/>

- 개선방안<br/>
"준비중입니다."와 같은 안내 멘트 작성된 화면 연결 후 "홈으로 이동하기" 모달<br/>
메인 페이지로 연결 시 로그아웃 처리되지 않으므로 [Home] 화면으로 연결<br/>

<img width="200" alt="Tutor_Notice_Issue" src="https://user-images.githubusercontent.com/93983402/140917691-d440bdbd-df56-44ba-92ee-c44ce8e2279a.png">  <img width="450" alt="Tutor_Notice_Home_Isuue" src="https://user-images.githubusercontent.com/93983402/140917717-2f917790-cbd7-4511-9cc5-3d86b3d03782.png" >

