# Usage
`ansible-playbook <playbook-filename> -i <inventory-directory-name>`

## Examples
`ansible-playbook schedule_ping.yml -i inventory`
`ansible-playbook docker_install.yml -i inventory`

# Variables
- docker install variables are available in group variables directory: `group_vars/raspberry_pi/docker-settings.yml`
    - `docker-version` - set which docker version should be installed