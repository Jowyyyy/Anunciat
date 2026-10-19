# # Anunciat — Plataforma de anuncios

<p align="center">
  <strong>Una plataforma web para publicar, explorar y guardar anuncios favoritos.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

## 📌 Descripción

**Anunciat** es una plataforma web de anuncios clasificados desarrollada como proyecto académico de Desarrollo de Aplicaciones Web (DAW).

La aplicación permite gestionar anuncios mediante diferentes roles de usuario, diferenciando entre quienes desean publicar productos y quienes quieren consultar anuncios y guardarlos en favoritos.

El proyecto está desarrollado con PHP, MySQL, HTML, CSS y JavaScript, y actualmente se encuentra en fase de mejora para incorporarlo a mi portfolio profesional.

## 📑 Tabla de contenidos

- [Descripción](#-descripción)
- [Roles de usuario](#-roles-de-usuario)
- [Funcionalidades](#-funcionalidades)
- [Tecnologías](#-tecnologías)
- [Capturas de pantalla](#-capturas-de-pantalla)
- [Instalación](#-instalación)
- [Configuración de la base de datos](#-configuración-de-la-base-de-datos)
- [Estructura del proyecto](#-estructura-del-proyecto)
- [Posibles mejoras](#-posibles-mejoras)
- [Autor](#-autor)

## 👥 Roles de usuario

### 🏷️ Vendedor

El vendedor dispone de las funcionalidades relacionadas con la gestión de anuncios.

- Publicar anuncios.
- Organizar los anuncios mediante categorías.
- Editar sus anuncios.
- Gestionar su perfil de usuario.
- Guardar anuncios en favoritos.

### 🛒 Comprador

El comprador está orientado a consultar anuncios y guardar aquellos que le interesan.

- Consultar los anuncios publicados.
- Guardar anuncios en favoritos.
- Gestionar sus anuncios favoritos.

## ✨ Funcionalidades principales

- **Gestión de roles:** diferenciación entre vendedores y compradores.
- **Publicación de anuncios:** creación de anuncios por parte del vendedor.
- **Categorías:** clasificación de anuncios para facilitar su organización.
- **Edición de anuncios:** modificación de las publicaciones por parte del vendedor.
- **Gestión del perfil:** edición de los datos de usuario.
- **Sistema de favoritos:** posibilidad de guardar anuncios para consultarlos posteriormente.

## 🧰 Tecnologías

| Tecnología | Descripción |
|---|---|
| PHP | Desarrollo de la lógica del servidor. |
| MySQL | Gestión y almacenamiento de los datos. |
| HTML5 | Estructura de las páginas web. |
| CSS3 | Diseño y presentación de la interfaz. |
| JavaScript | Interactividad del lado del cliente. |
| XAMPP | Entorno local para ejecutar PHP y MySQL. |

## 🖼️ Capturas de pantalla

En este apartado se mostrarán las principales vistas de la aplicación.

<!-- Añade aquí las capturas de pantalla del proyecto -->

### Página principal

<!-- ![Página principal](ruta/a/tu/captura.png) -->

### Gestión de anuncios

<!-- ![Gestión de anuncios](ruta/a/tu/captura.png) -->

### Perfil de usuario y favoritos

<!-- ![Perfil y favoritos](ruta/a/tu/captura.png) -->

## 🚀 Instalación

Para ejecutar Anunciat en local, es necesario disponer de un entorno compatible con PHP y MySQL. Se recomienda utilizar XAMPP.

### Requisitos

- [XAMPP](https://www.apachefriends.org/es/index.html).
- Navegador web.
- Git (opcional, para clonar el repositorio).

### 1. Clonar el repositorio

```bash
git clone https://github.com/Jowyyyy/Anunciat.git
```

### 2. Ubicar el proyecto

Coloca la carpeta del proyecto dentro del directorio `htdocs` de XAMPP.

Ejemplo en Windows:

```text
C:\xampp\htdocs\Anunciat
```

### 3. Iniciar los servicios

Abre el panel de control de XAMPP e inicia los servicios:

- Apache
- MySQL

### 4. Configurar la base de datos

Accede a phpMyAdmin desde:

[http://localhost/phpmyadmin](http://localhost/phpmyadmin)

Crea o importa la base de datos necesaria para el funcionamiento de la aplicación.

### 5. Revisar la configuración

Comprueba los datos de conexión a MySQL en el archivo correspondiente y ajusta la configuración para que coincida con tu entorno local.

### 6. Ejecutar la aplicación

Abre el navegador y accede a la ruta local del proyecto. Por ejemplo, si la carpeta se llama `Anunciat`:

[http://localhost/Anunciat/](http://localhost/Anunciat/)

Adapta la URL si has utilizado otro nombre de carpeta o una configuración de rutas diferente.

## 🗄️ Configuración de la base de datos

Anunciat utiliza MySQL para almacenar la información de la aplicación.

Para configurar la base de datos:

1. Inicia MySQL desde XAMPP.
2. Accede a phpMyAdmin.
3. Crea la base de datos que espera la aplicación.
4. Importa el archivo SQL del proyecto, si está disponible.
5. Revisa el archivo `database/db.php` y configura los parámetros de conexión necesarios.

**Nota:** el nombre exacto de la base de datos y del archivo SQL debe completarse según la configuración real del proyecto.

No incluyas contraseñas reales ni credenciales privadas en el repositorio.

## 📂 Estructura del proyecto

```text
Anunciat/
├── assets/       # Recursos estáticos
├── backend/      # Lógica del servidor
├── database/     # Recursos de base de datos
├── includes/     # Archivos compartidos
├── js/           # Scripts JavaScript
├── styles/       # Hojas de estilos
├── index.php     # Punto de entrada
├── config.php    # Configuración general
└── README.md     # Documentación del proyecto
```

## 🛠️ Posibles mejoras

Como parte de la evolución de Anunciat y su preparación para el portfolio, se pueden considerar las siguientes mejoras:

- [ ] Añadir capturas de pantalla de la aplicación.
- [ ] Mejorar la documentación de instalación y configuración.
- [ ] Revisar la validación de datos y la seguridad de los formularios.
- [ ] Comprobar la gestión de sesiones y los permisos de cada rol.
- [ ] Mejorar la adaptación de la interfaz a dispositivos móviles.
- [ ] Valorar el despliegue de una demostración online.

## 👨‍💻 Autor

**Joel Maqueda**

Proyecto académico de Desarrollo de Aplicaciones Web (DAW), en proceso de mejora para mi portfolio profesional.

- **GitHub:** [@Jowyyyy](https://github.com/Jowyyyy)
- **Repositorio:** [Anunciat](https://github.com/Jowyyyy/Anunciat)

---

<p align="center">
  Desarrollado como proyecto de aprendizaje y mejora continua en desarrollo web.
</p>
