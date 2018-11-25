# xhprof for PHP7

Please do not use this in an production env.


## Install

### Compile in Linux
```
$ /$PHP7/bin/phpize
$ ./configure --with-php-config=/$PHP7/bin/php-config
$ make && make install
```
edit php.ini, add a new line:
```
extension=xhprof.so
```
make sure it works:
```
php7 -m |grep xhprof
```
