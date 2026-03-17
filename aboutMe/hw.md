< 목표 - 나에 대한 모든 것 이라는 프로젝트를 git으로 관리해보기 >

- 모든 파일은 반드시 "이슈"와 연동되어야 있어야 함
  -> 어떤 사유로 추가되었는지가 명확해야함
  -> 커밋 메시지에 github.com > 자신의 repo > Issue > 게시글 번호를 반드시 넣기

- 만약 명령어를 쓰다가, ?? -> git {명령어} --help

< 개발 요구 사항 - 꼭 들어가야 하는 것 >

1. README.md 는 간단한 자기소개만 포함
2. 아래 항목은 반드시 포함
   - 취미 "디렉토리" / 하위에 항목별 md 파일 생성 ==> 각각의 항목은 이슈로 생성
   - 좋아하는 것 "디렉토리"

   ```
   ~
    READMD.md
    hobby/
        취미1.md
        취미2.md
        READMD.md
    favorite/
        좋아하는것1.md
        READMD.md

   ```

3. 커밋 메시지의 스타일

```
[이슈_#1] 메인 자기소개 페이지 신규 개발
[이슈_#2] 취미 페이지 신규 개발
[이슈_#3] 새로운 취미 추가
```

4. 반드시 사용해야 하는 명령어

```
git commit --amend
git commit --fixup
git branch
git checkout
git checkout -b

git merge
git rebase
git stash

git remote, fetch, push
```
