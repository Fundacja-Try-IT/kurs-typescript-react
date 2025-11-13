# Kurs React - Gra Memory 🎮

Witamy w kursie tworzenia gry Memory w React! Projekt stworzony specjalnie dla uczestniczek programu **Girls Go IT** prowadzonego przez Fundację Try IT.

**Zagraj w demo:** [W przypadku stabilnego hostingu]

**Playlist YouTube:** [krok po kroku przez cały projekt - wkrótce]

---

## 📖 O projekcie

To kompleksowy kurs React obejmujący tworzenie pełnoprawnej gry Memory od podstaw. Kurs prowadzi przez wszystkie kluczowe koncepcje React - od prostych komponentów po zaawansowane zarządzanie stanem.

**Czego się nauczysz:**
- ✅ Komponenty React i props
- ✅ Zarządzanie stanem (`useState`)
- ✅ Efekty uboczne (`useEffect`)
- ✅ Obsługa zdarzeń
- ✅ TypeScript w praktyce
- ✅ Stylowanie CSS
- ✅ Praca z cookies (opcjonalnie)

---

## 🗂️ Struktura kursu

Kurs wykorzystuje system **gałęzi Git** - każda gałąź reprezentuje konkretny etap nauki lub materiały pomocnicze.

### 🎯 Branch [`react-podstawy`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/react-podstawy) - Lekcja 1

**Start tutaj!** Podstawy React niezbędne do tworzenia gry.

Przełącz się na tę gałąź:
```bash
git checkout react-podstawy
```

**Commity do przerobienia:**
- [`commit 1`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/946463feee8c777cae0116d3772518a93304528c) Initial commit - projekt Vite + React + TypeScript
- [`commit 2`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/13242183121b0c29f82d986e66c0a5a959448840) Wyświetlanie komponentów
- [`commit 3`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/e538fdd9670bd200af930c48366a0fa8ba4c1629) Działanie useState
- [`commit 4`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/e107a3271553ae093836191a5478f185a143d804) Komponenty z props
- [`commit 5`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/879776d4fa6bb6157f071bec0f9a669e55293355) Lifting state up - stan we wspólnym rodzicu
- [`commit 6`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/398811b71914b509349f97acc81011b8ffa991f9) useEffect (reakcja na zmiany)

---

### 🎮 Branch [`gra`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/gra)- Lekcje 2-9

Pełna implementacja gry Memory - wzorcowa wersja do podglądania.

**Wszystkie commity z opisami:** Sprawdź [README w gałęzi `gra`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/gra) dla szczegółowego opisu każdego commitu.

**Kluczowe etapy:**
- Podstawowa struktura aplikacji
- Mechanika tasowania i odwracania kart
- Wykrywanie par i końca gry
- System statystyk (czas, ruchy)
- Grafika i UX
- Tablica wyników z cookies

---

### 🖼️ Branch [`materialy`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/materialy)

Wszystkie assety potrzebne do kursu: grafiki kart, favicon, tablice poziomów trudności.

```bash
git checkout materialy
```

**Zawiera:**
- Obrazki awersów i rewersów kart
- Favicon
- Gotowe tablice z konfiguracją poziomów
- Inne zasoby graficzne

**Uwaga:** Ta gałąź nie zawiera struktury Vite/React - to tylko repozytorium materiałów.

---

### 📝 Zadania domowe

Po każdej lekcji (od lekcji 3) dostępne jest zadanie domowe. Każde ma dedykowaną gałąź z bazowym kodem.

#### Jak pracować z zadaniem domowym?

1. **Przełącz się na gałąź zadania:**
```bash
git checkout zadanie-domowe-1
```

2. **Zainstaluj zależności i uruchom projekt:**
```bash
npm install
npm run dev
```

3. **Rozwiąż zadanie** zgodnie z instrukcjami w filmie YouTube i README w gałęzi zadania

4. **Porównaj swoje rozwiązanie** z gałęzią [`gra`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/gra) (kolejnym commitem), lub obejrz filmik z kolejną lekcją

#### Dostępne zadania:

| Gałąź | Opis zadania | Lekcja |
|-------|--------------|--------|
| [`zadanie-domowe-1`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/zadanie-domowe-1) | Stwórz planszę 4×2 z kartami używając CSS Grid | 3 |
| [`zadanie-domowe-2`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/zadanie-domowe-2) | Dodaj pole wyboru poziomu trudności - dynamiczna zmiana danych | 4 |
| [`zadanie-domowe-3`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/zadanie-domowe-3) | Wykryj odwrócenie dwóch kart i znajdź pary (lifting state up) | 5 |
| [`zadanie-domowe-4`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/zadanie-domowe-4) | Wykryj koniec gry używając useEffect | 6 |
| [`zadanie-domowe-5`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/zadanie-domowe-5) | Dodaj funkcję resetowania gry do stanu początkowego | 7 |
| [`zadanie-domowe-6`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/zadanie-domowe-6) | Zaimplementuj licznik ruchów w panelu statystyk | 8 |

**💡 Wskazówka:** Każda gałąź zadania zawiera plik `README.md` ze szczegółowymi instrukcjami!

---

### ⭐ Branch [`zadanie-z-gwiazdka`](https://github.com/Fundacja-Try-IT/kurs-typescript-react/tree/zadanie-z-gwiazdka)

**Dla ambitnych!** Zaawansowane zadanie wprowadzające cookies i localStorage.

```bash
git checkout zadanie-z-gwiazdka
```

Sprawdź plik `README.md` w tej gałęzi - zawiera opis zadania i wskazówki dotyczące implementacji zapisywania najlepszych wyników.

---

## 🛠️ Jak zacząć?

### Wymagania
- Node.js (wersja 18 lub nowsza)
- Podstawowa znajomość JavaScript
- Edytor kodu (zalecamy VS Code)

### Instalacja

1. **Sklonuj repozytorium:**
```bash
git clone https://github.com/Fundacja-Try-IT/kurs-typescript-react.git
cd kurs-react-memory
```

2. **Przełącz się na gałąź `react-podstawy`:**
```bash
git checkout react-podstawy
```

3. **Zainstaluj zależności:**
```bash
npm install
```

4. **Uruchom projekt:**
```bash
npm run dev
```

Aplikacja dostępna pod adresem `http://localhost:5173/`

---

## 🎯 Nawigacja między gałęziami

```bash
# Zobacz wszystkie gałęzie
git branch -a

# Przełącz się na wybraną gałąź
git switch nazwa-gałęzi

# Wróć do głównej gałęzi
git switch main

# Zobacz historię commitów w danej gałęzi
git log --oneline nazwa-gałęzi
```

---

## 📞 Wsparcie

- Dokumentacja React: [https://react.dev](https://react.dev)
- Fundacja Try IT: [https://www.tryit.org.pl](https://www.tryit.org.pl)
- Issues na GitHub: [zgłoś problem](https://github.com/Fundacja-Try-IT/kurs-typescript-react/issues)

---

## 📝 Licencja

MIT License - projekt edukacyjny Fundacji Try IT

**Credits:** Grafiki owoców autorstwa [Conania](https://www.iconfinder.com/iconsets/fruit-and-vegetable-15), licencja [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/)

---

**Powodzenia w nauce! 🚀**

*Projekt stworzony z ❤️ przez Wojciecha Kowalczyka dla Girls Go IT*