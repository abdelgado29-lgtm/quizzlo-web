# Quizzlo

Juego interactivo de preguntas tipo quiz (asignaturas, niveles, modos de juego, ranking y banco de preguntas).

Abre `index.html` en el navegador para jugar.

> Nota: el ranking compartido, el perfil de usuario y el banco de preguntas usan el runtime de los Artifacts de claude.ai (`window.claude`). Fuera de claude.ai esas funciones no estarán disponibles.

Versión publicada: https://claude.ai/artifact/AgWEzh7ouWzSxKVuEeBCU9

## Versión web independiente (`web/`)

`web/index.html` funciona en cualquier hosting estático (GitHub Pages, Firebase Hosting, Netlify…), sin claude.ai.
- Los datos (tarjeta de jugador, ranking, progreso) se guardan en el navegador de cada persona, así que el ranking no se comparte entre dispositivos.
- Modo profesor: añade `?profesor=1` a la URL.
