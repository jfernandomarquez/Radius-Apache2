# Autenticación en Apache2 con Radius

Solicitar contraseña para ingresar a una página web

## Topología

[![config](https://github.com/jfernandomarquez/Radius-Apache2/blob/master/topologia.radius.PNG)](https://jfernandomarquez.blogspot.com/) 

[![config](https://github.com/jfernandomarquez/Radius-Apache2/blob/master/topologia2-%20apache.PNG)](https://jfernandomarquez.blogspot.com/)

## Configuración de freeradius

el cliente es el servidor que tiene apache y por la tanto la ip es la correspendiente a dicho servidor

[![config](https://github.com/jfernandomarquez/Radius-Apache2/blob/master/clients-conf.PNG)](https://jfernandomarquez.blogspot.com/) 

[![config](https://github.com/jfernandomarquez/Radius-Apache2/blob/master/users.PNG)](https://jfernandomarquez.blogspot.com/) 

## Configuración de Apache2

Se configura el archivo apache2.conf

[![config](https://github.com/jfernandomarquez/Radius-Apache2/blob/master/apache2-conf.PNG)](https://jfernandomarquez.blogspot.com/) 

la ip debe ser la ip del servidor radius, testing123 es el parametro *secret* configurado en el archivo clientes.conf del servidor radius

[![config](https://github.com/jfernandomarquez/Radius-Apache2/blob/master/00-default-conf.PNG)](https://jfernandomarquez.blogspot.com/) 

en el archivo *users* se especifica las credenciales para acceder a la página web. 



