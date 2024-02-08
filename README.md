README.txt

¡Bienvenido al repositorio de E-COMERCE URAEUS - Ropa deportiva para gente común! Aquí encontrarás el código fuente y los archivos necesarios para el desarrollo y mantenimiento de nuestro sitio web de comercio electrónico CampusShop

Estructura de la página web
El sitio web está organizado de la siguiente manera:

index.html: Página principal que muestra 12 imagenes de productos de 3 categorias diferentes; Abrigos, Camisetas y Pantalones. Al hacer clic en cada imagen, se redirige a la página de descripción del producto correspondiente.

Otras Paginas:

Ademas del index, se encuentran las paginas de cada categoria; Abrigos.html, Camisetas.hmlt y Pantalones.hyml. Se encuentras paginas de carritos de compra; Carrito.html (prductos seleccionados), Carrito-Vacio.html (muestra el carrito vacio), Carrito-2.html (confirmacion de compra)
y detalle-producto.html (que muestra mas informacion de cada producto y campusShop.html (que muestra el menu de las categorias para la version movil para la version movil)
)
CSS: Existen un archivo CSS para las categorias de productos, llamada style.css, un archivo CSS para los carritos, llamada style2.css, un archivo CSS para el detalle del producto, llamada style3.css y un archivo CSS para el menu, llamada style4.css
en las que se dio formato grid y flex, así como animaciones y funciones de media query.

style.css: Archivo css de las categorias.
  - A traves de la regla grid-template se le da el formato de grid (grilla) al contenido del <body> con 2 columnas. En la primer columna se ubica el dashboard de las categorias y productos y en la segunda columna se ubica el contenido principal

  - A traves de la regla grid-template se le da el formato de grid (grilla) al contenido principal <main> con 2 filas y las columnas que sean necesarias segun los elementos que hay con el atributo repeat(auto-fit) y se le da un tamaño maximo y minimo a los elementos
    a traves del atributo minmax(275px, 1fr); el atributo repeat(auto-fit) tambien nos permite darle responsividad a la pagina ajustando el ancho de las columnas a diferentes anchos de pagina

  - De manera general se aplican reglas padding, background-color, color, border, border-radius para darle estilos al contenido y precisar mejor la ubicacion de los distintos elementos

  - Se aplica una animacion llamada imagen al momento de hacer :hover sobre las imagenes de los productos en la cual se escala la imagen a 1.5, se le da una inclinacion y se generan bordes de colores al rededor de la imagen

  - Se aplica un media query para ajustar la rersponsividad de la pagina para moviles en donde se hace invisible el dashboard a traves de display: none, para darle prioridad a las imagenes y por consiguiente aparece un icono de menú que redirige al usuario a la navegacion
    de las categorias.

style2.css, style3.css, style4.css

  -  Se aplica un media query para ajustar la rersponsividad de la pagina para moviles en donde se hace invisible el dashboard a traves de display: none, para darle prioridad a las imagenes y por consiguiente aparece un icono de menú que redirige al usuario a la navegacion
     de las categorias.

Tecnologías utilizadas El sitio web se desarrolló utilizando las siguientes tecnologías:

HTML5: Para la estructura y contenido de las páginas web. CSS: Para la presentación y estilos de las páginas. Media queries, Grid y Flexbox: Utilizados para hacer que el diseño de la página sea responsivo y adaptable a diferentes dispositivos y tamaños de pantalla.

USO DE LA PAGINA

Navegación y Exploración de Productos

Página Principal (index.html): Al acceder a la página principal, los usuarios encontrarán las imagenes de todos los productos. Estas imágenes están enlazadas a las páginas individuales de cada producto, donde los usuarios pueden obtener más detalles y realizar compras.

Dashboard (Abrigos, Camisetas y Pantalones): En el dasboard el usuario puede navegar en cada categoría donde se muestran los productos disponibles en esa categoría. Los usuarios pueden explorar los productos y hacer clic en cada uno para ver más detalles.

Detalles del Producto

Páginas de Producto (detalle-producto): Cada producto muestra una página donde se muestran detalles adicionales, como descripciones, características, precios y opciones de compra. Los usuarios pueden agregar el producto al carrito de compra desde esta página.

Carrito de Compra

Página de Carrito de Compra (carrito, carrito-2 y carrito-vacio): Los productos seleccionados por el usuario se muestran en esta página, junto con sus precios.


Responsividad

La página web está diseñada con técnicas de diseño responsivo utilizando CSS Grid, Flexbox y Media Queries. Esto garantiza una experiencia de usuario óptima en una variedad de dispositivos y tamaños de pantalla, desde teléfonos móviles y tabletas hasta computadoras de escritorio.

Experiencia de usuario

Exploración de Productos: Los usuarios navegan por las categorías y productos disponibles en el sitio.

Selección de Productos: Los usuarios seleccionan los productos que desean comprar y los agregan al carrito de compra.

Revisión del Carrito: Los usuarios revisan los productos seleccionados y proceden al pago.

NOTA: Los botones de - agregar y comprar - aun no son interactivos y no cumplen funciones en tiempo real. Están dispuestos allí a manera de ejemplo visual. Se espera seguir dando actualización para hacer mas robusta la página y hacer que estos botones sean funcionales.

¡Esperamos que esta guía te ayude a disfrutar de tu experiencia de compra en E-COMERCE URAEUS - Ropa deportiva para gente común! Si tienes alguna pregunta o necesitas asistencia adicional, no dudes en contactarnos. ¡Gracias por elegirnos!
