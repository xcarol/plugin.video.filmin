# Filmin Kodi
Reproduce tu contenido de Filmin favorito usando Kodi ≥ 19 (Matrix)

## Cómo instalar
### Recomendado
Para poder tener actualizaciones automáticas puedes usar los siguientes métodos:
#### Zip
Para sistemas en los que _sí_ puedes copiar archivos al disco (PC, Teléfono, Raspberry Pi...)

Descarga el [siguiente](https://kodi.pabloferreiro.es/repository.pabloferreiro/repository.pabloferreiro-1.2.0.zip) archivo e instálalo usando Kodi.

Una vez instalado ya puedes descargar Filmin para Kodi desde el menú de addons
#### Explorador
Para sistemas empotrados (Fire Stick, Chromecast...)

Accede a Ajustes -> Gestor de Archivos -> Añadir fuentes

Una vez ahí agrega la ruta `https://kodi.pabloferreiro.es` con el nombre que quieras.

Accede a Addons -> Instalar desde  un archivo zip -> Carpeta con el nombre que pusiste -> repository.pabloferreiro -> repository.pabloferreiro-1.2.0.zip

Una vez instalado ya puedes descargar Filmin para Kodi desde el menú de addons

### Manual
Descarga el archivo .zip generado por Github e instálalo.

## Roadmap
### Funciones agregadas
* Autorización
* Reproducción con y sin DRM, pudiendo elegir audio y subtítulos
* Búsqueda
* Highlights
* Colecciones
* Watching
* Listas de reproducción
* Sincronizar progreso de visionado con Filmin (Roto por ahora)
* Soporte para Portugal y México
* Watch Later

### Prioridades
* Integración con Up Next
* Paginación
* Adaptar más métodos de `api.py` a la nueva uapi
* Migrar de `ListItem` a `InfoTagVideo`
* Arreglar la sincronización con Filmin
