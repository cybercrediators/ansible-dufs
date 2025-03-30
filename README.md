# Ansible dufs
(*WIP*) Small Ansible role to set up the [dufs](https://github.com/sigoden/dufs) (distinctive utility file server) using a systemd service (not the docker image). Checks if `cargo` is present, since a working `rust` installation is assumed. Currently works for and tested on Ubuntu 24.04

# Requirements
- Change the `default` config variables according to the project
- Check if `rustup` or `cargo` is already installed for the target `dufs` user

# Role Variables
- [defaults](./defaults/main.yml)

# Dependencies
None
