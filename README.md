# Ansible Debian Dev Workstation Setup

This is a simple ansible package to configure any debian compatible distro

Contains: 
* Rust (using rustup - default to nightly)
* Golang (from go.dev)
* Python (with virtualenv and venv)
* C/C++ (cmake, make, meson, ninja, clang)
* NodeJs (using LTS)
* Neovim (with Plug)
* Docker (Docker official repository)

# Usage:

Run all packages with: (except neovim and docker)

```bash
$ ansible-playbook -K main.yml
```

for node:

```bash
$ ansible-playbook -K main.yml --tags node
```

for neovim:

```bash
$ ansible-playbook -K main.yml --tags neovim 
```

for docker:

```bash
$ ansible-playbook -K main.yml --tags docker 
```
