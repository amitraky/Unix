# Unix Basic Commanders

* i stands for ignore case (optional in your case).
* R stands for recursive.
* l stands for "show the file name, not the result itself".
* / stands for starting at the root of your machine.


# use of swiches
```
 -i -> ignore text case
 -R -> recursively search files in subdirectories.
 -l -> show file names instead of file contents portions.
 -w -> stands for match the whole word.
 -n -> stands for match the whole word.
 / stands for starting at the root of your machine
```

# other swiches
```
grep -r "some text here" search text in each file folder  
```
# file and folder permission
```
sudo chmod -R ugo+rw /DATA/SHARE
```


# install require application
```
sudo su
apt-get install php
apt-get install apache2
apt-get install mysql-server mysql-client
apt-get install phpmyadmin
apt-get install python
apt-get install python-mysqldb 

ln -s /etc/phpmyadmin/apache.conf
ln -s /etc/apache2/conf-available/phpmyadmin.conf

service apache2 restart 
``` 
- [install reference](https://askubuntu.com/questions/451708/php-script-not-executing-on-apache-server)
