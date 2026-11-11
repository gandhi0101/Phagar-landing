# PHAGAR — Landing page

Sitio web estático de PHAGAR, preparado para publicarse en GitHub Pages.

## Contenido

- `index.html`: página HTML autónoma; estilos, JavaScript y el logotipo están incluidos en un único archivo.
- No requiere instalación, compilación ni servidor de aplicaciones.

## Publicación con GitHub Pages

1. Ve a **Settings → Pages** en este repositorio.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Elige la rama **main**, carpeta **/(root)** y guarda.
4. Comprueba que la página aparezca en `https://gandhi0101.github.io/Phagar-landing/`.

## Dominio propio

El dominio de PHAGAR es `phagar.com`. Para conectarlo, configura **Custom domain** en GitHub Pages y los registros DNS según la documentación oficial de GitHub. **No cambies los registros de `n8n.phagar.com`**, que corresponden a las automatizaciones.

## Contacto

Los botones de contacto abren el formulario comercial de PHAGAR alojado en `https://n8n.phagar.com/form/phagar-consulta`. La página también enlaza al aviso de privacidad vigente y a `phagar.contacto@gmail.com`.

## Actualizaciones

El proyecto no necesita dependencias. Los cambios al sitio se realizan editando `index.html` y publicando un commit en `main`.
