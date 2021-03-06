# Git 명령어

#### 원격 저장소(remote)와 로컬 저장소 연결하기
```bash
git remote add origin https://username@hostname/project/repository.git
git push -u origin master
```


#### 원격 저장소 URL 변경하기
```bash
git remote -v #저장소 위치 확인
git remote set-url origin https://username@hostname/project/repository.git
git remote -v #저장소 위치 변경 확인
```


#### 추가 / 커밋
```bash
git add . #모든 내용 추가
git commit -m "subject: commit sentance"
```


#### 클론
```bash
git clone https://username@hostname/project/repository.git
```


#### 되돌리기
- 수정한 파일 되돌리기
```bash
git checkout -- /path/filename.md
```

- 이미 커밋한 내용에 추가로 add 하기
```bash
git commit -m "first commit"
git add forgotten_file
git commit --amend
```