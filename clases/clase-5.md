
**Describir los 5 pasos de la metodologia. Sus nombres y que hacen. El metodo 5 de heuristica no figura en el libro pero si va**

# Orientacion a Objetos

  Los datos a diferencia de las funciones modelan todo junto. Tiene la posibilidad de tener estados.
  ADOO Analisis y diseño orientado a objetos NO LAS VEMOS pero se hacen juntos.
  A la altura del analisis se hizo de una OO por lo tanto se puede seguir con un diseño OO.
  Tenemos 
  + interfaces
  + aplicaciones
  especifican los mecanismo de control
  + utilidad.
  Enfocamos en el comportamiento dinamico del sistema.
  Estado persistente(se mantiene en el tiempo) de un Objeto. El Objeto depende de su estado y no de las entradas como las funciones.
  Cada objeto tiene una identidad distinta.
  Clase es una plantilla que crea un Objetos con operaciones publicas, privadas y protegidas: las hijas las pueden ver y los nietos dependiendo del lenguaje.
  Que es una instancia ? Las instancias las voy creando. Es un objeto en particular y cada objeto es de una clase. Puedo tener clases y no haber creado ningun objeto.
  Realcion de 
  + asociasion
    - linea sin flecha
  + agregacion
    - flecha con pintada
  + composicion
    - flecha no pintada

  + Herencia. La herencia siempre implica polimorfismo(En un momento me comporto como un elemento del padre y a veces como el hijo). Cada vez un objeto que hereda debe tener conciencia a que clase estoy pertenenciendo.
  Herencia Multiple UN Hijo hereda de dos padres-
  Herencia simple.
  **La optimizacion temprana es la raiz de todos los males**
    - Esticta: No Re definimos la super clase
    - No estricta: Podemos re definir la clase. Tiene muchos efectos Colaterales.
      1. Hereda una funcion de mi clase madre y luego la redefino en mi clase
      2. la misma funcion de mi clase madre lo tomo pero le añado mas parametros de entrada.
  El diseño se puede evaluar:**siempre se toma**
  + Acoplaimento
    - Por interaccion -> ocurre debido a metodos de una clase que invocan a metodos de otra clase. No podemoa hacer nada con esta.
    - por componente
    - por herencia
  + Cohesion
    - de metodo
    - de clase
    - de herencia -> que este bien hecha. Por re uso NO es lo optimo.
  + Principio Abierto-Cerrado:
    - Cerrado para modificarlas
    - Abiertas para extenderlas
    - Minimiza el riesgo de dañar
    - siguiendo el principio obtendremos una buena herencia
    - **principio de sustitucion de liskov, siempre se toma en los parciales**Si yo en esa subclase re defini una de las funciones no voy a poder cumplir el principio. Hay lenguajes que ni permiten el principio de liskov.
    - Se busca que se cumpla abierto-cerrado. Y principio de liskov. En general si cumples liskov tenes implicito el principio de abierto-cerrado.
    - Osea en genral, liskov => abierto-cerrado.
 
# Metodoslogia de diseño
 Similar a las funiones.
 
 Metodologia OMT
 
 **Estudiar los titulos de los 5 pasos y que son, siempre va al parcial**
 
 1.
 
 2.Producir el modelo dinamico -> Veo lo que despues serian clases. Tiene una relacion de esto sucede y lo hace en el tiempo. Una vez modela en los escenarios. Los podemos sacar de los Caaos de Uso de la SRS.
 
 3.
 
 4. ... .Sumo lo que obtuve los 3 modelos que obtuve antes.
 
 5. Optimizar y empaquetar. Lo mas dificil es ajustar herencia teniendo en cuanta abierto-cerrado.
 
 Los metodos no los pedimos en la clase pero si saberlas.
 
 ### Metricas
 
 WMC metodos pesados por clases. Ponerle para cada metodo una complejidad. Sumamos. Mientras mas grande la clase mas propensa a tener errores.
 
 DIT Profundidad del arbol de herencia. Mientras mas profundo la herencia mas propensa a errores.
 
 NOC cantidad de hijos. Si muchos me usan la clase debe estar bien hecha.
 
 CBC aoplamiento entre clase. Siempre hay alguna de estas.
 
 RFC respuesta para una clase. 
