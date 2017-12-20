Proyecto Laravel

El siguiente proyecto sera realizado utilizando Lavavel 5.5 y PHP 7.1
Consistira en la creacion de una pagina web para una institucion bancaria, denominada MOMOBANK
La aplicacion hara uso de dos bases de datos, una para la aplicacion y otra para el banco
Asi mismo se hara uso de dos usuarios por cada base de datos, un admin y un user.
La configuracion de bases de datos seria la siguiente:

DB: momobank
USER: momobankadm
PASS: mRMq8cAFvKdmEyP4
USER: momobankusr
PASS: 6PJVtJFAPPwxLY1j

DB: momoapp
USER: momoappadm
PASS: RSxJcW83tUmzI60V
USER: momoappusr
PASS: 2N1yy7vy80OjxR9s

A fin de unificar la configuracion de la aplicacion se creara un link simbolico para el virtual host
```
ln -s momoweb.conf /etc/apache2/sites-available/momoweb.conf
```

Creation Apache Virtual Host
http://laravel-recipes.com/recipes/25/creating-an-apache-virtualhost

Fix Permission on MariaDB 10.1 for user phpmyadmin
https://askubuntu.com/questions/763336/cannot-enter-phpmyadmin-as-root-mysql-5-7
