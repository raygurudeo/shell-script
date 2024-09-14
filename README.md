# shell-script

--> We can use user_management.sh script to perform all the user management related operation.
--> Please use user_managemeent.sh as a main script which is calling modify_user.sh script to perform specific user modification task.
--> Please execute script with sudo privileges as below:
    sudo user_management.sh
--> Update modify_user.sh location in the user_management.sh file accordingly.
--> Steps to configure git local repo with remote repo using personal access token:
    - Go to your Github profile -> Developer setting -> Token (classic) -> Generate personal access token and save it somewhere.
    -> Go to your local git repo commandline
    git config --global user.email "<Email>"
    git config --global user.name "<github username>"
    git push origin master
    git remote set-url origin https://<personal access tocken>@github.com/<username>/<repo name>.git
