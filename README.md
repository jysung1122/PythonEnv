# PythonEnv

파이썬 구축
1. gpt에 대해 알아봄
2. conda 가상환경 구축 ** 새폴더 만들기 -> 가상환경 만들기 --> conda create -n (이름) python=3.9
3. vscode IDE 설치
4. gpt를 통해 addBook 생성
5. pyQt5를 이용해서 QtDesigner(UI디자인) 사용
6. WAMP를 설치하고 Apache(서버를 돌리기위한 에이전트), MySQL, PHP(데이터베이스를 사용할 수 있는 툴) 사용
7. MySQL에서의 SELECT, UPDATE, DELETE, INSERT, INSERT 공부, 5번과 연결하여 모듈화
8. 완성하고 배포하기 위해 pyinstaller -w -F ... 
9. pip freeze > requierment.txt(프로그램을 사용하기 위한 설치파일들 목록) --> pip install -r requirements.txt 명령시 다운
10. install factory사용하여 setup.exe 생성


Github
- profile page(사용자이름과 동일한 repository 생성 - Read.me를 같이 생성)
- homepage(임의의 repo 이름 - Read.me를 같이 생성 - index.html을 복사 - setting의 page의 branch menu - main - save -Refresh)
- 저장소(개인용 소스컨트롤)


Git을 이용한 source control
- Git을 pc에 설치
- Git 명령어 -> 소스코드를 저장하고 동기화
- 프로필 페이지에 연결


git 에서 복사한 프로젝트 시작하는 방법
1.0 빈폴더 만들기
	1.1 git clone <url주소>
2.0 VSCode 실행하기 
3.0 터미널 열기 
4.0 가상환경 만들기 
5.0 가상환경과 VS코드 연결(Sift+Ctrl+P)
6.0 터미널 열기 (S⁭hift+Ctrl+~)
7.0 pip install -r requirements.txt
8.0 VSCode에서 디버깅 하기(경로등) 

만드는법
pip freeze > requirements.txt


==============================================================

AI 응용SW
1) What? = 무엇을 구별할건지
2) Data 구하기 = Data Set
3) Pre-Trained 모델 구하기 (YOLO 등)
4) Fine Tuning <- Data Set 을 사용하여 커스텀 모델이 만들어 짐
5) 응용SW 개발 (WebApp, NativeApp)
