# Esemény-sorrend minták (5. lépés)

Ablakok: 2024 night: 1367, 2024 rth: 765, 2025 night: 1511, 2025 rth: 862

Átmegy: a valódi darabszám nagyobb a 1000 „időzítés” keverés 99%-os kvantilisénél (minden esemény megtartja a saját időzítését és gyakoriságát, csak az ablakok keverednek, hasonló eseményszámú ablakok között). Azonos görbéből két esemény nem lehet egy mintában. gyak. = az ablakok %-a, várt = az időzítés-keverés átlaga, sima / szigorú = a két régi keverés 99%-os szintje, u = a minta utolsó eseményének medián normalizált ideje (csúcs = 0).

## Éjszaka

| hossz | jelölt | átment 2024 | átment 2024 és 2025 |
|---|---|---|---|
| 2 | 2856 | 491 | 384 |
| 3 | 1482 | 1406 | 1266 |
| 4 | 2000 | 1936 | 1745 |

### A leggyakoribb minták, amelyek 2024-ben és 2025-ben is átmennek: minden esemény

| minta | gyak. 2024 | várt 2024 | sima q99 | szigorú q99 | u 2024 | gyak. 2025 | várt 2025 |
|---|---|---|---|---|---|---|---|
| def_hidden_lo > def_eff_up > att_eff_peak > delta_lo | 14.6 | 5.8 | 2.2 | 5.0 | 0.33 | 12.3 | 5.0 |
| def_hidden_lo > def_eff_up > att_eff_peak > att_cancel_hi | 14.5 | 6.4 | 2.1 | 5.2 | 0.45 | 14.7 | 5.9 |
| def_hidden_lo > def_eff_up > att_eff_peak > att_refill_lo | 14.1 | 5.6 | 2.2 | 4.7 | 0.39 | 12.2 | 5.1 |
| def_hidden_lo > def_eff_up > att_eff_peak > cross_large | 14.0 | 6.1 | 2.6 | 5.0 | 0.24 | 14.9 | 6.6 |
| def_hidden_lo > def_eff_up > att_eff_peak > def_large_down | 13.5 | 5.1 | 2.8 | 4.6 | 0.18 | 13.0 | 5.1 |
| def_hidden_lo > def_eff_up > att_eff_down > att_cancel_hi | 13.3 | 6.9 | 2.1 | 5.7 | 0.49 | 15.1 | 6.0 |
| def_hidden_lo > def_eff_up > att_eff_peak > def_refill_hi | 11.9 | 4.3 | 1.8 | 4.0 | 0.29 | 10.3 | 3.7 |
| def_hidden_lo > def_eff_up > att_eff_down > delta_lo | 11.7 | 6.2 | 2.0 | 5.3 | 0.37 | 12.2 | 5.0 |
| def_hidden_lo > def_eff_up > att_eff_down > att_refill_lo | 11.7 | 6.0 | 2.2 | 5.2 | 0.43 | 10.3 | 5.1 |
| def_hidden_lo > def_eff_up > att_eff_down > cross_large | 11.3 | 6.3 | 2.8 | 5.3 | 0.28 | 12.9 | 6.3 |
| def_hidden_lo > def_eff_up > att_eff_up > def_large_hi | 11.0 | 5.6 | 2.3 | 4.5 | 0.34 | 9.3 | 5.0 |
| def_hidden_lo > def_eff_up > att_eff_down > att_large_peak | 9.7 | 4.4 | 3.2 | 4.5 | 0.08 | 9.5 | 4.0 |
| def_hidden_lo > def_eff_up > att_eff_up | 38.8 | 25.9 | 14.6 | 20.6 | 0.00 | 37.5 | 24.1 |
| def_hidden_lo > def_eff_up > att_eff_lo | 33.9 | 20.8 | 8.3 | 19.4 | 0.44 | 31.3 | 18.6 |
| def_hidden_lo > def_eff_up > att_eff_peak | 33.7 | 18.2 | 13.2 | 16.7 | -0.25 | 34.1 | 18.6 |
| def_hidden_lo > def_eff_up > att_eff_down | 32.9 | 22.8 | 13.6 | 20.2 | 0.03 | 34.2 | 22.1 |
| def_hidden_lo > att_eff_peak > def_eff_hi | 28.1 | 14.6 | 7.0 | 14.9 | 0.30 | 27.2 | 14.7 |
| def_hidden_lo > att_eff_peak > def_eff_down | 27.2 | 17.0 | 11.3 | 14.6 | -0.01 | 27.1 | 17.7 |
| def_eff_up > att_eff_peak > cross_large | 26.6 | 15.7 | 9.9 | 16.0 | 0.22 | 28.3 | 17.3 |
| att_large_up > delta_down > def_large_down | 26.1 | 14.8 | 12.3 | 15.6 | -0.09 | 26.9 | 15.5 |
| def_eff_up > def_refill_up > att_eff_up | 25.7 | 17.7 | 13.6 | 16.2 | 0.04 | 21.2 | 15.0 |
| def_hidden_lo > att_eff_up > def_eff_down | 25.6 | 17.2 | 12.1 | 15.7 | 0.00 | 26.5 | 17.8 |
| def_eff_up > delta_down > cross_large | 25.6 | 15.4 | 10.6 | 16.2 | 0.12 | 24.9 | 16.2 |
| def_eff_up > def_refill_up > cross_large | 25.1 | 16.2 | 10.8 | 16.4 | 0.16 | 21.4 | 15.4 |
| def_eff_up > att_eff_up | 64.1 | 56.6 | 45.8 | 53.8 | -0.02 | 62.5 | 53.3 |
| def_hidden_lo > att_eff_up | 63.7 | 59.2 | 42.1 | 51.5 | -0.06 | 62.5 | 58.9 |
| def_eff_up > att_eff_peak | 57.7 | 42.2 | 40.7 | 44.9 | -0.31 | 60.0 | 43.4 |
| def_hidden_lo > def_eff_up | 57.3 | 48.5 | 42.9 | 44.8 | -0.47 | 56.3 | 48.2 |
| def_hidden_lo > att_eff_peak | 56.2 | 46.9 | 36.8 | 42.4 | -0.39 | 57.3 | 49.9 |
| def_eff_up > att_eff_down | 56.0 | 49.7 | 42.8 | 52.2 | 0.02 | 56.5 | 48.3 |
| def_hidden_lo > att_eff_down | 54.6 | 52.5 | 38.5 | 48.6 | 0.01 | 54.9 | 53.1 |
| def_eff_up > def_refill_up | 52.2 | 45.0 | 39.2 | 45.1 | -0.11 | 46.5 | 42.3 |
| att_large_up > def_refill_up | 50.7 | 44.6 | 39.1 | 44.8 | -0.24 | 53.4 | 47.7 |
| def_eff_up > att_large_peak | 49.9 | 42.9 | 37.9 | 41.5 | -0.20 | 49.3 | 43.0 |
| def_eff_up > cross_large | 49.9 | 44.0 | 33.0 | 42.6 | 0.12 | 53.7 | 47.8 |
| def_hidden_lo > def_eff_down | 49.6 | 46.3 | 34.5 | 40.2 | -0.12 | 50.9 | 48.6 |

