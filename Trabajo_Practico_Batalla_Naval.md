# Batalla Naval

## Trabajo Práctico Python: Listas de listas

A resolver en grupos de 2 a 3 personas.

## Consigna

Con lo visto en clase sobre listas de listas, armar un programa que simule un juego de "Batalla Naval".

Dado un tablero de `N * N`, es decir una lista de `N` listas de `N` elementos cada una, donde cada elemento puede contener o no un barco, el programa debe permitir ingresar las coordenadas de disparo, y mostrar si se acertó o no en un barco. Para este ejemplo `N=10` pero deberia poder cambiar el tamaño del tablero en función de `N`.

Para esta primera consigna, los barcos se asignan por código. Opcionalmente se pueden ubicar en posiciones al azar. Los barcos ocupan una sola casilla

El usuario tiene una cantidad predefinida de disparos, esto es, una cantidad de intentos para acertar en los barcos.

Al finalizar el juego, mostrar la cantidad de disparos acertados y fallados, y como finaliza el tablero (los barcos que quedaron en pie).

Recomendaciones:

- Implementar el tablero como una `List[List[Bool]]`, de esta forma las coordenadas del tablero serán `tablero[fila][columna]`.
- Utilizar constantes para definir la cantidad de disparos y la cantidad de barcos.

## ⚡️ Bonus

- Dada una variable que determine la cantidad de barcos, modificar el programa para permitirle a otro usuario ingresar previamente las posiciones de los `N` barcos.

- Permitir jugar de a 2 jugadores, y que, por turnos cada uno pueda disparar contra el tablero del otro.

- Permitir barcos de hasta 3 casillas.

## Formato de entrega

Entregar un archivo `naval-Apellido1-Apellido2-Apellido3.py` que contenga el código del programa en el siguiente formulario de [Google Forms](https://forms.gle/WkaGStsaor52564y6).

El código debe estar comentado y contar con Type Hints. Cualquier referencia por fuera de lo visto en clase debe ser incluida en los comentarios (links a StackOverflow, docs, conversaciones de ChatGPT, etc).

## 📅 Fecha de entrega: Viernes 26 de Abril
