# Example Ansible playbooks to deploy micromamba and create defined Python environments

Modify the vars section in the corresponding YAML files to set micromamba version, Python version, and Python libraries to install.
This is intended as an example or a starting point for further customization. Please clone and make any changes you need in your own repository.

## Install micromamba
`ansible-playbook install_micromamba.yml`

## Deploy Python environment
`ansible-playbook create_mamba_env.yml`

## Known Issues
1. This does not deploy shell hooks to .bashrc or .zshrc for easier interactivity with micromamba. My use case does not need this.