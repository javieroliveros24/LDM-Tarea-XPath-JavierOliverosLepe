README AEE.: Reto de Refactorización
--------------------------------------
Javier Oliveros Lepe
--------------------------------------
--------------------------------------
--------------------------------------
PARA COMPLETAR LA MISION 1
__________________________
He sacado los atributos id, rack y estado del elemento servidor y los he metido en un group que se llama AtributoServidor asi ase puede reutilizar los campos en otras partes del documento sin repetir el código.
______________________________________________________________________________________________________________________________________________________________________________________________________________________________

PARA COMPLETAR LA MISION 2
__________________________
He creado un xs group que se llama Componentes Hardware y he metido los elementos cpu, ram, gpu y discos y he aplicado una sequence ahora obliga  a quelos componentes aparezcan en ese orden y mejora la estructura.
______________________________________________________________________________________________________________________________________________________________________________________________________________________________
PARA COMPLETAR LA MISION 3
__________________________
He puesto que gpu tenga minOccurs=0 para que pueda ser opcional y he ajustado el lemento disco con el maxOccurs=8 para limita el numero de und que puede tener ubn servidor
__________________________________________________________________________
__________________________________________________________________________
__________________________________________________________________________
PARA COMPLETAR LA MISION 4
__________________________
He puesto un elemento nuevo que se llama red y que utiliza el choice para que cada servidor teng o una ip fija o un valor de dhcp y nunca pueda tener las dos cosas .
__________________________________________________________________________
__________________________________________________________________________
__________________________________________________________________________
PARA COMPLETAR LA MISION 5
__________________________
He añadido una etiqueta auditoria al final de cada servidor para meter la fecha el tecnico y las notas y he usado xs:all para que se pueda nrellenar esos datos en cualquier orden,
__________________________________________________________________________
__________________________________________________________________________
__________________________________________________________________________
PARA COMPLETAR LA MISION 6
__________________________
He usado el unique para el atributo id para que los identificadores no se puedan duplicar.

--Creo que he ahorrado entre 10 y 20 lineas de código.
--Si itentara poner 2 servidores con el mismo id habria imcumplido una restriccion de integridad que puse en el XSD