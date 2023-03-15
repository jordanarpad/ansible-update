# ansible-update

#### Prerequisite:
`ansible` needs to be installed to use this repository. On Debian based distros `ansible` can be installed with the following command.
```
sudo apt update
sudo apt install ansible
```
#### Usage:
```
git clone https://github.com/jordanarpad/ansible-update.git
ansible-playbook -i ansible-update/inventory ansible-update/apt.yml
```
For names I use zeronsd as detailed in the following post:

https://myraspberrypiadventure.blogspot.com/2023/03/running-ansible-apt-via-zerotier-from.html
