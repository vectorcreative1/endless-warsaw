# PIXEL FIGHT — prototyp bijatyki 8-bit

Jeden plik `index.html` (HTML5 Canvas, bez zależności). Otwórz w przeglądarce.

## Tryby
- **1 PLAYER** — gracz vs CPU
- **2 PLAYERS** — dwóch graczy na jednej klawiaturze
- W tle menu walczą dwa boty (tryb demo)

## Sterowanie
| | P1 | P2 |
|---|---|---|
| Ruch / skok / kucnięcie | WASD | strzałki |
| Cios | J | , (lub Num1) |
| Kopnięcie | K | . (lub Num2) |
| Blok | L | / (lub Num3) |
| Special (skrót) | I | ; (lub Num5) |

- dół + cios — podbródkowy (wybija w powietrze)
- dół + kopnięcie — podcięcie (blokuje się tylko kucając)
- dół, przód + cios — pocisk energii
- skok + cios/kopnięcie — kopnięcie z powietrza
- Esc — menu

Na telefonie (poziomo) pojawiają się przyciski dotykowe.

## Mechanika
Rundy do 2 wygranych, timer 60 s, combo z licznikiem, hit-stop, trzęsienie ekranu,
„PERFECT!”, a w decydującej rundzie — „FINISH!” i dobicie przeciwnika („FINAL BLOW!”).

## Grafika
Postacie są rysowane kodem (placeholdery). Docelowo podmieniamy je na sprite’y
od grafika klienta: ~8–15 animacji na postać (stance, chód, cios, kopnięcie, blok,
kucnięcie, skok, trafienie, upadek, wygrana, special).
