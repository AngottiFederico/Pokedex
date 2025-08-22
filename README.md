<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pokédex CRUD</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        h1 {
            text-align: center;
        }
        section {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        img {
            display: block;
            max-width: 100%;
            height: auto;
            margin: 20px auto;
            border-radius: 10px;
        }
        a {
            color: #2980b9;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <h1>Pokédex CRUD</h1>

    <section>
        <p>Aplicación de escritorio en <strong>.NET con C#</strong> para la gestión de un catálogo de Pokémon. Permite crear, modificar, eliminar y buscar Pokémon, con visualización de imágenes y filtros avanzados. La interfaz está desarrollada con <strong>Windows Forms</strong> y el proyecto sigue una arquitectura en capas.</p>
    </section>

    <section>
        <h2>Características Principales</h2>
        <ul>
            <li>CRUD completo: crear, leer, actualizar y eliminar Pokémon.</li>
            <li>Baja física y baja lógica diferenciadas.</li>
            <li>Búsqueda rápida y filtros avanzados.</li>
            <li>Visualización de imágenes asociadas a cada Pokémon.</li>
            <li>Arquitectura en capas (Negocio y Presentación).</li>
            <li>Interfaz gráfica construida con Windows Forms.</li>
        </ul>
    </section>

    <section>
        <h2>Tecnologías Aplicadas</h2>
        <ul>
            <li><strong>.NET con C#</strong>: Lógica de negocio y capa de presentación.</li>
            <li><strong>Windows Forms</strong>: Interfaz gráfica de usuario.</li>
            <li><strong>SQL Server</strong>: Base de datos para almacenamiento de registros.</li>
        </ul>
    </section>

    <section>
        <h2>Estructura del Proyecto</h2>
        <ul>
            <li><code>Pokemon/</code>: Proyecto principal con formularios y <code>Program.cs</code>.</li>
            <li><code>negocio/</code>: Lógica de negocio y acceso a datos.</li>
            <li><code>App.config</code>: Configuración de conexión a la base de datos.</li>
            <li><code>Database/</code>: Script SQL para crear la base de datos y tabla Pokémon.</li>
        </ul>
    </section>

    <section>
        <h2>Uso y Despliegue</h2>
        <ol>
            <li>Configurar SQL Server y ejecutar el script incluido en <code>/Database</code>.</li>
            <li>Ajustar la cadena de conexión en <code>App.config</code>.</li>
            <li>Abrir la solución en Visual Studio.</li>
            <li>Seleccionar <code>Pokemon</code> como proyecto de inicio.</li>
            <li>Ejecutar con <strong>F5</strong>.</li>
        </ol>
    </section>

    <section>
        <h2>Contacto</h2>
        <p>Proyecto desarrollado por <strong>[Tu Nombre]</strong></p>
        <p>📧 <a href="mailto:tuemail@email.com">tuemail@email.com</a></p>
        <p>🔗 <a href="[Tu LinkedIn o GitHub]" target="_blank">Perfil</a></p>
    </section>

    <section>
        <h2>Vista previa de la aplicación</h2>
        <img src="./screenshots/app.png" alt="Pokédex CRUD">
    </section>

</body>
</html>
