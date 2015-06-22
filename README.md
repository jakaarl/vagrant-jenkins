Jenkins CI on a VirtualBox
==========================

Box file can be created with the following steps:

1. Install Vagrant and VirtualBox on host system.
2. Run "vagrant init hashicorp/precise32".
3. Run "vagrant up".
4. Connect to virtual box ("vagrant ssh" or ssh to localhost:2222 user/pass vagrant/vagrant).
5. Install Jenkins, see: http://pkg.jenkins-ci.org/debian/
6. Install headless JRE 7: "sudo apt-get install openjdk-7-jre-headless".
7. On the host, run VirtualBox to see the name of the box.
8. Run "vagrant package --base <boxname>" to package the box.
 
