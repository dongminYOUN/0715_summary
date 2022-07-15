

# Git

1. **README.md**

   -  프로젝트에 대한 설명 문서
   -  일반적으로 마크다운을 이용해 작성


2.  **Repository** 

   - 특정 디렉토리를 버전 관리 하는 저장소
   - git init 명령어로 로컬 저장소를 생성

   - ![image-20220715130926753](TIL.assets/image-20220715130926753.png)\
   - master의 의미 : git이 지금 관리하고 있는 디렉토리다



3.  README.md  만들기

   4.  touch 함수로 만들기

   5.  git status 로 상태 확인 - untrack됨

   6.  git add 로 추가

   7.  git commit

      - 커밋의 3가지 영역 

        - Wokring Directory : 내가 작업하고 있는 실제 디렉토리

        - Staging Area : 커밋으로 남기고픈 특정 버전으로 관리하고 싶은 파일이 있는 곳

          ​      					staging에 값을 넣어주고 commit을 해서 특정 파일 값 추적

        - Repository : 커밋들이 저장되는 곳


## git 기본기




1. git init 으로 수정 시작 (master가 뜰거임)
2. git config --global user.name '이름'
   git config --global user.email ' xx@xxx.com' 설정해야 git 상태 확인가능
3. git add 파일이름 (어떤 파일에 commit을 넣겠다 대기상태, git status에 남은 상태, 즉 커밋이 아직 안됨) - staging area 상태
4. git commit -m'원하는메세지'(커밋을 넣은거임, 그러니까 git status에 비어있게됨)
5. git log(최종적으로 들어간지 확인)
6. update 하는법 ( 그 파일을 클릭해서 내용을 수정하면 M이라고 파일에 뜸)
7. 그럼 다시 git add를 해준다음에 commit을 해서 수정하는것!
8. dz

