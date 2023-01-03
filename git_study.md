# 깃 설치하기
- 깃에 가서 다운 받아서 설치한다
    -- 깃의 브런치를 main에서 master로 바꾼다

# 깃으로 관리할 폴더를 선택하여서
- 오른쪽 버튼 git bash here로 쉘 명령어 열기

# 깃 초기 설정하기
- 한 번만 하면 된다.
- git config --global user.name "깃허브아이디명"
- git config --global user.email "깃에가입한이메일"

# 깃 초기화 된 것 확인하기
- git config --global --list

# 깃의 상태를 확인
- git status

# 깃이 관리하는 폴더로 만들려면
- git init
- 주의 하위 폴더는 깃의 관리 대상이 됩니다.
- __그러므로 하위폴더를 git init하면 안 됩니다.__

# staging area에 파일 올리기
- git add 파일명.확장자
- git add 폴더명 //해당 폴더를 올린다.
- git add. //모든 파일을 다 올려라.

## 연습
- c.txt를 만들고 그곳에 임의의 문자를 넣어 주세요
- 깃의 상태를 보고
- commit까지 해보세요