## Java Installation Ansible Role

This role installs Java from package manager or manually.
It is preferably to use package manager installation since `unarchive` module does
not work well in my case.

### How to use

+ Set `java_manual` to false to run package manager installation.
+ Set Java vars to install the desired version.
+ The var `java_default` set to true installs the specified version and
sets it as default.