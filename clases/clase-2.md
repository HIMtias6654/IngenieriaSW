
Trabajo Pr ́actico N◦ 1
Dominio del problema
1.. ¿Qu ́e es la ingenier ́ıa del software y cu ́al es su relaci ́on con la Ciencia de la Computaci ́on?
2.. ¿En qu ́e difieren la ingenier ́ıa de software de otras ingenier ́ıas m ́as tradicionales, como la ingenier ́ıa mec ́anica o la
ingenier ́ıa civil?
3.. Si el objetivo principal es hacer al software mantenible, liste algunas de las cosas que usted har ́ıa y algunas de las
cosas que no har ́ıa durante la implementaci ́on y el testing.
4.. Liste algunos de los problemas que surgir ́an si los m ́etodos que usted utiliza para desarrollar aplicaciones peque ̃nas
son utilizados para desarrollar grandes aplicaciones.
5.. Los atributos de calidad de software pueden clasificarse en externos (observables por los usuarios del software) e
internos (concernientes a los desarrolladores). Clasifique los seis atributos de calidad fundamentales mencionados en el
cap ́ıtulo 1 de “An Integrated Approach to Software Engineering”(Jalote).
6.. En el cap ́ıtulo 1 de “An Integrated Approach to Software Engineering”(Jalote) se explica que una medida comun-
mente utilizada para la calidad es defectos por KLOC en el software entregado. Para un producto de software dado,
¿c ́omo puede medirse su calidad? ¿c ́omo puede ser estimada su calidad antes de ser entregado?
7.. Suponga que durante el desarrollo de un proyecto de software se le diera tiempo extra para mejorar la confiabilidad
del producto final. ¿En qu ́e utilizar ́ıa ese tiempo extra?
8.. ¿De que manera un proceso separado en fases ayuda en la obtenci ́on de alta Q & P (calidad y productividad)?
Cu ́ando parece que estamos haciendo m ́as tareas en un proceso por fases que en uno ad-hoc?
9.. Entre los atributos de calidad enumerados en el cap ́ıtulo 1 de “An Integrated Approach to Software Engineering”
(Jalote) no se encuentra la reutilizabilidad. Defina este atributo, y describa cu ́al es la relaci ́on entre  ́este y portabilidad.



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

Similares a los que se ven a diseño pero son muy distintos, tener cuidado con sus descripciones

> Una buena pregunta dara una respuesta buena

rol pasivo -> consulta
rol activo -> plasmando lo consultado

> Asegurar completitud
> Asegurar consistencia
> Evitar resolver el problema

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

### Siempre toma casos de uso

# Glosario

brainstroming: discutir de manera correcta ideas
