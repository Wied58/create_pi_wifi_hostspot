To update your GONet...

Install Ansible and Git localy on your pi: sudo apt-get install ansible git -y

If that commad errors, please update Raspian with: sudo apt-get update  -y &&  sudo apt-get upgrade  -y

To run the Playbook:

ansible-pull -d /home/pi/pull -i 'localhost,' -U https://github.com/Wied58/create_pi_wifi_hostspot create_pi_wifi_hostspot.yml


