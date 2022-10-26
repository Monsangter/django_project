# django_project

웹프로그래밍 = > 홈페이지 만들기, 웹 서비스 만들기
프론트 : 화면(웹 브라우저에서 동작하는 코드) => HTML, CSS, JS
백엔드 : 서버(데이터를 입출력하거나, 계산하는 서버에서 동작하는 코드)
	=> 컴퓨터에서 동작하는 언어는 대부분 사용 가능하다.
		(http메소드에 맞게 요청이 들어오면 읽고 응답해주는 절차가필요)	(python, ruby, java, php, js, c#)

	=> 게임서버에도 컴퓨터가 필요함. go, erlang, perl등의 언어

HTTP
-웹 사이트 동작 방식
=> 웹 브라우저 주소창에 URL 입력 후 엔터
=> URL이용 서버 IP찾기. (네트워크 관련)
=> IP이용 서버에 접속
=> URL에 해당하는 자료를 요청
=> 웹 어플리 케이션이 URL을 해석해 해당하는 코드가 동작
=> 코드의 동작 결과를 응답으로 돌려줌.
=> 서버가 웹브라우저로 보내줌.
=> 웹 브라우저 응답 받는 데이터를 화면에 표시
=> JS(AJAX) 기술을 통해 여러번 요청이 될 때도 잇음.

백엔드 코드 : 각각 URL 패턴마다 소스코드 1개 이상.
옛날에는 하나씩 다 짜줘야했고 validation 테스트까지 수동으로 했어야 했다.

FRAMEWORK: 어떤 일을 할때 자주 사용되는 기능을 미리 준비해 둔 것.
=>제품을 빨리 출시해야한다.
-micro : 최소한의 기능 + 추가 기능을 원하는대로 설치해 사용 커스터마이징 쉬움  플라스크
-ufllstack: 거의 대부분의 기능 + 추가 기능도 설치 가능.	커스터마이징 귀찮아짐 장고

디자인 패턴 : 개발 설계상 발생하는 문제를 해결하기 위한 해결책(디자이너, 프론트, 백엔드) 분업
-MVC : 모델(데이터베이스) , 뷰(프론트), 컨트롤러(계산 처리 백엔드)
-MTV : 모델 템플릿 뷰.  (장고에서의 용어)

장고로 프로젝트 만드는 순서
1. 파이참 프로젝트 만들기
2. 장고설치
3. 장고프로젝트 만들기
4. 설정하기 (데이터베이스)
5. 데이터베이스 초기화
6. 관리자 계정 만들기

7. 앱만들기
8. 모델 설계(db)
9. 뷰 만들기(back)
10. 템플릿 만들기(front)
11.url을 만든다
대표적 기능: CRUD -> create.read, update, delete

