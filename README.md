# Studie zahrady RD Kunžak — statický web

Kompletní statický web. Žádný build, nic se neinstaluje. Hlavní stránka je `index.html` v kořeni.

## Nasazení na GitHub Pages
1. Nahraj **obsah této složky** do kořene repozitáře (ať je `index.html` v rootu, ne ve podsložce).
2. Soubor `.nojekyll` ponech — zajišťuje, že se publikuje i složka `_ds` (GitHub Pages by ji jinak kvůli podtržítku ignoroval).
3. V repu: Settings → Pages → Source: „Deploy from a branch", branch `main`, složka `/ (root)`.
4. Za chvíli web poběží na `https://<uživatel>.github.io/<repo>/`.

## Struktura
- `index.html` — deck (listuje se šipkami)
- `support.js`, `deck-stage.js`, `image-slot.js` — runtime
- `_ds/` — design systém (CSS + bundle)
- `assets/` — fotky, plán, loga

Musí běžet přes http(s) hosting, ne otevřením souboru z disku (runtime načítá části přes fetch).
