# gitLab
git command and notice check

## commit message example
`refs #109542 ~~이유로 ~~ 변경있었음`

## git useful command
`git branch` : branch 확인<br/>
`git checkout [branch_name]` : 해당 branch로 이동 (`option -b` -> 해당 branch를 생성함과 동시에 checkout)<br/>
`git rm [file_path/file_name]`: 해당 file local에서 삭제 및 삭제 상태 staging
`git checkout [filepath/file_name]` : 해당 file restore (git rm이나 그냥 rm으로 삭제한 경우 restore 하는 방법)
`git push origin [branch_name]` : 해당 branch를 master에 push 요청<br/>
`git status` : git 상태 정보 확인 (수정 사항)<br/>

## git config command
`git config --list` : 현재 접속 정보 확인<br/>
`git config --local [user.name/user.email...]` : local 접속 정보 변경<br/>
`git config --global [user.name/user.email...]` : global 접속 정보 변경<br/>
