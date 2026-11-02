# DESIGN.md – portfolio Anny Ziółkowskiej

**Idea przewodnia:** tryb sugestii. Strona wygląda jak dokument w edytorze, w którym Anna poprawia tekst: skreśla puste frazy, wpisuje konkret i zostawia komentarze na marginesie. Portfolio pokazuje sposób pracy, zamiast go opisywać.

## Paleta
| Rola | Kolor |
|---|---|
| Tło (blat) | `#EEF0F2` |
| Arkusz, karty | `#FFFFFF` |
| Linia | `#E3E5E8` |
| Tekst | `#15171A` |
| Tekst pomocniczy | `#3B4048` |
| Wyciszony | `#646A73` |
| Zakreślacz (wyróżnienia, inicjały) | `#FFE45C` |
| Wstawienie (poprawka, status) | `#0B7A45` na `#E2F5EA` |
| Usunięcie (skreślenie) | `#C8372B` na `#FBE6E3` |

Czerwony i zielony zawsze razem z drugim sygnałem (skreślenie / podkreślenie), nigdy jako jedyna informacja.

## Typografia
- **Bricolage Grotesque** (700, 800) – nagłówki i liczby.
- **Inter** – tekst, przyciski, formularz.
- **IBM Plex Mono** – drobne etykiety (nazwy źródeł, podpisy statystyk, komentarze).
- Fonty hostowane lokalnie w `fonts/`.

## Elementy
- Arkusz dokumentu z cieniem jako hero i sekcja „O mnie”.
- Komentarze na marginesie; najechanie na komentarz podświetla frazę, której dotyczy.
- Wizytówka z inicjałami (miejsce na zdjęcie 4:5, instrukcja w komentarzu HTML).
- Projekty w siatce kafelków o różnej szerokości; ciemne kafelki z przykładami UX writingu (przed → po).
- „Historia wersji”: żółte punkty = etapy, które Anna robi sama; szare = z pomocą AI.
- Liczby w hero prowadzą do dowodów (case study, biblioteka, O mnie).
- Linki zewnętrzne oznaczone ↗ i nazwą serwisu.
- Telefon: jednorzędowy pasek z przyciskiem Menu, chowany przy przewijaniu w dół; zakładki w „Historii wersji”; zwijane kompetencje.
- Druk / „Zapisz jako PDF”: czysty dokument na 3 strony A4 z danymi kontaktowymi.
- Case study i strona 404 w tym samym stylu.
- Kontakt: prawdziwy formularz z walidacją, który przygotowuje wiadomość e-mail, z uczciwą informacją, że trzeba ją wysłać z programu pocztowego.

## Ruch
- Skreślenie i wpisywanie poprawki w nagłówku, komentarze pojawiają się po kolei.
- Pulsujący status „Otwarta na nową rolę”, łagodne wejście sekcji, podniesienie kafelków przy najechaniu.
- Wszystko wyłączone przy `prefers-reduced-motion`.

## Czego unikać
Etykiet sugerujących nieistniejące pliki, powtarzania tej samej zasady w kilku miejscach, elementów udających pola formularza, zmyślonych liczb i opinii, beżów i szeryfów w stylu Claude.
