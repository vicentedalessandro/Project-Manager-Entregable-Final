# E-COMMERCE DE LÍMINE | PROJECT MANAGER - ENTREGABLE FINAL.

## 1. DESCRIPCIÓN DEL PROYECTO

### **CONTEXTO**

La empresa **Límine Energía Renovable** busca expandir sus **ventas** más allá de Junín, Bolívar y la zona. Cómo principal interés se busca lograr un **e-commerce** donde los clientes/usuarios tengan un catálogo de productos y puedan realizar compras atravez de la plataforma. 

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
    4. Métodos de Pago y Facturación.

### **OBJETIVOS SMART**

1. Generar un espacio de encuentro entre Límine y el Cliente. Es importante que en el e-commerce haya una sección "About Us", en donde se hablará brevemente de la empresa, como por ejemplo, intereses, objetivos e integrantes de la misma.
2. Generar un catálogo para la visualización de los productos. Con esto, estaríamos logrando informar al cliente sobre los productos que vende Límine, detallando nombre, marca, precios (contado, tarjeta) y stock. Además, esto tambien le brindará a Límine un sistema para controlar el stock y los precios de sus productos.
3. Generar una lógica de negocio para la venta de productos atravez del e-commerce. Se hará un sistema de pedidos con carrito de compras para que el cliente pueda seleccionar productos del catálogo y realizar la compra de forma rápida y sencilla.
4. Contratar microservicio para métodos de pago y facturación. Buscaremos contratar un microservicio para los distintos métodos de pago y facturación, asi no tendremos que invertir tiempo y costo en desarrollar uno. Ya que, hoy en día, un microservicio de estas características no conlleva un gasto importante, ademas de que evitaríamos tener que generar un presupuesto adicional para el mantenimiento del mismo.

### **STAKEHOLDERS**

**WEGA ENERGY** es el principal proveedor de Límine. Por eso, se buscara mostrar en la pagina un espacio pequeño, pero informativo y de redirección. Con eso ultimo, nos referimos a direccionar al cliente, si asi lo desea, a la página oficial de Wega Energy y asi saber más sobre ellos.

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

Se buscará mantener al equipo sincronizado con el objetivo de identificar obstáculos y planificar el trabajo del día. Tendrá una duración máxima de 15 minutos y se realizara de forma diaria.

**Planificación**

En este encuentro diario va a participar todo el equipo (Scrum Master, Product Owner, y el equipo de desarrollo) donde cada miembro del equipo responde a tres preguntas:
1. ¿Qué hice ayer?
2. ¿Qué voy a hacer hoy?
3. ¿Hay algún obstáculo en mi camino?

#### 2. **Sprint Planning**

**Descripción**

Se buscará definir qué se va a lograr en el próximo sprint y cómo se va a hacer. Este encuentro se realizara al inicio de cada sprint y tendra una duración de 2 a 4 horas. Esto último va a variar dependiendo de la duración del sprint.

**Planificación**

En este encuentro va a participar todo el equipo Scrum. Donde se utilizará una agenda que contiene las siguientes tres etapas:
- **Revisión del Backlog del Producto:** el Product Owner presenta los ítems prioritarios.
- **Establecimiento del Objetivo del Sprint:** el equipo decide qué se puede lograr durante el sprint.
- **División de Tareas:** desglosar los ítems seleccionados en tareas más pequeñas y manejables.

A partir de acá se utilizara un tablero colaborativo, en este caso, **Trello**.

#### 3. **Sprint Review**

**Descripción**

Se buscará mostrar el trabajo completado durante el sprint y se hará un feedback con las partes interesadas. Este encuentro se realizara al final de cada sprint y tendrá una duración de 1 a 2 horas.

**Planificación**

En este encuentro va a participar todo el equipo Scrum y el cliente. Donde se utilizara nuevamente una agenda que contiene las siguientes tres etapas:
- **Demostración:** el equipo va a mostrar el trabajo terminado.
- **Feedback:** obtener comentarios de las partes interesadas.
- **Actualización del Backlog del Producto:** acomodar el backlog respecto al feedback recibido.

#### 4. **Sprint Retrospective**

