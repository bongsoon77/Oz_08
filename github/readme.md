### Day1    
*Git의 3가지 범위 

지역(Local)-특정 저장소 한정/폴더 하나만 적용, 
전역(Global)-모든 저장소 한정/생성하는 모든 폴더 적용, 
시스템(System)-해당 컴의 모든 저장소, 사용자 걸쳐 적용/잘 사용되지 않음


*Git 기본 명령어

1. git -- version - 버전 확인
2. git status - 파일 상태 확인 명령어

   
*Git파일 Commit하는 순서

1. git init - 선택 폴더를 깃 저장소로 만드는 명령어 (이때 깃 저장소에 필요한 모든 뼈대 파일이 담긴 .git라는 숨겨진 폴더가 생성됨, cmd+shift_.로 확인)
2. git config --global user.name/ user.email "Github 가입시 사용한 닉넴과 이멜" - 전역에 사용자 정보 입력
3. git config --global user.name/ user.email - 이름 이멜 확인
4. git config --list - 저장소의 설정 전체 출력
5. git config --unset user.name/ user.email - 전역에 설정된 이름 이멜 삭제
6. git config --global init.defaultBranch main - 로컬 저장소를 master->main 변경
   
*git 관리 설정 순서

1.cat "원하는 내용" > back.yaml, cat "원하는 내용" > front.yaml -cat 내용 있는 파일 생성, .yaml JSON과 같은 데이터 형식 파이썬의 dict 자료형처럼 key, value 형태로 저장하는 .yaml 확장자 파일 생성
2. git status - 파일 상태 확인 명령어 (Untracked-Git 추적 X,Tracked-Git 추적 O)
3. git add "commit 원하는 파일명" - Untracked 상태인 한가지 파일만 임시저장영역인 스테이지로 더하기 위한 명령어
4. git add . - 모든 Untracked 상태인 파일을 임시저장영역인 스테이지로 더하기 위한 명령어
5. cat "원하는 내용" > admin_info.yaml
6. touch gitignore - touch 파일만 생성
7. mv admin_info.yaml gitignore - 원하는 파일을 원하는 디렉토리로 이동

