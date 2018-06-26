# owncloud10client
Install owncloud 2.4 client on ubuntu 16.04 (for owncloud 10 support)


You can add the repository key to apt. 
Keep in mind that the owner of the key may distribute updates, packages and repositories that your system will trust (more information). 
To add the key, run:

<pre>
wget -nv https://download.opensuse.org/repositories/isv:ownCloud:desktop/Ubuntu_16.10/Release.key -O Release.key
sudo apt-key add - < Release.key
sudo apt-get update
</pre>

For Ubuntu 16.04 run the following:

<pre>
sudo sh -c "echo 'deb http://download.opensuse.org/repositories/isv:/ownCloud:/desktop/Ubuntu_16.04/ /' > /etc/apt/sources.list.d/isv:ownCloud:desktop.list"
sudo apt-get update
sudo apt-get install owncloud-client
</pre>
