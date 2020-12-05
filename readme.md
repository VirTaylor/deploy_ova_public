#Python Requirements
sudo apt-get install python3
sudo apt-get install python3-pip

#Ansible Requirements
pip3 install pyvim
pip3 install pyvmomi

#Ansible Galaxy Requirements
ansible-galaxy collection install community.vmware


#Running Playbook
update site/common values within answerfile.yml
update device speciic values within inventory file
ansible-playbook deploy_ova.yml -i inventory -l <host_group> 


