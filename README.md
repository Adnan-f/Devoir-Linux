# Devoir-Linux-
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
cd nom_du_rép
mkdir bldMySQL
cd bldMySQL
cmake ..
#make
#make install
echo export  PATH=$PATH:/usr/local/mysql/bin >> ~/.bashrc


