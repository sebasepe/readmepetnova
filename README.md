### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

<table>
  <tr>
    <th> Sprint # </th>
    <th> Sprint 2 </th>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Planning Background </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Date </td>
    <td> 27/04/2025 </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Time </td>
    <td> 19:00 horas (GMT-5) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Location </td>
    <td> Virtual (Google Meet) </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Prepared By </td>
    <td> Escobar Palomino, Sebastian Matias </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
    <td>
      Bastidas Bastidas, Diego Martin<br>
      Belahonia Miranda, Fabrisio<br>
      Choquehuanca Núñez, Luciana Carolina<br>
      Escobar Palomino, Sebastian Matias<br>
      Prado Vargas, Mario Benjamín
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Review Summary </td>
    <td> En Sprint 1, se completó con éxito la Landing Page de Pet Nova, incluyendo secciones como la barra de navegación, "Why Choose Us?", suscripciones, reseñas, formulario de contacto, videos y cambio de idioma. Todas las User Stories (US17 a US23) fueron implementadas y desplegadas en GitHub Pages. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 1 Retrospective Summary </td>
    <td> El equipo identificó que la comunicación en Google Meet fue efectiva, pero los mensajes de commit podrían ser más descriptivos. Se acordó mejorar la documentación de commits y realizar pruebas de usabilidad más exhaustivas en futuros sprints. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;" colspan="2"> Sprint Goal & User Stories </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 2 Goal </td>
    <td> Iniciar el desarrollo de la Web Application de Pet Nova, implementando funcionalidades clave como el registro e inicio de sesión de usuarios, la gestión de perfiles, el registro de mascotas y las notificaciones de citas, con un enfoque en una interfaz intuitiva, integración inicial con la base de datos MySQL, y pruebas de funcionalidad básica para garantizar una experiencia fluida para veterinarios y dueños de mascotas. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sprint 2 Velocity </td>
    <td> <strong>8</strong><br> El equipo mantiene una capacidad de 8 Story Points para este Sprint, consistente con Sprint 1, considerando la experiencia adquirida y la carga de trabajo estimada. </td>
  </tr>
  <tr>
    <td style="font-weight: bold;"> Sum of Story Points </td>
    <td> 8 </td>
  </tr>
</table>

#### 5.2.2.2. Aspect Leaders and Collaborators

| **Team Member (Last Name, First Name)**  | **GitHub Username** | **Capítulo I: Introducción (L/C)** | **Capítulo II: Requirements Elicitation & Analysis (L/C)** | **Capítulo III: Requirements Specification (L/C)** | **Capítulo IV: Product Design (L/C)** | **Capítulo V: Product Implementation, Validation & Deployment (L/C)** |
| ---------------------------------------- | ------------------- | ---------------------------------- | ---------------------------------------------------------- | -------------------------------------------------- | ------------------------------------- | --------------------------------------------------------------------- |
| **Belahonia Miranda, Fabrisio**          | devfab17            | L                                  | C                                                          | C                                                  | C                                     | C                                                                     |
| **Bastidas Bastidas, Diego Martin**      | ghostnotfound404    | C                                  | L                                                          | C                                                  | C                                     | C                                                                     |
| **Choquehuanca Núñez, Luciana Carolina** | lucianxaaa          | C                                  | C                                                          | L                                                  | C                                     | C                                                                     |
| **Prado Vargas, Mario Benjamín**         | mariopvdev          | C                                  | C                                                          | C                                                  | L                                     | C                                                                     |
| **Escobar Palomino, Sebastian Matias**   | sebasepe            | C                                  | C                                                          | C                                                  | C                                     | L                                                                     |

#### 5.2.2.3. Sprint Backlog 2

En el segundo sprint, el equipo se enfocó en iniciar el desarrollo de la Web Application de Pet Nova, implementando funcionalidades esenciales para la autenticación de usuarios, gestión de perfiles, registro de mascotas y notificaciones. Las tareas se asignaron según las habilidades de cada miembro.

