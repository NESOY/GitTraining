# GitTraining
<pre><code>
Option 정보
 --Long Name
 -Short Name

-기존 계정 정보 삭제
git config --global --unset credential.helper
git config --system --unset credential.helper

-계정 설정
git config user.email "kyoje11@naver.com"
git config user.name "Kwon Young Jae"

-설정확인
git config --list
git config user.email; git config user.name;

-도움말 보기
git help 명령어

-git 상태 확인
git status
git status -s (Short View)

-파일 무시하기
.gitignore 파일 생성후 무시 파일 패턴 적기

-git 저장소 만들기
git init

-commit 과정
git add testFileName
git commit -m "First Commit Message"
git commit -sm "서명을 포함한 commit"
git commit -a -m "First Commit Message" (Add 과정 포함)

-파일 삭제하기
git rm FileName

-History 조회하기
git log
git shortlog

-되돌리기
git commit --amend (이전 커밋으로 한번에 한다)

-Unstage로 변경하기
git reset HEAD FileName

-Remote 저장소
git remote -v (단축이름과 URL을 볼 수 있다.)
git remote add 단축이름 URL

-branch 만들기 및 확인
git branch
git branch testing

-branch 이동하기
git checkout otherBranch

-branch 삭제하기
git branch -d branchName

-git merge 하기
git checkout master
git merge BranchName

-git branch commit message 보기
git branch -v

</code></pre>

참고 : http://www.internetmap.kr/1558
