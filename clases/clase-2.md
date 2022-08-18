
# Trabajo Pr ́actico N◦ 1
## Dominio del problema
1. ¿Qu ́e es la ingenier ́ıa del software y cu ́al es su relaci ́on con la Ciencia de la Computaci ́on?

La IG del SW es la APP del enfoque diciplinado, cuantitativo y sistematico al desarrollo, operacion, mantenimiento del SW. Su relacion con las ciencias
de la computacion es trabajar atraves de lenguajes de programacion. 

2. ¿En qu ́e difieren la ingenier ́ıa de software de otras ingenier ́ıas m ́as tradicionales, como la ingenier ́ıa mec ́anica o la
ingenier ́ıa civil?

Difieren que lo que trabajan no es tangible

3. Si el objetivo principal es hacer al software mantenible, liste algunas de las cosas que usted har ́ıa y algunas de las
cosas que no har ́ıa durante la implementaci ́on y el testing.

+ SW mantenible, que haria durante la implementacion y el testing
  - Haria:
    1. Usaria Programacion Funcional
    2. dar nombres significativos a las funciones y variables
    3. usar comentario donde sea necesario
  - No haria:
    1. Usar codigo de funciones anonimas salvo que esten dentro de una llamada o variable nombrada
    2. no llamar a librerias sin mantenimiento
    3. usar variables globales salvo que sea absolutamente necesario

4. Liste algunos de los problemas que surgir ́an si los m ́etodos que usted utiliza para desarrollar aplicaciones peque ̃nas
son utilizados para desarrollar grandes aplicaciones.

 - Lista:
   1. no es escalable
   2. dificil mantenimiento
   3. 

5. Los atributos de calidad de software pueden clasificarse en externos (observables por los usuarios del software) e
internos (concernientes a los desarrolladores). Clasifique los seis atributos de calidad fundamentales mencionados en el
cap ́ıtulo 1 de “An Integrated Approach to Software Engineering”(Jalote).

6. En el cap ́ıtulo 1 de “An Integrated Approach to Software Engineering”(Jalote) se explica que una medida comun-
mente utilizada para la calidad es defectos por KLOC en el software entregado. Para un producto de software dado,
¿c ́omo puede medirse su calidad? ¿c ́omo puede ser estimada su calidad antes de ser entregado?

7. Suponga que durante el desarrollo de un proyecto de software se le diera tiempo extra para mejorar la confiabilidad
del producto final. ¿En qu ́e utilizar ́ıa ese tiempo extra?

+ Restestear lo viejo y testear lo nuevo

8. ¿De que manera un proceso separado en fases ayuda en la obtenci ́on de alta Q & P (calidad y productividad)?

+ permite detectar fallas en el sw y saber en que fase fallo
+ permite verificar las fallas

Cu ́ando parece que estamos haciendo m ́as tareas en un proceso por fases que en uno ad-hoc?

+ 

9. Entre los atributos de calidad enumerados en el cap ́ıtulo 1 de “An Integrated Approach to Software Engineering”
(Jalote) no se encuentra la reutilizabilidad. Defina este atributo, y describa cu ́al es la relaci ́on entre  ́este y portabilidad.

reutilizabilidad: 

+ failure -> manifestacion de que existe un bug adentro

  **que exista el bug no significa que se manifieste**
  
Lo mas caro es la mano de obra -> nuestros cerebros

IG -> Se centra en los procesos
El proceso del desarrollo

Crisis del SW -> No poder definir bien ni costos ni tiempo

Proceso y la Administracion estan separados -> se mantienen los objetivos de calidad -> planificacion y administracion -> usamos metricas para medirlas

Producto separado del proceso

# Fases

+ Separar en fases permite verificar, detectar antes fallas
+ para echar culpa aquines fallaron en su fase -> definir donde esta fallando
+ entrada y salida definida
+ se pueden medir usando metricas

# Analisis de requisitos y especificacion

especificacion -> lo tengo tangible, ver lo que se especifico es pausible, no necesariamente formales
analisis -> descubrir/entender que es lo que se quiere hacer, preguntando al cliente, asesora al cliente, convencer al cliente que se apunte a lo que manejas el desarrollador

Problema -> En tamaño y/o complejidad

SRS -> Solo especifica NO da una solucion, son firmados por abogados, es un contrato, evita ambiguedad si esta bien hecha, necesaria para cobrar

Cliente -> Paga
Usuario -> el que usa el sw

Los requisitos cambian

**SRS NO VALIDA NADA** -> Aunque ayuda a validar

SRS de alta calidad => SW de alta calidad

Perder tiempo en la SRS => Reduccion de Costos

Mas facil encontrar y solucionar en la SRS. Pues los errores en los requerimientos es mas caro si se detecta en la fase de diseño que si se detecta en la fase de requerimientos.

