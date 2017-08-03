# KTGDEEPDEV Mac Local Dev Laptop & Ubuntu Development Node (Virtual on Mac)

First Run DEEPDEVSEUP.git
After you log in to your docker-machine node run:

cd $HOME
sudo apt-get install -y git-core
git clone https://github.com/koverus/KTGDEEPDEVIMAGE/setup.git
./setup/setup.sh   

See also http://github.com/startup-class/dotfiles 


Defines machines for docker-machine and their
compose files, while integrating the two via a small
shell script.

Machine definitions:
A directory structure is expected as follows: 
/Users/<username>/Documents/Docker/<machine-name>/
/Users/<username>/Documents/Docker/DockerFiles  *Source Docker Files

With Files
<machine-name>/machine.env
<machine-naem>/docker-compose.yml




