# 🌿 Jelitko – Instrukcja wdrożenia na GitHub Pages

## Pliki w tym folderze
- `index.html` – główna aplikacja
- `manifest.json` – konfiguracja PWA
- `sw.js` – service worker (tryb offline)
- `icon.png` – ikona 192×192
- `icon512.png` – ikona 512×512

---

## Jak wrzucić na GitHub Pages (5 minut)

### Krok 1 – Załóż konto GitHub
Wejdź na github.com i załóż bezpłatne konto jeśli nie masz.

### Krok 2 – Utwórz nowe repozytorium
1. Kliknij zielony przycisk **"New"**
2. Nazwij je np. `jelitko`
3. Ustaw jako **Public**
4. Kliknij **"Create repository"**

### Krok 3 – Wgraj pliki
1. Kliknij **"uploading an existing file"**
2. Przeciągnij WSZYSTKIE pliki z tego folderu (index.html, manifest.json, sw.js, icon.png, icon512.png)
3. Kliknij **"Commit changes"**

### Krok 4 – Włącz GitHub Pages
1. Wejdź w **Settings** (górna belka repozytorium)
2. Kliknij **Pages** (lewy panel)
3. W sekcji "Branch" wybierz **main** i **/ (root)**
4. Kliknij **Save**

### Krok 5 – Gotowe!
Po ~2 minutach aplikacja jest dostępna pod adresem:
`https://TWOJA-NAZWA.github.io/jelitko`

---

## Jak dodać do ekranu głównego (iOS Safari)
1. Otwórz link w Safari
2. Kliknij ikonę **Udostępnij** (kwadrat ze strzałką)
3. Wybierz **"Dodaj do ekranu głównego"**
4. Kliknij **Dodaj**

Jelitko pojawi się jak normalna aplikacja z zieloną ikoną 🌿

---

## Jak dodać do ekranu głównego (Android Chrome)
1. Otwórz link w Chrome
2. Kliknij **⋮** (trzy kropki) 
3. Wybierz **"Dodaj do ekranu głównego"**

---

## Aktualizacje
Gdy będziesz chciał zaktualizować aplikację:
1. Wgraj nowy `index.html` do repozytorium (zastąpi stary)
2. Dane użytkowników zostają – są w localStorage na ich telefonach

**Dane NIE znikają przy aktualizacji pliku!**
