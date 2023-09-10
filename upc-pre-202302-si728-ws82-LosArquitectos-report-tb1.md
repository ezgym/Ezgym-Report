# **Capítulo I: Introducción**
## **1.1. Startup Profile**
### **1.1.1. Descripción de la Startup**

Los Arquitectos es una startup de desarrollo de software que otorga, mediante el uso de deep learning y visión artificial, la facilidad de que nuevas personas puedan adentrarse al mundo fitness teniendo la seguridad de que la aplicación los ayudará a supervisar en vivo sus rutinas de ejercicio.

**Misión**

Facilitar rutinas de ejercicios a personas que comienzan a adentrarse al mundo fitness y supervisar sus rutinas de ejercicios mediante el uso de visión artificial y deep learning.

**Visión**

Ser una startup reconocida a nivel nacional y la primera opción de nuevos personas que ingresan por primera vez al mundo fitness.

### **1.1.2. Perfiles de integrantes del equipo**

**Nombre:** Vanessa Irene Flores Ñahuis

<img src="assets/profile_vanessa.jpg" width="150"/>

**Carrera:** Ingeniería de software

**Descripción:** Soy estudiante de la carrera de ingeniería de software en la Universidad Peruana de Ciencias Aplicadas. Me considero una persona dispuesta a aprender nuevas habilidades y aportaré al equipo y al desarrollo del trabajo con los conocimientos que he adquirido en cursos previos y los conocimientos que adquiriré en este curso.

**Nombre:** José Sebastián Chacón Córdova

<img src="assets/profile_sebastian.jpg" width="150"/>

**Carrera:** Ingeniería de software

**Descripción:** Soy estudiante de la carrera de Ingeniería de Software, actualmente curso el 8vo ciclo. Tengo conocimiento en diversos lenguajes de programación tales como python, C, java y Dart y considero que estos podrán ser de utilidad en el desarrollo de este curso.

## **1.2. Solution Profile**
### **1.2.1 Antecedentes y problemática**

### **1.2.2 Lean UX Process**

#### **1.2.2.1. Lean UX Problem Statements**

#### **1.2.2.2. Lean UX Assumptions**

#### **1.2.2.3. Lean UX Hypothesis Statements**

#### **1.2.2.4. Lean UX Canvas**

## **1.3. Segmentos objetivo**

# **Capítulo II: Requirements Elicitation & Analysis**
## **2.1. Competidores**
### **2.1.1. Análisis competitivo**

### **2.1.2. Estrategias y tácticas frente a competidores**

## **2.2. Entrevistas**
### **2.2.1. Diseño de entrevistas**

### **2.2.2. Registro de entrevistas**

### **2.2.3. Análisis de entrevistas**

## **2.3. Needfinding**
### **2.3.1. User Personas**

### **2.3.2. User Task Matrix**

<table>
    <thead>
        <tr>
            <th rowspan=2>User Task</th>
            <th colspan=2>Cliente</th>
        </tr>
        <tr>
            <th>Frequency</th>
            <th>Severity</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Buscar rutinas predeterminadas de ejercicio</td>
            <td align="center">Multiple</td>
            <td align="center">High</td>
        </tr>
        <tr>
            <td>Filtrar rutinas por duración</td>
            <td align="center">Rare</td>
            <td align="center">Medium</td>
        </tr>
        <tr>
            <td>Filtrar rutinas por tipo</td>
            <td align="center">Rare</td>
            <td align="center">Medium</td>
        </tr>
        <tr>
            <td>Activar la supervisión de la ejecución de rutina de ejercicio</td>
            <td align="center">Multiple</td>
            <td align="center">High</td>
        </tr>
        <tr>
            <td>Agregar rutinas de ejercicio a favoritos</td>
            <td align="center">Rare</td>
            <td align="center">Medium</td>
        </tr>
        <tr>
            <td>Visualizar rutinas favoritas</td>
            <td align="center">Rare</td>
            <td align="center">Medium</td>
        </tr>
        <tr>
            <td>Calificar rutinas de ejercicio</td>
            <td align="center">Rare</td>
            <td align="center">Medium</td>
        </tr>
        <tr>
            <td>Visualizar detalles de un ejercicio en específico</td>
            <td align="center">Rare</td>
            <td align="center">Medium</td>
        </tr>
        <tr>
            <td>Adquirir membresía</td>
            <td align="center">Rare</td>
            <td align="center">Medium</td>
        </tr>
    </tbody>
</table>

### **2.3.3. Empathy Mapping**

### **2.3.4. As-is Scenario Mapping**

# **Capítulo III: Requirements Specification**
## **3.1. To-Be Scenario Mapping**

## **3.2. User Stories**

