## PyCharm Installation Ansible Role

Installs PyCharm through package manager or manually. It
is generally design for community versions. It is preferably
to use package manager installation since `unarchive` module does
not work well in my case.

This role does not install Python.

### How to use

+ Set `pycharm_manual` to false to run package manager installation.
+ Set PyCharm vars to change your version.