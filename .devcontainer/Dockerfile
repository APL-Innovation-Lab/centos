FROM centos:7

# Install utilities
RUN yum -y update && yum -y install epel-release yum-utils

# Install Remi Repository
RUN yum -y install https://rpms.remirepo.net/enterprise/remi-release-7.rpm

# Enable PHP 7.4
RUN yum-config-manager --enable remi-php74

# Install PHP 7.4 and specific extensions
RUN yum -y install php php-cli php-fpm php-json php-mbstring php-xml php-mysqlnd
