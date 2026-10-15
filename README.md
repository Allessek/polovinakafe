# Polovina kafe

Web kavárny Polovina kafe (Třída T. G. Masaryka 1084, Roudnice nad Labem).

Jednosouborová statická stránka — čistě HTML/CSS/vanilla JS, žádný build krok, žádný framework.

## Spuštění lokálně

Stačí otevřít `index.html` v prohlížeči, nebo spustit libovolný statický server ve složce projektu, např.:

```bash
python3 -m http.server 8080
```

a otevřít `http://localhost:8080`.

## Struktura

- `index.html` — celá stránka (HTML, CSS i JS v jednom souboru)
- `images/` — fotky použité na webu

## Poznámky

- Živé počasí v hero sekci táhne data z [Open-Meteo](https://open-meteo.com/) (bez API klíče).
- 3D galerie "Momentky" používá [ogl](https://github.com/oframe/ogl) načtené přes jsDelivr CDN.
- Rezervační formulář otevírá WhatsApp s předvyplněnou zprávou (bez backendu).
