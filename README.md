# SSH-to-your-server-from-anywhere-
ssh to your server from anywhere using linux

Install OpenSSH:

RedHat family

sudo dnf install openssh-server

Debian family

sudo apt-get install openssh-server

Enable SSHD:

sudo systemctl enable sshd

After enabling, start the SSH server with:

sudo systemctl start sshd


To verify that the SSH server is running correctly, you can check its status:

systemctl status sshd

Login to your SSH for the first time by:

ssh localhost
choose YES
choose a password for your ssh server

Find your Public IP address in terminal by:

curl https://ipinfo.io/ip
XXX.XXX.XXXX.XXXX

Now try ssh from your phone to connect to your server 

Iphone users Download Termius app from App Store  and follow below
where you see IP or Hostname type your "PUBLIC IP"
where you see Username type the host name host name in the linux terminal (ex. mine is centos) ---->  [centos@localhost ~]$  <----
where you see Password its the one of the ssh you just choose 

now you should be connected
