**Polski** | [English](README.en.md)

# Portfolio w HTML

Wielostronicowa strona-portfolio w czystym **HTML**, wykonana jako ćwiczenie z kursu tworzenia stron, dotyczące łączenia podstron i porządkowania projektu w folderach.

## Podstrony

- **`index.html`** — strona główna z odnośnikami i podglądami dwóch wcześniejszych projektów,
- **`public/movie-ranking.html`** — projekt Movie Ranking (top 3 filmy),
- **`public/birthday-invite.html`** — projekt Birthday Invite (zaproszenie na urodziny),
- **`public/about.html`** — O mnie,
- **`public/contact.html`** — Kontakt.

`goal.png` i `solution.html` to materiały wzorcowe z kursu.

## Struktura

```
index.html
public/          – podstrony
assets/images/   – podglądy projektów
```

## Uruchomienie

Odnośniki używają ścieżek względem katalogu głównego (np. `/public/about.html`), więc stronę otwieraj przez lokalny serwer, a nie dwuklikiem w plik — np. rozszerzeniem **Live Server** w VS Code albo:

```bash
python -m http.server
```

i wejdź na <http://localhost:8000>.
