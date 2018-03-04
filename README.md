# How to install apache server on CentOS 7 (Red Hat Distribution)

## Install httpd package on CentOS 7 
[root@testvm ~]# yum install httpd -y

## Start httpd service on CentOS 7
[root@testvm ~]# systemctl start httpd

## Start httpd service on Boot
[root@testvm ~]# systemctl enable httpd

## Stop local firewall on CentOS 7
[root@testvm ~]# systemctl stop firewalld

## Check httpd service Status
[root@testvm ~]# systemctl status httpd

## Check firewalld service Status
[root@testvm ~]# systemctl status firewalld

## Go to document root of the web server
[root@testvm ~]# cd /var/www/html

## Edit document root of the web server with your index file
[root@testvm html]# vi index.html [Write plain text]

## Open Port 80 on Google Cloud Platform Firewall Rules under your VPC or Default VPC

## Now Browse Your Public IP 

## Have Funnnnnn...!!!


