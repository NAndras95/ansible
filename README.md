# ansible

### Run the playbook
```
ansible-playbook -l [target] -i [inventory file] -u [remote user] playbook.yml
```
example:
```
ansible-playbook playbook.yml -l server1 -u myuser
```

run on local machine
```
# hosts
127.0.0.1 ansible_connection=local
```
run install
```
ansible-playbook --connection=local --inventory 127.0.0.1, playbook.yml
```

