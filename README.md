# Proyecto: Laboratorio1 - Cybertruck Landing Page

## Descripción
Esta es una página web responsiva para promocionar el Cybertruck, con información sobre sus características, dimensiones, cobertura de envío y planes de entrega.
La estructura sigue las mejores prácticas de accesibilidad y diseño semántico para ofrecer una experiencia inclusiva a todos los usuarios.


## Estructura Semántica
El código HTML utiliza etiquetas semánticas para mejorar la accesibilidad y la legibilidad del contenido:


### 1. **`<header>`**
El encabezado contiene:
- Un **`<nav>`** para la navegación principal.
- Un logo en formato SVG.
- Un banner promocional con llamada a la acción (CTA) para pedir o agendar una prueba.

**Justificación:** Define claramente la sección superior de la página, accesible para lectores de pantalla y motores de búsqueda.

### 2. **`<main>`**
Incluye el contenido principal del sitio:
- **`<article>`** para presentar información detallada sobre el producto y sus dimensiones.
- **`<section>`** para áreas de cobertura y tipos de envío.

**Justificación:** Permite a los lectores de pantalla identificar el contenido central de la página, separando las distintas áreas de información.

### 3. **`<footer>`**
Contiene:
- Información de contacto.
- Enlaces importantes (términos y condiciones, política de privacidad).
- Redes sociales y un mensaje de misión.

**Justificación:** Marca el final de la página y proporciona enlaces adicionales y datos de contacto para el usuario.

## Accesibilidad
Se han aplicado las siguientes pautas de accesibilidad:
- Todas las imágenes incluyen el atributo **`alt`**.
- Se ha seguido un orden lógico del contenido para una mejor lectura por lectores de pantalla.
- Uso de roles ARIA específicos:
  - `role="banner"` para el encabezado.
  - `role="main"` para el contenido principal.
  - `role="contentinfo"` para el pie de página.

## Tecnologías Utilizadas
- **HTML5**
- **CSS3**
- **Google Fonts**

## Detalles CSS
- Alineamiento y Posicionamiento de Elementos : Se uso la tecnica FlexBox
- Dimensiones: Se priorizaron las unidades relativas (rem,%)
- Nombres descriptivos a las clases o id de los elementos HTML para mayor facilidad de identificacion en CSS

## Breakpoints de Media Queries
En el código CSS, se busco aplicar unicamente dos breakpoints, uno para celulares y otro para tables, pero conforme se visualizaba la disposicion de cada parte de la estructura html (sections,divs,etc), se aplico a ciertas partes otros reakpoints adicionales siguiendo lo siguiente:

### 📱 **Celulares (≤ 480px)**
Se aplican estilos específicos cuando el ancho de la pantalla es de 480 píxeles o menos:
- `.nav-links`: Se organizan en columna y aumentan el tamaño de fuente.
- `.buttons`: Se centran y agrandan.
- `.product-info`: Se ajusta al 90% del ancho disponible.
- `.product-dimensions`: Se organizan en columna.
- `.gallery-product > img`: Se expanden a un 80% del ancho.
- `.footer`: Se reorganiza en una sola columna.

### 📱 **Celulares Medianos (≤ 600px)**
- `.product-dimensions`: Cambia a diseño vertical con imagen en la parte superior.
- `.container-areas`: Se reorganiza en columna.
- `.container-shiping`: Se ajusta al 80% de ancho y aumenta el tamaño de fuente.

### 📊 **Tablets (≤ 769px)**
- `.nav-links`: Se reorganizan con mayor separación.
- `.buttons`: Se vuelven apiladas verticalmente y más grandes.
- `.product-info`: Se expande al 85% de ancho y se permite el ajuste flexible de los textos.
- `.product-dimensions img`: Se agranda al 50% del ancho.
- `.gallery-product > img`: Se expanden a un 40% del ancho.

### 💻 **Laptops Pequeñas (≤ 800px)**
- `.container-areas > div`: Se ajusta al 30% del ancho.
- `.product-dimensions img`: Se redimensiona al 50% del ancho.
- `.celda`: Se agranda para mejorar la legibilidad.

### 🖥 **Laptops Medianas (≤ 1000px)**
- `.types-shipping`: Se centra con más espacio entre elementos.

### 🖥 **Laptops Grandes (≤ 1150px)**
- `.gallery-product > img`: Se redimensiona al 40% del ancho.