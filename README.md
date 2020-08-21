# ansible_playbook_iptv_analyzer
Playbook to install the role iptv_analyzer on localhost


# Prerequestics
* sudo apt update && sudo apt upgrade
* sudo apt install git python3-pip
* pip3 install ansible

# Clone this repository
git clone https://github.com/bsmeding/ansible_playbook_iptv_analyzer


# Use
* Logout and login again to get ansible in path
* cd ansible_playbook_iptv_analyzer
* ansible-galaxy install bsmeding.iptv_analyzer
* ansible-playbook install_iptv_analyzer_localhost.yml -i ./inventory --ask-become-pass

>> Give your sudo password

# Update iptv_analyzer:
ansible-galaxy install bsmeding.iptv_analyzer --force
