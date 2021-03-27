# Jitsi

## About Jitsi

Jitsi is a collection of free and open-source multiplatform voice (VoIP), 
video conferencing and instant messaging applications for the web platform,
Windows, Linux, macOS, iOS and Android.


## Ansible
I create ansible roles for easy way to install and configure jitsi for self-hosting

## Vagrantfile.try

Vagrantfile.try is example how it should be minimum installed

To try Vagrantfile.try you need to do:

      sudo echo "192.168.33.10  jitsi.example.com" >> /etc/hosts
      mv Vagrantfile.try Vagrantfile
      vagrant up

And after download vagrant box and starting Vagrantfile you need to go on your browser:
      jitsi.example.com
