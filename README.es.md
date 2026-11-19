# OrcaGif – Creador y editor de GIF gratis y privado

[English](README.md) · [Deutsch](README.de.md) · [Français](README.fr.md) · **Español** · [العربية](README.ar.md) · [हिन्दी](README.hi.md) · [中文](README.zh.md) · [বাংলা](README.bn.md) · [Português](README.pt.md) · [Bahasa Indonesia](README.id.md)

Convierte un vídeo en GIF, edita un GIF que ya tienes o guarda el resultado como WebP o WebM, mucho más ligeros. OrcaGif es un único archivo HTML. Todo funciona en local en tu navegador: sin subir archivos, sin cuenta, sin cookies.

## Inicio rápido
1. Abre `OrcaGif.html` en tu navegador.
2. Elige una pestaña arriba: **🎬 Vídeo a GIF** (crear un GIF a partir de un vídeo) o **🎨 Editor de GIF** (editar un GIF, imagen, vídeo, WebP o WebM que ya tienes).
3. Elige el tipo de archivo (GIF, WebP o WebM), pulsa el botón azul y descarga el resultado.

> La guía «Cómo funciona – guía rápida y preguntas frecuentes» en la parte superior de la página explica los mismos pasos con palabras sencillas, en los 10 idiomas.

## ¿Qué tipo de archivo elegir?
- **GIF** funciona en todas partes (chats, foros, correo), pero los archivos pesan más. ¿Dudas? Elige GIF.
- **WebP** es mucho más pequeño que GIF, se ve mejor y puede tener fondo transparente. Todos los navegadores actuales lo muestran; algunos programas antiguos no.
- **WebM** es el más pequeño y fluido, pero es un vídeo: sin fondo transparente, y crearlo tarda más que el propio fragmento (se graba en tiempo real: mantén la pestaña en primer plano).
- **Calidad** (WebP y WebM): alta, media o baja. Menos calidad significa un archivo más pequeño.
- Si WebP o WebM aparece atenuado, tu navegador no puede crear ese formato. Usa una versión actual de Chrome, Edge o Firefox.

## Crear un GIF a partir de un vídeo – paso a paso
1. Haz clic en la pestaña **🎬 Vídeo a GIF**.
2. Haz clic en el botón de archivo de la izquierda y elige un vídeo de tu dispositivo (MP4 y WebM funcionan en cualquier navegador moderno; MKV y HEVC dependen del navegador y del dispositivo). No se sube a ningún sitio, y funcionan incluso archivos de varios GB.
3. Elige la parte que quieras: arrastra sobre la barra bajo el vídeo, usa **Fijar inicio aquí** / **Fijar fin aquí** (teclas `I` / `O`) o escribe los tiempos. **▶ Reproducir fragmento** muestra una vista previa. Los fragmentos cortos de 2 a 6 segundos funcionan mejor.
4. Ajusta el **Ancho de salida** (lo ancho que será el GIF; 480 es un buen punto de partida) y los **FPS** (fotogramas por segundo; 15 se ve fluido). Números más bajos dan un archivo más pequeño.
5. Elige el tipo de archivo y pulsa el botón azul. Mantén la pestaña en primer plano hasta que la barra se llene.
6. Pulsa el botón azul de descarga. Si es un GIF, antes puedes pulsar **Editar en el editor de GIF** para añadir texto.

## Editar un GIF que ya tienes
1. Abre la pestaña **🎨 Editor de GIF** y elige tu archivo a la izquierda: un GIF, una imagen, un vídeo, un **WebP animado** o un **WebM**. También funciona arrastrar y soltar.
2. Pulsa ▶ para reproducir. Mueve el control deslizante para ver las imágenes una a una (fotogramas).
3. En **Editar**: **Fotograma inicial** / **Fotograma final** quitan el principio o el final, **Velocidad ×** lo acelera o ralentiza, **Invertir** lo reproduce al revés, **FPS** (máx. 50) y **Ancho de salida** cambian la fluidez y el tamaño, **Recortar** recorta la imagen.
4. Elige el tipo de archivo, pulsa el botón azul y descarga el resultado. ¿Te has equivocado? Pulsa **Deshacer** arriba.

## Añadir texto, imágenes y dibujos
- **+ Texto** pone palabras sobre tu GIF. Escríbelas en el cuadro de la izquierda, elige fuente, tamaño y color, y arrastra el texto al lugar adecuado. **Haz doble clic en el texto de la imagen para editarlo otra vez** (o doble clic en la lista de capas).
- **+ Imagen** añade tu propia imagen, por ejemplo un logotipo. **✏️ Dibujar** te deja dibujar con el ratón o el dedo.
- Cada texto, imagen o dibujo es una **capa**. Haz clic en una capa de la lista para seleccionarla; ▲ ▼ la suben o bajan y ✕ la elimina. **Visible desde el fotograma** / **hasta el fotograma** deciden cuándo se muestra.
- Rueda del ratón sobre una capa = tamaño, Mayús + rueda = rotación. Las capas también se pueden dejar fuera de la imagen (margen oscurecido) y recuperarlas más tarde.

## Dar movimiento a los elementos
- **La forma rápida:** selecciona un texto o una imagen y pulsa un efecto: Aparecer, Entrar volando, Pulso, Sacudir, Girar o Rebotar.
- **A tu manera:** marca **Animar (fotogramas clave)**, ve a otro fotograma y arrastra la capa a otro sitio. OrcaGif rellena el movimiento intermedio. Elige una aceleración si quieres.

## ¿Qué significan estas palabras?
- **Fotograma (frame)** – una sola imagen de una animación. Un GIF son muchos fotogramas mostrados rápidamente uno tras otro.
- **FPS** – fotogramas por segundo. Más es más fluido, pero el archivo pesa más.
- **Ancho de salida** – lo ancho que será el archivo final, en píxeles (puntos diminutos en la pantalla).
- **Tramado (dithering)** – un GIF solo puede usar 256 colores. Este truco mezcla puntitos para que los cielos y la piel se vean más suaves. Actívalo para fotos y vídeos y déjalo apagado para logotipos y dibujos de colores planos. (Solo GIF.)
- **Fondo transparente** – las partes transparentes dejan ver lo que hay detrás de la imagen. Funciona en GIF y WebP.
- **Capa** – un texto, imagen o dibujo que está encima de tu GIF.
- **Fotograma clave** – una posición, tamaño o ángulo guardado en un momento. OrcaGif rellena el movimiento entre dos fotogramas clave.
- **Marca de agua** – el pequeño texto «OrcaGif» en una esquina. Está activada por defecto: mantenla para apoyar esta herramienta gratuita.

## Mi archivo pesa demasiado, ¿qué hago?
Usa un **Ancho de salida** menor, menos **FPS** o un fragmento más corto, o elige **WebP**. Si los colores de un GIF se ven con manchas, activa el **tramado (dithering)**.

## Proyectos
- **Guardar** conserva el proyecto en tu navegador para continuar más tarde.
- **Archivo de proyecto ↓ / ↑** guarda / abre un archivo real (`.gifproj`).

## Atajos
`Ctrl+Z` deshacer · `Ctrl+Y` rehacer · `Ctrl+S` guardar · `Ctrl+D` duplicar capa · `←` `→` fotograma anterior / siguiente · doble clic en un texto = editarlo · `I` / `O` inicio / fin (Vídeo a GIF)

---
Proyecto personal sin ánimo de lucro. Contador de visitas anónimo y sin cookies ([GoatCounter](https://www.goatcounter.com)). Contacto: Discord (enlace en el pie de la aplicación).
