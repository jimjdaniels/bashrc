#### bashrc
#### .bashrc

#### Source global definitions
if [ -f /etc/bashrc ]; then
 . /etc/bashrc
fi

#### Uncomment the following line if you don't like systemctl's auto-paging feature:
#### export SYSTEMD_PAGER=

#### User specific aliases and functions

set -o vi


####export DOCKER_TLS_VERIFY=1
####export DOCKER_HOST=tcp://10.12.39.205:2376

####export PATH=$PATH:/opt/kubernetes/platforms/linux/amd64/

####export PYTHONPATH=/usr/local/lib/python2.7/site-packages
####export PYTHONSTARTUP=/usr/local/etc/pythonrc

#### GO VARIABLES
export PATH=/home/demo/venv/bin:/usr/local/bin:/usr/bin:/usr/local/sbin:/usr/sbin:/home/demo/.local/bin:/home/demo/bin
export GOPATH=\$HOME/go
export PATH=$PATH:$GOPATH/bin
export PATH=/usr/local/bin/go/bin:$PATH
export GOPROXY=http://goproxy.sas.com:3000
export GONOSUMDB=*.sas.com


export GOPATH="$HOME/go/"
export PATH=$PATH:~/go/bin

if [ -d "$HOME/.local/vim/bin/" ] ; then
   PATH="$HOME/.local/vim/bin/:$PATH"
fi
alias c="clear"
alias l="ls -a"
alias p3="/usr/bin/python36"
#alias python="/usr/local/bin/python"
alias envp3="source envp3/bin/activate"
alias da="deactivate"

alias d="docker"
alias dc="docker-compose"
alias di="docker images"
alias dps="docker ps"
alias dpsa="docker ps -a"
alias rmi="docker rmi"
alias rmif="docker rmi -f"
alias prune="sudo docker system prune"

#### kubectl command aliases
alias kubectl="/usr/bin/kubectl"
alias k="kubectl"
alias kgd="kubectl get deployments"
alias kgp="kubectl get pods"
alias kgs="kubectl get services"
alias kgr="kubectl get replicasets"
alias kg="kubectl get"
alias kgname="kubectl get namespaces"
alias kgnet="kubectl get networkpolicy"
alias kdp="kubectl delete pods"
alias kdd="kubectl delete deployments"
alias kds="kubectl delete services"
alias kl="kubectl logs"
alias kc="kubectl create -f"
alias ke="kubectl exec -it"

#### GO VARIABLES
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
export GOPROXY=http://goproxy.sas.com:3000
export GONOSUMDB=*.sas.com

