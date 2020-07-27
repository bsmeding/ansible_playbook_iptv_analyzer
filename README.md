# ansible_playbook_iptv_analyzer
Playbook to install the role iptv_analyzer on localhost


# Prerequestics
sudo apt install git python3-pip
pip3 install ansible

# Install
git clone https://github.com/bsmeding/ansible_playbook_iptv_analyzer


# Use
cd ansible_playbook_iptv_analyzer
Logout and login again to get ansible in path
* ansible-galaxy install bsmeding.iptv_analyzer
* ansible-playbook install_iptv_analyzer_localhost.yml -i ./inventory --ask-become-pass

>> Give your sudo password

# Update iptv_analyzer:
ansible-galaxy install bsmeding.iptv_analyzer --force
