# Ansi

#Ansible documentation 

root@Ansible:~/Ansi# ansible all -i hosts -m ping
10.10.10.13 | SUCCESS => {
    "changed": false,
    "ping": "pong"
}
root@Ansible:~/Ansi# ansible all -i hosts -a uptime
10.10.10.13 | SUCCESS | rc=0 >>
 10:33:54 up 11 min,  1 user,  load average: 0.02, 0.02, 0.00

root@Ansible:~/Ansi#


