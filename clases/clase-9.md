
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

## testing de caja negra

+ clase de equivalencia -> parecido al de matematica, lo unico que no cumple al 100% es que un elemento pertenezca a solo un subconjuto del conjuntos general podria pertener a mas de uno.

+ la clases de equivalencia se hace para las entradas y para las salidas.

seleccionar los casos de test
+ En la filminas hay 9 clases de test para la 1ra seleccion -> son 9 auunque las filminas pongan 8 pues son clases de equivalencia restrictiva 
+ En la filminas hay 5 casos de test para la 2da seleccion (es suma no multiplicacion)

## grafos de causa efecto

mi programa tiene cosas que me producen otras cosas
+ tabla
para cada condicion de entrada lo pone en falso o verdadero

# Laura dice

Nos tomara la teoria
causas -> distintas condiciones que pueden ser verdaderas o falsas
