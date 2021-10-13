
$git clone https://github.com/containerrepos/ansible.git

$cd ansible

$docker image build -t my .

$docker container run -it --net=host -v /root/.ssh:/hostssh my
