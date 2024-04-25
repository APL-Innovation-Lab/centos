FROM centos:7

# Install utilities
RUN yum -y update && yum -y install epel-release yum-utils

# Install Remi Repository
RUN yum -y install https://rpms.remirepo.net/enterprise/remi-release-7.rpm

# Enable PHP 8.1
RUN yum-config-manager --enable remi-php81

# Install PHP
RUN yum -y install php php-cli php-fpm php-json
