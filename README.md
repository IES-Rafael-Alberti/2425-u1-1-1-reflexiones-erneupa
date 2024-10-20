[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Z6NE2ogx)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16551484&assignment_repo_type=AssignmentRepo)
# Práctica 1: Introducción al desarrollo. Reflexiones.

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica010/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:** [P.1 Introducción al desarrollo. Reflexiones.]
- **Módulo:** [EDES] (`PROG`, `IS`, `EDES`, etc.)
- **Unidad de Trabajo:** [U1]
- **Fecha de Creación:** [15/10/2024]
- **Fecha de Entrega:** [20/10/2024]
- **Alumno(s):** 
  - **Nombre y Apellidos:** [Aarón Neupaver Montiel]
  - **Correo electrónico:** [aneumon2402@g.educaand.es]
  - **Iniciales del Alumno/Grupo:** [1 DAW A]

## Descripción de la Actividad
[Descripción detallada de la actividad, objetivos, y contexto necesario para comprenderla. Explicar en qué consiste la actividad y qué se espera que el alumno desarrolle o implemente.]

## Instrucciones de Compilación y Ejecución
1. **Requisitos Previos:**
   - [Lenguaje de programación y versión]
   - [Entorno de desarrollo o dependencias necesarias]

2. **Pasos para Compilar el Código:**
   ```bash
   [Comando para compilar el código]
   ```

3. **Pasos para Ejecutar el Código:**
   ```bash
   [Comando para ejecutar la aplicación]
   ```

4. **Ejecución de Pruebas:**
   ```bash
   [Comandos para ejecutar pruebas, si las hubiera]
   ```

## Desarrollo de la Actividad
### Descripción del Desarrollo
[Explicación de cómo se ha abordado el desarrollo de la actividad, incluyendo las decisiones de diseño, estructura del código y enfoque de resolución de problemas. Se recomienda adjuntar diagramas o capturas de pantalla si es necesario.]

#P1.10: Reflexión y discusión sobre los resultados

##1. Relación software y hardware

###1.1. Primera parte

####1.1.1. ¿Cómo se ejecuta el código en el procesador?

Recoge las instrucciones en forma de código específico, para poder realizar una serie de cálculos, de tal manera para que tal programa funcione.

####1.1.2. ¿Qué hace la memoria RAM con la información del botón o el LED?

El botón le manda un impulso de energía al ser pulsado al LED, entonces la RAM almacena este dato que permite que este se ilumine o al contrario.

####1.1.3. ¿Cómo se comunican los periféricos (botón y LED) con el procesador?

La ALU recoge los datos procesados en el mismo procesador, controlando o recibiendo señales de estos dos periféricos. 

###1.2. Segunda parte

####1.2.1. ¿Cómo interactúan el procesador, la memoria y los periféricos en la ejecución del programa?

El procesador ejecuta el programa desde la memoria y se comunica con los periféricos para recibir o enviar datos. La memoria guarda las instrucciones y datos, mientras los periféricos permiten al procesador reflejarlo al exterior.

####1.2.2. ¿Qué pasa con los datos en la memoria cuando el programa se ejecuta?

Permite a los datos comunicarse con los periféricos para recibir o enviar datos.

####1.2.3. ¿Qué roles juegan las instrucciones del software en esta interacción?

Las instrucciones del software le dicen al procesador cómo usar la memoria RAM y comunicarse con los periféricos para ejecutar el programa.


####1.2.4. ¿Cómo se relaciona esta simulación con lo que ocurre en un ordenador real?

Dicha simulación refleja cómo un ordenador real trabaja al hacer que el procesador, la memoria y los periféricos se comuniquen entre sí. 

##2.Del código fuente al ejecutable

####2.1. ¿Cómo se diferencia el código fuente del código objeto y del ejecutable?

El código fuente es el  que escribimos, el código objeto es un archivo compilado del código fuente en un formato intermedio y el código ejecutable es el archivo final que se  ejecuta en un ordenador.

####2.2. ¿Por qué el ordenador no puede entender el código fuente directamente?

El ordenador solo reconoce el código máquina constituido por 0 y 1.

####2.3. ¿Por qué es importante el paso de enlazado en la creación de programas?

Es importante, ya que une todos los archivos en uno solo "ejecutable", de esta manera corroboramos que todas las referencias sean correctas y optimizamos el programa.

####2.4. ¿Qué ocurre si falta alguna de las etapas (código objeto o ejecutable)?

Como a través del código objeto podemos crear el archivo ejecutable, no pasaría nada, el problema es si ocurre al contrario, en este caso, no podremos conseguir el código objeto de ninguna manera. 

##3.Generación de código intermedio

####3.1. ¿Cómo difiere el código intermedio del código ejecutable tradicional?

El código intermedio está listo para ejecutarse a través de cualquier máquina virtual mientras que el tradicional no, esto se debe a que el código intermedio, lo prepara para ejecutarse en todas las máquinas como dije antes.

####3.2. ¿Por qué es útil tener una máquina virtual?

Gracias a las máquinas virtuales, nos servirán como intermedio entre el código y el hardware.

