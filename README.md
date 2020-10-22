```
pip install jmespath passlib[bcrypt]
ansible-galaxy install -r roles/requirements.yml
ansible-galaxy collection install community.crypto
ansible-playbook site.yml
```