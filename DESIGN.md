# DESIGN.md – portfolio Anny Ziółkowskiej

**Idea przewodnia:** „Oliwka nocą”. Nowoczesny styl technologiczny w ziemistych kolorach. Strona wygląda jak produkt: hero z panelem „przeglądu treści”, który pokazuje sposób pracy Anny (skreślona pusta fraza → konkret → lista kontrolna z ostatnim słowem człowieka).

## Paleta
| Rola | Kolor |
|---|---|
| Tło | `#14170F` (prawie czarna oliwka) |
| Powierzchnia (karty, panele) | `#1D2116` |
| Powierzchnia 2 (etykiety) | `#252A1D` |
| Linia | `#30362A` / `#3A4030` |
| Tekst | `#ECEBE4` |
| Tekst pomocniczy | `#B9BCAE` |
| Wyciszony | `#8F9483` |
| Akcent – terakota | `#E2683C` (tekst na niej: `#14170F`) |
| Drugi akcent – szałwia | `#A3B18A`, tekst `#C3CEA9` |

Terakota: główne przyciski, wyróżnione słowa, etapy „robię sama”, logo. Szałwia: status „otwarta na nową rolę”, odhaczone punkty, poprawiony tekst. Bez kremowych teł i szeryfów (zbyt podobne do stylu Claude).

## Typografia
- **Space Grotesk** (500, 700) – nagłówki i liczby.
- **Inter** – tekst, przyciski, formularz.
- **IBM Plex Mono** – drobne etykiety, numery sekcji, statusy.
- Fonty hostowane lokalnie w `fonts/`.

## Elementy
- Delikatna siatka w tle hero i ciepła poświata terakoty.
- Panel przeglądu treści: wpisywana poprawka i odhaczana lista (pętla co ok. 9 s).
- Liczby pod hero prowadzą do dowodów (O mnie, biblioteka, case study).
- Projekty w siatce kafelków; ciemne kafelki z przykładami UX writingu; poświata za kursorem.
- Proces: trzy ścieżki z etapami „AI” i „Anna”; na telefonie zakładki.
- O mnie: karta z inicjałami (miejsce na zdjęcie opisane w komentarzu HTML), linki, „Zapisz jako PDF”; kompetencje zwijane na telefonie.
- Kontakt: LinkedIn, kopiowanie adresu i prawdziwy formularz z walidacją (przygotowuje wiadomość e-mail).
- Case study i strona 404 w tym samym stylu; wersja do druku na jasnym tle.

## Ruch
Wpisywanie poprawki, odhaczanie listy, pulsujący status, dryfująca poświata, łagodne wejście sekcji, chowany pasek przy przewijaniu w dół. Wszystko wyłączone przy `prefers-reduced-motion`.
