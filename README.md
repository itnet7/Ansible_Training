# Ansible_Training
This repo will be used to allow others to learn how to use ansible, leveraging vagrant.

To get started with lightbulb, the training environment to help with doing Ansible presentation, visit: 
https://github.com/ansible/lightbulb

Once you pull it down, you can go and install vagrant-mutant to convert the tower virtualbox image to kvm:
https://github.com/sciurus/vagrant-mutate

It seems like this project is looking for a new maintainer, but it worked for me in my setup. I am currently running Fedora 27 and was having some issues with some gem dependencies for nokogiri, which I was able to resolve by install the missing version number like this: 
gem install nokogiri '<version# in single quotes>'

I had a few other dependencies as well but resolved them by using whatprovides. 
