# Jitsi

## About Jitsi

Jitsi is a collection of free and open-source multiplatform voice (VoIP), 
video conferencing and instant messaging applications for the web platform,
Windows, Linux, macOS, iOS and Android.


## Ansible

Still in progress... I create ansible roles for easy way to install and configure jitsi for self-hosting

## Installation script
Having problem with configuration ansible roles for installation and configuration. I create quick install script

## Vagrantfile.try

Vagrantfile.try is example how it should be minimum installed

To try Vagrantfile.try you need to do:

      sudo echo "192.168.33.10  meet.example.com" >> /etc/hosts
      mv Vagrantfile.try Vagrantfile
      vagrant up

And after download vagrant box and starting Vagrantfile you need to go on your browser:
      meet.example.com
