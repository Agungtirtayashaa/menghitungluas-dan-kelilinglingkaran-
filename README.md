# menghitung luas dan keliling lingkaran

## Rumus Luas dan Keliling lingkaran 

Luas     = π × r²
Keliling = 2 x π × r

   ### Nilai Phi yang akan kita gunakan adalah 3.14
   ### r merupakan jari-jari lingkaran

Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran. Sebetulnya ada rumus lain untuk menghitung keliling lingkaran yaitu dengan menggunakan diameter, tapi pada kasus ini kita cukup menggunakan jari jari lingkaran saja.

## Flowchart Menghitung Luas & Keliling Lingkaran

![gambar1](menghitungluas-dan-kelilinglingkaran-/sketsa1.png)

## Program Python Menghitung Luas & Keliling Lingkaran

import math
r = float(input("Masukan Jari-jari : "))

luas = math.pi*(r*r)
keliling = 2*math.pi*r

print ("Luas Lingkaran \t\t= ",luas)
print ("Keliling Lingkaran\t= ",keliling)

### Output:

Masukan Jari-jari : 4.5

Luas Lingkaran          = 63.61725123519331
Keliling Lingkaran      = 28.274333882308138