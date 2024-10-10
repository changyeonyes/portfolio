image CloverFeed

동료의 익명 피드백을 통해 내 직무상 강점을 알 수 있는 서비스!
내가 만든 피드백 질문 목록을 동료들에게 공유해서 피드백을 받아보세요 👀
English Version
🖱️Production
https://cloverfeed.kr/

⭐️ Medium
🇰🇷 CloverFeed.Kor
🇺🇸 CloverFeed.Eng

📋 Features
회원가입 및 로그인	피드백 질문 폼 생성
	
피드백 답변 제출	피드백 답변 확인
	
📌 System Architecture
image



📚 Tech Stack
분야	사용 기술
Fronted	        
Backend	  
AI	 
DevOps	   
etc	GitHub Slack Notion Figma Postman  GitKraken Visual Studio Code
Frontend
Backend
DevOps

🔐 ERD 설계
스크린샷 2024-01-05 오후 2 22 29




📈 API(swagger)
  
🛠 Installation
사용설명서
준비물

OpenAI secret key (발급받으러 가기(비용이 발생할 수 있음))
Docker를 시스템에 설치합니다.
아래의 shell 명령문을 똑같이 따라 칩니다.
$ git clone https://github.com/2023WinterBootCamp-Team-L/CloverFeed.git
.env 파일을 알맞은 위치에 작성합니다.
/.env (docker-compose.yml 파일과 같은 디렉토리)
MYSQL_ROOT_PASSWORD=(여기에 원하는 MySQL 루트 비밀번호 입력)
MYSQL_DATABASE=cloverfeed
MYSQL_USER=user
MYSQL_PASSWORD=(여기에 원하는 MySQL 루트 비밀번호 입력)
/backend/config/.env
DB_NAME=cloverfeed
DB_USER=root
DB_PASSWORD=(여기에 상단 .env파일에서 설정한 MySQL 루트 비밀번호 입력)
DB_HOST=mysql
DB_PORT=3306
CORS_ORIGIN_WHITELIST=http://127.0.0.1:5173,http://frontend:5173,http://localhost:5173,http://127.0.0.1:5174,http://frontend:5174,http://localhost:5174,http://127.0.0.1:80,http://frontend:80,http://localhost:80,http://127.0.0.1,http://frontend,http://localhost,http://localhost:8000
ALLOWED_HOSTS=backend,localhost,127.0.0.1
OPENAI_KEY=(여기에 OpenAI secret key 입력)
아래의 shell 명령문을 똑같이 따라 칩니다.
$ cd project
$ docker compose up -d --build
Docker Desktop에서 Docker Container들이 잘 실행되고 있는지 확인합니다.
Docker Desktop에서 backend container를 선택한 다음, django secret key를 확인합니다. (확인 방법)
확인한 django secret key를 .env 파일에 추가합니다.
/backend/config/.env
DB_NAME=cloverfeed
DB_USER=root
DB_PASSWORD=(여기에 상단 .env파일에서 설정한 MySQL 루트 비밀번호 입력)
DB_HOST=mysql
DB_PORT=3306
SECRET_KEY=django-insecure-(여기에 django secret key 입력)
CORS_ORIGIN_WHITELIST=http://127.0.0.1:5173,http://frontend:5173,http://localhost:5173,http://127.0.0.1:5174,http://frontend:5174,http://localhost:5174,http://127.0.0.1:80,http://frontend:80,http://localhost:80,http://127.0.0.1,http://frontend,http://localhost,http://localhost:8000
ALLOWED_HOSTS=backend,localhost,127.0.0.1
OPENAI_KEY=(여기에 OpenAI secret key 입력)
아래의 shell 명령문을 똑같이 따라 칩니다.
$ docker compose up -d --build
Docker Desktop에서 Docker Container들이 잘 실행되고 있는지 한 번 더 확인합니다.
아래의 shell 명령문을 똑같이 따라 칩니다.
$ cd frontend
$ yarn
$ yarn dev
그 상태에서 'localhost:5173'에 접속하면 사용할 수 있습니다.
👨‍👩‍👧‍👦 Members
Pictures							
Name	강석규	조상아	석민정	강지은	정현수	한현서	이창연
Position	Leader
Backend
DevOps
Backend
DevOps
Backend
Frontend
Frontend
Frontend
Frontend
GitHub							

개발 기간 : 2023년 12월26일 ~ 2024년 2월3일
