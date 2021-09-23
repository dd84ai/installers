 
apt update && apt install -y ansible && wget https://raw.githubusercontent.com/dd84ai/installers/master/docker.yml && wget https://raw.githubusercontent.com/dd84ai/installers/master/localhost && ansible-galaxy install geerlingguy.docker && ansible-playbook -i localhost docker.yml
