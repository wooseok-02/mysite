
# 파이썬 & 장고 설치 방법
1. 파이썬 홈페이지에서 다운
2. vsc에서 익스텐션 설치
3. python3 쳐서 설치 확인
4. python3 -m venv venv 
5. source venv/bin/activate
6. pip install django

# Django 제공 개발 프로젝트
1. django-admin startproject mysite #기본 프로젝트 만들기( 앱 이름 : mysite )
2. python3 manage.py startapp polls #기본 app 만들기( 앱 이름 : polls )

# Django 작동 원리
1. urls.py 에서 각 url로 파싱
2. View.py 에서 핵심 로직 구현
3. model.py,DB,managers 등 검증과 연결
4. Template 에서 디자인 담당
5. 사용자 응답

# Django 백엔드 서버 on/off
py manage.py runserver
cntl+c

# Git & Git hub 사용법
1. git 설치
2. git hub 회원가입
3. git init
4. git add . (staging)
5. git commit -m "first commit" (local repository)
6. git push (git repository)


# Database 
1. view에 class 만들기
2. urls.py에 경로 만들기
3. 루트에서 파싱하기

1. models 에서 class 정의하기
2. settings.py에서 installed_apps 에서 해당 app(polls) 인스톨하기 -> 이제야 장고에서 인식
3. python manage.py makemigrations -> DBMS에 넘기기위한 설계도 만들기
4. python manage.py migrate (실제 테이블 생성)

# admin
1. python manage.py createsuperuser
2. polls/admin에 모델에 입력한 Question 넣기
3. 백엔드 서버 실행해서 확인

# view
