# SkiFree Remix

Prototipo de un juego de esquí inspirado en SkiFree (Microsoft, 1991). Tiene tres niveles con meta y cronómetro, banderas para sumar puntos y un yeti que aparece a mitad de cada nivel.

## Cómo jugar

Abre `index.html` en un navegador. No necesita servidor ni instalación.

## Controles

Con cámara (recomendado):

- Mueve la cabeza a los lados para esquivar.
- Acerca la cabeza a la pantalla para ir más rápido.
- Aleja la cabeza de la pantalla para frenar.
- Al empezar, centra la cabeza unos segundos para calibrar.

Sin cámara, o si no se detecta tu cara:

- ← →: moverte a los lados
- ↓: ir más rápido
- ↑: frenar

Enter o Espacio: continuar, o reintentar después de perder.

## Energía y yeti

- Ir rápido gasta energía. La energía se recupera cuando vas a velocidad normal.
- La barra de la izquierda muestra la energía, y la de la derecha, qué tan cerca está el yeti.

## Reglas

- Pasa entre cada par de banderas (roja y azul) para sumar 100 puntos.
- Chocar con un árbol o una roca te frena un momento y acerca al yeti.
- Si el yeti te alcanza, pierdes el nivel.
- Si se acaba el tiempo antes de llegar a la meta, también pierdes.
- Al llegar a la meta, recibes un bonus por el tiempo que te sobró.

## Ajustes

Los niveles están en la lista `LEVELS` dentro de `index.html`. Puedes cambiar:

- `largo`: distancia de la meta
- `tiempo`: segundos disponibles
- `densidad`: cantidad de árboles y rocas
- `yeti`: velocidad base del yeti

## Privacidad

La cámara se usa solo para seguir la nariz en el navegador. No se graba, no se guarda y no se envía a ningún servidor. El detector de rostros (MediaPipe) se descarga de su CDN. No se usa micrófono.

## Estado

Probado con un detector de rostros simulado en Chrome headless: sin errores de página, calibración correcta y render de la pantalla. No probado con la cámara real ni con el detector real, ni en Safari.
