+ Para que quiero el oraculo para comparar los test y comprender si el test paso o no paso
+ white box
  * conoce el codigo
+ black box
  - tiene entradas y salidas
  - ...
# testing de caja negra
+ Exiten test que abarcan a otros test => idealmente buscamos la ejecucion de la minimo cantidad de test
+ las clases de equivalencia y los test no solo de la entrada sino tambien de la salida
+ el valor limite de las clases de equivalencia (**si o si van al parcial**)
+ grafo causa-efecto
  - buscamos que los efecto sea true para las distintas causas
+ testing de a pares
  - dependa de 3 causas, o algo asi
+ cobertura de transiciones
  - como maximo la cantidad de flechas pero podria ser menos
+ cobertura de par de transiciones
  - testeamos los pares de entradas y salidas
  - puede que se cubra mas de un par
+ cobertura de arbol de transiciones
  - si entra a un loop lo hace una sola vez

+ mutaciones
  es un sistema que a proposito lo rompimos
+ cobertura de sentencia
+ cobertura de ramificacion
  - para toda diferencia entro o no entro puede que halla un hueco
+ cobertura de caminos
# white box
+ criteria basado en flujo de datos **practicarlo siempre se toma**
  - vemos cada estado es un sentencia a priori
  - cada flecha indica que variable necesito saber su valor
  - estado se ponen 2 conjuntos
    - los def les doy un valor o le cambio su valor
    - conjunto de valores que yo necesito su valor para dar un cambio
**son todas las ramificaciones**
Existe todo una teoria detras que no veremos de este criterio basado en flujos
+ que es un test ? una tupla de entradas y salidas, valores de entrada. SI no hay tiempor en el parcial no se muestra la salida laura no le gusta al menos indicar con una variables por ejemplo: (valores de entrada,z=...) la z que indique la salida.

# Procesos de testing - niveles de testing

cuanto mas arriba estoy en la V mas nefasto es el codigo que testeo
testing de integracion
  + se supone que los modulos ya fueron testeados por separado
+ testeador es una persona distinta
+ el que arregla el bug por lo general es el programador del codigo

testing de desempeño -> velocidad
testing de estres -> que pasa cuando llegamos al limite
testing de regresion -> testing mas usados **se toma en el parcial**

load testing -> se trata de llenar las cosas

el plan de test

cuando voy a detenerme es importante


+ # Laura dice
+ **Diferencia entre fail y failure** siempre lo toma
el la observacion de que hay un bug adentro
