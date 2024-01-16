# ansible
ansible-playbook -i environment/inventory-efk-master.yml  -e @vars/efk-master-var.yml   efk-master-deploy.yml


ansible-playbook -i environment/inventory-td-agent.yml -e @vars/td-agent-var.yml td-agent-deploy.yml