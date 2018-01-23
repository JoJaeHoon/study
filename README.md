### 실전 프로그램 개발 - Bookmark
1. 프로젝트 생성  
`pip install --upgrade`
 - 버전이 낮을 시 업그레이드 설치 하라는 오류 메세지
 >![python](./img/py_2.PNG)  
프로젝트를 생성하기전 가상 환경 사용  
`source venv/bin/activate` ( 비활성화 : `deactivate` )  
 - 가상환경 활성화  
`pip install django`  
 - PIP 파이썬으로 작성된 패키지를 설치,관리하는 시스템  
`django-admin.py startproject jjhsite`  
 - jjhsite 디렉토리로 프로젝트를 만듬  
>![python](./img/py_3.PNG)  
>![python](./img/py_4.PNG)  
2. 파일 분석
프로젝트 설정 파일인 settings.py 파일에 필요한 사항을 지정합니다  
장고는 디폴트로 SQLite3 데이터베이스 엔진을 사용하도록 설정됨  
- SQLite3 : 독립적이고 서버가 불필요하며,설정도 필요없고 트랜잭션을 지원함  
- 트랜잭션 : 데이터베이스의 상태를 변화시키기 위해 수행하는 작업의 단위 ( SQL를 이용해 데이터베이스 접근하는 것 )  
MySQL이나 Oracle 다른 데이터 베이스 변경시 파일 수정  
