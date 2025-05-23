update your machine " yum update -y"

1. create a directory on linux machine
2. swithch to that directory
3. install git "yum install git -y"
4. run cmd " git init" it will make your directory to git repository
5. in this there is 3 area  1.working area --> whare you write your code  2.stagging area --> here you save your working area code  3. local repo : in this you commit some file from stagging area
6. create a file "touch file"
7. now write some line of code in that file
8. add this file to stagging area using command "git add file "
9. now create another file in working spae and after that save in stagging area
10. now we commit file to local repo " git commit -m " message or tag of that file "
11. now we have to push on github so coonect github using ssh client
12. "ssh-keygen -t rsa -b 4096 -C "abc@gmail.com" "   enter all set defeault to all msg  
13. cat ~/.ssh/id_rsa.pub     copy that link to paste in github->setting->ssh->new->paste->asve
14. git remote set-url origin < repo url paste here >
15 git push origin master

"git log " to show all commit 
" git status" shows the current status 
" git remote remove origin "  remove the origin 
" git remote -v" see the origin 
" git show <commit-id> "  it will show paticular commit code 


"git branch " shows all branch in that repo 
"git branch <branch name> " create new branch 
" git checkout <brach name> " move from one branch to another 
