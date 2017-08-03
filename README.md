# KTGDEEPDEV Mac Local Dev Laptop & Ubuntu Development Node (Virtual on Mac)

Steps:
1. Prepare Mac Dev laptop follow this blog:
2. Connect to your base image and run the follwing scripts

Login in using terminal or virtual box (not docker yet)  This will just setup our base ubuntu dev image.

cd $HOME
sudo apt-get install -y git-core
git clone https://github.com/koverus/KTGDEEPDEVIMAGE.git
./setup.sh   

git clone https://github.com/koverus/KTGDEEPDEVIMAGE.git
ln -sb .screenrc .
ln -sb .bash_profile .
ln -sb .bashrc .
ln -sb .bashrc_custom .
mv .emacs.d .emacs.d~
ln -s .emacs.d .


Machine definitions:
A directory structure is expected as follows: 
/Users/<username>/Documents/Docker/<machine-name>/
/Users/<username>/Documents/Docker/DockerFiles  *Source Docker Files

With Files
<machine-name>/machine.env
<machine-naem>/docker-compose.yml




