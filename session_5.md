Sigamos practicando pseudocódigo
===
En esta sesión aprenderemos pseudocódigo, una manera más cercana de programar en lenguaje natural, así representaremos nuestros algoritmos y los dejaremos listos para luego ir a nuestra computadora y traducirlos al lenguaje de programación de nuestra elección.


¿Qué es un ciclo?
--
Un bucle o ciclo, en programación, es una sentencia que se realiza repetidas veces a un trozo aislado de código, hasta que la condición asignada a dicho ciclo deje de cumplirse. Generalmente,un ciclo es utilizado para hacer una acción repetida sin tener que escribir varias veces el mismo código, lo que ahorra tiempo, deja el código más claro y facilita su modificación en el futuro. El ciclo y los condicionales representan la base de la programación estructurada.

**NOTA**: Es importante mencionar que para que nuestro ciclo funcione perfectamente necesitamos una variable que lo controle, el proceso que queremos repetir varias veces y la condición que hará que el ciclo se rompa.


¿Para qué me sirve?
--
Sirver para reducir código en caso de hacer una instrucción repetitiva.

Clasificación 
--
**Ciclo automático** - Son aquellos en que el número de iteraciones se conoce antes de ejecutarse el ciclo.

Para(For):Dado un valor inicial exp1 asignado a la variable esta se irá aumentando o disminuyendo de acuerdo a la exp3 hasta llegar a la exp2; si se omite el paso, significa que la variable aumentará de uno en uno.

**Ciclos indeterminados** - Son aquellos en que el numero de iteraciones no se conoce con exactitud.

Mientras Que(Do While): Esta es una estructura que repetirá un proceso durante “N” veces, donde “N” puede ser fijo o variable. Para esto, la instrucción se vale de una condición que es la que debe cumplirse para que se siga ejecutando. Cuando la condición ya no se cumple, entonces ya no se ejecuta el proceso. 

Repita-Hasta(Do Until): Esta es una estructura repite un proceso una cantidad de veces, pero a diferencia del Do While, el Do Until lo hace hasta que la condición se cumple y no mientras, como en el Do While. Por otra parte, esta estructura permite realizar el proceso cuando menos una vez, ya que la condición se evalúa al final del proceso, mientras que en el Do While puede ser que nunca llegue a entrar si la condición no se cumple desde un principio. 

Ejemplos de ciclos en la vida real
--
El ciclo del agua, los años, actualizaciones de software, etc.

¿Qué es un método?
--
- Conjunto de instrucciones a las que se les asocia un nombre de modo que si se desea ejecutarlas sólo basta con referenciarlas a través de dicho nombre en vez de tener que escribirlas.

- Todo método devuelve algo (un objeto) como resultado.

- Parámetros: opcionalmente puede llevar parámetros

- Ejemplo: la salsa que se hace aparte para una receta :P


Tipos de datos
--

Primitivos
- int = enteros
- float = decimales
- double = decimales
- char = caracteres
- boolean = 0/1, true/false

Compuestos

- String
- Array

Ejemplos
--

Realizar el pseudocódigo de un programa que permita calcular el área de un rectángulo. Se debe introducir la base y la altura para poder realizar el cálculo.

```bash
Programa; área
Entorno: BASE, ALTURA, AREA son número enteros
Algoritmo:
    escribir “Introduzca la base y la altura”
    leer BASE, ALTURA
    calcular AREA = BASE * ALTURA
    escribir “El área del rectángulo es “ AREA
Finprograma
```

Ejercicios
--

1. Realizar el pseudocódigo que permita al usuario introducir por teclado dos notas, calculando la suma y el producto de las notas.

2. Realizar el pseudocódigo de un programa que permita saber si un número es mayor, menor o igual a cero.

3. (Ejercicio previo) Hacer un diagrama de flujo para saber el área de un triángulo, requerimos que el usuario nos proporcione la base y la altura! Mostrar el resultado al usuario.

4. Calcular el factorial de un número proporcionado por el usuario utilizando !.

5. Imprimir los números pares que existan desde el número 1 hasta el número que nos proporcione el usuario.

6. Realizar un algoritmo que muestre los números de uno en uno hasta diez usando una estructura Para(For)

7. Usando una estructura Mientras(Do While), realizar un algoritmo que escriba los números de uno en uno hasta 20.

8. Realizar un algoritmo que pregunte al usuario un número comprendido en el rango de 1 a 5. El algoritmo deberá validar el número, de manera que no continúe la ejecución del programa mientras no se escriba un número correcto(Do Until).


Slides:
--
Sesión 5: [Sigamos practicando pseudocódigo](https://www.haikudeck.com/baby-steps-education-presentation-eUqycWloNl)

