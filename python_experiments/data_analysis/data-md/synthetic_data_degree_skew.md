## Elapsed Time of a Single Vertex Computation

Fixed the web-it degree-descending dataset

### LCCPU12

u | d[u]  |  Merge | Pivot | Hybrid | BitVec | BitVec2D
--- | --- | --- | --- | --- | --- | --- 
19 | 803,716 | 117.771 |  3.300 | 3.479 | 0.436 | 0.332 
21 | 172,118 | 3.510 | 0.204 | 0.217 | 0.045 | 0.043
40-49 | 51,690 - 53,916 | 4.234 | 0.491 | 0.590 | 0.255 | 0.143 
460-470 | 12,480 - 12734 | 0.403 |  0.159 |  0.184  | 0.067  | 0.108 

### KNL


u | d[u]  | Merge | Pivot | Hybrid | BitVec-hbw | BitVec2D-hbw
--- | --- | --- | --- | --- | --- | ---
19 | 803,716 | 308.728 | 10.239 | 10.822 | 0.868 | 1.314
21 | 172,118 | 3.682 | 0.513 | 0.503  |  0.094 |  0.128
40-49 | 51,690 - 53,916 | 4.815 | 1.393 |  1.333 |  0.321 |  0.509
460-470 | 12,480 - 12734 | 0.402 | 0.371 | 0.306 |   0.166 | 0.150
