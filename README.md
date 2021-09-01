# ansible_training
My labs from Ansible Up and Running book

# Run ansible commands
ansible your_server -m command -a 'uptime' # send command uptime and get output
ansible your_server -b -m command -a 'cat /etc/passwd' # to become the root