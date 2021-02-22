# Run the playbook
```
ansible-playbook -l [target] -i [inventory file] -u [remote user] playbook.yml
```
example:
```
ansible-playbook playbook.yml -l server1 -u sammy
```