| **ID**   | **Title**               | **ID**   | **Title**                 | **Description**                                                          | **Estimations(Hours)** | **Assigned To**                          | **Status(To-do/InProcess/ToReview/Done)** |
| -------- | ----------------------- | -------- | ------------------------- | ------------------------------------------------------------------------ | ---------------------- | ---------------------------------------- | ----------------------------------------- |
| **US01** | Registro de usuario     | **TS08** | Formulario de registro    | Crear formulario HTML/CSS con validación para nombre, email, contraseña. | 2                      | **Bastidas Bastidas, Diego Martin**      | To-do                                     |
| **US01** | Registro de usuario     | **TS09** | Backend de registro       | Implementar endpoint en backend para guardar usuarios en MySQL.          | 2                      | **Bastidas Bastidas, Diego Martin**      | To-do                                     |
| **US02** | Inicio de sesión        | **TS10** | Formulario de login       | Crear formulario de inicio de sesión con email y contraseña.             | 2                      | **Belahonia Miranda, Fabrisio**          | To-do                                     |
| **US02** | Inicio de sesión        | **TS11** | Autenticación backend     | Implementar endpoint para autenticar usuarios con JWT.                   | 2                      | **Belahonia Miranda, Fabrisio**          | To-do                                     |
| **US03** | Gestión de perfil       | **TS12** | Pantalla de perfil        | Desarrollar pantalla para mostrar/editar datos del usuario.              | 3                      | **Choquehuanca Núñez, Luciana Carolina** | To-do                                     |
| **US09** | Registro de mascotas    | **TS13** | Formulario de mascota     | Crear formulario para registrar nombre, edad, raza de la mascota.        | 3                      | **Escobar Palomino, Sebastian Matias**   | To-do                                     |
| **US09** | Registro de mascotas    | **TS14** | Backend de mascotas       | Implementar endpoint para guardar datos de mascotas en MySQL.            | 2                      | **Escobar Palomino, Sebastian Matias**   | To-do                                     |
| **US15** | Notificaciones de citas | **TS15** | Sistema de notificaciones | Implementar envío de notificaciones por email o en la app para citas.    | 3                      | **Prado Vargas, Mario Benjamín**         | To-do                                     |

#### 5.2.2.4. Development Evidence for Sprint Review

| Repositorio                                                                 | Rama     | Commit ID | Mensaje de Commit                        | Cuerpo del Mensaje                        | Fecha de Commit |
|-----------------------------------------------------------------------------|----------|-----------|------------------------------------------|-------------------------------------------|-----------------|
| https://github.com/1ASI0730-2510-4370-G4-PetNova/PetNova-Fronted | PetNova-LandingPage/main     | bb84e62   | ci: add RailWay Web Apps workflow file |                                           | 14/05/2025      |

#### 5.2.2.5. Execution Evidence for Sprint Review

En el Sprint 2 se inició el desarrollo de la Web Application de Pet Nova, implementando funcionalidades esenciales como el registro e inicio de sesión de usuarios, la gestión de perfiles, el registro de mascotas y las notificaciones de citas. Estas funcionalidades permiten a los usuarios (veterinarios y dueños de mascotas) interactuar con la plataforma de manera inicial, facilitando la autenticación y la gestión de datos básicos. A continuación, se muestran las evidencias.
**US02**
<div style="text-align: center;">
  <img src="https://i.imgur.com/JROcPpX.png[/img]" width="100%" />
</div>

**US02**
<div style="text-align: center;">
  <img src="https://i.imgur.com/xYaKBXy.png[/img]" width="100%" />
</div>

**US03**
<div style="text-align: center;">
  <img src="https://i.imgur.com/bEdNRPA.png[/img]" width="100%" />
</div>

**US03**
<div style="text-align: center;">
  <img src="https://i.imgur.com/3f8UYmL.png[/img]" width="100%" />
</div>

**US25**
<div style="text-align: center;">
  <img src="https://i.imgur.com/37XcGPQ.png[/img]" width="100%" />
</div>

**US04**
<div style="text-align: center;">
  <img src="https://i.imgur.com/HJzdYzD.png[/img]" width="100%" />
</div>

**US09**
<div style="text-align: center;">
  <img src="https://i.imgur.com/8HhZZ52.png[/img]" width="100%" />
</div>

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

