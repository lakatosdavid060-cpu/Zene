STREAMIFY – GitHub Pages csomag

Feltöltés iPhone-ról:
1. Nyisd meg a GitHub repositorydat.
2. Add file -> Upload files.
3. Töltsd fel ezt a 3 fájlt ugyanabba a mappába:
   - index.html
   - manifest.json
   - sw.js
4. Commit changes.
5. GitHub -> Settings -> Pages -> Deploy from a branch -> main -> / (root).

Fontos:
- A YouTube API-kulcsot nem kell az index.html-be beleírni. Az oldal saját beállításai között adható meg, és localStorage-ban marad.
- A YouTube iframe hivatalos beágyazását használja; iOS háttérlejátszást YouTube-tartalomnál a weboldal nem tudja garantálni.
- A saját/licencelt audiofájlok <audio> lejátszással jobb alapot adnak iOS háttérlejátszáshoz.
