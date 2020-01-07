# Instalacion
Teniendo el siguente esquema de red, instala el servidor dns en webmin

imagen gns3


Para hacer este ejercicio utilizaremos el sistema operativo de Ubuntu Server:


Para acceder a webmin abrimos un navegador y buscamos la direccion https://localhost:10000

1-Primero buscaremos dns en el buscador y lo instalaremos 



2-Despues vamos a crear una zona de busqueda directa.

Imagen con los pasos para crear la zona

3-Ahora reiniciamos el servidor

imagen de como reiniciar

4-Comprobamos con el comando "nslookup(nombre del servidor)" que resuelva consultas.

imagen del uso del comando

5-Luego con el comando "sudo gedit(ruta del archivo)" comprobamos el archivo log(/var/log) y el contenido del archivo named.conf.local.

imagen del uso 

[Volver a la pagina pricipal](README.md)
