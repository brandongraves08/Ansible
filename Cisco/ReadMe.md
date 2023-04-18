#Ensure that you have the required collection installed. You can install the cisco.nxos collection from Ansible Galaxy

ansible-galaxy collection install cisco.nxos

#Usage

ansible-playbook -i hosts.ini add_snmp_strings_nxos.yml
