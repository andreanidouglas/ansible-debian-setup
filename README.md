# Ansible Debian Dev Workstation Setup

This is a simple ansible package to configure any debian compatible distro

Contains: 
* Rust (using rustup - default to nightly)
* Golang (from go.dev)
* Python (with virtualenv and venv)
* C/C++ (cmake, make, meson, ninja)
* NodeJs (using nvm)
* Neovim (with Plug)

# Usage:

```bash
$ ansible-playbook -K main.yml
```
