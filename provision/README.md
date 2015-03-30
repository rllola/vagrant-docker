# Provision

Vagrantfile with docker provisionning. It does only pull the `busybox` and run an `/bin/echo Hello World` command.

## Start VM

> vagrant up

## Why provision

So basically using provision with docker will allow you to download images or start a container in your environnement. 

For example, if you need a quick database when developing your django app or whatever. It would easily make it run for you if you don't have an existing docker host.

For more info on docker provisioner : [http://docs.vagrantup.com/v2/provisioning/docker.html](http://docs.vagrantup.com/v2/provisioning/docker.html)

## TODO

* Change `phusion/ubuntu-14.04-amd64` base box to `rancherOS` image (http://rancher.com/ | https://atlas.hashicorp.com/rancherio/boxes/rancheros) [Done]
