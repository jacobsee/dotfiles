dotfiles
========

This is my equivalent of a `dotfiles` repo - as an Ansible playbook!

Everything can be installed with:

`ansible-playbook local_env.yml --ask-become-pass`

Or a subset of things can be installed using tags:

`ansible-playbook local_env.yml --ask-become-pass --tags "virtualization"`

Or

`ansible-playbook local_env.yml --ask-become-pass --tags "rpmfusion, exfat"`