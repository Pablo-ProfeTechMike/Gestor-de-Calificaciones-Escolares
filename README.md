# 🎓 Gestor de Calificaciones Escolares & Generador de Credenciales

Una aplicación web interactiva, responsiva y fácil de usar diseñada para calcular promedios escolares y generar credenciales/boletas oficiales personalizadas para estudiantes de todos los niveles educativos (**Primaria, Secundaria, Preparatoria y Universidad**).

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/Licencia-MIT-green?style=for-the-badge)

---

## 🚀 Características Principales

- 📚 **Soporte Multinivel Educativo:**
  - **Primaria:** Grados de 1.º a 6.º año (evaluación por Bloques).
  - **Secundaria:** Grados de 1.º a 3.º año (evaluación por Bloques).
  - **Preparatoria / Bachillerato:** Modalidad General o Carrera Técnica con selección de semestres o parciales.
  - **Universidad:** Especificación de Carrera Profesional y periodo (Semestral o Cuatrimestral).

- 🧮 **Cálculo Automático e Instantáneo de Promedios:**
  - Configuración flexible de la cantidad de materias y periodos (Parciales o Bloques).
  - Edición libre de nombres de materias y calificaciones en tiempo real.
  - Cálculo automático del promedio por materia y del **Promedio General Final**.

- 🆔 **Generación de Credenciales Escolares Estilo ID:**
  - Genera una tarjeta de credencial estilizada para cada alumno registrado.
  - Carga opcional de **Fotografía del Estudiante**.
  - Indicadores visuales de estado: **Verde** (Aprobado ≥ 6.0) y **Rojo** (Reprobado < 6.0).

- 🖨️ **Vista Previa de Impresión y Ajuste de Tamaño:**
  - Modal dinámico de configuración previo a la impresión.
  - Slider para ajustar la escala/tamaño de la credencial en milímetros o porcentaje.
  - Generación rápida de reportes en PDF o impresión física directa.

- 💾 **Persistencia de Datos (LocalStorage):**
  - Guarda automáticamente las credenciales generadas en el navegador para no perder información al recargar la página.
  - Gestión individual para eliminar credenciales creadas.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Estructura semántica de la aplicación.
- **Tailwind CSS (CDN):** Estilizado moderno, responsivo y modo oscuro.
- **JavaScript (ES6+):** Lógica del cálculo de promedios, renderizado dinámico del DOM y almacenamiento local.
- **FontAwesome / Lucide Icons:** Iconografía limpia e intuitiva.

---

## 💻 Instalación y Uso Local

No requiere ningún entorno de ejecución (*Node.js*, servidores, etc.) ni dependencias adicionales.

1. **Clona el repositorio:**
   ```bash
   git clone [https://github.com/Pablo-ProfeTechMike/Gestor-de-Calificaciones-Escolares.git](https://github.com/Pablo-ProfeTechMike/Gestor-de-Calificaciones-Escolares.git)
