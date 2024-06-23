<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Slingcode para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/slingcode.svg)](https://dash.yunohost.org/appci/app/slingcode) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/slingcode.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/slingcode.maintain.svg)

[![Instalar Slingcode con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=slingcode)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarSlingcode rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Slingcode is a code editor contained in a single HTML file. Therefore, it has no server component, so all of your data is stored in your browser's cache. However, it is still possible to make web apps, run them, export them, and even share them using peer-to-peer.

### Features:

- You can make, run, and share web apps with it.
- You don't need any complicated tools to use it, just a web browser.
- You don't need a server, hosting, or an SSL certificate to run the web apps.
- You can put Slingcode on a web site, run it from a USB stick, laptop, or phone, and it doesn't need an internet connection to work.
- You can "add to home screen" in your phone's browser to easily access your library of programs on the go.
- You can share apps peer-to-peer over WebTorrent.
- It's private. You only share what you choose.


**Versión actual:** 0.2.2~ynh5

**Demo:** <https://slingcode.net/slingcode.html>

## Capturas

![Captura de Slingcode](./doc/screenshots/Screenshot.png)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Sitio web oficial: <https://slingcode.net/>
- Documentación usuario oficial: <https://slingcode.net/screencasts.html>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/chr15m/slingcode>
- Catálogo YunoHost: <https://apps.yunohost.org/app/slingcode>
- Reportar un error: <https://github.com/YunoHost-Apps/slingcode_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing --debug
o
sudo yunohost app upgrade slingcode -u https://github.com/YunoHost-Apps/slingcode_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
