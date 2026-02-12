# Dashboard de Gestión de Grupos

Este proyecto es una aplicación web diseñada para la gestión, visualización y seguimiento de grupos de clases. Permite administrar horarios, calcular pagos y visualizar estadísticas detalladas de cada grupo.

## 🚀 Características Principales

- **Dashboard Interactivo**: Visualización de grupos organizados por días y horas.
- **Gestión de Pagos**: Sistema de cálculo automático de honorarios basado en el tipo de grupo (Individual vs. Grupal).
- **Importación de Datos**: Soporte para cargar datos de grupos desde archivos JSON.
- **Estadísticas en Tiempo Real**: Panel de estadísticas que reemplaza formularios antiguos para ofrecer una visión clara del rendimiento y pagos.
- **Cálculo de Clases**: Lógica optimizada para determinar el número de clases mensuales considerando duraciones específicas (ej. cursos de 40 clases).

## 📁 Estructura del Proyecto

- `board_grupos.html`: Interfaz principal del tablero de grupos y estadísticas.
- `index.html`: Punto de entrada de la aplicación.
- `groups.json`: Archivo de datos fuente con la configuración de los grupos (días, horas, nombres, fechas finales).
- `groups copy.json`: Copia de respaldo/trabajo de los datos de los grupos.
- `datos_prueba.csv`: Datos de ejemplo para pruebas de importación.

## 🛠️ Tecnologías Utilizadas

- **HTML5/CSS3**: Estructura y diseño responsivo.
- **JavaScript (Vanilla)**: Lógica de la aplicación, cálculos y manipulación del DOM.
- **JSON**: Formato de almacenamiento de datos para los grupos.

## 📖 Cómo Empezar

1. Abre `index.html` o `board_grupos.html` en cualquier navegador web moderno.
2. Asegúrate de que los archivos `.json` estén en la misma carpeta para que la aplicación pueda cargar los datos correctamente.
3. Utiliza la función de importación si necesitas actualizar la lista de grupos desde un archivo externo.

---
*Desarrollado para optimizar el seguimiento académico y administrativo.*
