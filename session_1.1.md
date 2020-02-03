# Diagramas de flujo

En esta sesión vamos a entender cómo funciona a nivel lógico el hecho de recargar nuestra tarjeta del metrobús/metro y pasar por el torniquete con ayuda de los diagrama de flujo.


**Temas:**
- ¿Qué es un diagrama de flujo y para qué me sirve?
- Manos a la obra.


**Actividades:**
- Actividad 3 - Resuelve el "misterio" del metrobús.
- Actividad 4 - Diagramas extras.

**Material**
- Tarjetas para participantes con conceptos impresos.
---

#### ¿Qué es un diagrama de flujo y para qué me sirve?
Es la representación gráfica de un algoritmo. Nos puede ayudar al empezar a resolver un problema.

#### Manos a la obra.
> Actividad 3 - Resuelve el "misterio" del metrobús.

## Actividades.
#### Actividad 3 - Resuelve el "misterio" del metrobús.
Este problema se propone ya que es un aspecto común que casi todas las personas han usado en la ciudad de México o al menos tienen una idea de su funcionamiento. El profesor deberá hacer el ejercicio con los alumnos e ir explicando cada componente y concepto.

> Diseccionar cómo es que funciona la interacción que tenemos con el metrobús o el metro y el uso de la tarjeta.

Deberán realizarse dos diagramas de flujo que describan:
- ¿Qué implica el hecho de hacer una recarga?
- ¿Qué implica el hecho de pasar mi tarjeta por el lector para poder entrar al servicio de transporte?

Para esto tendremos las siguientes condiciones.
 - La recarga máxima es de $120.00 pesos.
 - Solo se puede recargar en pesos mexicanos.*
 - Recientemente se dio un cambio en las tarjetas válidas para el sistema de transporte.*


*Entendimiento del Problema*
> Análisis de recarga.

- El lector de tarjetas dentro de la máquina de recargas siempre está en espera de que se introduzca una tarjeta.
- Cuando se introduce, la máquina lee el saldo disponible y lo muestra en pantalla.
- La máquina cambiará de mensaje en la pantalla y esperará un tiempo determinado a que el usuario ingrese el monto que desee recargar.
- Cuando el usuario ingrese dinero ala máquina, esta actualizará en su pantalla el monto ingresado, validando que no exceda el límite.
- Si el usuario presiona cancelar, la máquina deberá regresar el dinero y reiniciar el valor de monto ingresado.
- Una vez que el usuario presione el botón de recarga, escribirá en el chip de la tarjeta el nuevo saldo. (Haciendo una sumatoria del saldo ingresado y el saldo inicial).
- Terminado el proceso anterior, la máquina indicará al usuario que puede retirar su tarjeta y hacer uso de ella.
- La máquina regresa al estado inicial.


> Análisis de uso de tarjeta.  

- El lector en el torniquete está en espera de que se presente una tarjeta.
- Cuando se presente una tarjeta, deberá valida si es una tarjeta usable.
- En caso de que no sea así, notificar al usuario y eventualmente regresar al estado inicial.
- Si es válida, deberá hacer el descuento de un pasaje ($6.00 pesos) y liberar el torniquete.
- La máquina regresa al estado inicial.

---


#### Actividad 4 - Diagramas extras.
1. Hacer un diagrama de flujo para saber el área de un triángulo, requerimos que el usuario nos proporcione la base y la altura! Mostrar el resultado al usuario.

2. Hacer un diagrama de flujo para calcular la edad de una persona, necesitamos que el usuario nos proporcione su fecha de nacimiento! Mostrar la edad del usuario.

3. Hacer un diagrama de flujo para calcular el promedio final de un alumno, pedir al usuario las calificaciones de 5 materias! Mostrar el promedio final del alumno y también decir si el alumno aprobó o reprobó. Si el promedio <= 5 (reprobado), Si el promedio es >5 (aprobado!)


## Material

> Ver la posibilidad de hacer tarjetas o cheatsheets con el siguiente contenido.

#### Componentes de un diagrama de flujo

**Óvalo** - Inicio y fin del diagrama de flujo

**Flechas** - Indican la dirección del flujo

**Rombo** - Decisiones o condiciones, tu algoritmo tomará varios rumbos? Úsalo!

**Rectángulo** - Procesos, aquí se representan los procesos que nos dan un resultado que podemos usar más adelante.

**Romboide** - Entrada y salida de datos

**Rectángulo embarazado :)** - Nos sirve para imprimir en pantalla.

**NOTA**: es importante recordarles que existe más simbología, pero estos son los más comunes.


#### Conceptos adicionales

**Variables:** una variable es el nombre que le damos a los datos que utilizamos en nuestros diagramas, estos nos permiten variar los datos que ellas guardan. Por ejemplo num=5, pero también puede ser num=45.

**Constantes:** es un concepto parecido a las variables, la diferencia es que para éstas el valor que guardan no cambia, es por eso que podemos dejar un dato como el 2 que discutíamos tal cual. En caso de ser necesario lo guardamos en una variable pero su valor es constante como el ejemplo del IVA.

**Operadores aritméticos:** nos permiten hacer cualquier operación aritmética que necesitemos.
- Suma (+)
- Resta (-)
- Multiplicación (*)
- División (/)
- Módulo/Residuo (%)
- Potencia (^)

**Operadores lógicos o relacionales:** nos permiten hacer comparaciones entre dos valores. Si el resultado de la comparación es correcto la expresión considerada es verdadera de lo contrario es falsa.
- Igual a (=)
- Distinto a (<>)
- Mayor que (>)
- Menor que (<)
- Mayor o igual que (>=)
- Menor o igual que (<=)
- And (&)
- Or (|)


## TODO
- Slides
