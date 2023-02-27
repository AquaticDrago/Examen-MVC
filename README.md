# Examen-MVC

## Funcion
El siguiente proyecto tiene como funcion el realizar el registro en una base de datos los datos en este caso de diferentes categorias que podria tener un punto de venta y ademas de su fecha de creacion

El proyecto esta dividido en diferentes carpetas con el fin de controlar e identificar mas facilmente las funciones de cada nota de codigo, divididos claramente por la vista, controlador y modelo, esto al momento de querer agregar alguna funcion nos facilitara la organizacion de la misma para su mantenimientos

## ¿Como se usa?
Su uso es tan simple como rellenar los campos que se indican y acto seguido pulsar el boton de insertar para que este sea añadido a los registros de la BD, pero ademas de eso este proyecto tiene las funciones de un CRUD, por lo cual en la tabla que contiene mostrara los datos previamente registrados desde donde podras actualizar pulsando el boton claramente identificado para cambiar los datos del registro en los campos que se llenaran con los datos que tenian el registro seleccionado para ser modificado, una vez corregido se debera pulsar el boton de insertar para que estos sean actualizados en la BD.

A su vez cuenta con el boton de eliminar el cual dara de baja de la BD el registro seleccionado.

No olvidar la barra de busqueda el cual facilitara el datos a buscar entre todos los registros disponibles, este buscara por el nombre de la categoria

## Ejecucion
Para el correcto funcionamiento del proyecto es necesaria la creacion de una BD que contenga los campos para el Nombre y Fecha de la categoria, ademas de su identificador, una vez creada es necesario la modificacion del archivo de conexion a la bd que se encuentra en la carpeta "BD" , en este archivo se debera modificar los datos a los de su BD con el fin de lograr una correcta insercion de datos, a su vez deberan modificarse algunas lineas del archivo del modelo ya que estan se comunican con la BD, por lo cual debera cambiarse dependiendo el nombre y datos de su BD creada

Finalmente para los archivos de la pagina basta con moverlos a su carpeta htdocs de su servidor local que este utilizando y acceder a ellos mediante la URL de localhost
