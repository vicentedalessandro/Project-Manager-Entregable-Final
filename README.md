# E-COMMERCE DE LÍMINE | PROJECT MANAGER - ENTREGABLE FINAL.

## 1. DESCRIPCIÓN DEL PROYECTO

### **CONTEXTO**

La empresa **Límine Energía Renovable** busca expandir sus **ventas** más allá de Junín, Bolívar y la zona. Cómo principal interes se busca lograr un **e-commerce** donde los clientes/usuarios tengan un catálogo de productos y puedan realizar compras atraves de la plataforma. 

### **OBJETIVOS PRINCIPALES**
1. Expandir las ventas a todo el país.
2. Generar un e-commerce para facilitar el **OBJETIVO N°1**

### **STAKEHOLDERS**

- WEGA ENERGY

## 2. PLANIFICACIÓN INICIAL

### **ALCANCE DEL PROYECTO**

- **E-commerce**:
    1. About us.
    2. Catálogo de Productos.
    3. Carrito de Compras.
    4. Metodos de Pago y Facturación.

### **OBJETIVOS SMART**

1. Generar un espacio de encuentro entre Límine y el Cliente. Es importante que en el e-commerce haya una seccion "About Us", en donde se hablará brevemente de la empresa, como por ejemplo, intereses, objetivos e integrantes de la misma.
2. Generar un catálago para la visualización de los productos. Con esto, estariamos logrando informar al cliente sobre los productos que vende Límine, detallando nombre, marca, precios (contado, tarjeta) y stock. Ademas, esto tambien le brindará a Límine un sistema para controlar el stock y los precios de sus productos.
3. Generar una logica de negocio para la venta de productos atraves del e-commerce. Se hará un sistema de pedidos con carrito de compras para que el cliente pueda seleccionar productos del catalago y realizar la compra de forma rapida y sencilla.
4. Contratar microservicio para metodos de pago y facturación. Buscaremos contratar un microservicio para los distintos metodos de pago y factuación, asi no trendremos que invertir tiempo y costo en desarrollar uno. Ya que, hoy en dia, un microservicio de estas caracteristicas no conlleva un gasto importante, ademas de que evitariamos tener que generar un presupuesto adicional para el mantenimiento del mismo.

### **STAKEHOLDERS**

**WEGA ENERGY** es el principal proveedor de Límine. Por eso, se buscara mostrar en la pagina un espacio pequeño, pero informativo y de redirección. Con eso ultimo, nos referimos a direccionar al cliete, si asi lo desea, a la página oficial de Wega Energy y asi saber más sobre ellos.

## 3. **IMPLEMENTACIÓN DE SCRUM**

### **DEFINICIÓN DE ROLES DE SCRUM**

#### **EQUIPO DE TRABAJO** (Generado con la ayuda de ChatGPT)

#### **Scrum Master: Vicente Daniel D'Alessandro** (Project Manager) <--- No estoy hecho con ChatGPT :)

#### **Product Owner: Ana López** (Ayudante de Project Manager)

**Fortalezas:**
- Técnicas: Amplia experiencia en la gestión de proyectos, excelente comprensión del ciclo de vida del desarrollo de software, habilidades avanzadas en la planificación y priorización de tareas.
- Emocionales: Gran capacidad de liderazgo, habilidades de comunicación excepcionales, empática y orientada a la resolución de conflictos.

**Debilidades:**
- Técnicas: Conocimientos limitados en programación y diseño de interfaces de usuario.
- Emocionales: A veces puede ser demasiado perfeccionista, lo que puede llevar a retrasos en la toma de decisiones.

#### **Desarrollador Frontend: Carlos García**

**Fortalezas:**
- Técnicas: Experto en HTML, CSS y JavaScript, experiencia con frameworks modernos como React y Vue.js, habilidades avanzadas en el desarrollo de interfaces de usuario responsivas.
- Emocionales: Creativo, entusiasta y con una gran pasión por el diseño visual.

**Debilidades:**
- Técnicas: Poca experiencia en pruebas automatizadas y optimización del rendimiento.
- Emocionales: Puede ser impulsivo y, a veces, le cuesta aceptar críticas constructivas.

#### **Desarrolladora Backend: María Fernández**

**Fortalezas:**
- Técnicas: Experta en lenguajes de programación como Java, Python y Node.js, sólida comprensión de bases de datos y arquitecturas de microservicios, experiencia en el desarrollo de API RESTful.
- Emocionales: Analítica, meticulosa y con gran capacidad para resolver problemas complejos.

**Debilidades:**
- Técnicas: Menos experiencia en la integración de servicios de terceros y tecnologías emergentes.
- Emocionales: Puede ser introvertida y tener dificultades para comunicarse efectivamente con el equipo de frontend.

#### **Diseñador UX/UI: Juan Pérez**

**Fortalezas:**
- Técnicas: Experto en diseño de interfaces de usuario y experiencia de usuario, domina herramientas como Sketch, Figma y Adobe XD, habilidades en diseño gráfico y prototipado.
- Emocionales: Innovador, empático y con una fuerte orientación hacia la satisfacción del usuario.

**Debilidades:**
- Técnicas: Conocimientos limitados en desarrollo frontend y backend.
- Emocionales: Puede ser sensible a las críticas y a veces se siente abrumado por el feedback negativo.

#### **Tester de Calidad: Laura Jiménez**

