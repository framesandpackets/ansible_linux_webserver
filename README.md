# ansible_linux_webserver

Step 1: 
sudo apt install ansible

Step 2:
git clone https://github.com/framesandpackets/ansible_linux_webserver

Step 3:
cd ansible_linux_webserver

Step 4:
add IP address of your linux machines to 'hosts' file. You can find your IP address with ifconfig command

Step 5: 
create user on linux machine with username: ansible password: ansible or enter your username and password in hosts file

Step 6:
ansible-playbook webserver_install.yml


Once the installtions take place your machine will gracefully reboot. DON'T PANIC!
