# larabel-sandbox
A repo for trying out larabel PHP framework

# Initial Setup

https://laravel.com/docs/10.x

# Installing PHP and composer

[brew install php](https://formulae.brew.sh/formula/php)
[brew install composer](https://formulae.brew.sh/formula/composer)

## Output from installing PHP
```
To enable PHP in Apache add the following to httpd.conf and restart Apache:
    LoadModule php_module /opt/homebrew/opt/php/lib/httpd/modules/libphp.so

    <FilesMatch \.php$>
        SetHandler application/x-httpd-php
    </FilesMatch>

Finally, check DirectoryIndex includes index.php
    DirectoryIndex index.php index.html

The php.ini and php-fpm.ini file can be found in:
    /opt/homebrew/etc/php/8.2/

To start php now and restart at login:
  brew services start php
Or, if you don't want/need a background service you can just run:
  /opt/homebrew/opt/php/sbin/php-fpm --nodaemonize
```