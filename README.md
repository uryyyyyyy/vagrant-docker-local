vagrant-docker-local
====================

## setup

Virtualbox
Vagrant 1.6~

## useage

cd [each folder]

### use
sudo vagrant up --provider=docker

### stop
sudo vagrant destroy
// it' OK. because image is cached by docker

//if you use proxyVM, you should command below too
cd proxyVM
sudo vagrant halt

### check status
sudo vagrant global-status

## architecture

use vagrant 

### when HostOS have docker (like Ubuntu)

HostOS => Docker(vagrant interface)

### when HostOS haven't docker(like Windows, MacOS)

HostOS => proxyVM(vagrant interface) => Docker


