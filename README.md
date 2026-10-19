# 🧩 UparPuzzle Studio

**UparPuzzle Studio** es una aplicación web interactiva y de archivo único (*single-file*) para diseñar, resolver e imprimir **Sopas de Letras** y **Crucigramas** de forma algorítmica. Pensada especialmente para docentes, estudiantes y creadores de contenido educativo que buscan generar material didáctico listo para el aula o para resolver en pantalla.

---

## ✨ Características Principales

### 1. Dos Modos de Juego y Creación
* **Sopa de Letras:**
  * Tamaño de cuadrícula configurable (`10×10`, `12×12`, `15×15`, `18×18`) con ajuste automático según la longitud de las palabras.
  * Control de direcciones permitidas: Horizontal (`→`), Vertical (`↓`), Diagonal (`↘ ↗`) e Invertidas (`← ↑`).
  * Selección interactiva con ratón (arrastrar o clic inicio-fin) y soporte táctil para pantallas móviles o tableros digitales.
* **Crucigrama Inteligente:**
  * Algoritmo de entrelazamiento automático que evalúa múltiples disposiciones para lograr la mayor cantidad de cruces y la cuadrícula más compacta[cite: 1].
  * Resolución interactiva con teclado, navegación con flechas, cambio de orientación (`Horizontal`/`Vertical`) mediante clic, botón **Girar** o barra espaciadora[cite: 1, 4].
  * Herramientas de ayuda en pantalla: **Comprobar Letras** (marca aciertos en verde y errores en rojo) y **Dar Letra** (revela la casilla activa)[cite: 1].

### 2. Gestión de Palabras (Individual y por Lotes)
* **Modo Individual:** Añade palabras una por una con su respectiva pista o definición[cite: 1].
* **Modo Pegar Lista (Carga Masiva):** Pega listas completas de palabras separadas por salto de línea. Soporta detección automática de separadores (`:`, `-`, `;`, `|`) para incluir la pista del crucigrama al instante, o permite pegar únicamente las palabras para agregar las pistas más tarde.
* **Edición en Vivo:** Modifica cualquier pista directamente desde la lista lateral sin perder el progreso actual del tablero[cite: 1].
* **Plantillas Predefinidas:** Incluye 4 categorías listas para usar (*Astronomía*, *Naturaleza*, *Tecnología* y *Geografía*) tanto en Español como en Inglés[cite: 1].

### 3. Almacenamiento Local y Portabilidad (`localStorage` + JSON)
* **Actividades Guardadas:** Guarda tus actividades directamente en el navegador conservando el título, la lista de palabras, las pistas y la disposición exacta generada tanto para la sopa de letras como para el crucigrama[cite: 2].
* **Buscador y Paginación:** Filtra rápidamente tus actividades por nombre o contenido y organiza listas extensas con paginación dinámica (`5`, `10`, `15`, `50` o `Todas`).
* **Exportar e Importar (`.json`):** Descarga copias de seguridad completas de tus actividades para compartirlas o abrirlas en cualquier otro computador sin perder ningún ajuste[cite: 2].

### 4. Impresión Optimizada y Exportación a Imagen
* **Impresión / PDF Nativa:** Hoja de estilos `@media print` dedicada que oculta los paneles de edición, añade encabezado formal (*Nombre* y *Fecha*) y muestra todas las pistas completas sin recortes de texto[cite: 1].
* **Descarga en Imagen PNG:** Renderizado directo en HTML5 Canvas en alta resolución (`1200px` de ancho con ajuste dinámico de altura y *word-wrap* automático en las definiciones), ideal para insertar en guías de Word, presentaciones o compartir digitalmente[cite: 1].

### 5. Personalización de Interfaz
* **Bilingüe (ES / EN):** Cambio instantáneo de idioma entre Español e Inglés en toda la interfaz, plantillas e impresiones.
* **Tema Claro / Oscuro:** Modo oscuro nativo con persistencia en el navegador para trabajar cómodamente en cualquier entorno de iluminación.

---

## 🚀 Cómo Usar

El proyecto no requiere instalación de dependencias ni servidores complejos.

1. Clona este repositorio o descarga el archivo `index.html`[cite: 1]:
   ```bash
   git clone [https://github.com/kevinluisfl/uparpuzzle.git](https://github.com/kevinluisfl/uparpuzzle.git)
