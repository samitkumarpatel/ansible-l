# ansible-l

- [ansible getting started](https://docs.ansible.com/ansible/latest/)
- [Installation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installation-guide)

  The easiest way to install, If you have python3 installed on your machine:
 > For Linux and Mac
  ```sh
    python3 -m venv <virtual-env-name>
    # Once done, activate it
    source <virtual-env-name>/bin/activate
    # try If all your expected python tool are pointed to the virtual env or not
    which python3 # This path should show python3 inside to your virtual env
    # Install ansible
    pip3 install ansible
  ```
  > For Windows
  ```
  python3 -m venv <virtual-env-name>
  # one time execution
  Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process -Force
  ./<virtual-env-name>/bin/Activate.ps1
  ```
  
- after the installation, ansible will give various command like `ansible`, `ansible-playbook`, `ansible-config`, `ansible-doc` and etc ... For each,  the documents are available [here i.e. Working with ansible command line](https://docs.ansible.com/ansible/latest/command_guide/command_line_tools.html) as well as:

  - [ansible | ansible AdHoc command](https://docs.ansible.com/ansible/latest/command_guide/intro_adhoc.html#intro-adhoc)
  - [ansible-playbook](https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html#ansible-playbook)
  - [ansible-config](https://docs.ansible.com/ansible/latest/installation_guide/intro_configuration.html#intro-configuration)
  - [ansible-console](https://docs.ansible.com/ansible/latest/cli/ansible-console.html)
  - [ansible-doc](https://docs.ansible.com/ansible/latest/cli/ansible-doc.html)
  - [ansible-galaxy](https://docs.ansible.com/ansible/latest/cli/ansible-galaxy.html)
  - [ansible-inventory](https://docs.ansible.com/ansible/latest/cli/ansible-inventory.html)
  - [ansible-playbook](https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html)
  - [ansible-pull](https://docs.ansible.com/ansible/latest/cli/ansible-pull.html)
  - [ansible-vault](https://docs.ansible.com/ansible/latest/cli/ansible-vault.html)
- [ansible cheatsheet](https://docs.ansible.com/ansible/latest/command_guide/cheatsheet.html)

- [ansible configuration i.e. about ansible.cfg](https://docs.ansible.com/ansible/latest/installation_guide/intro_configuration.html#intro-configuration)
- [ansible inventory](https://docs.ansible.com/ansible/latest/inventory_guide/index.html)
- [ansible playbook, in details](https://docs.ansible.com/ansible/latest/playbook_guide/index.html)
- [ansible vault, in details](https://docs.ansible.com/ansible/latest/vault_guide/index.html)
- [ansible modules & plugins](https://docs.ansible.com/ansible/latest/module_plugin_guide/index.html)

  - [plugins](https://docs.ansible.com/ansible/latest/collections/all_plugins.html#all-modules-and-plugins)
  - [modules](https://docs.ansible.com/ansible/latest/collections/index_module.html)
