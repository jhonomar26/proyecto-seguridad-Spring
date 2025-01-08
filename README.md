# Proyecto de Seguridad con Spring y Hibernate

> Aplicación web que implementa autenticación y autorización de usuarios con Spring Security y Hibernate. Incluye codificación segura de contraseñas con BCrypt.

## Tabla de Contenidos
1. [Descripción](#descripción)
2. [Instalación](#instalación)
3. [Uso](#uso)
4. [Contribución](#contribución)
5. [Licencia](#licencia)

## Descripción

Este proyecto es una aplicación web que utiliza **Spring Security** y **Hibernate** para gestionar usuarios y roles. Implementa autenticación y autorización, codificación segura de contraseñas usando **BCrypt**, y define reglas de acceso a rutas basadas en roles como **ADMIN** y **USER**.

El objetivo es proporcionar un sistema sencillo para gestionar usuarios con roles diferentes, permitiendo el acceso restringido a ciertas rutas en función de los privilegios.

### Características
- Autenticación de usuarios con **Spring Security**.
- Roles y permisos configurados para rutas específicas.
- Codificación de contraseñas usando **BCrypt** para mayor seguridad.
- Acceso a rutas protegidas según el rol del usuario.

---

## Instalación

### Requisitos previos

Antes de comenzar, asegúrate de tener los siguientes programas instalados:

- **Java** (versión 11 o superior): [Descargar Java](https://www.java.com/es/download/)
- **Maven** o **Gradle**: Utilizados como herramientas de construcción.
  - [Instalar Maven](https://maven.apache.org/install.html)
  - [Instalar Gradle](https://gradle.org/install/)

### Pasos para instalar

1. **Clona el repositorio**:

   Abre tu terminal y ejecuta el siguiente comando para clonar el repositorio:

   ```bash
   git clone https://github.com/tu_usuario/proyecto-seguridad.git
2. **Acceder al directorio del proyecto**:

   ```bash
   cd proyecto-seguridad
3. **Compilar el pr**:

Si estás usando Maven:
  
  mvn clean install
## Contribución

¡Contribuye al proyecto! Si deseas hacer mejoras o correcciones, sigue estos pasos:

1. Haz un **fork** del repositorio.
2. Crea una nueva rama para tu funcionalidad:

   ```bash
   git checkout -b feature-nueva
## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## Tecnologías Utilizadas

- **Spring Boot**: Framework para construir aplicaciones web.
- **Spring Security**: Para gestionar la autenticación y autorización de usuarios.
- **Hibernate**: ORM utilizado para interactuar con la base de datos.
- **BCrypt**: Algoritmo para la codificación segura de contraseñas.
- **Maven** o **Gradle**: Herramientas de construcción y gestión de dependencias.

