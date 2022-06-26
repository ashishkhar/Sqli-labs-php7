SQLI-LABS link : (https://github.com/Audi-1/sqli-labs.git).

Steps to follow

1. Download the repository from here
	[https://github.com/skyblueee/sqli-labs-php7/archive/refs/heads/master.zip](https://github.com/ashishkhar/Sqli-labs-php7.git)

2. Move the folder to var/www/html
	$mv sqli-labs-php7-master /var/www/html
3. $service mysql start
4. $mysql -u root -p (default pass 'toor')
5. $GRANT ALL PRIVILEGES ON *.* TO 'user'@'localhost' IDENTIFIED BY '123';
6. $service mysql restart
7. $cd /var/www/html/sqli-labs-php7/sql-connections
8. $nano db-creds.inc #(change credentials as in step 7)
9. $service mysql restart
10. $service apache2 start

For refernece : https://www.youtube.com/watch?v=NJ9AA1_t1Ic&list=PLkiAz1NPnw8qEgzS7cgVMKavvOAdogsro&index=24
