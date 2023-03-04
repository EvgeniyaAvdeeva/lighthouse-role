Lighthous role
=========

Copies Lighthouse from the Git repository and installs

Role Variables
--------------

In the file vars/main.yml:
* lighthouse_vcs: https://github.com/VKCOM/lighthouse.git
* lighthouse_access_log_name: lighthouse_access
* lighthouse_location_dir: ~/home/lighthouse
* nginx_user_name: "root"

Dependencies
------------

To open lighthouse on the host, the nginx web server will be launched with it
