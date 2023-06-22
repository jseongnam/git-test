git init : 해당 디렉토리에 새로운 git 저장소를 생성한다.
git remote add origin <remote repository url> : repository url에 해당하는 파일들을 모두 git에 add한다.
git add <file name> : file name을 git 에 add한다.
git commit -m "message" : add한 file들을 message를 보내면서 commit 한다.
git push origin <branch name> : commit에서 한 message로 git에 push하여 해당 파일들을 github에 pull request 한다.
git pull origin <branch name> : github에서 branch name으로 push한 파일들을 내 git에 pull 받는다.
git merge <branch name> : 내가 merge 할 수 있는 권한이 있을 때, branch name인 branch를 github에 merge한다.
