# foro-api
Repositorio de foro-api 
# Foro API - Proyecto Java Spring Boot

## Descripción

Este proyecto consiste en una **API REST de un foro**, desarrollada con **Java y Spring Boot**. La aplicación permite que los usuarios creen, listan y eliminen tópicos dentro de un foro, simulando la interacción básica de una comunidad en línea.  
La API está diseñada para ser **simple, ejecutable y fácilmente extendible**, ideal para presentar en GitHub y compartir con otros desarrolladores.

---

## Objetivos del proyecto

- Practicar el desarrollo de **APIs REST con Java y Spring Boot**.
- Implementar **CRUD básico** (crear, listar y eliminar tópicos).
- Familiarizarse con la integración de **Spring Data JPA** y **H2 en memoria**.
- Introducir conceptos básicos de **seguridad con Spring Security** (configuración inicial).
- Crear un proyecto **listo para ser publicado en GitHub**, con README y estructura organizada.

---

## Tecnologías utilizadas

- Java 17+
- Spring Boot 3.x
- Spring Data JPA
- Spring Security (configuración inicial)
- H2 Database (in-memory)
- Maven
- Insomnia o Postman (para pruebas HTTP)

---

## Estructura del proyecto
foro-api/
├─ src/
│  └─ main/
│     ├─ java/
│     │  └─ com/tuusuario/foro/
│     │     ├─ controller/        # Controladores que manejan los endpoints REST
│     │     │   └─ TopicoController.java
│     │     ├─ model/             # Modelos / entidades de la base de datos
│     │     │   └─ Topico.java
│     │     ├─ repository/        # Interfaces JPA para acceso a datos
│     │     │   └─ TopicoRepository.java
│     │     ├─ service/           # Lógica de negocio
│     │     │   └─ TopicoService.java
│     │     ├─ security/          # Configuración de seguridad (Spring Security)
│     │     │   └─ SecurityConfig.java
│     │     └─ ForoApiApplication.java  # Clase principal de Spring Boot
│     └─ resources/
│        ├─ application.properties  # Configuración de base de datos y Spring
│        └─ data.sql (opcional)    # Datos iniciales para pruebas
├─ .gitignore                     # Archivos a ignorar en Git
├─ pom.xml                        # Archivo de configuración de Maven
└─ README.md                      # Documentación del proyecto