En la entrega del segundo sprint, se completó la implementación de la landing page funcional, cumpliendo con las user stories correspondientes a este entregable. Además, se lanzó una versión preliminar de la aplicación web. Link del Web Aplication: [WEB APLICATION](https://petnova-fronted-production.up.railway.app)

**Capturas de pantalla landing page:**
<div style="text-align: center;">
  <img src="https://i.imgur.com/IRYz79z.png[/img]"  width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/zwxLecZ.png[/img]"  width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/ZV9nhgF.png[/img]"  width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/uo0xEiV.png[/img]"  width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/rDngf4T.png[/img]"  width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/RxzVkV7.png[/img]"  width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/Ybk9Cdu.png[/img]"  width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/AFZbka2.png[/img]"  width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/FjZQiU9.png[/img]"  width="100%" />
</div>

**Capturas de pantalla Web Application:**

<div style="text-align: center;">
  <img src="https://i.imgur.com/JROcPpX.png[/img]" width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/xYaKBXy.png[/img]" width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/bEdNRPA.png[/img]" width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/3f8UYmL.png[/img]" width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/37XcGPQ.png[/img]" width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/HJzdYzD.png[/img]" width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/8HhZZ52.png[/img]" width="100%" />
</div>

#### 5.2.2.8. Team Collaboration Insights during Sprint

Para el desarrollo de la Web Application en este sprint, se utilizaron herramientas clave como Visual Studio Code para la escritura de código, Git para el control de versiones, y GitHub para la gestión de ramas y pull requests. Las funcionalidades de la Web App, como el registro e inicio de sesión, gestión de perfiles, registro de mascotas y notificaciones, se dividieron en tareas específicas asignadas a cada miembro del equipo según sus habilidades. Un integrante se encargó de integrar las contribuciones individuales, asegurando la cohesión del producto final.

<div style="text-align: center;">
  <img src="https://i.imgur.com/jOq2ETh.png[/img]" width="100%" />
</div>

<div style="text-align: center;">
  <img src="https://i.imgur.com/N4wzfhc.png[/img]" width="100%" />
</div>

#### **Avance de Conclusiones**

- La colaboración efectiva entre los miembros del equipo fue clave para avanzar de manera organizada y cubrir todas las etapas del proyecto. Cada integrante asumió con claridad su rol y responsabilidades, facilitando una ejecución ordenada.

- La definición de User Stories y del Product Backlog permitió priorizar las funcionalidades esenciales, asegurando que el producto respondiera a las necesidades del mercado.

- Un diseño de arquitectura sólido y orientado a objetos favoreció la escalabilidad y el mantenimiento, minimizando riesgos en el despliegue.

- El uso de metodologías ágiles, como reuniones de sprint y retrospectivas, ayudó a ajustar prioridades y mejorar continuamente el flujo de trabajo.

- Finalmente, el enfoque en UI/UX permitió construir una plataforma intuitiva y atractiva para los usuarios finales.
  
- Progreso satisfactorio en la construcción de la Web Application: En el Sprint 2, el equipo logró iniciar el desarrollo de la Web Application de Pet Nova, implementando funcionalidades clave como el registro e inicio de sesión de usuarios, gestión de perfiles, registro de mascotas y notificaciones de citas. Esto permitió un avance significativo en la estructura de la aplicación, enfocándose en una interfaz intuitiva y la integración inicial con la base de datos MySQL.
  
- Mejoras en la planificación y seguimiento de tareas: Durante este sprint, se mantuvo la misma capacidad de trabajo de 8 Story Points que en el Sprint 1. La planificación y distribución de tareas se realizó de acuerdo con las habilidades de los miembros del equipo, lo que contribuyó a la eficiente asignación de responsabilidades y al progreso constante hacia el objetivo del sprint.
  
- Lecciones aprendidas sobre la documentación de commits: A partir de las retrospectivas del Sprint 1, se identificó la necesidad de mejorar la documentación de los commits. Este aspecto fue abordado en Sprint 2, ya que se tomaron medidas para que los mensajes de commit fueran más descriptivos y claros, lo que facilitó el seguimiento del progreso y la colaboración dentro del equipo.

- Desarrollo colaborativo y herramientas utilizadas: El equipo utilizó herramientas como Visual Studio Code, Git y GitHub para asegurar una colaboración fluida y el control adecuado de versiones. Estas herramientas permitieron la integración de tareas individuales de manera efectiva, lo que resultó en una versión preliminar funcional de la Web Application de Pet Nova, demostrando la importancia de las plataformas de colaboración y control de código en proyectos ágiles.

#### **Bibliografia**

- Sedano, L. (2024). _Manual para la gestión eficaz de clínicas veterinarias: Estrategias administrativas y organizativas_. Recuperado de [https://punto-medic.cl/blogs/manuales-y-guias/manual-para-la-gestion-eficaz-de-clinicas-veterinarias-estrategias-administrativas-y-organizativas](https://punto-medic.cl/blogs/manuales-y-guias/manual-para-la-gestion-eficaz-de-clinicas-veterinarias-estrategias-administrativas-y-organizativas)

- BioSystems S.A. (s.f.). _Guía de buenas prácticas en veterinaria_. Barcelona, España: ioSystems S.A. Recuperado de [https://covetrija.org/wp-content/uploads/2021/10/VET_GuiaBuenasPracticas_ESP.pdf](https://covetrija.org/wp-content/uploads/2021/10/VET_GuiaBuenasPracticas_ESP.pdf)

#### **Anexo**

1. Despliegue del Landing Page: https://1asi0730-2510-4370-g4-petnova.github.io/PetNova-Landing-Page/
2. Despliegue de la App Web: https://petnova-fronted-production.up.railway.app
3. Figma con los User Flow Diagrams, wireframes y mockups de la landing page.: https://www.figma.com/design/XjI2alaHmyFV0MPlaPpxzO/Web-design?node-id=401-8424&t=kuv2vsPlXaFzVYvk-0
4. Video De Exposición TB1: https://upcedupe-my.sharepoint.com/:f:/g/personal/u20221a301_upc_edu_pe/Eqi44YEDeiVKgGPNfaTVK6MBWYenSQeOT--MkZtImi2TbQ?e=86Pe27
