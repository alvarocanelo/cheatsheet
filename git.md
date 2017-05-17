# GIT Stuff

## Create a remote repository on a server
_(from [How To Set Up Automatic Deployment with Git with a VPS](https://www.digitalocean.com/community/tutorials/how-to-set-up-automatic-deployment-with-git-with-a-vps))_  
In order to crete a remote (_private?_) server, once there is a local repository do the following steps:

1. On remote:

    mkdir -p    /path/to/remote/repository_name.git  
    cd          /path/to/remote/repository_name.git  
    git init --bare
1. Then, on local:

    cd    /path/to/local/repository  
    git   remote add remotename ssh://user@domainorip.com/path/to/remote/repository_name.git
