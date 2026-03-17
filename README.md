[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-s1_zvqh)
# SDLC-Lab01

- Requisitos de entrega y aprobacion:
  - Respetar el formato Markdown.
  - Solo se aceptan los trabajos por GitHub Classroom
  - Todas las respuestas deben realizarse en el archivo **README.md** del repositorio asignado..
  - El Trabajo en individual. Si bien se puede realizar de forma grupal, la entrega es siempre ***individual***
  - Defensa individual
  - Respetar las fechas de entraga. No se aceptan las actividades fuera de termino.

> Si surge algún cambio o aclaración adicional, se comunicará durante la clase.

### Actividad 1
Teniendo en cuenta el material de clase, responda las siguientes preguntas:

1. ¿Por qué el desarrollo de software no puede realizarse simplemente comenzando a programar?

   R: Porque requiere seguir una serie de tareas interrelacionadas en un orden específico y cumplir con pautas determinadas para asegurar tanto el éxito del proyecto como la calidad del producto resultante.

2. ¿Qué significa que un desarrollo sea dirigido por un plan?

   R: Que implica que el desarrollo comienza con un análisis profundo de las necesidades del cliente para elaborar un plan detallado antes de iniciar la construcción.

3. ¿Cuáles son las ventajas de utilizar un plan de desarrollo?

   R:
- Previsibilidad: Permite presupuestar costos y estimar tiempos de entrega de manera más precisa.
- Estructura: El desarrollo se organiza en etapas secuenciales previamente definidas.
- Claridad de objetivos: Los requisitos acordados al inicio son los que se reflejan fielmente en la versión final del software.
- Eficacia organizacional: Resulta la mejor alternativa para organizaciones con procesos estables que funcionan eficazmente del mismo modo durante años.

4. ¿Qué críticas se hacen a los modelos tradicionales de desarrollo?

   R: de primeras que es difícil introducir cambios una vez que el proyecto ha comenzado, ya que los requerimientos se fijan al inicio, sumado que los proyectos de software rara vez siguen un flujo perfectamente lineal, quiere decir que los errores de una etapa se arrastran fácilmente a las siguientes y a menudo solo se descubren al final, esto empeora por la poca comunicación con el cliente durante el desarrollo, quien no ve el resultado hasta que el software está terminado; y en especial resulta difícil de aplicar en proyectos que son muy grandes o excesivamente complejos.

5. ¿Por qué en la práctica muchas organizaciones combinan metodologías ágiles y modelos dirigidos por un plan?

   R: En la práctica, la mayoría de los proyectos combinan ambos enfoques porque las organizaciones necesitan adaptarse a diferentes necesidades. Muchas compañías integran habilidades ágiles en sus procesos dirigidos por un plan para obtener los beneficios de ambos mundos: la estructura y documentación necesaria para sistemas complejos o regulados, y la flexibilidad de las entregas incrementales para responder a la retroalimentación del cliente. La elección depende de factores como el tamaño del sistema, si el equipo está distribuido, la cultura de la organización o si existen regulaciones externas que exijan documentación detallada.


### Actividad 2

| Etapa                         | Descripción                                                           |
| ----------------------------- | -----------                                                           |
| Análisis                      | Se centra en comprender y documentar qué debe hacer el software.      |
|                               | Incluye la recopilación de necesidades del cliente y                  |
|                               | la definición de los requisitos funcionales y técnicos.               |
| ----------------------------- | --------------------------------------------------------------------- |
| Diseño                        | Se define la arquitectura del sistema.                                |
|                               | Es la etapa donde se decide cómo se estructurará el software,         |
|                               | las bases de datos,                                                   |
|                               | las interfaces de usuario y los componentes técnicos.                 |
| ----------------------------- | --------------------------------------------------------------------- |
| Codificación                  | Es la fase de construcción propiamente dicha.                        Los desarrolladores escriben el código fuente utilizando              
                               lenguajes de programación siguiendo las especificaciones del diseño   | 
