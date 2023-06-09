![Tutorial condicional ternario JavaScript](https://raw.githubusercontent.com/sergiecode/ternario-javascript-tutorial/master/ternario.jpg)

# Condicionales ternarios en JavaScript

Este README tiene como objetivo proporcionar una explicación sobre el uso de condicionales ternarios en JavaScript. Los condicionales ternarios son una forma concisa de escribir una estructura de control que permite evaluar una condición y asignar valores diferentes en función de si la condición es verdadera o falsa.

## Ejemplo de código

A continuación, se presenta un ejemplo de código que ilustra el uso de condicionales ternarios en JavaScript:

javascriptCopy code

`const variable = condicion ? valorSiCondTrue : valorSiCondFalse;` 

En este caso, `condicion` es la expresión que se evalúa como verdadera o falsa. Si `condicion` es verdadera, se asigna el valor `valorSiCondTrue` a `variable`; de lo contrario, se asigna el valor `valorSiCondFalse`.

## Ejemplo de uso

Supongamos que queremos asignar un texto a la variable `texto` en función de si `isMember` es verdadero o falso. Podemos utilizar un condicional ternario de la siguiente manera:

javascriptCopy code

`const texto = "La Cuota es de: " + (isMember ? "$25.00" : "$100.00");` 

En este ejemplo, si `isMember` es verdadero, se concatena el texto "$25.00" a la cadena "La Cuota es de: "; de lo contrario, se concatena "$100.00".

Los condicionales ternarios pueden ser útiles para simplificar el código y hacerlo más legible en situaciones donde se necesita tomar decisiones basadas en una condición.