**Descripción**

Se buscará reflexionar sobre el sprint anterior para mejorar los procesos y la colaboración del equipo. Este encuentro se realizara al final de cada sprint, después de la Sprint Review y tendrá una duración de 1 a 2 horas.

**Planificación**

En este encuentro va a participar todo el equipo Scrum. Donde se utilizara por tercera vez una agenda que contiene las siguientes tres etapas:
- **Revisión del Sprint:** reflexionar sobre lo que salió bien, lo que salió mal y lo que se puede mejorar.
- **Ver Mejoras:** Proponer métodos para mejorar en el próximo sprint.
- **Plan de Mejoras:** delegar responsabilidades para las mejoras propuestas en el punto anterior.

#### **HISTORIAS DE USUARIOS - BACKLOG - SPRINTS**

Las **Historias de Usuarios**, el **Backlog** y los **Sprints** están definidos en el tablero colaborativo.

## 4. **USO DE TABLEROS COLABORATIVOS**

### **SELECCIÓN DE UN TABLERO COLABORATIVO**

Como tablero colaborativo he seleccionado [**Trello**](https://trello.com/b/ozaTjmyb/e-commerce-limine-pm-entregable-final).

**JUSTIFICACIÓN** 

Vi un poco de **Jira**, es una herramienta bastante fuerte, pero todavía no tengo practica en ella. Con Trello ya tenia un contacto mas cercano, aun asi no llego a utilizarlo a su máximo potencia. Sentía que podía ser la herramienta adecuada para realizar este proyecto por su sencillez a la hora de manejar tableros, tarjetas y tareas.

**EJEMPLOS DE USO**

Este contendrá 6 tableros

- **Historias de Usuarios**: contendrá una lista ordenada de las historias de usuarios.
- **Backlog**: contendrá una lista ordenada de las funcionalidades que requiere el producto.
- **Sprints**: contendrá los distintos sprints programados con sus backlogs seleccionados y sus tareas correspondientes.
- **To-do**: tareas por hacer.
- **Current**: tareas en desarrollo.
- **Done**: tareas terminadas.

Las últimos 3 tableros (To-do, Current, Done) servirán como una guía para la realización de tareas, mantener cierta organización con los tiempos y cantidad de tareas que se harán en simultaneo.

---

### **Tableros con Historias de Usuarios, Backlog y Sprints**
![Tableros con Historias de Usuarios, Backlog y Sprints](/imagenes/hu-backlog-sprints.png)

### **Tareas del Sprint**
![Tareas de los Sprints](/imagenes/sprint-task.png)

### **Tablero con las distintas etapas de una Tarea**
![Tableros de Tareas](/imagenes/todo-current-done.png)

---

## 5. **DEFINICIÓN DE ENTREGABLES, CRITERIOS DE ACEPTACIÓN Y ESTIMACIÓN DE TIEMPO**

### **LISTADO DE ENTREGABLES**

1. PÁGINA INFORMATIVA - MVP 
2.  CATÁLOGO DE PRODUCTOS (Implementación de funcionalidades
avanzadas)
3.  PEDIDOS DE COMPRA (Finalización del proyecto)

### **PRIMER ENTREGABLE**

- **Alcance:** Roles y Permisos, Registro de Usuario, Inicio de Sesión de Usuario y About Us de la empresa. 
- **Formato:** será de forma digital. Se presentara la pagina web funcional con los alcances anteriormente mencionados.
- **Fecha de entrega:** 15/08/2024.
- **Responsable**: Carlos García.
- **Criterios de aceptación:** deberán estar finalizados todos los alcances anteriormente mencionados, tambien tendrá que cumplir con los estándares del diseño proporcionado por el desarrollador UX UI y deberá aprobar las pruebas de Testing.
- **Estimación de tiempo para cada tarea y del entregable:**
    - Entregable: 15 días.
    - Sprints: son 2 sprints con una duración de 1 semana cada uno.

        **Sprint 1 (1 semana)**

        | **Tarea**             | **Duración**   |
        |-------------------|------------|
        | Tarea uno         | 2-3 horas  |
        | Tarea dos         | 2-3 horas  |
        | Tarea tres        | 2-3 horas  |

        **Sprint 2 (1 semana)**

        | **Tarea**             | **Duración**   |
        |-------------------|------------|
        | Tarea uno         | 8 horas    |
        | Tarea dos         | 6-8 horas  |
        | Tarea tres        | 3-4 horas  |
        | Tarea cuatro      | 2-3 horas  |
        | Tarea cinco       | 3-4 horas  |

    - Ver tareas en [**Trello**](https://trello.com/b/ozaTjmyb/e-commerce-limine-pm-entregable-final)

### **SEGUNDO ENTREGABLE**

- **Alcance:** agregar o editar Marcas, Categorías y Productos, Catálogo de Productos y Filtrado de los mismos.
- **Formato:** será de forma digital. Se presentara la pagina web funcional con los alcances anteriormente mencionados.
- **Fecha de entrega:** 15/09/2024.
- **Responsable**: María Fernández.
- **Criterios de aceptación:** deberán estar finalizados todos los alcances anteriormente mencionados, tambien tendrá que cumplir con los estándares del diseño proporcionado por el desarrollador UX UI y deberá aprobar las pruebas de Testing.
- **Estimación de tiempo para cada tarea y del entregable:**
    - Entregable: 1 mes.
    - Sprints: son 2 sprints con una duración de 2 semana cada uno.

        **Sprint 1 (2 semanas)**

        | **Tarea**             | **Duración**   |
        |-------------------|------------|
        | Tarea uno         | 8 horas    |
        | Tarea dos         | 6-8 horas  |
        | Tarea tres        | 3-4 horas  |
        | Tarea cuatro      | 2-3 horas  |
        | Tarea cinco       | 3-4 horas  |

        **Sprint 2 (2 semanas)**

        | **Tarea**            | **Duración**   |
        |-------------------|------------|
        | Tarea uno         | 8-10 horas |
        | Tarea dos         | 10-12 horas|
        | Tarea tres        | 3-4 horas  |
        | Tarea cuatro      | 2-3 horas  |
        | Tarea cinco       | 2-3 horas  |
        | Tarea seis        | 1-2 horas  |
        | Tarea siete       | 6-8 horas  |
        | Tarea ocho        | 6-7 horas  |

    - Ver tareas en [**Trello**](https://trello.com/b/ozaTjmyb/e-commerce-limine-pm-entregable-final)

### **TERCER ENTREGABLE**

- **Alcance:** Carrito de Compras, Solicitud de Pedidos y Facturación de Compras.
- **Formato:** será de forma digital. Se presentara la pagina web funcional con los alcances anteriormente mencionados.
- **Fecha de entrega:** 30/10/2024.
- **Responsables**: Carlos García y María Fernández.
- **Criterios de aceptación:** deberán estar finalizados todos los alcances anteriormente mencionados, tambien tendrá que cumplir con los estándares del diseño proporcionado por el desarrollador UX UI y deberá aprobar las pruebas de Testing.
- **Estimación de tiempo para cada tarea y del entregable:**
    - Entregable: 1 mes y 15 días.
    - Sprints: son 2 sprints con una duración de 3 semanas cada uno.

        **Sprint 1 (3 semanas)**

        | **Tarea**             | **Duración**   |
        |-------------------|------------|
        | Tarea uno         | 10-12 horas|
        | Tarea dos         | 16-18 horas|
        | Tarea tres        | 3-4 horas  |
        | Tarea cuatro      | 6-7 horas  |
        | Tarea cinco       | 4-6 horas  |
        | Tarea seis        | 3-4 horas  |
        | Tarea siete       | 6-8 horas  |
        | Tarea ocho        | 2-4 horas  |
        | Tarea nueve       | 1-2 horas  |
        | Tarea diez        | 2-4 horas  |
        | Tarea once        | 2-4 horas  |
        | Tarea doce        | 1-2 horas  |
        | Tarea trece       | 2 horas    |
        | Tarea catorce     | 2-3 horas  |
        | Tarea quince      | 2 horas    |

        **Sprint 2 (3 semanas)**

        | **Tarea**            | **Duración**   |
        |-------------------|------------|
        | Tarea uno         | 8 horas    |
        | Tarea dos         | 8-10 horas |
        | Tarea tres        | 2 horas    |
        | Tarea cuatro      | 2 horas    |
        | Tarea cinco       | 4 horas    |
        | Tarea seis        | 2-3 horas  |
        | Tarea siete       | 5-6 horas  |
        | Tarea ocho        | 6-7 horas  |
        | Tarea nueve       | 2-3 horas  |
        | Tarea diez        | 2 horas    |
        | Tarea once        | 3-4 horas  |
        | Tarea doce        | 1-2 horas  |
        | Tarea trece       | 3-4 horas  |
        | Tarea catorce     | 2 horas    |
        | Tarea quince      | 3 horas    |
        | Tarea dieciséis   | 1 hora     |
        | Tarea diecisiete  | 1 hora     |
        | Tarea dieciocho   | 30 min     |
        | Tarea diecinueve  | 1 hora     |
        | Tarea veinte      | 1 hora     |
        | Tarea veintiuno   | 30 min     |

    - Ver tareas en [**Trello**](https://trello.com/b/ozaTjmyb/e-commerce-limine-pm-entregable-final)

## 6. **IDENTIFICACIÓN DE RIESGOS**

#### **LISTADO DE RIESGOS POTENCIALES DEL PROYECTO**

1. Retrasos en el desarrollo.
2. Problemas de compatibilidad con dispositivos.
3. Baja adopción por parte de los usuarios.

## 7. **EVALUACIÓN DE RIESGOS Y PRIORIZACIÓN**

| **Riesgo**                                 | **Impacto** | **Probabilidad** | **Prioridad** |
|--------------------------------------------|-------------|------------------|---------------|
| Retrasos en el desarrollo                  | Alto        | Media            | Alta          |
| Problemas de compatibilidad con dispositivos | Medio       | Alta             | Alta          |
| Baja adopción por parte de los usuarios    | Alto        | Media            | Alta          |

## 8. **PLANIFICACIÓN DE RESPUESTA A RIESGOS**

### **ESTRATEGIAS DE MITIGACIÓN, ACEPTACIÓN, TRANSFERENCIA Y EVITACIÓN PARA CADA RIESGO IDENTIFICADO**

#### 1. **Retrasos en el desarrollo**

- **Mitigación**:
  - Implementar metodologías ágiles para mejorar la planificación y ejecución del proyecto.

- **Aceptación**:
  - Aceptar que pueden suceder pequeños retrasos y ajustar el cronograma del proyecto según sea necesario, manteniendo comunicación constante con las partes interesadas.

- **Transferencia**:
  - Delegar partes del desarrollo a proveedores externos o contratar consultores para asegurar que las tareas críticas se completen a tiempo.

- **Evitación**:
  - Realizar una planificación detallada desde el inicio, identificando y eliminando posibles "cuellos de botella".
  - Asignar recursos adecuados y asegurar que el equipo esté bien capacitado y preparado.

#### 2. **Problemas de compatibilidad con dispositivos**

- **Mitigación**:
  - Realizar pruebas en múltiples dispositivos y plataformas.
  - Utilizar herramientas de desarrollo multiplataforma y seguir buenas prácticas de desarrollo.

- **Aceptación**:
  - Reconocer que pueden existir algunos problemas de compatibilidad menores.

- **Transferencia**:
  - Contratar empresas especializadas en pruebas de compatibilidad.

- **Evitación**:
  - Optar por tecnologías y estándares que garantizan una mayor compatibilidad desde el inicio del proyecto.
  - Diseñar la aplicación con una arquitectura flexible que facilite adaptaciones y actualizaciones.

#### 3. **Baja adopción por parte de los usuarios**

- **Mitigación**:
  - Realizar estudios de mercado y obtener feedback temprano de los usuarios.

- **Aceptación**:
  - Aceptar que la adopción puede ser progresiva y establecer expectativas realistas con los interesados.

- **Transferencia**:
  - Asociarse con empresas de marketing especializadas para mejorar la visibilidad y promoción del producto.

- **Evitación**:
  - Realizar una investigación de mercado antes del desarrollo para asegurarse de que el producto cumpla con las necesidades básicas.
  - Involucrar usuarios en el proceso de desarrollo para asegurar que el producto sea relevante y útil.

### **PLAN DE CONTINGENCIA PARA LOS RIESGOS MÁS CRÍTICOS**

#### 1. **Retrasos en el desarrollo**

- **Acción Inmediata**: 
  - Daily Stand-ups para identificar y resolver bloqueos rápidamente.
  - Revisar y ajustar el cronograma del proyecto regularmente.

- **Medidas Correctivas**:
  - Reasignar recursos o contratar de forma temporal desarrolladores adicionales.
  - Priorizar las características críticas y aplazar las menos importantes si es necesario.

- **Plan de Comunicación**:
  - Mantener a todos los interesados informados sobre el estado del proyecto y cualquier ajuste en el cronograma.

#### 2. **Problemas de compatibilidad con dispositivos**

- **Acción Inmediata**:
  - Iniciar pruebas intensivas en los dispositivos y plataformas problemáticas.
  - Utilizar entornos de prueba automatizados.

- **Medidas Correctivas**:
  - Desarrollar y lanzar parches o actualizaciones para resolver problemas de compatibilidad.

- **Plan de Comunicación**:
  - Informar sobre los problemas de compatibilidad y las medidas que se están tomando para resolverlos.

#### 3. **Baja adopción por parte de los usuarios**

- **Acción Inmediata**:
  - Realizar encuestas a los usuarios para identificar las barreras de adopción.
  - Analizar datos para detectar patrones y áreas a mejorar.

- **Medidas Correctivas**:
  - Mejorar la experiencia del usuario (UX) y la interfaz de usuario (UI) basándose en el feedback recibido.

- **Plan de Comunicación**:
  - Crear contenido educativo y de soporte para ayudar a los usuarios a entender y utilizar el producto de manera efectiva.

## 9. **PRODUCTO MÍNIMO VIABLE (MVP) Y ROADMAP**

### **DEFINICIÓN DEL MVP**

- **Producto:** e-commerce de productos solares.
- **Definición:** página web para comercio electrónico. Diseñada para publicar productos y venderlos a los clientes interesados.
- **Valor para el Usuario**: brinda un espacio para comprar productos solares desde internet y con cualquier medio de pago.

### **JUSTIFICACIÓN DEL MVP**

Una página web para comercio electrónico de productos solares es útil para lograr los objetivos de expansión de ventas de Límine Energía Renovable. Esta estrategia se justifica por varias razones:

- Alcance y Accesibilidad.

- Comodidad para el Cliente.

- Diversos Métodos de Pago.

- Optimización del stock de productos.

- Visibilidad y Marketing.

- Adaptabilidad y Escalabilidad.

### **PLAN DE LANZAMIENTO DEL MVP**

- Identificación de las Funcionalidades Esenciales: definir claramente las características críticas que resolverán el problema principal del usuario y ofrecerán valor inmediato.

- Desarrollo del MVP: establecer un cronograma de desarrollo con hitos claros y fechas de entrega.

- Pruebas Internas: realizar pruebas internas para saber si el MVP funcione correctamente

- Estrategias de Marketing: realizar anuncios en redes sociales.

- Lanzamiento del MVP: asegurar un soporte adecuado para los usuarios, incluyendo canales de atención y respuesta rápida a problemas o sugerencias.

- Iteración y Mejora Continua: analizar la retroalimentación y los datos recolectados para identificar áreas de mejora.

### **ROADMAP DEL PROYECTO**

```plaintext
Julio 2024
|---------------------------------------------|
          Planificación Inicial

Agosto 2024
            Primer Entregable
|-------------------|-------------------------|
   
|-------------------|-------------------------|
  Sprint 1            Sprint 2

Septiembre 2024
            Segundo Entregable
|-------------------|-------------------------|
   
|-------------------|-------------------------|
  Sprint 1            Sprint 2

Octubre 2024
            Tercer Entregable
|-------------------|-------------------------|
   
  Sprint 1            Sprint 2
|-------------------|-------------------------|
```