# UAS

    def main():
    total = 0
    while True:
        item = input("Masukkan item (atau 'selesai'): ")
        if item == 'selesai': break
        harga = float(input("Harga: "))
        jumlah = int(input("Jumlah: "))
        total += harga * jumlah
    
    diskon = total * 0.1 if total > 100000 else 0
    print(f"Total: {total:.2f}, Diskon: {diskon:.2f}, Bayar: {total - diskon:.2f}")

    main()  

penjelasan
total: Variabel ini digunakan untuk menghitung jumlah total harga dari barang yang dibeli.
while True: Program akan terus meminta input barang hingga pengguna mengetik 'selesai'.
input("Masukkan item (atau 'selesai')"): Menanyakan nama item yang ingin dibeli. Jika pengguna mengetik 'selesai', loop akan berhenti.
harga dan jumlah: Menanyakan harga dan jumlah barang yang dibeli, lalu menambahkan hasil perkalian harga dan jumlah ke total.
Perhitungan diskon: Jika total harga lebih dari 100.000, diskon sebesar 10% akan diberikan.
Output akhir: Program akan menampilkan total harga, diskon yang diberikan, dan jumlah yang harus dibayar setelah diskon.
  
