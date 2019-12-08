## Práctica Fundamentos web

### Propuesta diseño

Basándome en una noticia del medio irónico El Mundo Todya, he diseñado el portal **FLETNIX** (la primera plataforma para disléxicos).

### Maquetación
He utilizado la forma de trabajo mobile first, en los que he ido añadiendo primero las propiedades en vista móvil para ir progresivamente ensanchando la pantalla para cuadrar los elementos lo mejor posible. 

La disposición de las tarjetas de las películas se han resuelto mediante el uso de display: grid y display: flex.

El hover de la tarjeta para mostrar información de la película o serie se ha tomado en cuenta para pantallas tipo dekstop y en el caso de dispositivo tipo tablet y móvil lo he resuelto dejando dicha información visible. 

### Estilos
He usado una única hoja de estilos *(style.css)* para en ella ir cargando los diferentes estilos que componen la web. En este caso, he optado por dividir el árbol de archivos por secciones y componentes para poder hacerla lo más reutilizable posible. 

### Interacción
Las interacciones han usado efectos únicamente con css, por lo tanto, por ejemplo en la ficha de la película, el botón de play desaparecería usando JS y cuando se hiciera click en él automáticamente comenzaría la reproducción de la película y el botón desaparecería. 
Al igual que en los iconos para marcar si una peli o serie es favorita, he simulado cómo quedaría si se marca una como tal. 

### Propósito del tema elegido
Espero no molestar con el tema elegido así como con las imágenes, que son totalmente fake y para el uso de pruebas así como los textos lorem ipsum. Me pareció una noticia graciosa y me imaginé cómo sería su web.