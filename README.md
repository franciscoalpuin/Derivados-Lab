# Derivados Lab

Herramienta interactiva y *offline* diseñada para el aprendizaje práctico de Derivados e Ingeniería Financiera. Desarrollada como material de apoyo y experimentación académica para estudios de posgrado (MBA).

Esta aplicación concentra la teoría de futuros y opciones en un entorno donde se puede experimentar con variables en tiempo real, comprender la procedencia de cada cálculo y validar los resultados contra casos de estudio prácticos.

## Características Principales

*   **Rutas de Aprendizaje:** Módulos progresivos que van desde la intuición básica hasta la valuación compleja de Futuros y Opciones.
*   **Laboratorio Guiado:** Un entorno interactivo para modificar parámetros (precio spot, tasa libre de riesgo, plazo, volatilidad) y visualizar al instante el impacto en el precio teórico y las curvas mediante gráficos dinámicos.
*   **Cálculos Nativos en el Navegador:** Utiliza [Pyodide](https://pyodide.org/) para compilar y ejecutar los scripts de Python directamente en el cliente.
*   **Validación Académica:** Un módulo dedicado ejecuta automáticamente casos de estudio contra el código actual, garantizando la consistencia de los modelos (Black-Scholes, árboles binomiales, etc.).
*   **100% Offline:** Todo el sistema está contenido en un único archivo HTML. Tras la descarga inicial del motor de Python en la caché del navegador, la herramienta puede utilizarse sin conexión a internet.
*   **Taller de Código:** Un espacio libre donde las cotizaciones y variables alimentan un editor integrado, permitiendo escribir y ejecutar código Python personalizado sobre la marcha.

## Uso

No requiere instalación, dependencias de servidor ni bases de datos.
1. Descargar el archivo `Derivados_Lab .html`.
2. Abrirlo en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).
3. La primera ejecución requerirá conexión a internet por unos segundos para descargar el motor de Python (aprox. 6 MB). Luego funcionará de manera local.
![Módulo de Volatilidad](https://raw.githubusercontent.com/franciscoalpuin/Derivados-Lab/main/Volatilidad.png)
## Tecnologías

*   **Frontend:** HTML5, CSS puro, JavaScript.
*   **Motor de Cálculo:** Python (mediante Pyodide WebAssembly).
*   **Licencia:** MIT.
![Captura de pantalla de Derivados Lab](https://raw.githubusercontent.com/franciscoalpuin/Derivados-Lab/main/Imagen%201)
<video src="https://github.com/franciscoalpuin/Derivados-Lab/raw/main/Video%20Project%202.mp4" width="100%" controls></video>
