# Cretacic Kingdom

Terror y aventura en primera persona con estética de cinta VHS: un parque de
dinosaurios abandonado en una isla que no está en ningún año. Hay que robar un
huevo de cada una de las siete exhibiciones y escapar antes de quedarse dentro.

Motor de raycasting escrito a mano en un solo archivo HTML — sin dependencias,
sin imágenes y sin audio externo. Todos los sprites, texturas y sonidos se
generan por código al cargar.

## Cómo jugar

Abre [index.html](index.html) en cualquier navegador moderno. Haz clic en la
imagen para capturar el teclado.

### Controles
- `WASD` — moverse · `MAYÚS` — esprintar
- `RATÓN` — mirar (o arrastrar con el botón pulsado si el navegador bloquea el puntero)
- `← →` — girar con el teclado
- `ESPACIO` — saltar · `C` — agacharse
- `E` — interactuar · `F` — linterna · `G` — devolver el huevo al nido
- `1 2 3` — elegir objeto · `Q` — usarlo
- `TAB` — plano del parque · `N` — archivo de documentos · `ESC` — pausa

## La isla

No es una isla: una isla está en algún sitio. Esto está en todos los sitios a la
vez y en ninguno de sus años. Se lleva lo que quiere —un barco, un animal, una
tarde de abril, un parque entero con la gente dentro— y no lo suelta.

Todo lo que hay ya ocurrió, y por eso no se mueve nada. Los huevos no: todavía
no han pasado. Mientras los lleves encima el sitio no sabe en qué año ponerte.

En el mapa conviven nueve procedencias: una carabela de 1537 encallada en la
plaza, los hornos de grasa de unos balleneros de 1841, el campamento de un
naturalista de 1888, una expedición de 1920 acampada en mitad de la calle
comercial, un avión de 1943, una estación de campo de 1971, el parque de 1994,
contenedores y placas solares de 2047, y monolitos de antes de todo.

## Los siete recintos

Anatomía paleontológica actual, no la de las películas. Cada animal es un
problema distinto, no el mismo con otra piel.

| # | Recinto | Especie | Cómo te encuentra |
|---|---|---|---|
| 1 | Valle del Tirano | *Tyrannosaurus rex* | Por el olfato — el desinfectante borra el rastro |
| 2 | Recinto de Manada | *Deinonychus* ×3 | Te flanquean — la bengala los junta |
| 3 | Jardín Húmedo | *Dilophosaurus* | Te alcanza en campo abierto — quédate en el escombro |
| 4 | El Aviario | *Pteranodon* | Cae en picado a cielo abierto — usa los pasillos techados |
| 5 | La Laguna | *Spinosaurus* | Por la onda del agua — vadea agachado o salta los islotes |
| 6 | El Pastizal | *Ankylosaurus* | Está ciego y lo oye todo — agachado no haces ruido |
| 7 | Ala Cerrada | *Therizinosaurus* | Nada lo distrae. Nació aquí y no tiene año |

## Reglas

- **Un huevo solo cuenta si logras sacarlo del recinto.** Al cogerlo suena la
  alarma y la compuerta empieza a cerrarse. Si te encierra dentro, devuélvelo al
  nido con `G` o no sales.
- No hay armas. Hay bengalas, señuelos acústicos y un táser de ganadería.
- Los animales no trepan. Subirse a algo es la única ruta que no siguen — pero
  los grandes tienen alcance de sobra.
- Morir no mata: el sitio te devuelve a la plaza. Los huevos asegurados siguen
  en la caja; el que llevabas encima vuelve a su nido.

## Los 21 documentos

Están tirados por el suelo, escritos por gente de siglos distintos que llegó
igual que tú. Diez enseñan a sobrevivir a un animal concreto; el resto cuenta
qué es este lugar.

Con **14 documentos** se desbloquea el mejor de los tres finales: emitir desde
la torre hacia todos los años a la vez, para que quien navegue cerca —en
cualquier año— entienda que esto no es un delirio de náufrago, sino un mapa.
