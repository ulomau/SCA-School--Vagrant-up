# SCA-School--Vagrant-up
# This is a repository of how to Install and get Vagrant up and running.
# Vagrant is a portable environment container for developing and running your applications. These environment are tiny virtual machines.
# To be able to use Vagrant you need to install both Vagrant and a virtualbox 
# You can download and install Vagrant from WWW.vagrantup.com and also download and install Virtualbox at www.virtualbox.org
# Once installed, run the command "vagrant-v" in the vagrant terminal this will list the version of vagrant installed 
# Go to WWW.vagrantup.com and click on find boxes, and choose a vagrant box to work with ( i used Ubuntu/Trusty64) as the OS
# Open your favourite IDE ( i used VS code)
# In the vagrant terminal run the command "vagrant init ubuntu/trusty64" this will create a vagrant file. If you open the editor now you will see the file 
# Run the command "vagrant up" This will start the vagrant box running. 

# Note: there are five main parts of vagrant box that make it to run succesfully, these includes:
# 1. Config.vm.box  = The Operating system
# 2. Config .vm.provider  = Virtual box
# 3. Config.vm.network
# 4. Config.vm.synced_folder
# 5. Config.vm.provision.
