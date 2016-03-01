# centos_puppetclient_v3.8
Repo for sharing Vagrantfile that creates a Centos 6.7/Puppet v.3.8 client for Puppet Module development
Vagrantfile for a Centos67 vm with puppet client for developing puppet modules

Instructions (if you're new to Vagrant):

    git clone https://github.com/fortunecookiezen/centos_puppetclient_v3.8.git
    cd centos_puppetclient
    vagrant up --provider virtualbox or
    vagrant up --provider vmware_workstation
    vagrant ssh or use Putty to connect to localhost:2222
