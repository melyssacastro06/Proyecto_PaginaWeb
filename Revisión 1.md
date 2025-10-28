#  Proyecto FIS – Página Web del Centro de Cómputo UMT

## Descripción general

El proyecto consiste en el diseño y desarrollo de una página web informativa sobre el Centro de Cómputo de la UMT.  
Su propósito es mostrar información relevante como el personal responsable, los becarios, los horarios de los centros (CC1 y CC2), el reglamento y los servicios que ofrece.

---

##  Objetivo

Desarrollar una página web informativa, funcional y accesible que proporcione a los usuarios especialmente a aquellos que son nuevos y aún no conocen el Centro de Cómputo información clara y actualizada sobre el personal responsable, los becarios, los horarios de los salones, el reglamento vigente de los salones de cómputo (CC1 y CC2) y los servicios disponibles. Además, busca facilitar a los estudiantes y al personal académico la consulta de información relevante y promover el uso adecuado de las instalaciones y servicios del Centro de Cómputo de la UMT.

---

##  Requisitos funcionales

| ID | Requisito funcional | Descripción | Prioridad | Fecha de reunión |
|----|----------------------|--------------|------------|------------------|
| RF-01 | Visualización de personal | Mostrar catálogo con fotos y nombres del personal responsable y becarios. | Alta | 17 sept |
| RF-02 | Consulta de horarios | Permitir consultar los horarios de los salones CC1 y CC2. | Alta | 17 sept |
| RF-03 | Visualización del reglamento | Mostrar el reglamento del centro de cómputo. | Alta | 17 sept |
| RF-04 | Visualización de servicios | Mostrar servicios disponibles (computadoras, impresiones, etc.). | Alta | 17 sept |
| RF-05 | Datos de contacto | Incluir correos y medios de contacto en el pie de página. | Media | 17 sept |
| RF-06 | Menú de navegación | Permitir navegación fluida entre secciones. | Alta | 17 sept |
| RF-07 | Descarga de documentos | Permitir la descarga de reglamentos y horarios en PDF. | Alta | 22 sept |
| RF-08 | Impresión de documentos | Ofrecer opción de imprimir documentos desde la web. | Media | 22 sept |
| RF-09 | Control de zoom y vista | Incluir herramientas de zoom, desplazamiento y vista previa. | Media | 22 sept |
| RF-10 | Actualización de información | Mantener la información actualizada periódicamente. | Alta | 22 sept |
| RF-11 | Accesibilidad y compatibilidad | Compatibilidad con navegadores y dispositivos. | Alta | 22 sept |

---

##  Requisitos no funcionales

- **Rendimiento:** Debemos de tratar de garantizar un uso cómodo en nuestra página web, que permite navegar de una forma que la página no esté lenta y no tenga problemas al albergar a una cantidad considerable de gente.
- **Seguridad:** en términos de seguridad podríamos usar diferentes métodos de encriptación para poder mantener una mejor seguridad dentro de la página web, para así tener una mejor resistencia ante posibles ataques que puedan darse hacía la página, así mismo, crear copias de seguridad de las versiones que hagamos para ir llevando un seguimiento en cuanto a los cambios que se realicen y que puedan ir afectando durante su desarrollo y por último el uso de HTTPS (certificado SSL).
- **Mantenibilidad:** a la hora de realizar nuestra página web, debemos de procurar de mantener un orden en cuanto al desarrollo de la página, por ello realizaríamos un código fuente claro y documentado para poder tener en orden la creación de este mismo, así mismo el uso de frameworks sobre páginas web nos sería de mucha utilidad.
- **Compatibilidad:** Nuestra web debe de tener una compatibilidad con diferentes navegadores para así poder tener un campo amplio y mayor accesibilidad a la hora de ser consultada y también con las nuevas versiones que vayan saliendo de estas para así ahorrar un proceso de retocar código o de rehacerlo.
- **Portabilidad:** Nuestra web debe de tener en cuenta el dispositivo y sistema operativo en el que se esté ejecutando ya que así podemos mantener esa forma de uso cómoda y eficiente con el que procuramos que cuente.


---

##  Metodología – SCRUM

Se utiliza la metodología **ágil Scrum**, por su enfoque iterativo y colaborativo.

