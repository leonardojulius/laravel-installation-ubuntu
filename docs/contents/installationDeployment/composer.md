## Composer Installation

1. >sudo apt update

2. >sudo apt install php-cli unzip

3. >curl -sS https://getcomposer.org/installer -o /tmp/composer-setup.php 

4. >HASH=`curl -sS https://composer.github.io/installer.sig` 

5. >php -r "if (hash_file('SHA384', '/tmp/composer-setup.php') === '$HASH') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;" 

6. >sudo php /tmp/composer-setup.php --install-dir=/usr/local/bin --filename=composer

7. >composer