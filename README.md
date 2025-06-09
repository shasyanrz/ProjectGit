| Fungsi f(x)                             | Hasil Integral ∫₀ᴸ f(x) dx                                          | Nilai / Nilai dalam n                          |
|-----------------------------------------|----------------------------------------------------------------------|------------------------------------------------|
| sin(nπx/L)                              | - (L / (nπ)) [cos(nπ) - 1]                                           | (L / (nπ)) · [1 - (−1)ⁿ]                        |
| x sin(nπx/L)                            | (L² / (nπ)) (−1)ⁿ⁺¹ + (L² / (n²π²)) [sin(nπ) − nπ cos(nπ)]          | (L² / (nπ)) · (−1)ⁿ⁺¹                           |
| cos(nπx/L)                              | (L / (nπ)) [sin(nπ) − sin(0)]                                       | 0 (n ≥ 1)                                      |
| x cos(nπx/L)                            | (L / (nπ)) [L sin(nπ)] − ∫₀ᴸ (L / (nπ)) sin(nπx/L) dx               | (L² / (n²π²)) · [(−1)ⁿ − 1]                     |
| sin²(nπx/L)                             | ∫₀ᴸ (1/2) dx − ∫₀ᴸ (1/2) cos(2nπx/L) dx                            | L / 2                                          |
| cos²(nπx/L)                             | ∫₀ᴸ (1/2) dx + ∫₀ᴸ (1/2) cos(2nπx/L) dx                            | L / 2                                          |
| sin(nπx/L) · sin(mπx/L), n ≠ m          | ∫₀ᴸ (1/2) [cos((n−m)πx/L) − cos((n+m)πx/L)] dx                     | 0                                              |
| sin(nπx/L) · sin(mπx/L), n = m          | ∫₀ᴸ (1/2) [1 − cos(2nπx/L)] dx                                     | L / 2                                          |
| cos(nπx/L) · cos(mπx/L), n ≠ m          | ∫₀ᴸ (1/2) [cos((n−m)πx/L) + cos((n+m)πx/L)] dx                     | 0                                              |
| cos(nπx/L) · cos(mπx/L), n = m          | ∫₀ᴸ (1/2) [1 + cos(2nπx/L)] dx                                     | L / 2                                          |
| sin(nπx/L) · cos(mπx/L), semua n, m     | ∫₀ᴸ (1/2) [sin((n+m)πx/L) + sin((n−m)πx/L)] dx                     | 0 (n, m ≥ 1)                                   |
