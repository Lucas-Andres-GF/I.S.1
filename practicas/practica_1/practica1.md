<<<<<<< HEAD:Practicas/Pr-1.md
## Obtención de los requerimientos.
=======
# Práctica 1
## Obtención de los requerimientos
>>>>>>> 2a2a568021653aef8dbff1840023426144503f66:practicas/practica1/practica1.md

### Definiciones

1. Definir brevemente qué es un requerimiento. 

    Característica necesaria para el sistema a la hora de solucionar un problema o alcanzar cierto objetivo. 

2. Defina requerimientos funcionales y no funcionales.

    - *Funcional:* Describen las funciones que el software debe poseer para alcanzar los objetivos.


    - *No Funcional:* Definen las propiedades/contexto del software. 


3. Defina que es un stakeholder. 

    *stakeholder:* Entidad/Individuo que interviene directa o indirectamente sobre el programa. 

4. Defina las fuentes más importantes para la obtención de información. 

    #### Recopilación de información: ​

    *Métodos discretos​*
    ​

    - Muestreo de la documentación, los formularios y los datos existentes.​

    - Investigación y visitas al lugar.​

    - Observación del ambiente de trabajo.​


    *Métodos interactivos​*


    - Cuestionarios.​

    - Entrevistas.​

    - Planeación conjunta de Requerimientos (JRP o JAD).​

    - Lluvia de Ideas - Brainstorming .

5. Indique los puntos de vista (de manera genérica) que se pueden reconocer en un proyecto de software.

    Tipos de Puntos de vista: 

    *Interactuadores:* Entidades/Individuos/Sistemas que interactúan directamente con el software pudiendo influir en sus requerimientos algún modo.

    *Indirecto:* Stakeholders que no utilizan el sistema ellos mismos, sin embargo influyen en los requerimientos de algún modo.

    *Dominio:* representan las características y restricciones del contexto que influyen en los requerimientos del sistema.

    **Los más específicos son:​**

    Los proveedores de servicios al sistema, los receptores de servicios del sistema.​

    Los sistemas que deben interactuar.​

    Las regulaciones y estándares a aplicar.​

    Las fuentes de requerimientos.​

    Los puntos de vista de las personas que lo van a desarrollar, administrar y mantener.​

    Puntos de vista del marketing y otros que generan requerimientos sobre las características del sistema.​
    
6. Enumere tres problemas de comunicación que pueden existir en la elicitación de requisitos. 

    #### ​Limitaciones cognitivas (del desarrollador)​

    - No conocer el dominio del problema.​

    - Hacer suposiciones sobre el dominio del problema.​

    - Hacer suposiciones sobre aspectos tecnológicos.​

    - Hacer simplificaciones excesivas.​

    #### Conducta humana​

    - Conflictos y ambigüedades en los roles de los participantes.​

    - Pasividad de clientes, usuarios o ingenieros de requisitos.​

    - Temor a que el nuevo sistema lo deje sin trabajo.​

    #### Técnicos ​

    - Complejidad del dominio del problema.​

    - Complejidad de los requisitos.​

    - Múltiples fuentes de requisitos.​

    - Fuentes de información poco claras.


### Problemas

#### a) Indicar para cada problema quienes podrían ser los Stakeholders, los puntos de vista y las fuentes de información.

1. *En un sistema de registro de asistencia a través de técnicas biométricas (huella digital) de **estudiantes universitarios** para la cátedra de Ingeniería I. Este sistema se alimentará de un listado otorgado por la **oficina de alumnos de la facultad**. Además, necesita la autorización del **Jefe de Trabajos Prácticos** del turno correspondiente para luego los alumnos poder registrar el presente. También, el **profesor a cargo de la materia** podrá consultar y listar el estado de cada alumno perteneciente a su cátedra. El sistema sólo se utilizará en el ámbito de la **facultad de Informática** y deberá adecuarse a la reglamentación sobre privacidad de los datos en el ámbito de la misma.*

    *Stakeholders:*
    - Desarrolladores. 
    - Estudiantes universitarios.
    - Oficina de alumnos de la facultad.
    - Jefe de Trabajos Prácticos.
    - Profesor a cargo de la materia.
    - Facultad de Informática.

    *Puntos de vista:* 

    Interactuadores: 
    - Desarrolladores. 
    - Estudiantes universitarios.
    - Profesor a cargo de la materia.

    Indirecto: 
    - Oficina de alumnos de la facultad.
    - Jefe de Trabajos Prácticos.
    - Profesor a cargo de la materia.

    Dominio: 
    - Reglamentación sobre privacidad de los datos en el ámbito de la Facultad de Informática.

    *Fuentes de información:*

    - Oficina de alumnos de la facultad.
    - Observación del ambiente de la facultad. 
    - Investigacion de otros proyectos similares. 
    - Entrevistas a las autoridades y empleados (JTP, Profesor a cargo).


