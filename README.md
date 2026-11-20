# SkiFree Remix

Prototipo de un juego de esquí inspirado en SkiFree (Microsoft, 1991). Tiene tres niveles con meta y cronómetro, banderas para sumar puntos y un yeti que aparece a mitad de cada nivel.

## Cómo jugar

Abre `index.html` en un navegador. No necesita servidor ni instalación.

## Controles

- ← →: moverte a los lados
- ↓: ir más rápido
- ↑: frenar
- Enter o Espacio: continuar, o reintentar después de perder

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

El juego no usa cámara, micrófono ni red. Todo corre en el navegador y no guarda datos.

## Estado

Prototipo sin probar en navegadores reales. Se revisó la sintaxis del código, pero no se jugó en un navegador.
