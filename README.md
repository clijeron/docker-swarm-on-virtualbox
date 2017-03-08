# docker-swarm-on-virtualbox
This repo provides a quick guide on how to deploy Docker swarm on a MAC OS X using VirtualBox


Install Docker Machine
  	sudo curl -L https://github.com/docker/machine/releases/download/v0.10.0/docker-machine-`uname -s`-`uname -m` >/usr/local/bin/docker-machine && \ sudo chmod +x /usr/local/bin/docker-machine
    
    
Check that the installation is complete
    docker-machine version
      --> docker-machine version 0.10.0, build 76ed2a6  # Expected Result
    
Install Homebrew.  This is basically installing or updating the command line tools for XCode.
    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    
    
Check your brew installation
  	brew doctor
      --> Your system is ready to brew  # Expected Result
