Qué se resolvió

Hice los 20 ejercicios, desde lo más básico (estructura HTML, listas, tablas) hasta lo más avanzado (grid, animaciones, formulario multi-step y la landing final que integra todo)

Ejercicio 1 al 7: nivel básico (estructura, listas, tablas, formulario, primeros estilos, selectores, box model)

Ejercicio 8 al 14: nivel intermedio (flexbox, grid, pseudo-clases, posicionamiento, formulario estilizado, variables CSS)

Ejercicio 15 al 20: nivel más avanzado (responsive, animaciones, menú hamburguesa sin JS, grid tipo mosaico, formulario multi-step, landing page integradora)4

Algunas decisiones que tomé
En el ejercicio 1 usé una imagen real (de Unsplash) con su alt en vez de un placeholder, para practicar el atributo de accesibilidad con un caso más real.

En los ejercicios 9 y 18 (las galerías) también usé imágenes de Unsplash para que se sienta más parecido a un catálogo real y no algo vacío.

En el ejercicio 14 definí las variables CSS (--color-primario, --color-secundario, etc.) en :root y las reutilicé para armar una versión "modo oscuro" simple, cambiando solo esas variables.

En el ejercicio 17 el menú hamburguesa lo resolví con el truco del checkbox oculto (:checked) y su <label> asociado, sin usar JavaScript, tal como pedía la consigna.

En el ejercicio 19 el paso entre las dos secciones del formulario lo hice con anclas (#paso1 / #paso2) y validación nativa de HTML (:required, pattern, minlength), también sin JS.

Para el ejercicio 20, el integrador, no quise dejarlo genérico así que le inventé una marca ("Groove Discos", una tienda de vinilos) y armé la landing completa: navbar fija con scroll suave, hero con imagen de fondo, sección de servicios en grid, testimonios y formulario de contacto, todo junto con variables CSS y una animación.

Con qué está hecho

HTML5 semántico y CSS3 puro (flexbox, grid, variables, media queries, keyframes). Sin frameworks y sin JavaScript, salvo en los ejercicios donde la consigna explícitamente pedía resolver todo solo con CSS (como el menú hamburguesa).
