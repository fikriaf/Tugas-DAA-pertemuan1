=======================<br>
Nama: Fikri Armia Fahmi<br>
NIM: 2023071018<br>
=======================<br>
A. ALGORITMA
<br>
======================<br>
ALGORITMA KELIPATAN 2<br>
======================
1. Pengguna menginput angkanya<br>
2. Komputer mengambil angka dari variabel<br>
3. Memproses dengan cara penambahan 2 dalam loop sampai batas angka yang ditentukan, memakai kondisi<br>
4. Komputer menampilkan hasilnya

====================================<br>
ALGORITMA MENCARI ANGKA TERBESAR<br>
====================================
1. Pengguna menginput Angka 1
2. Pengguna menginput Angka 2
3. Komputer membandingkan Angka 1 dan Angka 2
4. Jika Angka 1 lebih besar dari Angka 2, tampilkan "Angka yang lebih besar adalah Angka 1"
5. Jika Angka 2 lebih besar dari Angka 1, tampilkan "Angka yang lebih besar adalah Angka 2"
6. Jika Angka 1 sama dengan Angka 2, tampilkan "Angkanya sama besar"

===================================<br>
ALGORITMA MENCARI KPK DARI 3 DAN 4<br>
===================================
1. Tentukan nilai a = 3 dan b = 4
2. Definisikan fungsi FPB(a, b):
   - Tentukan angka kecil sebagai FPB<br>
   - Untuk setiap angka dari 1 hingga angka kecil:<br>
     - Jika a dan b bisa dibagi tanpa sisa dengan angka ini:<br>
       - Set FPB ke angka ini<br>
   - Kembalikan FPB<br>
3. Definisikan fungsi KPK(a, b):<br>
   - Hitung KPK dengan rumus (a * b) / FPB(a, b)<br>
   - Kembalikan KPK<br>
4. Hitung FPB dari a dan b
5. Hitung KPK menggunakan hasil FPB
6. Tampilkan KPK

===========================================<br>
ALGORITMA MENUKAR POSISI MANGGIS DAN PISANG<br>
===========================================
1. Tampilkan "Piring 1: Manggis"
2. Tampilkan "Piring 2: Pisang"
3. Tampilkan "Piring 3: Kosong"
4. Tukar isi piring 1 dan piring 2
   - Piring 1 menjadi "Pisang"
   - Piring 2 menjadi "Manggis"
5. Tampilkan hasil setelah ditukar
   - Tampilkan "Piring 1: Pisang"
   - Tampilkan "Piring 2: Manggis"
   - Tampilkan "Piring 3: Kosong"

================================<br>
ALGORITMA MENCARI LUAS SEGITIGA<br>
=================================
1. Tetapkan alas = 25 dan tinggi = 30
2. Tampilkan informasi alas dan tinggi
3. Hitung luas segitiga dengan rumus 1/2 * alas * tinggi
4. Tampilkan hasil luas segitiga

=====================================<br>
ALGORITMA MENCARI LUAS JAJAR GENJANG<br>
=====================================
1. Tetapkan panjang = 25 dan tinggi = 30
2. Tampilkan informasi panjang dan tinggi
3. Hitung luas jajargenjang dengan rumus panjang * tinggi
4. Tampilkan hasil luas jajargenjang

=================================<br>
ALGORITMA MENCARI VOLUME TABUNG<br>
=================================
1. Tetapkan jari-jari = 3 dan tinggi = 5
2. Tampilkan informasi jari-jari dan tinggi
3. Hitung volume tabung dengan rumus π * jari-jari^2 * tinggi
4. Tampilkan hasil volume tabung

===================================<br>
PSEUDOCODE MENCARI VOLUME KERUCUT<br>
===================================
1. Tetapkan diameter = 5 dan tinggi = 4
2. Tampilkan informasi diameter dan tinggi
3. Hitung volume kerucut dengan rumus 1/3 * π * (diameter / 2)^2 * tinggi
5. Tampilkan hasil volume kerucut
   
B. PSEUDOCODE<br>
======================<br>
PSEUDOCODE KELIPATAN 2<br>
======================
1. Start
2. Input angka
4. For i in range(2, angka+1, 2)
6. If i<angka, Print i
7. End

=================================<br>
PSEUDOCODE MENCARI ANGKA TERBESAR<br>
=================================
1. Start
2. Input Angka1
3. Input Angka2
5. If Angka1>Angka2, print "Angka yang lebih besar adalah {Angka1}"
7. If Angka2>Angka1, print "Angka yang lebih besar adalah {Angka2}"
8. If Angka1==Angka2, print "Angkanya sama besar"
9. End

===================================<br>
PSEUDOCODE MENCARI KPK DARI 3 DAN 4<br>
===================================
1. Start
2. a = 3 dan b = 4
3. Def fpb():<br>
   -If a < b, smaller=a<br>
   -Else, smaller=b<br>
   -For i in range (1,smaller+1)<br>
     -If a%i == 0 and b%i == 0<br>
        fpb = i<br>
     -Return fpb<br>
4. Def kpk(a,b)<br>
   -kpk = int(a*b/fpb(a,b))<br>
   -Retur kpk<br>
5. Print kpk(a,b)
6. End

============================================<br>
PSEUDOCODE MENUKAR POSISI MANGGIS DAN PISANG<br>
============================================
1. Start
2. Piring1 = "Manggis"
3. Piring2 = "Pisang"
4. Piring3 = "Kosong"
5. Piring1, Piring2 = Piring2, Piring1
6. Print Piring1
7. Print Piring2
8. Print Piring3
9. End

================================<br>
PSEUDOCODE MENCARI LUAS SEGITIGA<br>
================================
1. Start
2. alas = 25
3. tinggi = 30
5. luas_segitiga = 1/2 * alas * tinggi
6. Print luas_segitiga
7. End

====================================<br>
PSEUDOCODE MENCARI LUAS JAJAR GENJANG<br>
=====================================
1. Start
2. panjang = 25
3. tinggi = 30
5. luas_jajargenjang = panjang * tinggi
6. Print luas_jajargenjang
7. End

================================<br>
PSEUDOCODE MENCARI VOLUME TABUNG<br>
================================
1. Start
2. jari = 3
3. tinggi = 5
5. volume_tabung = 3.14 * jari*jari * tinggi
6. Print volume_tabung
7. End

=================================<br>
PSEUDOCODE MENCARI VOLUME KERUCUT<br>
=================================
1. Start
2. diameter = 5
3. tinggi = 4
5. volume_kerucut = 1/3 * 3.14 * (diameter/2) * (diameter/2) * tinggi
6. Print volume_kerucut
7. End
