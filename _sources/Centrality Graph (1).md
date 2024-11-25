---
title: Centrality Graph

---

---
title: Centrality_Graph

---

# Analisa Graph

* **Social Network** Analysis merupakan bidang kajian yang mengekplorasitentang hubungan manusia dengan menggunakan teori graf. Implementasi Social Network Analysis dapat menjelaskan relasi atau hubungan antar aktor melalui visualisasi berbentuk graf. Relasi dalam analisis jaringan sosial dapat diproses dalam bentuk perhitungan yang disebut centrality dalam sebuah jaringan sosial sesuai dengan posisi masing-masing aktor di dalam struktur jaringan tersebut.

* **Social network** 
terdapat node yang mewakili orang atau individu atau aktor.Relasi  antar objek  dapat dinyatakan dengan link atau edges yang terjadi antara aktor tersebut Social network terdiri dari banyak aktor yang mempunyai relasi satu sama lain hingga membentuk peta jaringan sosial yang dinyatakan dengan graph.
![Picture10](https://hackmd.io/_uploads/ryDj7gwfJx.png)
![Picture2](https://hackmd.io/_uploads/HkdaQxvfye.png)
* Tidak semua node dalam jaringan adalah penting  (aktor).
* Mencari node yang paling penting dalam suatu jaringan.
* Centrality adalah penentuan aktor menggunakan ukuran pada Social Network Centrality dalam teori graf dan social network .Dibagi menjadi empat jenis, 
-degree centrality, 
-betweeness centrality, 
-closeness centrality, 
-eigenvector centrality.

# Degree Centrality
* Degree centrality adalah jumlah edge yang terkoneksi pada suatu node yang mewakili interaksi.
* Pentingnya node ditentukan oleh jumlah node yang berdekatan dengan node tersebut
-Lebih besar derajatnya (degree), maka lebih penting node itu dalam suatu jaringan. 
-Hanya sebagian kecil node yang memiliki derajat tinggi dalam jaringan.
**Degree Centrality**
![Picture3](https://hackmd.io/_uploads/H1njExPGkg.png)
**Normalisasi  Degree Centrality**
![Picture4](https://hackmd.io/_uploads/BkpAEevf1e.png)
![Picture5](https://hackmd.io/_uploads/SJRxrxDGke.png)
Untuk  node 1, degree centrality adalah 3;
Normalisasi degree centrality adalah  
3/(9-1)=3/8.

# Closeness Centrality
* *Closenes centrality* adalah nilai kedekatan antara satu node dengan node lain dalam jaringan dengan menghitung rata-rata dari jarak relasi node-node tersebut. Skor closeness centrality mewakili kecepatan dalam penyebaran informasi.
**Average Distance**
![Picture6](https://hackmd.io/_uploads/HJgDrxDz1g.png)
**Closeness Centrality**
![Picture7](https://hackmd.io/_uploads/H1zKrewzye.png)
**Contoh Closeness Centrality**
![Picture8](https://hackmd.io/_uploads/Skk2SeDGJe.png)![Picture9](https://hackmd.io/_uploads/B1u6SlDMyg.png)
![Picture10](https://hackmd.io/_uploads/rk1lIxPMJl.png)
*Node 4  lebih central  dari node 3*

# Betweenness Centrality
* *Skor betweeness Centrality* mewakili seberapa besar informasi yang tersebar dari suatu aktor. Semakin besar skor, artinya aktor tersebut semakin berperan dalam penyebaran informasi.
* Semakin banyak lintasan yang harus melewati persimpangan itu (misal tidak ada jalan alternatif), maka semakin penting arti persimpangan tersebut. Hal ini menandakan seberapa besar suatu node diperlukan sebagai penghubung dalam penyebaran informasi di dalam jaringan.
* Ukuran ini juga dapat digunakan. untukmengidentifikasi boundary spanners, yaitu orang atau node yang berperan sebagai penghubung (jembatan) antara dua komunitas.
**Betweenness Centrality**
* Menghitung jumlah lintasan terpendek yang melewati suatu node.
* Node dengan  betweenness  tinggi  adalah  penting dalam komunikasi dan penyebaran informasi.
* Betweenness Centrality.
![Picture11](https://hackmd.io/_uploads/HyIZwxDGyl.png)
![Picture14](https://hackmd.io/_uploads/rkHVPxvGkg.png) Jumlah lintasan terpendek antara  s dan t
![Picture15](https://hackmd.io/_uploads/HJmwDgDGyg.png)Jumlah lintasan terpendek antara s dan t yang melewati vi
**Betweenness Centrality**
![Picture16](https://hackmd.io/_uploads/BksqDxPM1x.png)
![Picture17](https://hackmd.io/_uploads/H183vePfyl.png)
*betweenness centrality  untuk node 5?*
![Picture14](https://hackmd.io/_uploads/Hkm7ueDzkg.png) Jumlah path terpendek antara  s dan t.
![Picture15](https://hackmd.io/_uploads/HkeSuxvGyx.png)Jumlah path terpendek antara s dan t yang melewati  vi
![Picture11](https://hackmd.io/_uploads/BJ4u_ePG1x.png)
**Normalisasi Betweenness Centrality**
![Picture18](https://hackmd.io/_uploads/HkF5OxvfJg.png)











 
















