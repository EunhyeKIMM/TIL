# Git 기초

### 용어 알기

- vcs: 버전 관리 시스템

### 명령어 

| 명령어                                    | 뜻                                                        |
| ----------------------------------------- | --------------------------------------------------------- |
| Ctrl + L                                  | command 창 초기화                                         |
| Ctrl + A                                  | 명령어 맨 앞 이동                                         |
| Ctrl + E                                  | 명령어 맨 뒤 이동                                         |
| $ mkdir                                   | 현재 경로에 생성할 디렉토리명                             |
| $ git rm -r                               | 삭제할 디렉토리명                                         |
| $ dir / $ ls                              | 디렉토리 목록 조회                                        |
| $ cat [파일명]                            | 파일 내용 조회                                            |
| $ git init                                | 저장소 초기화                                             |
| $ git status                              | 커밋 상태 조회                                            |
| $ git log                                 | 커밋 이력 상세 조회                                       |
| $ git commit -m '[커밋설명(커밋이름)]'    | 변경사항 저장(사진 찍기)                                  |
| $ git config --global user.name "이름"    | 지금 이 PC에서 git을 하는 사용자가 누구인지 알려준는 것   |
| $ git config --global user.email "이메일" | 지금 이 PC에서 git을 하는 사용자가 누구인지 알려준는 것   |
| $ git add [파일명/dirname]                | 커밋할 변경사항들을 Stage에 올린다                        |
| $ git diff                                | 차이점                                                    |
| $ git restore [파일명/dirname]            | Stage에 올린걸 되돌리거나 커밋되지 않은 내용을 바꾼다..?? |



- vcs(version control system): 버전관리시스템

mkdir

- touch 파일 생성 명령어 

  cd (~/./..)
  ls
  ls -a
  rm
  rm -r
  mv

CLI 문서 편집기 vim
i => 편집(insert)모드
esc => 명령모드
명령모드에서
:w => 저장
:q => 종료
:wq => 저장 후 종료
:q! => 강제 종료

git 명령어
git config --global user.name "이름"
git config --global user.email "이메일"
git init
git status
git log
git add <file/dirname>
git commit -m "<message>"
git restore <file/dirname>

git 핵심 주제어들

.git/
스테이지(stage area)
commits
staged



git log --pretty=oneline --abbrev-commit
로그 간략하게 하기

git log --pretty=format:"%h %s" --graph
로그 그래프로 

--> 해보기 

프로그래머들이 자주 쓰는 폰트 이름 --> 콘솔라스 (consolas)

https://gitignore.io
이그노어 파일 복붙 사이트

project 생성할 때,
1. touch .gitignore
2. touch README.md
3. git init => add => commit...



Ctrl + C => vs code에서 프로그램 강제종료 단축기 