# Cheatsheet de Drush


```
$ drush version 
```
--> te dice la versión de drush instalada.

```
$ drush list
```
--> lista los comandos que tenemos disponibles de drush

```
$ drush help [command]
```
--> te da ayuda sobre lo que hace un comando de drush que le indiquemos

```
$ drush status 
```
--> saca un reporte sobre la instalación de drupal sobre la que se ejecuta

```
$ drush pm-list
```
--> lista los mádulos que podemos instalar en drupal

```
$ drush cache-clear
```
--> limpia la cache, te debe mostrar de que existe cache y cual eliminar.

```
$ drush cr
```
--> reconstruye las cache, rebuild. IMPORTANTE, si queremos ver el efecto de cualquiera de los otrso comandos en la BBDD a través del interfaz web siempre tendremos que ejecutar este comando previamente.

```
$ drush watchdog-list
```
--> muestra los logs del sistema que se guardan en las tablas watchdog

```
$ drush config-get
```
--> muestra el valor de una variable de configuración o de un objeto completo

```
$ drush config-get [variable]
```
--> muestra el valor o el objeto por el que le estamos preguntando

```
$ drush config-get [variable] [campo]
```
--> muestra el subvalor campo del objeto variable. 

```
$ drush config-export
```
--> exporta toda la configuración del sistema por si despues necesitamos importarla

```
$ drush user-create
```
--> crea un usuario

```
$ drush user-information [usuario]
```
--> enseña la información de un usuario determinado

```
$ drush user-block [usuario]
```
--> bloquea a un usuario determinado, status=0

```
$ drush user-unblock [usuario]
```
--> desbloquea a un usuario determinado, status=1

```
$ drush user-add-role [rol] [usuario]
```
--> aplica un rol a un usuario determinado

```
$ drush user-remove-role [rol] [usuario]
```
--> quita un rol a un usuario determinado