---
title: deretan dan rekursif

---

---
title: deretan dan rekursif

---

# Deretan dan rekursi

## deretan
### pengertian deretan
deretan adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu.

### definisi deretan
Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.

N = {1, 2, 3, 4, … }
   S misalnya {2, 4, 6, 8, …},   {1/3, 1/5, 1/7, …},  dsb

Notasi deretan: {an}

##
Deretan umumnya dinyatakan dalam suatu formula, misalnya:
	an = 2n
	an = 1/n
	an = 7 – 3n

## 
Dalam konteks matematika, deretan sering merujuk pada barisan bilangan, yaitu kumpulan bilangan yang disusun dalam suatu pola tertentu.
 Misalnya:
1. Deretan bilangan ganjil: 1,3,5,7,…
2. Deretan bilangan genap: 2,4,6,8,…
3. Deretan bilangan yang membentuk deret aritmetika: 3,6,9,12....

macam macam jenis deretean beserta prnjrlasan
penjumlahan deretan

## Contoh-contoh deretan dan formulanya:

### deret aritmatika
-contoh: 2,5,8,11,14, ,,,
-rumus suku ke-n:
    𝑈_𝑛=𝑎+(𝑛−1)⋅𝑏
 dimana:
-a:suku pertama
-𝑏: beda (selisih antar suku
-𝑛: nomor suku yang dicari

### deret geometri
## 
Deret dengan pola kelipatan tetap.
- Contoh: 3,6,12,24,48,…
- Rumus suku ke-n:
     𝑈_𝑛=𝑎⋅𝑟^((𝑛−1) )
## 
Di mana:
- 𝑎: suku pertama 
- 𝑟: rasio (perbandingan antar suku,
- 𝑛: nomor suku yang dicari

### deret bilangan kuadrat
Deret dengan pola nilai berupa kuadrat bilangan bulat.
- Contoh: 1,4,9,16,25,…
- Rumus suku ke-n:
    𝑈_𝑛=𝑛^2

### deret bilangan kubik
Deret dengan pola nilai berupa kubik bilangan bulat.
- Contoh: 1,8,27,64,125,…
- Rumus suku ke-n:
    𝑈_𝑛=𝑛^3

### Deret Fibonacci
Deret dengan pola di mana setiap suku merupakan jumlah dua suku sebelumnya.
- Contoh: 0,1,1,2,3,5,8,…
- Rumus suku ke-n(rekursif):
    𝐹_𝑛=𝐹_(𝑛−1)+𝐹_(𝑛−2),𝐹_0=0,𝐹_1=1

### String
adalah deretan berhingga karakter berbentuk
		a1a2a3a4…an

    Panjang string S adalah jumlah karakter di dalam string tersebut
     
    Contoh:  informatika adalah string dengan panjang 11 karakter
	         10100101 adalah string biner dengan panjang 8 bit

String kosong dilambangkan dengan , panjangnya = 0

## penjumlahan deretan
Jumlah deretan 
	am, am+1, am+2, …, an
  adalah
	 am + am+1 + am+2 + … + an
  atau dalam notasi sumasi:
	∑_(𝑘=𝑚)^𝑛▒𝑎_𝑘   
   
    k adalah indeks summasi, 
    m adalah batas bawah indeks,
    n adalah batas atas indeks

## Contoh 2: 
Berapa nilai ∑_(𝑘=1)^5▒𝑘^2 ?
Jawaban: 
	∑_(𝑘=1)^5▒𝑘^2 = 12 + 22 + 32 + 42 + 52 = 1 + 4 + 9 + 16 + 25 = 55

## Contoh 3:
Batas bawah sumasi kadangkala perlu digeser agar dapat dijumlahkan dengan sumasi lain yang memiliki batas bawah berbeda. Pada contoh 2 di atas batas bawah digeser dari 1 menjadi 0, akibatnya:
	 ∑_(𝑘=1)^5▒𝑘^2 = ∑_(𝑘=0)^4▒〖(𝑘+1)〗^2  

## Contoh 4: 
Sumasi dapat dipecah dengan membagi dua indeksnya, misalnya
	  ∑_(𝑘=1)^100▒𝑘^2 =  ∑_(𝑘=1)^49▒𝑘^2  +  ∑_(𝑘=50)^100▒𝑘^2 

## TUGAS PEMBUKTIAN Dari 3 rumus dibawah
Beberapa sumasi sudah ditemukan rumus penjumlahannya sebagai berikut:
![image](https://hackmd.io/_uploads/Syk3k1W7ye.png)
(deret geometri)
(deret aritmetika)

## Contoh 5: 
Hitung nilai    ∑_(𝑘=50)^100▒𝑘^2   
Jawaban:
	   ∑_(𝑘=1)^100▒𝑘^2 =  ∑_(𝑘=1)^49▒𝑘^2  +  ∑_(𝑘=50)^100▒𝑘^2   

	    ∑_(𝑘=50)^100▒𝑘^2  = ∑_(𝑘=1)^100▒𝑘^2 −  ∑_(𝑘=1)^49▒𝑘^2   

 Gunakan rumus                                                 ,  :

	      ∑_(𝑘=50)^100▒𝑘^2  =((100)(101)(201))/6 − ((49)(50)(99))/6  = 338.350 – 40.425 = 297.925
          
# Sumasi ganda
Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.

    Contoh: ∑_(𝑖=1)^4▒∑_(𝑗=1)^3▒𝑖𝑗 

    Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu  dilanjukan dengan sumasi terluar:
	 	∑_(𝑖=1)^4▒∑_(𝑗=1)^3▒𝑖𝑗 = ∑_(𝑖=1)^4▒〖(𝑖+2𝑖+3𝑖)= ∑_(𝑖=1)^4▒6𝑖〗 = 6 + 12 + 18 + 24 = 60

	Contoh penggunaan: 
	Berapa kali operasi + dilakukan di dalam algoritma di bawah ini? 
	x = 0
	for j = 1 to 10 do
	    for k = 1 to j do
	           x = x + 2
	   end for
	end for 

    Penyelesaian:
    Operasi + terdapat di dalam pernyataan x = x + 2
    Operasi ini dilakukan satu kali pada setiap pengulangan
    Jumlah seluruh operasi + adalah:

    t = ∑_(𝑗=1)^10▒∑_(𝑘=1)^𝑗▒1 
  
       = ∑_(𝑗=1)^10▒〖(1+1+ …+1 𝑠𝑒𝑏𝑎𝑛𝑦𝑎𝑘 𝑗 𝑘𝑎𝑙𝑖)〗

       = ∑_(𝑗=1)^10▒𝑗

       = (10(10+1))/2  = 55

    Latihan:
    1. Tentukan nilai ∑_(𝑘=1)^8▒2^𝑘  + ∑_(𝑘=2)^8▒〖(−3)〗^𝑘 

    2. Tentukan nilai ∑_(𝑖=0)^2▒∑_(𝑗=0)^3▒〖(2𝑖+3𝑗)〗 

    3. Tentukan nilai ∑_(𝑖=0)^3▒∑_(𝑗=0)^2▒𝑖 

# Rekursi

Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 

Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).

Perhatikan tiga buah gambar pada tiga slide berikut ini.

Objek fraktal  adalah contoh bentuk rekursif.
![image](https://hackmd.io/_uploads/HyB5f1bQkl.png)
![image](https://hackmd.io/_uploads/ryx3fybXyl.png)

# Fungsi Rekursif
Fungsi rekursif didefinisikan oleh dua bagian:
 (i)  _Basis_
Bagian yang berisi nilai fungsi yang terdefinisi secara eksplisit. 
Bagian ini juga sekaligus menghentikan rekursif (dan memberikan sebuah nilai yang terdefinisi pada fungsi rekursif).
 
 (ii)  _Rekurens_
Bagian ini mendefinisikan fungsi dalam terminologi dirinya sendiri. 
Berisi kaidah untuk menemukan nilai fungsi pada suatu input dari nilai-nilai lainnya pada input yang lebih kecil. 

Contoh 6:  Misalkan f didefinsikan secara rekusif sbb

								
		           
		        Tentukan nilai f(4)!
	
	Solusi:      f(4) = 2f(3) + 4 
			=  2(2f(2) + 4) + 4
			=  2(2(2f(1) + 4) + 4) + 4
			=  2(2(2(2f(0) + 4) + 4) + 4) + 4
			=  2(2(2(23 + 4) + 4) + 4) + 4	
			=  2(2(2(10) + 4) + 4) + 4
			=  2(2(24) + 4) + 4
			=  2(52) + 4
			= 108	

    Cara lain menghitungnya:
		f(0) = 3
		f(1) = 2f(0) + 4 = 2  3 + 4 = 10
		f(2) = 2f(1) + 4 = 2  10 + 4 = 24
		f(3) = 2f(2) + 4 = 2  24 + 4 = 52
		f(4) = 2f(3) + 4 = 2  52 + 4 = 108
		
		Jadi, f(4) = 108.

# Contoh 7: 
Nyatakan n! dalam definisi rekursif
	Solusi:     ![image](https://hackmd.io/_uploads/ryiyNJ-myg.png)
Misalkan f(n) = n!, maka  
![image](https://hackmd.io/_uploads/HkkdE1bXyx.png)

# Algoritma menghitung faktorial:

function Faktorial (input  n :integer)integer
{ mengembalikan nilai n!;
  basis   : jika n = 0, maka 0! = 1
  rekurens: jika n > 0, maka n! = n  (n-1)!
}
DEKLARASI
      -
ALGORITMA:
    if n = 0 then
       return 1		              { basis }
    else
       return  n * Faktorial(n – 1)	{ rekurens }
    end

## Contoh 8: 
Barisan Fibonacci  0, 1, 1, 2, 3, 5, 8, 11, 19, …. Dapat dinyatakan secara rekursif sebagai berikut:
![image](https://hackmd.io/_uploads/Hk6brkWQ1g.png)

## Contoh 9: 
Fungsi (polinom) Chebyshev dinyatakan sebagai
![image](https://hackmd.io/_uploads/BkxitHy-71g.png)

## Contoh 10: 
Sumasi![image](https://hackmd.io/_uploads/SJ12rJZmyl.png) didefinisikan secara rekursif sebagai  berikut:

![image](https://hackmd.io/_uploads/SJ6y8JbmJg.png)

sehingga ![image](https://hackmd.io/_uploads/H14-Lybmkl.png)

Latihan
	1. Definisikan an secara rekursif , yang dalam hal ini a adalah bilangan riil tidak-nol dan n adalah bilangan bulat tidak-negatif.

2. Nyatakan a  b secara rekursif, yang dalam hal ini a dan b adalah bilangan bulat positif.

(Solusinya ada setelah slide berikut!)

Solusi:
	1. ![image](https://hackmd.io/_uploads/ryTO8yb7yl.png)
sehingga:
![image](https://hackmd.io/_uploads/rkrqI1b7Jl.png)
    2.
![image](https://hackmd.io/_uploads/B1dh8kZm1x.png) 
![image](https://hackmd.io/_uploads/BkiUvJbm1l.png)
![image](https://hackmd.io/_uploads/rJGYwkWXye.png)

# Struktur Rekursif
Struktur data yang penting dalam komputer adalah pohon biner (binary tree). 
![image](https://hackmd.io/_uploads/ByHjdkbQyg.png)

Simpul (node) pada pohon biner mempunyai paling banyak dua buah anak.

Jumlah anak pada setiap simpul bisa 1, 2, atau 0.

Simpul yang mempunyai anak disebut simpul cabang (branch node) atau simpul dalam (internal node)

Simpul yang tidak mempunyai anak disebut simpul daun (leave).

Pohon biner adalah struktur yang rekursif, sebab setiap simpul mempunyai cabang yang juga berupa pohon. Setiap cabang disebut  upapohon (subtree).
![image](https://hackmd.io/_uploads/BkogtkbXkg.png)

Oleh karena itu, pohon dapat didefinisikan secara rekursif sebagari berikut:

(i) Basis: kosong adalah pohon biner
(ii) Rekurens: Jika T1 dan T2 adalah pohon biner, maka                        
          adalah pohon biner
								                    T1       T2 
Proses pembentukan pohon biner secara rekursif:
(i)                 
(ii)  
![image](https://hackmd.io/_uploads/Hkt9YJWQ1e.png)



