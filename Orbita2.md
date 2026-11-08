Órbita 2: sistema visual de Raidfinder
Enlaces:
Archivo de Figma	Mockups: https://www.figma.com/design/pfbZpsNycfUNI6r9t4LYah/Mockups?node-id=0-1&p=f&t=ripkeY2zCRBiFWJg-0
Prototipo Escritorio: https://www.figma.com/proto/pfbZpsNycfUNI6r9t4LYah/Mockups?node-id=22-10&p=f&t=ripkeY2zCRBiFWJg-0&scaling=min-zoom&content-scaling=fixed&page-id=3%3A8
Prototipo Móvil: https://www.figma.com/design/pfbZpsNycfUNI6r9t4LYah/Mockups?node-id=3-9&p=f&t=ripkeY2zCRBiFWJg-0
Proyecto de Google Stitch:	No se usó.


Dónde está cada cosa en Figma
Entregable	Página y sección del archivo
Inventario de decisiones: No tengo inventario de decisiones.
Wireframes rediseñados con sus notas	No están incluidos en "Mockups". Los wireframes de referencia están en App WoW Escritorio y App WoW Mobile. No los he rediseñado.
Componentes:	Página «Componentes» → «App WoW · Biblioteca de componentes». Incluye acciones y filtros, formularios, contenido, navegación, avatares, composición de grupo, conversación, solicitudes y valoraciones.
Mockups del happy path:	Páginas «Escritorio» y «Movil», pantallas 01–09.
Pantalla principal en el segundo ancho: 
Pantallas en modo oscuro:	Colección local «Tokens de color» → modos «Claro» y «Oscuro». Las páginas tienen modo seleccionable.
Guía de estilo: colecciones locales «Tokens de color», «Tipografias», «Espaciado» y «Radios».


Lista de comprobación de Figma
- [x] Variables en dos colecciones (primitivos y semánticos), con alias, modos claro y oscuro, ámbito, descripción y sintaxis de código.
- [ ] Estilos de texto, efecto y retícula vinculados a las variables.
- [x] Componentes con Auto layout, variables, propiedades y variantes de estado.
- [x] Mockups construidos enteros con Auto layout y espacios sacados de variables.
- [ ] Pantalla principal en un segundo ancho, con los mismos componentes.
- [x] Modo oscuro aplicado con el selector de modo.
- [x] Prototipo que recorre el happy path completo.
- [x] Prueba 1 superada: al cambiar color/primary, cambian todas las pantallas a la vez.
- [x] Prueba 2 superada: con todos los mockups en modo oscuro, nada desaparece contra el fondo.
Resumen de decisiones
Rediseño de los wireframes
No he rediseñado los wireframe ya que mis mockups son prácticamente iguales en estructura.

Color
El color principal es azul petróleo #072E3B; el acento secundario es arena #C6AF8D. El primero identifica navegación y acciones principales; el segundo da un acento cálido a bordes y selecciones. Los fondos base son #F7F7F7 y blanco en claro, y #101B20 y #18282D en oscuro.

Contraste medido en textos de interfaz:
- Claro: Text/Muted #788484 sobre Background/Canvas #F7F7F7
- Oscuro: Status/Success #52C2AE sobre Background/Success #173A34

Tipografía
Se usa Inter en Regular, Medium, Semi Bold y Bold. La colección «Tipografias» incluye Inter para familia y estilos primario y de título. Se mantiene una sola familia para dar consistencia a textos de interfaz y datos compactos.
Espaciado y retícula
La escala parte de 4 px, con tokens de 4, 8, 12, 16 y 24 px. Los radios disponibles son 6, 8, 12 y 999 px.

La pantalla móvil principal usa un ancho de 390 × 844 px y márgenes laterales de 18 px. En escritorio, los mockups miden 1440 × 900 px, con márgenes de 40 px y una separación de 30 px entre el panel lateral y el contenido.
Componentes
La biblioteca contiene estos conjuntos y variantes:
- Botón: primario/secundario y compacto/regular.
- Campo de texto: predeterminado, foco y error.
- Chip de filtro: seleccionado y predeterminado.
- Tarjeta de raid: escritorio y móvil.
- Navegación superior: escritorio y móvil.
- Navegación inferior: Inicio, Crear, Chat y Perfil activos.
- Avatar: pequeño y mediano.
- Slot de grupo: escritorio/móvil, tanque/sanador/DPS y vacío/asignado.
- Mensaje de chat: otra persona y propio.
- Solicitud de grupo: escritorio y móvil.
Responsive y modo oscuro
La pantalla principal se adaptó de 1440 × 900 a 390 × 844 px con variantes de navegación y tarjetas, y una presentación móvil en una sola columna. La escala de espaciado se mantiene entre ambos tamaños.

Para el modo oscuro se vincularon fondos, superficies, textos, bordes y colores de estado a la colección «Tokens de color». También se añadieron tokens semánticos para roles, avisos, éxito y especialización, y se ajustaron varios colores de texto para que mantuvieran contraste sobre fondos oscuros.

Uso de IA

He usado la IA generativa de Gemini (nano banana) para hacer imágenes de como sería mi web terminada para tener una orientación a la hora de hacer los mockups, también he usado ChatGPT para solucionar dudas sobre figma y hacer algunos cambios con su integración. También me pudo solucionar algún error mediante la conexión a figma.

Lo que ha quedado pendiente

Me ha quedado pendiente añadir algunos iconos e imagenes ya que no los encontraba a buena resolucion o vectoriales, son iconos e imagenes especificos de world of warcraft y solo los he encontrado de pago. Seguiré buscando la manera de conseguir esos iconos de forma gratuita.
