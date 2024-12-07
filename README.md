# linux_cli_tools

## screen
- alt + a is main key combination
- screen is part of epel repo and epel-relase pkg
- screen -r to list all screen sessions
- alt + a + Tab to switch tabs
- alt + a + shift + | or s for vertial or horizontal split
- screen -r scereen_id to reattach the session 

## ssh/telnet
- port 22
- cmd:: ssh user@ip_addr
- sshd service needs to be running on server machine for ssh connection
- systemctl start/stop/status sshd
- work as server client

## rsync
- for backup/copy/sync server files on bakup server
- port 22
- users ssh protocol, so no client-server file required
- cmd:: rsync commnad_options source destination
- file transfer: rsync -zvh backup.tar /tmp/backups/ or dest_dir
- directoy: rsync -azvh /home/backup/ dest_dir or patelra1@ip_addr:dest_directory

## 
