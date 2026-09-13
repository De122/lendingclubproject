when we clone a remote project, then origin is referring to that - git push origin main
when we start developing on local, then we need to set the origin  - git remote add origin

To check where the origin points to , use - git remote -v

To know which branch we are in currently - git branch  

NOTE : - In local IDE, when we create the repo folder first, main is represented as master, so if we try to execute any command from IDE having main in it, it might not work , so we need to remain master first to main. cmd : git branch -M main

