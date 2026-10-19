Streamify Mobile Pro

Telefonra optimalizált GitHub Pages verzió:
- mobil alsó navigáció
- modern mini-lejátszó
- extrák panel
- alvásidőzítő
- képernyő-ébrentartás, ha az iOS engedi
- megosztás
- shuffle/queue gyorsvezérlők
- PWA metaadatok
- beépített YouTube API-kulcs

FONTOS: a YouTube IFrame Player API-val az iOS lezárt képernyős/háttérben futó YouTube-hangja
nem garantálható. A YouTube iframe-et nem szabad elrejteni vagy más módszerrel megkerülni az
iOS/YouTube háttérlejátszási korlátozásait. A valódi, megbízható háttérhanghoz saját vagy
engedélyezett közvetlen audioforrás (<audio>) szükséges, illetve a YouTube saját alkalmazása
által támogatott háttérlejátszás.

Az API-kulcs nyilvánosan látható lesz az index.html-ben; Google Cloudban korlátozd a kulcsot
a saját GitHub Pages domainre.
