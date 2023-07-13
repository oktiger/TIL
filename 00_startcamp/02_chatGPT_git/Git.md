ctrl + ` -> 터미널 열기
# Git 이란...
> 분산 버전 관리 시스템

- 버전관리: 변화를 기록하고 추적하는 것

-git의 역할 
- 코드의 버전(히스토리) 관리
- 개발되어 온 과정 파악
- 이전 버전과의 변경 사항 비교
- 코드의 '변경 이력'을 기록하고 '협업'을 원활하게 하는 도구

-git의 3가지 영역
1. working directory: 실제로 작업하고 있는 공간

2. Staging Area: work directory에서 변경된 파일 중, 다음 버전에 포함시킬 파일들을 선택적으로 추가하거나 제외할 수 있는 중간 준비영역

3. Repository: 버전이력과 파일들이 영구적으로 저장되는 영역 모든 버전과 변경 이력이 기록됨

버전: commit 이라고 함 
-커밋찍으세요(변경된 파일들을 저장하는 행위)

### git 초기화
```bash
$git init
```

```bash
$ rm -r .git : 파일삭제
```

### 상태 확인 명령어
```bash
$ git status :깃아 상태 보여줘
```


### Staging area에 추가
```bash
$ git add {path}<folder name> :README 파일 staging area에 추가헤줘
```

### Repostitory에 저장하기
```bash
$ git commit -m "commit message"
```
-공백의 의미 생각하기.

### git 기초 설정
```bash
$ git config --global user.email "sehun9803@naver.com"

$ git config --global user.name "부울경_1반_옥세훈"

$ git config --global --list
```

터미널 삽입 shift+insert// crtl+v

### 커밋 기록 확인하기
```bash
$git log
```