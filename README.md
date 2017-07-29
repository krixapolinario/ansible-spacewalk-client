Spacewalk Client
================

This project has the intention to automate installation of the Spacewalk client version 2.6 on CentOS 7 machines.


Prerequisites
-------------

  * CentOS 7 installed on target hosts;
  * Ansible 2.2.1.0 or higher.

Usage
-----

Clone this repository:

git clone https://github.com/krixapolinario/ansible-spacewalk-client.git

Adjust the configuration information to client on defaults/main.yaml
   * NOTE_1: If you don't set any one of those variables the instalation won't work.
   * NOTE_2: The variable spacewalk_server_fqdn needs to be a FQDN and you don't need to set the http:// or https://.

Resources
---------

Following links might be of value in case you are interested:

  * [spacewalk project page](http://spacewalkproject.org/),
  * [spacewalk wiki](https://github.com/spacewalkproject/spacewalk/wiki),
  * [ansible project page](https://www.ansible.com/),
  * [ansible documentation page](http://docs.ansible.com/ansible/).

