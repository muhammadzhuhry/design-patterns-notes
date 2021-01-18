**Singleton**

Singleton adalah sebuah pattern yang membuat sebuah kelas hanya memiliki satu
buah objek saja. Sehingga ketika kita menginisiasi suatu objek dari kelas tersebut
maka objek tersebut merupakan objek yang selalu sama.\
<br>
analoginya:
Dalam sebuah keluarga, yang berperan sebagai suami hanya boleh satu orang, 
sampai kapan? ya minimal sampai suami ini meninggal dunia /cerai, 
maka selama itu tidak boleh ada orang lain yang berhak menggantikannya 
sebagai suami. Konsep monogami ini disebut sebagai singleton.
  
Singleton dapat memberi dua hal:

- objek yang dapat diakses secara global
- memastikan bahwa semua obyek mengakses instance yang sama

Di dalam programming, singleton pattern paling sering digunakan ketika 
membuat objek  untuk melakukan **koneksi ke database**.<br>
Ketika kita melakukan koneksi ke database kita selalu menggunakan instance
yang sama.

reference: \
https://www.hafidmukhlasin.com/2015/12/25/design-pattern-singleton/
https://medium.com/@ranggaantok/design-pattern-series-singleton-objek-yang-tidak-ingin-diduakan-b0d5a604bcd0