<table>
    <thead>
        <tr>
            <th>User Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Criterios de aceptación</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">US01</td>
            <td>Buscar rutinas</td>
            <td>Como cliente quiero buscar rutinas de ejercicios para ejercitarte y mantenerte más saludable</td>
            <td>Escenario 1: Búsqueda de rutinas
            <br>Dado que me encuentro en la sección “Encontrar rutinas” cuando hago clic en la barra de búsqueda, escribe el nombre de la rutina de deseo y hago clic en el ícono de la lupa entonces el sistema muestra todos las rutinas que coincidan con lo especificado.
            <br><br>Escenario 2: No se encontró ninguna rutina
            <br>Dado que me encuentro en la barra de búsqueda de la sección “Encontrar rutina” cuando introduzco el nombre de una rutina que no coincida con ninguna rutina alojada en la aplicación y hago clic en el ícono de la lupa entonces el sistema muestra el mensaje “No se encontró ninguna rutina”.</td>
        </tr>
        <tr>
            <td align="center">US02</td>
            <td>Filtrar rutinas por duració</td>
            <td>Como cliente quiero filtrar rutinas de ejercicios según su duración para encontrar aquellas rutinas que se adecuen al tiempo que tengo disponible.</td>
            <td>Escenario 1: Búsqueda filtrada según duración
            <br>Dado que me encuentro en la sección “Encontrar rutina” cuando selecciono la duración que deseo y hago clic en el ícono de la lupa entonces el sistema muestra todas las rutinas que coincidan con la duración especificada.
            <br><br>Escenario 2: Selección de una sola opción
            <br>Dado que me encuentro en la sección “Encontrar rutina” y una opción de duración está seleccionada cuando hago clic en otra opción de duración entonces el sistema mantiene seleccionada solamente la última opción escogida.
            <br><br>Escenario 3: Especificar duración
            <br>Dado que me encuentro en la sección “Encontrar rutina” cuando selecciono la opción duración personalizada, ingreso los parámetros de duración mínima y máxima, y hago clic en el ícono de la lupa entonces el sistema muestra las rutinas que coincidan con la duración especificada.
            </td>
        </tr>
        <tr>
            <td align="center">US03</td>
            <td>Filtrar rutinas por tipo</td>
            <td>Como cliente quiero filtrar las rutinas de ejercicio según su tipo para ejercitar solamente las partes del cuerpo que desee.</td>
            <td>Escenario 1: Búsqueda filtrada según tipo
            <br>Dado que me encuentro en la sección “Encontrar rutina” cuando selecciono el tipo de rutina que deseo y hago clic en el ícono de la lupa entonces el sistema muestra todas las rutinas que coincidan con lo especificado.
            <br><br>Escenario 2: Selección de una sola opción
            <br>Dado que me encuentro en la sección “Encontrar rutina” y una opción de tipo de rutina está seleccionada cuando hago clic en otra opción de tipo de rutina entonces el sistema mantiene seleccionada solamente  la última opción escogida.
            </td>
        </tr>
        <tr>
            <td align="center">US04</td>
            <td>Activar supervisión de rutina</td>
            <td>Como cliente quiero activar la supervisión de mis rutas de ejercicio en vivo para que la aplicación pueda verificar su correcta ejecución.</td>
            <td>Escenario 1: Supervisión activada
            <br>Dado que me encuentro en la vista de una rutina cuando la cámara está habilitada y selecciono la opción “Supervisar rutina en vivo” entonces el sistema me redirige a una nueva ventana donde se supervisa en vivo las posturas que realizo en mi rutina de ejercicios.
            <br><br>Escenario 2: Cámara inhabilitada
            <br>Dado que me encuentro en la vista de una rutina cuando la cámara está inhabilitada y selecciono la opción “Supervisar rutina en vivo” entonces el sistema muestra un mensaje pidiendo que se otorgue a la aplicación los permisos de cámara.
            <br><br>Escenario 3: Error en la ejecución de la rutina
            <br>Dado que encuentro en la ventana “Supervisión en vivo de rutina” cuando el sistema detecta una postura incorrecta durante la rutina entonces muestra en pantalla una alerta y la postura en la que el usuario se equivocó.
            </td>
        </tr>
        <tr>
            <td align="center">US05</td>
            <td>Agregar rutina a favoritos</td>
            <td>Como cliente quiero agregar una rutina a favoritos para posteriormente acceder rápidamente.</td>
            <td>Escenario 1: Rutina guardada en favoritos
            <br>Dado que me encuentro en la vista de una de las rutinas cuando seleccione el ícono corazón entonces el sistema guardará la rutina en mi lista de rutinas favoritas.
            <br><br>Escenario 2: Rutina eliminada de favoritos
            <br>Dado que me encuentro en la vista de una de las rutinas y el ícono de corazón está seleccionado cuando seleccione el ícono de corazón entonces el sistema elimina la rutina de mi lista de rutinas favoritas.
            </td>
        </tr>
        <tr>
            <td align="center">US06</td>
            <td>Visualizar rutinas favoritas</td>
            <td>Como cliente quiero visualizar mis rutinas favoritas para encontrar y acceder rápidamente a la rutina que desee.</td>
            <td>Escenario 1: Todas las rutinas favoritas
            <br>Dado que me encuentro en la página principal cuando seleccione la opción “Rutinas favoritas” entonces el sistema me redirige a dicha sección y muestra todas las rutinas guardadas como favoritas.
            <br><br>Escenario 2: No hay rutinas favoritas
            <br>Dado que me encuentro en la página principal cuando seleccione la opción “Rutinas favoritas” y no tenga ninguna rutina guardada como favorita en la aplicación entonces el sistema muestra el mensaje “No ha guardado ninguna rutina como favorita”.
            </td>
        </tr>
        <tr>
            <td align="center">US07</td>
            <td>Calificar rutina de ejercicio</td>
            <td>Como cliente quiero calificar una rutina de ejercicio para dar una valoración a dicha rutina.</td>
            <td>Escenario 1: Rutina calificada
            <br>Dado que me encuentro en la vista de una rutina de ejercicio cuando selecciono la cantidad de estrellas que considero que se merece la rutina entonces el sistema promedia y muestra la nueva calificación general de la rutina.
            <br><br>Escenario 2: Calificación cambiada
            <br>Dado que me encuentro en la vista de una rutina de ejercicio cuando selecciono una nueva cantidad de estrellas que considero que se merece la rutina entonces el sistema modificará mi calificación, promedia nuevamente y muestra la nueva calificación general de la rutina.
            </td>
        </tr>
        <tr>
            <td align="center">US08</td>
            <td>Visualizar un ejercicio</td>
            <td>Como cliente quiero visualizar un ejercicio en particular para estudiar los movimientos y secuencia de pasos.</td>
            <td>Escenario 1: Visualizar ejercicio
            <br>Dado que me encuentro en la vista de la rutina de ejercicios cuando hago clic en uno de los ejercicios de la rutina entonces el sistema me redirige a la vista del ejercicio seleccionado.
            <br><br>Escenario 2: Volver a la rutina de ejercicios
            <br>Dado que me encuentro en la vista de un ejercicio de una rutina cuando hago clic en el ícono con una flecha hacia la izquierda entonces el sistema me redirige a la rutina de ejercicios a la que pertenece el ejercicio.
            </td>
        </tr>
        <tr>
            <td align="center">US09</td>
            <td>Adquirir plan</td>
            <td>Como cliente quiero adquirir un plan para conseguir las funcionalidades premium de la aplicación.</td>
            <td>Escenario 1: Pasarela de pagos
            <br>Dado que me encuentro en la sección “Planes” cuando selecciono un plan entonces el sistema me redirige a la pasarela de pagos.
            <br><br>Escenario 2: Plan adquirido
            <br>Dado que me encuentro en la pasarela de pagos cuando ingreso el método de pago y complete correctamente los datos solicitados entonces el sistema indica que el pago se ha efectuado y cuento con plan escogido.
            <br><br>Escenario 3: Abandona pasarela de pagos
            <br>Dado que me encuentro en la pasarela de pagos cuando hago clic en el ícono con una flecha hacia la izquierda  entonces el sistema me redirige a la sección Planes.
            </td>
        </tr>
    </tbody>
