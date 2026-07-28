# Documentación de Diseño: AquaPura del Sur (Landing Page)

Esta documentación describe la identidad visual, la paleta de colores, la tipografía y la estructura de la landing page de **AquaPura del Sur**, diseñada específicamente para la captación de socios comerciales y B2B.

---

## 1. Paleta de Colores

La paleta de colores ha sido elegida para transmitir frescura, pureza, profesionalismo y rentabilidad. Se compone de las siguientes variables CSS declaradas en `src/styles/global.css`:

| Variable CSS | Color Hexadecimal | Representación Visual / Uso |
| :--- | :--- | :--- |
| `--aquapura-navy` | `#0A2E4D` | **Azul Marino Profundo**: Color primario. Representa la profundidad del agua, la seriedad corporativa y la solidez financiera. Usado en fondos oscuros, encabezados principales y textos de alto contraste. |
| `--aquapura-turquoise` | `#16A6C9` | **Turquesa Brillante**: Color secundario. Representa la pureza, la frescura y la innovación del agua tratada químicamente. Usado para destacar etiquetas, bordes, iconos y efectos hover. |
| `--aquapura-amber` | `#F2A413` | **Ámbar Calidez**: Color de acento. Simboliza el valor del oro (la inversión rentable) y genera urgencia visual. Usado exclusivamente para botones de Llamado a la Acción (CTA) primarios. |
| `--aquapura-light` | `#F4F6F8` | **Gris Claro / Fondo**: Color de contraste. Permite que la lectura sea ligera y limpia en las secciones de información general. |
| `--aquapura-text` | `#1A2530` | **Gris Carbón / Texto**: Usado para el cuerpo de texto principal, asegurando un óptimo contraste de lectura y evitando el negro puro para mejorar la legibilidad. |

---

## 2. Tipografía

- **Fuente Principal**: `'Inter'` (importada de Google Fonts).
- **Características**: Es una tipografía sans-serif geométrica moderna y legible en pantallas de alta resolución.
- **Pesos de Fuente (Font-Weights)**:
  - `300` (Light) y `400` (Regular): Utilizados en párrafos y descripciones generales.
  - `500` (Medium) y `600` (Semi-Bold): Utilizados en textos de navegación y etiquetas secundarias.
  - `700` (Bold) y `800` (Extra-Bold): Utilizados en encabezados principales (`h1`, `h2`, `h3`) para generar una jerarquía visual impactante.

---

## 3. Estructura de las Secciones

La landing page se compone de las siguientes secciones estratégicamente ordenadas para maximizar el embudo de conversión de inversionistas:

1. **Header / Navegación**:
   - Barra fija (fixed navbar) con fondo semi-transparente y efecto de desenfoque (`backdrop-filter: blur`).
   - Contiene el logotipo de AquaPura del Sur, enlaces internos de navegación rápida y el botón CTA destacado "Invertir Hoy" para accesibilidad inmediata.

2. **Hero Section (Inicio)**:
   - Sección de impacto con fondo gradiente (`water-hero-bg`) y una animación CSS fluida que simula el movimiento del agua.
   - Cuenta con dos capas flotantes de desenfoque radial (`water-bubble`) para una experiencia tridimensional de ondas.
   - Incluye el título principal y subtítulo orientados al retorno de inversión.
   - Concluye con un divisor de forma de ola (SVG) que conecta orgánicamente con la siguiente sección.

3. **Sección de Trayectoria (Stats)**:
   - Muestra las credenciales de la empresa en una rejilla (grid) de tarjetas modernas.
   - Destaca de manera prioritaria los **12 años de experiencia** y las **38 sucursales activas**.
   - Integra métricas atractivas de rendimiento financiero (como el 32% de retorno promedio).

4. **Proceso de Purificación (7 Pasos)**:
   - Línea de tiempo interactiva detallando las tecnologías empleadas:
     1. *Filtración de Sedimentos* (Retiene partículas sólidas).
     2. *Carbón Activado Granular* (Elimina cloro, olores y sabores).
     3. *Suavizador de Agua* (Remueve dureza y minerales pesados).
     4. *Ósmosis Inversa* (Purificación microscópica molecular).
     5. *Filtro Pulidor* (Otorga la brillantez cristalina final).
     6. *Esterilización por Luz UV* (Elimina el 99.9% de bacterias).
     7. *Ozonización final* (Mantiene el garrafón estéril a largo plazo).

5. **Precios Corporativos y B2B**:
   - Tarjetas de precios diseñadas para demostrar el volumen de ventas:
     - *Garrafón en Sucursal (Básico)*
     - *Suministro Corporativo (Más Demandado)* con entrega programada a oficinas.
     - *Distribuidor Autorizado (Mayoreo)* para reventa local.

6. **Formulario de Contacto para Inversionistas**:
   - Formulario detallado enfocado en captación B2B.
   - Campos de captura específicos: Nombre Completo, Razón Social, Correo, Teléfono y un selector para el **Rango de Inversión Estimado** (de $100k a más de $3M de pesos).

7. **Footer / Pie de Página**:
   - Resumen institucional de la marca.
   - Datos oficiales del Director Comercial: **Lic. Refugio Méndez** (Teléfono y correo directo).
   - Enlaces legales (Aviso de privacidad y términos y condiciones de franquicia).
