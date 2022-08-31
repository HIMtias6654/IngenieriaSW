
# Problema de SRS

Estan involucrados aun el cliente y el usuario, ambiguo palabras

Una buena SRS nos va ha servir para ver si despues esta bien o no el sw.

Analisis -> Tratar de entender el problema -> Funciones, Objetos, Eventos(poco visto)
         -> Protipado, es descartable en el diseño
Especificacion -> Plasmarlo en un Documento
Validacion -> chequeo

# Especificaion

+ Orgaanizado de secciones y subsecciones
+ se habla del lenguaje que se va usar
+ referencias a otro documento
+ descripcion global -> perspectiva, restrcciones, supocisones y dependencias
+ requerimientos -> que sw usamos, restriciones del sw, velocidad de internet // No se dice el como -> No hay algoritmia
   - sino usmos casos de uso

# Caso de Uso
+ Npmbre: Describe que hace el caso de uso
+ Puede haber un actor secundario o alguna pre-condicion
+ Describe que hace el usuario y como el sistema debe responder
  - interaccion entre los usuarios y el sistema
  - se enfoca solo en la funcionalidad
  - contrato entre el usuario y el comportamiento del sistema
  - Generalmente los ptos numerados del escenario principal un pto es el actor, el sgte. pto es el sistema, y asi(secuencial pero puede ser en paralelo)
  - No le importa lo que haga internamente
  - escenario princiapal -> se cummplio el objetivo
  - escenario alternativo -> no se cumplio el objetivo o si no se llego a cumpletar, listar las mas importantes
  - aveces hay subjetivos
  - usen gramatica simple -> usar presente

# Validacion de los requerimientos

La omision. la incosistencia, echos incorrectos
ambiguedad -> tener mas de una interpretacion
Revisiones, inspeccion, listas de control para cada una de las fases -> Lo vemos al final de la materia
para la fase de requerimientos tiene su propia lista de control -> se muestra las preguntas en las slides
costoso llevar una SRS a un lenguaje formal

# Metricas

El tamaño del SRS es el principal factor
Estimar un tamaño
A la larga nos ayuda a cobrar y ver tiempos
No usamos la SRS como metrica porque depende demasiado del autor
1 pto funcion indica X LOC de algun lenguajes => cantidad de lineas de un proyecto => estimo un costo

#### Metricas de Calidad

Numero de errores encontrados
Numero de cambios de la SRS => muchos => mal echa la SRS

Otro metrica COCOMO -> NO LO VEMOS

# Arquitectura

El usuario tiene problema para dimensionar el costo de un cambio
Una buena arquitectura ayuda a los cambios
Los subsistemas lo mas independientemente posibles
Los mejores pagados, mucha experiencia
Para cada elemento nos preocupa las propiedades externas
La definicion no habla de bondad,ie, que es una buena o mala arquitectura
Entenderlo desde la perspectiva de los planos de una casa -> Paredes
Seleccion de tecnologia, servidores
Propiedaddes de confiabilidad y desempeño
Exiten maneras de graficarlo
Vision de partes del sistema -> dividir en parte logicas => dividir en grupos de trabajo
Para que dividirlo ? Comprension y comunicacion
Que cosas puedo reusar de sistemas previos, tuneamos lo que ya se tiene
**impacto**: Un cambio que involucre a mas de una parte => Un costo mas grande
Divide y dice que hace cada parte
No hay una unica arquitectura
Se hacen distintas vistas => exponer distintas propiedades Ej. un plano de la luz habla de la luz y del gas veo un plano del gas
+ Vitas(hay un triangulito)
  - Modulos: elementos dentro del codigo, clase, relacion es parte de, usa a, ...
  - Componentes y conectores: elementos entidades de ejecucion, objetos => Que define y Que describe **se pregunta en el parcial**, ver slides
    * ser consistentes con el dibujo elejido para tal componente
    * no todos los conectores son binarios
    * se pueden realizar extensiones
  - Asignacion de recursos

Estilo arquitectonico, MVC ? entra aqui ?
  + tubos y filtros
  + datos compartidos, variantes: **se toma en el parcial que significa cada variante **
    - pizzara
    - repositorio
  + cliente-servidor
    - comunicacion iniciada por el cliente
    - lugares fisicos distintos por lo general
  + publicar y subscribir, parecido al estilo pizarra
  + peer-to-peer
  + procesos que se comunican

Por lo general uno usa combinaciones de estilos
Describir lo que estamos haciendo usando estos estilos
**En el parcial debemos decir las restricciones de cada estilo de manera exhaustiva**

> Paramos en los documentos de estilos arquitectonicos

## Diseño de Alto Nivel
## Diseño de Bajo Nivel

# Trabajar con Objetos

Tengo capas de abstracciones
Conjunto de funciones que se abstraen de la implementacion

# Laura quiere

Analisis Estructurado -> Dar sus 3 pasos en el parcial

Caracteristicas de la SRS -> saberselas de memoria

Slide del Alcance -> Usarlo para el TakeHome

Siempre saber describir un caso de uso
casos de uso con subobjetivos NO son Usuales NO los piden

Si se puede usar el etc pero cuanto mas exhaustivo sea mejor
lenguaje formal. no vemos

Se toma si o si metrica de punto funcion
Saber componentes y conectores

# Glosario

oraculo: es quien sabe la respuesta correcta

buffering: procuparse por el orden que llegan las cosas

pasivo: no nos avisa
