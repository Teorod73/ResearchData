# ZigZag forduló ablakok (2 x ATR1, fejlesztési időszak 2025-12-31-ig)

Minden sor egy forduló (a 0,3 és 0,5 közös fordulója egyszer számít).

## Esetszám

| év | rész | típus | összes | csak 0,3 | 0,5 is | nincs kezdet | nincs vég |
|---|---|---|---|---|---|---|---|
| 2024 | night | high | 1008 | 665 | 343 | 121 | 110 |
| 2024 | night | low | 1023 | 669 | 354 | 125 | 120 |
| 2024 | none | high | 338 | 213 | 125 | 85 | 78 |
| 2024 | none | low | 340 | 211 | 129 | 84 | 76 |
| 2024 | rth | high | 490 | 275 | 215 | 28 | 25 |
| 2024 | rth | low | 471 | 273 | 198 | 22 | 21 |
| 2025 | night | high | 1154 | 764 | 390 | 202 | 182 |
| 2025 | night | low | 1144 | 749 | 395 | 183 | 180 |
| 2025 | none | high | 362 | 209 | 153 | 119 | 110 |
| 2025 | none | low | 368 | 215 | 153 | 108 | 109 |
| 2025 | rth | high | 562 | 326 | 236 | 72 | 61 |
| 2025 | rth | low | 553 | 322 | 231 | 64 | 67 |

Vizsgálható (night / rth, van kezdet és vég): 5203. Ebből az ablak 09:30 előtt kezdődik, de a forduló 09:30 után van: 25.

## Az ablak hossza (perc)

| rész | n | medián előtte | q90 előtte | medián utána | q90 utána |
|---|---|---|---|---|---|
| night | 3397 | 3 | 9 | 5 | 13 |
| rth | 1806 | 4 | 12 | 6 | 15 |

## k = (High - belépő nyitó + 20 tick) / ATR1

A könyvsáv szorzója (N) legalább ekkora kell legyen, hogy a sáv minden esetben 20 tickkel a High fölé (Low alá) érjen.

| csoport | n | medián | q90 | q95 | q99 | max |
|---|---|---|---|---|---|---|
| összes | 5203 | 5.83 | 11.18 | 13.45 | 17.44 | 56.48 |
| night | 3397 | 7.16 | 12.52 | 14.67 | 18.39 | 56.48 |
| rth | 1806 | 4.45 | 6.22 | 6.86 | 8.79 | 15.05 |
| night high | 1692 | 7.35 | 12.90 | 14.91 | 18.09 | 23.70 |
| night low | 1705 | 7.02 | 12.18 | 14.42 | 18.52 | 56.48 |
| rth high | 914 | 4.65 | 6.40 | 6.88 | 8.23 | 13.16 |
| rth low | 892 | 4.31 | 5.97 | 6.70 | 9.37 | 15.05 |

A legnagyobb k értékek:

| session | rész | típus | k | ATR1 | elmozdulás (ATR1) | perc előtte |
|---|---|---|---|---|---|---|
| 2024-05-14 | night | low | 56.48 | 0.65 | 48.79 | 0 |
| 2025-08-26 | night | low | 33.91 | 0.73 | 27.06 | 0 |
| 2024-06-19 | night | low | 24.21 | 0.23 | 2.20 | 2 |
| 2024-07-12 | night | low | 23.98 | 0.97 | 18.82 | 0 |
| 2024-05-28 | night | high | 23.70 | 0.25 | 3.95 | 1 |
| 2024-02-12 | night | low | 23.48 | 0.26 | 3.91 | 3 |
| 2025-06-05 | night | high | 22.49 | 1.83 | 19.76 | 0 |
| 2024-02-09 | night | high | 21.90 | 0.27 | 3.65 | 5 |
| 2024-07-04 | night | low | 21.67 | 0.27 | 2.83 | 3 |
| 2024-04-10 | night | low | 21.39 | 0.27 | 2.79 | 2 |

ATR1 (pont):

| rész | medián | q10 | q90 |
|---|---|---|---|
| night | 1.16 | 0.53 | 3.00 |
| rth | 2.94 | 1.57 | 5.74 |

Tx (másodperc) megtalálva: 5203 / 5203.
