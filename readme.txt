Buenas prácticas: diseño
Hay algunas cosas a tener en cuenta al diseñar campañas de correo electrónico HTML.

-Los correos electrónicos deben tener un ancho máximo de 600-800 píxeles. Esto hará que se comporten mejor dentro del tamaño del panel de vista previa proporcionado por muchos clientes.
-Diseño para la simplicidad. Utilice capas basadas en cuadrículas y evite elementos complicados que requieren flotantes HTML o posicionamiento.
-Suponga que las imágenes serán bloqueadas inicialmente por clientes de correo electrónico, o que ciertas imágenes (imágenes de fondo, por ejemplo) no se cargarán por completo.
-No diseñe un correo electrónico que sea esencialmente una imagen grande y cortada. Si bien este tipo de correos electrónicos se ven bonitos, funcionan mal.
-Utilice fuentes básicas multiplataforma como Arial, Verdana, Georgia y Times New Roman.
-Evite los elementos que requieren Flash o JavaScript. Si necesita movimiento en un correo electrónico, un .gif es su mejor opción.
-¡No te olvides de la experiencia móvil! ¿Se puede leer su correo electrónico a distancia en una pantalla pequeña? ¿Las imágenes ralentizarán su tiempo de carga en un dispositivo móvil? ¿Sus enlaces son fáciles de presionar con un pulgar?
-Mejores prácticas: desarrollo

Al igual que con el diseño, hay buenas prácticas a seguir cuando se codifica el correo electrónico HTML.

-Codifique toda la estructura utilizando el elemento de tabla. Para diseños más complicados, debe anidar tablas para construir estructuras complejas.
-Use atributos de elementos (como relleno de celdas, valign y ancho) para establecer las dimensiones de la tabla. Esto obliga a una estructura de modelo de caja.
-Mantenga su CSS simple. Evite las declaraciones de estilo compuesto (IE: "font: # 000 12px Arial, Helvetica, sans-serif;"), código abreviado (IE: # 000 en lugar de # 000000), propiedades de diseño CSS (IE: ranura, posición, claro, visibilidad , etc.), selectores complejos (IE: selectores descendientes, secundarios o hermanos y pseudoelementos)
-Inline todos los CSS antes de enviarlos. (Mailchimp hará esto por usted automáticamente).
-Utilice solo enlaces absolutos para imágenes y aloje esas imágenes en un servidor confiable. (Mailchimp proporciona alojamiento gratuito de imágenes).
-No se moleste con JavaScript o Flash: esas tecnologías no son en gran medida compatibles con los clientes de correo electrónico.
-Tenga en cuenta la compatibilidad con dispositivos móviles, si es posible. Use consultas de medios para aumentar el tamaño del texto en pantallas pequeñas, proporcione áreas de impacto del tamaño del pulgar (~ 46x46px) para los enlaces. Haga que un correo electrónico responda si el diseño lo permite.
-Prueba, prueba, prueba. Cree cuentas de correo electrónico en varios servicios y envíese correos electrónicos a usted mismo. Haga esto junto con servicios como Litmus.