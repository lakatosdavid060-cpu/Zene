Streamify – GitHub Pages csomag

Fájlok:
- index.html
- manifest.json
- sw.js

A YouTube API-kulcs be van építve az index.html-be.

FONTOS:
A böngészőben használt API-kulcs nyilvánosan látható lesz. A Google Cloud Console-ban érdemes
HTTP referrer korlátozást beállítani a saját GitHub Pages domainedre, és csak a szükséges
YouTube Data API jogosultságot engedélyezni.

iOS háttérlejátszás:
A Streamify YouTube iframe-es lejátszást használ. GitHub Pages statikus tárhely, és a YouTube
IFrame Player API nem ad garantált iOS háttérlejátszást/lezárt képernyős lejátszást. Ezt nem lehet
megbízhatóan megoldani egy egyszerű JavaScript-kóddal vagy az iframe elrejtésével.

A csomag a hivatalos YouTube IFrame Player API-t használja.
