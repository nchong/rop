We are going to try to follow this tutorial:

    http://blog.techorganic.com/2015/04/10/64-bit-linux-stack-smashing-tutorial-part-1/

1. Install ubuntu 14.10 VM

2. Set apt-get for older releases. See: http://askubuntu.com/questions/91815/how-to-install-software-or-upgrade-from-an-old-unsupported-release

    $ sudo sed -i -re 's/([a-z]{2}\.)?archive.ubuntu.com|security.ubuntu.com/old-releases.ubuntu.com/g' /etc/apt/sources.list

3. Install tools
    $ sudo apt-get update
    $ sudo apt-get install vim git

4. Clone this repo

    $ git clone
