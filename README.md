#Vagrant + Spark + Zeppelin + Hadoop a Toolbox to the Data Analyst
Modified for UCB MIDS W205 Students
##Instructions
The following instructions are based on a step by step guide that is available with the blog post: [Vagrant + Spark + Zeppelin a Toolbox to the Data Analyst](http://arjon.es/2015/08/23/vagrant-spark-zeppelin-a-toolbox-to-the-data-analyst/).  Please check this blog if you have any issues during install that are not addressed below.  Furthermore, note that the instructions below are more specific to Unix/Mac enviornments.

###Installation
You will install VirtualBox VM and Vagrant<BR>

1. You will need VM software for Vagrant to create its configured VM's.  Head over to VirtualBox, download the installer for your OS and install.  https://www.virtualbox.org/wiki/Downloads
2. If you have never installed Vagrant before, head on over to the vagrant downloads page, select the installer for your OS and install.  http://www.vagrantup.com/downloads
3. Now check the version of Vagrant in your terminal with the command: ```vagrant version ``` and it should return to you a version that is greater than 1.5

###Configuration
To create the VM with Vagrant, we will need the Vagrant settings which tell the VM all the libraries it needs to install.  The vagrant file located in the following github will provide those settings.
1. ```cd /home/username/repos``` - Change into a directory where you want to clone the repo containing the vagrant settings. 
2. Clone the repository to that directory: ```git clone https://github.com/MIDS-W205/vagrant-spark-zeppelin.git```
3. ```cd vagrant-spark-zeppelin``` - Change into the cloned directory
4. ```vagrant up``` - Build the vagrant VM
5. 

###Possible Issues


##Acknowledge
This is an installation of Apache Spark and Apache Zeppelin based on Debian [debian/jessie64](https://atlas.hashicorp.com/debian/boxes/jessie64)
`bootstrap.sh` was inspired by [gettyimages/docker-spark](https://github.com/gettyimages/docker-spark)

###Examples Datasets
There are a few datasets [available here](./data/).

