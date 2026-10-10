# Sablon-diagnosztika (kereskedés nélkül)

Jelöltek C# adattal: minden ZigZag-jelölt és a többi jelölt 10%-os mintája (súly 10). Normalizált idő a valódi véggel (T0 = -1, csúcs = 0, vég = +1). d = a két sablon mediánjának különbsége a két robusztus szórás átlagában (binenként). Előtte = a -1..0 binek |d| átlaga, utána = a 0..1 binek |d| átlaga.

## Ablakok

| év | rész | forduló | lezárult nem forduló | érvénytelenült |
|---|---|---|---|---|
| 2024 | night | 1452 | 1140 | 1564 |
| 2024 | rth | 823 | 399 | 827 |
| 2025 | night | 1500 | 1029 | 1699 |
| 2025 | rth | 848 | 400 | 847 |

## Éjszaka

| görbe | év | forduló - összes (előtte / utána) | lezárult - összes | érvénytelenült - összes | forduló - lezárult max |d| | érvénytelenült / forduló szórás (utána) | profil r 2024-2025 | marad |
|---|---|---|---|---|---|---|---|---|
| delta | 2024 | 0.04 / 0.18 | 0.02 / 0.19 | 0.02 / 0.15 | 0.24 | 1.00 | 0.96 | igen |
| delta | 2025 | 0.06 / 0.19 | 0.04 / 0.20 | 0.02 / 0.13 | 0.34 | 1.02 |  | |
| def_cancel | 2024 | 0.08 / 0.26 | 0.02 / 0.25 | 0.01 / 0.19 | 0.50 | 0.90 | 0.99 | igen |
| def_cancel | 2025 | 0.10 / 0.19 | 0.03 / 0.27 | 0.01 / 0.18 | 0.49 | 0.93 |  | |
| att_cancel | 2024 | 0.05 / 0.29 | 0.03 / 0.24 | 0.02 / 0.18 | 0.32 | 0.86 | 0.98 | igen |
| att_cancel | 2025 | 0.09 / 0.30 | 0.04 / 0.26 | 0.02 / 0.17 | 0.46 | 0.92 |  | |
| def_refill | 2024 | 0.13 / 0.08 | 0.04 / 0.16 | 0.02 / 0.11 | 0.29 | 1.04 | 0.92 | igen |
| def_refill | 2025 | 0.17 / 0.11 | 0.04 / 0.18 | 0.01 / 0.10 | 0.43 | 1.06 |  | |
| att_refill | 2024 | 0.18 / 0.32 | 0.05 / 0.16 | 0.02 / 0.14 | 0.37 | 1.13 | 0.97 | igen |
| att_refill | 2025 | 0.22 / 0.36 | 0.08 / 0.11 | 0.03 / 0.10 | 0.42 | 1.22 |  | |
| att_eff | 2024 | 0.20 / 0.27 | 0.07 / 0.28 | 0.03 / 0.13 | 0.58 | 0.94 | 0.97 | igen |
| att_eff | 2025 | 0.26 / 0.23 | 0.08 / 0.31 | 0.02 / 0.15 | 0.55 | 1.05 |  | |
| def_eff | 2024 | 0.05 / 0.18 | 0.03 / 0.31 | 0.02 / 0.17 | 0.49 | 1.11 | 0.96 | igen |
| def_eff | 2025 | 0.13 / 0.16 | 0.04 / 0.31 | 0.02 / 0.18 | 0.59 | 1.19 |  | |
| balance | 2024 | 0.34 / 0.14 | 0.07 / 0.17 | 0.02 / 0.11 | 0.46 | 1.08 | 0.98 | igen |
| balance | 2025 | 0.26 / 0.15 | 0.02 / 0.13 | 0.01 / 0.07 | 0.36 | 1.07 |  | |
| volume | 2024 | 0.46 / 0.42 | 0.13 / 0.06 | 0.05 / 0.03 | 0.71 | 0.65 | 0.71 | igen |
| volume | 2025 | 0.56 / 0.55 | 0.09 / 0.06 | 0.01 / 0.04 | 0.76 | 0.46 |  | |
| large_delta | 2024 | 0.11 / 0.07 | 0.07 / 0.06 | 0.06 / 0.04 | 0.44 | 1.25 | 0.49 | nem |
| large_delta | 2025 | 0.05 / 0.05 | 0.05 / 0.08 | 0.02 / 0.04 | 0.44 | 1.53 |  | |
| large_delta_post | 2024 | nan / 0.15 | nan / 0.08 | nan / 0.04 | 0.67 | 1.10 | 0.68 | igen |
| large_delta_post | 2025 | nan / 0.08 | nan / 0.13 | nan / 0.08 | 0.56 | 1.27 |  | |
| large_div | 2024 | 0.08 / 0.09 | 0.05 / 0.04 | 0.03 / 0.03 | 0.26 | 1.20 | 0.53 | igen |
| large_div | 2025 | 0.02 / 0.03 | 0.02 / 0.06 | 0.02 / 0.04 | 0.16 | 1.45 |  | |
| large_div_post | 2024 | nan / 0.12 | nan / 0.06 | nan / 0.03 | 0.34 | 1.19 | 0.76 | igen |
| large_div_post | 2025 | nan / 0.06 | nan / 0.12 | nan / 0.07 | 0.24 | 1.32 |  | |

