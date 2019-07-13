# Machine provisioning

# Prereqs
1. use python 3.7
1. install pipenv
1. `pipenv install`
1. `pipenv shell`
1. install [bitwarden cli](https://github.com/bitwarden/cli)


# Run playbook
1. as default `mike` user
    - `ansible-playbook -i production devboxes.yml -b -K --become-user=mike`
### notes:
1. use inventories to separate dev vs server machines

### TODO:
1. add `requirements.txt` for installation of `pipenv`
1. declare dependencies between roles?
1. add content to base readme
1. add notes to role readmes
1. find way to aggregate dependencies from all roles
1. add script for
    1. install dependencies
    2. checking for bw cli/unlocking bitwarden vault
    

## Reference
1. [ansible best practices](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html#content-organization)