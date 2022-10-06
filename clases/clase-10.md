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

# Especificacion de los casos de test

+ script -> te posicionas a donde queres llegar, es un programa que evalua tests
+ test son tuplad de entradas y salidas

sw Cuanto mas grande mas defectos va ha tener
se trata que se corrija el mismo programador que los creo por que lo haria mas rapido
se gasta tiempo hasta que se vuelve de nuevo ha un estado estable
hay muchos ciclos de vida
+ ciclo de vida de los defectos no siempre es lineal
+ hablamos de un failure(ingresado por quien lo encontro) luego hacer un debugging
+ cosmetico NO quiere deci que sea estetico, pues en un juego lo que se ve podria ser un error critico
+ llevar un traking(seguimiento) de los defectos

---

terminamos testing y la proxima clase es la ultima del teorico

# planeamiento del proyecto de sw

desboquen que un proyecto tarda/cuetan mas
tiene 3 partes
1. etapa de plananing, antes que el proyecto se ejecute
2.
3.

Topicos hay 7
punto funcion es una estimacion de esfuerzo
1. planeamiento de proceso
2. **yo no se cuanto va ha costar**
 + se vuelve ha estimar todo el tiempo
 + metodo COCOMO(modelo de costo constructivo) -> muy usado y lo vemos, es considera bueno
 + COCOMO
  - las empresas tunean a a y tunean a b
  - para el parcial no es necesario saberse los numeros
  - a cada uno de esos atributos le hago un analisis
  - multiplico esos 15 atributos por la estimacion inial
  - con el numero obtenido, existen 3 tablas, que dictaminan, el esfuerzo que me ha requerir cada una de las fases
3.
  planificacion detallada -> hecha por una herramienta, para pedir plata se usa esto -> una persona puede ser muy productiva durante 2 o 3 dias
  planificacion global
  Existe una relacion entre esfuerzo y la cantidad de personas para realizar ese proyecto
  cual es la optima division para hacer las cosas -> por ejemplo: tantos meses como la raiz cuadrada de ...
  + organizacion jerarquica -> los jefes son responsables de cosas y no siempre ganan mas que los programadores
  + cuanto mas responsabilidad implica mas paga

# Laura dice

+ **Diferencia entre fail y failure** siempre lo toma
el la observacion de que hay un bug adentro
