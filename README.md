# AulaConecta - Plataforma Web Educativa

## 1. Descripción del Proyecto
AulaConecta es una plataforma web desarrollada para facilitar la consulta de cursos, el registro de estudiantes e interesados, y la administración de contenidos educativos. Este repositorio alberga el código fuente correspondiente a la interfaz de usuario (*front-end*).

## 2. Problema que Resuelve y Objetivo del Front-End
* **Problema que resuelve:** Elimina el desorden organizativo, la pérdida de información y la sobreescritura accidental de código causados por la distribución manual de archivos, estableciendo un control de versiones centralizado y trazable.
* **Objetivo del front-end:** Proveer una experiencia de usuario fluida, intuitiva, accesible y responsiva para que aprendices y administradores interactúen con la oferta académica de forma rápida y segura.

## 3. Alcance Inicial
En esta primera fase se planea construir la estructura base para las siguientes secciones/módulos:
* **Página de Inicio (Home):** Presentación de la plataforma y destacados académicos.
* **Catálogo de Cursos:** Módulo interactivo con filtros para consultar la oferta educativa disponible.
* **Formulario de Registro/Contacto:** Captura de datos para personas interesadas.
* **Panel de Administración (Vista previa):** Interfaz para la gestión básica de contenidos.

## 4. Equipo y Roles
| Nombre / Aprendiz | Usuario de GitHub | Rol en el Proyecto |
| :--- | :--- | :--- |
| *Kevin Garay* | `@KhevinH` | Responsable del Repositorio / Responsable de Rama / Revisor / Auditor |

## 5. Ruta Tecnológica Prevista
El proyecto seguirá una evolución tecnológica escalonada:
1. **HTML5:** Estructura semántica de los documentos web.
2. **CSS3:** Estilos, diseño responsivo (*Flexbox/Grid*) y consistencia visual.
3. **JavaScript (ES6+):** Lógica del lado del cliente, manipulación del DOM y manejo de eventos.
4. **React:** Biblioteca basada en componentes reutilizables para la construcción modular del front-end en fases avanzadas.

## 6. Acuerdo de Trabajo (Flujo de Git)
* **Rama principal (`main`):** Protegida. Almacena únicamente versiones estables y aprobadas.
* **Uso de ramas:** Ningún cambio se realiza directamente sobre `main`. Todo trabajo se desarrolla en ramas descriptivas (ejemplo: `feature/readme-inicial`, `fix/login-form`).
* **Mensajes de Commit:** Deben ser claros y explícitos (ejemplo: `docs: agregar sección de alcance inicial al README`). Se rechazan mensajes genéricos como *"cambios"*, *"listo"* o *"prueba"*.
* **Flujo de Integración:** Se utiliza el modelo de Pull Request (PR) con revisión previa obligatoria antes de realizar la fusión (*merge*).

## 7. Criterios de Calidad para Contribuciones (Checklist de PR)
Antes de fusionar una rama hacia `main`, el aporte debe cumplir estrictamente con:
1. **Sin información sensible:** Garantizar la ausencia de contraseñas, *tokens*, credenciales, documentos o teléfonos en el código.
2. **Mensajes explicativos:** Commits con mensajes estructurados que justifiquen el *por qué* del cambio.
3. **Revisión y Aprobación:** Tener al menos una observación/comentario de mejora resuelto y aprobado en el Pull Request.
4. **Código Limpio:** Ausencia de archivos temporales, código comentado innecesario o duplicado.
5. **Aislamiento en Rama:** Verificación de que la funcionalidad se probó de forma aislada sin romper otras áreas del proyecto.

## 8. Fuentes Consultadas
* *Git Documentation:* [https://git-scm.com/doc](https://git-scm.com/doc)
* *GitHub Docs - About Pull Requests:* [https://docs.github.com/en/pull-requests](https://docs.github.com/en/pull-requests)
