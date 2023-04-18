#Ensure that you have the required collection installed. You can install the cisco.nxos collection from Ansible Galaxy

ansible-galaxy collection install cisco.nxos

#Vars
Update vars in snmp3_vars.yml 

#Usage

ansible-playbook -i hosts.ini add_snmpv3_users_nxos.yml

