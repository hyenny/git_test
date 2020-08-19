# git 연습용 저장소

## git 기본 명령어

### git 저장소 복제
```
$ git clone 주소
$ git clone https://github.com/hyenny/git_test.git
```

### git 서버 업로드
1. 수정된 파일을 저장소에 올릴 준비를 한다.
```
$ git add 파일 이름
$ git add .
```

2. add한 파일을 저장소에 올릴 것을 확정한다. (실제 remote repository에 반영 x, 로컬에서만 확정)
```
$ git commit -m "커밋 메세지"
```

3. push한다. (remote repository에 반영)
```
$ git push
$ git push origin 브랜치명
```

