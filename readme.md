# Python Requirements  
sudo apt-get install python3  
sudo apt-get install python3-pip  

# Ansible Requirements  
pip3 install pyvim  
pip3 install --upgrade pyvmomi  

# Ansible Galaxy Requirements  
ansible-galaxy collection install community.vmware  


# Running Playbook  
1: Update site/common values within answerfile.yml.  
2: Update device specific values within inventory file.  
3: ansible-playbook deploy_ova.yml -i inventory -l <host_group>  

# Validation
Validated with Nested ESXI 7.0U1 (William Lam - VirtuallyGhetto) OVA and Cisco CSR (IOS XE 17.2). VAPP Properties names may change between versions. 

# Additional Information/Corresponding Blog Post
https://virtualizedtaylor.com/2020/12/05/automating-csr-and-esxi-deployments-with-ansible/




