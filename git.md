# GIT Stuff

## Create a remote repository on a server
In order to crete a remote (private?) server, once there is a local repository do the following steps:

1. On remote:

    mkdir -p    /path/to/remote/repository_name.git  
    cd          /path/to/remote/repository_name.git  
    git init --bare
1. Then, on local:

    cd    /path/to/local/repository  
    git   remote add remotename ssh://user@domainorip.com/path/to/remote/repository_name.git
