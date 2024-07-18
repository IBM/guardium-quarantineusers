# Ansible Playbook README

## Prerequisites

- Ansible installed on your control node.
- Necessary permissions to access the CSV file and execute REST API commands.
- The `community.general` collection should be installed.

## How to Run

1. **Update the Variables**: Edit `vars.yaml` to include the correct values for your environment.

2. **Execute the Playbook**:

   ```bash
   ansible-playbook main.yml