## RTH

| görbe | év | forduló - összes (előtte / utána) | lezárult - összes | érvénytelenült - összes | forduló - lezárult max |d| | érvénytelenült / forduló szórás (utána) | profil r 2024-2025 | marad |
|---|---|---|---|---|---|---|---|---|
| delta | 2024 | 0.06 / 0.25 | 0.07 / 0.25 | 0.03 / 0.15 | 0.29 | 0.94 | 0.95 | igen |
| delta | 2025 | 0.05 / 0.24 | 0.06 / 0.23 | 0.02 / 0.13 | 0.25 | 1.03 |  | |
| def_cancel | 2024 | 0.11 / 0.22 | 0.04 / 0.21 | 0.03 / 0.12 | 0.33 | 0.86 | 0.95 | igen |
| def_cancel | 2025 | 0.08 / 0.17 | 0.04 / 0.20 | 0.03 / 0.11 | 0.24 | 0.97 |  | |
| att_cancel | 2024 | 0.11 / 0.13 | 0.06 / 0.15 | 0.04 / 0.08 | 0.27 | 0.95 | 0.93 | igen |
| att_cancel | 2025 | 0.07 / 0.13 | 0.04 / 0.15 | 0.02 / 0.07 | 0.18 | 1.02 |  | |
| def_refill | 2024 | 0.13 / 0.11 | 0.05 / 0.23 | 0.02 / 0.11 | 0.44 | 0.94 | 0.90 | igen |
| def_refill | 2025 | 0.14 / 0.12 | 0.06 / 0.20 | 0.02 / 0.08 | 0.43 | 1.05 |  | |
| att_refill | 2024 | 0.18 / 0.37 | 0.10 / 0.15 | 0.03 / 0.10 | 0.40 | 1.03 | 0.93 | igen |
| att_refill | 2025 | 0.19 / 0.32 | 0.08 / 0.10 | 0.02 / 0.09 | 0.38 | 1.10 |  | |
| att_eff | 2024 | 0.11 / 0.24 | 0.09 / 0.28 | 0.03 / 0.13 | 0.46 | 1.01 | 0.97 | igen |
| att_eff | 2025 | 0.13 / 0.24 | 0.06 / 0.31 | 0.02 / 0.15 | 0.57 | 1.04 |  | |
| def_eff | 2024 | 0.09 / 0.22 | 0.06 / 0.26 | 0.02 / 0.14 | 0.48 | 1.17 | 0.95 | igen |
| def_eff | 2025 | 0.11 / 0.23 | 0.05 / 0.30 | 0.02 / 0.14 | 0.47 | 1.17 |  | |
| balance | 2024 | 0.04 / 0.03 | 0.11 / 0.22 | 0.05 / 0.11 | 0.35 | 1.01 | 0.63 | igen |
| balance | 2025 | 0.15 / 0.11 | 0.19 / 0.21 | 0.07 / 0.09 | 0.41 | 1.00 |  | |
| volume | 2024 | 0.52 / 0.60 | 0.08 / 0.12 | 0.02 / 0.06 | 0.76 | 0.57 | 0.90 | igen |
| volume | 2025 | 0.55 / 0.60 | 0.13 / 0.09 | 0.02 / 0.06 | 0.73 | 0.68 |  | |
| large_delta | 2024 | 0.06 / 0.12 | 0.04 / 0.13 | 0.02 / 0.07 | 0.12 | 1.31 | 0.80 | igen |
| large_delta | 2025 | 0.07 / 0.12 | 0.05 / 0.22 | 0.02 / 0.09 | 0.22 | 1.19 |  | |
| large_delta_post | 2024 | nan / 0.08 | nan / 0.12 | nan / 0.07 | 0.41 | 1.58 | 0.76 | igen |
| large_delta_post | 2025 | nan / 0.12 | nan / 0.11 | nan / 0.06 | 0.61 | 1.79 |  | |
| large_div | 2024 | 0.06 / 0.10 | 0.04 / 0.10 | 0.02 / 0.05 | 0.11 | 1.29 | 0.91 | igen |
| large_div | 2025 | 0.08 / 0.10 | 0.04 / 0.19 | 0.02 / 0.08 | 0.23 | 1.18 |  | |
| large_div_post | 2024 | nan / 0.07 | nan / 0.11 | nan / 0.07 | 0.37 | 1.65 | 0.70 | igen |
| large_div_post | 2025 | nan / 0.11 | nan / 0.11 | nan / 0.05 | 0.50 | 1.78 |  | |

