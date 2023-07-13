#CLI
- command_Line Interface

- 새 폴더 만들기($는 터미널에서 했다는 뜻)
```bash
$ mkdir new_folder
> mkdir(make 디렉토리)
```

-작업 위치를 new_folder로 이동
```bash
$ cd new_folder
```

- 현재 작업 위치를 열기
```
# . 은 현재위치를 나타냄(상대경로)
$start.
```

- VS code 로 열기
```bash
$ code .
```

- 파일 열기
```bash
$ code README.md
VS code로 README 파일 열기
```


- 현재 작업 위치의 파일 목록
```bash
$ ls
```

- 파일의 이름을 바꾸거나 위치를 옳기기
```bash
$ mv {이동할 대상}{이동될 위치}
$ mv {이름바꿀 대상 대상}{바뀔이름 위치}
```


### 상대경로, 절대경로
1. 절대 경로(상세하고 정확한 위치)

2. 상대 경로
- 나를 기준으로 경로를 저장

- 삭제
```bash
$ rm {파일 명}
$rm -r {폴더}
```

$ cat 