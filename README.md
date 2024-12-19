# EC2-RDS
### instalation in ec2 server
- ```sudo apt update -y```
- ```sudo apt install apache2 php php-mysql mysql-client -y```
- ```sudo systemctl start apache2```
- ```sudo systemctl enable apache2```
- ```mysql -h <RDS-Endpoint> -u <Master-Username> -p```
- ```cd /var/www/<taruh file>```
- ```sudo systemctl restart apache2```
