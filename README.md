# How to use this
1. vagrant up
2. vagrant ssh machine1
3. cd /vagrant
4. ansible-playbook setup_swarm.yml
. Done
*Keep in mind this will take some time to run, so please be patient*


## To use swarm
1. sudo docker service create -p 8080:80 --name nginx nginx:latest
. Done
