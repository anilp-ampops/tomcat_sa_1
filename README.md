## Ansible Tomcat8 server installation

- Requires Ansible 1.2 or newer
- Expects CentOS/RHEL 7.x hosts

This is a basic implementation of basic implementation of Tomcat Application Server version 8 running on Centos 7.

To run this playbook, run the below command:

  ansible-playbook -i hosts site.yml

When the playbook execution completes, you will notice tomcat process running
Check configuration for application Server ports listening on target machines.