### A leggyakoribb minták, amelyek 2024-ben és 2025-ben is átmennek: csak könyv- és orderflow-események (delta és hatékonyság nélkül)

| minta | gyak. 2024 | várt 2024 | sima q99 | szigorú q99 | u 2024 | gyak. 2025 | várt 2025 |
|---|---|---|---|---|---|---|---|
| att_large_up > def_cancel_down > att_cancel_up > def_large_down | 8.9 | 3.5 | 3.3 | 4.6 | 0.06 | 7.5 | 3.5 |
| att_large_up > def_cancel_down > def_refill_up > def_large_down | 8.7 | 3.9 | 3.3 | 4.4 | 0.05 | 6.6 | 3.6 |
| att_large_up > def_cancel_down > att_cancel_up > att_refill_lo | 8.5 | 4.0 | 2.0 | 4.3 | 0.39 | 6.8 | 3.7 |
| def_cancel_down > att_cancel_up > def_refill_up > cross_large | 8.2 | 3.8 | 2.8 | 4.5 | 0.13 | 6.8 | 3.4 |
| att_large_up > att_cancel_up > def_refill_up > def_large_down | 7.8 | 3.5 | 3.2 | 4.0 | 0.07 | 6.5 | 3.4 |
| att_large_up > def_cancel_down > att_cancel_up > def_refill_up | 7.8 | 3.1 | 3.4 | 4.5 | 0.02 | 7.2 | 3.7 |
| att_large_up > def_cancel_down > def_refill_up > att_cancel_down | 7.7 | 3.3 | 3.3 | 4.2 | 0.00 | 5.2 | 3.5 |
| att_large_up > def_cancel_down > def_refill_up > volume_down | 7.3 | 2.5 | 2.5 | 3.6 | 0.03 | 5.9 | 2.8 |
| def_cancel_down > def_refill_up > att_large_peak > volume_down | 7.2 | 2.1 | 2.3 | 2.9 | -0.11 | 5.9 | 2.1 |
| att_large_up > def_cancel_down > att_cancel_up > volume_down | 7.2 | 2.2 | 2.6 | 3.7 | 0.02 | 6.9 | 2.7 |
| def_cancel_down > att_cancel_up > def_refill_up > def_large_down | 7.1 | 3.0 | 3.3 | 3.7 | 0.09 | 4.3 | 2.5 |
| def_cancel_down > def_refill_up > att_large_peak > volume_peak | 6.8 | 1.5 | 1.8 | 2.5 | -0.17 | 5.5 | 1.6 |
| att_large_up > def_cancel_down > def_refill_up | 22.7 | 13.9 | 12.4 | 15.4 | -0.04 | 21.4 | 15.6 |
| att_large_up > def_cancel_down > att_cancel_up | 21.7 | 12.6 | 12.4 | 16.1 | -0.12 | 20.7 | 13.7 |
| def_cancel_down > def_refill_up > cross_large | 21.7 | 14.9 | 9.9 | 13.8 | 0.15 | 19.8 | 13.9 |
| att_large_up > def_refill_up > def_large_down | 21.7 | 15.1 | 12.3 | 15.4 | 0.04 | 18.7 | 14.5 |
| att_large_up > att_refill_down > def_large_down | 21.4 | 14.5 | 11.9 | 14.9 | -0.03 | 19.1 | 14.7 |
| def_cancel_down > att_cancel_up > cross_large | 20.8 | 13.7 | 10.0 | 13.8 | 0.16 | 19.3 | 13.7 |
| att_large_up > att_cancel_up > def_large_down | 20.8 | 13.7 | 11.9 | 14.9 | 0.05 | 20.4 | 14.6 |
| att_large_down > def_refill_up > def_large_down | 20.7 | 14.7 | 12.3 | 15.4 | 0.03 | 16.4 | 13.3 |
| att_large_up > def_cancel_down > def_large_down | 20.3 | 14.3 | 12.1 | 15.3 | -0.00 | 19.0 | 14.8 |
| att_large_up > att_cancel_up > def_refill_up | 20.0 | 13.0 | 12.0 | 14.9 | 0.01 | 22.7 | 15.2 |
| def_cancel_down > def_refill_up > def_large_down | 19.2 | 12.7 | 11.6 | 12.5 | -0.03 | 14.0 | 10.7 |
| def_cancel_down > def_refill_up > att_large_peak | 19.1 | 11.4 | 11.9 | 11.9 | -0.27 | 14.6 | 10.1 |
| att_large_up > def_refill_up | 50.7 | 44.6 | 39.1 | 44.8 | -0.24 | 53.4 | 47.7 |
| att_large_down > def_refill_up | 49.1 | 44.0 | 39.7 | 45.1 | -0.24 | 49.4 | 44.9 |
| att_large_up > att_cancel_up | 48.2 | 39.8 | 36.4 | 42.6 | -0.32 | 53.3 | 44.0 |
| att_large_up > att_refill_down | 47.8 | 39.8 | 37.1 | 40.7 | -0.38 | 46.5 | 42.0 |
| att_large_up > def_large_up | 47.4 | 44.0 | 37.9 | 44.8 | -0.10 | 50.3 | 47.6 |
| att_large_down > def_large_down | 47.3 | 42.5 | 36.9 | 43.4 | -0.11 | 47.3 | 44.2 |
| att_large_up > def_refill_down | 47.2 | 41.6 | 36.7 | 42.2 | -0.17 | 51.2 | 46.2 |
| att_large_up > def_large_down | 46.5 | 42.9 | 37.2 | 43.4 | -0.10 | 50.6 | 46.8 |
| def_cancel_down > att_large_peak | 45.9 | 37.2 | 36.1 | 36.0 | -0.37 | 43.6 | 36.7 |
| att_large_up > def_cancel_down | 45.4 | 38.5 | 38.3 | 42.0 | -0.33 | 49.4 | 43.4 |
| def_cancel_down > def_refill_up | 44.5 | 38.1 | 36.5 | 38.0 | -0.28 | 40.3 | 36.7 |
| att_large_up > att_cancel_down | 44.3 | 39.7 | 35.5 | 40.1 | -0.27 | 50.4 | 44.2 |

