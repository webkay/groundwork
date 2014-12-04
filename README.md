# README - Installation Instructions

---------------------------------

## Step Zero - Install Ansible

You can follow the instructions on the [Ansible website](http://docs.ansible.com/intro_installation.html#installing-the-control-machine) or either of the options below:

```
sudo easy_install pip
sudo pip install ansible
```


### OR (if you have homebrew)

`brew install ansible`

---------------------------------

## Step One - Virtualbox

Download [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and install.

---------------------------------

## Step Two - Vagrant

Download [Vagrant](http://www.vagrantup.com/downloads) and install.

---------------------------------

## Step Three - Repo

`git clone https://github.com/webapp-builders/groundwork.git`

---------------------------------

## Step Four

`cd groundwork`

---------------------------------

## Step Five

`vagrant up`

---------------------------------

## Step Six

`vagrant ssh`

---------------------------------

## Step Seven

`cd /vagrant/application/web`

---------------------------------

## Step Eight

`bundle install`

---------------------------------

## Step Nine

`bundle exec rspec spec`
