## system-setup-basics Ansible role

This role installs some basic packages and other useful tools like `autojump`.
A default git configuration is given. It is also supported zsh installation.

### How to use

+ Create your own list by defining the list var `basic_packages` or add more.
If you prefer, you can use the given by default.
+ To skip zsh installation and git and autojump configurations, just
remove these packages form `basic_packages` list.
+ Zsh may require more actions or a system reboot.