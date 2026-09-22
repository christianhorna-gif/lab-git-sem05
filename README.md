# Arena Breakout - Sitio Web Informativo

Página web informativa sobre el videojuego **Arena Breakout** (versiones Mobile y PC - Infinite), desarrollada como proyecto colaborativo para el **Laboratorio 5: Reto Integrador** (`lab-git-sem05`).

---

## 📝 Descripción del Proyecto

El sitio web recopila información esencial sobre el videojuego **Arena Breakout**:
* **Información General:** Fecha de lanzamiento, desarrollador (MoreFun Studios / Tencent Games) y concepto de juego táctico de extracción.
* **Características Clave:** Gestión de equipamiento, inventario y recursos.
* **Modos de Juego:** Modalidades como Todos contra Todos (4vs4), Carrera por el Botín, La Granja Botín, Valle Botín, entre otros.
* **Sección Visual:** Capturas y logotipos oficiales de las versiones Mobile y PC - Infinite.

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso / Función |
| :--- | :--- |
| **HTML5** | Estructuración y maquetación del contenido |
| **CSS3** | Estilos visuales (`style.css`), paleta oscura y diseño responsivo |
| **JavaScript** | Lógica e interacción dinámica (`script.js`) |
| **Git & GitHub** | Control de versiones, ramas, Issues, Pull Requests y Merges |
| **Markdown** | Documentación técnica e informe del proyecto (`README.md`) |

---

## 🎨 Aspecto Visual e Interfaz de la Página Web

La interfaz web presenta una estética **oscura y táctica** acorde a la temática militar y de extracción del videojuego:

* **Estructura en dos columnas:** 
  * **Barra lateral izquierda:** Muestra la galería de imágenes con las portadas oficiales para las plataformas **Mobile** y **PC - Infinite**.
  * **Panel principal:** Organizado en contenedores y tarjetas independientes con acentos de color amarillo/verde táctico para jerarquizar la lectura.
* **Secciones Informativas Claramente Definidas:**
  * **Información General:** Ficha técnica con fecha de lanzamiento global, desarrollador (*MoreFun Studios / Tencent Games*) y sinopsis temática.
  * **Características:** Resumen de mecánicas clave, sistema de equipamiento (armas, cascos, armaduras) y gestión de recursos en partida.
  * **Modos y Mapas:** Listas estructuradas que detallan las modalidades de juego (*4vs4, Carrera por el Botín, La Granja Botín*) y los mapas disponibles (*La Granja, La Cresta Norte, Valle, Armería, TV Station*).

---

## 💻 Descripción del Código y Arquitectura

El desarrollo sigue una arquitectura web limpia y modular distribuida en 3 archivos principales:

1. **`index.html` (Estructura de Contenido):**
   * Emplea etiquetas semánticas de HTML5 (`<header>`, `<main>`, `<aside>`, `<section>`, `<div>`) para organizar la información en módulos independientes.
   * Incorpora listas no ordenadas (`<ul>`, `<li>`) para presentar de forma clara los modos de juego y mapas.

2. **`style.css` (Diseño y Estilos):**
   * Aplica una paleta de colores oscuros (`#12181f`, `#1b232e`) inspirada en la interfaz original del videojuego.
   * Utiliza bordes y líneas decorativas verticales en color amarillo/dorado (`#e5a100`) para resaltar los títulos de cada sección.
   * Implementa **Flexbox** y **CSS Grid** para asegurar una distribución fluida entre la columna de logotipos y las tarjetas de información.

3. **`script.js` (Lógica Dinámica):**
   * Contiene funciones en JavaScript para gestionar eventos de usuario e interactividad en la página.

## 💻 Código Fuente del Proyecto

