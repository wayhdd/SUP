# EPITA_annales

Des documents pour pouvoir taffer

N'hésitez pas à faire des ajouts si vous avez des docs qui pourraient aider les autres.
Veillez bien à suivre les [conventions de nommage des fichiers](Naming.md)

## Une liste de liens intéressants pour bosser

* [ici](LiensUtiles.md)

## Applications recommandées pour les scans sur portable

### Android

* [Office Lens](https://play.google.com/store/apps/details?id=com.microsoft.office.officelens)
* [Adobe Scan](https://play.google.com/store/apps/details?id=com.adobe.scan.android)

### iOS

* [Office Lens](https://itunes.apple.com/fr/app/office-lens/id975925059)
* [Adobe Scan](https://itunes.apple.com/fr/app/adobe-scan/id1199564834)
* [Evernote Scannable](https://itunes.apple.com/fr/app/evernote-scannable/id883338188)

## Applications recommandées pour les scans sur PC/Mac

### Windows

* [NAPS2](https://www.naps2.com/) avec une fonctionnalité sympa d'acquisition par lot

## Si vous voulez participer et nous aider

* Veillez bien à suivre les [conventions de nommage des fichiers](Naming.md)
* Pour faire des modifs sur le git -> [ici](Participer.md)
* La liste des choses à faire dans le git -> [ici](TODO.md)

## Merci de bien vouloir compresser vos scans pour ne pas saturer le repo

* Automatiquement (avec renommage en _c) : `python3 cleaner.py` à la racine de votre repo git
* Manuellement : `gs -q -dSAFER -dNOPAUSE -dBATCH -sDEVICE=pdfwrite -dPDFSETTINGS=/ebook -sOutputFile=output.pdf -f input.pdf`
