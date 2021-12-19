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
cd ansible-update
ansible-playbook -i inventory apt.yml
```
