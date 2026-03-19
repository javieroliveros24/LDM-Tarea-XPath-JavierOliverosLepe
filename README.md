#LDM-Tarea-XPath-JavierOliverosLepe
##En este poyecto he realizado 4 consultas a un archivo XML a traves de xpath, para filtrar datos.

###En la primera consulta teniamos que hacer lo siguiente:
Reto 1: Filtrado por contenido y estado. El departamento de desarrollo necesita actualizar su bibliografía sobre diseño. Obtén los títulos de todos los recursos cuya categoría sea 'CSS' y que, además, estén marcados como disponibles (true).
#### He ido por orden jerarquico hasta llegar a recurso, utilice el operador and para decirle las dos cosas que se deben cumplir para los datos que debe mostrarme y lo finalice con string para que solo me devuelva cadenas de texto.

Reto 2: Atributos y negaciones. No todos nuestros recursos son documentos estándar. Queremos identificar aquellos materiales que tienen un formato especial. Selecciona los ID (el atributo id) de todos los recursos cuyo formato no sea "PDF".
#### Fui hasta recurso y ahi le dije mediante el operador distinto que el formato debe ser distinto a PDF y tambien quiero el id y finalizo de nuevo con string.


Reto 3: Manejo de múltiples nodos (Autores). La colaboración es clave en la ciencia. Localiza y muestra únicamente el nombre del primer autor de aquellos recursos que han sido publicados después del año 2015.
### Fui de nuevo hasta recurso y le dije que me de los añosquer son mayores que 2015 y finalice de nuevo con string.

###Reto 4: Consultas de complejidad técnica (Nivel y Categoría). Buscamos material para un seminario avanzado de arquitectura de datos. Necesitamos los títulos de los recursos que pertenezcan a las categorías de "XPath" o "XSLT" y que tengan un nivel de dificultad de 5.
### La ultima consulta me ha dado fallo y aun no se porque, este es el error.
 XError:Required cardinality of value in 'function Q{com.functions.ext}createContextElement()' expression is exactly one; supplied value is empty; code:XTTE0780
 #Lo mirare detenidamente con mas tiempo y lo arreglare