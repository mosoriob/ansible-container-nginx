## ansible + docker + nginx upstream

### Howto

Install the required software

```
$ yum install -y python-pip
$ pip install docker-py
```

Run

```
ansible-playbook -i inventory.yml site.yml --tags common

### Todo

- Create a role to install pip
