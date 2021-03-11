# Docker
Docker setup for AlcheDesk project. The fowwling tree will show the file structure of the project.

```
.
├── docker-compose.yml
├── atm
│   ├── app
│   │   ├── application.yml <ATM configuration file>
│   │   ├── ATM_API.conf <ATM application java configuration file>
│   │   ├── ATM_API.jar <ATM application jar>
│   │   └── atm-application.log <ATM log>
│   └── data <ATM database files>
├── cert
│   └── letsencrypt <sectificat location>
├── dnsrobocert
│   └── config.yml < dnsrobocert configuration file https://github.com/adferrand/dnsrobocert>
├── ems
│   ├── app
│   │   ├── application.yml <EMS configuration file>
│   │   ├── EMS_API.conf <EMS application java configuration file>
│   │   ├── EMS_API.jar <EMS application jar>
│   │   └── ems-application.log <EMS log>
│   └── data <EMS database files>
├── php
│   └── config 
│       └── php.ini <php configuration file>
├── samba
│   ├── result <result files location>
│   └── upload <location ofr user to updaload files>
└── web
    ├── config
    │   └── site.conf <niginx configuration file>
    ├── data
    │   └── db <WebUI database>
    ├── log
    │   ├── access.log <Nginx access log>
    │   └── error.log <Nginx Error log>
    └── www
        ├── .env <Little boy configuration file>
        └── ***<all Little boy project files here>
```