## RTH

| hossz | jelölt | átment 2024 | átment 2024 és 2025 |
|---|---|---|---|
| 2 | 1924 | 277 | 201 |
| 3 | 528 | 472 | 422 |
| 4 | 561 | 469 | 391 |

### A leggyakoribb minták, amelyek 2024-ben és 2025-ben is átmennek: minden esemény

| minta | gyak. 2024 | várt 2024 | sima q99 | szigorú q99 | u 2024 | gyak. 2025 | várt 2025 |
|---|---|---|---|---|---|---|---|
| delta_up > att_cancel_up > att_large_peak > volume_peak | 15.9 | 3.2 | 3.1 | 5.0 | -0.39 | 13.1 | 3.1 |
| att_cancel_down > def_cancel_down > att_large_peak > volume_peak | 14.5 | 3.2 | 3.3 | 5.2 | -0.31 | 12.3 | 3.1 |
| def_refill_down > att_cancel_up > att_large_peak > volume_peak | 13.7 | 2.9 | 3.1 | 4.6 | -0.28 | 11.7 | 2.8 |
| att_cancel_down > def_refill_up > att_large_peak > volume_peak | 13.5 | 3.2 | 3.0 | 4.8 | -0.39 | 12.1 | 3.2 |
| delta_up > def_cancel_down > att_large_peak > volume_peak | 13.5 | 3.4 | 3.1 | 5.1 | -0.28 | 10.1 | 3.2 |
| delta_up > def_refill_up > att_large_peak > volume_peak | 13.3 | 3.3 | 3.3 | 5.0 | -0.32 | 11.6 | 3.4 |
| delta_up > att_cancel_up > att_large_peak > volume_down | 13.1 | 3.1 | 2.7 | 4.6 | -0.20 | 10.1 | 2.8 |
| att_cancel_down > def_cancel_down > att_large_peak > volume_down | 12.4 | 3.1 | 2.6 | 4.8 | -0.21 | 10.9 | 2.8 |
| def_cancel_down > att_cancel_up > att_large_peak > volume_peak | 12.3 | 3.1 | 3.1 | 4.7 | -0.32 | 11.5 | 2.8 |
| def_cancel_down > def_refill_up > att_large_peak > volume_peak | 12.3 | 3.2 | 3.1 | 4.7 | -0.26 | 10.4 | 3.0 |
| att_cancel_down > att_refill_down > att_large_peak > volume_peak | 12.0 | 3.3 | 3.1 | 5.1 | -0.26 | 10.9 | 3.2 |
| delta_up > att_cancel_up > att_eff_down > volume_peak | 12.0 | 3.2 | 3.1 | 4.8 | -0.01 | 10.6 | 3.1 |
| delta_up > att_cancel_up > att_eff_down | 28.6 | 16.8 | 14.6 | 20.4 | 0.01 | 29.0 | 17.9 |
| att_cancel_up > att_large_peak > volume_peak | 28.5 | 11.9 | 9.9 | 13.2 | -0.36 | 25.6 | 11.7 |
| def_cancel_down > att_large_peak > volume_peak | 28.4 | 12.1 | 10.2 | 14.1 | -0.26 | 24.2 | 11.4 |
| delta_up > att_large_peak > volume_peak | 27.5 | 12.5 | 10.2 | 15.0 | -0.22 | 24.6 | 12.4 |
| att_cancel_down > def_cancel_down > att_eff_down | 26.7 | 16.5 | 15.3 | 20.4 | 0.02 | 25.4 | 18.0 |
| def_refill_down > att_cancel_up > att_eff_down | 26.5 | 15.5 | 14.4 | 19.3 | 0.01 | 25.9 | 16.6 |
| delta_up > att_cancel_up > att_large_peak | 26.4 | 13.1 | 15.0 | 16.3 | -0.46 | 23.7 | 12.1 |
| def_refill_up > att_large_peak > volume_peak | 26.4 | 12.3 | 9.9 | 13.1 | -0.31 | 23.3 | 11.6 |
| att_cancel_down > att_large_peak > volume_peak | 26.4 | 11.7 | 10.2 | 15.0 | -0.27 | 26.1 | 11.9 |
| delta_up > att_cancel_up > volume_peak | 26.4 | 11.6 | 10.6 | 14.9 | -0.19 | 23.3 | 11.0 |
| att_cancel_down > att_refill_down > def_large_down | 25.6 | 15.5 | 15.7 | 18.0 | -0.25 | 22.7 | 15.9 |
| delta_up > att_refill_down > def_large_down | 25.5 | 16.4 | 15.9 | 19.0 | -0.20 | 22.0 | 17.0 |
| att_cancel_down > def_large_down | 55.7 | 45.2 | 44.8 | 49.0 | -0.26 | 52.4 | 46.1 |
| att_refill_down > def_large_down | 54.4 | 46.3 | 45.2 | 48.1 | -0.25 | 50.7 | 46.3 |
| delta_up > att_large_peak | 54.2 | 43.8 | 44.3 | 46.9 | -0.42 | 51.3 | 42.4 |
| def_cancel_down > att_large_peak | 53.9 | 42.4 | 44.2 | 44.2 | -0.42 | 49.1 | 39.2 |
| delta_up > att_eff_down | 52.5 | 49.5 | 43.5 | 52.8 | 0.01 | 55.2 | 51.4 |
| def_cancel_down > def_large_down | 52.0 | 46.4 | 44.6 | 47.3 | -0.25 | 50.8 | 45.7 |
| att_cancel_up > att_eff_down | 51.9 | 47.2 | 42.2 | 47.6 | -0.13 | 53.7 | 47.9 |
| def_refill_up > att_large_peak | 51.8 | 42.8 | 44.6 | 43.9 | -0.48 | 48.7 | 40.6 |
| att_cancel_up > att_large_peak | 51.8 | 41.4 | 42.2 | 41.7 | -0.46 | 48.7 | 39.5 |
| def_refill_up > def_large_down | 51.8 | 47.0 | 45.2 | 47.8 | -0.22 | 50.2 | 47.2 |
| def_cancel_down > att_eff_down | 51.6 | 48.2 | 44.3 | 49.9 | 0.00 | 51.7 | 48.7 |
| delta_up > def_large_down | 51.0 | 47.6 | 45.0 | 50.3 | -0.22 | 50.9 | 48.5 |

