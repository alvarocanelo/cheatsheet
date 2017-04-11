# SSH tricks

## Access directly to a folder when executing a command in SSH
SSH access by default to $HOME directory, or wherever is specified in SSH-server's configuration. To change is `-t` flag is necessary plus launching a console. Example:
`ssh user@host -t 'cd /target/directory/ ; bash --login'
