# MARKET AI – MVP 0.1

## Co funguje
- Responzivní webová aplikace optimalizovaná pro iPhone.
- PWA manifest a service worker (po nasazení na HTTPS lze přidat na plochu).
- Živá data kryptoměn z veřejného CoinGecko API, pokud API dovolí požadavek.
- Přehled BTC/ETH/SOL, seznam dalších kryptoměn, jednoduchý 7denní graf BTC.
- Lokální watchlist uložený v prohlížeči.

## Co zatím není hotové
- Akciová data: pro veřejnou aplikaci je nutný poskytovatel s odpovídající licencí a serverová integrace.
- Účty a synchronizace: vyžadují backend a bezpečné ověřování.
- Push notifikace, skutečné AI analýzy, placené předplatné a billing.
- Toto je prototyp, nikoli produkčně zabezpečená finanční služba.

## Nasazení
Nahraj celý obsah složky na hosting, který poskytuje HTTPS a statické soubory (např. GitHub Pages, Netlify nebo Cloudflare Pages). Pak otevři veřejnou HTTPS adresu v Safari na iPhonu → Sdílet → Přidat na plochu.

## Důležité
CoinGecko veřejné API může mít limity, výpadky nebo změnit podmínky. Pro komerční veřejné použití ověř licenci a podmínky poskytovatele. API klíče nikdy nevkládej do veřejného JavaScriptu. Před veřejným spuštěním je potřeba doplnit backend, ochranu proti zneužití, zásady ochrany osobních údajů a obchodní podmínky.
