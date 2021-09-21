# Ejercicio_MontyHall
El problema de Monty Hall es un problema bastante popular que se basa en el principio de una paradoja. En México se puede comparar a la catafixia de Chabelo. Para este problema imagina que tienes que un presentador te da a escoger una puerta de 3 disponibles donde sabemos que una de ellas tiene un premio y dos no. El presentador sabe qué puerta tiene el premio, por lo que una vez escogida la puerta él muestra una puerta donde no hay premio y te da a escoger si quieres cambiar de puerta o cambiarte. La pregunta acá es ¿Qué te conviene? Pues usando probabilidad se puede demostrar que te conviene cambiar de puerta, tú lo demostrarás a través de una simulación. Acá te explico cómo.

## Simulación
Para este ejercicio tendrás que simular este problema ¿Cómo haces esto? pues muy sencillo, imaginate que tienes que decirle a tú código paso a paso qué hacer para simular esta situación. así que te explicaré los pasos:

- Empieza un contador en 0
- Empieza asignando el premio a una lista de 3 elementos, los elementos pueden ser los que sean.
- Al Azar escoge un valor entre 1 y 3 que sirva como la puerta escogida por el usuario.
- Elimina una puerta que no sea ni la puerta escogida por el usuario ni la puerta ganadora.
- para cuestiones del cálculo NO CAMBIES la puerta escogida.
- Si la puerta escogida es la puerta asignada añade uno al contador
- Repite esto 10,000 veces.
- Divide el contador entre las 10,000

¿Cuál fue el resultado de esta división?

## Bonus
Ahora hazlo con una lista de x elementos, ten en cuenta que en este caso vas a eliminar x-2 elementos y estos no deben de ser la puerta escogida ni la puerta con el premio. ¿Ahora cuál es la probabilidad de que la puerta inicial sea la correcta?