### Roles del equipo
- **Product Owner:** Melyssa Castro  
- **Scrum Master:** Paola Cámara (Tester)  
- **Equipo de desarrollo:** Julio Chan, Melyssa Castro, Lizeth Canché, José Antonio y Nalleli Polanco.

### Etapas del trabajo
1. **Sprint Planning:** definición de objetivos y tareas.  
2. **Desarrollo:** trabajo en las funcionalidades y diseño.  
3. **Daily Scrum:** reuniones breves de seguimiento.  
4. **Sprint Review:** presentación de avances.  
5. **Retrospectiva:** revisión de aciertos y mejoras.

**Beneficios:**
- Organización y orden en el trabajo.
- Comunicación constante.
- Flexibilidad ante cambios.
- Producto de mayor calidad.

---

##  Casos de uso principales



---

##  Herramientas utilizadas

| Propósito | Herramienta |
|------------|-------------|
| Comunicación | WhatsApp |
| Diseño del prototipo | Figma |
| Repositorio | GitHub |
| Editor de código | Visual Studio Code |

---

##  Diagrama de Gantt 

| Sprint / Etapa | Actividad | Fechas | Responsable(s) | Estado |
|-----------------|------------|---------|----------------|--------|
| **Sprint 0 – Planificación y requisitos** | Reunión inicial de planificación del proyecto | 15 de septiembre | Melyssa (Líder) | Realizado |
| | Reunión para definir requisitos funcionales | 17 de septiembre | Todo el equipo | Realizado |
| | Reunión para validar y ampliar requisitos | 22 de septiembre | Todo el equipo | Realizado |
| | Asignación de roles Scrum (PO, SM, Dev Team) | 22 de septiembre | Melyssa | Realizado |
| **Sprint 1 – Diseño del prototipo y estructura** | Diseño del prototipo en Figma | 23 sept – 1 oct | Lizeth (Diseñadora) | Terminado |
| | Revisión del diseño (Sprint Review) | 2 oct | Todo el equipo | Realizado |
| | Ajustes visuales y retroalimentación | 3 – 6 oct | Lizeth / Melyssa | Realizado |
| **Sprint 2 – Desarrollo inicial de la página** | Programación del menú y navegación | 7 – 12 oct | Julio / Melyssa | Hecho |
| | Sección “Personal y becarios” | 13 – 17 oct | Julio | Hecho |
| | Sección “Horarios” y “Reglamento” | 18 – 22 oct | Melyssa | Hecho |
| | Revisión de avance (Sprint Review) | 23 oct | Todo el equipo | Realizado |
| | Correcciones y ajustes funcionales | 24 – 27 oct | QA (Nalleli) / Tester (Paola) | En proceso |
| **Sprint 3 – Funcionalidades y pruebas** | Implementar descargas e impresión de documentos | 28 oct – 2 nov | Julio | Pendiente |
| | Agregar controles de zoom y vista | 3 – 6 nov | Melyssa | Pendiente |
| | Pruebas de compatibilidad y accesibilidad | 7 – 9 nov | Paola (Tester) / Nalleli (QA) | Pendiente |
| | Revisión del Sprint y retroalimentación | 10 nov | Todo el equipo | Pendiente |
| **Sprint 4 – Ajustes finales y documentación** | Revisión general del código y contenido | 11 – 15 nov | Melyssa / Julio | Pendiente |
| | Elaboración de documentación técnica | 16 – 20 nov | José Antonio (Documentador) | Pendiente |
| | Pruebas finales y control de calidad | 21 – 23 nov | Paola / Nalleli | Pendiente |
| | **Entrega final del proyecto** | **25 nov** | **Todo el equipo** | **Pendiente** |


## Hitos del proyecto:
Finalización del Sprint 0 – Planificación y requisitos
Fecha: 22 de septiembre
Descripción: Roles definidos, requisitos funcionales consolidados y aprobados.
Finalización del Sprint 1 – Diseño del prototipo
Fecha: 6 de octubre
Descripción: Prototipo inicial en Figma terminado y revisado.
Finalización del Sprint 2 – Desarrollo inicial de la página
Fecha: 27 de octubre
Descripción: Secciones implementadas: menú, navegación, “Personal y becarios”, “Horarios” y “Reglamento”; revisión de avance y ajustes funcionales.
Finalización del Sprint 3 – Funcionalidades y pruebas
Fecha: 10 de noviembre
Descripción: Funcionalidades implementadas (descargas, impresión, controles de vista), pruebas de compatibilidad y accesibilidad realizadas, revisión del sprint.
Finalización del Sprint 4 – Ajustes finales y documentación
Fecha: 25 de noviembre
Descripción: Código y contenido revisados, documentación técnica elaborada, pruebas finales completadas y entrega final del proyecto.

