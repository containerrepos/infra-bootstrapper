
$git clone https://github.com/containerrepos/ansible.git

$cd ansible

$ansible-playbook plays/cicd.yml

$docker image build -t my .

$docker container run -it --net=host -v /root/.ssh:/hostssh my
