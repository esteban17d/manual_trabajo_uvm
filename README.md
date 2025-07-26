# Manual de Buenas Prácticas para el Trabajo en Grupo Universitario

[![Estado del Proyecto](https://img.shields.io/badge/estado-finalizado-green)](./) 
[![Licencia](https://img.shields.io/badge/licencia-MIT-blue.svg)](LICENSE)

Repositorio oficial del "Manual de Buenas Prácticas para el Trabajo en Grupo". Este proyecto fue desarrollado como un ejercicio práctico para aplicar metodologías de colaboración y control de versiones con Git y GitHub en un proyecto de documentación.

---

## 🎯 Descripción del Proyecto

Este proyecto tiene un doble objetivo:

1.  **Crear un Recurso Práctico:** Desarrollar un manual completo y fácil de seguir para que los estudiantes universitarios puedan mejorar su forma de trabajar en equipo, cubriendo desde la planificación inicial hasta la presentación final.
2.  **Aplicar Metodologías Profesionales:** Utilizar Git y GitHub para gestionar todo el ciclo de vida del documento, demostrando cómo el control de versiones, las ramas, los Pull Requests y la gestión de issues pueden aplicarse eficazmente fuera del desarrollo de software.

## ✨ Características Principales del Manual

El manual está estructurado para guiar al estudiante a través de todas las fases de un proyecto en equipo:

* **Capítulo 1: Planificación y Organización:** Estrategias para arrancar con buen pie, definir roles y establecer una comunicación efectiva.
* **Capítulo 2: Herramientas Colaborativas:** Una selección de las mejores herramientas para la gestión de tareas, escritura simultánea y manejo de bibliografía.
* **Capítulo 3: Normas de Citación (APA 7):** Una guía clara y con ejemplos para citar correctamente y evitar el plagio.
* **Capítulo 4: La Presentación Final:** Consejos prácticos para diseñar diapositivas impactantes y exponer en equipo con seguridad.

---

## 🚀 Cómo Usar este Manual

### Para Lectores

La forma más sencilla de leer el manual es descargar la versión final en formato PDF, que está lista para su visualización en cualquier dispositivo.

* Puedes encontrar el archivo **`manual_v1.0.pdf`** directamente en la raíz de este repositorio. ¡Descárgalo y empieza a mejorar tus trabajos en grupo!

### Para Colaboradores

Si deseas consultar el código fuente del manual, puedes encontrar todos los archivos de texto en formato Markdown dentro de la siguiente carpeta:
* `/documento/manual.md`

---

## 🤝 Cómo Contribuir

Aunque este proyecto está marcado como finalizado, las contribuciones para mejorarlo siempre son bienvenidas. Si encuentras un error, tienes una sugerencia o quieres añadir contenido nuevo, sigue este flujo de trabajo:

1.  **Crea un `Issue`:** Antes de nada, ve a la pestaña "Issues" de este repositorio y abre un nuevo issue para describir tu propuesta. Esto permite discutir los cambios antes de empezar a trabajar.

2.  **Clona el Repositorio:**
    ```bash
    git clone [https://github.com/esteban17d/manual_trabajo_uvm.git](https://github.com/esteban17d/manual_trabajo_uvm.git)
    cd manual_trabajo_uvm
    ```

3.  **Crea una Nueva Rama (`branch`):** Trabaja siempre en una rama nueva para mantener el historial limpio.
    ```bash
    # Usa un nombre descriptivo, ej: fix/corregir-error-apa
    git checkout -b feature/añadir-seccion-nueva
    ```

4.  **Realiza tus Cambios:** Edita los archivos necesarios dentro de la carpeta `/documento`.

5.  **Guarda tus Cambios (`commit`):** Usa un mensaje claro que explique qué hiciste.
    ```bash
    git add .
    git commit -m "feat: Añade nueva sección sobre gestión de conflictos"
    ```

6.  **Sube tus Cambios (`push`):**
    ```bash
    git push -u origin feature/añadir-seccion-nueva
    ```

7.  **Abre un Pull Request (PR):** En GitHub, crea un Pull Request desde tu rama hacia `main`. En la descripción, explica tus cambios y vincula el `Issue` que creaste.

## 📂 Estructura del Repositorio

```
.
├── /documento/
│   └── manual.md       # Archivo fuente del manual en Markdown
├── .gitignore          # Archivos y carpetas a ignorar por Git
├── CHANGELOG.md        # Registro de cambios por versión
├── LICENSE             # Licencia MIT del proyecto
├── README.md           # Este archivo
└── manual_v1.0.pdf     # Versión final del manual para el lector
```

## 👥 Autor

* **Esteban Elí Gómez González** - [@esteban17d](https://github.com/esteban17d)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
