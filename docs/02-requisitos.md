# Requisitos del Sistema

## Requisitos Funcionales

### Usuarios
* Registro, Autenticación y gestión de perfiles (avatar, biografia, carrera, universidad).
* Sistema de niveles y experiencia basados en el uso de la plataforma.

### Mazos y Tarjetas
* Creación, edición y eliminación de mazos
* Soporte para texto, imagenes y niveles de dificultad en la tarjetas.
* Sistema de versionado y contribuciones comunitarias.

### Modos de Estudio
* Motor de repetición espaciada ajustado por la confianza del usuario (Facil, Medio, Dificil).
*Retos cronometrados Pvp (Jugador vs Jugador).

### Inteligencia Artificial
* Generación de tarjetas a partir de **prompts** de texto o documentos.
* egistro de tokens consumidos por usuario para control de costos.

## Requisitos No Funcionales
* **Rendimiento:** La API debe responder en menos de 200 ms, Tambien dependera del texto y el nivel requerido de evaluación y análisis.
* **Escalibidad:** Arquitectura desacoplada (Frontend/Backend).
* **Disponibilidad:** Despliege en la nube (AWS)con redundancia de base de datos.