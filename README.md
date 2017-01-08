# WordPress-Ansible
An Ansible script to install latest Wordpress on Ubuntu 16.04 LTS

### How to build the playbook


### HowTo
Open your wp-config.php file, locoed at the root of your WordPress installation, and add the following snippet:
define(‘UPLOADS’, ‘wp-content/myimages’);

Make sure you add this code before the line:
require_once(ABSPATH.’wp-settings.php’);