A continuación se presenta la estructura HTML principal (`index.html`) utilizada para la maquetación del sitio web:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arena Breakout</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>Bienvenido</header>

    <nav>
        <a href="[https://www.arenabreakoutinfinite.com/act/wand/pc-download1/index.html?media=google&network=x&campaign=24010452424&adgroup=&ad=&utm_source=google&utm_medium=google&utm_campaign=24010452424&utm_content=&utm_term=&gad_source=1&gad_campaignid=24001107072&gclid=CjwKCAjwq8PVBhAKEiwA2i3SHbNgSGqJUcj-wycATPCYTjh6Y_jk86C4nlKN_GVgBD2DKYTrwNniwBoCb6AQAvD_BwE&lang_type=en](https://www.arenabreakoutinfinite.com/act/wand/pc-download1/index.html?media=google&network=x&campaign=24010452424&adgroup=&ad=&utm_source=google&utm_medium=google&utm_campaign=24010452424&utm_content=&utm_term=&gad_source=1&gad_campaignid=24001107072&gclid=CjwKCAjwq8PVBhAKEiwA2i3SHbNgSGqJUcj-wycATPCYTjh6Y_jk86C4nlKN_GVgBD2DKYTrwNniwBoCb6AQAvD_BwE&lang_type=en)" target="_blank">Descargar</a>
    </nav>

    <article>

        <section class="info">
            <h2>Informacion</h2>

            <p><strong>Fecha de lanzamiento global:</strong> 14 de julio de 2023.</p>

            <p><strong>Desarrollador:</strong> MoreFun Studios, estudio de Tencent Games, China.</p>

            <p><strong>¿De qué trata?</strong> Arena Breakout es un videojuego de disparos táctico y de extracción. 
            Los jugadores exploran zonas de combate, buscan recursos y deben conseguir escapar 
            de la zona para conservar lo que encontraron.</p>

        </section>

        <section class="caract">
            <h2>Caracteristicas</h2>

            <p>
                Una de las principales diferencias de Arena Breakout es su enfoque
                táctico y de extracción. A diferencia de otros juegos de disparos,
                el jugador debe administrar cuidadosamente su equipamiento y los
                recursos que consigue durante cada partida.
            </p>

            <p>
                El juego cuenta con una gran variedad de armas, granadas y
                equipamiento. Los jugadores pueden utilizar diferentes tipos de
                armas, además de cascos, armaduras y otros elementos de protección
                para prepararse antes de entrar a una partida.
            </p>
            
        </section>
        <br>
        <section class="MyM">
            <h2>Modos y Mapas</h2>
             <p>
                <strong>Modos :</strong>
                <ul>
                    <li>Todos contra Todos ( 4vs4 )</li>
                    <li>Carrera por el Botin</li>
                </ul>
                Y mas modos que suelen salir con el paso de tiempo como :
                <ul>
                    <li>La Granja Botin</li>
                    <li>Valle Botin</li>
                    <li>La Cresta Norte Botin</li>
                </ul>
                Entre Otros
            </p>

            <p>
                <strong>Mapas :</strong>
                <ul>
                    <li>La Granja</li>
                    <li>La Cresta Norte</li>
                    <li>Valle</li>
                    <li>Armeria</li>
                    <li>TV Station</li>
                    <li>El Puerto</li>
                </ul>
            </p>

        </section>

    </article>

    <aside>
        <h2>Logos del Juego</h2>
        <br><br><br>
        <h3>Mobile</h3>
        <img src="[https://m.media-amazon.com/images/M/MV5BYTQ2YTNlNWQtOWU2OC00MjM3LThlMjAtMjMzMmUwMTY5NmQ4XkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg](https://m.media-amazon.com/images/M/MV5BYTQ2YTNlNWQtOWU2OC00MjM3LThlMjAtMjMzMmUwMTY5NmQ4XkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg)" alt="Logo de Arena Breakout Mobile">
        <br><br><br>
        <h3>PC - Infinite</h3>
        <img src="[https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbIK0cQ_mJoDXAgCNpsbVFjzg_LewJyn9p9qG79dfHmpfC7QrdImMwDwc&s=10](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbIK0cQ_mJoDXAgCNpsbVFjzg_LewJyn9p9qG79dfHmpfC7QrdImMwDwc&s=10)" alt="Logo de Arena Breakout PC(Infinite)">
    </aside>

    <footer>2026 -- Arena Breakout</footer>
    
