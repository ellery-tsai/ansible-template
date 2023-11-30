## Prerequisite

Install collections
```
ansible-galaxy collection install -r ./collections/requirements.yml \
                                  -p ./collections
```

Install python packages
```
pip3 install -r ./collections/requirements.txt
```

Create ansible.cfg
```
cp ansible.cfg.example ansible.cfg
```

### Run in console

```
ansible-playbook run_playbook.yml
```
