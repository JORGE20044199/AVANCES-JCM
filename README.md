Proyecto Juego del ahorcado
16/12/2024
Jorge Carrillo M.

Objetivo del Programa 

El objetivo principal del programa es simular el juego clásico del ahorcado en una interfaz de línea de comandos usando lenguaje Python.
El programa selecciona aleatoriamente una palabra de un conjunto predefinido y el jugador debe adivinarla letra por letra. Si el jugador introduce una
letra incorrecta, se dibuja una parte del ahorcado. El juego termina cuando el jugador adivina todas las letras de la palabra o cuando se agotan los intentos. 


Funcionalidades del codigo:


Variables: ​​

palabra_secreta: Almacena la palabra que el jugador debe adivinar.​​

intentos: Contabiliza las oportunidades que tiene el jugador.​​

letras_adivinadas: Guarda las letras que el jugador ya ha ingresado.​​

palabra_seleccionada: Representa la palabra a adivinar con guiones bajos inicialmente y se va completando con las letras correctas.​​

Tipos de datos: ​​

Cadenas: Se utilizan para las palabras, las letras y los mensajes que se muestran al usuario.​​

Enteros: Para contar los intentos y los índices en las listas.​

Estructuras de control: ​​

Condicionales (if, else): ​ Se usan para verificar si la letra ingresada está en la palabra secreta, para determinar si el jugador ha ganado o perdido.​

Bucles (while): ​​

El bucle while principal se ejecuta mientras queden intentos y la palabra no esté completamente adivinada.​​

For: Se utiliza para iterar sobre los caracteres de la palabra secreta y actualizar la palabra_seleccionada cuando se encuentra una letra correcta.​​

Funciones: ​​

dibujar_ahorcado(): Muestra el estado actual del ahorcado según los intentos restantes.​​

obtener_palabra_azar(): Selecciona una palabra aleatoria de una lista.​​

jugar_juego(): Contiene la lógica principal del juego.​​

Entrada y salida: ​​

input(): Permite al usuario ingresar una letra.​​

print(): Muestra mensajes en la consola, como el estado del juego, las instrucciones.
