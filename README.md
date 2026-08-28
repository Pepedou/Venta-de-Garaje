# Venta de Garaje

Sitio estático bilingüe para una venta de garaje en CDMX. No necesita base de datos ni cuenta de pago: las publicaciones viven en `data/items.json` y `data/items.js`, y las fotos en `assets/items/`.

## Publicarlo gratis con GitHub Pages

1. Crea un repositorio privado o público en GitHub y sube esta carpeta.
2. En **Settings → Pages**, selecciona **Deploy from a branch**, elige la rama `main` y la carpeta `/ (root)`.
3. GitHub mostrará la dirección pública del sitio. Cada vez que hagas *commit* y *push*, se actualizará en pocos minutos.

## Agregar artículos sin programar

1. Abre `admin.html` con Chrome o Edge (también puedes abrir `http://localhost:8000/admin.html` tras ejecutar `python3 -m http.server 8000` dentro de esta carpeta).
2. Presiona **Elegir carpeta del sitio** y selecciona esta carpeta, `Venta de Garaje`.
3. Presiona **Agregar artículo**, escribe el texto en español e inglés, selecciona las fotos y guarda.
4. El editor copia las fotos a `assets/items/` y actualiza ambos archivos del catálogo automáticamente.
5. En GitHub Desktop, revisa los cambios y usa **Commit to main** → **Push origin** para publicarlos.

Para marcar un artículo como vendido, abre el mismo editor y usa **Marcar vendido**. Los artículos vendidos no se muestran de forma predeterminada, pero siguen disponibles en la pestaña **Todos** con la etiqueta “Vendido”.

## Contacto

El sitio prepara un mensaje para WhatsApp al `+52 55 2955 6036` y también permite enviarlo por correo a `debate.duvet-53@icloud.com`. No guarda datos de clientes en el sitio.