</body>
</html>
```

## 🎨 Estilos Visuales (`style.css`)

Se ha diseñado una hoja de estilos CSS orientada a ofrecer una estética militar táctica, moderna y responsiva:

* **Paleta de Colores Táctica:** Fondo oscuro general (`#0d141a`) con variaciones de tonos para tarjetas (`#182532`, `#202b20`, `#273544`) y un color de acento dorado/amarillo (`#d49a18`) para botones y bordes decorativos.
* **Layout Flexbox:** Implementación de `display: flex` con reordenamiento mediante la propiedad `order` para ubicar el panel lateral (`aside`) a la izquierda (`order: 1`) y el contenido principal (`article`) a la derecha (`order: 2`).
* **Efectos Interactivos (Hover):** Transición suave (`transition: 0.3s`) y desplazamiento vertical (`transform: translateY(-5px)`) al pasar el cursor sobre las tarjetas informativas y el botón de descarga.
* **Indicadores Tácticos:** Pseudo-elementos `::before` para crear barras verticales doradas antes de cada título principal.

```css
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #0d141a;
    color: white;
    display: flex;
    flex-wrap: wrap;
}

header {
    width: 100%;
    background-color: #101820;
    color: white;
    text-align: center;
    padding: 30px;
    font-size: 32px;
    font-weight: bold;
    box-sizing: border-box;
}

nav {
    width: 100%;
    background-color: #273326;
    padding: 14px;
    text-align: right;
    box-sizing: border-box;
}

nav a {
    display: inline-block;
    background-color: #d49a18;
    color: black;
    text-decoration: none;
    padding: 12px 25px;
    border-radius: 6px;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    background-color: #e6ad2b;
    color: white;
    transform: translateY(-5px);
}

aside {
    width: 25%;
    box-sizing: border-box;
    padding: 45px 25px;
    text-align: center;
    background-color: #17252d;
    order: 1; /* Posiciona el aside a la izquierda */
}

aside h2 {
    margin-top: 0;
    margin-bottom: 35px;
    font-size: 28px;
}

aside h3 {
    margin-top: 30px;
    margin-bottom: 15px;
    font-size: 20px;
}

aside img {
    width: 230px;
    max-width: 100%;
    margin-bottom: 20px;
}

article {
    width: 75%;
    box-sizing: border-box;
    padding: 30px;
    order: 2; /* Posiciona el article a la derecha */
}

.info {
    background-color: #182532;
    padding: 35px;
    margin-bottom: 25px;
    min-height: 125px;
    box-sizing: border-box;
    position: relative;
    transition: 0.3s;
}

.info:hover {
    transform: translateY(-5px);
}

.info::before {
    content: "";
    position: absolute;
    left: 25px;
    top: 35px;
    width: 7px;
    height: 55px;
    background-color: #d49a18;
}

.info h2 {
    margin: 0 0 25px 25px;
    font-size: 28px;
}

.info p, .info ul {
    margin-left: 25px;
}

.caract {
    background-color: #202b20;
    padding: 35px;
    margin-bottom: 25px;
    min-height: 125px;
    box-sizing: border-box;
    position: relative;
    transition: 0.3s;
}

.caract:hover {
    transform: translateY(-5px);
}

.caract::before {
    content: "";
    position: absolute;
    left: 25px;
    top: 35px;
    width: 7px;
    height: 55px;
    background-color: #d49a18;
}

.caract h2 {
    margin: 0 0 25px 25px;
    font-size: 28px;
}

.caract p, .caract ul {
    margin-left: 25px;
}

.MyM {
    background-color: #273544;
    padding: 30px;
    margin-bottom: 20px;
    min-height: 125px;
    box-sizing: border-box;
    position: relative;
    transition: 0.3s;
}

.MyM:hover {
    transform: translateY(-5px);
}

.MyM::before {
    content: "";
    position: absolute;
    left: 25px;
    top: 30px;
    width: 7px;
    height: 55px;
    background-color: #d49a18;
}

.MyM h2 {
    margin: 0 0 25px 25px;
    font-size: 28px;
}

.MyM p, .MyM ul {
    margin-left: 25px;
}

.MyM ul {
    padding-left: 20px;
}

footer {
    width: 100%;
    background-color: #3d4348;
    color: white;
    text-align: center;
    padding: 18px;
    font-size: 17px;
    box-sizing: border-box;
    order: 3;
}

```

