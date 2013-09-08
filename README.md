## Description

Practical tutorial about development with Vagrant.

## Quick Start

First, make sure you has installed [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
 (latest version) and [Vagrant](http://downloads.vagrantup.com/) (latesl version too)

The setup from that point forward is very easy:

    1. $ sudo sh -c 'echo "192.168.33.20   app.dev" >> /etc/hosts'
    2. $ git clone git@github.com:gustavobgama/Vagrant-Tutorial.git <your-folder>
    3. $ cd <your-folder>/machine && vagrant up
    4. Go get a cup of coffee...

## Try it

When finished, type in your browser `http://app.dev`. After this, edit files in folder `<your-folder>/code` and return to the browser to see results. Congratulations, you are developing on a virtual machine !!