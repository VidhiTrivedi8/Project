# Project

Step 1:
Installation of Ulfuis Framework:

Prerequisite: There should be a Linux environment

$ sudo apt install -y libmicrohttpd-dev libjansson-dev libcurl4-gnutls-dev libgnutls28-dev libgcrypt20-dev libsystemd-dev

$ wget https://github.com/babelouest/ulfius/releases/download/v2.7.0/ulfius-dev-full_2.7.0_debian_buster_x86_64.tar.gz

$ tar xf ulfius-dev-full_2.7.0_debian_buster_x86_64.tar.gz

$ sudo dpkg -i liborcania-dev_2.1.1_Debian_stretch_x86_64.deb

$ sudo dpkg -i libyder-dev_1.4.12_Debian_stretch_x86_64.deb

$ sudo dpkg -i libulfius-dev_2.7.0_Debian_stretch_x86_64.deb


Step 2: 
Clone the repository from the Git or install the zip file from the provided link. This will provide you with the necessary files to run the REST API.

Step 3:
Compile the required files using the Makefile provided. This will create the necessary executable files for running the REST API.

Step 4: 
Once the necessary files have been compiled, you can now transfer any JSON data between services using the REST API.



