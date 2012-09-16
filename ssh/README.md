ssh
===

Adds config for openssh. The config options are in options and
this is the only file under version control. In `bash/bash_profile`
the options will be mixed together with any `hosts.local` file to
make your ssh/config. This avoids putting sensitive host information
in your public dotfiles repo.

To use, add the following to **dotsyncrc**

    [files]
    ..
    ssh
    ..
    [endfiles]

