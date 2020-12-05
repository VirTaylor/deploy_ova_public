# Python Requirements  
sudo apt-get install python3  
sudo apt-get install python3-pip  

# Ansible Requirements  
pip3 install pyvim  
pip3 install pyvmomi  

# Ansible Galaxy Requirements  
ansible-galaxy collection install community.vmware  


# Running Playbook  
1: Update site/common values within answerfile.yml  
2: Update device speciic values within inventory file  
3: ansible-playbook deploy_ova.yml -i inventory -l <host_group>   


