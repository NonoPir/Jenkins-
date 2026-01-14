scp -i C:\Users\YOUR_NAME\Downloads\ansible-key.pem `

C:\Users\YOUR_NAME\Downloads\ansible-key.pem `




scp -i C:\Users\YOUR_NAME\Downloads\ansible-key.pem `

C:\Users\YOUR_NAME\Downloads\Network_Ansible_lab.zip `

ubuntu@<CONTROLLER_PUBLIC_IP>:/home/ubuntu/



unzip Network_Ansible_lab.zip

mkdir Network_Ansible_lab

mv README.md group_vars inventory playbooks templates Network_Ansible_lab/

cd Network_Ansible_lab



sudo apt update

sudo apt install -y software-properties-common

sudo add-apt-repository --yes --update ppa:ansible/ansible

sudo apt install -y ansible

ansible --version
