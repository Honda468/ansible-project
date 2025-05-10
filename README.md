# Ansible LAMP Stack (Localhost)

## ✅ Setup Instructions
- Ensure Ansible is installed on your Fedora system.
- Extract the project and enter the directory.

## 🧾 Inventory Structure
- `inventory/localhost`: configured to run on your local machine.

## 🚀 Run the Playbook
```bash
ANSIBLE_CONFIG=./ansible.cfg ansible-playbook playbook.yml
```

## ⚠️ Notes
- Includes error handling using block, rescue, always.
- Uses handlers to restart Apache after changes.
- Designed for use only on localhost.
