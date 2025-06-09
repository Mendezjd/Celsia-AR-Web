
Built by https://www.blackbox.ai

---

# Lago Calima Celsia - Visualizador 3D

## Descripción del Proyecto
**Lago Calima Celsia** es una aplicación web interactiva que permite a los usuarios explorar un modelo 3D del Lago Calima. Utilizando Babylon.js para el renderizado y Tailwind CSS para el diseño, este proyecto ofrece una experiencia inmersiva con controles de audio, visualización de documentos PDF y un diseño responsivo adaptado tanto para dispositivos móviles como de escritorio.

## Instalación

Para ejecutar el proyecto localmente, sigue estos pasos:

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/lago-calima-celsia.git
   cd lago-calima-celsia
   ```

2. **Abre el archivo `index.html`:**
   Puedes abrirlo directamente en un navegador o configurar un servidor local para una mejor experiencia. Por ejemplo, usando el servidor HTTP de Python:
   ```bash
   python -m http.server 8000
   ```

3. **Visita la aplicación:**
   Abre tu navegador y navega a `http://localhost:8000`

## Uso

Una vez que la aplicación esté cargada en tu navegador:

- Interactúa con el modelo 3D usando el mouse o controles táctiles:
  - Click izquierdo + arrastrar: Rotar la cámara
  - Click derecho + arrastrar: Pan
  - Rueda del mouse: Zoom
- Usa los botones de control para:
  - Reproducir información de audio sobre diferentes puntos de interés
  - Ver documentos PDF informativos

## Características

- **Visualizador 3D:** Carga e interactúa con el modelo GLB del Lago Calima.
- **Control de Audio:** Reproduce información de audio sobre diferentes puntos de interés.
- **Visor de PDF:** Accede a documentos informativos directamente desde la interfaz.
- **Diseño Responsivo:** Optimizado para dispositivos móviles y de escritorio.
- **UI Amigable:** Controles intuitivos y animaciones de carga que mejoran la experiencia del usuario.

## Dependencias

El proyecto utiliza las siguientes bibliotecas:

- **[Babylon.js](https://www.babylonjs.com/):** Motor 3D para renderizar el modelo GLB.
- **[Tailwind CSS](https://tailwindcss.com/):** Framework CSS para el diseño.
- **[Font Awesome](https://fontawesome.com/):** Iconos para los botones de control.

Las dependencias se incluyen a través de CDN en el archivo HTML.

## Estructura del Proyecto

```
.
├── index.html                # Archivo HTML principal
├── LagoCalimaCelsia.glb     # Modelo 3D del lago
├── Imagen Satelital.pdf      # Documento informativo
└── audio/                   # Archivos de audio informativos
```

## Contribución

Este proyecto es parte de la iniciativa de Celsia para proporcionar información interactiva sobre el Lago Calima. Si deseas contribuir, puedes abrir issues o enviar pull requests en el repositorio.
