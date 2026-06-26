# Forge VM

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=279848665)   

## Commands

1. sudo su

2.  sudo apt update 

3. cd win10 

4.  sudo apt install moby-engine moby-containerd moby-cli 

5.  sudo apt install docker.io docker-compose -y 

6. cd /workspaces/Forge-VM/win10/windows

7. curl -L -o 11.iso "https://software-static.download.prss.microsoft.com/dbazure/888969d5-f34g-4e03-ac9d-1f9786c66749/26200.6584.250915-1905.25h2_ge_release_svc_refresh_CLIENT_CONSUMER_x64FRE_en-us.iso"

7. sudo docker-compose -f win10.yml up

### IF THE SIXTH COMMAND FAILS RUN 'sudo apt update && sudo apt install --reinstall docker.io'
