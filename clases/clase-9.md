
existe testing de hw

# Testing

Exite un testing para cada una de las caracteristicas de calidad
confiabilidad -> menor cantidad de errores
con el tiempo uno se da cuenta que es de calidad

El programador es el que introdce una falla o el programador lo programo para que falle

> hay que aceptar que te critiquen, un buen tester es un buen critico

desperfecto => defecto
defecto => desperfecto es muy dificil encontrarlo

+ desperfecto
+ defecto
+ failure es 

## Rol de testing

habra defectos despues de los requerimientos, codificacion

Set de test o conjunto de test

La confianza crece a medida que no encuetro bug pero no implica su ausencia 

El buen tester tiene que tratar de mostrar los desperfectos

Identificar ese bug que hemos dicho que existe

**revisar la pagina de Amy tiene buenas cosas**

Oraculos de test: Es quien sabe la respuesta correcta

testear es ejecutar mi programa
como se que lo que dio es correcto, uso el oraculo para comprobarlo

+ correcto
+ incorrecto
+ indeterminado: cuanto esta comparacion no se puede dar

+ El oraculo puede ser humano, no es lo ideal
+ El oraculo puede generase automaticamente desde las especificaciones

+ testear es caro y ademas los programas son muy grandes para testear todos
+ los casos de test son infinitos. Ejemplo: un vaso de cafe pongo en la cafetera espero 1 ms y me da un cafe y asi con cada 2 ms, 3ms, ...

+ Criterio de seleccion **(se toma si o si en el parcial)**

Existen 2 productividades, que es lo que queremos

confiabilidad -> que no existe un error que es detetado por uno de los conjutos de test y que no es detectado por otro conjunto de test, creo que algo asi
validez -> que para cualquier error dentro de mi programa habra un test que lo detecte, muy mas dificil de cumplir

cumplir ambos es complicado

## psicologia del tester

un tester tiene que ser destructivo

# testing de caja negra

+ clase de equivalencia -> parecido al de matematica, lo unico que no cumple al 100% es que un elemento pertenezca a solo un subconjuto del conjuntos general podria pertener a mas de uno.

+ la clases de equivalencia se hace para las entradas y para las salidas.

seleccionar los casos de test
+ En la filminas hay 9 clases de test para la 1ra seleccion -> son 9 auunque las filminas pongan 8 pues son clases de equivalencia restrictiva 
+ En la filminas hay 5 casos de test para la 2da seleccion (es suma no multiplicacion)

## grafos de causa efecto

mi programa tiene cosas que me producen otras cosas
+ tabla
para cada condicion de entrada lo pone en falso o verdadero

## testing de a pares -> el menos usado

un par de los parametros este en un cierto estado => reducir

ejecutar cada par como un test
unir pares de combinaciones

## casos especiales

adivinanza del error
usar el juicio para adivinar

## basado en estados

sistemas etiquetados de transicion, son burbujas que se unen entre ellos
uno puede agarrar la especificacion
estados logicos del sistema
si modelo mal es grave
tiene muchas ventajas el modelado pero es dificil hacerlo bien
hacer tantos test que cubran todas las transiciones
minima cantidad de test que cubran todas las transiciones
si el mismo test me sirve para mas de una transicion trato de juntarlo pero podria no saber donde fue el fallo lo que implica el debugging mas complicado
son maquinas que elijen test
generar test automaticos pueden comprobar cosas que son repetitivos que un humano nunca lo haria

+ criterio de mutacion -> se usa mas en el hw que en el sw(pues uno no cambia una asignacion de x < 0 por x > 0 y ve que se rompe de los casos de test)

rompo algo para ver algo

+ criterio basado en flujo de control
  - criterio de cobertura de sentencia
    suponiendo que una sentencia es hasta que termine en un ";"
si una cobertura es 100% de sentencia no significa que no halla errores

**hablar de codigos NO DE IMPLEMENTACION**
+ test de caja blanca -> mirar dentro del codigo ..
+ test de caja negra -> mirar una especificaion ...

# Laura dice

Nos tomara la teoria
causas -> distintas condiciones que pueden ser verdaderas o falsas
coverage(cubrimiento): cuanto estoy testeando del codigo, implementacion, especificacion, ...
mutacion: en algo esta roto
sentencia(en cada lenguaje): 
