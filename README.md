# Cztery Łapy — Klinika Weterynaryjna

Przykładowa strona-wizytówka dla fikcyjnej kliniki weterynaryjnej „Cztery Łapy" w Warszawie.
Projekt wykonany jako element portfolio stronainternetowa.biz.

## Styl i design

- **Paleta**: kremowa biel `#fff7ec`, pomarańcz `#f59e42`, teal `#2bb3a3`, ciepły brąz `#6b4f3a`
- **Fonty**: Baloo 2 (nagłówki — zaokrąglony, przyjazny) + Nunito (body — czytelny, miękki)
- **Klimat**: ciepły, przyjazny, lekko ilustracyjny — miękkie kształty, zaokrąglenia, łapki 🐾

## Sekcje

1. **Nawigacja** — fixed, CTA „Umów wizytę", hamburger mobilny
2. **Hero** — pełnoekranowe zdjęcie psa, hasło, dwa CTA, statystyki
3. **O klinice** — mozaika zdjęć, lista cech, animowane liczniki
4. **Usługi** — 6 kart (profilaktyka, chirurgia, stomatologia, USG/RTG, seniory, dyżur 24/7)
5. **Zespół** — 4 karty lekarzy z fotkami i specjalizacjami
6. **Godziny i dyżury** — harmonogram + numer alarmowy + info o dojezdzie
7. **Opinie** — 4 recenzje właścicieli z gwiazdkami
8. **Formularz + Mapa** — rejestracja online + iframe OpenStreetMap
9. **Stopka** — linki, social media, credit stronainternetowa.biz

## Stack

- **Astro 5** — framework SSG
- **Tailwind CSS 4** — utility-first (przez `@tailwindcss/vite`)
- **Google Fonts** — Baloo 2 + Nunito
- Bez zewnętrznych bibliotek JS

## Komendy

```bash
npm install
npm run dev      # serwer deweloperski
npm run build    # build produkcyjny → dist/
npm run preview  # podgląd buildu
```

## Hosting

Gotowy do wdrożenia na [Vercel](https://vercel.com) — wystarczy `git push`.
