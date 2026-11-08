# Visual Lab

Editor de nodos en el navegador (estilo TouchDesigner / Cables.gl): cámara, audio, manos, línea de tiempo, curvas, fórmulas y exportación a PNG / GIF / WebM.

- `nodes.html`: el editor de nodos (con tutoriales integrados: botón "? Tutoriales").
- `index.html`: prototipo simple de efectos reactivos al audio y la cámara (con un acceso al editor de nodos).

En el editor de nodos:

- **Compartir link** copia una URL con todo el proyecto comprimido después de `#g=`. No usa servidor: quien abre el link ve el mismo proyecto y lo puede modificar. La cámara y los archivos cargados no viajan en el link.
- **Proyector** abre una ventana aparte que muestra solo el visual, sin interfaz. Se arrastra a la segunda pantalla y con doble clic pasa a pantalla completa (el cursor se oculta solo).

Es un sitio estático: no necesita instalar nada. Para verlo con GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root, y abrir `/nodes.html`.

La cámara, el micrófono y las manos requieren HTTPS (GitHub Pages lo da) o localhost.