</table>

## **3.3. Impact Mapping**

## **3.4. Product Backlog**

<table>
    <thead>
        <tr>
            <th>#Orden</th>
            <th>User Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Story Points (1/2/3/5/8)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">1</td>
            <td align="center">US01</td>
            <td>Buscar rutinas</td>
            <td>Como cliente quiero buscar rutinas de ejercicios para ejercitarte y mantenerte más saludable.</td>
            <td align="center">8</td>
        </tr>
        <tr>
            <td align="center">2</td>
            <td align="center">US04</td>
            <td>Activar supervisión de rutina</td>
            <td>Como cliente quiero activar la supervisión de mis rutas de ejercicio en vivo para que la aplicación pueda verificar su correcta ejecución.</td>
            <td align="center">8</td>
        </tr>
        <tr>
            <td align="center">3</td>
            <td align="center">US02</td>
            <td>Filtrar rutinas por duración</td>
            <td>Como cliente quiero filtrar rutinas de ejercicios según su duración para encontrar aquellas rutinas que se adecuen al tiempo que tengo disponible.</td>
            <td align="center">5</td>
        </tr>
        <tr>
            <td align="center">4</td>
            <td align="center">US03</td>
            <td>Filtrar rutinas por tipo</td>
            <td>Como cliente quiero filtrar las rutinas de ejercicio según su tipo para ejercitar solamente las partes del cuerpo que desee.</td>
            <td align="center">5</td>
        </tr>
        <tr>
            <td align="center">5</td>
            <td align="center">US08</td>
            <td>Visualizar un ejercicio</td>
            <td>Como cliente quiero visualizar un ejercicio en particular para estudiar los movimientos y secuencia de pasos.</td>
            <td align="center">5</td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">US09</td>
            <td>Adquirir plan</td>
            <td>Como cliente quiero adquirir un plan para conseguir las funcionalidades premium de la aplicación.</td>
            <td align="center">3</td>
        </tr>
        <tr>
            <td align="center">7</td>
            <td align="center">US05</td>
            <td>Agregar rutina a favoritos</td>
            <td>Como cliente quiero agregar una rutina a favoritos para posteriormente acceder rápidamente.</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td align="center">8</td>
            <td align="center">US06</td>
            <td>Visualizar rutinas favoritas</td>
            <td>Como cliente quiero visualizar mis rutinas favoritas para encontrar y acceder rápidamente a la rutina que desee.</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td align="center">9</td>
            <td align="center">US07</td>
            <td>Calificar rutina de ejercicio</td>
            <td>Como cliente quiero calificar una rutina de ejercicio para dar una valoración a dicha rutina.</td>
            <td align="center">2</td>
        </tr>
    </tbody>
