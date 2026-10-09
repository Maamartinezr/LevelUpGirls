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

## Autoría

María Alejandra Martínez Reverol

Proyecto desarrollado para la asignatura **Frontend I**.

Tienda ficticia: **Level Up Girls**.