## ⚙️ Requisitos del Sistema

* **Navegador Web:** Google Chrome, Mozilla Firefox, Microsoft Edge o Brave.
* **Git:** Para clonación y gestión del repositorio local (opcional).
* **Editor de Código:** Visual Studio Code (opcional para revisión de código).

---

## 🚀 Instalación y Ejecución

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/christianhorna-gif/lab-git-sem05.git](https://github.com/christianhorna-gif/lab-git-sem05.git)

   ## 👥 Integrantes y responsabilidades

### 👤 Christian Horna — Líder y responsable de documentación
- Coordinación y organización del proyecto.
- Creación y gestión de las Issues del proyecto.
- Revisión de los cambios realizados por el desarrollador.
- Revisión y aprobación de los Pull Requests.
- Realización del Merge de los Pull Requests hacia la rama principal.
- Elaboración y actualización de la documentación del proyecto mediante el archivo `README.md`.
- Organización de la información necesaria para comprender el funcionamiento y estructura del proyecto.

### 👨‍💻 Ángel Anampa — Desarrollador
- Desarrollo de la estructura inicial de la página web.
- Implementación y actualización del contenido de la página sobre Arena Breakout.
- Incorporación de información sobre el juego, incluyendo:
  - Descripción del juego.
  - Modos de juego.
  - Armas.
  - Requisitos.
- Realización de commits con los avances del proyecto.
- Creación de Pull Requests para presentar los cambios realizados.
- Corrección y actualización de la página según las tareas asignadas.

## 🔄 Flujo de trabajo colaborativo

El proyecto se desarrolló utilizando Git y GitHub para organizar y controlar los cambios.

1. Se crearon Issues para definir las tareas del proyecto.
2. El desarrollador trabajó los cambios desde su rama.
3. Se realizaron commits para registrar los avances.
4. Se crearon Pull Requests para solicitar la incorporación de los cambios.
5. El líder revisó los Pull Requests.
6. Una vez revisados los cambios, el líder realizó el Merge hacia la rama principal.
7. Las Issues fueron cerradas después de completar las tareas correspondientes.


   ## 📋 Lista de Tareas y Estado del Proyecto

- [x] Crear el repositorio e integrar la estructura inicial.
- [x] Configurar hojas de estilos CSS y scripts dinámicos JS.
- [x] Diseñar e integrar la maquetación sobre Arena Breakout.
- [x] Gestionar ramas (*feature branches*) para cada integrante.
- [x] Registrar e integrar al menos 3 Issues.
- [x] Crear, revisar y fusionar los Pull Requests.
- [x] Redactar la documentación profesional en el `README.md`.

## 🔄 Flujo de Trabajo (Issues, Branches y Pull Requests)

El proyecto se desarrolló aplicando las directrices del laboratorio:

### 1. Registro de Issues

| Issue | Descripción | Estado |
| :---: | :--- | :---: |
| `#1` | Crear estructura inicial del sitio web | Closed |
| `#2` | Finalizar estilos e integrar funcionalidades básicas | Closed |
| `#3` | Agregar contenido informativo completo de Arena Breakout | Closed |

### 2. Pull Requests e Integración

| PR | Descripción | Rama Origen | Estado |
| :---: | :--- | :--- | :---: |
| `#4` | Crear estructura inicial de la página web | `feature/desarrollo-angel` | Merged |
| `#5` | Finaliza Issue 2 y actualiza index | `feature/desarrollo-angel` | Merged |
| `#6` | Finaliza Issue 3 | `feature/desarrollo-angel` | Merged |

## 👥 Autores y Roles

| Integrante | Usuario de GitHub | Rol en el Proyecto |
| :--- | :--- | :--- |
| **Christian Horna** | `@christianhorna-gif` | Líder de Proyecto & Documentación |
| **Angel Anampa** | `@AngelAnampa` | Desarrollador Front-End |