# Install-chrome-ubuntu-server
How to install google chrome on ubuntu server headless install?
(This command assumes you have logged in as root, or have made yourself root using "sudo -s")

```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
dpkg -i google-chrome-stable_current_amd64.deb
apt install -f
```
Confirm with "y" to start the installation process.
