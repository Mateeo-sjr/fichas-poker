# Fichas de póker

Web para jugar al Texas Hold'em con amigos cuando tenéis baraja pero no fichas. Ponéis el móvil en el centro de la mesa: vosotros repartís las cartas y la app lleva las fichas, el turno, las ciegas y el bote, incluidos los botes paralelos.

- Un solo archivo `index.html`, sin dependencias ni compilación.
- Se instala en el móvil ("Añadir a pantalla de inicio") y funciona sin conexión.
- La partida se guarda en el propio móvil.

## Editar

1. Cambia `index.html`.
2. Pruébalo en local: `python -m http.server 4600` y abre `http://localhost:4600`.
3. Sube la versión de `CACHE` en `sw.js` (`fichas-v1` → `fichas-v2`) para que los móviles que ya la tienen instalada cojan la nueva.
4. `git commit` y `git push`. GitHub Pages la publica sola en un minuto o dos.
