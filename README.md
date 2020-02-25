generate ssh key or use existing SSH KEY
 for generate
mkdir -p ~/ssh_key/
ssh-keygen -q -b 2048 -t rsa -N "" -C "creating SSH" -f ~/ssh_key/my_SSH_key
# ansible
Ansible

ansible-playbook add_ssh.yml
