# Gazdasági próba: a kiválasztott minták a jelölteken

Short a csúcson, long az aljon; belépés a minta teljesülésekor, legkorábban a jelölt megerősítésekor; stop a szélsőérték + 2 tick; kockázat legfeljebb 2 x ATR1; 1R / 2R / 3R cél; 60 perc. Nettó R kötésenként (súlyozva: a nem ZigZag-jelöltek 10-es súllyal), ± 95% seanszonként klaszterezve. pontosság = a kötések (súlyozott) hány %-a ZigZag-forduló. A minták csak 2024-ből választva, 2025 az ellenőrzés.

## Éjszaka

| minta | év | kötés | súlyozott | pontosság | 1R | 2R | 3R | MFE (R, medián) | kockázat (ATR1) |
|---|---|---|---|---|---|---|---|---|---|
| (minden jelölt) | 2024 | 1692 | 10800 | 6.3% | -0.026 ±0.071 | -0.158 ±0.098 | -0.120 ±0.109 | 2.51 | 1.48 |
| (minden jelölt) | 2025 | 2370 | 15528 | 5.8% | -0.037 ±0.053 | -0.105 ±0.074 | -0.083 ±0.082 | 2.46 | 1.37 |
| def_hidden_lo > def_eff_up > att_eff_up | 2024 | 618 | 4281 | 4.9% | +0.050 ±0.102 | -0.165 ±0.147 | -0.185 ±0.168 | 2.23 | 1.56 |
| def_hidden_lo > def_eff_up > att_eff_up | 2025 | 949 | 6844 | 4.3% | -0.041 ±0.085 | -0.094 ±0.117 | +0.000 ±0.137 | 2.27 | 1.44 |
| def_hidden_lo > def_eff_up > att_eff_lo | 2024 | 136 | 1018 | 3.7% | -0.021 ±0.239 | -0.183 ±0.305 | -0.345 ±0.321 | 1.88 | 1.64 |
| def_hidden_lo > def_eff_up > att_eff_lo | 2025 | 330 | 2562 | 3.2% | -0.015 ±0.136 | -0.107 ±0.177 | -0.033 ±0.230 | 1.70 | 1.62 |
| def_hidden_lo > def_eff_up > att_eff_peak | 2024 | 553 | 3847 | 4.9% | +0.056 ±0.102 | -0.096 ±0.160 | -0.117 ±0.196 | 2.38 | 1.54 |
| def_hidden_lo > def_eff_up > att_eff_peak | 2025 | 882 | 6291 | 4.5% | -0.031 ±0.089 | -0.105 ±0.122 | -0.080 ±0.141 | 2.17 | 1.44 |
| def_hidden_lo > def_eff_up > att_eff_down | 2024 | 476 | 3302 | 4.9% | +0.019 ±0.115 | -0.189 ±0.164 | -0.210 ±0.200 | 2.15 | 1.58 |
| def_hidden_lo > def_eff_up > att_eff_down | 2025 | 716 | 5000 | 4.8% | +0.014 ±0.099 | -0.081 ±0.136 | -0.134 ±0.142 | 2.22 | 1.48 |
| def_hidden_lo > att_eff_peak > def_eff_hi | 2024 | 206 | 1601 | 3.2% | -0.103 ±0.181 | -0.282 ±0.248 | -0.222 ±0.274 | 1.67 | 1.67 |
| def_hidden_lo > att_eff_peak > def_eff_hi | 2025 | 452 | 3467 | 3.4% | -0.076 ±0.113 | -0.092 ±0.164 | +0.004 ±0.200 | 1.79 | 1.62 |
| def_hidden_lo > att_eff_peak > def_eff_down | 2024 | 410 | 3092 | 3.6% | +0.009 ±0.130 | -0.265 ±0.173 | -0.312 ±0.191 | 1.86 | 1.51 |
| def_hidden_lo > att_eff_peak > def_eff_down | 2025 | 739 | 5581 | 3.6% | -0.006 ±0.095 | -0.088 ±0.130 | -0.098 ±0.153 | 2.11 | 1.43 |
| def_eff_up > att_eff_peak > cross_large | 2024 | 327 | 2118 | 6.0% | -0.048 ±0.156 | -0.040 ±0.206 | +0.038 ±0.247 | 2.87 | 1.48 |
| def_eff_up > att_eff_peak > cross_large | 2025 | 592 | 4093 | 5.0% | -0.024 ±0.098 | -0.009 ±0.140 | -0.031 ±0.177 | 2.43 | 1.44 |
| att_large_up > delta_down > def_large_down | 2024 | 364 | 2182 | 7.4% | +0.093 ±0.130 | +0.073 ±0.188 | -0.032 ±0.220 | 2.73 | 1.43 |
| att_large_up > delta_down > def_large_down | 2025 | 440 | 2402 | 9.2% | +0.085 ±0.134 | -0.053 ±0.179 | -0.037 ±0.208 | 3.29 | 1.33 |
| def_eff_up > def_refill_up > att_eff_up | 2024 | 377 | 2429 | 6.1% | -0.044 ±0.143 | -0.255 ±0.193 | -0.215 ±0.227 | 2.38 | 1.55 |
| def_eff_up > def_refill_up > att_eff_up | 2025 | 446 | 2993 | 5.4% | -0.008 ±0.123 | -0.083 ±0.151 | +0.032 ±0.182 | 2.44 | 1.49 |
| def_hidden_lo > att_eff_up > def_eff_down | 2024 | 396 | 2853 | 4.3% | -0.047 ±0.134 | -0.287 ±0.188 | -0.284 ±0.204 | 1.97 | 1.51 |
| def_hidden_lo > att_eff_up > def_eff_down | 2025 | 647 | 4508 | 4.8% | +0.014 ±0.101 | -0.060 ±0.139 | -0.095 ±0.168 | 2.33 | 1.40 |
| att_large_up > def_cancel_down > def_refill_up | 2024 | 331 | 1870 | 8.6% | +0.038 ±0.149 | -0.065 ±0.203 | -0.000 ±0.245 | 3.16 | 1.46 |
| att_large_up > def_cancel_down > def_refill_up | 2025 | 368 | 2114 | 8.2% | -0.027 ±0.127 | -0.169 ±0.172 | -0.154 ±0.219 | 2.73 | 1.37 |
| att_large_up > def_cancel_down > att_cancel_up | 2024 | 317 | 1901 | 7.4% | -0.045 ±0.153 | -0.167 ±0.194 | -0.162 ±0.217 | 2.62 | 1.48 |
| att_large_up > def_cancel_down > att_cancel_up | 2025 | 380 | 2162 | 8.4% | +0.143 ±0.134 | +0.020 ±0.196 | +0.126 ±0.247 | 3.25 | 1.36 |
| def_cancel_down > def_refill_up > cross_large | 2024 | 321 | 1977 | 6.9% | -0.122 ±0.150 | -0.237 ±0.191 | -0.212 ±0.234 | 2.52 | 1.46 |
| def_cancel_down > def_refill_up > cross_large | 2025 | 350 | 2051 | 7.8% | +0.054 ±0.129 | +0.076 ±0.180 | +0.090 ±0.220 | 3.09 | 1.36 |
| att_large_up > def_refill_up > def_large_down | 2024 | 293 | 1769 | 7.3% | +0.028 ±0.147 | -0.002 ±0.201 | -0.099 ±0.239 | 2.71 | 1.45 |
| att_large_up > def_refill_up > def_large_down | 2025 | 353 | 2225 | 6.5% | +0.008 ±0.150 | -0.071 ±0.183 | -0.127 ±0.218 | 2.71 | 1.36 |
| att_large_up > att_refill_down > def_large_down | 2024 | 293 | 1823 | 6.7% | +0.045 ±0.156 | -0.013 ±0.227 | -0.139 ±0.253 | 2.60 | 1.45 |
| att_large_up > att_refill_down > def_large_down | 2025 | 383 | 2372 | 6.8% | -0.020 ±0.134 | -0.129 ±0.181 | -0.137 ±0.225 | 2.76 | 1.38 |
| def_cancel_down > att_cancel_up > cross_large | 2024 | 305 | 1880 | 6.9% | -0.104 ±0.162 | -0.192 ±0.203 | -0.125 ±0.251 | 2.58 | 1.45 |
| def_cancel_down > att_cancel_up > cross_large | 2025 | 358 | 2077 | 8.0% | +0.125 ±0.139 | +0.041 ±0.187 | +0.110 ±0.228 | 3.15 | 1.40 |
| att_large_up > att_cancel_up > def_large_down | 2024 | 280 | 1657 | 7.7% | +0.045 ±0.147 | +0.042 ±0.211 | -0.045 ±0.255 | 2.81 | 1.43 |
| att_large_up > att_cancel_up > def_large_down | 2025 | 349 | 2032 | 8.0% | -0.021 ±0.147 | -0.099 ±0.214 | -0.125 ±0.229 | 3.00 | 1.37 |
| att_large_down > def_refill_up > def_large_down | 2024 | 268 | 1627 | 7.2% | -0.000 ±0.153 | -0.056 ±0.225 | -0.178 ±0.245 | 2.64 | 1.47 |
| att_large_down > def_refill_up > def_large_down | 2025 | 308 | 1847 | 7.4% | -0.034 ±0.178 | -0.090 ±0.230 | -0.139 ±0.254 | 2.81 | 1.37 |
| att_large_up > def_cancel_down > def_large_down | 2024 | 278 | 1718 | 6.9% | +0.057 ±0.159 | -0.069 ±0.213 | -0.098 ±0.252 | 2.63 | 1.45 |
| att_large_up > def_cancel_down > def_large_down | 2025 | 350 | 2186 | 6.7% | -0.011 ±0.138 | -0.163 ±0.180 | -0.174 ±0.217 | 2.44 | 1.35 |
| att_large_up > att_cancel_up > def_refill_up | 2024 | 277 | 1546 | 8.8% | -0.009 ±0.168 | +0.003 ±0.221 | +0.054 ±0.281 | 3.00 | 1.45 |
| att_large_up > att_cancel_up > def_refill_up | 2025 | 342 | 1755 | 10.5% | -0.024 ±0.139 | -0.139 ±0.176 | -0.177 ±0.219 | 2.78 | 1.39 |
| def_hidden_lo > def_eff_up > att_eff_peak > delta_lo | 2024 | 129 | 930 | 4.3% | -0.054 ±0.205 | -0.198 ±0.290 | -0.287 ±0.360 | 1.91 | 1.57 |
| def_hidden_lo > def_eff_up > att_eff_peak > delta_lo | 2025 | 189 | 1476 | 3.1% | -0.054 ±0.167 | -0.142 ±0.212 | -0.191 ±0.249 | 1.57 | 1.57 |
| def_hidden_lo > def_eff_up > att_eff_peak > att_cancel_hi | 2024 | 84 | 606 | 4.3% | -0.164 ±0.270 | -0.260 ±0.397 | -0.366 ±0.400 | 1.80 | 1.55 |
| def_hidden_lo > def_eff_up > att_eff_peak > att_cancel_hi | 2025 | 134 | 890 | 5.6% | +0.031 ±0.236 | +0.021 ±0.308 | +0.116 ±0.350 | 2.73 | 1.57 |
| def_hidden_lo > def_eff_up > att_eff_peak > att_refill_lo | 2024 | 163 | 1117 | 5.1% | -0.008 ±0.212 | -0.285 ±0.273 | -0.387 ±0.306 | 1.95 | 1.63 |
| def_hidden_lo > def_eff_up > att_eff_peak > att_refill_lo | 2025 | 212 | 1544 | 4.1% | -0.127 ±0.184 | -0.173 ±0.241 | -0.157 ±0.284 | 1.83 | 1.47 |
| def_hidden_lo > def_eff_up > att_eff_peak > cross_large | 2024 | 176 | 1193 | 5.3% | -0.011 ±0.196 | +0.002 ±0.290 | +0.008 ±0.359 | 2.71 | 1.45 |
| def_hidden_lo > def_eff_up > att_eff_peak > cross_large | 2025 | 327 | 2415 | 3.9% | +0.030 ±0.135 | +0.065 ±0.199 | +0.083 ±0.257 | 2.39 | 1.47 |
| def_hidden_lo > def_eff_up > att_eff_peak > def_large_down | 2024 | 191 | 1361 | 4.5% | -0.066 ±0.180 | -0.136 ±0.270 | -0.174 ±0.299 | 2.16 | 1.48 |
| def_hidden_lo > def_eff_up > att_eff_peak > def_large_down | 2025 | 295 | 2185 | 3.9% | -0.029 ±0.147 | -0.089 ±0.210 | -0.055 ±0.243 | 2.14 | 1.45 |
| def_hidden_lo > def_eff_up > att_eff_down > att_cancel_hi | 2024 | 79 | 565 | 4.4% | -0.113 ±0.284 | -0.224 ±0.386 | -0.395 ±0.389 | 2.07 | 1.56 |
| def_hidden_lo > def_eff_up > att_eff_down > att_cancel_hi | 2025 | 137 | 875 | 6.3% | +0.045 ±0.227 | -0.030 ±0.303 | +0.008 ±0.365 | 2.45 | 1.60 |
| def_hidden_lo > def_eff_up > att_eff_peak > def_refill_hi | 2024 | 140 | 1076 | 3.3% | -0.051 ±0.220 | +0.096 ±0.301 | -0.020 ±0.350 | 2.33 | 1.57 |
| def_hidden_lo > def_eff_up > att_eff_peak > def_refill_hi | 2025 | 237 | 1884 | 2.9% | +0.003 ±0.161 | -0.109 ±0.212 | -0.047 ±0.255 | 1.71 | 1.57 |
| def_hidden_lo > def_eff_up > att_eff_down > delta_lo | 2024 | 103 | 706 | 5.1% | -0.042 ±0.256 | -0.337 ±0.330 | -0.459 ±0.369 | 1.86 | 1.59 |
| def_hidden_lo > def_eff_up > att_eff_down > delta_lo | 2025 | 158 | 1157 | 4.1% | +0.045 ±0.200 | -0.031 ±0.275 | -0.114 ±0.320 | 1.92 | 1.59 |
| def_hidden_lo > def_eff_up > att_eff_down > att_refill_lo | 2024 | 131 | 923 | 4.7% | +0.109 ±0.235 | -0.115 ±0.311 | -0.169 ±0.355 | 2.27 | 1.61 |
| def_hidden_lo > def_eff_up > att_eff_down > att_refill_lo | 2025 | 162 | 1125 | 4.9% | -0.065 ±0.215 | -0.144 ±0.277 | -0.230 ±0.306 | 2.09 | 1.50 |
| def_hidden_lo > def_eff_up > att_eff_down > cross_large | 2024 | 139 | 1003 | 4.3% | -0.080 ±0.211 | -0.133 ±0.290 | -0.133 ±0.356 | 2.19 | 1.57 |
| def_hidden_lo > def_eff_up > att_eff_down > cross_large | 2025 | 256 | 1822 | 4.5% | -0.026 ±0.148 | -0.041 ±0.217 | -0.117 ±0.261 | 2.14 | 1.46 |
| att_large_up > def_cancel_down > att_cancel_up > def_large_down | 2024 | 117 | 756 | 6.1% | +0.069 ±0.233 | +0.036 ±0.334 | +0.101 ±0.404 | 2.85 | 1.46 |
| att_large_up > def_cancel_down > att_cancel_up > def_large_down | 2025 | 127 | 766 | 7.3% | +0.154 ±0.239 | +0.085 ±0.343 | +0.094 ±0.427 | 3.26 | 1.42 |
| att_large_up > def_cancel_down > def_refill_up > def_large_down | 2024 | 130 | 805 | 6.8% | +0.080 ±0.205 | +0.043 ±0.297 | +0.001 ±0.367 | 2.93 | 1.42 |
| att_large_up > def_cancel_down > def_refill_up > def_large_down | 2025 | 117 | 702 | 7.4% | +0.058 ±0.243 | +0.014 ±0.330 | -0.090 ±0.377 | 3.09 | 1.35 |
| att_large_up > def_cancel_down > att_cancel_up > att_refill_lo | 2024 | 106 | 664 | 6.6% | +0.016 ±0.255 | -0.182 ±0.344 | -0.096 ±0.420 | 2.73 | 1.52 |
| att_large_up > def_cancel_down > att_cancel_up > att_refill_lo | 2025 | 101 | 551 | 9.3% | +0.335 ±0.254 | +0.315 ±0.379 | +0.457 ±0.463 | 3.46 | 1.44 |
| def_cancel_down > att_cancel_up > def_refill_up > cross_large | 2024 | 110 | 614 | 8.8% | -0.082 ±0.256 | -0.195 ±0.337 | -0.099 ±0.400 | 2.72 | 1.44 |
| def_cancel_down > att_cancel_up > def_refill_up > cross_large | 2025 | 116 | 647 | 8.8% | +0.021 ±0.240 | -0.156 ±0.323 | -0.025 ±0.420 | 2.89 | 1.43 |
| att_large_up > att_cancel_up > def_refill_up > def_large_down | 2024 | 96 | 519 | 9.4% | +0.020 ±0.248 | +0.216 ±0.374 | -0.007 ±0.475 | 2.97 | 1.40 |
| att_large_up > att_cancel_up > def_refill_up > def_large_down | 2025 | 99 | 522 | 10.0% | -0.081 ±0.281 | -0.305 ±0.324 | -0.310 ±0.371 | 3.00 | 1.37 |
| att_large_up > def_cancel_down > att_cancel_up > def_refill_up | 2024 | 104 | 599 | 8.2% | +0.110 ±0.275 | -0.082 ±0.358 | +0.083 ±0.444 | 3.00 | 1.48 |
| att_large_up > def_cancel_down > att_cancel_up > def_refill_up | 2025 | 119 | 659 | 9.0% | +0.164 ±0.224 | +0.004 ±0.338 | -0.057 ±0.443 | 2.78 | 1.39 |
| att_large_up > def_cancel_down > def_refill_up > att_cancel_down | 2024 | 118 | 640 | 9.4% | +0.156 ±0.238 | -0.114 ±0.340 | +0.020 ±0.422 | 3.36 | 1.37 |
| att_large_up > def_cancel_down > def_refill_up > att_cancel_down | 2025 | 87 | 501 | 8.2% | +0.257 ±0.287 | +0.288 ±0.421 | +0.555 ±0.534 | 3.46 | 1.35 |
| att_large_up > def_cancel_down > def_refill_up > volume_down | 2024 | 109 | 577 | 9.9% | -0.019 ±0.257 | -0.094 ±0.344 | -0.061 ±0.410 | 3.00 | 1.39 |
| att_large_up > def_cancel_down > def_refill_up > volume_down | 2025 | 85 | 454 | 9.7% | +0.235 ±0.296 | +0.120 ±0.425 | +0.329 ±0.525 | 4.20 | 1.23 |
| def_cancel_down > def_refill_up > att_large_peak > volume_down | 2024 | 120 | 696 | 8.0% | +0.045 ±0.258 | -0.075 ±0.348 | -0.089 ±0.409 | 3.00 | 1.31 |
| def_cancel_down > def_refill_up > att_large_peak > volume_down | 2025 | 93 | 516 | 8.9% | -0.008 ±0.293 | -0.049 ±0.387 | +0.194 ±0.495 | 3.36 | 1.29 |
| att_large_up > def_cancel_down > att_cancel_up > volume_down | 2024 | 108 | 675 | 6.7% | -0.210 ±0.249 | -0.230 ±0.316 | -0.254 ±0.369 | 2.29 | 1.41 |
| att_large_up > def_cancel_down > att_cancel_up > volume_down | 2025 | 118 | 631 | 9.7% | +0.174 ±0.260 | +0.229 ±0.375 | +0.435 ±0.495 | 3.51 | 1.34 |

