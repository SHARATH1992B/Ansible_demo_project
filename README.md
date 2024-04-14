# Ansible_demo_project

This repo is to setting up a developer pipeline using Ansible playbook.

Run the playbook using command:
"ansible-playbook -i inventory playbook.yml"


Note: In Jenkins Master setup of playbook.yml, i have added 'when' statement for some of the technologies. It provides conditional tasks to install those technologies on the Jenkins host machine only if the corresponding variables are set to true, if we feel some of those are not required we can set it to false.
