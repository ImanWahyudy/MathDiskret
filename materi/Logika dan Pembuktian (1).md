---
title: Logika dan Pembuktian

---

# Logika Matematika

## Negasi
Negasi adalah, pernyataan yang memimiliki nilai kebenaran yang berlawanan dengan dengan pernyataan lain
proposisi \(p\) dilambangkan dengan \($\neg p$) dan berbunyi "Tidaklah benar bahwa \(p\)". Misalkan, negasi dari proposisi "Hari ini adalah Jumat" adalah "Bukanlah benar bahwa hari ini adalah Jumat" atau "Hari ini bukan Jumat"

 Tabel Kebenaran untuk Negasi dari Proposisi.
 ###### TABEL1
 
|      P      | $\neg p$  |
| --------    | --------  |
|      T      |     F     |
|      F      |     T     |

## Konjungsi
Konjungsi adalah pernyataan majemuk yang menggunakan kata hubung "dan" untuk menyambung dua pernyataan. Konjungsi disimbolkan dengan ∧, yang setara dengan operator AND. Konjungsi hanya benar jika kedua pernyataan yang disambungnya juga benar.
 
The Truth Table
untuk Konjungsi Dua Proposisi.
###### TABEL 2

|  p   |  q  |  p∧q  |
| -----|---  | ----  |
|  T   |  T  |   T   |
|  T   |  F  |   F   |
|  F   |  T  |   F   |
|  F   |  F  |   F   |


## Disjungsi
Disjungsi adalah pernyataan majemuk yang menggunakan kata hubung "atau". Disjungsi dilambangkan dengan simbol "∨". Untuk dua pernyataan p dan q, disjungsi ditulis sebagai "p ∨ q" dan dibaca "p atau q". Disjungsi bernilai benar jika salah satu pernyataan benar dan salah jika kedua pernyataan salah

Tabel Kebenaran untuk
Pemisahan Dua Proposisi
 ###### TABEL 3 
 
|  p   |  q  |  p∨q  |
|------|-----|-------|
|  T   |  T  |   T   |
|  T   |  F  |   T   |
|  F   |  T  |   T   |
|  F   |  F  |   F   |


## Implikasi
Implikasi adalah hubungan antara dua pernyataan, di mana pernyataan kedua merupakan konsekuensi logis dari pernyataan pertama. Implikasi menggunakan kata hubung "jika... maka..." dan disimbolkan oleh karakter "→". Dalam notasi "p ⇒ q", p disebut sebagai anteseden atau penyebab, dan q disebut sebagai konsekuen atau akibat.

Tabel Kebenaran untuk Pernyataan Bersyarat
P →q.

 ###### TABEL 4
|  p   |  q  |  p→q  |
|------|-----|-------|
|  T   |  T  |   T   |
|  T   |  F  |   F   |
|  F   |  T  |   T   |
|  F   |  F  |   T   |

## Biimplikasi
Biimplikasi adalah logika matematika yang menggunakan kata "jika dan hanya jika". Biimplikasi terjadi dalam proposisi majemuk dan disimbolkan dengan "↔". Biimplikasi benar hanya jika dua pernyataan (p dan q) keduanya benar atau keduanya salah. Jika salah satu pernyataan salah, implikasi kondisional salah. 

The Truth Table
untuk Bikondisional p ↔ q.
###### TABEL 6

|  p   |  q  | p ↔ q.|
|------|-----|-------|
|  T   |  T  |   T   |
|  T   |  F  |   F   |
|  F   |  T  |   F   |
|  F   |  F  |   T   |

https://www.ruangguru.com/blog/logika-matematika
Colab.research.google.com/drive/1EOlgHzlgHobSq1Tkdf9rFvO3yq41B5Mg#scrollTo=G77syGiVUcFV



Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{-}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{-}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{-}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{-}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{-}&\text{T}&\text{T}&\text{}\end{array}$$