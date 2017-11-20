Varios bugs
1_ No crea ejecutbles, pero no da información de errores
2_ El flag -g informa los warnings y el mejor flag de optimización es el -O0
3_ Da los warning en funciones donde no se declara el header o donde no se inicializan variables.

floting pont exception

En la primera parte agregamos include math.h en el código y además compilamos con gcc y linkeamos a la librera libm


Segemntation fualt

1_Primiero da error: "Violación de segmento (`core' generado)".
2_ al ejecutar ulimit -s unlimited vemos que cambia stack size asa de 8192 a sin límite.
3_ Error de optomización de recursos.
4_ La solución sería pasar a una arreglo dinámico usando la función malloc

   
