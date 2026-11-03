# Nemo

**Notas adhesivas gratuitas para el escritorio de Windows. Las notas se guardan al instante en este PC y, si inicias sesión, puedes usar las mismas notas en varios PC y en la web.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión coreana](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%207%20%2F%208%20%2F%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/nemo?lang=es)

![Pantalla de Nemo](images/nemo-en.png)

## Descripción general

Nemo te permite apuntar una idea en una nota y pegarla en el escritorio. Cada nota tiene un título y un cuerpo, y se guarda sola cuando dejas de escribir. Puedes dar a cada nota su propio color y fijarla por encima de las demás ventanas; su posición, tamaño y fijación vuelven tal cual la próxima vez que inicies Nemo.

Las notas se **guardan primero en este PC**, así que puedes usar Nemo sin iniciar sesión e incluso sin conexión a internet. Si inicias sesión con una cuenta de Kilho.net, tus notas se sincronizan con el servidor y puedes ver y editar las mismas notas en Nemo en tus otros PC y en [Web Memo](https://webmemo.kilho.net).

## Funciones

- **Notas en el escritorio** — las ventanas de nota no ocupan sitio en la barra de tareas ni en Alt+Tab, y se quedan en el escritorio al cerrar la ventana de lista.
- **Guardado automático** — la nota se guarda 3 segundos después de que dejes de escribir o al hacer clic en otro sitio. No hay botón Guardar.
- **Recuerda dónde la dejaste** — posición, tamaño, fijación y qué notas estaban abiertas se recuerdan y se restauran en el siguiente inicio.
- **6 colores** — Predeterminado · Amarillo · Verde · Azul · Morado · Rosa. En la lista, cada fila lleva el color de su nota, así se distinguen de un vistazo.
- **Siempre visible** — una nota fijada nunca queda oculta tras otras ventanas.
- **Búsqueda de notas** — la lupa de la ventana de lista busca en títulos y cuerpos.
- **Tu propio orden** — arrastra las notas en la lista para reordenarlas. El orden se aplica también en tus otros PC con sesión iniciada.
- **Atajo para nueva nota** — pulsa **Ctrl+Shift+N** desde cualquier programa para abrir una nota nueva. Puedes cambiar la tecla.
- **Funciona sin servidor** — iniciar sesión es opcional. Al cerrar sesión, las notas de este PC se quedan.
- **Sincronización entre PC y la web** — con la sesión iniciada, Nemo se sincroniza con el servidor 2 segundos después de guardar, cada 10 minutos o al pulsar **Sincronizar**. Si la misma nota se editó en dos sitios, no se descarta ninguna edición: se conservan ambas, una como **copia en conflicto**.
- **Inicio de sesión seguro con el navegador** — nunca escribes tu contraseña en Nemo. Inicias sesión con tu cuenta de Kilho.net en el navegador que ya usas (OAuth 2.0 + PKCE).
- **Emoji** — añade emoji en títulos y cuerpos.
- **22 idiomas** — sigue el idioma de visualización de Windows, o elige uno tú mismo en Configuración.

## Descarga / Instalación

| Tipo | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/nemo?lang=es) |
| Portable (ZIP) | [Descargar](https://down.kilho.net/nemo?lang=es&nosetup) |

En la primera instalación, el instalador activa **Ejecutar al iniciar**. Para la versión portable, descomprime el ZIP y ejecuta `Nemo.exe`. **Ejecutar al iniciar** solo está disponible en la versión instalada. La versión portable guarda tus notas en la misma carpeta que el programa, así que al mover la carpeta tus notas se mueven con ella.

## Uso

### Primeros pasos

1. Inicia Nemo. Se abre la ventana de lista y aparece el icono de Nemo en el área de notificación (bandeja).
2. Haz clic derecho en un espacio vacío de la lista o en el icono de la bandeja y elige **Nueva nota**. (También puedes pulsar **Ctrl+Shift+N** en cualquier momento.)
3. La nota nueva se abre con el campo de título listo. Escribe un título y pulsa **Enter** para pasar al cuerpo.
4. Escribe el cuerpo. Cuando dejas de escribir, la nota se guarda 3 segundos después y aparece en la lista.
5. Deja la nota en cualquier lugar del escritorio. Arrastra la barra de título para moverla y un borde para cambiar su tamaño.
6. Cuando termines, haz clic en la **✕** de la nota. Se guarda y se cierra. Para abrirla de nuevo, haz doble clic en ella en la lista.

### Distribución de la pantalla

**Ventana de lista**

| Elemento | Descripción |
|---|---|
| Lupa (barra de título) | Buscar notas. Busca en títulos y cuerpos; **ESC** la cierra |
| Engranaje (barra de título) | Configuración |
| ✕ (barra de título) | Oculta la ventana de lista en la bandeja. Nemo sigue funcionando |
| Lista de notas | Las notas nuevas aparecen arriba y puedes arrastrarlas para cambiar el orden. Cada fila tiene el color de su nota. **↑** y **↓** mueven la selección; doble clic para abrir la nota. La barra de desplazamiento solo aparece al pasar el ratón o al desplazarte |
| Barra de estado, izquierda | **Notas: n** |
| Barra de estado, derecha — icono de nube | Conexión con el servidor. Al pasar el ratón muestra **Guardado solo en este PC** · **Conectado al servidor (cuenta)** · **Última sincronización**; al hacer clic abre la página **Servidor** de Configuración |

**Ventana de nota**

| Elemento | Descripción |
|---|---|
| Barra de título | Arrástrala para mover la nota. Haz clic dos veces en el título o doble clic para renombrarla. Clic derecho para el menú de la nota |
| Chincheta | Activa o desactiva **Siempre visible**. Desactivada se muestra como una chincheta tachada |
| ✕ | Guardar y cerrar |
| Cuerpo | El texto de la nota. **Tab** inserta 4 espacios. La barra de desplazamiento solo aparece al pasar el ratón o al desplazarte |
| Bordes | Arrástralos para cambiar el tamaño |

**Menú contextual**

| Menú | Dónde | Qué hace |
|---|---|---|
| **Nueva nota** | Lista · Bandeja | Abre una nota en blanco |
| **Lista** | Bandeja (con la ventana de lista oculta) | Vuelve a mostrar la ventana de lista |
| **Editar** | Lista (sobre una nota) · Barra de título de la nota | Abre la nota / la renombra |
| **Eliminar** | Lista (sobre una nota) · Barra de título de la nota | Pregunta una vez y elimina |
| **Color ▸** | Lista (sobre una nota) · Barra de título de la nota | Elige uno de los 6 colores. Se guarda al momento |
| **Configuración** | Lista · Bandeja | Abre Configuración |
| **Kilho.net** | Lista · Bandeja | Página de presentación de Nemo |
| **Salir** | Lista · Bandeja | Pregunta una vez y cierra Nemo. Las notas abiertas vuelven en el siguiente inicio |

### Consejos para situaciones habituales

**Cuando se te ocurre algo en pleno trabajo**
Aunque estés en otro programa, pulsa **Ctrl+Shift+N** y aparece delante una nota nueva. Escribe un título, pulsa Enter, escribe el cuerpo y déjala: se guarda sola.

**Cuando quieres una nota siempre a la vista**
Haz clic en la chincheta de la nota para activar **Siempre visible**; las demás ventanas no la taparán. Vuelve a hacer clic para desactivarla. La fijación también se restaura en el siguiente inicio.

**Cuando tus notas quedan enterradas tras otras ventanas**
Haz clic izquierdo en el icono de Nemo de la bandeja para traer al frente todas las notas abiertas. La ventana de lista se queda donde está. Si no hay ninguna nota abierta, se abre la ventana de lista. Si necesitas la ventana de lista mientras hay notas abiertas, haz clic derecho en el icono de la bandeja y elige **Lista**.

**Cuando quieres ordenar las notas por tipo**
Decide un código de colores: amarillo para tareas, azul para trabajo, etc. Haz clic derecho en la barra de título de una nota o en una nota de la lista → **Color ▸**, y tanto la nota como su fila en la lista cambian de color al instante.

**Cuando quieres las notas que más usas arriba**
Pulsa sobre una nota de la lista y arrástrala hasta donde quieras. Si la arrastras al borde de la lista, esta se desplaza sola. El nuevo orden se guarda al instante y, si has iniciado sesión, la lista de tus otros PC sigue el mismo orden. Las notas nuevas se añaden arriba.

**Cuando tienes tantas notas que no encuentras una**
Haz clic en la lupa de la barra de título de la ventana de lista y escribe lo que buscas. Solo quedan las notas con ese texto en el título o el cuerpo. Pulsa **ESC** para cerrar la búsqueda y volver a ver toda la lista.

**Cuando solo quieres renombrar una nota**
Haz clic en el título de la nota y, un momento después, otra vez (igual que al renombrar un archivo en el Explorador de archivos), haz doble clic o haz clic derecho en la barra de título → **Editar**. **Enter** confirma y **Esc** recupera el título anterior. Hacer clic en otro sitio también conserva lo que escribiste.

**Cuando quieres sangrar texto en una nota**
Pulsa **Tab** en el cuerpo para insertar 4 espacios. Si lo pulsaste por error, un solo Ctrl+Z quita los 4.

**Cuando quieres quitar la lista de en medio pero conservar las notas**
Haz clic en la **✕** de la ventana de lista; pasa a la bandeja y tus notas se quedan en el escritorio. Para cerrar Nemo del todo, elige **Salir** en el menú de la bandeja.

**Las notas vuelven justo donde las dejaste**
Aunque apagues Windows o salgas de Nemo con notas abiertas, reaparecen en el mismo sitio y con el mismo tamaño la próxima vez que inicies Nemo. Si una nota quedara fuera de la pantalla porque cambió la configuración de monitores, se vuelve a colocar dentro de la pantalla.

**Cuando quieres ver tus notas cada vez que se enciende el PC**
Activa **Ejecutar al iniciar** en Configuración → **General** (con el instalador ya viene activado). Esta opción solo está disponible en la versión instalada; en la versión portable aparece atenuada. Al arrancar Windows, Nemo se inicia discretamente en la bandeja sin la ventana de lista, y solo aparecen en el escritorio las notas que dejaste abiertas.

**Cuando quieres las mismas notas en el trabajo y en casa**
En ambos PC, haz clic en **Iniciar sesión** en Configuración → **Servidor**. Se abre el navegador; inicia sesión con tu cuenta de Kilho.net y, cuando aparezca la página «Sesión iniciada», ciérrala y vuelve a Nemo. A partir de entonces las notas se sincronizan solas 2 segundos después de guardar y cada 10 minutos. Para sincronizar ahora mismo, haz clic en **Sincronizar**.

**Cuando estás lejos de tu PC**
Entra en [Web Memo](https://webmemo.kilho.net) con la cuenta que usas en Nemo para ver y editar las mismas notas. Los cambios que hagas en la web llegan a las notas de Nemo en la siguiente sincronización.

**Cuando la misma nota se editó en dos PC**
No se sobrescribe nada. Una versión queda como la nota original y la otra se convierte en una nota nueva con **(copia en conflicto)** al final del título. Compáralas, une lo que necesites en una y elimina la otra.

**Cuando ya tienes notas de antes de iniciar sesión**
Al iniciar sesión, las notas de este PC suben a esa cuenta y las notas del servidor bajan a este PC, todas en una sola lista. Si el PC se usó antes con otra cuenta, Nemo pregunta primero «Has iniciado sesión con otra cuenta. ¿Combinar las notas de este PC con esta cuenta?»; si eliges **No**, Nemo no inicia sesión.

**Cuando quieres dejar de sincronizar y guardar las notas solo en este PC**
Haz clic en **Cerrar sesión** en Configuración → **Servidor**. Las notas de este PC se quedan y la barra de estado cambia a **Guardado solo en este PC**. Las notas del servidor y de tus otros PC no se tocan.

**Cuando no tienes internet**
Las notas siempre se guardan primero en este PC, así que sigue usando Nemo como siempre. Cuando vuelvas a tener conexión, se suben al servidor en la siguiente sincronización.

**Cuando quieres otro atajo para nueva nota**
Haz clic en el cuadro **Atajo (nueva nota)** en Configuración → **General**; cambia a «Pulsa una tecla». Pulsa la combinación que quieras (por ejemplo Ctrl+Alt+M) y se aplica al momento. Si otro programa ya usa esa tecla, Nemo te avisa, así que elige otra.

**Cuando quieres llevar Nemo en una memoria USB**
Descomprime la versión portable en la memoria USB y ejecútala desde ahí. Las notas se guardan en la misma carpeta, así que se abren las mismas notas en cualquier PC donde la conectes.

**Cuando desinstalas y vuelves a instalar Nemo**
Desinstalar la versión con instalador no borra tus notas. Instala de nuevo y tus notas siguen ahí.

**Cuando apagas Windows**
Nemo nunca retrasa el apagado. Guarda las notas que estabas escribiendo y se cierra junto con Windows.

**Cuando vuelves a iniciar Nemo y no ves ninguna ventana**
Solo se ejecuta una copia de Nemo a la vez. Si lo inicias cuando ya está en marcha, la ventana de lista sale de la bandeja al frente.

## Configuración

Ábrela con el engranaje de la ventana de lista o con **Configuración** en el menú contextual. Los cambios se aplican al momento; no hay botón Aceptar.

| Página | Elemento | Valor predeterminado |
|---|---|---|
| General | Ejecutar al iniciar | Activado con el instalador (no disponible en la versión portable) |
| General | Atajo (nueva nota) | Ctrl+Shift+N |
| General | Idioma | Sistema (idioma de visualización de Windows) |
| Servidor | Cuenta — Iniciar sesión / Cerrar sesión | Sin sesión iniciada |
| Servidor | Sincronización — hora de la última sincronización, Sincronizar | Solo se muestra con la sesión iniciada |
| Acerca de | Versión · Autor · Sitio web · Licencias | — |

Con **Sistema**, el idioma sigue el idioma de visualización de Windows; elige uno de la lista y cambia en el acto. El árabe se muestra de derecha a izquierda.

## Requisitos

- Windows 7 · 8 · 8.1 · 10 · 11 (32 bits · 64 bits)
- Windows 7 necesita el Service Pack 1 (SP1) y las últimas actualizaciones de Windows.
- No necesita ningún runtime adicional.
- Solo para la sincronización con el servidor se necesitan conexión a internet y una cuenta de Kilho.net.

## Actualizaciones

Nemo **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; al pulsar **Sí** se abre la página de descarga y el programa se cierra. Las nuevas versiones se publican manualmente tras una verificación interna y se anuncian en la [página de Nemo](https://kilho.net/nemo). Consulte el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

## Licencia

Nemo es **freeware**. Puedes usarlo gratis en cualquier lugar —en la oficina, en casa, en organismos públicos o en la escuela— y redistribuirlo libremente.

## Enlaces

- Sitio web: <https://kilho.net/nemo>
- Página de Nemo: <https://nemo.kilho.net>
- Web Memo: <https://webmemo.kilho.net>
- Foro: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
