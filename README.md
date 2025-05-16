# Ansible Server Update Playbook

This is a Ansible project to update a remote AWS server.

## Files

- `inventory.ini`: Defines the server and SSH settings.
- `update.yml`: Ansible playbook to update the server and install packages like Apache.

## Usage

1. Install Ansible `sudo apt install ansible`.
2. Update your private key path in `inventory.ini`.
3. Run the playbook:

    ```bash
    ansible-playbook -i inventory.ini update.yml
    ```