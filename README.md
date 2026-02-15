
# Sistema de Gestión de Streaming

Proyecto  en Go que simula una plataforma de streaming para administrar **usuarios** y **contenidos** (películas/series).

## Qué incluye
- **Structs** para modelar Usuario, Película, Serie, Reproducción y la plataforma.
- **Encapsulación**: atributos privados + getters/setters con validaciones.
- **Manejo de errores**: las funciones retornan `error` cuando hay datos inválidos, duplicados o elementos inexistentes.
- **Interfaces (Multimedia)** para aplicar **polimorfismo** y manejar películas/series en un mismo catálogo.
- **Slices y maps** para almacenamiento, listados y búsquedas rápidas (por email e ID).

## Funcionalidades
- Registrar usuarios (evita duplicados por email).
- Registrar contenido (película/serie) con plan requerido (free/premium).
- Gestionar favoritos (agregar, quitar, listar).
- Registrar reproducciones e historial.
- Regla de negocio: usuario **free** no puede reproducir contenido **premium**.

