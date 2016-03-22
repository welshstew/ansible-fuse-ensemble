### Ansible Playbook for JBoss Fuse

#### Install instructions

- launch VM from RHEL 7.2 image with SSH authentication available
- copy `hosts.example` create an inventory file e.g. `hosts`, and configure IPs, SSH user, and SSH key
- configure `group_vars/all` with Red Hat credentials and whatever role variables you want to override
- execute the playbook e.g. `ansible-playbook -i hosts playbook.yml`
- verify Hawtio console at `http://[any-playhost]:8181/hawtio`


