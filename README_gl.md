# A empaquetar unha app, mira este exemplo

- Copia esta app antes de traballar nela, usando o botón ['Usa este modelo'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost) no repo en Github
- Edita o `manifest.toml` con información específica da app
- Edita os scripts `install`, `upgrade`, `remove`, `backup` e `restore`, así como os ficheiros conf necesarios en `conf/`
  - Usar a [documentación dos asistentes para scripts](https://yunohost.org/packaging_apps_helpers)
- Editar tamén os scripts `change_url` e `config` , ou eliminalos se non os usaches
- Engade un ficheiro `LICENSE` para o paquete.
  - Nota: este ficheiro `LICENSE` non ten que ser necesariamente o LICENSE da app da que procede - só é a LICENZA coa que queres publicar o código deste paquete. Podes elexir libremente! (Se non o tes claro, recomendamos usar a licenza [AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt))
- Editar os ficheiros dentro do directorio `doc/` ([le a páxina acerca de documentar os paquetes](https://yunohost.org/packaging_app_doc))
- Os ficheiros `README.md` créanse automáticamente con <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>

---
<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Example app para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/example.svg)](https://dash.yunohost.org/appci/app/example) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/example.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/example.maintain.svg)

[![Instalar Example app con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Example app de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral



**Versión proporcionada:** 1.0~ynh1

**Demo:** <https://demo.example.com>

## Capturas de pantalla

![Captura de pantalla de Example app](./doc/screenshots/example.jpg)

## Avisos / información importante

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentación e recursos

- Web oficial da app: <https://example.com>
- Documentación oficial para usuarias: <https://yunohost.org/apps>
- Documentación oficial para admin: <https://yunohost.org/packaging_apps>
- Repositorio de orixe do código: <https://some.forge.com/example/example>
- Tenda YunoHost: <https://apps.yunohost.org/app/example>
- Informar dun problema: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
ou
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
