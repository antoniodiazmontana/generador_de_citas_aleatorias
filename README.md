# Generador de Citas Aleatorias en Vue.js

## Descripción

Este es un proyecto simple que genera una cita aleatoria cada vez que el usuario hace clic en un botón. Está construido utilizando Vue.js, un framework progresivo de JavaScript que facilita la creación de interfaces interactivas. El proyecto está diseñado con un diseño limpio y moderno, con una interfaz centrada en la página que permite al usuario ver citas inspiradoras al azar.

## Características

- **Generación de Citas Aleatorias**: Al hacer clic en el botón, el usuario recibe una nueva cita seleccionada aleatoriamente de un conjunto predefinido de citas.
- **Interfaz limpia y visualmente atractiva**: Con un fondo visualmente atractivo y un diseño minimalista.
- **Diseño adaptativo**: La aplicación está diseñada para ser visualmente atractiva en diferentes tamaños de pantalla.

## Requisitos

Para ejecutar este proyecto, solo necesitas tener un navegador web que soporte JavaScript y Vue.js.

## Instalación

1. **Clona el repositorio**:
   Si aún no tienes el repositorio, puedes clonarlo con el siguiente comando:

   ```bash
   git clone https://github.com/tuusuario/generador-citas-aleatorias.git
   ```

2. **Abre el proyecto**:
   Una vez clonado el proyecto, abre el archivo `index.html` en tu navegador preferido. No necesitas servidores o herramientas adicionales para verlo en funcionamiento.

## Estructura del Proyecto

El proyecto tiene la siguiente estructura de archivos:

```
/generador-citas-aleatorias
│
├── assets
│   ├── audio
│   │   └── Zen_Music.mp3 (opcional)
│   └── img
│       └── pexels-pixabay-235990.jpg (opcional)
│
├── index.html
│   └── Archivo principal con la estructura HTML y Vue.js para el generador de citas
└── README.md
    └── Este archivo
```

- **index.html**: Este archivo contiene el código HTML, Vue.js y el estilo CSS para la interfaz.
- **assets/audio**: Archivos de audio opcionales como música de fondo (no incluidos por defecto).
- **assets/img**: Fondo de imagen para el diseño visual de la aplicación.

## Uso

1. Abre el archivo `index.html` en tu navegador.
2. Haz clic en el botón **"Generar cita"** para ver una cita aleatoria.
3. La cita cambiará cada vez que se haga clic en el botón.

## Funcionalidad

El código funciona de la siguiente manera:

- La aplicación Vue está configurada con un conjunto de citas.
- Cuando el usuario hace clic en el botón **Generar cita**, se selecciona una cita aleatoria utilizando `Math.random()` para calcular el índice.
- La cita aleatoria se muestra en el área de la página donde está el `h1`.

## Personalización

Puedes agregar más citas al array `citas` en el archivo `index.html` para personalizar las frases que se mostrarán. Simplemente sigue el formato de las citas existentes.

## Contribución

Si quieres mejorar este proyecto o agregar nuevas funcionalidades, siéntete libre de hacer un fork y enviar tus cambios a través de un pull request.

## Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.
