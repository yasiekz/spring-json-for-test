# spring-json-for-test

Some basic jsons what we need to spring workshop at 30.11.2016r i duck team.

## Use this as a apache v 2.4 vhost

``
<VirtualHost *:80>
        ServerName json-spring

        ServerAdmin yasiekz@gmail.com
        DocumentRoot /home/jzieba/www/java/spring-json-for-test

        <Directory "/home/jzieba/www/java/spring-json-for-test">
                AllowOverride All
                Require all granted
        </Directory>

        ErrorLog ${APACHE_LOG_DIR}/json-spring.log
        CustomLog ${APACHE_LOG_DIR}/json-spring-access.log combined
</VirtualHost>
``
