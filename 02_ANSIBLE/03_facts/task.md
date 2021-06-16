## Create own Playbook with ansible facts

Basing on the file `playbook.yaml` in previous task
1. install nginx only if operating system is ubuntu (use `when` stating propper fact)
2. put version the output of command `date` into `/root/output`


Find the propper modules from here https://docs.ansible.com/ansible/latest/collections/ansible/builtin/index.html#plugins-in-ansible-builtin

More information about ansible-facts https://docs.ansible.com/ansible/latest/user_guide/playbooks_vars_facts.html#vars-and-facts