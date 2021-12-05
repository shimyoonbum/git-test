git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/shimyoonbum/git-test.git
git push -u origin master
git log
git ls-remote

제주도에서 작업 후 commit
git clone https://github.com/shimyoonbum/git-test.git
git checkout -b topic(topic branch 생성)
git branch(branch 확인)
touch write50%.txt(텍스트 파일 생성)
git status(상태 확인)
git push origin topic(push)

집에서 다시 와서  branch 다운로드 받고 마저 작업 진행
git ls-remote(remote 상태 확인)
git fetch origin(모든 브렌치 다운로드)
git checkout -b topic origin/topic

touch write100%.txt
git checkout master(마스터로 branch 변경)
git merge --squash topic(master branch에 topic에서 추가됬던 내용을 병합)
git status
git commit
git push