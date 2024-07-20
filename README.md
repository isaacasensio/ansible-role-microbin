microbin 
=========

MicroBin is a feature rich, performant and secure text and file sharing web application, a "paste bin".

This Ansible role installs microbin as a Docker service.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

```
microbin_image: "danielszabo99/microbin:latest"
```
The version of the docker image to run as a container.
```
microbin_host_data_path: /var/lib/microbin
```
microbin data folder in the host machine
```
microbin_container_user: microbin
```
microbin container username
```
microbin_host_port: 8765
```
microbin host port
```
microbin_admin_username: admin
```
microbin admin username
```
microbin_admin_password: m1cr0b1n
```
microbin admin password

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - iasensio.microbin

License
-------

MIT

