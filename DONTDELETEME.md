 Before starting to work  in   VScode  do these First  to avoid merge conflicts 
   
     while (1) 
{ 


1) git checkout main  // branch up to date or ahead of local by commits 

2) git pull origin main 

3) !important ;   #Creating a branch to avoid bugs in production branch 

     git branch <your branch name>
  
     git checkout  <your branch name>


4)  Happy hacking ! 
    make commits to your new branch  

5)  when you are ready to push bug free code , do...
     
     git checkout main 

     git merge  <your branch name> 

     git push origin main 

  #do the above steps after merging and pushing  local  branch  
  
     }


