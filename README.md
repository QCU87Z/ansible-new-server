# New Server setup

ansible-galaxy install -r requirements.yml -f

ansible-playbook -i hosts --ask-pass --ask-vault-pass 01-user.yml

ansible-playbook -i hosts 02-user.yml