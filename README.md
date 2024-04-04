#Implementación de Pila y Cola Java
(En Gid)
<h1>IMPLEMENTACION DE PILA</h1>
<h2>Descripción del codigo</h2>

<p>Este código Java implementa un programa simple para simular el lavado de platos utilizando una pila (stack).</p>
<h2>Explicación detallada del código:</h2>

<p><em><string>Paquete y clases importadas: </string></em>El código está en un paquete llamado "pila".
Se importan las clases Scanner y Stack del paquete java.util.</p>

<p><em><string>Clase Pila_PlatoSucios:</string></em>
Esta es la clase principal que contiene el método main donde comienza la ejecución del programa.</p>

<p><em><string>Método main:</string></em>
Se crea una pila llamada pilaPlatos para almacenar los platos sucios.
Se crea un objeto Scanner para leer la entrada del usuario desde la consola.
Se inicializa la variable salir como false para controlar la salida del bucle while.</p>

El bucle se ejecuta mientras salir sea false.
Se muestran las opciones de menú para que el usuario elija.
Se lee la opción ingresada por el usuario utilizando el objeto Scanner.
Dependiendo de la opción elegida por el usuario, se ejecuta un bloque de código específico dentro del switch.</p>

<p><em><string>Bloque switch:</string></em> Cada caso dentro del switch representa una opción de menú.
Para cada caso, se realiza una operación específica como agregar un plato sucio a la pila, lavar el plato superior de la pila, ver el plato superior, verificar si la pila está vacía o buscar un plato en la pila.
Si se selecciona la opción 6, la variable salir se establece como true para salir del bucle while.</p>

<p><em><string>Operaciones en la pila:</string></em> Se utilizan métodos de la clase Stack para realizar operaciones en la pila, como push para agregar un plato sucio, pop para lavar el plato superior, isEmpty para verificar si la pila está vacía y search para buscar un plato en la pila. </p>

<p><em><string>Mensajes al usuario:</string></em> Se muestran mensajes informativos al usuario en función de las operaciones realizadas.</p>

<p><em><string>Salida del bucle while:</string></em> Cuando la variable salir se establece como true, se imprime "¡Hasta Luego!" y el programa termina.
<p>Este programa simula el proceso de lavado de platos utilizando una pila para almacenar los platos sucios y realizar las operaciones correspondientes según la opción seleccionada por el usuario.</p>
[![Captura-de-pantalla-2024-04-03-223021.png](https://i.postimg.cc/hG2qPvXB/Captura-de-pantalla-2024-04-03-223021.png)](https://postimg.cc/674PM9Vj) 


<h1>IMPLEMENTACION DE LA COLA</h1>
<p></p><h2>Descripción del codigo:</h2>Este código Java implementa un programa simple para simular una cola de atención en un banco utilizando una cola (queue).</p>
<h2>Explicación detallada del código:</h2>

<p><em><string>Paquete y clases importadas: </string></em>El código está en un paquete llamado "pila".
Se importan las clases LinkedList y Queue del paquete java.util.</p>

<p><em><string>Clase ColaBanco: </string></em>Esta es la clase principal que contiene el método main donde comienza la ejecución del programa.</p>

<p><em><string>Método main: </string></em>Se crea una cola llamada colaAtencion utilizando la clase LinkedList.
Se crea un objeto Scanner para leer la entrada del usuario desde la consola.
Se inicializa la variable salir como false para controlar la salida del bucle while.</p>

<p><em><string>Bucle while: </string></em>El bucle se ejecuta mientras salir sea false.
Se muestran las opciones de menú para que el usuario elija.
Se lee la opción ingresada por el usuario utilizando el objeto Scanner.
Dependiendo de la opción elegida por el usuario, se ejecuta un bloque de código específico dentro del switch.</p>

<p><em><string>Bloque switch: </string></em>Cada caso dentro del switch representa una opción de menú.
Para cada caso, se realiza una operación específica como agregar un cliente a la cola de atención, atender al próximo cliente, ver al próximo cliente en la cola, verificar si la cola de atención está vacía o salir del programa.
Si se selecciona la opción 5, la variable salir se establece como true para salir del bucle while.</p>

<p><em><string>Operaciones en la cola: </string></em>Se utilizan métodos de la clase Queue para realizar operaciones en la cola, como add para agregar un cliente, poll para atender al próximo cliente, peek para ver al próximo cliente en la cola y isEmpty para verificar si la cola está vacía.</p>

<p><em><string>Mensajes al usuario: </string></em>Se muestran mensajes informativos al usuario en función de las operaciones realizadas.</p>

<p><em><string>Salida del bucle while: </string></em>Cuando la variable salir se establece como true, se imprime "¡Hasta Luego!" y el programa termina.</p>

<p>Este programa simula el proceso de atención de clientes en un banco utilizando una cola para mantener el orden de llegada de los clientes y realizar las operaciones correspondientes según la opción seleccionada por el usuario.</p>




