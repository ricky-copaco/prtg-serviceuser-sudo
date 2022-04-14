# prtg-serviceuser-sudo
Only run PRTG commands and no other commands as root for PRTG service user (passwordless) to prevent having to give full root access to the user.

How to:
Save as /etc/sudoers.d/svc_prtg_core or execute this: echo "svc_prtg_core ALL=(ALL) NOPASSWD: /var/prtg/scripts/*" > /etc/sudoers.d/svc_prtg_core
