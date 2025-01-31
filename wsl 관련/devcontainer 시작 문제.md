vim /etc/wsl.conf
증상: sh: 1: /mnt/c/Users/<유저명>/.vscode/extensions/ms-vscode-remote.remote-wsl-0.88.5/scripts/wslServer.sh: Permission denied
####
"boot"
systemd=true
"user"
default=root
####

root외에 다른걸로 되어있으면 root로 바꿔주면 에러 해결 가능