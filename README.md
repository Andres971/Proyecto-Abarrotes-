# Proyecto-Abarrotes-

# Descripcion Del Problema y Solucion 
Actualmente la tienda de abarrotes es muy pequeña ya que es un proyecto nuevo y por esa razón no cuentan con un sistema de punto de venta para realizar las transacciones en las cuales se puedan marcar las ventas realizadas y además de esto el inventario que se tiene actualmente. 

Con un punto de venta Web la empresa se beneficiaría bastante ya que dejaría de usar el sistema “manual” que consiste en el cálculo por Excel en la cual por día se anotan los artículos vendidos y al mismo tiempo se va descontando del inventario. Con esto el usuario o el gerente de la tienda en este caso podría estar registrando las compras de una manera más rápida y calculando los precios de los productos de una manera mucho más eficaz, además de contar con una sección de inventario para ir agregando o restando directamente para tener un mejor control sobre los productos que se tienen en las bodegas.

# Requerimientos:
Servidores de aplicación: Tomcat 8
Bases de datos: Mysql
Paquetes adicionales: JDBC Mysql 5 Connector
Versión de Java: 1.8 

# Instalación
¿Cómo instalar el ambiente de desarrollo?
Se debe agregar el proyecto (WAR) en el App Manager de tomcat y desplegarlo y crear la base de datos con los archivos sql.

¿Cómo implementar la solución en producción en un ambiente local o en la nube como Heroku?

Con el cliente de Heroku  Puedes agregar el archivo WAR con el Siguiente comando: 
$ heroku war:deploy <path_to_war_file> --app <app_name>

Uso:

# Guía de contribución para usuarios.

Descargar el codigo:
git clone https://github.com/Andres971/Proyecto-Abarrotes-.git

Para realizar cambios:
Agregar cambios 
Entrar a la carpeta
Hacer commit con el commando git commit -m "Mensaje de commit"
Hacer deploy con comando git push

# Requerimientos que se implementarán en un futuro.
Implementacion de escaner para codigo de barras
Implementacion del modulo de inventario
