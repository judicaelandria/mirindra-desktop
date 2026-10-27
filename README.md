<img src="icon.svg" width="72" alt="Mirindra">

# Mirindra

La gestion de votre boutique, simplement.

Mirindra for Mac and Windows is a window around the live site. Stock, orders, and the rest of the shop stay on [mirindra.app](https://mirindra.app), so a deploy reaches the app at once. The app adds its own window, an offline page, the dock count, and updates.

## Download

The current installers are the [latest release](https://github.com/judicaelandria/mirindra-desktop/releases/latest). The same files are offered on [mirindra.app/download](https://mirindra.app/download).

| | |
| --- | --- |
| Mac | [Télécharger pour Mac](https://mirindra.app/download/mac) |
| Windows | [Télécharger pour Windows](https://mirindra.app/download/windows) |

The Mac build runs on Apple silicon and Intel. Windows is 64-bit.

The first time you open the app, the computer asks you to confirm it. It is not signed by Apple, and it has no Windows certificate.

- On a Mac: Réglages Système → Confidentialité et sécurité → Ouvrir quand même.
- On Windows: Informations complémentaires → Exécuter quand même.

## This repository

It holds the installers. The source of the app is not here.

`releases/latest/download` always points at the newest release. The site and the installed apps read that address.

| File | What it is |
| --- | --- |
| `Mirindra-<version>-mac.dmg` | The Mac installer |
| `Mirindra-<version>-mac.zip` | The Mac update |
| `Mirindra-<version>-windows.exe` | The Windows installer and update |
| `latest-mac.yml`, `latest.yml` | Which file is current |

Until a release is published, those links have nothing to serve.
