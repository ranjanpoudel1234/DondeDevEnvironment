DondeDevEnvironment

i) Install Vagrant
ii) Install Virtual box Oracle(https://www.virtualbox.org/wiki/Downloads)
iii) Get latest of DondeDevEnvironment
iv) Install vbguest plugin ```vagrant plugin install vagrant-vbguest```
v) Install plugin vagrant-docker-compose https://github.com/leighmcculloch/vagrant-docker-compose
iv) run vagrant provision, this should install docker.
v) vagrant up, vagrant ssh
vi) docker-compose pull
vii) docker-compose up -d. You should have docker container.