Marad: 2024-ben valamelyik jó sablon legalább egy binben ≥ 0.1 eltérés az összes jelölttől, és a jó - összes eltérés-profil (a két jó osztály átlaga, 40 bin) 2024 és 2025 között r ≥ 0.5. Összevonható a két jó sablon, ha a forduló - lezárult |d| minden binben < 0.25.

## Görbék együttmozgása (2024, ablak x bin értékek, |r| ≥ 0,5)

| rész | görbe | görbe | r |
|---|---|---|---|
| night | delta | att_cancel | -0.52 |
| night | delta | att_eff | +0.53 |
| night | delta | def_eff | -0.56 |
| night | def_cancel | att_cancel | -0.64 |
| night | def_cancel | att_eff | +0.66 |
| night | def_cancel | def_eff | -0.66 |
| night | att_cancel | att_eff | -0.68 |
| night | att_cancel | def_eff | +0.67 |
| night | att_eff | def_eff | -0.76 |
| night | large_delta | large_delta_post | +0.60 |
| night | large_delta | large_div | +0.97 |
| night | large_delta | large_div_post | +0.59 |
| night | large_delta_post | large_div | +0.60 |
| night | large_delta_post | large_div_post | +0.98 |
| night | large_div | large_div_post | +0.60 |
| rth | delta | att_eff | +0.65 |
| rth | delta | def_eff | -0.68 |
| rth | def_cancel | att_eff | +0.60 |
| rth | def_cancel | def_eff | -0.59 |
| rth | att_cancel | att_eff | -0.59 |
| rth | att_cancel | def_eff | +0.60 |
| rth | def_refill | att_eff | -0.53 |
| rth | def_refill | def_eff | +0.53 |
| rth | att_refill | att_eff | +0.51 |
| rth | att_refill | def_eff | -0.52 |
| rth | att_eff | def_eff | -0.91 |
| rth | large_delta | large_div | +0.99 |
| rth | large_delta_post | large_div_post | +0.99 |
