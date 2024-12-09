---
title: UAS.MD

---

# UAS.MD 

## soal  1. 
$(P \to Q) \to (R \to S)$


| NO | P | Q | R | S |$(P \to Q)$|$(R \to S)$|
|  - | - | - | - | - |-|-|
|  1 | T | T | T | T | T | T 
|  2 | T | T | F | T | T | F
|  3 | T | T | F | T | T | T
|  4 | T | F | F | F | F | T
|  5 | F | T | T | T | T | T
|  6 | F | T | T | F | T | F
|  7 | F | T | F | T | T | T
|  8 | F | T | F | F | T | T

## soal 2.
buat graph A, B, C, D, E, F, G dan hitung Closennes centrality dan beetwinnes centrality

![image](https://hackmd.io/_uploads/r1UdOM44Jl.png)


a. Closennes Centrality
| NODE | A | B | C | D | E | F | G |
|  -   | - | - | - | - |-| - |-    | 
|  G   | 2 | 1 | 2 | 3 |  1  | 2 |0 

Jumlah Rute Terpendek = (2+1+2+3+1+2)
$$
Cc(g) = \frac{7-1}{2+1+2+3+1+2} = {0,545}
$$

| NODE | A | B | C | D | E | F | G |
|  -   | - | - | - | - |-| - |-    | 
|  F   | 2 | 1 | 1 | 3 |  1  | 0 |2 

b. Beetwinnes Centrality
$$
C_b(f) = \frac{7-1}{((10-1)(10-2))/2}=\frac{6}{36}
$$