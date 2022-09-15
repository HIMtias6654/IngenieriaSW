# Codificaciòn

+ Programacion estructura


  - Estatica -> Orden del codigo
  - Dinamica -> El orden que se ejecuta
  - Objetivo: Se busca que sean ambas lo mas cercano posible

+ No dejar huecos en el codigo para que los hackers la utilizaen

+ Proceso de codificaion incremental -> 1ra flecha desde que tengo la especificaion del codigo se hace una eleccion de que se va ha implementar
+ luego de que hize el codigo se trata de mejorar creando nuevos test para  testear la parte que implemente luego los corro , teste todo no solo lo que implmente, si no tengo errores chequeo cuanto falta implementar, si me falta vuelvo para atras y vuelvo a decidir. Una vez que no me falta nada para implementar termino.

+ Desarrollo dirigido por test -> Se decide un grupo de caracteriticas para crear,  se escribe el script del test, el codigo para pasar esos test, se corren los test, sec orrigen los errores, hasta que no hallan errores. Se hace un analisis si se necesita refactorizacion, volver a correr los test si no hay error y considero el codigo me sirve, analizo si me falta algo o no.

+ Es muy importante lo del turneo en programacion en pares
+ Refactorizacion -> Si se toam los tipos. Es importante hacer los test lo mas automatico que se pueda. Se puede tardar hasta como 48 hs testeo.
+ Vale la pena refactorizar lo hace el jefe de diseño
+ Malos olores
+ Grandes refactorizaciones(Se toma en el parcial su definicion y las 3 que hay)
  - De metodos
    - extraccion -> objetivo es separar
    - agregar/eliminar parametros -> visto en el acoplamiento
  - Desplazar clases
  - Extrraccion de clases -> Problema de cohesion
  - Remplazar valores de datos por objetos
  - mejoraras de jerarquia -> habla de la herencia

+ Verifiacion
   - inspeccion de codigo -> se apliza luego que el codigo este terminado, se supone que se hizo un testeo previo
   - listas de control -> importante: todos los loops terminan
   - testing de unidad -> se lo hace el mismo programador que lo hizo
   - escalibilidad con metodos formales son pequeños

> El buen codigo es invisble

# Modelo de Procesos

+ Proceso de desarrollo -> habla de esfuerzo
+ Especifican una idea de como deberian ser las etapas, de como va ha ser su proyecto en la realidad
+ modelo de proceso -> lo que hacemos en la materia
+ Especificaion del proceso -> Es el plan de lo que se hara

Modelos comunes(Se toman los 4 en el parcial)
1. Cascada -> Es una secuencia lineal de las fases que vimos, saber: la secunacia lineal , como son los pasos
              cada fase comienza solo cuando la anterior termino
              depende de 
ventajas -> Es simple, divide las fases claramente
  desventaja -> se deja de hablar con el cliente luego del analisis de los requerimientos, se trato de solucionar con cascada con feedback aun que solo un nivel atras o se dice a cuanto retroceder
3. Prototipado
  - Mini cascada -> y se sigue las fases siguientes
  - mostrarle el usuario para la venta
  - es descartado
  - permite un buen feedback
  - hace un test tonto
  ventaja -> es mas estable, hay una experencia en la creacion
  desventaja -> tiempo y costo
5. Iterativo
  SCRUM es un iterativo pero no el unico
  uso los beneficios de cascda+prototipado
  incremental
  ayuda al testing
  **la lista del control del proyecto** -> dice todas las cosas que debo hacer en el proyecto(mini cascada con un grupo de elementos) y esto se repita
  + modelo en espiral -> 4 pasos -> primeros intentos hacia lo que es SCRUM
  Aplicacion -> Es muy efectivo
  Es muy customizable
  Problema del todo o nada -> puede   que al producto lo ames o lo odies
  + hay otros enfoques
7. Timeboxing
  La idea es planear tiempos fijos para hacer cada una de las cosas
  priemero fija el tiempo
  la especificacion que hara ese tiempo
  Es un estilo de iterativo
  desventaja -> equipos de trabajo suele ser muy grande. necesito mucha gente en cada etapa
  Esas ejecuciones en paralelo es de cada proyecto distinto NO de un mismo proyecto -> Es lo mas normal
  necesita mucha sincronizaciòn

# Laura dice

Saber si o si las tablas de comparaciones en las slides de los 4 Modelos Comunes

pipline: a la larga todos los recursos esten siendo usados

SCRUM -> No va al parcial

La de IA ve que nos gusta

+ el costo del iterativo es costoso pero lo quieren pues el cliente puede intervenir con su opiniones

+ La semana del 20 y 22 de septiembre es consulta de TakeHome

> El testing no es exhaustivo, se trata que lo sea lo maximo posible

feasibility(viabilidad, factibilidad): lo que tengo planeado crear tiene o no coherencia

Esfuerzo -> Costo, Tiempo -> Cada empresa tiene una medida de esfuerzo por ejemplo 1 medida de esfuerzo es necesito 3 personas que trabajan 8 hs en el dia

+ Libro: Habitos Atomicos

+ Lo importante es reveer lo que uno hizo

+En el libro el printRepoort() es una truchada para el entendimiento de la refactorizacion

+ Control de codigo fuente -> No va al Parcial, pero se usa en los proyectos

Proceso basico de proceso de codificacion incremental -> esos tres items que se ponen si lo escribimos en el parcial desapruebas debes decribir las que hacen cada flecha, es mas o menos como lo escribi arriba.

refactorizacion -> mejora el diseño del codigo, no agrega funcinalidades.

test es una tupla
script del test es todo lo que te rodea para hacer el test

Slide de Arquitectura estaba mal la parte de Tuberias y Filtros -> Sobre el buffering
Mañana estara el slide correcto

Existen 2 tipos de empresas los que la hakearon y se entreraron y los que no lo saben aun


Estandares de codificacion: Convenciones de Nombre, etc -> No va al parcial
