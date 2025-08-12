# Gobierno de Datos – Suite Frontend

## Descripción

Esta es una suite de frontend para la Gobernanza de Datos, desarrollada como una aplicación de una sola página (SPA). Proporciona una interfaz de usuario interactiva para gestionar diversas tareas y artefactos de gobierno de datos. La aplicación está construida con HTML, CSS y JavaScript vainilla, utilizando Bootstrap 5 para el diseño y los componentes de la interfaz de usuario. Todos los datos se persisten localmente en el navegador utilizando `localStorage`, lo que la hace completamente funcional sin necesidad de un backend.

## Características

La suite incluye los siguientes módulos funcionales:

*   **Business Glossary:** Permite definir y gestionar un glosario de términos de negocio, incluyendo dominios, dueños, sensibilidad y estado. Soporta búsqueda, filtrado, creación, edición, eliminación e importación/exportación (CSV/JSON) de términos.
*   **Data Catalog:** Un catálogo de los activos de datos (datasets). Permite buscar y filtrar datasets por dominio, sensibilidad y tipo. Muestra detalles de cada dataset, incluyendo sus columnas, métricas de calidad y un mini-gráfico de linaje.
*   **Data Lineage:** Un visualizador de linaje de datos que muestra el flujo de datos entre diferentes sistemas o procesos.
*   **Quality Dashboard:** Un panel de control para monitorizar la calidad de los datos. Muestra KPIs clave (número de reglas, porcentaje de aprobación, incidencias abiertas) y una tabla de reglas de calidad de datos con sus resultados.
*   **Reglas Builder:** Una herramienta para construir reglas de calidad de datos en formato JSON.
*   **Políticas & Estándares:** Un módulo para documentar y consultar políticas y estándares de datos de la organización.
*   **Matriz RACI:** Permite definir y visualizar una matriz de responsabilidades (Responsible, Accountable, Consulted, Informed) para diferentes procesos y artefactos de datos.
*   **Acceso a Datos:** Un sistema para gestionar solicitudes de acceso a recursos de datos.
*   **DPIA (Evaluación de Impacto de Protección de Datos):** Un formulario interactivo para realizar evaluaciones de impacto relativas a la privacidad de los datos y calcular un puntaje de riesgo.
*   **Retención & Disposición:** Gestiona políticas de retención de datos, mostrando las próximas acciones de disposición en una tabla y un calendario.
*   **Incidencias (Kanban):** Un tablero Kanban para gestionar incidencias de datos, permitiendo moverlas entre los estados "Backlog", "En Progreso" y "Hecho" mediante arrastrar y soltar.
*   **Data Contracts:** Un constructor y validador para "Data Contracts" en formato JSON.
*   **Mapa de Dominios:** Visualiza los productos de datos organizados por dominio.
*   **Entrenamiento & Certificación:** Un módulo de formación con cursos y un quiz para certificar a los usuarios.
*   **Data Sharing:** Gestiona y muestra acuerdos de compartición de datos.

## Cómo Utilizar

Simplemente abre el archivo `index.html` en cualquier navegador web moderno (como Chrome, Firefox, Safari o Edge). No se requiere instalación ni servidor web.

## Tecnologías Utilizadas

*   **HTML5**
*   **CSS3**
*   **JavaScript (ES6+)**
*   **Bootstrap 5:** Para el framework de UI.
*   **Bootstrap Icons:** Para la iconografía.

## Almacenamiento de Datos

La aplicación utiliza la API de `localStorage` del navegador para almacenar todos los datos. Esto significa que los datos que ingreses persistirán en tu navegador entre sesiones. Si limpias los datos de tu navegador para este sitio, se restablecerán los datos de ejemplo iniciales.
