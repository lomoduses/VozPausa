# VozPausa

**Lee, escucha y aprende a tu ritmo.** VozPausa es una aplicación web ligera de lectura en voz alta diseñada para estudiar, repasar apuntes, practicar pronunciación y escuchar cualquier texto con pausas personalizadas.

A diferencia de un lector de texto convencional que reproduce un párrafo completo de principio a fin, VozPausa divide el contenido en bloques pequeños. El usuario decide cuántas palabras se leen antes de cada pausa, cuánto dura el silencio y a qué velocidad habla la voz seleccionada. Así puede seguir el material poco a poco, tomar notas o comprobar si comprendió cada fragmento.

## Funciones

### Editor y gestión de textos
- Escribir o pegar contenido directamente en el editor.
- Cargar archivos de texto `.txt`.
- Probar la aplicación con un texto de ejemplo.
- Consultar el recuento de palabras y caracteres y la cantidad estimada de bloques.
- Guardar el contenido escrito como un archivo `.txt`.
- Limpiar el editor y preparar una nueva lectura.

### Voz y ritmo de lectura
- Elegir entre las voces que tenga disponibles el navegador y el sistema operativo.
- Seleccionar una voz en español cuando haya alguna instalada.
- Ajustar la velocidad de lectura para adaptar el audio a las preferencias de cada persona.

### Pausas configurables
- Dividir el texto en bloques de entre 1 y 20 palabras.
- Utilizar accesos rápidos para configuraciones habituales de 3, 4 o 5 palabras.
- Definir la duración de cada pausa entre 0 y 8 segundos.
- Activar una pausa adicional al finalizar un párrafo para separar mejor las ideas.

### Controles durante la lectura
- Comenzar, pausar, continuar y detener la reproducción.
- Repetir el bloque actual para volver a escuchar una parte difícil.
- Avanzar al siguiente bloque cuando se quiera continuar.
- Visualizar el fragmento actual, el número de bloque y el porcentaje de progreso.
- Utilizar la barra espaciadora para iniciar o pausar/continuar, y `Esc` para detener la sesión (cuando el foco no está en un campo de escritura).

### Experiencia de uso
- Interfaz adaptable a computadoras, tabletas y teléfonos.
- Tema oscuro y tema claro.
- Diseño sin registro, sin cuenta de usuario y sin instalación.

## Cómo utilizar VozPausa

1. Abre la página y escribe o pega el texto que quieras escuchar.
2. También puedes importar un archivo `.txt`.
3. Selecciona una de las voces disponibles.
4. Elige cuántas palabras debe leer antes de insertar una pausa.
5. Configura la duración del silencio y la velocidad de lectura.
6. Pulsa **Comenzar lectura**.
7. Durante la sesión, usa los controles para pausar, continuar, repetir el bloque actual o avanzar.

## Tecnología y privacidad

VozPausa es una aplicación estática construida con HTML, CSS y JavaScript. La lectura utiliza la API de síntesis de voz del navegador (`SpeechSynthesis`). No requiere un servidor propio para convertir el texto ni una cuenta de usuario. El contenido se procesa en el navegador y no se envía a un servidor de VozPausa.

La lista de voces, su calidad, pronunciación y disponibilidad dependen del navegador, del sistema operativo y de las voces instaladas en el dispositivo. Por ello, la experiencia puede variar entre equipos. Se recomienda utilizar una versión actualizada de Chrome, Edge, Firefox o un navegador compatible con la síntesis de voz.

**Nota sobre el nombre:** VozPausa convierte texto escrito en voz (texto a voz). No es, en esta versión, un sistema de reconocimiento o transcripción de voz a texto.

## Publicar con GitHub Pages

Este proyecto está preparado para funcionar como un sitio independiente. El archivo de inicio `index.html` se encuentra en la raíz del repositorio.

1. Crea un repositorio nuevo en GitHub llamado `VozPausa` (o el nombre que prefieras).
2. Sube `index.html` y `README.md` a la raíz de ese repositorio.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
6. Espera a que GitHub Pages termine la primera publicación y utiliza la URL que GitHub muestre en esa misma sección.

No copies estos archivos dentro de UniDoc: VozPausa debe permanecer en su propio repositorio.

## Estructura

```text
VozPausa/
├── index.html   # Aplicación web completa
└── README.md    # Descripción, funciones e instrucciones
```

## Estado del proyecto

Primera versión funcional. Las funciones de voz dependen de las capacidades del navegador y de las voces instaladas en el dispositivo.
