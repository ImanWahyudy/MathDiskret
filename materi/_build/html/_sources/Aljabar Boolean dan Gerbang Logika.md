---
title: Aljabar Boolean dan Gerbang Logika

---

# Aljabar Boolean dan Gerbang Logika

### Operator Biner:
Aljabar Boolean memiliki dua operator biner:
Penjumlahan (+): Digunakan untuk operasi disjungsi (OR).
Perkalian (⋅): Digunakan untuk operasi konjungsi (AND).

### Operator Uner:
Komplemen (’): Digunakan untuk menghasilkan nilai yang berlawanan dari suatu elemen. Misalnya, jika a = 1, maka a’ = 0, dan sebaliknya.

### Manfaat dalam Pemrograman
Aljabar Boolean sering digunakan dalam pemrograman untuk mengevaluasi ekspresi logika.

### Contoh dalam pemrograman python
![image](https://hackmd.io/_uploads/BkdbeE91yg.png)

### Aksioma-Aksioma:
Untuk setiap a, b, c ∈ B, berlaku aksioma-aksioma berikut:
**Closure**: a + b ∈ B dan a ⋅ b ∈ B.
**Identitas**: a + 0 = a dan a ⋅ 1 = a.
**Komutatif**: a + b = b + a dan a ⋅ b = b ⋅ a.
**Distributif**: a ⋅ (b + c) = (a ⋅ b) + (a ⋅ c) dan a + (b ⋅ c) = (a + b) ⋅ (a + c).
**Komplemen**: Untuk setiap a ∈ B, terdapat elemen unik a’ ∈ B sehingga a + a’ = 1 dan a ⋅ a’ = 0

**Aljabar Boolean adalah sistem matematika untuk manipulasi variabel yang dapat memiliki salah satu dari dua nilai.**  

Dalam logika formal, nilai-nilai ini adalah "benar" dan "salah."  
Dalam sistem digital, nilai-nilai ini adalah "nyala" dan "mati," 1 dan 0, atau "tinggi" dan "rendah."  

Ekspresi Boolean dibuat dengan melakukan operasi pada variabel Boolean.  
Operator Boolean yang umum termasuk AND (AND), (OR), dan (NOT).

### Aljabar Boolean
Sebuah operator Boolean dapat dijelaskan sepenuhnya menggunakan tabel kebenaran.  
Tabel kebenaran untuk operator Boolean D (AND) dan (OR) ditunjukkan di sebelah kanan.  
Operator AND  juga dikenal sebagai produk Boolean. Operator OR adalah jumlah Boolean.
![image](https://hackmd.io/_uploads/B1tU-V511g.png)

### Boolean Algebra
Tabel kebenaran untuk operator Boolean (NOT) ditunjukkan di sebelah kanan.  
Operasi NOT paling sering dilambangkan dengan garis atas. 
![image](https://hackmd.io/_uploads/rkOKWE5kJx.png)

Sebuah fungsi Boolean memiliki:  
Setidaknya satu variabel Boolean,  
Setidaknya satu operator Boolean, dan  
Setidaknya satu input dari himpunan {0,1}.  
Fungsi ini menghasilkan output yang juga merupakan anggota dari himpunan {0,1}.

Tabel kebenaran untuk fungsi Boolean. : 
   ![image](https://hackmd.io/_uploads/SkLR-4ck1l.png)
![image](https://hackmd.io/_uploads/BJ61ME9ykg.png)

Untuk mempermudah evaluasi fungsi Boolean, tabel kebenaran berisi kolom tambahan (diarsir) untuk menyimpan evaluasi dari bagian-bagian subfungsi.

Sebagian besar identitas Boolean memiliki bentuk AND (perkallian) serta bentuk OR (jumlah). Kami menyajikan identitas kami menggunakan kedua bentuk tersebut
![image](https://hackmd.io/_uploads/BySXf4c1kx.png)

Kelompok kedua
![image](https://hackmd.io/_uploads/BkqVfNqkkg.png)

Kelompok 3 

![image](https://hackmd.io/_uploads/HkKLGEqJye.png)

Terkadang, lebih ekonomis membangun sirkuit dengan menggunakan komplemen fungsi dan mengkomplementasi hasilnya dibandingkan mengimplementasikan fungsi secara langsung. Hukum DeMorgan memudahkan penemuan komplemen dari fungsi Boolean, yang menyatakan:
![image](https://hackmd.io/_uploads/By3wME9kyx.png)

# Logic Gates
Fungsi Boolean diimplementasikan dalam sirkuit komputer digital yang disebut gerbang (gates).  

Gerbang adalah perangkat elektronik yang menghasilkan hasil berdasarkan dua atau lebih nilai input.  

Dalam kenyataannya, gerbang terdiri dari satu hingga enam transistor, tetapi desainer digital menganggapnya sebagai satu kesatuan.  

Sirkuit terintegrasi mengandung kumpulan gerbang yang sesuai untuk tujuan tertentu.

Tiga gerbang AND, OR, dan  NOT
![image](https://hackmd.io/_uploads/r1Ry7N9k1e.png)

![image](https://hackmd.io/_uploads/ByvlXVcJyl.png)
![image](https://hackmd.io/_uploads/r1PZmEck1g.png)
![image](https://hackmd.io/_uploads/BJ0lQE9Jke.png)
![image](https://hackmd.io/_uploads/H1_QX4911g.png)

Gerbang yang sangat berguna lainnya adalah gerbang eksklusif OR (XOR).  
Output dari operasi XOR adalah benar hanya ketika nilai-nilai input berbeda.
![image](https://hackmd.io/_uploads/SykSQN9yye.png)
![image](https://hackmd.io/_uploads/SJaHX49kkx.png)



![image](https://hackmd.io/_uploads/Hk8wXN9k1l.png)
![image](https://hackmd.io/_uploads/S1Qd745yye.png)
![image](https://hackmd.io/_uploads/rkKFm49yyx.png)
![image](https://hackmd.io/_uploads/SyK97Eckyx.png)

### NAND dan NOR dua gerbang yang sangat penting. Simbol dan tabel kebenarannya ditunjukkan di sebelah kanan. 
![image](https://hackmd.io/_uploads/Hkuh7V5J1e.png)

# Gerbang logika
NAND dan NOR dikenal dengan gerbang universal  karena mereka murah untuk diproduksi dan setiap fungsi Boolean dapat dibangun menggunakan gerbang ini. NAND atau hanya gerbang NOR .  
![image](https://hackmd.io/_uploads/rJNlEV9yye.png)

Gerbang dapat memiliki beberapa  inputs dan dan lebih dari satu output.
Output kedua dapat disediakan untuk komplemen dari operasi. 
![image](https://hackmd.io/_uploads/rktINN911x.png)

### Komponen Digital
Hal utama yang perlu diingat adalah bahwa kombinasi gerbang menerapkan fungsi Boolean.
Rangkaian di bawah ini mengimplementasikan fungsi Boolean :
![image](https://hackmd.io/_uploads/S18YNV511l.png)
![image](https://hackmd.io/_uploads/HJaF4EcJyl.png)
![image](https://hackmd.io/_uploads/HyB94V51Jx.png)

### Combinational Circuits
Kami telah merancang rangkaian yang mengimplementasikan fungsi Boolean :
![image](https://hackmd.io/_uploads/r1w3445JJx.png)
Rangkaian ini merupakan contoh rangkaian logika kombinasional.
Rangkaian logika kombinasional menghasilkan output tertentu

Rangkaian logika kombinasional memberi kita banyak perangkat yang berguna.
Salah satu yang paling sederhana adalah half adder, yang mencari jumlah dua bit.
Kita dapat memperoleh beberapa wawasan tentang konstruksi half adder dengan melihat tabel kebenarannya, yang ditunjukkan di sebelah kanan.
![image](https://hackmd.io/_uploads/BkCmHN5kke.png)

Seperti kita lihat, jumlahnya dapat ditemukan menggunakan operasi XOR dan sisanya menggunakan operasi AND.
![image](https://hackmd.io/_uploads/SJeSHEqkJx.png)
![image](https://hackmd.io/_uploads/H1uSrV5yJe.png)

![image](https://hackmd.io/_uploads/HyELBE5kJx.png)
![image](https://hackmd.io/_uploads/SkYLSNckkl.png)
