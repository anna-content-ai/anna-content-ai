# DESIGN.md – portfolio Anny Ziółkowskiej

**Idea przewodnia:** redakcja. Strona wygląda jak tekst po korekcie: ciepły papier, atrament i czerwony długopis, który poprawia to, co nie działa.

## Paleta
| Rola | Kolor |
|---|---|
| Papier (tło) | `#F5F0E6` |
| Papier 2 (panele) | `#EDE6D8` |
| Karta | `#FBF8F2` |
| Linia | `#D9D0BF` |
| Atrament (tekst, ciemne bloki) | `#1A1814` |
| Atrament 2 (tekst pomocniczy) | `#46423A` |
| Wyciszony | `#6B6456` |
| Korekta (akcent) | `#C23B22` |
| Korekta jasna (tła etykiet) | `#F3D9CF` |

Akcent czerwony tylko do: skreśleń, poprawek, wyróżnionych słów w nagłówkach, etykiet ról i liczb. Nigdy jako tło dużych powierzchni.

## Typografia
- **Instrument Serif** – nagłówki, liczby, tytuły projektów; kursywa = „poprawka”.
- **Inter** – tekst, przyciski, etykiety.
- Fonty hostowane lokalnie w `fonts/`.

## Elementy
- Karty: zaokrąglenie 22–26 px, cienka linia, delikatny cień przy najechaniu.
- Przyciski: pigułki min. 52 px wysokości; ciemny = główna akcja, obrys = druga.
- Etykieta „człowiek” w procesach = etap wykonywany przez Annę.

## Ruch
- Skreślenie i poprawka w nagłówku przy wejściu na stronę.
- Sekcje wjeżdżają łagodnie przy przewijaniu.
- Wszystko wyłączone przy `prefers-reduced-motion`.

## Czego unikać
Gradientów fiolet–niebieski, ikonek w kółkach, emoji, generycznych haseł („innowacyjne rozwiązania” – chyba że skreślone), zmyślonych liczb i opinii.
