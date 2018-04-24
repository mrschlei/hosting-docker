FROM drupal:7

# required if you want the sqlite db to persist
# can be used in conjunction with a runtime command like:
# docker run -it -p 80:80 -v /temp/drupal:/var/www/html/sites/default/files drupal-sample
VOLUME ["/var/www/html/sites/default/files/"]