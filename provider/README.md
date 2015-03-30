# Provider

In this Vagrantfile we run a docker provider and force it to use the phusion base box instead of the default boot2docker for MacOS/Windows.

## Why ?

It allows you to use the same docker host for Linux/MacOS/Windows which is usefull when developping in team.

## Info

This solution is slower than directly booting with the default one but I find it more clean.

Also now when doing `vagrant ssh` you will ener directly in the container and not the VM for that your container need ssh access.
You'll also need to generate an ssh key. But we will see that later...

## TODO

* Try with `rancherio/rancheros` (because this os look awesome)