# zip_install
Mit diesem AddOn kannst du gezippte AddOns einfach im Backend hochladen und installieren.

![Screenshot](https://raw.githubusercontent.com/FriendsOfREDAXO/zip_install/assets/screenshot.png)

Benutzung
------------
Das AddOn registriert eine neue Subpage im Installer (neben "Eigene hochladen"). Dort kannst du einfach eine ZIP-Datei eines gültigen AddOns uploaden (wird geprüft). Plugins lassen sich damit _noch_ nicht installieren, werde ich aber ggf. als Update nachreichen

Installation
------------
Hinweis: dies ist kein Plugin! (verhält sich jedoch wie eines)

* Release herunterladen und entpacken.
* Ordner umbenennen in `zip_install`.
* In den Addons-Ordner legen: `/redaxo/src/addons`.

Danach musst du diese nervigen Schritte nie wieder wiederholen, wenn du eigene AddOns z.B. von Github installieren möchtest. (oder eigene, lokal entwickelte).

Oder den REDAXO-Installer nutzen!

Voraussetzungen
------------

* fileinfo extension
* zlib extension