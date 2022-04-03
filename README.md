# fedora_provision on fresh Fedora 35 OS
clone this project or copy paste content fedora_provision.yml file
Run:
1. sudo dnf -y install ansible 
2. as root: ansible-playbook fedora_provision.yml
3. *Note: add tags at end of some play for only that play and add --tags "tag_name" to ansible-playbook command
example: ansible-playbook fedora_provision.yml --tags mysql
