Build VM with Ubunutu 18.04
apt install -y ansible git openssh-server
ansible-playbook -i localhost pxe-setup.yaml
Make sure this server is the DHCP server
PXE boot machine to install
