# Kyodai Font Lab

**Versión 1.0.0**

Comparador tipográfico A/B para evaluar familias y pesos de Google Fonts bajo las mismas condiciones de contenido, tamaño, interlineado, anchura y separación entre caracteres.

## Funciones principales

- Selección independiente de fuentes para titulares y párrafos en las versiones A y B.
- Pesos configurables por separado para cada tipo de texto y versión.
- Incorporación de otras familias disponibles en Google Fonts.
- Sincronización bidireccional de familias entre A y B, manteniendo los pesos independientes.
- Comprobación del estado de carga de cada fuente y peso.
- Controles compartidos mediante deslizadores y campos numéricos editables.
- Edición en tiempo real del título, la marca, los párrafos y el texto de los enlaces.
- Comparación de enlaces, cifras y textos en distintos tamaños.
- Barra lateral adaptable, colapsable y optimizada para dispositivos móviles.
- Paneles de configuración fijos durante el desplazamiento.
- Guía de uso integrada.

## Uso

La aplicación está contenida completamente en `index.html` y no necesita instalación ni proceso de compilación.

Puede abrirse directamente en un navegador moderno o servirse localmente desde el directorio superior:

```bash
python3 -m http.server 8000 --directory "Font Lab"
```

Después, abre:

```text
http://localhost:8000
```

## Requisitos

- Navegador moderno con soporte para variables CSS, `dialog` y la API `document.fonts`.
- Conexión a Internet para cargar Google Fonts. El logotipo de atribución va incluido en el proyecto.

Si una combinación muestra el estado **NO CARGADA**, no debe evaluarse como si utilizara la fuente solicitada. Comprueba el nombre de la familia, el peso seleccionado y la conexión.

## Estructura

```text
Font Lab/
├── assets/
│   └── logo-kyodai-agency-white.png
├── index.html
├── index.min.html
├── LICENSE
├── LICENSE.html
└── README.md
```

`index.html` es la versión de trabajo (marcado, estilos y JavaScript). `index.min.html` es la misma aplicación, compactada para publicar. `LICENSE` contiene el texto completo de CPAL-1.0 con los anexos A y B rellenados. `LICENSE.html` es la misma licencia para leerla en el navegador. `assets/` incluye el logotipo de atribución (marca Kyodai Agency).

## Tecnologías

- HTML5
- CSS
- JavaScript sin frameworks
- Google Fonts

## Licencia

Kyodai Font Lab se publica como software de código abierto bajo la **Common Public Attribution License 1.0** (`CPAL-1.0`). El titular es **Kyodai Online Services LLC**. Kyodai Agency es una marca de esa empresa. Las fuentes y otros activos son propiedad de sus respectivos dueños. El texto completo está en [`LICENSE`](LICENSE).

Puedes usar, copiar, modificar y distribuir este software, también con fines comerciales, con estas condiciones:

1. El código cubierto permanece bajo CPAL-1.0 y debe ir acompañado de esta licencia.
2. Hay que mostrar de forma visible la atribución de Kyodai Online Services LLC:
   - aviso: `Copyright (c) 2026 Kyodai Online Services LLC`
   - frase: `Powered by Kyodai Online Services`
   - URL: [https://kyodaiagency.com/](https://kyodaiagency.com/)
   - logotipo: `assets/logo-kyodai-agency-white.png` ([archivo original](https://kyodaiagency.com/wp-content/uploads/2023/06/logo-kyodai-agency-white-350x100-1.png))
3. Esa atribución debe aparecer al iniciar una sesión (el diálogo de ayuda) y en el área dedicada del pie. En un trabajo mayor que incluya este código, la atribución sigue siendo obligatoria.
4. Si ofreces el programa como servicio en red, debes publicar el código fuente de tus modificaciones.

La atribución no concede derechos de marca. El nombre y el logotipo de Kyodai Online Services, y la marca Kyodai Agency, siguen siendo de Kyodai Online Services LLC. Las fuentes y otros activos son propiedad de sus respectivos dueños.

## Versión

### 1.0.0

Primera versión pública de Kyodai Font Lab.
