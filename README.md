# ansible
Ansible playbooks

## Commands

cd /opt/ansible

ansible all -i inventory -m ping

ansible-playbook -i inventory.ini jenkins_ssl_proxy.yml

ansible-playbook -i inventory.ini install_jenkins.yml
