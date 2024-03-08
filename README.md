# project-docs
## Setup Development Server
Execute this script

```
curl -s https://raw.githubusercontent.com/daisyduck-project/project-docs/main/development.server.setup.sh | sudo bash -s
```

if Docker failed, please add your user to docker group:

```
sudo gpasswd -a $USER docker
newgrp docker
```
