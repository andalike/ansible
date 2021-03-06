# ansible

#In case of Older OS use this commans (export LC_ALL=C)

#In case pid does not work
sudo apt-get remove --purge python-pip
sudo apt-get autoremove
sudo rm -f /usr/local/bin/pip
sudo easy_install pip=20.3.4
sudo easy_install pip==20.3.4
pip --version