####3.3. ¿Qué ventajas ofrece el código intermedio?

Proporciona portabilidad, optimización, seguridad, facilidad de depuración e interoperabilidad.

####3.4. ¿Además de java, qué otros lenguajes usan máquinas virtuales?

Hay otras lenguajes que las utilizan, como C#, Scala, Kotlin o Groovy. 

##4.Lenguajes de programación

###4.1. Primera parte

#####Compara el proceso de ejecución entre el lenguaje compilado y el interpretado.

####4.1.1. ¿Qué diferencias notaron en el proceso de compilación frente a la ejecución directa?

En la compilación, sabemos el error a la hora de hacer ese proceso, de esta manera luego al ejecutarse está más optimizado, mientras que la ejecución directa, va leyendo línea por línea hasta encontrar el error, por tanto es mas lento .

####4.1.2. ¿Qué pasa si hay un error de sintaxis en cada lenguaje? ¿Cuándo se detecta el error?

En un lenguaje, el error de sintaxis lo encontraremos a la hora de compilarlo, mientras el otro va leyendo el programa línea a línea hasta encontrar el problema. 

###4.2. Segunda parte

#####Compara un lenguaje de alto nivel con uno de bajo nivel.

####4.2.1. ¿Qué notaron sobre la abstracción entre los lenguajes de alto nivel y bajo nivel?

Los lenguajes de alto nivel son fáciles de usar y funcionan en diferentes máquinas sin cambios, mientras que los lenguajes de bajo nivel son más difíciles y requieren más control del hardware, pero no siempre funcionan en otras máquinas.

####4.2.2. ¿Qué ventajas y desventajas encontraron en cada uno?

El de alto nivel es más fácil para nosotros aun que no tenemos tantas ventajas en cuanto al sistema. Y el de bajo nivel, es todo lo contrario. 

###4.3. Tercera parte

#####Compara un lenguaje orientado a objetos vs funcional.

####4.3.1. ¿Cómo funciona la organización de datos en Java usando objetos y métodos?

En este lenguaje se organiza datos usando objetos que combinan información y acciones, lo que hace que el código sea más fácil de entender y manejar

####4.3.2. ¿Cómo es diferente trabajar en un enfoque funcional en Python, usando solo funciones puras?
Es de diferente hasta el punto de crear un código más claro, predecible y fácil de manejar. 

###4.4. Reflexión final

####4.4.1. ¿Qué lenguajes se sintieron más fáciles de usar? ¿Por qué?

De los que hemos visto, Python ya que muchas veces lees lo que escribes, sin necesidad de tener un alto conocimiento.

####4.4.2. ¿En qué casos es preferible usar un lenguaje compilado frente a uno interpretado?

Es preferible cuando  queremos que nuestro programa esté mas optimizado.

####4.4.3. ¿Cuándo es mejor usar un lenguaje de alto nivel en lugar de uno de bajo nivel?

Cuando necesitamos un código que no requiera tanto de funcionalidades de la máquina y queremos que sea desarrollado rápidamente.

####4.4.4. ¿Cómo se siente trabajar con el paradigma orientado a objetos en comparación con el imperativo o funcional?

Trabajar con el enfoque orientado a objetos es más fácil para representar cosas del mundo real , mientras que los enfoques imperativo y funcional son más simples y rápidos para tareas pequeñas, pero pueden volverse complicados en proyectos grandes.



### Código Fuente
[Aquí se incluirá un enlace directo a los archivos de código fuente en el repositorio, por ejemplo, si se está usando GitHub: `src/main.java` o algún enlace directo.]

### Ejemplos de Ejecución
- **Entrada 1:** Descripción de la entrada y valor de prueba.
- **Salida Esperada 1:** Explicación de la salida esperada y el resultado de la prueba.

### Resultados de Pruebas
[Aquí se detallará cómo se ha verificado la funcionalidad del código, incluyendo resultados de pruebas automatizadas o manuales, en caso de que las haya.]

## Documentación Adicional
- **Manual de Usuario:** [Enlace a la documentación del usuario, si existe]
- **Autorización de Permisos:** Verificar que el profesor tenga permisos de lectura en el repositorio para revisar el código.

## Conclusiones
[Resumen de las conclusiones alcanzadas al desarrollar la actividad, las lecciones aprendidas, y posibles mejoras que se puedan implementar en futuras entregas.]

## Referencias y Fuentes
[Aquí se listarán las fuentes consultadas para el desarrollo de la actividad, tales como documentación oficial, artículos, o cualquier recurso externo relevante.]

### Notas Adicionales:
1. **Nombres de Archivos y Repositorios:**
   - Asegúrate de que el nombre del archivo o repositorio siga la estructura definida: `XXX-idActividad-Iniciales`.
2. **Permisos:**
   - Verifica que el profesor tenga los permisos necesarios para acceder al repositorio o documento.
3. **Formato:**
   - Si se entrega en formato PDF o Google Docs, asegúrate de cumplir con el mínimo y máximo de folios establecidos.
4. **Compilación y Ejecución:**
   - Detalla claramente cómo compilar y ejecutar el código, incluyendo las instrucciones en el archivo `README.md`.
