# MyPDF — téléchargements et mises à jour

MyPDF est un lecteur et éditeur PDF gratuit pour Windows 10 et 11, hors
ligne : lire, signer (signatures, paraphes, tampons), modifier le texte,
remplir des formulaires, organiser et combiner des pages.

## Télécharger

Dernière version : **[Releases › Latest](../../releases/latest)**

* **MyPDF-Setup-X.Y.Z.exe** : installation pour votre compte Windows, sans
  droits d'administrateur.
* **MyPDF-Portable-X.Y.Z.zip** : sans installation (à décompresser dans un
  dossier modifiable, sur un PC ou une clé USB).

Windows peut afficher « Windows a protégé votre ordinateur » (exécutables non
signés par un certificat commercial) : « Informations complémentaires » ›
« Exécuter quand même ». Empreintes SHA-256 : `SHA256SUMS.txt` de chaque
version.

## Mises à jour

MyPDF vérifie lui-même ce dépôt (une fois par jour si l'option est cochée,
ou par Paramètres › Mises à jour › « Rechercher une mise à jour »), sans
compte ni identifiant. Chaque mise à jour est signée : MyPDF contrôle la
signature et l'empreinte du fichier, lance l'autotest de la nouvelle version
et revient à la précédente en cas de problème. Vos signatures, tampons,
préréglages et réglages ne sont jamais modifiés.

Les autres fichiers d'une version servent à ces mises à jour :
`MyPDF-app-X.Y.Z.zip`, `mypdf-update.json` et sa signature
`mypdf-update.json.sig`.

## Code source et licence

MyPDF est un logiciel libre sous licence **GNU AGPL-3.0 ou ultérieure**
(fichier `LICENSE`). Le **code source complet de chaque version**, y compris
les scripts qui construisent l'application, l'installateur et la version
portable, est publié avec ses exécutables : fichier
**`MyPDF-X.Y.Z-source.zip`** de la même version. Les composants tiers et leurs
licences sont décrits dans `THIRD_PARTY_NOTICES.md`, à l'intérieur de cette
archive et de chaque installation.

Ce dépôt ne contient que les versions publiées ; le développement a lieu
ailleurs.
