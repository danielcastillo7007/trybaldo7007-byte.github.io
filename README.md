# ViveFutTIV Admin Web

Panel web remoto para administrar las transmisiones autorizadas de ViveFutTIV.

## Publicarlo en GitHub Pages

1. Crea o usa un repositorio de GitHub.
2. Sube `index.html` y `.nojekyll` a la raíz del repositorio.
3. En GitHub abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona `main` y `/ (root)`.
6. Guarda y espera la publicación.

GitHub Pages puede tardar unos minutos en publicar los cambios.

## Seguridad

- El sitio usa solamente la clave pública/publishable de Supabase.
- Nunca coloques `sb_secret_...` ni `service_role` en este sitio.
- La autorización real para administrar `app_config` y `streams` debe permanecer en las políticas RLS de Supabase.
- Solo usuarios incluidos en `public.admin_users` deben tener permisos de administrador.

## URL esperada

Si el repositorio es `trybaldo7007-byte.github.io`, la dirección será:

https://trybaldo7007-byte.github.io/

Si lo colocas dentro de otro repositorio, la URL será:

https://trybaldo7007-byte.github.io/NOMBRE-DEL-REPOSITORIO/
