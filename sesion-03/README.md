# Algoritmos en PSeInt

Estos programas se hicieron usando la lógica básica de programación.

## ¿Cómo se hicieron?

- Primero se definían las variables que necesitaban guardar información.
- Luego se usaban estructuras como `Si`, `Mientras`, `Para` y `Repetir` para resolver el problema.
- En algunos casos se usaron `SubProceso` para organizar el código y hacerlo más fácil de entender.
- Finalmente, se pedían datos con `Leer` y se mostraban resultados con `Escribir`.

## Descripción de cada algoritmo

### CajeroParqueadero.psc
Este algoritmo suma el dinero cobrado por cada carro.

- El usuario escribe el valor cobrado.
- El programa lo acumula en una variable llamada `total`.
- También cuenta cuántos carros fueron atendidos.
- Cuando se escribe `0`, el ciclo termina.
- Al final muestra el total recaudado y la cantidad de carros.

### Calificaciones.psc
Este programa calcula el promedio de 5 notas.

- Suma todas las notas.
- Cuenta cuántas están aprobadas (`>= 3`).
- Busca la nota mayor y menor.
- Si hay alguna nota reprobada, lo muestra.

### FacturaRestaurante.psc
Este algoritmo crea una factura de restaurante.

- Pide los precios de los platos hasta ingresar `0`.
- Suma todos esos precios para obtener el subtotal.
- Calcula el impuesto del 8% y la propina del 10%.
- Muestra el total a pagar.

Se hizo con subprocesos para ordenar mejor el código.

### Piramide.psc
Este programa dibuja una pirámide con `*`.

- Usa un ciclo para la altura.
- Otro ciclo imprime espacios a la izquierda.
- Y otro imprime los asteriscos de cada fila.

### ValidarPin.psc
Este algoritmo valida un PIN.

- El usuario ingresa un número.
- Si es igual a `2580`, le da acceso.
- Si no, aumenta el número de intentos.
- Si falla 3 veces, muestra que la tarjeta está bloqueada.

## En resumen

Los algoritmos se hicieron con lógica paso a paso, usando variables, condiciones y ciclos para resolver cada problema de forma simple y clara.
