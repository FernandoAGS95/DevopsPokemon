# Uso de Github Actions y Pipelines

Tenemos un proyecto python en el cual se montara un servidor python en aws, en el cual al generar el pipeline, si todo es correcto.
Tendremos un servidor que provee una pagina, que permite subir y guardar informacion de pokemones

Lo vital en este proyecto seria

> Setear las variables de entorno o secrets en github 
> Preparar el ambiente en aws para montar el servidor
> Setear las ACL para los puertos que se estaran disponiendo

*Para obtener los comandos que debemos utilizar en nuestros pipes, ya sea el usop de algun comando de python o 
por ejemplo en este caso el uso de ssh para hacer un comando remoto, es necesario entrar a Github marketplace y buscar
en este mercado, los comandos para realizar la tarea que debemos hacer
* En el caso de ssh_actions, debemos utilizar variables de entorno que en este casos
se llaman secrets.EL_nombre_de_la_variable pára poder hacer uso de estas
*

*Dentro de un pipe, el name se utiliza para 
Especificar la tarea, para poder visualizar en github en caso de que esta tenga una falla