

## MySQL-Server

1. >sudo apt update && sudo apt upgrade -y

2. >sudo apt install mysql-server

?>press Y then Hit Enter

3. >sudo mysql
  

4. >alter user 'root'@'localhost' identified with mysql_native_password by 'password';
  
5. >mysql -u root -p

6. >exit

## MYSQL SECURE INSTALLATION
7. >mysql_secure_installation

8. >Press y

9. >Press 0

10. >Press N

11. >Choose Y for Yes Until the last.

## Login To MySQL 
12. >login using mysql –u root –p

13. >show schemas;

14. >create user 'newuser'@'localhost' identified with mysql_native_password by 'password';



