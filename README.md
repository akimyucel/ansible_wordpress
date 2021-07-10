## Wordpress Installation with Ansible

### Prerequisites

### Package Requirements
Webserver
```
Wordpress Version: 5.7.2
PHP Version: 7.4 or greater
Mysql Version: 5.6 or greater
MariaDB Version: 10.1 or greater
Apache/2.4.37 (centos)
```

Database
```
MariaDB Server Version: 10.3.29
MySQL Version: 5.6 or greater
```

#### Server Requirements
Webserver
```
Operating System: CentOS 8
CPU/RAM: 1 / 1GB
Storage: 10 GB or more
```

Database Server
```
Operating System: Ubuntu 20.04 
CPU/RAM: 1 / 1GB
Storage: 10 GB or more
```

### Diagram

### Directory Structure
```
.
├── dev_inventory.yaml
├── LICENSE
├── playbooks
│   ├── database.yaml
│   ├── packages1.yaml
│   ├── ping.yaml
│   ├── useradd_ansible.yaml
│   └── webserver.yaml
├── README.md
└── variables
    ├── database_vars.yaml
    ├── ping_vars.yaml
    └── webserver_vars.yaml
```