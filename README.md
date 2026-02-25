# silly-hydra
Silly Hydra Page
 
Configuración para GitHub Pages

- Asegúrate en la configuración del repositorio (Settings → Pages) que la fuente sea la rama `main` y la carpeta `/ (root)`.
- El archivo `CNAME` contiene el dominio personalizado usado: `www.sillyhydra.com`.
- Para que el dominio funcione correctamente añade estos registros DNS en tu proveedor:
	- Si usas el subdominio `www`: añade un registro CNAME apuntando a `your-github-username.github.io`.
	- Si quieres usar el dominio raíz (sillyhydra.com): añade A records apuntando a las IPs de GitHub Pages:
		- 185.199.108.153
		- 185.199.109.153
		- 185.199.110.153
		- 185.199.111.153

- Tras cambiar DNS puede tardar hasta 24–48 horas en propagarse. Verifica también que en Settings → Pages aparece el dominio personalizado configurado.

Si quieres, puedo añadir una comprobación automática o ayudarte a generar pasos concretos según tu proveedor DNS.
