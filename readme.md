# iDocker - Docker for Mac within a Ubuntu VM.

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

