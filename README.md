# Harga tiket
harga_reguler = 50000
harga_vip = 100000
diskon_member = 0.2

# Meminta input dari user
tipe_tiket = input("Masukkan tipe tiket (reguler/vip): ").lower()
status_member = input("Apakah Anda memiliki kartu member? (ya/tidak): ").lower()

# Menghitung harga berdasarkan tipe tiket
if tipe_tiket == "reguler":
    harga_tiket = harga_reguler
elif tipe_tiket == "vip":
    harga_tiket = harga_vip
else:
    print("Tipe tiket tidak valid.")
    harga_tiket = 0

# Menentukan apakah user mendapatkan diskon
total_harga = harga_tiket * (1 - diskon_member) if status_member == "ya" else harga_tiket

# Menampilkan hasil
if harga_tiket != 0:
    print(f"Total harga yang harus dibayar: Rp{total_harga}")

# Gambzr Flowchart
![Foto](https://github.com/keeyyaaa/labpy2/blob/main/Screenshot%202024-10-30%20092416.png?raw=true)

