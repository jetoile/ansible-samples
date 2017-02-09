My utils for my local VM on ubuntu 14.04.01-server ;)

Do not use for your project.

```bash
ansible-playbook setup.yml --ask-pass -K
ansible-playbook -l ubuntu1 setup.yml
ansible-playbook clean-docker.yml 
```
