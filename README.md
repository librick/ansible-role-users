# Ansible Role: Users
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit)](https://github.com/pre-commit/pre-commit)

This role sets up users on Debian-based Linux systems.

## Role Variables
See [defaults/main.yml](./defaults/main.yml).

## Dependencies
I recommend using a Python3 virtual environment (venv).  
`python3 -m venv venv`  
`source ./venv/bin/activate`  
`python3 -m pip install -r requirements.txt`

## Testing
Testing is performed using Molecule.  
See the [molecule](./molecule/) directory for more information.

## Linting
Linting is done automatically via [https://pre-commit.com/](https://pre-commit.com/).  
After setting up a virtual environment and installing `requirements.txt`, run  
`pre-commit run --all-files`  
See: https://github.com/ansible/ansible-lint  
See: https://github.com/pre-commit/pre-commit

## License

MIT Licensed

## Author Information

This role was created in 2023 by [Eric McDonald](https://juniperspring.xyz/).
