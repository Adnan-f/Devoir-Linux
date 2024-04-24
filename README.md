# Devoir-Linux
# MySQL
## Téléchargement de la source
https://dev.mysql.org 
## décompression et désarchivage
source: mysql*.tar.gz
```bash
tar -zxvf mysql*.tar.gz
```
## installation des dépendances
-> OpenSSL library 
```bash
#apt-get install libssl-dev openssl
```
-> ncurse library
```bash
#apt-get install libncurses5-dev
```
->libxml2 library
```bash
#apt-get install libxml2-dev
```
-> zlib library
```bash
#apt-get install zlib1g-dev
```
## étape d'installation
```bash
sudo apt-get install build-essential
cd nom_du_rép_désarchivé
mkdir bldMySQL
cd bldMySQL
cmake ..
#make
#make install
echo export  PATH=$PATH:/usr/local/mysql/bin >> ~/.bashrc
```
# Apache
## Téléchargement de la source
https://httpd.apache.org
## décompression et désarchivage
source: httpd*.tar.gz
```bash
tar -zxvf httpd*.tar.gz
```
## installation des dépendances
-> APR library
```bash
#apt-get install libapr1-dev libaprutil1-dev
```
-> PCRE
```bash
#apt-get install libpcre3-dev
```
## étape d'installation
```bash
cd nom_du_rép_désarchivé
./configure
#make
#make install
echo export  PATH=$PATH:/usr/local/apache2/bin >> ~/.bashrc
service start apache2
```
# PHP
## Téléchargement de la source
https://php.net
## décompression et désarchivage
source: php*.tar.gz
```bash
tar -zxvf php*.tar.gz
```
## installation des dépendances
-> sqlite3 database
```bash
#apt-get install libsqlite3-dev
```
## étape d'installation
```bash
cd nom_du_rép_désarchivé
./configure
#make
#make install
