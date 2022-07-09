
# Glosario de términos de Drupal

[A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) [J](#j) [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) [X](#x) [Y](#y) [Z](#z)


# A
___

### acción - action
En el módulo Views

### Acquia
Es una compañia de servicios de software fundada por el creador de Drupal, Dries Buytaert. Se dedica a dar soporte a nivel empresarial a Drupal y a certificar los conocimientos de los profesionales que trabajan con este CMS.

### Acquia Dev Desktop
Entorno de desarrollo para Mac y para Windows que permite realizar una instalación sencilla de WAMP para desarrollar en Drupal. (es como un XAMPP orientado a Drupal)

### administrador - admin

### admin_toolbar
Es uno de los primeros módulos que se instalan tradicionalmente en Drupal. Permite ver los menus de adminsistración como desplegables.

# B
___
### bloque - block
En Drupal TODO son bloques. Son contenidos principalmente dinámicos que se pueden habilitar en distintas zonas (denominadas regiones) del tema del sitio. Por ejemplo, un bloque puede mostrar los últimos usuarios registrados, los últimos comentarios publicados en el sitio o un calendario de eventos.


# C
___
### cache - cache

### campos - fields

### consola de drupal - drupal console

### composer
Es un sistema de gestión de paquetes para programar en PHP el cual provee los formatos estándar necesarios para manejar dependencias y librerías de PHP. LA forma recomendada de instalar Drupal es con composer:
```bash
composer create-project drupal/recommended-project my_site_name_dir

composer create-project drupal-composer/drupal-project:8.9.x-dev my_site_name_dir

composer create-project drupal-composer/drupal-project:7.x-dev -n my_site_name_dir
```


# D
____
### drush - drush
Drush es una aplicación basada en shell de software que se utiliza para controlar, manipular y administrar los sitios web de Drupal. Fie pensado originalmente para instalar y actualizar módulos pero tiene un rango de usos mucho más amplio.



# E
___
### entidad - entity
Las entidades son elementos a los que se les puede añadir campos de información de diferentes tipos (texto, imagen, archivo, número, fecha, etc.). Su finalidad es homogeneizar la gestión y presentación de campos adicionales. Algunas entidades en Drupal son los usuarios, los nodos, los términos de taxonomía y los comentarios. 

### estatus - status (de un usuario)
Son estatus válidos de un usuario: Bloqueado (Blocked); Activo (Actived).

### extender - extend
(Interfaz de Drupal) En la pestaña extend se encuentran todos los módulos que extienden la funcionalidad básica de Drupal.

# F
___

# G
___
### gancho - hook

### gulp
Gulp es una herramienta que forma parte del desarrollo de softwares, y está especialmente relacionada con el front-end. Su principal objetivo es automatizar los flujos de trabajo lentos y repetitivos, facilitando y acelerando el rendimiento diario del programador.

# H
___

### HAL
Hypertext Application Language (HAL) is an Internet Draft (a "work in progress") standard convention for defining hypermedia such as links to external resources within JSON or XML code (however, the latest version of HAL Internet-Draft expired on November 12, 2016.). The standard was initially proposed in June 2012 specifically for use with JSON and has since become available in two variations, JSON and XML. The two associated MIME types are media type: application/hal+xml and media type: application/hal+json.

# I
____


# J
____


# K
____


# L
____

# M
___
### Menús
Los menús facilitan la organización de los nodos publicados. Drupal integra un potente gestor de menús que permite disponer de múltiples y variados menús en un mismo sitio web. Los menús se pueden colocar en distintas áreas o regiones de un tema y se adaptan al diseño gráfico del sitio, establecido a través del tema seleccionado. es decir, los menús representan estructuras de enlaces de acceso a los contenidos del sitio web. Los Menús tambien son bloques y pueden ser manejados como tales. En Structure son ejemplos de Menu: Administration, Footer, Main navigation, Tools, User account menu (menus añadidos por los usuarios).

### menú de administración - administration (menu)
Toda la administración del sitio se lleva a cabo a través del menú de Administración (Management), este menú se divide en grupos de tareas, teniendo inicialmente las siguientes opciones principales: Panel de control, Contenido, Estructura, Apariencia, Personas, Módulos, Configuración, Informes, Ayuda.

### módulo - module
Pieza de software que aporta funcionalidades adicionales al nucleo de drupal. Existen dos tipos de módulos contrib y custom. Los modulos se buscan en drupal.org en la dirección:
```URL
https://drupal.org/project/modules
```

### módulo contribuido - contrib module
módulos creados por la comunidad drupal.

### módulo personalizado - custom module
módulos creados por nosotros.

# N
___

### nombre de máquina - machine name

### nodo - node
Conjunto de datos que puede ser presentado en el sitio web, usualmente asociado a un tipo de cotenido.

### núcleo - core
El núcleo aporta a drupal la base necesaria para su funcionamiento y para la incorporación del resto de componentes de la arquitectura.


# O
___


# P
____

### phar
Un archivo con extensión PHAR es un formato de paquete que permite la distribución de aplicaciones y bibliotecas al agrupar muchos archivos de código PHP y otros recursos en un solo archivo comprimido.

### permisos -permission
Conjunto de acciones permitidas para los usuarios del sitio web. De esta forma se controla si el usuario puede o no realizar una determinada acción.
Los permisos están separados por categorías para una mejor administración. Los permisos en la categoria Bloques (Block) es Administrar Bloques (Administer blocks). Los permisos en la categoria Comentarios (Comment) son: Administer comment types and settings; Edit own Comments; Post comments; Skip comment aprovals. Los permisos en la categoría Contacto (Contact) son: .... 


# Q
___

# R
___
### región - region
Las regiones son áreas visuales que permiten la introducción de bloques de contenido. Son ejemplos de regiones: Header, Primary menu, Secondary menu, Highligted, Featured Top, Breadcrumb, Content, Sidebar first, Sidebar Second, Featured bottom first, Featured bottom second, Featured bottom third, Footer first, Footer second, Footer third, Footer fourth, footer fifth.

### requerimientos (casos de uso)
Es una especificación en un documento de lo que cada tipo de uaurio puede hacer en una página web y cómo esta se comporta.

### REST
REST es una interfaz para conectar varios sistemas basados en el protocolo HTTP (uno de los protocolos más antiguos) y nos sirve para obtener y generar datos y operaciones, devolviendo esos datos en formatos muy específicos, como XML y JSON.

### rol - rol
Un rol es un conjunto de permisos, y cada usuario puede tener asignados diferentes roles. Una vez creado un nuevo rol hay que añadir los permisos oportunos en la pestaña correspondiente. Son ejemplos de roles: Usuario Autenticado (Authenticated user); Administrador (Administrator); los que el administrador añada.

### ruta - path
Ruta a un contenido del sitio web, normalmente una URL.


# S
___
# T
___
### taxonomia - taxonomy
La taxonomía permite la clasificación de los contenidos del sitio. El módulo Taxonomy de Drupal está constituido por dos elementos fundamentales: los vocabularios (o categorías) y los términos (o etiquetas). Cada vocabulario puede agrupar a uno o más términos. Drupal nos permite a través de los vocabularios categorizar los nodos y por medio de los términos describir aspectos particulares de éstos.

### tema - theme
Define un diseño específico para el sitio web. Existe un repositorio oficial de temas libres de Drupal, que pueden ser descargados y modificados para adaptarlos al diseño de nuestro sitio.
Mediante el uso de temas, Drupal separa los contenidos del diseño, de forma que es posible cambiar el aspecto del sitio cambiando o modificando el tema. La forma más fácil de personalizar los temas es modificando las hojas de estilo CSS que contienen.
Los temas se dividen en regiones, que son áreas diferenciadas en las que se puede colocar contenido. Por ejemplo, una región puede ser la cabecera, y otra podría ser la columna lateral izquierda.

### tipo de contenido - content type
Normalmente relacionado con un Nodo, dicese de los diferentes conjuntos de datos presentables gestionados en el sitio web. los tipos de contenido iniciales en drupal 7 y 8 son : Article(contenido que permite introsucir informaciones variables en el sitio web ) y Page (contenido estatico del sitio web). Son ejemplos de content type: Article, Basic Page.

### twig
Twig es un motor de plantillas desarrollado para el lenguaje de programación PHP y que nace con el objetivo de facilitar a los desarrolladores de aplicaciones web que utilizan la arquitectura MVC el trabajo con la parte de las vistas.

# U
___

### usuarios - people
Un usuario es cualquier persona que interactua de alguna forma con nuestri Drupal. Son ejemplos de usuarios: Anonymous user, Authenticated user, Administrator.

# V
___

### vistas - views
Comenzó siendo el módulo más contribuido para Drupal 7, su éxito fue tal que se incorporó al core de las versiones posteriores. En Drupal 8 aparece como Views y Views UI. 
En la Interfaz de administración de Drupal está en Estructura (Structure), Vistas (Views). 


### vocabulario - vocabularies

# W
___

# X
___

# Y


___
# Z
___

### zurb foundation
Foundation es un marco frontend responsivo que cuenta con una gran variedad de componentes HTML y CSS para el diseño de interfaces de usuario, diferentes fragmentos de código y plantillas, así como extensiones opcionales de JavaScript. Este framework web modular se distribuye bajo la licencia libre MIT y se puede descargar tanto en su página web oficial,  como también en GitHub.
[zurb-foundation-compacto-framework-ui/](https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/zurb-foundation-compacto-framework-ui/)


[A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) [J](#j) [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) [X](#x) [Y](#y) [Z](#z)


