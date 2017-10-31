# README

Install Ruby on rails 

Paso 1: entrar como super root
su  
Paso 2
### Debian ###
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 
curl -sSL https://get.rvm.io | bash -s stable
source /etc/profile.d/rvm.sh

### Install Ruby ###
rvm requirements
rvm list known
rvm install 2.4.1
ruby -v

### Install Rails ### 

gem install rails
rails -v

### Install Node.js ###

apt-get -y install nodejs

### Install MYSQL ### 
cd Documents
wget https://dev.mysql.com/get/mysql-apt-config_0.8.6-1_all.deb
ls
dpkg -i ysql-apt-config_0.8.6-1_all.deb
apt update
apt install mysql-server
### Configure password into terminal ###

### Install Gem mysql2 ###
gem install mysql2

### cd proyecto ###
bundle install


### end ###
rails server

### goto web ###
localhost:3000
