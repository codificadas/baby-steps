Primer contacto con lenguajes de programación
==

En nuestre sexta sesión de Baby Steps empezaremos con una serie de platicas sobre conceptos necesarios para programar.

¿Qué puede hacer la computadora por mi?
--

En nuestra primera sesión de Baby Steps platicamos de qué podiamos hacer con la computadora y comentamos que son muchas cosas las que se pueden hacer tantas que nos asustaba, algunos ejemplo mencionados fueron: escribir documentos, escuchar musica, ver peliculas, navegar en la red, etc. Sin embargo hay otras cosas que igual hace la computadora y no nos damos cuenta, como: operaciones aritméticas, comparaciones u lógicas. Todo esto lo hace por detras para poder darnos resultados como un editor de texto o un programa para escuchar música.

Por esta razon para que nosotras lleguemos a realizar programas tan poderosos es necesario que recordemos/aprendamos los conceptos de **jerarquía de operadores y las tablas de verdad.**

Tipos de lenguajes
--

Por otro lado, igual ya hemos platicado de los tipos de lenguajes: alto y bajo nivel. ¿Cómo los identificamos? Super simple, entre más entendible sea por un humano más de alto nivel es.

Ahora remontándonos un poco a la historia (prehistoria diría yo :P), para que entendamos mejor esto de los tipos de lenguajes. 

En los años 30's los lenguajes eran de muy bajo nivel y muy difícil de usarlos por lo que los mismos programadores de esa época crearon lenguajes menos complicados. Ya por ahí de los 60's empezaron a enfocarse para crear lenguajes human friendly.

Gracias a esta evolución en los lenguajes existen 4 generaciones y los lenguajes de nuestra epoca caen en la 4 generación.

Veamos como han ido evolucionando: 

   * 1ra generación (lenguaje máquina) (1930's - 1950's)

      * binario y ensamblador

   * 2da generación (1950's - 1960's)

      * primer grupo de lenguajes de programación que traían operaciones lógicas.
      * FORTRAN, LISP, COBOL

   * 3ra generación (human friendly) (1960's - 1980's)

      * Programas estructurados y programación orientada a objetos
      * Small talk, C, C++, BASIC, SQL

   * 4ta generación (frameworks) (1980's - Today)

      * Cross platform compatibility
      * Visual Basic, C#, Java, Ruby



Paradigmas de programación
--
**¿Qué es eso?** Es el estilo en el que está hecho un lenguaje de programación. Así como hay diferentes estilo de danza, igual hay diferentes estilos lenguajes.Existen muchos tipos, pero el que mas importante actualmente es el **Orientado a Objetos**.

Orientado a objetos como su mismo nombre lo dice. Todo lo convierte a objetos, de esta manera es más fácil abstraer las soluciones a código, ya que en nuestra vida diaria todo son objetos. **Hablaremos más sobre esto en otra sesión**

Tipos de ejecución
--
Un tipo de ejecución es como la computadora traduce los codigos a su lenguaje.

**Compilado**: El código fuente es convertido a lenguaje máquina por un compilador. Es decir que la computadora evalúa todo nuestro código y luego nos dice si lo entendió, mostrando un resumen de lo que no en caso de haber errores. Es fácil identificar este tipo de ejecución porque siempre, luego de compilar todo nuestro código, obtenemos un archivo "extra", un archivo ejecutable.

**Interpretado**: El código fuente es convertido a lenguaje máquina durante su ejecución por un programa externo llamado intérprete. Es decir, la computadora evalúa nuestro código línea por línea. De esta manera el código se va ejecutando hasta que esté bien, paso a pasito.

**Framework**: El código fuente es convertido a CRL ( Common Runtime Languaje), el cual contiene instrucciones estandarizadas para ser procesadas por la Máquina virtual o por el Framework. Como ayer comentábamos un Framework es como un contenedor en el que podemos incluir diversas librerías que nuestro programa puede utilizar.

**Emulado**: Por lo general, el código máquina que se ejecuta en una plataforma que no era nativa compilada, significa que este emulador simula el hardware para el que el programa fue desarrollado y así poder ser ejecutado.

Jerarquía de Operadores
--

**Operadores aritméticos (su resultado es un número)**

1.- paréntesis ()

2.- signo -,+

3.- potencias y raices ^

4.- multiplicaciones y divisiones (módulo tmb) *,/,%

5.- Sumas y restas, +,-

**Operadores relacionales (su resultado es un valor de verdad, 0 falso, 1 verdadero)**

6.- ==, <, >, <=, >=, <> ó !=

**Operadores lógicos o booleanos (su resultado es un valor de verdad, 0 falso, 1 verdadero)**

7.- not, and, or (!, &&, ||)

**NOTAS:**
- Si hay dos o más de la misma jerarquía u orden, resolver de izquierda a derecha.
- Si se quiere alterar el orden normal de operaciones, entonces usar paréntesis.
- Tampoco es bueno usar paréntesis de más en una operación, esto sólo indica que no se evalúo bien la formula, como en el siguiente ejemplo: area = (base * altura) / 2

Lenguajes más comunes (Investiguen de cada uno ;))
--

  * C
  * C++
  * C#
  * Perl
  * HTML
  * JavaScript
  * PHP
  * Objective-C
  * Java
  * Ruby
  * TCL
  * Visual Basic
  * ------------------
  * Ajax
  * SOAP
  * UNIX shell
  * Python
  * COBAL
  * -----------------
  * SQL
  * MySQL
  * PostgreSQL
  * Oracle
  * MongoDB

Ejercicios de Jerarquía de Operadores
--

**Básicos :P**

  1. ( 5 ( 7 ( 5 - 3 ) + 12 ) - 2 )
  2. ( 5 - 6 ( 7 / 2 ( - 6 - 3 ) + 12 * 24 ) - 2 )
  3. 5 * 3 + 12 - 14 / 2
  4. 2 * 5 * 5 + 3 * 5 + 7
  5. 10 * 20 > 40 * 10 + 2,
  6. 8 * 10 <> ( 10 - 30 ) * 16
  7. 5 > 2 AND 10 >= 9
  8. 3 > 5 AND 3 < 10
  9. 5 > 2 OR 10 >= 9
  10. 3 > 5 OR 3 < 10
  11. NOT( 99 > =50 || 10 >= 75 )
  12. ( 5 > 2 || NOT( 10 >= 9 ))

**Nota para los primeros 2 ejercicios** si tenemos por ejemplo **5(5-3)** el primer 5 junto al paréntesis indica multiplicación, es decir evaluamos primero: (5-3) = 2, y tenemos 5(2) = 10, 10 es el resultado aquí

**Complicadísimos :3**

  1. NOT( NOT( ( 10 - 3 ) < ( 8*16 )) AND ( ( 5 - 8 * 16 ) == 12))
  2. ((( 2 + 3 / 4 ) < ( 7 * 60 / 10 ) ) OR ( ( 5 - 8 ) == 12 ) )  OR  ( NOT(( 20 - 2 * 3 ) < ( 8 * 16 )) AND ( 5 - 8 * 16 ) == 12)

Slides:
--
Sesión 6: [Primer contacto con los lenguajes de programación](https://www.haikudeck.com/baby-steps-education-presentation-TgOxMAprjV)
