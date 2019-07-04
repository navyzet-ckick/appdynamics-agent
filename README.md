# Ansible script for deploy appdynamics agent 


Deploy agent:
    
    ansible-playbook -D -l server1,server2 ./appdynamics.yml -e "archive_url=http://storage.com/machineagent.zip"

Remove agent:

    ansible-playbook -D -l server2 ./remove_appdynamics.yml