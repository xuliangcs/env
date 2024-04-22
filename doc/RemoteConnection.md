# vsftp
```shell
sudo apt-get install vsftpd
```
> ftp xxx.xxx.xxx.xxx 




Configurations:

/etc/vsftpd.conf

sudo ufw allow 21/tcp
sudo ufw allow 61001:62000/tcp

adduser xxx

/etc/allowed_user

service vsftpd reload
service ufw reload

poert 20 data,  21 command

ref:
[1] https://blog.csdn.net/qq_41017452/article/details/123695442



--

## SSH
openssh

```bash
ssh-keygen -t rsa -C "username@pcname"
```
- generated folder: `~/.ssh/`
- generated files: 
    - `id_rsa`
    - `id_rsa.pub` (give to server)
    - `config` (easy to connect, otherwise you need incomplete command line arguments, e.g., `ssh user@xxx.xxx.xxx.xxx`)
    - `known_hosts` (as a client)
    - `authorized_keys` (as a server)

tips:
- `ssh+ip`, need enter `username` and `pwd`
- `ssh+username@ip`, use ssh to login 

`config`:
```bash
Host xxx
    HostName xxx.xxx.xxx.xxxx
    Port xxxx
    User xxx
    IdentityFile xxx/.ssh/id_rsa
```

tips: If there are multiple users (such as root or git) on the server, you must specify the home directory of the authorized user's `.ssh`. In addition, `git` user are not allowed to log in to the shell terminal.