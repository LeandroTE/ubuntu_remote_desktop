# ubuntu_remote_desktop
Ansible playbook to configure a Ubuntu machine as a remote desktop

It is important to run the base role only one time.

## How to Set up the enviroment ##

Create a python enviroment and install the required packages ###

```
python3.10 -m venv ubuntu_env
```

After creating the enviroment activate it.

```
source ubuntu_env/bin/activate
```

after the enviroment is activated install all packages required

```
pip install -r requirements.txt
```

# Deployment

Activate the ansible enviroment and run

* Important change the user password in the base role


```
ansible-playbook deploy.yml
```
