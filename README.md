# Package php-pecl-xdebug for Software Collections

This repository contains sources for RPMs that are used
to build Software Collections for CentOS by SCLo SIG.

This branch is for php54 and php55 SCL
Find other branches for rh-php56 specific sources.


PHP 5.4 / EL 6

    build -bs *spec --define "scl php54" --define "dist .el6"
    cbs add-pkg sclo6-sclo-php54-sclo-candidate --owner=sclo  sclo-php54-php-pecl-xdebug
    cbs build   sclo6-sclo-php54-sclo-el6       <above>.src.rpm

PHP 5.5 / EL 6

    build -bs *spec --define "scl php55" --define "dist .el6"
    cbs add-pkg sclo6-sclo-php55-sclo-candidate --owner=sclo  sclo-php55-php-pecl-xdebug
    cbs build   sclo6-sclo-php55-sclo-el6       <above>.src.rpm

PHP 5.4 / EL 7

    build -bs *spec --define "scl php54" --define "dist .el7"
    cbs add-pkg sclo7-sclo-php54-sclo-candidate --owner=sclo  sclo-php54-php-pecl-xdebug
    cbs build   sclo7-sclo-php54-sclo-el7       <above>.src.rpm

PHP 5.5 / EL 7

    build -bs *spec --define "scl php55" --define "dist .el7"
    cbs add-pkg sclo7-sclo-php55-sclo-candidate --owner=sclo  sclo-php55-php-pecl-xdebug
    cbs build   sclo7-sclo-php55-sclo-el7       <above>.src.rpm
