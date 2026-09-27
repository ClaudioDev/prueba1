# prueba1
Prueba1

## El Mago y el Balrog

Animación en pixel art (Canvas + JavaScript, sin dependencias) de un mago que lanza poderes con su bastón contra un Balrog sobre un puente de piedra.

- Archivo: [`index.html`](index.html)
- Para verla en la web: activa GitHub Pages en **Settings → Pages** (rama `master`, carpeta `/ (root)`) y abre `https://claudiodev.github.io/prueba1/`.
- También se puede abrir `index.html` directamente en el navegador.

### El Balrog en 3D

[`balrog3d.html`](balrog3d.html): el Balrog en 3D (Three.js) con animación en reposo, fuego, alas, espada y látigo. Se puede girar alrededor con el dedo o el mouse, acercar con la rueda o pellizcando, y hacerlo rugir.

### El Balrog realista

[`balrog-realista.html`](balrog-realista.html): versión cinematográfica en 3D. El cuerpo es una sola malla orgánica generada a partir de formas suaves (SDF + surface nets) y animada con un esqueleto (skinning), con piel de obsidiana con relieve y grietas de lava, llamas y humo, puente de Khazad-dûm, profundidad de campo, gradación de color y grano de película. Mismos controles: girar, rugir, latigazo, agitar el látigo, sonido y música.

### Sombra y llama

[`balrog-sombra.html`](balrog-sombra.html): un Balrog hecho de fluido vivo. Una simulación de fluidos (Navier-Stokes) en la GPU con WebGL puro, donde el cuerpo inyecta humo y calor: el humo se arremolina, el fuego sube con flotabilidad real y las alas son masas de humo. Intro cinemática, luz que se lleva con el dedo o el mouse, latigazo al tocar, rugido y "¡No puedes pasar!" con el puente que se quiebra.