2. *Se desea desarrollar un sistema para gestionar y administrar la atención de **pacientes** en una **clínica** privada especializada en tratamientos alérgicos. Cuando un paciente nuevo es ingresado a la clínica el **empleado** registra todos sus datos personales, posteriormente un **enfermero** registra los controles y realiza las anotaciones habituales (temperatura, presión, peso, reacciones alérgicas etc.). Luego, el paciente es derivado con alguno de los **doctores** de la clínica, quién registra qué tratamientos deberá realizar. El **médico** también se encarga de registrar si el paciente debe quedar internado y debe mantener su historia clínica durante el período que dure el tratamiento. Se sabe que el**director de la clínica** puede consultar las **historias clínicas** de todos los pacientes. El sistema debe adecuarse a las **normativas impuestas por el ministerio de salud de la provincia de Bs As***

    Stakeholders:
    - Grupo desarrollador. 
    - Clínica. 
    - Pacientes.
    - Empleados.
    - Emfermeros.
    - Médicos. 
    - Director de la clínica.
    - Sistema de historias clínicas.
    - Ministerio de salud de la provincia de BSAS.


    Puntos de vista:
    *Interactuadores:*
    - Grupo desarrollador. 
    - Empleados. 
    - Enfermeros.
    - Medicos. 
    - Director de la clínica. 

    *Indirecto:*
    - Clinica, ya que al ser especializada en tratamientos alérgicos, influye en los requerimientos. 
    - Sistema de historias clínicas, usado para obtener los datos de los clientes. 

    *Dominio:*
    - Ministerio de salud de la provincia de Bs As, obligando a que el sistema de adecue a sus normativas y reglamentaciones. 

    Fuentes de información:

    - Observacion de documentación, datos y sistema (ya sea manual) ya existentes.

    - Visitas al lugar e investigación. 

    - Observación del ambiente de trabajo.

    - Entrevistas a empleados, enfermeros y doctores. al igual que personal del ministerio de salud de la provincia de BSAS para obtener mas informacion sobre el dominio.

    - Una reunion JAD, para la planeacion conjunta de requierimiento. 

#### b) Habiendo resuelto los problemas presentados, ¿por qué considera que los requerimientos de los distintos stakeholders podrían entrar en conflicto?

Considero que podrián probocarse conflictos por la cantidad de Stakeholders a disposición. Aplicando buenas y efectivas tecnicas, se solucionarian estos mismo. 


## Entrevistas.

### Parte I Definiciones.

1. Describa qué tipo de información puede obtenerse en una entrevista.

2. Enumere y describa brevemente las etapas de la preparación de una entrevista.

3. Enumere y describa brevemente qué tipos de preguntas puede contener una entrevista. Detalle ventajas y desventajas de cada una.

4. Enumere y describa brevemente qué tipo de estructuras y organización existen para el armado de una entrevista.

5. Analice un formato de la planilla adecuado al momento de armar una entrevista.

6. Analice un formato de la planilla adecuado al momento de terminar una entrevista.

### Parte II Situaciones

**Situación 1**

**Tiene una entrevista con el gerente de ventas de una empresa el cual desea informatizar dicho sector pero no tuvo tiempo de preparar las preguntas por lo que le pidió a un nuevo empleado que le prepare algunas. Cuando las lee, se da cuenta que son inadecuadas.**

**Lea las preguntas y vuelva a redactarlas de una manera más apropiada. Especifique por qué le parece inadecuada cada una de ellas.**

