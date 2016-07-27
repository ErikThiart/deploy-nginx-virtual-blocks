# deploy-nginx-virtual-blocks #
Bash Script to create or delete nginx virtual hosts/blocks on ubuntu

## Global Installation ##

    $ cd /usr/local/bin
    $ wget -O virtualhost-nginx https://raw.githubusercontent.com/ErikThiart/deploy-nginx-virtual-blocks/master/virtualhost-nginx.sh
    $ chmod +x virtualhost-nginx
        
## Usage ##

    $ sudo virtualhost [create | delete] [domain] [optional host_dir]
      
### Examples ###

to create a new virtual host:

    $ sudo virtualhost create mysite.dev

to create a new virtual host with custom directory name:

    $ sudo virtualhost create anothersite.dev my_dir

to delete a virtual host

    $ sudo virtualhost delete mysite.dev

to delete a virtual host with custom directory name:

    $ sudo virtualhost delete anothersite.dev my_dir
