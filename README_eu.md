# Aplikazio bat paketatzen, honako adibidea oinarritzat hartuz

- Kopiatu aplikazio hau aldaketak egin baino lehen, Github gordailuko ['Erabili txantiloi hau'](https://github.com/new?template_name=example_ynh&template_owner=YunoHost) botoia erabiliz
- Editatu `manifest.toml` aplikazioaren informazio zehatzarekin
- Editatu `install`, `upgrade`, `remove`, `backup` eta `restore` scriptak, eta konfigurazio fitxategiak `conf/` direktorioan, beharrezkoak badira
  - Erabili [scripten laguntza-dokumentazioa](https://yunohost.org/packaging_apps_helpers)
- Editatu `change_url` eta `config` scriptak ere, edo kendu ez badute inolako betekizunik
- Gehitu `LICENSE` fitxategia paketerako.
  - Ohart ongi: `LICENSE` fitxategiak ez du zertan jatorrizko aplikazioaren lizentzia bera izan: pakete honen kodeak izatea nahi duzun lizentzia baino ez da eta aske zara berau aukeratzeko! (Ez badakizu zein aukeratu, guk [AGPL-3](https://www.gnu.org/licenses/agpl-3.0.txt) gomendatzen dugu)
- Editatu `doc/` direktorioko fitxategiak ([ikus paketeak dokumentatzeari buruzko orria](https://yunohost.org/packaging_app_doc))
- `README.md` fitxategiak automatikoki sortuko dira <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker

---
<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Example app YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/example.svg)](https://dash.yunohost.org/appci/app/example) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/example.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/example.maintain.svg)

[![Instalatu Example app YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Example app YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena



**Paketatutako bertsioa:** 1.0~ynh1

**Demoa:** <https://demo.example.com>

## Pantaila-argazkiak

![Example app(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Ezespena / informazio garrantzitsua

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

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://example.com>
- Erabiltzaileen dokumentazio ofiziala: <https://yunohost.org/apps>
- Administratzaileen dokumentazio ofiziala: <https://yunohost.org/packaging_apps>
- Jatorrizko aplikazioaren kode-gordailua: <https://some.forge.com/example/example>
- YunoHost Denda: <https://apps.yunohost.org/app/example>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/example_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
edo
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
