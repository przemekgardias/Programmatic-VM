# Programmatic-VM
This repo includes Vagrant file to set up a dev environment
## Set up
1. Clone this repo to your local machine
2. Clone [the other repo](https://github.com/drines-uc/hello_http/tree/main) to your local machine
3. In this repo update the first argument of `config.vm.synced_folder` in the Vagrantfile to point at the other repo
4. Run `vagrant up`
5. Install www.virtualbox.org to manage your VM
