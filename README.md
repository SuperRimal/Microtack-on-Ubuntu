# Microtack-on-Ubuntu
Installing and Running Virtual Machine on Microstack

# Requirements:
Ubuntu 20.04 or 21.04 LTS 

6 processors, may also work in 4

More than 4GB of RAM (In my case I used 5.3GB)

## Installing Mictostack
sudo snap install microstack --devmode --beta

When installtalation is completed, below dialog will appear

microstack (beta) ussuri from Cannonical installed

## Intialization of Mircostack
sudo microstack init --auto --control  (it may take some time)

## Accessing Openstack
sudo snap get microstack config.credentials.keystone-password

Username is Admin

(Password in My case)
OAEHxLgCBz7Wz4usvolAAt61TrDUz6zz'

## To Disable and Enable microstack servcies
sudo snap disable microstack

sudo snap enable microstack

# You can access Openstack dashboard on

https://10.20.20.1
