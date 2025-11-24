# Proceso de Desarrollo del Proyecto del Centro de Cómputo

## Requisitos

### **Requisitos Funcionales**  
*(Reuniones del 15, 17 y 22 de septiembre)*

| ID | Requisito funcional | Descripción | Prioridad | Fecha |
|----|---------------------|-------------|-----------|--------|
| RF-01 | Visualización de personal | Mostrar un catálogo con fotos y nombres del personal responsable y becarios del Centro de Cómputo. | Alta | 17 sept |
| RF-02 | Consulta de horarios | Permitir consultar los horarios de atención de los salones de cómputo (CC1 y CC2). | Alta | 17 sept |
| RF-03 | Visualización del reglamento | Mostrar el reglamento del centro de cómputo. | Alta | 17 sept |
| RF-04 | Visualización de servicios | Mostrar los servicios disponibles como préstamos e impresiones. | Alta | 17 sept |
| RF-05 | Datos de contacto | Incluir correos y medios de contacto en el pie de página. | Media | 17 sept |
| RF-06 | Menú de navegación | Permitir navegación fluida entre secciones mediante un menú principal. | Alta | 17 sept |
| RF-07 | Descarga de documentos | Permitir la descarga de reglamentos, horarios y documentos en PDF. | Alta | 22 sept |
| RF-08 | Impresión de documentos | Ofrecer la opción de imprimir documentos desde la página. | Media | 22 sept |
| RF-09 | Control de vista | Incluir herramientas de desplazamiento y vista previa para documentos. | Media | 22 sept |
| RF-10 | Actualización de información | Garantizar actualización periódica del contenido. | Alta | 22 sept |
| RF-11 | Accesibilidad y compatibilidad | Asegurar compatibilidad con distintos navegadores y dispositivos. | Alta | 22 sept |

---

### **Requisitos No Funcionales**

**RNF-01 – Rendimiento**  
El sistema debe garantizar navegación fluida, tiempos de carga rápidos y estabilidad.

**RNF-02 – Mantenibilidad**  
El código debe estar organizado, documentado y estructurado para facilitar actualizaciones.

**RNF-03 – Compatibilidad**  
Debe funcionar en Chrome, Firefox, Edge y Safari.

**RNF-04 – Portabilidad**  
El sitio debe ser accesible desde computadoras, celulares y tablets.

---

## Diseño

### **Diseño del prototipo en Figma (23 sept – 1 oct)**  

**Link al prototipo:**  
https://www.figma.com/proto/HcdJdN4oPAIhU3Tz0NoASS/Untitled?node-id=0-1&t=4CTkS1A8oZVKuibk-1

---

## Construcción

- **Programación del menú y navegación (7–12 oct):**  
  Menú funcional para moverse entre las secciones del sitio.

- **Implementación de secciones principales:**  
  - Personal y becarios  
  - Horarios  
  - Reglamento  
  - Servicios  

- **Integración de documentos PDF:**  
  Los usuarios pueden visualizar reglamentos y horarios directamente en la página.

- **Diseño responsivo:**  
  Adaptado para computadora, tablet y celular.

---

## Pruebas

**Prueba 1: Pruebas de Navegación**
Objetivo: Confirmar que el menú y los enlaces internos funcionen correctamente y lleven a las secciones adecuadas.
Actividades realizadas:
•	Se probó cada opción del menú.
•	Se verificó que los botones redirigieran a su sección correspondiente.
•	Se revisó que no existieran enlaces rotos.
Resultado:
La navegación funcionó correctamente en todas las secciones. No se detectaron enlaces rotos y el desplazamiento entre páginas fue fluido.

**Prueba 2: Prueba de Visualización del Contenido**
Objetivo: Asegurar que la información (texto, imágenes, tablas y PDFs) se muestre correctamente.
Actividades realizadas:
•	Revisión de la correcta carga de imágenes de personal y becarios.
•	Comprobación del formato y alineación del texto.
•	Verificación de que los documentos PDF se visualizaran y descargaran sin problemas.
Resultado:
Las imágenes cargaron correctamente, los textos se mostraron legibles y bien distribuidos, y los PDF pudieron abrirse y descargarse sin errores.

**Prueba 3: Pruebas de Responsividad**
Objetivo: Validar que la página se adapte a distintos dispositivos (computadora, tablet y móvil).
Actividades realizadas:
•	Pruebas en diferentes resoluciones de pantalla.
•	Simulación de dispositivos móviles mediante herramientas del navegador.
•	Revisión del menú en versión móvil (hamburguesa).
•	Verificación de ajuste de imágenes y tamaños de texto.
Resultado:
El sitio se adaptó correctamente en todos los tamaños probados. El menú se convirtió adecuadamente en menú móvil. No se encontraron problemas de corte o desbordamiento de contenido.

**Prueba 4: Pruebas de Compatibilidad**
Objetivo: Comprobar que la página funcione correctamente en distintos navegadores.
Navegadores utilizados:
•	Google Chrome
•	Mozilla Firefox
•	Microsoft Edge
•	Safari (en simulación)
Actividades realizadas:
•	Carga completa de la página en cada navegador.
•	Revisión del diseño y estilos.
•	Prueba de descarga de documentos.
Resultado:
La página funcionó correctamente en todos los navegadores probados. Solo se notaron ligeras variaciones en fuentes en Firefox, pero no afectaron el funcionamiento.

