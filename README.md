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

