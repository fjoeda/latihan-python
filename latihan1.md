# Latihan Python : list & function

### Soal 1
Buatlah sebuah fungsi untuk menghitung pangkat?
hint : pangkat di python bisa menggunakan operator `**`

```python:
def pangkat(angka, angka_pangkat):
  # isi fungsi
```

|sample input | sample output |
|-------------|---------------|
|pangkat(2,3)| 8|
|pangkat(4,1)| 4|

### Soal 2
Buatlah sebuah fungsi untuk memilih angka kelipatan tertentu di dalam list dan menyimpannya dalam sebuah list?

```python:
def cetak_angka(list_angka, kelipatan):
  # isi fungsi
```

|sample input | sample output |
|-------------|---------------|
|cetak_angka([2,3,4,5],2)| [2,4]|
|cetak_angka([12,15,18,24,21],6)| [12,18,24]|

### Soal 3
Buatlah sebuah fungsi untuk membuat list angka dengan kelipatan tertentu dan dengan jumlah tertentu?
hint : untuk membuat perulangan dengan jumlah tertentu bisa menggunakan for loop dengan contoh kode berikut

```python:
for i in range(angka):
  print(i)

# perintah di atas akan mencetak angka sebanyak sesuai yang dimasukkan di dalam fungsi range
```

```python:
def buat_list_angka(kelipatan, jumlah_angka):
  # isi fungsi
```

|sample input | sample output |
|-------------|---------------|
|buat_list_angka(2,2)| [2,4]|
|buat_list_angka(3,6)| [3,6,9,12,15,18]|
|buat_list_angka(4,3)| [4,8,12]|


### Catatan 
Untuk mencetak hasil dapat menggunakan contoh kode berikut
```python:
input_1 = 2
input_2 = 3

hasil = nama_fungsi(input_1,input_2)
print(hasil)
```
