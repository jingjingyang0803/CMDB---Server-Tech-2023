# CMDB - Server Tech 2023 - Jingjing Yang


## Description
This repo is for storing the configuration of my two servers on POUTA - `jingjing-serverb-2023` and `jingjing-nfs-server`.

Informaion about system installed packages for each server are placed in `docs` directory.

## Directory structure
```
.
├── README.md
├── docs
│   ├── jingjing-nfs-server
│   │   └── apt_installed.txt
│   └── jingjing-serverb-2023
│       └── apt_installed.txt
├── jingjing-nfs-server
│   ├── etc
│   │   ├── exports
│   │   ├── sudoers.d
│   │   │   └── 91-stec-nfs
│   │   └── ufw
│   │       ├── ufw.conf
│   │       ├── user.rules
│   │       └── user6.rules
│   └── var
│       └── spool
│           └── cron
│               └── crontabs
│                   └── root
└── jingjing-serverb-2023
    ├── etc
    │   ├── apache2
    │   │   ├── apache2.conf
    │   │   └── sites-available
    │   │       ├── 000-default.conf
    │   │       ├── default-ssl.conf
    │   │       └── tips.jingjing.ilab.fi.conf
    │   ├── apt
    │   │   └── apt.conf.d
    │   │       └── 50unattended-upgrades
    │   ├── bash.bashrc
    │   ├── fstab
    │   ├── hosts
    │   ├── inputrc
    │   ├── letsencrypt
    │   │   ├── cli.ini
    │   │   ├── options-ssl-apache.conf
    │   │   └── renewal
    │   │       └── jingjing.ilab.fi.conf
    │   ├── passwd
    │   ├── pm2-jingjing.service
    │   ├── ssh
    │   │   └── sshd_config
    │   ├── sudoers.d
    │   │   ├── 90-cloud-init-users
    │   │   ├── 91-stec22-users
    │   │   └── README
    │   └── ufw
    │       ├── ufw.conf
    │       ├── user.rules
    │       └── user6.rules
    ├── opt
    │   └── totd
    │       ├── README.md
    │       ├── linuxtips.sh
    │       └── tips
    │           ├── 1.txt
    │           ├── 10.txt
    │           ├── 2.txt
    │           ├── 3.txt
    │           ├── 4.txt
    │           ├── 5.txt
    │           ├── 6.txt
    │           ├── 7.txt
    │           ├── 8.txt
    │           └── 9.txt
    └── var
        ├── spool
        │   └── cron
        │       └── crontabs
        │           └── root
        └── www
            ├── html
            │   └── index.html
            └── tips.jingjing.ilab.fi
                ├── files -> /opt/stec/tip-of-the-day-1.0-bash-script/tips
                ├── index.html
                ├── tips -> /opt/stec/tip-of-the-day-1.0-bash-script/tips
                └── txt -> /opt/stec/tip-of-the-day-1.0-bash-script/tips

32 directories, 48 files
```
