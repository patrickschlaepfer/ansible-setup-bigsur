# setup-bigsur

Before install python3.

https://flaviocopes.com/python-installation-macos/#:~:text=Go%20to%20https%3A%2F%2Fwww,Then%20click%20%E2%80%9CContinue%E2%80%9D%20again.

## Installation requirements

    ansible-galaxy install -r roles/requirements.yml

## Run playbook

    ansible-playbook -i inventory playbook.yml -K
