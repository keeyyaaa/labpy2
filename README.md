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


# Gambzr Flowchart
![Foto](https://github.com/keeyyaaa/labpy2/blob/main/Screenshot%202024-10-30%20092416.png?raw=true)

