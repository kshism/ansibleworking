# ansibleworking
ansible working

Hurry We are setup

ansible all -m gather_facts -u kshama --limit vm1
git status
git add .
git commit 
git commit -m "ansible.cfg"

ansible all -m apt -a "update_cache=true" -u kshama --become --ask-become-pass
ansible all -m apt -a "update_cache=true" -u kshama --become --ask-become-pass
ansible all -m apt -a "name=vim-nox" -u kshama --become --ask-become-pass
ansible all -m apt -a "name=snapd" -u kshama --become --ask-become-pass
ansible all -m apt -a "name=snapd state=latest" -u kshama --become --ask-become-pass
ansible all -m apt -a "upgrade=dist" -u kshama --become --ask-become-pass

