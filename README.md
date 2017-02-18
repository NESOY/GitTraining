# Git Command
> (2017-02-02 Update Version) 

1. Option 정보

```shell
 -- : Long Name Option
 - : Short Name Option
```

2. 기존 계정 정보 삭제

```shell
$ git config --global --unset credential.helper
$ git config --system --unset credential.helper
```

3. 계정 설정

```shell
$ git config user.email "kyoje11@gmail.com"
$ git config user.name "Kwon Young Jae"
```

4. 설정확인

```shell
$ git config --list
$ git config user.email;
$ git config user.name;
```

5. 도움말 보기

```shell
$ git help 명령어
```

6. git 상태 확인

```shell
$ git status
$ git status -s (Short View)
```

7. 파일 무시하기
.gitignore 파일 생성후 무시 파일 패턴 적기
Nesoy Posting : <https://nesoy.github.io/articles/2017-01/Git-Ignore>

8. git 저장소 만들기

```shell
$ git init
```

9. commit 과정

```shell
$ git add testFileName
$ git commit -m "First Commit Message"
$ git commit -sm "서명을 포함한 commit"
$ git commit -a -m "First Commit Message" (Add 과정 포함)
```

10. 파일 삭제하기

```shell
$ git rm FileName
```

11. History 조회하기

```shell
$ git log
$ git shortlog
```

12. 되돌리기

```shell
$ git commit --amend (이전 커밋으로 한번에 한다)
```

13. Unstage로 변경하기

```shell
$ git reset HEAD FileName
```

14. Remote 저장소

```shell
$ git remote -v (단축이름과 URL을 볼 수 있다.)
$ git remote add 단축이름 URL
```

15. branch 만들기 및 확인

```shell
$ git branch
$ git branch testing
```

16. branch 이동하기

```shell
$ git checkout otherBranch
```

17. branch 삭제하기

```shell
$ git branch -d branchName
```

18. git merge 하기

```shell
$ git checkout master
$ git merge BranchName
```

19. git branch commit message 보기

```shell
$ git branch -v
```
