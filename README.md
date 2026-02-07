# SensiBody – Landing Page Warsztatów

Landing page prezentujący ofertę warsztatów emocjonalno-ruchowych SensiBody dla placówek edukacyjnych.

## Podgląd

Strona prezentuje trzy pakiety warsztatów dla rad pedagogicznych:
- **Pakiet Poznaj** (2 490 zł) – wprowadzenie do metody
- **Pakiet Wdrożenie** (3 900 zł) – pełne materiały + follow-up
- **Pakiet System** (5 400 zł) – systemowe wdrożenie z dokumentacją

## Technologia

- Czysty HTML5 + CSS3 + vanilla JavaScript
- Brak zależności (no npm, no build tools)
- Responsywny design (mobile-first)
- Fonty: DM Serif Display + Source Sans 3 (Google Fonts)
- Animacje CSS + Intersection Observer API

## Struktura

```
sensibody-warsztaty/
├── index.html          # Główna strona (all-in-one)
├── README.md
├── LICENSE
└── .gitignore
```

## Uruchomienie lokalne

Otwórz `index.html` w przeglądarce lub użyj prostego serwera:

```bash
# Python
python3 -m http.server 8000

# Node.js
npx serve .
```

## Deployment

Strona jest gotowa do wdrożenia na:
- **GitHub Pages** – Settings → Pages → Deploy from branch `main`
- **Netlify** – Drag & drop folderu
- **Vercel** – Import repozytorium

## Dostosowanie

### Dane kontaktowe
W `index.html` zmień:
- `href="mailto:kontakt@sensibody.pl"` na właściwy adres email
- Numer telefonu (jeśli dodajesz)
- Linki do social media

### Zdjęcie prowadzącej
Zamień placeholder `.about-image-placeholder` na element `<img>`:
```html
<img src="assets/ela-photo.jpg" alt="Elżbieta Markiewicz" style="border-radius: 24px; width: 100%; object-fit: cover; aspect-ratio: 4/5;">
```

### Testimoniale
Zaktualizuj opinie w sekcji `.testimonials` o prawdziwe recenzje z warsztatów.

## Licencja

© 2026 Elżbieta Markiewicz. Wszelkie prawa zastrzeżone.
