This Ansible playbook is a modified version of a previous playbook I made to join CentOS 7 machines to an Active Directory domain (see https://github.com/Omar-Khawaja/ansible_centos7_joinAD for the original playbook). You can use Ansible-pull with this repo. For more information on Ansible-pull, please see http://docs.ansible.com/ansible/playbooks_intro.html#ansible-pull

The secrets in this playbook are managed using Credstash. This playbook uses Ansible's Credstash lookup function (http://docs.ansible.com/ansible/playbooks_lookups.html#the-credstash-lookup).

For more information on Credstash in general, see the following link:
https://blog.fugue.co/2015-04-21-aws-kms-secrets.html
