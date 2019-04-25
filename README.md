# Puppet Development Environment:
```
Prerequisites:
- Vagrant
- Virtualbox v5.x
```
# Basic setup instructions

Create node definitions in manifests/default.pp

Add any modules into the Puppetfile

Clone any modules you want to develop into the modules directory

To bootstrap a server, run `vagrant up`. To re run puppet with any changes run `vagrant provision`

There are 5 different OS in the servers.yaml the user can test based on their preferences or the production environment they're trying to replicate