### A leggyakoribb minták, amelyek 2024-ben és 2025-ben is átmennek: csak könyv- és orderflow-események (delta és hatékonyság nélkül)

| minta | gyak. 2024 | várt 2024 | sima q99 | szigorú q99 | u 2024 | gyak. 2025 | várt 2025 |
|---|---|---|---|---|---|---|---|
| att_cancel_down > def_cancel_down > att_large_peak > volume_peak | 14.5 | 3.2 | 3.3 | 5.2 | -0.31 | 12.3 | 3.1 |
| def_refill_down > att_cancel_up > att_large_peak > volume_peak | 13.7 | 2.9 | 3.1 | 4.6 | -0.28 | 11.7 | 2.8 |
| att_cancel_down > def_refill_up > att_large_peak > volume_peak | 13.5 | 3.2 | 3.0 | 4.8 | -0.39 | 12.1 | 3.2 |
| att_cancel_down > def_cancel_down > att_large_peak > volume_down | 12.4 | 3.1 | 2.6 | 4.8 | -0.21 | 10.9 | 2.8 |
| def_cancel_down > att_cancel_up > att_large_peak > volume_peak | 12.3 | 3.1 | 3.1 | 4.7 | -0.32 | 11.5 | 2.8 |
| def_cancel_down > def_refill_up > att_large_peak > volume_peak | 12.3 | 3.2 | 3.1 | 4.7 | -0.26 | 10.4 | 3.0 |
| att_cancel_down > att_refill_down > att_large_peak > volume_peak | 12.0 | 3.3 | 3.1 | 5.1 | -0.26 | 10.9 | 3.2 |
| def_cancel_down > att_cancel_up > att_large_peak > volume_down | 11.2 | 2.9 | 2.9 | 4.6 | -0.17 | 10.0 | 2.6 |
| att_cancel_down > def_refill_up > att_large_peak > volume_down | 11.1 | 3.1 | 2.7 | 4.6 | -0.25 | 11.1 | 2.9 |
| def_refill_down > att_cancel_up > att_large_peak > volume_down | 11.1 | 2.9 | 2.7 | 4.4 | -0.23 | 9.4 | 2.4 |
| att_cancel_down > def_cancel_down > def_refill_up > volume_peak | 11.1 | 3.0 | 3.3 | 5.4 | -0.15 | 9.2 | 3.0 |
| def_refill_down > att_cancel_up > att_large_peak > div_volume | 10.8 | 2.1 | 3.8 | 3.1 | -0.27 | 8.8 | 2.2 |
| att_cancel_up > att_large_peak > volume_peak | 28.5 | 11.9 | 9.9 | 13.2 | -0.36 | 25.6 | 11.7 |
| def_cancel_down > att_large_peak > volume_peak | 28.4 | 12.1 | 10.2 | 14.1 | -0.26 | 24.2 | 11.4 |
| def_refill_up > att_large_peak > volume_peak | 26.4 | 12.3 | 9.9 | 13.1 | -0.31 | 23.3 | 11.6 |
| att_cancel_down > att_large_peak > volume_peak | 26.4 | 11.7 | 10.2 | 15.0 | -0.27 | 26.1 | 11.9 |
| att_cancel_down > att_refill_down > def_large_down | 25.6 | 15.5 | 15.7 | 18.0 | -0.25 | 22.7 | 15.9 |
| att_refill_down > att_large_peak > volume_peak | 25.5 | 12.1 | 10.3 | 14.2 | -0.15 | 21.0 | 11.6 |
| att_cancel_down > def_cancel_down > att_large_peak | 25.2 | 13.0 | 15.6 | 16.5 | -0.37 | 23.5 | 11.8 |
| att_cancel_down > def_cancel_down > def_large_down | 24.8 | 15.3 | 15.4 | 18.3 | -0.24 | 23.8 | 15.8 |
| att_cancel_down > def_refill_up > volume_peak | 24.7 | 11.3 | 10.5 | 15.0 | -0.25 | 21.5 | 11.2 |
| def_refill_down > att_cancel_up > att_large_peak | 24.6 | 12.0 | 14.6 | 15.3 | -0.45 | 21.2 | 11.1 |
| att_cancel_up > att_large_peak > volume_down | 24.4 | 11.1 | 8.8 | 12.4 | -0.20 | 21.2 | 10.3 |
| def_cancel_down > att_cancel_up > att_large_peak | 23.9 | 12.5 | 15.0 | 15.8 | -0.36 | 21.0 | 10.7 |
| att_cancel_down > def_large_down | 55.7 | 45.2 | 44.8 | 49.0 | -0.26 | 52.4 | 46.1 |
| att_refill_down > def_large_down | 54.4 | 46.3 | 45.2 | 48.1 | -0.25 | 50.7 | 46.3 |
| def_cancel_down > att_large_peak | 53.9 | 42.4 | 44.2 | 44.2 | -0.42 | 49.1 | 39.2 |
| def_cancel_down > def_large_down | 52.0 | 46.4 | 44.6 | 47.3 | -0.25 | 50.8 | 45.7 |
| def_refill_up > att_large_peak | 51.8 | 42.8 | 44.6 | 43.9 | -0.48 | 48.7 | 40.6 |
| att_cancel_up > att_large_peak | 51.8 | 41.4 | 42.2 | 41.7 | -0.46 | 48.7 | 39.5 |
| def_refill_up > def_large_down | 51.8 | 47.0 | 45.2 | 47.8 | -0.22 | 50.2 | 47.2 |
| att_cancel_down > att_large_peak | 50.3 | 41.4 | 43.5 | 45.8 | -0.40 | 49.9 | 40.1 |
| def_refill_down > def_large_down | 50.3 | 44.4 | 43.9 | 47.5 | -0.22 | 48.8 | 46.6 |
| att_refill_down > att_large_peak | 49.4 | 42.2 | 44.4 | 43.8 | -0.44 | 44.2 | 39.9 |
| att_cancel_down > def_cancel_up | 48.8 | 42.2 | 42.6 | 46.9 | -0.17 | 50.8 | 43.3 |
| div_att_large > balance_down | 48.5 | 43.8 | 32.2 | 44.3 | 0.01 | 47.4 | 45.0 |