---

## 👩‍💻 Roles del equipo

### Líder del proyecto – *Melyssa Castro*
- Coordinación general del equipo y del proyecto
- Gestión del cronograma y seguimiento de avances
- Toma de decisiones estratégicas
-	Resolución de conflictos y problemas
-	Asegurar el cumplimiento de objetivos y fechas de entrega	


### Diseñadora – *Lizeth Canché*
- Creación del diseño visual y la experiencia de usuario
-	Selección de paleta de colores, tipografía y elementos visuales
-	Asegurar la consistencia visual en todo el proyecto
-	Colaboración con el equipo de programación para implementar diseños	

### Programadores – *Melyssa Castro y Julio Chan*
- Desarrollo front-end y back-end 
-	Implementación de funcionalidades requeridas
-	Optimización del rendimiento del sitio web
-	Colaboración con el diseñador para implementar los diseños
-	Resolución de problemas técnicos
-	Mantenimiento del código fuente y documentación técnicas 	


### Documentador – *José Antonio*
- Elaboración de documentación técnica
-	Mantenimiento de registros de reuniones y acuerdos
-	Organización de la documentación del proyecto
Gestión de versiones de documentación


### Tester – *Paola Cámara*
- Pruebas de funcionalidad y usabilidad
-	Identificación y reporte de bugs o errores
-	Verificación de que el producto cumple con los requisitos
-	Pruebas de compatibilidad en diferentes navegadores
-	Validación de la experiencia de usuario


### QA – *Nalleli Janet Polanco*
-	Pruebas de funcionalidad
-	Supervisión de la calidad del producto
	Verificación de la funcionalidad de los requisitos


---

##  Bitácoras

**Bitácora 1 (15 sept)**  
Fecha de reunión: 15 de septiembre
Actividades realizadas: Reunión inicial de planificación del proyecto. Se definieron los objetivos generales y el alcance del proyecto.
Revisado / Conclusiones: Se establecieron las bases del proyecto y se asignaron responsabilidades iniciales; se acordó comenzar a trabajar en la recopilación de requisitos funcionales.

**Bitácora 2 (17 sept)**  
Fecha de reunión: 17 de septiembre
Actividades realizadas: Reunión para definir requisitos funcionales. Cada integrante aportó ideas y necesidades para el prototipo de la página.
Revisado / Conclusiones: Se logró un listado preliminar de requisitos funcionales que servirán como guía para el diseño inicial del prototipo.

**Bitácora 3 (22 sept)**  
Fecha de reunión: 22 de septiembre
Actividades realizadas: Reunión para validar y ampliar los requisitos. Se revisaron los puntos que faltaban y se ajustaron detalles según la viabilidad.
Revisado / Conclusiones: Se consolidaron los requisitos funcionales finales y se asignaron roles Scrum (Product Owner, Scrum Master, Dev Team).

**Bitácora 4 (2 oct)**  
Fecha de reunión: 2 de octubre
Actividades realizadas: Revisión del diseño (Sprint Review). Se presentó el prototipo inicial realizado en Figma.
Revisado / Conclusiones: Se analizaron aspectos visuales y de navegación; se recopilaron sugerencias y se planificaron ajustes visuales.

**Bitácora 5 (23 oct)**  
Fecha de reunión: 23 de octubre
Actividades realizadas: Revisión de avance de la programación (Sprint Review). Se revisaron secciones ya implementadas: menú, navegación y secciones “Personal y becarios”, “Horarios” y “Reglamento”.
Revisado / Conclusiones: Se validó que las secciones funcionan correctamente; se identificaron ajustes y correcciones pendientes.

**Bitácora 6 (27 oct)**  
Fecha de reunión: 27 de octubre
Actividades realizadas: Inicio de correcciones y ajustes funcionales. QA y tester revisan funcionalidades implementadas.
Revisado / Conclusiones: Se detectaron errores menores y se asignaron tareas de corrección; se planifica avanzar con funcionalidades nuevas en el próximo sprint.

---

##  Prototipo


