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

Van kezdet és vég (night / rth): 5203. Kizárva, mert a High gyertyája a belépő gyertya (nincs egész perc a High előtt): 516, mert átnyúlik egy UTC napon: 19.
**Vizsgált ablakok: 4668** (night 2978, rth 1690). Ebből az ablak 09:30 előtt kezdődik, de a forduló 09:30 után van: 25.

## Az ablak hossza (perc)

| rész | n | medián előtte | q90 előtte | medián utána | q90 utána |
|---|---|---|---|---|---|
| night | 2978 | 4 | 10 | 5 | 14 |
| rth | 1690 | 5 | 12 | 6 | 15 |

## A könyvsáv fele (tick): belépő nyitó +- (High - belépő nyitó + 20 tick)

| csoport | n | medián | q90 | q95 | q99 | max |
|---|---|---|---|---|---|---|
| összes | 4668 | 39 | 71 | 85 | 130 | 257 |
| night | 2978 | 33 | 55 | 66 | 106 | 176 |
| rth | 1690 | 52 | 85 | 103 | 159 | 257 |

ATR1 (pont):

| rész | medián | q10 | q90 |
|---|---|---|---|
| night | 1.20 | 0.54 | 3.08 |
| rth | 3.00 | 1.60 | 5.81 |

Tx (másodperc) megtalálva: 4668 / 4668.
