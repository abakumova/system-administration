# System Administration [LTAT.06.003](https://courses.cs.ut.ee/2023/sa/spring)
## [Labs (material)](https://sysadmin.cs.ut.ee/):
- Lab 1 - Introduction
- Lab 2 - ETAIS
- Lab 3 - Ansible
- Lab 4 - DNS
- Lab 5 - Apache Web Services lab
- Lab 6 - Email lab
- Lab 7 - TLS
- Lab 8 - Filesystems
- Lab 9 - Containers
- Lab 10 - DevOps
- Lab 11 - Kubernetes
- Lab 12 - Monitoring

#### Playbook with variables and roles according to labs.
#### The host file contains ip of the VM.
### Command to run the playbook:
`ansible-playbook playbook.yml --key-file "~/private-key-file" -u centos -i inventory/hosts`

Install:
- ansible-galaxy collection install community.mysql
- ansible-galaxy collection install ansible.posix
- ansible-galaxy collection install community.general
- ansible-galaxy collection install community.docker
