# G'nius - Oficina de Apoyo a la Innovación UTEC

G'nius es una plataforma web diseñada para gestionar emprendedores y empresas que forman parte de la Oficina de Apoyo a la Innovación de la UTEC. Esta herramienta permite administrar tanto a administradores como asesores, facilitando la creación de reportes y el registro de usuarios mediante un formulario multipasos, con verificación de cuentas a través de un código de activación enviado al correo.

## Características

- **Formulario Multipasos**: Registro de datos de emprendedores de manera sencilla y eficiente.
- **Gestión de Roles**: Administra cuentas de administradores y/o asesores.
- **Verificación de Cuenta**: Los usuarios reciben un código de activación en su correo para verificar su cuenta.
- **Generación de Reportes**: Facilita la creación y visualización de reportes.
- **Arquitectura MVC**: Implementación de la arquitectura Modelo-Vista-Controlador.
- **Interactividad con JavaScript**: Para una experiencia de usuario más dinámica.
- **Base de Datos MySQL**: Utiliza MySQL para el almacenamiento de datos.
- **Lenguaje PHP**: PHP como el lenguaje principal del backend.

## Tecnologías

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Base de Datos**: MySQL
- **Arquitectura**: MVC (Modelo-Vista-Controlador)

## Instalación

1. Clona este repositorio:
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```

2. Configura la base de datos:
    - Crea una base de datos MySQL y configura los parámetros en el archivo `Config/Conexion.php`.
    - Implementa un archivo para encriptar y desencriptar contraseñas en `Models/Publico/PasswordModel.php`

3. Sube los archivos al servidor web.

4. Accede a la aplicación a través de tu navegador y configura el sistema.

## Contribución

Si deseas contribuir, por favor realiza un fork de este repositorio y envía tus pull requests. Asegúrate de seguir las mejores prácticas de codificación y mantener la estructura del proyecto.

## Licencia

Copyright (c) [2025] [Marcela Menjívar - mgmarce]