**Prueba 5: Pruebas de Funcionalidades (Botones y PDFs)**
Objetivo: Validar que los botones principales respondan correctamente y que los documentos funcionen.
Actividades realizadas:
•	Prueba del botón de descarga del reglamento.
•	Prueba del botón de descarga de horarios.
•	Comprobación de enlaces externos.
•	Ensayo de botones de regresar o volver al inicio.
Resultado:
Todos los botones realizaron su función de manera correcta. Los documentos se descargaron sin errores y los enlaces funcionaron adecuadamente.

**Prueba 6: Pruebas de Rendimiento Básico**
Objetivo: Evaluar tiempos de carga y fluidez al navegar entre secciones.
Actividades realizadas:
•	Medición del tiempo de carga de la página principal.
•	Prueba de desplazamiento rápido entre secciones.
•	Revisión del tamaño y peso de imágenes.
Resultado:
El sitio cargó de manera rápida y sin retrasos. Las imágenes optimizadas ayudaron a mantener un buen rendimiento.

---

## Gestión

### **Costeo (COCOMO)**

| Tipo | Líneas |
|------|--------|
| HTML + JS | ~210 |
| CSS | ~310 |
| **Total LoC** | **≈ 520 líneas** |

**KLOC:** 0.52  
**Tipo de proyecto:** Orgánico  

### **Parámetros**

- a = 2.4  
- b = 1.05  
- c = 2.5  
- d = 0.38  

### **Resultados COCOMO**

Convertido a KLOC:
0.52 KLOC

Tipo de proyecto: Orgánico (simple, pequeño, estable)
Parámetros COCOMO Orgánico:
•	a = 2.4
•	b = 1.05
•	c = 2.5
•	d = 0.38

1. Esfuerzo (personas-mes)
Esfuerzo = a × (KLOC)^b
Esfuerzo = 2.4 × (0.52)^1.05
0.52^1.05 ≈ 0.515
Esfuerzo ≈ 2.4 × 0.515
Esfuerzo ≈ 1.23 personas-mes

3. Tiempo de desarrollo (meses)
Tiempo = c × (Esfuerzo)^d
Tiempo = 2.5 × (1.23)^0.38
1.23^0.38 ≈ 1.08
Tiempo ≈ 2.5 × 1.08
Tiempo ≈ 2.7 meses

5. Personal requerido
Personal = Esfuerzo / Tiempo
Personal = 1.23 / 2.7
≈ 0.45 personas

Conclusión:
Con una persona trabajando a medio tiempo se completa en 2–3 meses


---

### **Estimación del valor del proyecto (IA)**

Prompt: 
Quiero que actúes como un estimador profesional de proyectos de software. Te voy a describir mi proyecto para que tú calcules su valor total. Mi proyecto es un sitio web informativo para el Centro de Cómputo de la UMT, implementado con HTML, CSS y JavaScript, estructurado como una single-page donde un menú dinámico permite cargar el contenido sin cambiar de página. El sitio incluye las secciones de Personal y becarios (con tarjetas e imágenes), Horarios, Reglamento y Servicios, estas tres últimas mediante PDF incrustados. El diseño es completamente responsivo, adaptado para dispositivos móviles, con header y menús fijos, un footer con enlace externo, integración de documentos PDF, estilos personalizados en CSS y una navegación fluida manejada con JavaScript.
Respuesta: 
Después de analizar las características del sitio web informativo del Centro de Cómputo de la UMT —incluyendo la estructura en una sola página con menú dinámico, el diseño responsivo completo, la integración de documentos PDF, las tarjetas de personal con imágenes, los estilos personalizados en CSS y la navegación controlada por JavaScript— el costo estimado para un proyecto con este alcance, nivel de funcionalidad y calidad visual oscila entre $12,000 y $18,000 MXN.


---
## Roles humanos

- **Product Owner / Líder del Proyecto (Melyssa Castro)**  
  Encargada de coordinar actividades, organizar reuniones, dar seguimiento al avance y asegurar que se cumplan los objetivos del proyecto.

- **Desarrolladores (Melyssa y Julio)**  
  Implementan el código HTML, CSS y JavaScript, crean la estructura del sitio, diseñan la interfaz responsiva y añaden la navegación dinámica.

- **Diseñadora (Lizeth Canche)**  
  Realiza el prototipo en Figma, propone el diseño visual, la paleta de colores, la distribución de tarjetas, el menú y la estructura responsive.

- **Tester y QA (Paola y Janet)**  
  Ejecutan pruebas de funcionalidad, compatibilidad y responsividad; detectan errores y verifican que el sitio cumpla con los requisitos funcionales.

- **Documentador (José Mendoza)**  
  Elabora la documentación del proyecto, redacta bitácoras, requisitos, fases de desarrollo y evidencia de pruebas.

- **Scrum Master (Paola)**  
   Facilita el proceso de trabajo, supervisa el cumplimiento de los sprints, ayuda a resolver impedimentos y mantiene la comunicación fluida dentro del equipo.

---

## Herramientas utilizadas

- **Comunicación:** WhatsApp  
- **Diseño / Prototipo:** Figma  
- **Repositorio / Versionamiento:** GitHub  
- **Editor / Construcción de página:** Visual Studio Code

---

## Versionamiento
El proyecto utilizó GitHub como sistema de control de versiones.
Repositorio público en GitHub, donde se almacenó el código fuente, prototipos y avances del proyecto.

