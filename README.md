# ForoHub_Challenge

&#x20; &#x20;

## Índice

1. [Descripción del proyecto](#descripción-del-proyecto)
2. [Estado del proyecto](#estado-del-proyecto)
3. [Tecnologías usadas](#tecnologías-usadas)
4. [Instalación y configuración](#instalación-y-configuración)
5. [Autor](#autor)

---
## Descripción del proyecto
Este proyecto consiste en una aplicación de foro para crear consultas con respecto a los cursos disponibles, registrando usuarios que puedan acceder a todas estas opciones por medio de un token como método de seguridad

# Opciones del proyecto:
- Registrar usuarios con todos sus atributos.
- Iniciar sesión con usuario creado para generar un token.
- CRUD usuario:
  Listar usuarios, Actualizar usuario, Buscar usuario, Eliminar usuario.
- CRUD curso:
  Listar cursos, Actualizar curso, Buscar curso, Eliminar curso.
- CRUD consulta:
  -Listar consultas, Actualizar consulta, Buscar consulta, Eliminar consulta.
  
---
## Estado del proyecto
Actualmente, el proyecto se encuentra concluido, pero podría haber algún tipo de modificación en el futuro.

---
## Tecnologías usadas

- **Lenguaje:** Java 17 en adelante.
-  Spring Boot version 3 en adelante.
- **Gestor de dependencias:** Maven version 4 en adelante.
- **Base de datos:** MySQL version 8 en adelante.
-  IDE Intellij IDEA.
- **Dependencias:**
  - Lombok
  - Spring Web
  - Jackson
  - Spring Boot Dev Tools
  - String Data JPA
  - Flyway Migration
  - MySQL Driver
  - Validation
  - Spring Security
  
---
## Instalación y configuración

### Prerrequisitos

- JDK 17 instalado.
- IntellijIDEA instalado (Recomendado)
- MySQL instalado
- Insomnia instalado (opcional)

### Pasos
(Aquí faltan los datos de instalacion de intelliJ, creación con springboot, my sql e insomnia)
1. Clonar este repositorio o descargar el archivo:

   ```bash
   https://github.com/Paulitx/LiterAlura.git
   ```
()
2. Configurar la base de datos MySQL:

   - Crear una base de datos.
   - Actualizar las credenciales en el archivo `application.properties` o `application.yml`:
     properties
     spring.datasource.url=jdbc:/localhost:####/nombre_base_datos
     spring.datasource.username=tu_usuario
     spring.datasource.password=tu_contraseña
     

## Autor

**Paula Vargas**

&#x20;
