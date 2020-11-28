# AUS - Taller de programacion III

## Autor: Tudino Federico

### Memoria descriptiva

El objetivo de la aplicacion es visualizar en tiempo real una alarma vecinal.
Cada casa posee un dispositivo (token) con el cual puede activar o desactivar su alarma.
La disposicion de las casas esta determinada por una matriz de X filas e Y columnas, asignando
a cada casa una posicion (X, Y)

El sistema posee un servidor que maneja los pedidos de activacion y desactivacion, y almacena la matriz. Los clientes
son usuarios del sistema.

Una alarma activada se representa con un 1 , mientras que una desactivada se representa con un 0.
Cada usuario está asociado a una casa y puede visualizar el estado de la matriz en tiempo real 
asi como tambien activar o desactivar su token.

Cuando hay un cambio en la matriz el servidor envia a todos los clientes la nueva matriz.

```
0 0 0 0 0   0 0 0 0 0
0  0    0   0       0
0  0    0   0   0   0
0       0   0  0    0
0 0 0 0 0   0 0 0 0 0

0 0 0 0 0   0 0 0 0 0
0  0    0   0    0  0
0 0     0   0  0    0
0     0 0   0       0
0 0 0 0 0   0 0 0 0 0
```