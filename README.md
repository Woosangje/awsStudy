# awsStudy
0223
빅데이터 이야기 북한이 문제야기, 일주일 수업하고 3주 프로젝트 3월말부터 spring 있던걸로 version2 4월 스프링부트 1주일 after 개인프로젝트 517수료 <br>
aws는 vmw를 준다 <br>
작업한 파일을 외부로 export하는게 aws가하는일 <br>
● 웹소켓을 사용하여 채팅 프로그램 작성 공부하기<br>
24시간 open되어 있는 것을 서버라고한다.<br>
홈에디션,10명, 프로페셔널 20명 까지 접속, 1년무료 프리티어 가상머신 하나에1년 가상머신2개면 6개월<br>
aws로 DB접속시 패스워드 1234하면 무조건 뚤린다. 뚤리면 채굴돌림 cpu 100%사용됨<br>
aws는 루트사용자로 로그인, 채팅 = 웹소켓<br>

8.2 RDS aws가 DB를 가지고있는거<br>
플록시 서버란 대용량자료사용할때 사용 미리가지고 있는데이터<br>
이번주 aws읽어보기<br>
●  aws 홈페이지 > "요금" 검색 > 과금정보 및 비용 관리<br>
왼쪽 탭 > 예산 > 오른쪽 주황색 "예산 생성" <br>
이메일 수신자에 이메일 입력 ex)계정@naver.com<br>
프리티어라고 안적혀있는 것은 무조건 유료<br>

● ec2로 검색 > ec2 가상 검색 > Launch an instance<br>
Quick Start는 Windows로 설정<br>
mc windows sever 2016 base 로 설정<br>
core base는 GUI가 없음 명령어를 키보드로 선언해야한다.<br>

_새 키페어 생성<br>
이름 : jsptest<br>
jsptext.pem 파일이 있어야 가상 컴퓨터에 로그인 할때 사용<br>
인터넷에서 HTTPS 트래픽 허용,인터넷에서 HTTP 트래픽 허용 토글 on 할것<br>
> 인스턴스 시작(주황색)<br>
>인스턴스 주소 > https//퍼블릭 IPv4 주소 이다.<br>
● 보안 > 3389는 마리아 DB이다.<br>
"원격 데스크톱 파일 다운로드"<br>
암호는 "암호 해독하기" >  pem에서 복붙하고<br>
오른쪽 "연결" > 탭 RDP클라이언트 > 암호가져오기:이름.pem > 암호해독 ><br>
  인스턴스에 연결: 암호 복붙해서 이름.rdp 에 붙여넣고 실행<br>
종료됨 나오면 된다<br>
8000<br>
★core로 설치하면 마우스 작동안된다.<br>
★★★★ aws 설치절차 pdf보기
> https://mingyucloud.tistory.com/entry/EC2-%EA%B8%B0%EB%B0%98-window-%EC%9B%B9-%EC%84%9C%EB%B2%84-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0
시작 > Server Manager > add role and features (WEB SERVER (IIS)설치해야 서버작동한다.
 

● 오라클,jdk,톰켓, 외부에서 push되는지 확인<br>
 8000번안쓰고 80번 사용 톰켓 8001 , 80 순으로 입력<br>
팀장이 이클립스 > 원파는 프로젝트 오른쪽 클릭 > Export > warfile > 톰켓9.0인지 확인 체크박스 전부 on > 바탕화면 war 확장자인지 확인 finish 프로젝트이름.war을 조원들에게 뿌린다.<br>
조원들이 파일을 받아서 aws에올린다.<br>

connectionFull 사용할시 톰켓폴더의/conf/context.xml의 내용을 web.xml에 붙여넣어야 한다.<br>

awsMV의 sys?의 패스워드는 the1234<br>
자기가 만든 코드 쉐어링<br>
코드공유 ppt마무리하고<br>


C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps<br>
에 Subway.war 옮기고<br>
bin으로 이동하야 Tomcat9 실행 > startup.ext실행하고<br>
주소 http://3.36.65.43/Subway/Main/main.jsp 를 web에서 실행한다.<br>

오라클 연결 본인거 로컬서버로 연결해 사용<br>
