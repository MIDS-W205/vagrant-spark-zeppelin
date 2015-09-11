#Vagrant + Spark + Zeppelin + Hadoop a Toolbox to the Data Analyst
Modified for UCB MIDS W205 Students
##Instructions
The following instructions are based on a step by step guide that is available with the blog post: [Vagrant + Spark + Zeppelin a Toolbox to the Data Analyst](http://arjon.es/2015/08/23/vagrant-spark-zeppelin-a-toolbox-to-the-data-analyst/)

###Installation
You will install VirtualBox VM and Vagrant<BR>

1. You will need VM software for Vagrant to create its configured VM's.  Head over to VirtualBox, download the installer for your OS and install.  https://www.virtualbox.org/wiki/Downloads
2. If you have never installed Vagrant before, head on over to the vagrant downloads page, select the installer for your OS and install.  http://www.vagrantup.com/downloads
3. Now check the version of Vagrant in your terminal with the command: ```vagrant version ``` and it should return to you a version that is greater than 1.5

###Configuration
To create the VM with Vagrant, we will need the Vagrant settings which tell the VM all the libraries it needs to install.  
1. Clone this repository to your local computer with the following command:


##Acknowledge
This is an installation of Apache Spark and Apache Zeppelin based on Debian [debian/jessie64](https://atlas.hashicorp.com/debian/boxes/jessie64)
`bootstrap.sh` was inspired by [gettyimages/docker-spark](https://github.com/gettyimages/docker-spark)

###Examples Datasets
There are a few datasets [available here](./data/).

