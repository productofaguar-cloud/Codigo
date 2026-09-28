# Bravo Jeans Mayorista — códigos para Tiendanube (tema Ipanema)

Archivos listos para copiar y pegar en el panel de Tiendanube.

| Archivo | Qué es | Dónde se pega |
|---|---|---|
| `ipanema/css-personalizado.css` | Colores de marca, botones, etiquetas de oferta y estilos de la barra y del botón de WhatsApp | Mi Tienda → Diseño → Personalizar → **Editar CSS avanzado** |
| `ipanema/barra-anuncios.html` | Barra superior con mensajes que se deslizan | Configuración → **Códigos externos** (código para el body) |
| `ipanema/video-inicio.html` | Portada con video, título, compra mínima y botón a la categoría Anticipo | Diseño → Personalizar → Página de inicio → sección HTML |
| `ipanema/whatsapp-flotante.html` | Botón flotante de WhatsApp | Configuración → **Códigos externos** (código para el body) |
| `paginas/guia-de-talles.html` | Página de guía de talles, adaptada al celular | Mi Tienda → **Páginas** → Nueva → botón `<>` |
| `descripciones/plantilla-producto.html` | Plantilla de descripción de producto | Producto → Descripción → botón `<>` |

## Antes de publicar
1. Pegá **primero** el CSS: la barra y el botón de WhatsApp toman sus estilos de ahí.
2. Cambiá los datos de ejemplo: `549XXXXXXXXXX` (WhatsApp), las medidas de la guía de talles y lo que está entre `[corchetes]`.
3. Los colores se cambian en la sección 1 del CSS (`--bj-primario`, `--bj-acento`).
4. Si alguna regla de la sección 4 del CSS no se nota en Ipanema: clic derecho sobre el elemento → **Inspeccionar**, copiá su clase y reemplazala en el CSS.
