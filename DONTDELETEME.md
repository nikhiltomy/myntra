 Before starting to work  in   VScode  do these First  to avoid merge conflicts 
   
1) git checkout main  // branch up to date or ahead of local by commits 

2) git pull origin main 

3) !important ;   #Creating a branch to avoid bugs in production branch 

     git branch <your branch name>
  
     git checkout  <your branch name>


4)  Happy hacking ! 
    make commits to your new branch  

5)  when you are ready to push bug free code , do...
     
     git checkout main 
       #switches branch to main  . In case anyone has commited  to main branch while you are working on your feature  then perform ,  git pull origin main  
       
     git merge  <your branch name> 
       #merges your  feature branch onto main and  thus  deleting your feature branch 

     git push origin main 

  # Above steps need to be performed everytime  you create or experiment on a new feature  so as to  develop a clean production level code 
  
