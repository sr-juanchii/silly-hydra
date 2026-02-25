# silly-hydra
Silly Hydra Page

Configuración para GitHub Pages y cambios SEO

- Asegúrate en la configuración del repositorio (Settings → Pages) que la fuente sea la rama `main` y la carpeta `/ (root)`.
- El archivo `CNAME` contiene el dominio personalizado usado: `www.sillyhydra.com`.
- Para que el dominio funcione correctamente añade estos registros DNS en tu proveedor:
  - Si usas el subdominio `www`: añade un registro CNAME apuntando a `sr-juanchii.github.io`.
  - Si quieres usar el dominio raíz (sillyhydra.com): añade A records apuntando a las IPs de GitHub Pages:
    - 185.199.108.153
    - 185.199.109.153
    - 185.199.110.153
    - 185.199.111.153

- Tras cambiar DNS puede tardar hasta 24–48 horas en propagarse. Verifica también que en Settings → Pages aparece el dominio personalizado configurado y activa `Enforce HTTPS` cuando esté disponible.

Cambios SEO aplicados

- `index.html`: añadí meta `description`, `canonical`, Open Graph y Twitter card tags, `hreflang`, y JSON-LD (WebSite). También reorganicé la estructura en `header` / `main` / `footer` y usé `defer` en el `script.js`.
- `sitemap.xml`: creado en la raíz con la URL de la home.
- `robots.txt`: creado y referencia el `sitemap.xml`.

Próximos pasos recomendados

- Subir los cambios y comprobar en Settings → Pages que GitHub detecta el `CNAME` y emite certificados HTTPS.
- Añadir una imagen social (por ejemplo `social.png`) y actualizar las meta `og:image` y `twitter:image` para mejorar las tarjetas sociales.
- Registrar el sitio en Google Search Console y subir `sitemap.xml` ahí.

Si quieres, puedo generar una imagen social básica y añadir las meta correspondientes o preparar instrucciones específicas para tu proveedor DNS.
