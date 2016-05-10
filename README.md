# conference-aws

ansible-playbook -i deploy webservers.yml -u ubuntu -vvvv


ansible-playbook -i deploy webservers.yml -u ubuntu -vvvv --tags "deploy"
