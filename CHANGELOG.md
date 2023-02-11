# CHANGES
## GENERAL
- No crees carpetas con mayusculas (Marvel), en programacion (y en general en cualquier ordenador) todas las carpetas y ficheros en minusculas, sin acentos y sin espacios).
- Aunque no está mal, nadie pone <p> con la p en mayusucula.
## Header
- A modo personal, haría la imagen de Marvel un poco más pequeña.
- Como quieres que el cambio de altura repercuta en la anchura también (que no deforme la imagen), no es necesario que pongas el width, con el heigth vale.
## Banner
- El estilo .rc-section-hero--banner es cover para cubrir todo el ancho de la pantalla descratando la altura de la imagen.
- Además, aunque no importante para la estética, en index.html el attributo loading="lazy" no existía. Esto influye en el modo en que carga la imagen (para conexiones lentas o webs muy muy cargadas de fotos pesadas).

## Peliculas
- **Dentro de article** tiene que estar tanto titulo como la descripción no fuera, tanto el **h3** como el **p**
- Los articulos tienen el estilo article, no section. rc-section-featured__article
- La p de cada articulo no necesita ningun estilo, y de ninguna manera puede tener el preview de la imagen. Fíjate en el h3, no necesita nada
- Las imagenes de la web del profesor tienen margenes en la propia imagen, por eso he añadido un padding a cada articulo para que agregue ese margen de manera automatica. 
  ```
  .rc-section-featured--preview {
      ...
      padding: var(--rc-img-padding) 0 var(--rc-img-padding) 0;
  }
  ```
  Si no has visto este padding, el primer argumento es arriba, segundo derecha, tercero abajo, cuarto izquierda (como el reloj), por lo que he añadido padding solo arriba y abajo.
- Para no recargar las caratulas ocn demasiado texto he quitado _Recaudación_ de todas y he abreviado _millones $_ por _M\$_
- Al no tener las imagenes exactamente con la misma proporcion de alto y ancho se ven diferencias. Eso un autentico coñazo crear o buscar imagenes para web, para que realmente quede bien es vital que todo esté al milímetro, el ojo humano es buenisimo comparando y en cuanto ve dos cosas cerca diferentes... meeeeehck!

## Series
**Lo mismo que para películas**
- Añadir que los textos largos descuadran. Eso puedes preguntar si hay forma de arregrlarlo o se queda así

## Footer
- Faltaba entero
  - Faltaban los estilos: rc-section-video__description y rc-section-video
  - no había video



