# iDocker - Docker for Mac within an Ubuntu VM.

## Requires:
* Vagrant - https://www.vagrantup.com/
* Virtual Box - https://www.virtualbox.org/

## Process:
1. Clone this repo. 
2. `cd` into directory
3. Run vagrant up

## Once done, run the following commands
1. `vagrant ssh`
2. `sudo usermod -aG docker ${USER}`
3. `exit`
4. `vagrant ssh`
5. Navigate to var/www/html
6. Clone repo, cd and then run make init

TODO: (Need to do this on all rebuilds)
Find a way to automate NVM install
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.0/install.sh | bash
nvm install 6.9.2
nvm alias default 6.9.2
npm install -g npm@3.10.9