</table>

# **Capítulo IV: Strategic-Level Software Design**
## **4.1. Strategic-Level Attribute-Driven Design**
### **4.1.1. Design Purpose**

### **4.1.2. Attribute-Driven Design Inputs**

#### **4.1.2.1. Primary Functionality (Primary User Stories)**

Las historias de usuario más relevantes de nuestra solución de software son buscar rutinas y activar la supervisión de rutina de ejercicios, dado que ambas historias de usuario representan el core del negocio de nuestra startup.


<table>
    <thead>
        <tr>
            <th>User Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Criterios de aceptación</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">US01</td>
            <td>Buscar rutinas</td>
            <td>Como cliente quiero buscar rutinas de ejercicios para ejercitarte y mantenerte más saludable</td>
            <td>Escenario 1: Búsqueda de rutinas
            <br>Dado que me encuentro en la sección “Encontrar rutinas” cuando hago clic en la barra de búsqueda, escribe el nombre de la rutina de deseo y hago clic en el ícono de la lupa entonces el sistema muestra todos las rutinas que coincidan con lo especificado.
            <br><br>Escenario 2: No se encontró ninguna rutina
            <br>Dado que me encuentro en la barra de búsqueda de la sección “Encontrar rutina” cuando introduzco el nombre de una rutina que no coincida con ninguna rutina alojada en la aplicación y hago clic en el ícono de la lupa entonces el sistema muestra el mensaje “No se encontró ninguna rutina”.</td>
        </tr>
        <tr>
            <td align="center">US04</td>
            <td>Activar supervisión de rutina</td>
            <td>Como cliente quiero activar la supervisión de mis rutas de ejercicio en vivo para que la aplicación pueda verificar su correcta ejecución.</td>
            <td>Escenario 1: Supervisión activada
            <br>Dado que me encuentro en la vista de una rutina cuando la cámara está habilitada y selecciono la opción “Supervisar rutina en vivo” entonces el sistema me redirige a una nueva ventana donde se supervisa en vivo las posturas que realizo en mi rutina de ejercicios.
            <br><br>Escenario 2: Cámara inhabilitada
            <br>Dado que me encuentro en la vista de una rutina cuando la cámara está inhabilitada y selecciono la opción “Supervisar rutina en vivo” entonces el sistema muestra un mensaje pidiendo que se otorgue a la aplicación los permisos de cámara.
            <br><br>Escenario 3: Error en la ejecución de la rutina
            <br>Dado que encuentro en la ventana “Supervisión en vivo de rutina” cuando el sistema detecta una postura incorrecta durante la rutina entonces muestra en pantalla una alerta y la postura en la que el usuario se equivocó.
            </td>
        </tr>
        <tr>
    </tbody>
</table>


#### **4.1.2.2. Quality attribute Scenarios**

#### **4.1.2.3. Constraints**

### **4.1.3. Architectural Drivers Backlog**

### **4.1.4. Architectural Design Decisions**

### **4.1.5. Quality Attribute Scenario Refinements**

## **4.2. Strategic-Level Domain-Driven Design**
### **4.2.1. EventStorming**

### **4.2.2. Candidate Context Discovery**

### **4.2.3. Domain Message Flows Modeling**

### **4.2.4. Bounded Context Canvases**

### **4.2.5. Context Mapping**

## **4.3. Software Architecture**
### **4.3.1. Software Architecture System Landscape Diagram**

### **4.3.1. Software Architecture Context Level Diagrams**

### **4.3.2. Software Architecture Container Level Diagrams**

### **4.3.3. Software Architecture Deployment Diagrams**