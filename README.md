# Alena Bistro & Café

Sitio web de Alena Bistro & Café, Colonia Escalón, San Salvador.

## Páginas

| Archivo | Para qué es |
|---|---|
| `index.html` | Página principal: portada, nuestra comida, menú completo (solo para ver), favoritos, postres, cotizador de eventos privados (envía a WhatsApp), cómo llegar (Waze / Google Maps), pedidos a domicilio por Uber Eats y redes sociales. |
| `menu.html` | Menú digital para pedir desde el teléfono. Al escanear el QR de una mesa (`menu.html#mesa-7`) la mesa queda puesta; el pedido se muestra como ticket con su código QR para enseñarlo al mesero. |
| `qr.html` | Generador de carteles QR por mesa que apuntan a `menu.html#mesa-N`. |
| `assets/` | Logo y fotos de los platillos. |

## Editar el menú

Los productos están en el arreglo `MENU` dentro del `<script>` de `index.html` y `menu.html`. Cada producto tiene categoría, nombre, descripción, precio (`p:null` muestra "Consultá precio") y foto (`img`) o ilustración (`i`).

## Publicar

Son archivos estáticos: se pueden publicar tal cual en GitHub Pages, Netlify o cualquier hosting. En `qr.html`, el enlace del menú se llena solo con la dirección donde esté publicado `menu.html`.

## Contacto del negocio

- Dirección: 3a Calle Poniente, No. 5254, Colonia Escalón, San Salvador
- WhatsApp: +503 6060 5545 · Reservaciones: +503 2562 8372
- Instagram: [@alena.cafe](https://www.instagram.com/alena.cafe/) · Facebook: [alenacafesv](https://www.facebook.com/alenacafesv/)
