# Pokédex CRUD

Aplicación de escritorio en **.NET con C#** para la gestión de un catálogo de Pokémon. Permite crear, modificar, eliminar y buscar Pokémon, con visualización de imágenes y filtros avanzados. La interfaz está desarrollada con **Windows Forms** y el proyecto sigue una arquitectura en capas.

---

## Características Principales

- CRUD completo: crear, leer, actualizar y eliminar Pokémon.
- Baja física y baja lógica diferenciadas.
- Búsqueda rápida y filtros avanzados.
- Visualización de imágenes asociadas a cada Pokémon.
- Arquitectura en capas (Negocio y Presentación).
- Interfaz gráfica construida con Windows Forms.

---

## Tecnologías Aplicadas

- **.NET con C#**: Lógica de negocio y capa de presentación.
- **Windows Forms**: Interfaz gráfica de usuario.
- **SQL Server**: Base de datos para almacenamiento de registros.

---

## Estructura del Proyecto

- `Pokemon/`: Proyecto principal con formularios y `Program.cs`.
- `negocio/`: Lógica de negocio y acceso a datos.
- `App.config`: Configuración de conexión a la base de datos.
- `Database/`: Script SQL para crear la base de datos y tabla Pokémon.

---

## Uso y Despliegue

1. Configurar SQL Server y ejecutar el script incluido en `/Database`.
2. Ajustar la cadena de conexión en `App.config`.
3. Abrir la solución en Visual Studio.
4. Seleccionar `Pokemon` como proyecto de inicio.
5. Ejecutar con **F5**.

---
