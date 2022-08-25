# Arquitectura

Se divide en pedazos para poder comprender en pedazos de manera separada
Para saber en las revisiones quienes estan involucrados

# Familias de arquitectura, estilo arq para vista C&C 

+ tubos y filtros
No se puede bifurcar un pipe
No necesecita saber a quien esta mandando
unidireccional
filtro trabaja de manera asincrona y hacen buffering

los usuarios no se comunican entre si, en algunos estilos

publicar.subscribir -> cada evento es publicado similar al pizarra

# organizacion del documento
justificacion de las decisiones -> por que hay mucho recambio dentro de las empresa, debe estar si o si en alguna parte del documento

> *la arquitectura es un diseño de muy alto nivel*

Tarea post arquitectura -> lo idel es que se le consulte de su decision de aquitectura

# Metodo ATAM -> Tecnica antigua

Yo te doy pero vos me das
Agarra las aquitecturas y las analiza entre ellas
Y ver coonseciones: pierdo propiedades pero obtengo algo mas
+ recolectar escenarios: situaciones, de interes para el analisis -> o sea situaciones criticas. veo excepcionales solo si son importantes
+
+ vistas del sistema que seran evaluadas, disitntas vistas necesario para distintos analisis osea algunas vistas seran mejor para cierto escenarios
+ a la larga yo quiero elegir una de esas arquitecturas

performance -> desempeño
scablity -> escabilidad
availability -> accesibilidad o entendibilidad

# metodo CBAM

cost of performance(desempeño ?)
cost of scablity
cost of availability(disponibilidad ?)

> lo importante es poder elegir cualquier opcion

# Diseño

Se realiza antes de la implementacion
intermedio entre los lenguajes y el codigo
la idea es partir de algo abstracto a algo mas concreto

> Hoare dice:
  1. simple y obvio -> facil detectar los problemas
  2. tan dificil -> de modo que los problemas no se vean

Objetivo, crear un plano del sistema

**tienen mucho impacto al testing y mantenimiento**

+ diseño arquitectonico -> visto
+ diseño de alto nivel -> vemos hoy

# diseño de alto nivel -> dividido en 2

1. Orientado a Funcion
2. Orientado a Objeto

Oraculo: Los Requerimientos
(Esto mas un pensamiento abstracto)Criterio de evaluacion de diseño:
+ correcion -> si el diseño implementa los requerimientos
+ eficiencia -> los componentes hacen uso apropiado de los recursos. Ej. Si algo usa mucho el cpu
+ simplicidad -> dificil ser hechas y mas facil de mantener o descubrir un error

principios fundamentales(son 3, **saberlas**)
1. particion y jerarquia -> para dividir y conquistar, para poder modificar un pedazo qeu el todo, una buena jerarquia tiene particion
2. abstraccion -> ocultar que es lo que pasa adentro, ve ha los componenete como caja negra
  - funcional -> pueden tener pre y post condicion
  - de datos -> habla de una clase, notar que no tienen pre o post condicion
3. modularidad -> se pueden implementar de manera separada, mejora la claridad, reducir los costos

+ Estrategias
   - top-down -> cuando no tengo nada, en cada paso tenemos una claridad de lo  que hacemos. problema: suponemos que hacemos un modulo que al final no podemos hacer. primer parte refinamiento paso a paso, despues los pros y los contras
   - si ya tengo algo parto de ahi, en empresas grandes

# Acoplamiento
   division entre modulos
   pocos
   imposible el nulo acoplamiento
   buscamcos dependencia infima
   hay metricas para medir cuanto depende uno de otro
   nos interesa que tipo de conexion tenemos
   complejidad de interfaces simple -> vemos la cantidad de parametros
   fuerza de conexion entre los modulos
   maneras de definir los acoplamientos
   **variables compartidas -> feas**
   balance una interfaz un poco sucio pero muy facil
   hibrido es FEO
   
# Cohesion
  alta
  es interno al modulo
  Tipos de cohesio, orientado a funcion son 7 . **parcial va: cuales son y cual es su orden**
  - casual -> hecho asi no mas
  - logica -> tiene algo de coherencia, no es optima
  - temporal -> los elementos estan realionados en el tiempo osea se ejecutan juntos
  - procedular ->
  - comunicacional -> todos se comunican con algun dato
  - secuencial
  - funcional -> todos los elementos estan relacionados para realizar un unica funcion
  hay un test en las filminas para detectar algunas de las 7 -> **no se toma en el parcial**
  
# Notacion y especificacion del diseño

Diagrama de estructura
+ notacion grafica, modulos e interaccion entre ellos
+ cada flecha se etiqueta
+ se puede hacer una correlacion entre codigo y diagrama de estructura
+ metodologia de diseño estructurado nos da pautas para hacer un diagrama de estructura
  
 > alta cohesion y bajo acoplamiento se busca

# Laura dice

nos centramos en Componentes y conectores
definicion de tubos y filtros de la filmina dice que es eso va
no podemos hacer un ejemplo de pipe and filter de la filmina en el parcial
organizacion del documento **NO va al parcial**
ATAM saberlo
scoping: esta variable vive en este lugar
*sber los 3 criterios para evaluar el diseño: correcion, eficiencia, simplicidad **memorizar** que es ? que se supone que hace ?*
**los principios fundamentales**
**metdodo atam -> Tomara los 5 pasos los nombres y que hacen**
interfaz oscura: que no quede claro cual es el dato que se va ha usar
+ funcion que toma datos
+ funcion que toma control -> tienes una flag o if que indica que es lo que tengo que hacer dentro de la funcion => mejor dividir en pequeñas funciones
**siempre se toma acoplamiento o cohesion**

# Nada que ver pagina para encontrar libros
!(https://es.z-lib.org/)
