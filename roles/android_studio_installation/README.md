## Android Studio installation Ansible Role

This role installs Ansroid Studio through package manager, umake or manually.
It is preferably to use package manager installation since `unarchive` module does
not work well in my case. Umake installation works generally well, but it is not
performed very properly.

### How to use

+ Set `android_studio_package_manager` to true to run package manager installation
and others to false.
+ Set `android_studio_manual` to true to run manual installation
and others to false.
+ Set `android_umake` to true to run umake installation
and others to false.
