ARG HTTPD_VERSION
ARG HTTPD_OS_VERSION
FROM httpd:${HTTPD_VERSION}-${HTTPD_OS_VERSION}

COPY httpd.conf /usr/local/apache2/conf/httpd.conf
COPY httpd-vhosts.conf /usr/local/apache2/conf/extra/httpd-vhosts.conf
