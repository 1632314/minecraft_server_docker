# Ansible Role for deploying a minecraft server docker container
A role for deploying a minecraft server in a docker container. 
## Requirements
This role requires that docker-compose it's already installed on the target machine. For that you can use @geerlingguy rol for [docker](https://github.com/geerlingguy/ansible-role-docker).
## Role Variables
All the variables are directly extracted from the readme file for the [docker-minecraft-server](https://github.com/itzg/docker-minecraft-server/blob/master/README.md) github page. The current list is not complete and does not contain all the functionality present on the docker container.

To read an explanation of the variables related to minecraft(a.k.a. what can spawn, allowing nether...) you can read the [fandom.com page](https://minecraft.fandom.com/wiki/Server.properties) that also contains legal values for said variables.
