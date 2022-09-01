
# Analisis OO y diseño OO

Analisis -> Entender para hacer la SRS

Diseño -> Trato de resolver lo que quiero

Ya en el diseño hago incapie en la parte mas dinamica de la cosa

Todo elemento que hereda va ha tener polimorfismo

**Principio Solid** -> saberlo, va al parcial ?

# Diseño detallado

Tiene lenguajes naturales o formales

Natural -> Impreciso, ambiguo, tiende a errores

# PDL process design languaje

Propone usar un lenguaje natural
No queremos demasiado detalle
no es tan independiente del lenguaje de programacion por que nuestro cerebro tiende a pensar en alguno en particular
sintaxis parecida a un lenguaje de programacion estructurado
castellano estructurado
para ciertos lenguajes puede existir un PDL que se genera su codigo automatico
un tipo de pseudo-codigo

**No existen procedimientos claves**

Pautas a seguir: ...
 Es la formalizacion de este ingle-castellano para paso a paso hacercanos mas al codigo
 El ingles es acotado -> no queremos tiempo verbales
 
 + 3 metodos de verificaion
    - recorrido del diseño, quiero a la gente que quiero programar para decir si lo escrito es infactible
    - revision critica del diseño
    -  verificadores de consistencia 

+ Metricas
  - comlejidad ciclomatica
  - vinculo de datos
  - metrica de cohesion -> trata de ver si existen ejecuciones del modulo que no estoy usando => que tal ves no tenga tanta cohesion

# Codificacion -> Se toma siempre en el 2do parcial o final

Implementar el diseño de la mejor manera posible

parte del costo de testing es alto => busca reducir el costo de mantenimiento

codigo falta de leer y comprender

Experimento Weinberg -> dividio a distintos grupos de gente y les pidio una cosa especifica y el mismo tiempo a todos los grupos => todos los grupos entrgaron el proyecto con lo que se les pidio que sean especificamente y dio con que:
1- rapido -> muchos errores
2- no tenia errores -> super lento

> Al programar se debe tratar siempre de pensar que alguien vendra a chequear lo que hicimos

+ Programacion estructurada
  - tratar de ver por que habia tantos problemas con el go to
  - estructura estatica -> que es como yo leo las lineas de la sentecia
  - estructura dinamica -> como la maquina lo va ha computar
  - cuanto mas cerca este uno de la otra mejor
  - razonamos sobre el codigo no estamos haciendo testing
  - razonamineto dinamico es tan bien el flujo de control
  - queremo hacer un razonamiento lineal
  - tratar de pensar y de juntar que la estructura dinamica y estatica este muy cerquita
  - ver y ser conciente de la suposicion

+ ocultamiento de la info
  - si lo que queremos reducir acoplamiento -> le damos permiso a los de afuera a solo ciertas cosas

+ practicas

+ estandares de codificacion
  - inicializar las variables de los loops ... -> busca reducir el scope
  - todo lo estudiado para la SRS es aplicable para hacer comentarios

# Proceso de codificacion

+ Proceso de condificacion incremental

+ Desarrollo dirigido por test

Necesito ver si el codigo necesita refactorizacion
La refactorizacion no agrega codigo mas bien no agrega funciones nuevas sino mejora lo que tiene
La incrementabilidad -> si he o no generado todo el codigo
problema: lo que no se nos ocurrio testerar puede que no este en el codigo en si
suponemos que los tester no tienen errores
test -> es muy raro que este errado si puede que como fue programado este errado
Que el codigo necesitaria refactorizacion

+ Programacion de a pares
  - conjuntamente uno tipea y otro revisa lo que esta tipeando
  - en general es codigo bueno
  - efectividad del metodo -> no demostrado

+ control de codigo fuente

# Refactorizaion

Se toquetea el codigo aun si el diseño incial es bueno
Proposito es mejorar el diseño
> NO es corregir errores. Se hace sobre codigo que este funcionando.
Fin de simplicar sin cambiar su comprension
Vemos si el acoplamiento, cohesion, abierto-cerrado se cumple sino lo mejoramos
**Debe ser hecha en pasos pequeños** -> para poder ver donde cometiste el error al refactorizar pues en general haces un paso pequeño y testeas
Si las leyes cambian => SRS cambia => Paramos lo que hacemos(al menos 2 meses), chequeamos el diseño, hacemos la refactorizacion y hacemos los cambios nuevos, continuamos

+ Malos olores
  - codigo duplicado
  - metodos largos
  - lista larga de parametros -> posible error al usarlos pues se debe tener en cuenta el orden de los argumentos ingresados
 
 + Mas comunes
  - metodos
  - clases
  - jerarquia

+ mejora de metodos
+ mejora de clases
+ mejora de jerarquias
  - subir y bajar metodos -> en que lugar de la herencia deberia estar las cosas

# Verificacion

+ Inspeccion de codigo
  - existen herramientas que hacen testeos estaticos
  - son caros
  - estan listas de control
+ testing de unidad
+ metodos formales
  - falla en la escabilidad -> por eso no se usan en la practica
falso negativo -> es cuando test paso y en realidad habia un bug -> tal ves el test estaba mal hecho
falso positivo -> cuando test dice que hay un error pero no habia uno ahi
inconcluso

> El buen codigo es invisible

# Proceso de codificacion

# Laura dice

C/C++ -> lo mas rapido

al crear nuestro propio tipo de dato -> es buena practica limitar bien las cotas o limites del tipo de dato

No sera muy estricta si agregacion, composicion o asociacion nos confundimos. No asi con la herencia

> Cada profe de la practica hace incapie en distintas areas

> Chun -> le importa la identacion
> Diego Lis -> le molesta la herencia mal usada

Metodologia 5 -> nombres y para que son

Metricas(DIT, NOC, ...) -> para que sirven, para que quiero la metrica, que hacemos con el numero obtenido al final

Saberse la formula de las metricas

No pide saberse del formato del documento

Semana que viene traer todas las dudas y tambien se presenta el TH

Hasta lo de hoy va al parcial -> En la filminas figura como clase 5

> la refactorizacion NO se debe sacar Ni poner. Eje. Un monitor se refactoriza todo lo que ya hacia el monitor no cambio en nada, si se cambio eso no es refactorizacion o se refactoriza mal

**Acoplamiento se toma todos los parciales**

# Glosario

Estado persistente
supocision: que no es una certeza
scope: donde una variable va ha ser usada
fail: que hubo un error