**Fortalezas:**
- Técnicas: Experta en pruebas de software manuales y automatizadas, habilidades avanzadas en el uso de herramientas como Selenium, JUnit y Postman, experiencia en el desarrollo de casos de prueba y documentación de errores.
- Emocionales: Detallista, paciente y con una gran capacidad para mantener la calma bajo presión.

**Debilidades:**
- Técnicas: Conocimientos limitados en el desarrollo de software y debugging avanzado.
- Emocionales: A veces puede ser demasiado meticulosa, lo que puede llevar a conflictos con el equipo cuando los plazos son ajustados.

### **CEREMONIAS SCRUM**

#### **DESCRIPCIÓN Y PLANIFICACIÓN**

#### 1. **Daily Stand-up**

**Descripción**

Se buscará mantener al equipo sincronizado con el objetivo de identificar obstáculos y planificar el trabajo del día. Tendra una duración maxima de 15 minutos y se realizara de forma diaria.

**Planificación**

En este encuentro diario va a participar todo el equipo (Scrum Master, Product Owner, y el equipo de desarrollo) donde cada miembro del equipo responde a tres preguntas:
1. ¿Qué hice ayer?
2. ¿Qué voy a hacer hoy?
3. ¿Hay algún obstáculo en mi camino?

#### 2. **Sprint Planning**

**Descripción**

Se buscará definir qué se va a lograr en el próximo sprint y cómo se va a hacer. Este encuentro se realizara al inicio de cada sprint y tendra una duración de 2 a 4 horas. Esto último va a variar dependiendo de la duración del sprint.

**Planificación**

En este encuentro va a participar todo el equipo Scrum. Dondé se útilizara una agenda que contiene las siguientes tres etapas:
- **Revisión del Backlog del Producto:** el Product Owner presenta los ítems prioritarios.
- **Establecimiento del Objetivo del Sprint:** el equipo decide qué se puede lograr durante el sprint.
- **División de Tareas:** desglosar los ítems seleccionados en tareas más pequeñas y manejables.

A partir de aca se utilizara un tablero colaborativo, en este caso, **Trello**.

#### 3. **Sprint Review**

**Descripción**

Se buscará mostrar el trabajo completado durante el sprint y se hara un feedback con las partes interesadas. Este encuentro se realizara al final de cada sprint y tendra una duración de 1 a 2 horas.

**Planificación**

En este encuentro va a participar todo el equipo Scrum y el cliente. Dondé se útilizara nuevamente una agenda que contiene las siguientes tres etapas:
- **Demostración:** el equipo va a mostrar el trabajo terminado.
- **Feedback:** obtener comentarios de las partes interesadas.
- **Actualización del Backlog del Producto:** acomodar el backlog respecto al feedback recibido.

#### 4. **Sprint Retrospective**

**Descripción**

Se buscará reflexionar sobre el sprint anterior para mejorar los procesos y la colaboración del equipo. Este encuentro se realizara al final de cada sprint, después de la Sprint Review y tendra una duración de 1 a 2 horas.

**Planificación**

En este encuentro va a participar todo el equipo Scrum. Dondé se útilizara por tercera vez una agenda que contiene las siguientes tres etapas:
- **Revisión del Sprint:** reflexionar sobre lo que salio bien, lo que salio mal y lo que se puede mejorar.
- **Ver Mejoras:** Proponer metodos para mejorar en el próximo sprint.
- **Plan de Mejoras:** delegar responsabilidades para las mejoras propuestas en el punto anterior.

#### **HISTORIAS DE USUARIOS - BACKLOG - SPRINTS**

Las **Historias de Usuarios**, el **Backlog** y los **Sprints** estan definidos en el tablero colaborativo.

## 4. **USO DE TABLEROS COLABORATIVOS**

### **SELECCIÓN DE UN TABLERO COLABORATIVO**

Como tablero colaborativo he seleccionado **Trello**. 
https://trello.com/b/ozaTjmyb/e-commerce-limine-pm-entregable-final

**JUSTIFICACIÓN** 

Vi un poco de **Jira**, es una herramienta bastante fuerte, pero todavia no tengo practica en ella. Con Trello ya tenia un contacto mas cercano, aun asi no llego a utilizarlo a su maximo potencia. Sentia que podia ser la herramienta adecuada para realizar este proyecto por su sencilles a la hora de manejar tableros, tarjetas y tareas.

**EJEMPLOS DE USO**

Este contendra 6 tableros

- **Historias de Usuarios**: contendra una lista ordenada de las historias de usuarios.
- **Backlog**: contendra una lista ordenada de las funcionalidades que requiere el producto.
- **Sprints**: contendra los distintos sprinst programados con sus backlogs seleccionados y sus tareas correspondientes.
- **To-do**: tareas por hacer.
- **Current**: tareas en desarrollo.
- **Done**: tareas terminadas.

Las últimos 3 tableros (To-do, Current, Done) serviran como una guia para la realizacion de tareas, mantener cierta organizacion con los tiempos y cantidad de tareas que se haran en simultaneo.

### **Tableros con Historias de Usuarios, Backlog y Sprints**
![Tableros con Historias de Usuarios, Backlog y Sprints](/imagenes/hu-backlog-sprints.png)
### **Tareas del Sprint**
![Tareas de los Sprints](/imagenes/sprint-task.png)
### **Tablero con las distintas estapas de una Tarea**
![Tableros de Tareas](/imagenes/todo-current-done.png)