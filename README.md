# Ansible

### run playbook (default hosts.ini inventory)

    ansible-playbook setup-docker-ec2-user.yml

### run playbook (inventory_aws_ec2.yml inventory)

    ansible-playbook -i inventory_aws_ec2.yml setup-docker-ec2-user.yml

### run inventory graph

    ansible-inventory -i inventory_aws_ec2.yml --graph
