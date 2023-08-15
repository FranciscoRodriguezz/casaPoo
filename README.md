# casaPoo
Ejercicio de Composicion
Se desea modelar una relación de composición entre las clases "Casa" y
"Habitación" utilizando vectores en lugar de listas. Cada casa está compuesta por
varias habitaciones, y si la casa se destruye, las habitaciones también
desaparecen. Cada habitación tiene un número y un tamaño en metros
cuadrados.
Debes implementar un programa en Java utilizando programación orientada a
objetos que cumpla con los siguientes requisitos:
Define una clase llamada "Casa" que tenga los siguientes atributos:
o Un vector de habitaciones de tipo Habitación.
o Un contador de cantidad de habitaciones.
o Una constante llamada "CAPACIDAD_MAXIMA" con valor 100 para
indicar la capacidad máxima de habitaciones en una casa.
La clase "Casa" debe tener los siguientes métodos:
o Un constructor que inicialice el vector de habitaciones y el contador.
o Un método llamado "agregarHabitacion" que reciba un objeto de
tipo Habitación y lo agregue al vector de habitaciones si hay
capacidad disponible.
o Un método llamado "destruirCasa" que elimine todas las
habitaciones de la casa.
o Un método llamado "mostrarInformacionCasa" que muestre en la
consola la información de cada habitación en la casa.
Define una clase llamada "Habitación" que tenga los siguientes atributos:
o Un número de habitación de tipo int.
o Un tamaño de habitación en metros cuadrados de tipo double.
La clase "Habitación" debe tener los siguientes métodos:
o Un constructor que reciba el número y el tamaño de la habitación.
o Métodos getter para acceder al número y al tamaño de la habitación.
En el método principal (main) del programa, realiza lo siguiente:
o Crea una instancia de la clase "Casa" llamada "casa".
o Crea al menos dos instancias de la clase "Habitación" con datos
ficticios.
o Agrega las habitaciones creadas a la casa utilizando el método
"agregarHabitacion" de la clase "Casa".
o Llama al método "mostrarInformacionCasa" de la clase "Casa" para
mostrar la información de las habitaciones en la consola.
o Llama al método "destruirCasa" de la clase "Casa" para simular la
destrucción de la casa y vuelve a llamar al método
"mostrarInformacionCasa" para verificar que las habitaciones se han
eliminado.

https://drive.google.com/file/d/1TojwhG7io0A7ua7NFuqpke3OJvZ8dDib/view?usp=sharing
