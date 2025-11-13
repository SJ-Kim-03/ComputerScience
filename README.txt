Road to Developer.

git init
- .git 폴더: local repository 생성
- 초기화 과정
- shift + command + . : 숨김 파일 확인

git config -- global user.email(.name) "email(name)"
- 수정자 정보 등록
- 이메일, 이름 입력

git add file
- 버전으로 만들 파일 선택

git commit -m
- 커밋의 상세 설명 추가

git log
- 커밋 확인 가능, 최신순

git checkout 7자리
- 이전 커밋으로 되돌아가기
- 7자리 대신 - 사용시 최신 커밋으로 복원
- 최근 switch, restore 명령어로 나뉘어짐
- switch: 브랜치 간 이동
- restore: 파일 복구
- checkout은 실무에서 사용하지 않음

Repository 생성
- 주소: https://github.com/SJ-Kim-03/ComputerScience.git

git remote and origin 주소
- 원격 저장소 주소 입력
- origin: 원격 저장소

git branch -M name of branch
- 저장될 branch 생성

git push origin main
- 원격 저장소의 branch에 업로드
- origin의 main이라는 branch로 올려라
- github에서 repository 생성 시 main 브랜치 생성이 default
- CLI, 코드트리 환경에서는 master 브랜치 생성, 변경 가능
- name, token 입력

git clone 원격 저장소 주소 .
- 로컬 저장소에 내려받기
- 띄우고 마침표 하지 않으면 리포지토리 이름 폴더가 생성됨

git pull origin main
- 다른 로컬 저장소에서 최신본 가져오기