## RTH

| minta | év | kötés | súlyozott | pontosság | 1R | 2R | 3R | MFE (R, medián) | kockázat (ATR1) |
|---|---|---|---|---|---|---|---|---|---|
| (minden jelölt) | 2024 | 1267 | 7576 | 7.5% | +0.139 ±0.074 | +0.122 ±0.106 | +0.135 ±0.126 | 3.00 | 1.20 |
| (minden jelölt) | 2025 | 1417 | 8527 | 7.4% | +0.037 ±0.068 | +0.018 ±0.099 | +0.054 ±0.116 | 2.94 | 1.19 |
| delta_up > att_cancel_up > att_eff_down | 2024 | 232 | 1195 | 10.5% | +0.238 ±0.162 | +0.065 ±0.243 | -0.078 ±0.277 | 2.81 | 1.26 |
| delta_up > att_cancel_up > att_eff_down | 2025 | 266 | 1337 | 11.0% | +0.007 ±0.174 | -0.082 ±0.206 | -0.120 ±0.231 | 2.71 | 1.37 |
| att_cancel_up > att_large_peak > volume_peak | 2024 | 212 | 869 | 16.0% | +0.258 ±0.174 | +0.324 ±0.274 | +0.341 ±0.327 | 3.89 | 1.30 |
| att_cancel_up > att_large_peak > volume_peak | 2025 | 212 | 977 | 13.0% | -0.108 ±0.179 | -0.064 ±0.211 | -0.002 ±0.268 | 3.21 | 1.25 |
| def_cancel_down > att_large_peak > volume_peak | 2024 | 213 | 870 | 16.1% | +0.163 ±0.165 | +0.221 ±0.280 | +0.341 ±0.334 | 3.71 | 1.27 |
| def_cancel_down > att_large_peak > volume_peak | 2025 | 200 | 920 | 13.0% | -0.037 ±0.179 | -0.055 ±0.219 | -0.040 ±0.266 | 3.21 | 1.20 |
| delta_up > att_large_peak > volume_peak | 2024 | 197 | 854 | 14.5% | +0.223 ±0.176 | +0.118 ±0.277 | +0.183 ±0.339 | 3.67 | 1.25 |
| delta_up > att_large_peak > volume_peak | 2025 | 207 | 990 | 12.1% | -0.113 ±0.177 | -0.132 ±0.204 | -0.189 ±0.242 | 3.00 | 1.27 |
| att_cancel_down > def_cancel_down > att_eff_down | 2024 | 238 | 1210 | 10.7% | +0.299 ±0.159 | +0.320 ±0.235 | +0.245 ±0.308 | 3.05 | 1.29 |
| att_cancel_down > def_cancel_down > att_eff_down | 2025 | 242 | 1349 | 8.8% | +0.006 ±0.170 | -0.116 ±0.216 | -0.213 ±0.230 | 2.32 | 1.33 |
| def_refill_down > att_cancel_up > att_eff_down | 2024 | 231 | 1230 | 9.8% | +0.273 ±0.156 | +0.303 ±0.259 | +0.206 ±0.289 | 3.22 | 1.27 |
| def_refill_down > att_cancel_up > att_eff_down | 2025 | 250 | 1339 | 9.6% | +0.114 ±0.182 | +0.119 ±0.231 | +0.034 ±0.262 | 2.82 | 1.32 |
| delta_up > att_cancel_up > att_large_peak | 2024 | 254 | 1289 | 10.8% | +0.222 ±0.182 | +0.141 ±0.247 | +0.142 ±0.294 | 3.57 | 1.21 |
| delta_up > att_cancel_up > att_large_peak | 2025 | 250 | 1240 | 11.3% | -0.054 ±0.177 | -0.095 ±0.223 | -0.105 ±0.269 | 3.26 | 1.25 |
| def_refill_up > att_large_peak > volume_peak | 2024 | 209 | 884 | 15.2% | +0.199 ±0.176 | +0.253 ±0.276 | +0.361 ±0.359 | 3.91 | 1.26 |
| def_refill_up > att_large_peak > volume_peak | 2025 | 209 | 1028 | 11.5% | -0.066 ±0.176 | -0.029 ±0.216 | +0.037 ±0.278 | 3.23 | 1.27 |
| att_cancel_down > att_large_peak > volume_peak | 2024 | 194 | 824 | 15.0% | +0.120 ±0.192 | +0.163 ±0.287 | +0.239 ±0.338 | 3.71 | 1.26 |
| att_cancel_down > att_large_peak > volume_peak | 2025 | 214 | 961 | 13.6% | -0.082 ±0.181 | -0.104 ±0.214 | -0.048 ±0.268 | 3.23 | 1.25 |
| delta_up > att_cancel_up > volume_peak | 2024 | 197 | 863 | 14.3% | +0.179 ±0.178 | +0.058 ±0.282 | +0.156 ±0.316 | 3.61 | 1.23 |
| delta_up > att_cancel_up > volume_peak | 2025 | 202 | 922 | 13.2% | -0.128 ±0.192 | -0.260 ±0.208 | -0.343 ±0.217 | 2.94 | 1.27 |
| att_cancel_down > att_refill_down > def_large_down | 2024 | 229 | 1093 | 12.2% | +0.055 ±0.179 | -0.021 ±0.234 | +0.100 ±0.277 | 3.17 | 1.27 |
| att_cancel_down > att_refill_down > def_large_down | 2025 | 233 | 1196 | 10.5% | -0.120 ±0.188 | +0.005 ±0.253 | +0.036 ±0.288 | 3.00 | 1.24 |
| att_refill_down > att_large_peak > volume_peak | 2024 | 185 | 770 | 15.6% | +0.245 ±0.188 | +0.196 ±0.288 | +0.162 ±0.323 | 3.71 | 1.26 |
| att_refill_down > att_large_peak > volume_peak | 2025 | 172 | 874 | 10.8% | -0.097 ±0.190 | -0.096 ±0.238 | -0.043 ±0.299 | 3.00 | 1.26 |
| att_cancel_down > def_cancel_down > att_large_peak | 2024 | 245 | 1298 | 9.9% | +0.212 ±0.165 | +0.147 ±0.233 | +0.176 ±0.273 | 3.00 | 1.19 |
| att_cancel_down > def_cancel_down > att_large_peak | 2025 | 248 | 1247 | 11.0% | +0.050 ±0.156 | -0.052 ±0.229 | -0.004 ±0.276 | 3.33 | 1.19 |
| att_cancel_down > def_cancel_down > def_large_down | 2024 | 219 | 1074 | 11.5% | +0.155 ±0.169 | +0.009 ±0.230 | +0.095 ±0.275 | 3.00 | 1.26 |
| att_cancel_down > def_cancel_down > def_large_down | 2025 | 240 | 1203 | 11.1% | -0.015 ±0.188 | -0.095 ±0.253 | -0.190 ±0.263 | 2.82 | 1.22 |
| att_cancel_down > def_refill_up > volume_peak | 2024 | 184 | 751 | 16.1% | +0.369 ±0.196 | +0.363 ±0.314 | +0.323 ±0.389 | 3.71 | 1.25 |
| att_cancel_down > def_refill_up > volume_peak | 2025 | 179 | 755 | 15.2% | -0.121 ±0.205 | -0.102 ±0.249 | -0.051 ±0.291 | 3.38 | 1.25 |
| def_refill_down > att_cancel_up > att_large_peak | 2024 | 236 | 1217 | 10.4% | +0.347 ±0.158 | +0.362 ±0.251 | +0.407 ±0.312 | 3.74 | 1.24 |
| def_refill_down > att_cancel_up > att_large_peak | 2025 | 230 | 1193 | 10.3% | +0.080 ±0.182 | +0.040 ±0.261 | +0.067 ±0.304 | 3.42 | 1.23 |
| delta_up > att_cancel_up > att_large_peak > volume_peak | 2024 | 116 | 476 | 16.0% | +0.143 ±0.269 | +0.077 ±0.381 | +0.060 ±0.428 | 3.71 | 1.27 |
| delta_up > att_cancel_up > att_large_peak > volume_peak | 2025 | 116 | 521 | 13.6% | -0.109 ±0.257 | -0.194 ±0.298 | -0.196 ±0.334 | 3.21 | 1.25 |
| att_cancel_down > def_cancel_down > att_large_peak > volume_peak | 2024 | 110 | 425 | 17.6% | +0.248 ±0.263 | +0.432 ±0.427 | +0.531 ±0.507 | 3.68 | 1.26 |
| att_cancel_down > def_cancel_down > att_large_peak > volume_peak | 2025 | 96 | 411 | 14.8% | -0.078 ±0.262 | -0.135 ±0.303 | -0.094 ±0.391 | 2.93 | 1.23 |
| def_refill_down > att_cancel_up > att_large_peak > volume_peak | 2024 | 105 | 474 | 13.5% | +0.353 ±0.231 | +0.528 ±0.391 | +0.565 ±0.498 | 3.95 | 1.26 |
| def_refill_down > att_cancel_up > att_large_peak > volume_peak | 2025 | 98 | 440 | 13.6% | -0.247 ±0.268 | -0.271 ±0.320 | -0.249 ±0.366 | 3.05 | 1.26 |
| att_cancel_down > def_refill_up > att_large_peak > volume_peak | 2024 | 111 | 444 | 16.7% | +0.279 ±0.265 | +0.375 ±0.409 | +0.343 ±0.517 | 3.89 | 1.25 |
| att_cancel_down > def_refill_up > att_large_peak > volume_peak | 2025 | 105 | 456 | 14.5% | -0.191 ±0.259 | -0.119 ±0.323 | -0.028 ±0.386 | 3.31 | 1.25 |
| delta_up > def_cancel_down > att_large_peak > volume_peak | 2024 | 99 | 414 | 15.5% | +0.269 ±0.266 | +0.093 ±0.404 | +0.182 ±0.499 | 3.49 | 1.26 |
| delta_up > def_cancel_down > att_large_peak > volume_peak | 2025 | 92 | 443 | 12.0% | -0.188 ±0.264 | -0.248 ±0.300 | -0.304 ±0.345 | 2.45 | 1.20 |
| delta_up > def_refill_up > att_large_peak > volume_peak | 2024 | 103 | 427 | 15.7% | +0.291 ±0.265 | +0.153 ±0.405 | +0.228 ±0.502 | 3.91 | 1.25 |
| delta_up > def_refill_up > att_large_peak > volume_peak | 2025 | 106 | 493 | 12.8% | -0.149 ±0.267 | -0.211 ±0.318 | -0.291 ±0.342 | 2.96 | 1.29 |
| delta_up > att_cancel_up > att_large_peak > volume_down | 2024 | 95 | 410 | 14.6% | +0.161 ±0.325 | +0.134 ±0.427 | +0.122 ±0.501 | 3.61 | 1.34 |
| delta_up > att_cancel_up > att_large_peak > volume_down | 2025 | 92 | 425 | 12.9% | -0.075 ±0.298 | -0.281 ±0.312 | -0.376 ±0.296 | 2.38 | 1.24 |
| att_cancel_down > def_cancel_down > att_large_peak > volume_down | 2024 | 92 | 371 | 16.4% | +0.138 ±0.284 | +0.363 ±0.422 | +0.402 ±0.495 | 3.63 | 1.30 |
| att_cancel_down > def_cancel_down > att_large_peak > volume_down | 2025 | 86 | 383 | 13.8% | -0.009 ±0.273 | -0.144 ±0.331 | -0.213 ±0.392 | 2.59 | 1.25 |
| def_cancel_down > att_cancel_up > att_large_peak > volume_peak | 2024 | 105 | 483 | 13.0% | +0.155 ±0.239 | +0.167 ±0.376 | +0.244 ±0.462 | 3.11 | 1.27 |
| def_cancel_down > att_cancel_up > att_large_peak > volume_peak | 2025 | 107 | 512 | 12.1% | -0.205 ±0.255 | -0.227 ±0.310 | -0.310 ±0.319 | 2.38 | 1.22 |
| def_cancel_down > def_refill_up > att_large_peak > volume_peak | 2024 | 101 | 398 | 17.1% | +0.144 ±0.253 | +0.341 ±0.419 | +0.431 ±0.504 | 3.72 | 1.29 |
| def_cancel_down > def_refill_up > att_large_peak > volume_peak | 2025 | 98 | 512 | 10.2% | -0.229 ±0.253 | -0.191 ±0.334 | -0.103 ±0.410 | 2.37 | 1.29 |
| att_cancel_down > att_refill_down > att_large_peak > volume_peak | 2024 | 90 | 369 | 16.0% | +0.186 ±0.311 | +0.197 ±0.423 | +0.192 ±0.485 | 3.24 | 1.28 |
| att_cancel_down > att_refill_down > att_large_peak > volume_peak | 2025 | 88 | 394 | 13.7% | -0.127 ±0.273 | -0.149 ±0.342 | +0.013 ±0.458 | 3.27 | 1.34 |
| def_cancel_down > att_cancel_up > att_large_peak > volume_down | 2024 | 96 | 474 | 11.4% | +0.099 ±0.265 | +0.198 ±0.368 | +0.242 ±0.473 | 3.13 | 1.42 |
| def_cancel_down > att_cancel_up > att_large_peak > volume_down | 2025 | 103 | 526 | 10.6% | -0.184 ±0.251 | -0.193 ±0.316 | -0.257 ±0.333 | 2.38 | 1.24 |
| att_cancel_down > def_refill_up > att_large_peak > volume_down | 2024 | 91 | 370 | 16.2% | +0.081 ±0.297 | +0.128 ±0.415 | +0.257 ±0.509 | 3.85 | 1.32 |
| att_cancel_down > def_refill_up > att_large_peak > volume_down | 2025 | 102 | 462 | 13.4% | -0.003 ±0.287 | -0.048 ±0.338 | -0.031 ±0.382 | 3.30 | 1.27 |
| def_refill_down > att_cancel_up > att_large_peak > volume_down | 2024 | 93 | 462 | 11.3% | +0.205 ±0.264 | +0.345 ±0.385 | +0.478 ±0.490 | 3.71 | 1.35 |
| def_refill_down > att_cancel_up > att_large_peak > volume_down | 2025 | 83 | 371 | 13.7% | -0.209 ±0.305 | -0.311 ±0.322 | -0.348 ±0.322 | 2.38 | 1.24 |

