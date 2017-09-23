# Servidor y ClienteIRC
### Practicas de Redes de Comunicaciones 2


## Práctica 1: Servidor IRC

Para comprobar su funcionamiento usamos el corrector <b>R2D2</b> incluido en la libreria de la asignatura, por tanto, es posible que si se prueba pasado el curso 2016/2017 deje de funcionar correctamente o causara algún fallo, puesto que cada curso escolar la libreria sufre actualizaciones y modificaciones.

## Práctica 2: Cliente IRC

Por alguna razón aún desconocida, el cliente causaba un fallo solo en los laboratorios de la universidad, este era una violacion del core al rato de abrir una segunda instancia del cliente para probar el envio de ficheros. El fallo nunca se obtuvo probando en nuestros ordenadores personales (Mónica y Alfonso), según la profesora el fallo podia estar causado por la versión de la libreria de la asignatura instalada en los laboratorios o por la distribución de Linux.

En general el cliente funciona perfectamente, no tuvimos tiempo de realizar la implementacion del envio de audio. El cliente funciona con cualquier servidor IRC que siga los siguientes RFCs: <a href="https://tools.ietf.org/html/rfc1459"> RFC-1459</a>, <a href="https://tools.ietf.org/html/rfc2810">RFC-2810</a>, <a href="https://tools.ietf.org/html/rfc2811">RFC-2811</a>, <a href="https://tools.ietf.org/html/rfc2812">RFC-2812</a> y <a href="https://tools.ietf.org/html/rfc2813">RFC-2813</a>.

## Práctica 3: Seguridad SSL
Esta practica no llega a estar 100% acabada otra vez mas por falta de tiempo (muchas entregas al final del curso) Los certificados se realiza al compilar la práctica con <tt>make</tt>

El cliente y servidor echo con SSL funcionan perfectamente, y pasan el corrector <b>c3po</b> (una vez mas incluido en la libreria de la asignatura, por lo que es posible que en futuras versiones de la libreria deje de funcionar) En la correccion del laboratorio uno de los dos (cliente o servidor) no pasaba el test, pero en nuestros ordenadores si.

## Nota Final:
No nos hacemos responsables de posibles copias causadas por usar nuestro codigo, nosotros lo publicamos para ayudar, puesto que sabemos que al principio es complicado entender que es lo que hay que hacer. Recomendamos que el uso que se le den a nuestras practicas sean solo de consulta, y nunca como copia de codigo puesto que la universidad tiene un sistema anticopia y puede que no seas el unico que ha acabado en este repositorio.

El script que genera la documentacion simplemente esta para hacer mas rapida la generacion de esta, puesto que genera la documentacion con Doxygen en las 3 practicas, elemina todos los archivos innecesarios y organiza la documentacion en las carpetas que se nos indicaban en el formato de entrega. El script tambien tiene la posibilidad de eliminar toda la documentación, esto es util para ahorrar espacio, puesto que se puede volver a genrar posteriormente.

Generar documentación <tt>./doc.sh</tt> <br>
Limpiar documentación <tt>./doc.sh -c</tt>
<br>
<i>Se deben de ejecutar desde el directorio principal donde se encuentra el script</i>

### Calificaciones
Las practicas tuvieron buena nota en general, pero la mejor es con diferencia la primera (Servidor IRC) puesto que es para la que tuvimos mas tiempo.

## Autores
<ul>
<li> Alfonso Bonilla Trueba </li>
<li> Mónica de la Iglesia Martinez </li>
</ul>
