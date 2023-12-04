# REQUERIMIENTOS TECNICOS
-Lenguajes: PHP, TPL
-Seguridad y encriptacion
-Ruteo, URLs semanticas
-Base de datos: SQL
-Utilizacion de motor de plantillas Smarty
-Patron MVC

# REQUERIMIENTOS FUNCIONALES
-Desarrollar un sitio web dinámico que permita visualizar un conjunto de ítems cargados y gestionados dinámicamente por un usuario administrador. Este sitio podrá ser accedido por cualquier persona, pero será el usuario administrador el único con los permisos necesarios para administrar completamente todos los items del sitio, es decir, darlos de alta, modificarlos o eliminarlos. 

-Estos ítems deben estar modelados en el sistema mediante una relación 1 a N. Por ejemplo, se puede pensar como ítems pertenecientes a categorías, ítems que tienen un conjunto de componentes o cualquier modelo de datos deseado que se adapte a esta relación.

##Acceso público:
  Deben existir diferentes secciones donde se muestre el contenido dinámicamente generado desde la base de datos. Estas secciones pueden ser accedidas de manera pública, no es necesario loguearse.
  Listado de ítems: Se debe poder visualizar todos los items cargados
  Detalle de ítem: Se debe poder navegar y visualizar cada ítem particularmente 
  Listado de categorías: Se debe poder visualizar un listado con todas las categorías cargadas
  Listado de ítems x categoría: Se debe poder visualizar los ítems perteneciente a una categoría seleccionada
  
##Acceso administrador de datos 
  Debe existir una sección para la administración de datos, la cual es accedida solo a usuarios administradores del sitio.*
  El usuario administrador debe loguearse con usuario y contraseña.
  El usuario debe poder desloguearse (logout)
  Solo los usuarios logueados pueden modificar las categorías y los ítems.
