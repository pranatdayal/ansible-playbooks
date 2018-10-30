# ansible-playbooks
Ansible playbooks for security monitoring and incident response 

## How to run install_osquery.yml
Run the following:
`ansible-playbook -i /etc/ansible/hosts install_osquery.yml --ask-become-pass`

## How to run incident_response.yml
Run the following:
`ansible-playbook -i /etc/ansible/hosts incident_response.yml --ask-become-pass`