Hay 3 Metodos de Analisis de los Requerimientos

+ Modelado DFD

   1. diagrama de contexto
   2. DFD del sistema existente -> se hace la jerarquia para el entendimiento
   3. DFD del modelado del sistema propuesto -> se lo valida con el usuario, se le muestra hasta donde va ha terner las caracteristicas del sistema

+ Modelado Orientado a Objetos
   - Identificar los objetos
   - definir las clases
   - estructuras
   - buscar atributos
   - buscar asociaciones
   - definir servicios
   - los objetos provee servicios{} y operaciones{} -> super importante saber diferenciarlos
   - cada objeto tiene 3 rectangulitos en uno grande que los abraca. Siempre, si algun rectangulo este vacio no importa es aceptable indica que algo va ahi
   - Diagrama de clase, NO TODOS LOS UML son diagramas de clase
   - nombres, atributos, metodos
   - generalizacion y especificacion -> no importa su sintaxis o definir alguna, la metias sigue la del libro
   - los circulos indican multiplicidad

+ Prototipado -> Se toma en el parcial
  - Descartable
  - Evolucionario

Similares a los que se ven a diseño pero son muy distintos, tener cuidado con sus descripciones

> Una buena pregunta dara una respuesta buena

rol pasivo -> consulta
rol activo -> plasmando lo consultado

> Asegurar completitud
> Asegurar consistencia
> Evitar resolver el problema

Disitintos analistas => distintos SRS , no es conveniente

DFD -> como hacer ? laura dira como se hara
 + representacion grafica del flujo de datos dentro del sistema
 + tiene entradas y salidas
 + tranformadores que toman las entradas y devuelven salidas
 + burbujas deben tener nombres -> suelen ser verbos
 + las burbujas se conectan con flechas -> suelen ser sustantivos
 + rectangulos, fuentes o resumideros, estan fuera del sistema
 + las flechas a rectangulos es la conexion al mundo exterior
 + * indica multiplicidad
 + existen maneras de escribir multiplicidad
 + todas las flechas deben tener nombres
 + como ese transformador hace esa transformacion
 + NO EXISTE LOS LOOPS NI CONDICIONES
 + NO es un Diagrama de Control
 + Identificar las entradas y salidas, comenzar por las entradas, suele comenzarse aveces de atras para adelante
 + Idealmente hacer mas de un grafo
 + Se puede hacer una jerarquia de los grafos

Diccionario de Datos -> de que manera son los elementos que van en las flechitas, al estilo de expresiones regulares

- Poner cosas irrelantes dentro de DFD es grave
- Consistencia en el refinamiento que las flechitas vayan de acuerdo a algo

# SRS -> NO ES EL ANALISIS Y VICEVERSA
  Tiene tratamiento de errores
  Buen desempeño , quiero un cafe en determinado tiempo
  Si se tiene o no seguir ciertos estandares
  Recuperacion del Sistema pos algun problema
  No es directo
  
  Cliente(cerebro) <-corrrectitud- SRS
  SRS -completitud-> Cliente
  + Caracteristicas -> memorizarlas a todas tal cual
   1. correcta ->  el usuario/cliente quiere, lo correcto es el cliente
   2. completa -> 
   3. no ambiguedad -> que no tenga requerimientos que se puedan interpretar de otras formas
   4. consistencia -> no exista dos requeriemientos que se contradigan, cuando no se toca lo mismo por muchos lados
   5. verificable -> tiene un elemento que chequea el requerimiento que se espera
   6. rastreable -> que para cualquier elemento en el SRS debo saber que parte del sistema final lo hace y viceversa
   7. modificable -> que un elemento del SRS no este especificado en varios lugares(muy ligado a la consistencia)

  Conmponentes de la SRS:
   Funcionalidad, desepeño, restirciones ....

  Como se comporta el programa en situaciones extremas lo debe decir la SRS
  
  Requqerimientos:
  Tener en cuenta la escabilidad
  + Estaticos
  + Dinamicos
  
  Lenguajes de especifcacion -> no usar conjugacion de verbos tantos

# Alcance -> Sirve para el take home pero no se suele tomar en el parcial

# Palabras repetidas Laura

Mantenimiento
Escala
Calidad -> Estandar ISO
Productividad -> tiempo y costo
consistencia
cambio
Funcionalidad -> Las funciones que el cliente quiere
Usabilidad -> que sea facil aprender usar
mantenibilidad -> importante la legibilidad

Pide 3 caracteristicas del SRS, describir cualquiera, estudiar 3 faciles

### Siempre toma casos de uso

# Glosario

brainstroming: discutir de manera correcta ideas
taxes: impuestos
traceable: rastreable
