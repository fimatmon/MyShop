# MyShop
MyShop is a desktop Java application without any database connection.

MyShopDB version uses fully the MariaDB database connection.

Username: Admin Password: Admin1234

MariaDB user creation example:

A new user:
CREATE USER 'valvoja'@localhost IDENTIFIED BY 'mariadb';

Grant rights to use the database by the user valvoja:
GRANT ALL PRIVILEGES ON *.* TO 'valvoja'@localhost IDENTIFIED BY 'mariadb';
