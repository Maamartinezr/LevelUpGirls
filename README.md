# Level Up Girls - Ecommerce Gamer

**Level Up Girls** es un sitio web e-commerce desarrollado para una tienda gamer dirigida principalmente a mujeres, niñas y adolescentes interesadas en videojuegos, accesorios, merchandising y productos para setup gamer.

El proyecto fue construido como parte de la Evaluación Final Transversal de Frontend I, utilizando como base el avance previo del sitio PixelVault y adaptándolo a una nueva identidad visual, contenido comercial y experiencia de usuario.

## Concepto del sitio

Level Up Girls busca funcionar como una tienda gamer moderna, cercana e inclusiva. La propuesta visual combina una estética tecnológica con colores neón, manteniendo una identidad femenina sin caer en un diseño infantil o poco profesional.

El sitio utiliza una paleta basada en:

- Negro para header, footer y secciones de contraste.
- Blanco y tonos claros para legibilidad.
- Fucsia neón para llamadas a la acción.
- Azul turquesa para elementos destacados.
- Morado para acentos visuales y detalles de interfaz.

## Tecnologías utilizadas

El proyecto fue desarrollado con:

- HTML5
- CSS3
- JavaScript
- React
- Vite
- Bootstrap 5
- Fetch API
- LocalStorage

## Funcionalidades principales

El sitio incluye:

- Header fijo con navegación principal.
- Barra buscadora funcional.
- Hero principal con imagen de inicio y botones de acción.
- Carrusel de 5 imágenes rotativas.
- Imágenes del carrusel clickeables según categoría.
- Sección de productos destacados.
- Oferta de la semana.
- Catálogo de productos con filtros.
- Últimos lanzamientos cargados dinámicamente.
- Carrito de compras interactivo.
- Formulario de contacto con validación.
- Footer con iconos de redes sociales.
- Diseño responsivo para escritorio, tablet y móvil.

## Comportamiento de la búsqueda

La barra buscadora del menú permite buscar productos presentes en el sitio.

Si el término pertenece a un producto del catálogo, la página baja al catálogo y muestra los resultados correspondientes.

Si se escribe una palabra relacionada con ofertas, por ejemplo:

- oferta
- ofertas
- pack
- descuento
- gift card

la página redirige directamente a la sección **Oferta de la semana**.

Si se busca un producto relacionado con los últimos lanzamientos, la página redirige a la sección **Últimos lanzamientos**.

## Categorías del sitio

El sitio trabaja con las siguientes categorías:

- Videojuegos
- Accesorios Gamer
- Merchandising
- Setup Gamer
- Ofertas

Las categorías del carrusel y del mosaico visual funcionan como accesos rápidos.

Al hacer clic en:

- **Videojuegos**, se filtra el catálogo por videojuegos.
- **Accesorios Gamer**, se filtra el catálogo por accesorios.
- **Merchandising**, se filtra el catálogo por productos de merchandising.
- **Setup Gamer**, se filtra el catálogo por productos de setup.
- **Ofertas**, se redirige a la oferta de la semana.

## Carrito de compras

El carrito permite:

- Agregar productos.
- Aumentar o disminuir cantidades.
- Quitar productos.
- Vaciar el carrito.
- Ver cantidad total de productos.
- Calcular subtotal.
- Mostrar descuento agregado.
- Calcular envío.
- Mostrar total final.

Además, el carrito utiliza **LocalStorage**, por lo que conserva los productos agregados aunque la página se actualice.

## Uso de Fetch API

El catálogo y los lanzamientos se cargan desde archivos JSON locales:

```text
public/assets/data/catalogo.json
public/assets/data/lanzamientos.json
```

Esto permite mostrar datos dinámicos en la aplicación y cumplir con el requisito de carga externa mediante Fetch API.

## Estructura del proyecto

```text
VideoGameWeb_EFT9/
│
├── index.html
├── package.json
├── README.md
├── vite.config.js
│
├── src/
│   ├── App.jsx
│   └── main.jsx
│
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── data/
│   │   ├── catalogo.json
│   │   └── lanzamientos.json
│   └── img/
│       └── imagenes del sitio
│
├── public/
│   └── assets/
│       ├── data/
│       └── img/
│
├── dist/
│   └── version compilada por Vite
│
└── Sitio_para_GitHub_Pages/
    └── archivos listos para publicar en gh-pages
```

## Ejecución local

Para ejecutar el proyecto en el computador:

1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Abrir una terminal dentro de la carpeta raíz.
3. Instalar dependencias:

```bash
npm install
```

4. Ejecutar el servidor de desarrollo:

```bash
npm run dev
```

5. Abrir el enlace que muestra Vite en la terminal.

Normalmente será:

```text
http://localhost:5173/
```

## Compilar el proyecto

Para generar la versión final del sitio:

```bash
npm run build
```

Esto crea la carpeta:

```text
dist/
```

Esa carpeta contiene el sitio optimizado para publicación.

## Publicación en GitHub Pages

Para publicar el sitio en GitHub Pages se debe usar la carpeta:

```text
Sitio_para_GitHub_Pages/
```

Dentro de esa carpeta se encuentran los archivos ya preparados para subir a la rama `gh-pages`.

La estructura correcta en la rama `gh-pages` debe ser:

```text
gh-pages/
│
├── index.html
└── assets/
```

Es importante que `index.html` quede directamente en la raíz de la rama `gh-pages`.

No debe quedar dentro de una carpeta adicional como:

```text
gh-pages/Sitio_para_GitHub_Pages/index.html
```

## Objetivo académico

Este proyecto demuestra el uso de:

- Componentes funcionales en React.
- Manejo de estado con `useState`.
- Efectos secundarios con `useEffect`.
- Renderizado condicional.
- Carga de datos con Fetch API.
- Interactividad con eventos.
- Diseño responsivo con Bootstrap y CSS personalizado.
- Organización de archivos para un sitio frontend.
- Publicación mediante GitHub Pages.

## Autoría

Proyecto desarrollado para la asignatura **Frontend I**.

Tienda ficticia: **Level Up Girls**.
