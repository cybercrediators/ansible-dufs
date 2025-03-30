# Ansible dufs
(*WIP*) Ansible role to set up the [dufs](https://github.com/sigoden/dufs) (distinctive utility file server) (not the docker image). Installs `rustup` and `cargo` if not present, which _might_ be removed shortly. Currently works for and tested on Ubuntu 24.04

- Set the config variables according to the project
- Check if `rustup` or `cargo` is already installed for the target `dufs` user
