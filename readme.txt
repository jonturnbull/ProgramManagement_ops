Directory Structure
ProgramManagement
+—ProgramManagement_app (Rails app)
+-Program Management_ops (Deployment scripts)

Install Vagrant (Google Vagrant)
$vagrant box add pangolin http://files.vagrantup.com/precise64.box

#This downloads and adds the box to vagrant config

$cd ~\ProgramManagement
$mkdir puppetvm
$cd puppetvm


Install Facter, Hiera and Puppet (http://downloads.puppetlabs.com/mac/)