- a. Sus subordinados me dijeron que la empresa no anda bien. ¿Es cierto?

- b. Soy nuevo en esto. ¿Qué he dejado afuera?

- c. ¿Estará usted de acuerdo con los demás gerentes de ventas, respecto a que computarizar las ventas mensuales y luego realizar un análisis de la tendencia tendría usted grandes mejoras?

- d. ¿No habrá una mejor manera de hacer proyecciones de sus ventas, que ese procedimiento anticuado que usted utiliza?

**Situación 2**

**Apenas ha entrado a la oficina de su entrevistado se da cuenta que él no ha dejado de revisar papeles, mirar el reloj y hacer llamadas telefónicas. Usted supone que se siente nervioso porque está atrasado con otro trabajo que tiene que terminar.**

- a. Explique brevemente cómo resolvería tal situación.

- b. Qué opciones propone para el caso en que la entrevista no pueda reprogramarse.

**Situación 3**

**El siguiente es el primer informe de una entrevista realizada por uno de los miembros de su equipo de análisis de sistemas:**

*“En mi opinión, el resultado de la entrevista fue muy bueno. El entrevistado me permitió hablar con él durante una hora y media. Me relató toda la historia del negocio, que fue muy interesante. También mencionó que las cosas no han cambiado desde que él ha estado en la empresa, hace aproximadamente 16 años. En breve nos reuniremos nuevamente para terminar la entrevista, pues, no tuvimos tiempo para analizar las preguntas que preparé “.*

- a. Lea atentamente el informe de la entrevista y explique qué sensación le deja dicho informe.

- b. Indique si existe información que es irrelevante en el informe.

- c. Mencione tres sugerencias que le haría a su compañero de equipo para que realizara una mejor entrevista la próxima vez

### Parte III Problemas
**Problema 1**

**Preparar una entrevista para obtener los requerimientos del siguiente problema:**

**Se desea desarrollar un sistema que permita compartir un vehículo para un viaje. La idea es que cuando una persona tiene que realizar un viaje lo publique en la aplicación. Luego el resto de los usuarios se postulan para acompañarla y el chofer podrá seleccionar quienes viajan. El objetivo es abaratar costos y evitar congestiones en el tránsito.**


**Problema 2**

**Preparar una entrevista para obtener los requerimientos del siguiente problema:**

**CookBooks es un negocio pequeño manejado por una pareja jubilada. Hasta este momento, Cookbooks ha vendido sus libros sólo a través de pedidos por correo. Los dueños ahora quieren desarrollar un sistema en línea para vender libros de cocina difíciles de conseguir y agotados a través de internet. Los visitantes podrán hojear diferentes libros de cocina, pero tendrán que crear una cuenta del cliente antes de poder hacer una compra. Los pagos se aceptarán sólo en línea con una tarjeta de crédito reconocida.**

### Cuestionarios

#### Parte I Definiciones.
- 1) Describa qué tipo de información se busca mediante la aplicación de cuestionarios.

- 2) Describa bajo qué circunstancia considera apropiado utilizar cuestionarios.

- 3) Describa los dos tipos de cuestionarios.


#### Parte II Situaciones

**Situación 1**

**Alguien nuevo en el centro de cómputo de un gimnasio que tiene varias sucursales, viene con muchas ganas de mejorar las cosas que ve dentro del mismo. Dicho centro está desarrollando un sistema en red que usarán todas las sucursales.**

**Dado el siguiente cuestionario verifique si es necesario reescribir las preguntas, justifique.**

![](/images/cuestionario_situacion_1.png)

**Situación 2**

**El siguiente es un cuestionario diseñado por un empleado de una empresa textil que se especializa en fabricar medias para hombres. Este empleado lo escribió en calidad de gerente de la oficina que tiene a cargo la propuesta de compra / implementación de un nuevo sistema de cómputos**

![](/images/cuestionario_situacion_2.png)

- a. Reformule o elimine las preguntas que considere inapropiadas.

- b. Realice una crítica sobre el diseño y el estilo en cuanto a espacio en blanco, espacio para las respuestas,facilidad para responder, etc.

- c. Escriba el cuestionario nuevamente, teniendo en cuenta lo respondido en los puntos a y b.
