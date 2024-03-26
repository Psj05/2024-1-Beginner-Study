# 1주차

GIT이란?
    버전 관리 및 협업을 위해 사용하는 오픈소스 소프트웨어

파일의 생명주기
    Untracked Unmodified Modified Staged로 구분됨

GIT의 영역
    1. Working Directory
    2. Staging Area
    3. Repository

GIT으로 파일 관리하기 1
    1. 디렉토리에 Git 저장소 만들기
        $ git init
    2. Git으로 관리할 대상 등록하기
        $ git add
    3. 파일 수정 후 로컬 저장소로 옮기기
        $ git commit

GIT으로 파일 관리하기 2
    1. 모든 파일 한 번에 등록
        $ git add .
    2. 하나씩 등록
        $ git add <파일명>
    3. unstage로 되돌리기
        $ git rm --cached <file>

Commit Message - type
    feat (새로운 기능을 추가한 경우)
    refactor (기존 코드 개선)
    fix (버그를 수정한 경우)
    chore (코드 외의 설정을 바꾼 경우)
    docs (문서화)
    test (테스트 코드)

GIT에 커밋하기
    git commit -m "<commit message>"

GitHub에 올리기
    $ git add <파일명>
    $ git commit -m “commit message”
    $ git push origin main

https://github.com/Psj05/Psj05