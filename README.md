# ansible-newrelic-sysmond
## New Relic Server Monitor Daemon role for Ansible
Disclaimer - this is just barely worthy of being called a role. It's basically
a 5 line shell script, that is slightly more convenient to run as a role.

Running this couldn't be simpler. Just edit the tasks/main.yml and enter in
your licence, then call the role from a playbook. Boom. You're done. Never have
to think about it again.

If you put it in version control with your license in it, don't forget to use
Ansible Vault!

# Requirements
The only thing you need is a New Relic license. 

# Distros tested
- Ubuntu 14.04
- Ubuntu 12.04

It should work on any reasonably current Ubuntu or Debian host.
