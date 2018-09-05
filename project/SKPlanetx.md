# Tdevelopers
TO-BE
SKT developers
기간 : 2012-06 ~ 2013-06

솔루션으로 가져온 SKP 플랫폼에도 참여하였고 그때당시 개발담당은 Internel, External API CRUD 및 EhCache 연동
그리고 Quartz 를 이용한 배치 관리자 프로세스를 진행하였다. 보통은 배치를 crontab 로 고정되게 작업을 진행하는 형태가 많은데
관리자에서 JOB을 등록하고 시간을 추가를 동적으로 해야하는 고객에 나이스하지않은 요구사항으로 진행한것같다. 
Quartz 2.4.x 버전이었고 RDBMS에 11개 테이블을 추가해서 JOB이 등록되면 해당JOB이 RDBMS에 상태를 주기적으로 모니터링되어
진행하는 형태가 된것같다. 관리자에서 스케쥴시간변경이나 기존에 등록된 JOB 사용유무 상태값을 변경하면 스케쥴 JOB에 등록된 trigger를 초기화하여
재등록되는 형태로 작업하였다.



AS-IS
프로젝트명 : SKT Planet Developers
프로젝트 기간 : 2012-06 ~ 2013-06
고객사 : SKP
근무회사 : 블루다임
담당업무 : 3rd-Party User 가 Application 을 개발하기 위해서
필요한 서비스 API정보를 제공하는 서비스입니다.

2012년 정식 오픈 되었으며 담당 업무는 
Planet Developers에서 제공되는 서비스별 및 API 등록/수정/삭제 캐쉬연동 기능
그리고 운영자및 사용자 권한 관리 각 서비스에서 필요로 하는 External API, 스케쥴링 작업 등 백앤드 시스템(관리자 센터)기능을
구현하였습니다. 담당권한은 관리자센터 개발PL입니다.
