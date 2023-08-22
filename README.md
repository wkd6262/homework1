![스크린샷 2023-08-22 232704](https://github.com/wkd6262/homework1/assets/142865132/acaf0ae8-327f-49eb-9a54-941e2fb0cd7c)


230822

-GIT 브랜치

git branch ""    ("" 새로운 브랜치 생성)

git branch -d "" 병합되어진 브랜치 삭제

git branch -D "" 브랜치 강제삭제

-commit

git add ""  ""를 추가

git add .     추가된 파일을 모두 추가

git commit -m ""    add로 추가 된 파일을 ""메시지로 커밋함.

git commit -am ""     git add과정을 포함한 커밋명령어.

-git hub 및 과제

git init 으로 로컬저장소 main 지정

git config --list 로 user.name 및 email 확인 후 항목이 비어 있다면

git config --global user.name or email "" 등록한다

touch "README.ad" 로 마크다운 파일을 만듦

git add " "  리드미 파일 등록 후

git commit -m ""    마크다운 커밋

커밋이 되었으면 깃과 깃허브를 연결 시켜준다

깃허브 로그인 후 your Repositories 클릭 new 클릭 public 확인 후 Create 클릭

이제 깃을 다시 킨다.

git status 로 오류를 확인하고 빨간 글씨의 파일을 커밋한다.

git branch -M main 메인브런치 "main" 설정

git remote add origin https://github.com/자신의아이디/로컬저장소폴더이름.git 입력

git push -u origin main 메인으로 푸시한다.
