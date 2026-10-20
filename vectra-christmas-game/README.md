# 35 LAT VECTRY — wersja świąteczna (osobny projekt)

Kopia gry `vectra-crystal-game` (stan z 20.10.2026, commit bazowy `2469538`) jako
osobny projekt. Tu powstaje wersja świąteczna: bohaterowie i świat **nie w pikselach**.

- Kod: jeden plik `index.html` + folder `assets/` (bez `assets/X/` — nieużywane pliki).
- Grafiki do podmiany wrzucamy do `assets/` pod tymi samymi nazwami (lub zmieniamy ścieżki w `index.html`).
- `CONTEST_END_MS` ustawione na rok 2099 — trzeba wpisać prawdziwą datę końca konkursu świątecznego.
- Uwaga: konfiguracja Firebase (ranking) jest nadal ta sama co w wersji jubileuszowej
  (projekt `vectragame`, kolekcje `scores`, `nicknames`, `rate_limits`) — wyniki obu gier
  trafiałyby do tego samego rankingu. Przed publicznym startem trzeba rozdzielić bazę.
- Surowe materiały (np. filmy z Kling) leżą poza tym folderem, w `christmass_game/`
  i nie są częścią repozytorium.
