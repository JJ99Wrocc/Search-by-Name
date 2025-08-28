# Search-by-Name 🔍

**Krótki opis:**  
Lekka i responsywna aplikacja frontendowa do wyszukiwania danych (np. użytkowników, produktów) po imieniu/nazwie. Zbudowana w czystym HTML, CSS/SCSS oraz JavaScript — idealna do embedowania jako komponent lub część większej aplikacji.

---

##  Live Demo  
https://jj99wrocc.github.io/Search-by-Name/


---

##  Jak to działa

- Wprowadź nazwę/imę w polu wyszukiwania.
- Aplikacja dynamicznie filtruje i wyświetla pasujące wyniki.
- Stylizacja oparta na SCSS zapewnia łatwe dostosowanie wyglądu.
- Responsywna layout obsługuje różne rozdzielczości i urządzenia.

---

##  Technologie

- **HTML5** – struktura aplikacji.  
- **CSS3 / SCSS** – stylizacja i modularność kodu.  
- **JavaScript (vanilla)** – logika interakcji i filtrowania wyników.  
- (Opcjonalnie) **GitHub Actions** – automatyzacja testów, budowania i wdrażania :contentReference[oaicite:1]{index=1}.

---

##  Instrukcja uruchomienia lokalnie

1. Sklonuj repozytorium:  
   ```bash
   git clone https://github.com/JJ99Wrocc/Search-by-Name.git
   cd Search-by-Name
   npm install
   npm start
   Podczas rozwijania projektu, możesz używać tej struktury:

<div class="search-container">
  <input type="text" id="searchInput" placeholder="Wpisz nazwę...">
  <div id="results"></div>
</div>
<script src="javascript/app.js"></script>


SCSS możesz modyfikować w scss/, np.:

$primary-color: #3498db;

.search-container {
  input {
    border: 2px solid $primary-color;
    padding: 0.5rem;
    font-size: 1rem;
  }
}

Możliwości rozwoju

Podłączenie zewnętrznego API (np. REST) do pobierania danych dynamicznie.

Wersja komponentowa: Vue, React lub Web Component.

Udoskonalone wyszukiwanie (autouzupełnianie, fuzzy search).

Obsługa wielu języków i lokalizacji.

Co zyskałem tworząc projekt

Praktyka w pisaniu modularnego kodu w HTML/CSS/JS.

Praca z preprocesorem SCSS — czystszy i bardziej skalowalny CSS.

Doświadczenie z GitHub Actions — automatyzacja budowania i testowania.

Licencja

Autor: Joachim Esangbedo
