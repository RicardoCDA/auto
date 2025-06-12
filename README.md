# Instituto Tecnológico / Universidad  
**Carrera:** Ingeniería en Redes Inteligentes y Ciberseguridad  
**Materia:** Automatización de Infraestructura Digital  
**Unidad:** I  
**Actividad:** Actividad 1 – Archivo README  
**Estudiante:** Ricardo  
**Fecha:** [Agrega la fecha aquí]  

---

# README - Automatización de Infraestructura Digital

## Introducción

Este informe tiene como finalidad documentar el procedimiento realizado para la instalación, configuración y validación de un entorno de desarrollo destinado a la automatización de redes en el contexto de la materia de Automatización de Infraestructura Digital. A lo largo del desarrollo se describen las herramientas utilizadas, entre las que destacan Docker Engine, Docker Compose y Swagger, fundamentales para la gestión de contenedores y documentación de APIs.

Además, se detallan las fases técnicas para la instalación de software complementario como Visual Studio Code, sus extensiones, y Git como sistema de control de versiones. Se incluyen capturas o descripciones de las evidencias de instalación y funcionamiento, con pruebas como la ejecución de la imagen "hello-world" y un archivo `.yml` de ejemplo. Finalmente, se presenta un anexo con recursos utilizados provenientes de la comunidad técnica, foros y documentación oficial que guiaron el proceso.

---

## Desarrollo

### Herramientas utilizadas para automatización

1. **Docker Engine**: Plataforma de contenedores que permite crear, desplegar y ejecutar aplicaciones en entornos aislados.
2. **Docker Compose**: Herramienta para definir y correr aplicaciones multi-contenedor mediante archivos YAML.
3. **Swagger (OpenAPI)**: Herramienta para documentar y probar APIs REST mediante una interfaz interactiva.

---

### Procedimiento de instalación

- **Visual Studio Code**:
  - Descarga desde el sitio oficial.
  - Instalación del plugin "Docker Extension" y "YAML".

- **Docker**:
  - Instalación desde el sitio oficial.
  - Configuración de Docker Desktop (Windows/macOS) o Docker Engine (Linux).

- **Git**:
  - Instalación desde [https://git-scm.com/](https://git-scm.com/)
  - Configuración inicial con `git config --global user.name` y `git config --global user.email`.

---

### Evidencia de pruebas de verificación de funcionamiento

- **Ejecución de imagen `hello-world`**:
  - Comando: `docker run hello-world`
  - Resultado esperado: mensaje confirmando el correcto funcionamiento de Docker.

- **Ejecución de archivo `.yml`**:
  - Se utilizó un `docker-compose.yml` de ejemplo con Nginx.
  - Comando: `docker-compose up -d`
  - Resultado esperado: despliegue correcto del contenedor y acceso a servicio en localhost.

---

## Conclusión

Durante la realización de esta actividad, se logró implementar un entorno de desarrollo completo para la automatización de redes utilizando tecnologías modernas. Aprendí a instalar y configurar Docker, Compose y Swagger, además de integrar herramientas de desarrollo como VSCode y Git.

Uno de los logros más importantes fue comprobar que el entorno funciona correctamente mediante la ejecución de contenedores. La experiencia permitió reforzar habilidades técnicas esenciales para la gestión de infraestructura digital. También se destacó el valor de la documentación oficial y foros comunitarios como recursos clave para la resolución de problemas durante el proceso.

---

## Bibliografía

- Docker, Inc. (2024). *Get Docker*. https://docs.docker.com/get-docker/  
- Docker, Inc. (2024). *Docker Compose Overview*. https://docs.docker.com/compose/  
- OpenAPI Initiative. (2024). *Swagger Tools*. https://swagger.io/tools/  
- Microsoft. (2024). *Visual Studio Code Documentation*. https://code.visualstudio.com/docs  
- Git SCM. (2024). *Git - Documentation*. https://git-scm.com/doc  
