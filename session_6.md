Primer contacto con lenguajes de programación
==

Esta es la primera sesión de tres que nos ayudarán a entender unos conceptos necesarios para cuando ya toquemos código.

¿Qué puede hacer la computadora por mi?
--
En nuestra primera sesión platicamos de qué podiamos hacer con la computadora y comentamos que son muchas cosas las que se pueden hacer tantas que nos asustaba, tales como documentos, escuchar musica, ver peliculas, navegar en la red, etc. Sin embargo hay otras cosas que igual hace la computadora y no nos damos cuenta, como: operaciones aritméticas, comparaciones u lógicas. Todo esto lo hace por detras la computadora para poder darnos resultados como un editor de texto o un programa para escuchar música.

Por lo que es necesario que recordemos/aprendamos los conceptos de **jerarquía de operadores y las tablas de verdad.**

Tipos de lenguajes
--
Por otro lado, igual ya hemos platicado de los tipos de lenguajes: alto y bajo nivel. ¿Cómo los identificamos? Super simple, entre más entendible sea por un humano más de alto nivel es.

Ahora remontándonos un poco a la historia (prehistoria diría yo :P), para que entendamos mejor esto de los tipos de lenguajes. En los años 30's los lenguajes eran de muy bajo nivel y muy difícil de usarlos por lo que los mismos programadores de esa época crearon lenguajes menos complicados. Ya por ahí de los 60's empezaron a enfocarse para crear lenguajes human friendly.

Gracias a esta evoluciín en los lenguajes existen 4 generaciones. Por lo que los lenguajes actuales son lenguajes de cuarta generación.



   * 1ra generación (lenguaje máquina) (1930's - 1950's)

      * binario y ensamblador

   * 2da generación (1950's - 1960's)

      * primer grupo de lenguajes de programación que traían operaciones lógicas.
      * FORTRAN, LISP, COBAL

   * 3ra generación (human friendly) (1960's - 1980's)

      * Programas estructurados y programación orientada a objetos
      * Small talk, C, C++, BASIC, SQL

   * 4ta generación (frameworks) (1980's - Today)

      * Cross platform compatibility
      * Visual Basic, C#, Java, Ruby



Paradigmas de programación
--
**¿Qué es eso?** Es el estilo en el que está hecho un lenguaje de programación.

Existen muchos tipos, pero el que mas importante actualmente es el **Orientado a Objetos**.

Orientado a objetos como su mismo nombre lo dice. Todo lo convierte a objetos, de esta manera es más fácil abstraer las soluciones a código, ya que en nuestra vida diaria todo son objetos. **Hablaremos más sobre esto en otra sesión**

Tipos de ejecución
--
**Compilado**: El código fuente es convertido a lenguaje máquina por un compilador. Es decir que la computadora evalúa todo nuestro código y luego nos dice si lo entendió, mostrando un resumen de lo que no en caso de haber errores. Es fácil identificar este tipo de ejecución porque siempre, luego de compilar todo nuestro código, obtenemos un archivo "extra", un archivo ejecutable.

**Interpretado**: El código fuente es convertido a lenguaje máquina durante su ejecución por un programa externo llamado intérprete. Es decir, la computadora evalúa nuestro código línea por línea. De esta manera el código se va ejecutando hasta que esté bien, paso a pasito.

**Framework**: El código fuente es convertido a CRL ( Common Runtime Languaje), el cual contiene instrucciones estandarizadas para ser procesadas por la Máquina virtual o por el Framework. Como ayer comentábamos un Framework es como un contenedor en el que podemos incluir diversas librerías que nuestro programa puede utilizar.

**Emulado**: Por lo general, el código máquina que se ejecuta en una plataforma que no era nativa compilada, significa que este emulador simula el hardware para el que el programa fue desarrollado y así poder ser ejecutado.

Jerarquía de Operadores
--

Operadores aritméticos (su resultado es un número)
1. paréntesis ()
2. signo -,+
3. potencias y raices ^
4. multiplicaciones y divisiones (módulo tmb) *,/,%
5. Sumas y restas, +,-

Operadores relacionales (su resultado es un valor de verdad)
6. ==, <, >, <=, >=, <> ó !=

Operadores lógicos o booleanos (su resultado es un valor de verdad, 0 falso, 1 verdadero)
7. not, and, or (!, &&, ||)

Notas:
    * Si hay dos o más de la misma jerarquía u orden, resolver de izquierda a derecha.
    * Si se quiere alterar el orden normal de operaciones, entonces usar paréntesis.
    * Tampoco es bueno usar paréntesis de más en una operación, esto sólo indica que no se evalúo bien la formula, como en el siguiente ejemplo: area = (base * altura) / 2

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
  * SQL
  * TCL
  * Visual Basic
  * ------------------
  * Ajax
  * SOAP
  * UNIX shell
  * Python
  * COBAL

Ejercicios de Jerarquía de Operadores
--

