# Ejercicios 2 (Funciones)



1. Escriba una función que acepte dos números como parámetros y devuelva en consola la suma.

<br>
<hr>
<br>

2. Crea una función llamada `numeroMayor()` que toma dos números como entrada y retorna el numero mayor de ellos, si son iguales devolver un String “son iguales”.

<br>
<hr>
<br>

3. Escriba una función con el nombre de `esVocal()` que tome un carácter, devuelva true si es vocal(no importa si es mayúscula o minúscula), y devuelva false en caso contrario.


*Ayuda*
```JavaScript
const opcion = prompt("Seleccione una opción: E, A, C o S").toLowerCase();
```

<br>
<hr>
<br>

4. Crea una función llamada `generar_caracteres()` que tome como parámetro un número entero (n) y un carácter, retornar el carácter multiplicado por n, Por ejemplo, `generar_caracteres(5, x)`, deberá retornar “xxxxx”.

<br>
<hr>
<br>


5. Realice el código de una calculadora básica en JavaScript aplicando funciones arrow. El programa debe mostrar un menú al usuario mediante `prompt`, permitiendo seleccionar una operación de manera numerica 

`1_suma`<br>
`2_resta`<br>
`3_multiplicación`<br>
`4_división`

La visualización del menú debe implementarse en una *función arrow*. Luego de seleccionar la operación, el programa debe solicitar dos números mediante `prompt`. El cálculo de las operaciones debe realizarse en una única función arrow, que reciba como parámetros la operación seleccionada y los dos números ingresados. Muestra el resultado con `consola`.

Asegúrese de manejar posibles errores, como la división por cero o la introducción de valores no numéricos.

## Video ilustrativo.

<video src="Videos/video1.mp4" controls=""></video>

<br>
<hr>
<br>

6. Realice el código de un programa en JavaScript que simule el control de un motor industrial básico. El programa debe mostrar un menú mediante `prompt`, permitiendo al usuario seleccionar una de las siguientes opciones:

**E_Encender motor**: Enciende el motor si aún no está encendido. Si ya está en funcionamiento, muestra un `alert` indicando su estado.

**A_Apagar motor**: Apaga el motor y muestra un `alert` indicando que ha sido apagado.

**C_Consultar estado del motor**: Muestra con un `alert` si el motor está encendido o apagado.

**S_Salir del programa**: Finaliza la ejecución del programa y muestra un mensaje con `alert` que diga "Gracias por usar mi programa".

El programa debe ejecutarse en un bucle hasta que el usuario ingrese **S**. Si elige **S**, el programa debe agradecer al usuario y dejar de ejecutarse. Cada operación debe implementarse en una función arrow separada. El programa debe ser capaz de aceptar tanto mayúsculas como minúsculas en las opciones.

*Ayuda*

```JavaScript
const opcion = prompt("Seleccione una opción: E, A, C o S").toLowerCase();
```

## video ilustrativo.

<video src="Videos/video2.mp4" controls=""></video>

<br>
<hr>
<br>

7. Desarrolla un programa en JavaScript que simule el funcionamiento de un cajero automático básico. El programa debe solicitar al usuario ingresar un número de tarjeta de 9 dígitos y un PIN de 4 dígitos *(Esto debe ser realizado con funcion Arrow)* antes de ofrecer las siguientes opciones de operación:

A. Consultar saldo: Permite al usuario ver el saldo actual disponible en su cuenta bancaria, use `alert`.

B. Volver a realizar otra operación: Permite al usuario volver a ejecutar el programa desde el principio *(Esta opcion de puede ingresar en cualquier momento y nos debe llevar al menu principal)*.

C. Depositar dinero: Permite al usuario ingresar una cantidad de dinero para depositar en su cuenta, use `prompt`.

D. Retirar dinero: Permite al usuario retirar una cantidad específica de dinero de su cuenta, siempre y cuando tenga fondos suficientes disponibles, sino debe mostrar un `alert` con el mensaje *Saldo insuficiente*.

E. Salir del sistema: Termina la ejecución del programa.

El programa debe verificar que el número de tarjeta ingresado tenga exactamente 9 dígitos y que el PIN tenga 4 dígitos. Si el usuario ingresa el número de tarjeta o el PIN incorrectos, el sistema debe permitir hasta tres intentos para ingresar los datos correctamente. Después de tres intentos fallidos, el programa debe finalizar y mostrar un mensaje de error.

Si los datos ingresados son correctos dentro de los tres intentos, el usuario podrá acceder al menú de operaciones. El sistema debe seguir ejecutándose en un bucle hasta que el usuario seleccione la opción "E" para salir. El programa debe ser capaz de aceptar tanto mayúsculas como minúsculas en las opciones.

<br>
<hr>
<br>