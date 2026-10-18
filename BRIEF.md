# Brief del Proyecto: RaidFinder Classic

## 1. El Problema

Buscar gente para hacer raids en **WoW Classic** cuando no tienes una **guild fija** es un dolor de cabeza y te hace perder muchísimo tiempo:

* **Estar spameando o mirando el chat cansa:** El buscador del propio juego y el chat de comercio/LFG van lentos y es normal tardar entre **45 minutos y 2 horas** solo para montar un grupo.
* **Te funde el tiempo de juego:** Si solo tienes **hora y media o dos horas** para jugar por la noche, pasarte una hora buscando gente hace que se te vaya la mitad de la sesión a la basura sin haber pisado la raid.
* **No sabes con quién vas a jugar:** No sabes si la gente habla tu idioma, si van equipados de verdad o si se van a marchar a mitad de la raid (se cagan), lo que hace que muchísimos grupos se acaben rompiendo a la primera de cambio.

## 2. Personas (Nuestros User Persona)

### Alexis (20 años, Estudiante)
* **Su situación:** Juega bastante (unas **15 horas a la semana**) y hace raids **2 o 3 veces por semana**, pero juega solo.
* **Cuándo juega:** De **21:00 a 23:00**.
* **Lo que necesita:** Dejar el grupo reservado antes de cenar o conectarse para que a las **21:00** ya esté todo listo y no pierda sus **2 horas** buscando en el chat.

### Yoselin (34 años, Camarera y madre)
* **Su situación:** Anda muy pillada de tiempo (**6-8 horas a la semana**) y como mucho hace **una raid a la semana**. No puede meterse en horarios fijos de hermandad.
* **Cuándo juega:** De **22:30 a 00:00**, cuando la hija se duerme.
* **Lo que necesita:** Entrar a la web, apuntarse a un hueco que falta en un grupo que empiece ya y ponerse a jugar. Si tarda más de **20 minutos** en encontrar gente, apaga el ordenador.

## 3. Qué va a tener el MVP (Lo mínimo para que funcione)

El objetivo del **MVP** es poder buscar grupo, apuntarse, que el líder organice los huecos y podáis hablar antes de entrar al juego:

### Cuentas y Personajes:
* **Registro e inicio de sesión.**
* Poder guardar tus personajes (el principal y los **alters**) con su **nombre**, **nivel**, **raza**, **clase**, **rol** (tanque, healer, DPS), **profesiones** y su **nivel de equipo**.

### Página Principal y Buscador:
* Lista de raids creadas con filtros por **mapa** (Molten Core, Onyxia, etc.), **idioma** y **hora**.
* Ver de un vistazo cuánta gente hay dentro, a qué hora salen y qué idioma hablan.

### Detalle de la Raid y Plantilla del Líder:
* Pantalla para ver quién está ya metido en el grupo y qué roles faltan.
* **Plantilla visual de 20 o 40 huecos** para que el líder configure exactamente qué clases y roles necesita.
* Lista de solicitudes pendientes para que el líder **acepte o rechace** a la gente.

### Chat y Sistema de Reseñas:
* **Chat en tiempo real** dentro del grupo para hablar antes de la raid y ver el link de **Discord**.
* Poder valorar a los compañeros al terminar con **estrellas** y **etiquetas simples** (Buen DPS, Puntual, Tóxico, etc.).

## 4. Cómo sabremos si la web funciona (Criterios de Éxito)

Para ver si de verdad arreglamos el problema a Alexis y Yoselin, comprobaremos estos puntos:

* **Ahorrar tiempo a Yoselin:** Que tardemos menos de **10 minutos** en encontrarle un grupo aceptado, para que pueda aprovechar casi toda su hora y media de juego.
* **Asegurar la partida a Alexis:** Que más del **70%** de la gente que apunte su personaje un par de horas antes de su horario empiece la raid justo a tiempo.
* **Evitar la gente tóxica:** Que la nota media de las raids creadas en la web sea mayor de **4.2 sobre 5** y que menos del **10%** de los grupos se rompan a la mitad.

## 5. Limites y Restricciones del Proyecto

### Restricción de peso de la web (Eco-diseño / Criterio W3C WSG 2.4):
* La web no va a pesar más de **1.5 MB** en total por página.
* Comprimiremos las imágenes a formatos ligeros (**WebP/AVIF**) y limpiaremos el código para que cargue en menos de **2 segundos**, pensando en gente como Yoselin que se conecta desde el portátil con el Wi-Fi de casa un poco lejos y no puede estar esperando a que cargue una web pesada.

### Solo versión Web:
* Estará pensada para usar en el ordenador mientras tienes el **WoW abierto de fondo**, sin consumir mucha memoria RAM.
* **No utilizaremos addons** dentro del juego para este primer MVP, todo se gestiona desde la web.
