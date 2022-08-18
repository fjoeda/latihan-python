# Latihan Python : list & function & dictionary

### Soal 1
Buatlah sebuah fungsi untuk menghitung jumlah semua angka yang ada di dalam list?

```python:
def jumlah_angka(list_angka):
  # isi fungsi
```

|sample input | sample output |
|-------------|---------------|
|jumlah_angka([2,3])| 5|
|jumlah_angka([1,4,1,2])| 8|

### Soal 2
Buatlah sebuah fungsi untuk menghitung perkalian semua angka yang ada di dalam list?

```python:
def kali_angka(list_angka):
  # isi fungsi
```

|sample input | sample output |
|-------------|---------------|
|kali_angka([2,3])| 6|
|kali_angka([1,4,3,2])| 24|


### Soal 3
Seorang pedangan buah jeruk memiliki daftar harga seperti berikut

| nama_buah | stok | harga_satuan |
|-----------|--------|-------|
|jeruk|3|2000|

Item pertanyaan :
- Buatlah dictionary objek buah berdasarkan data tersebut
- Ubah nilai stok menjadi 10
- Ubah harga menjadi 9000
- Buat key baru 'potongan_harga' sebesar 3000

Catatan: setiap item pertanyaan harap di-print outputnya

### Soal 4
Anton ingin membeli buah dengan daftar seperti berikut

| nama_buah | jumlah | harga_satuan |
|-----------|--------|-------|
|jeruk|3|2000|
|mangga|3|5000|
|pisang|2|4000|

- Masukkan daftar buah tersebut ke dalam list yang berisi dictionary objek buah lalu print isi dari buah tersebut
- Masukkan key baru yaitu 'harga_total' ke masing-masing dictionary objek buah
- Hitung jumlah yang harus dibayar dengan masukkan list yang berisi dictionary objek buah

Catatan: setiap item pertanyaan harap di-print outputnya

### Tambahan

- Buat fungsi untuk menambahkan daftar buah tersebut ke dalam list yang berisi dictionary objek buah lalu print isi dari buah tersebut

contoh kode:
```python:
# list hanya contoh
list_buah = ["a","B"]
list_harga = [200,123]
list_jumlah = [2,3]



def masukkan_list_belanjaan(daftar_buah, daftar_harga, daftar_jumlah):
  #tulis perintah disini
  
list_belanjaan = masukkan_list_belanjaan(list_buah, list_harga, list_jumlah)
```

- Masukkan key baru yaitu 'harga_total' ke masing-masing dictionary objek buah
```python:
def tambah_harga_total_per_item(daftar_belanjaan):
  #tulis perintah
  
list_belanjaan_dan_harga_total =  tambah_harga_total_per_item(list_belanjaan)
```
- Hitung jumlah yang harus dibayar dengan masukkan list yang berisi dictionary objek buah
```python:
def hitung_total_belanjaan(daftar_belanjaan):
  #tulis perintah
  
total_belanjaan =  hitung_total_belanjaan(list_belanjaan)
```

- Tes fungsi tersebut dengan data baru berikut

- data 1
| nama sayur | jumlah | harga satuan | 
|-----------|--------|-------|
|tomat|3|2000|
|kol|3|5000|
|brokoli|2|4000|
|kentang|10|2000|

untuk total harga dihitung dengan harga satuan dikurangi harga diskon
- data 2
| nama sayur | jumlah | harga satuan | diskon (dalam persen)|
|-----------|--------|-------|-------|
|tomat|3|2000|10|
|kol|3|5000|20|
|brokoli|2|4000|25|
|kentang|10|2000|5|

untuk total harga dihitung dengan harga satuan dikurangi harga diskon

### Catatan 
Untuk mencetak hasil dapat menggunakan contoh kode berikut
```python:
input_1 = 2
input_2 = 3
hasil = nama_fungsi(input_1,input_2)
print(hasil)
```

Agar lebih mudah, bedakan jawaban tiap soal menjadi file tersendiri.
