# labpy02
Nama        : Ica Rizqiah <p>

Kelas       : TI.24.A.5 <p>

Nim         : 312410554 <p>

Mata kuliah : Bahasa Pemrograman <p>

## pengunaan `if`, `else` dan `elif` untuk tiket bioskop

```python
if tipe_tiket == "reguler":
    harga_tiket = harga_reguler
elif tipe_tiket == "vip":
    harga_tiket = harga_vip
else:
    print("Tipe tiket tidak valid!")
    exit()  
```
kondisi `if`
Memeriksa apakah variabel `tipe_tiket` sama dengan "reguler".
Jika kondisi ini benar (True), maka nilai `harga_tiket` diatur ke `harga_reguler`.

Kondisi `elif`
Jika kondisi sebelumnya tidak terpenuhi (tipe_tiket bukan "reguler"), program akan memeriksa apakah `tipe_tiket` sama dengan "vip".
Jika benar, maka `harga_tiket` diatur ke harga_vip.

Kondisi `else`
Jika kedua kondisi di atas tidak terpenuhi (artinya `tipe_tiket` tidak valid), program mencetak pesan "Tipe tiket tidak valid!" dan kemudian menghentikan eksekusi program dengan `exit()`.

 ```python
if status_member == "Y":
    diskon = 0.20 * harga_tiket
    harga_akhir = harga_tiket - diskon
    print(f"Anda mendapatkan diskon 20%! Potongan harga: Rp{diskon:.2f}")
else:
    harga_akhir = harga_tiket
```
kondisi `if`
Memeriksa apakah `status_member` sama dengan "Y" (yang mungkin berarti pengguna adalah anggota).

Jika benar, maka:

Diskon dihitung sebagai 20% dari `harga_tiket`.
`harga_akhir` dihitung dengan mengurangi `diskon` dari `harga_tiket`.
Program mencetak pesan yang menyatakan bahwa pengguna mendapatkan diskon, termasuk jumlah potongan harga dalam format yang diinginkan.

Kondisi else:

Jika pengguna bukan anggota (status_member bukan "Y"), maka `harga_akhir` diatur sama dengan `harga_tiket` tanpa diskon

![foto](https://github.com/keeyyaaa/labpy2/blob/main/Screenshot%202024-10-30%20122909.png?raw=true)

# hasil kode program
![foto](https://github.com/keeyyaaa/labpy2/blob/main/Screenshot%202024-10-30%20125323.png?raw=true)


## penggunaa `if`, `elif` dan `else 

```python
if operator == '+':
    hasil = angka1 + angka2
    print(f"Hasil: {angka1} + {angka2} = {hasil}")
```
Memeriksa apakah operator yang dimasukkan adalah `+`.
Jika benar, maka kode menghitung jumlah `angka1` dan `angka2`, lalu mencetak hasilnya.

```python
elif operator == '-':
    hasil = angka1 - angka2
    print(f"Hasil: {angka1} - {angka2} = {hasil}")
elif operator == '*':
    hasil = angka1 * angka2
    print(f"Hasil: {angka1} * {angka2} = {hasil}")
```
`elif` digunakan untuk memeriksa kondisi berikutnya, yaitu jika operator adalah `-` atau `*`.
Setiap blok `elif` melakukan operasi yang sesuai (pengurangan atau perkalian) dan mencetak hasilnya.

```python
elif operator == '/':
    if angka2 != 0:
        hasil = angka1 / angka2
        print(f"Hasil: {angka1} / {angka2} = {hasil}")
    else:
        print("Error: Pembagian dengan nol tidak diperbolehkan!")
```
Memeriksa apakah operator adalah `/`.
Sebelum melakukan pembagian, kode memeriksa apakah `angka2` tidak sama dengan 0.
Jika `angka2` tidak sama dengan 0, maka pembagian dilakukan dan hasilnya dicetak.
Jika `angka`2 sama dengan 0, kode mencetak pesan kesalahan karena pembagian dengan nol tidak diperbolehkan.

```python
else:
    print("Operator tidak valid! Silakan masukkan +, -, *, atau /.") 
```
Jika semua kondisi sebelumnya tidak terpenuhi (misalnya, pengguna memasukkan operator yang tidak valid), maka blok `else` dieksekusi.

Program akan mencetak pesan bahwa operator tidak valid dan meminta pengguna untuk memasukkan operator yang benar.

# Gambzr Flowchart
![Foto](https://github.com/keeyyaaa/labpy2/blob/main/Screenshot%202024-10-30%20092416.png?raw=true)

