1. run ping module to all hosts: `ansible all -m ping`

ansible playbook is a collection of tasks that are executed in sequence.

## Troubleshoots

1. `"Missing sudo password"`: use option -K when run playbook
2. `sshpass` is need to be installed with `ssh` connection type with password using for `become`
