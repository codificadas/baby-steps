Primer contacto con lenguajes de programación
==

En nuestre sexta sesión de Baby Steps empezaremos con una serie de platicas sobre conceptos necesarios para programar.

Variables
--

Son usadas para guardar un valor en memoria que puede ser usado en el programa.

- **Alcance de las variables (locales y globales)**: Una variable sólo está disponible para una sección de un programa basado en:
  - Dónde se declaró
  - El tipo de variable

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

IDE's
--

El programa para hacer programas :P

Un IDE nos da todas la hermamientas para que podamos escribir tranquilamente nuestro código. Estos ya compilan y corren el programa por ti.

Hay de muchos sabores y colores, cada quien usa el que más le gusta. Igual depende del lenguaje de programación que utilices

Aquí unos IDE's:
*RubyMine
*NetBeans
*Aptana

Por otro lado sino queremos usar programas tan sofisticados (complicados aveces) podemos usar simples editores de texto, hasta en notepad puedes usar para programar, claro que estos no tienen tantas herramientas pero sirven para el mismo fin.

Algunos de estos son:

- Sublime Text
- VIM

Ejercicios de Jerarquía de Operadores
--

**Básicos :P**

  1. ( 5 ( 7 ( 5 - 3 ) + 12 ) - 2 )
  2. ( 5 - 6 ( 7 / 2 ( - 6 - 3 ) + 12 * 24 ) - 2 )
  3. 5 * 3 + 12 - 14 / 2
  4. 2 *5* 5 + 3 * 5 + 7
  5. 10 *20 > 40* 10 + 2,
  6. 8 *10 <> ( 10 - 30 )* 16
  7. 5 > 2 AND 10 >= 9
  8. 3 > 5 AND 3 < 10
  9. 5 > 2 OR 10 >= 9
  10. 3 > 5 OR 3 < 10
  11. NOT( 99 > =50 || 10 >= 75 )
  12. ( 5 > 2 || NOT( 10 >= 9 ))

**Nota para los primeros 2 ejercicios** si tenemos por ejemplo **5(5-3)** el primer 5 junto al paréntesis indica multiplicación, es decir evaluamos primero: (5-3) = 2, y tenemos 5(2) = 10, 10 es el resultado aquí

**Complicadísimos :3**

  1. NOT( NOT( ( 10 - 3 ) < ( 8*16 )) AND ( ( 5 - 8* 16 ) == 12))
  2. ((( 2 + 3 / 4 ) < ( 7 *60 / 10 ) ) OR ( ( 5 - 8 ) == 12 ) )  OR  ( NOT(( 20 - 2* 3 ) < ( 8 *16 )) AND ( 5 - 8* 16 ) == 12)

Slides
--

Sesión 6: [Primer contacto con los lenguajes de programación](https://www.haikudeck.com/baby-steps-education-presentation-TgOxMAprjV)