| ----------------------------- | --------------------------------------------------------------------- |
| Prueba                        | Se ejecuta el software en entornos controlados para verificar que     |
|                               | funcione correctamente, no tenga errores (bugs)                       | 
|                               | y cumpla con los requisitos iniciales.                                |
| ----------------------------- | --------------------------------------------------------------------- |
| Puesta en marcha / Despliegue | Es la entrega final del producto. El software se instala en el entorno|
|                               | real de producción para que                                           | 
|                               | los usuarios finales puedan comenzar a utilizarlo.                    |
| ----------------------------- | --------------------------------------------------------------------- |


* Luego responda:
  * ¿En qué etapa se obtienen los requerimientos del sistema?
    
    R:En la etapa de Análisis. Es aquí donde se realiza el relevamiento con el usuario para determinar qué problemas debe resolver el sistema.
  * ¿En qué etapa se construye el programa?

    R:En la etapa de Codificación (también llamada Implementación o Construcción), donde se traduce el diseño a un lenguaje que la computadora pueda interpretar.
  * ¿Cuál es el objetivo principal de las pruebas?
    
    R:El objetivo principal es asegurar la calidad del software, detectando fallas, errores o discrepancias respecto a lo solicitado para corregirlos
    antes de que el sistema llegue al usuario final.
### Actividad 3
Ordene las siguientes etapas según corresponda  Diseño
-al modelo lineal secuencial:
- Codificación
- Prueba
- Diseño
- Despliegue
- Ingeniería de requerimientos
---
R:  Ingenieria de requerimientos - diseño - analisis de riesgo -  Prueba - Despliegue.

- Luego responder:
  * ¿Qué problema puede surgir si hay un error en una etapa inicial?
    
    R:Debido a la naturaleza secuencial del modelo, un error en las etapas iniciales (como requerimientos o diseño) se propaga y amplifica en las etapas siguientes. Esto puede causar que se construya un sistema que no es lo que el usuario necesita, lo que implica costos altísimos y una gran pérdida de tiempo para corregirlo al final del proceso.
    --------------------------------
  * ¿Por qué este modelo puede ser problemático cuando los requerimientos cambian?

    R:Porque es un modelo rígido que asume que todos los requisitos pueden definirse totalmente al principio. Como cada etapa debe terminarse antes de pasar a la siguiente, incorporar un cambio a mitad del desarrollo obliga a retroceder y rehacer gran parte del trabajo ya documentado y programado, lo que suele ser inviable en proyectos dinámicos.
    -----------------------------
### Actividad 4
Complete la siguiente tabla.
| Modelo      | Característica principal | Cuándo conviene usarlo |
| ----------- | ------------------------ | ---------------------- |
| Cascada     |                          |  Cuando tu proyecto requiera un grupo pequeño y una necesidad urgente.                 |
| Incremental |                          |                        |
| Prototipos  |                          |                        |
| Espiral     |                          |                        |
| RAD         |                          |                        |

- Responder:
  - ¿Qué modelo es más adecuado cuando existen muchos riesgos en el proyecto?
    R:
  - ¿Qué modelo ayuda a comprender mejor los requerimientos del usuario?
    R:
    
### Actividad 5 – Caso práctico
Una empresa quiere desarrollar un sistema de ventas para un pequeño comercio.

**Características del proyecto:**
- Sistema relativamente pequeño
- Pocos usuarios
- Requerimientos claros
- Tiempo limitado

**Preguntas**

- ¿Qué modelo de desarrollo recomendaría? 

  R: 
- Justifique su respuesta.

  R:
- ¿Qué etapas principales tendría el desarrollo?

  R:

### Actividad 7 – Verdadero o Falso
Indique si las siguientes afirmaciones son Verdaderas (V) o Falsas (F). ***marcar con x la verdaderas, dejar en blanco las falsas***

1. [F] El modelo en cascada permite cambios constantes en los requerimientos.
2. [V] El modelo incremental entrega el sistema en varias versiones.
3. [V] Un prototipo se utiliza para comprender mejor los requerimientos.
4. [V] El modelo RAD busca reducir los tiempos de desarrollo.
5. [V] El modelo en espiral incorpora el análisis de riesgos.
