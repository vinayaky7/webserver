# How to install apache server on CentOS 7 (Red Hat Distribution)

## Install httpd package on CentOS 7 or CentOS 6
[root@testvm ~]# yum install httpd -y

## Start httpd service on CentOS 7
[root@testvm ~]# systemctl start httpd

## Start httpd service on CentOS 6
[root@testvm ~]# service httpd start

## Start httpd service on Boot on CentOS 7
[root@testvm ~]# systemctl enable httpd

## Start httpd service on Boot on CentOS 6
[root@testvm ~]# chkconfig httpd on

## Stop local firewall on CentOS 7
[root@testvm ~]# systemctl stop firewalld

## Stop local firewall on CentOS 6
[root@testvm ~]# /etc/init.d/iptables stop

## Check httpd service Status on CentOS 7
[root@testvm ~]# systemctl status httpd

## Check httpd service Status on CentOS 6
[root@testvm ~]# service httpd status

## Check firewalld service Status on CentOS 7
[root@testvm ~]# systemctl status firewalld

## Go to document root of the web server
[root@testvm ~]# cd /var/www/html

## Edit document root of the web server with your index file
[root@testvm html]# vi index.html

## Open Port 80 on Google Cloud Platform Firewall Rules under your VPC or Default VPC

## Now Browse Your Public IP 

## Have Funnnnnn...!!!


