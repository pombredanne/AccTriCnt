# O(E) intersection count Elapsed time


Unit: seconds


### webgraph_twitter

file-name | 1 | 2 | 4 | 8 | 16 | 32 | 64 | 128 | 256
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
naive-merge | / | / | / | / | / | 3388.080 | 1705.055 | 1605.801 | 1657.199
naive-hybrid | / | / | / | / | / | 473.710 | 239.011 | 180.929 | 167.169
avx512-merge | / | / | / | / | / | 981.105 | 657.731 | 617.144 | 643.534
avx512-hybrid | 5562.579 | 2893.882 | 1465.865 | 729.686 | 365.381 | 184.500 | 101.873 | 83.067 | 86.168


### webgraph_twitter/rev_deg

file-name | 1 | 2 | 4 | 8 | 16 | 32 | 64 | 128 | 256
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
naive-bitvec | 3704.287 | 2031.953 | 1006.197 | 509.400 | 258.193 | 133.516 | 78.077 | 104.150 | 161.283
naive-bitvec-2d | 5052.566 | 2780.340 | 1389.657 | 695.530 | 350.256 | 177.130 | 91.770 | 82.134 | 109.184
naive-bitvec-hbw | / | / | / | / | / | / | / | / | /
naive-bitvec-hbw-2d | / | / | / | / | / | / | / | / | /


### snap_friendster

file-name | 1 | 2 | 4 | 8 | 16 | 32 | 64 | 128 | 256
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
naive-merge | / | / | / | / | / | 349.998 | 175.931 | 120.364 | 101.895
naive-hybrid | / | / | / | / | / | 350.752 | 176.473 | 120.941 | 102.141
avx512-merge | / | / | / | / | / | 141.787 | 74.116 | 59.770 | 62.667
avx512-hybrid | 4382.258 | 2272.660 | 1136.719 | 567.042 | 283.142 | 142.794 | 74.571 | 60.149 | 62.806


### snap_friendster/rev_deg

file-name | 1 | 2 | 4 | 8 | 16 | 32 | 64 | 128 | 256
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
naive-bitvec | 8765.759 | 4810.823 | 2397.829 | 1204.425 | 623.120 | 338.749 | 248.722 | 324.263 | 421.926
naive-bitvec-2d | 6932.211 | 4165.030 | 2069.878 | 1032.502 | 514.919 | 260.810 | 135.462 | 115.740 | 143.241
naive-bitvec-hbw | / | / | / | / | / | / | / | / | /
naive-bitvec-hbw-2d | / | / | / | / | / | / | / | / | /