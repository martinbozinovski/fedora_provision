# fedora_provision on fresh Fedora 35 OS
clone this project or copy paste content fedora_provision.yml file
Run:
sudo dnf -y install ansible 
as root: ansible-playbook fedora_provision.yml
*Note: add tags at end of some play for only that play and add --tags "tag_name" to ansible-playbook command
