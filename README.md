# Muhammad Rizal Hardiansyah (312410257)
latihan 1
![Screenshot_20241111_105928_Chrome](https://github.com/user-attachments/assets/43fe4bbc-9a81-4319-b783-8a029ca01329)
![Screenshot_20241111_105938_Chrome](https://github.com/user-attachments/assets/81ede701-8047-4e60-a2a6-1fee5b0d6869)
Penjelasan Alur algoritma pada program diatas:

1. Program dimulai dengan mengimpor fungsi random dari modul random Python

2. Didefinisikan sebuah fungsi bernama generate_random_numbers()

3. Alur dalam fungsi:

* Meminta input nilai N dari user

* Menginisialisasi variabel count = 1

* Melakukan perulangan while selama count <= N:

* Generate angka random antara 0-1 menggunakan random()

* Jika angka random < 0.5:

      Cetak data ke-count beserta nilai randomnya

      Increment count


 * Setelah perulangan selesai, cetak "Selesai"

4. Program utama memanggil fungsi generate_random_numbers()

Dari output yang terlihat, ketika dijalankan:

* User memasukkan N = 5

* Program menghasilkan 5 angka random yang nilainya < 0.5

* Setiap angka dicetak dengan format "data ke: [urutan] => [nilai random]"

* Program berakhir dengan mencetak "Selesai"

Program ini pada dasarnya membangkitkan N buah angka random antara 0-1, namun hanya mencetak angka-angka yang nilainya kurang dari 0.5.

latihan 2

Penjelasan Alur algoritma pada program diatas:

1. Inisialisasi awal:

* modal_awal = 10000000

*laba_bulanan = [] (list kosong untuk menyimpan laba per bulan)

* total_laba = 0

2. Perulangan untuk bulan 1-8:

* Menggunakan for loop for bulan in range(1, 9)

* Perhitungan laba berdasarkan kondisi:

      Bulan 1-2: laba = 0 (belum ada laba)

      Bulan 3-4: laba = 1% dari modal awal (0.01 × modal_awal)

      Bulan 5-7: laba = 5% dari modal awal (0.05 × modal_awal)

      Bulan 8: laba = 2% dari modal awal (0.02 × modal_awal)

Setiap laba bulanan ditambahkan ke list laba_bulanan

* Total laba diakumulasi

3. Menampilkan hasil:

* Menggunakan enumerate untuk menampilkan laba per bulan

* Format output: "laba bulan ke-[nomor_bulan] sebesar: [jumlah_laba]"

* Di akhir menampilkan total laba keseluruhan

Dari output yang terlihat:

     Bulan 1-2: Rp 0

     Bulan 3-4: Rp 1.000.000

     Bulan 5-7: Rp 5.000.000

     Bulan 8: Rp 2.000.000

Total laba: Rp 19.000.000

Program ini mensimulasikan perhitungan laba bulanan dari sebuah investasi dengan persentase keuntungan yang berbeda-beda tiap periodenya.
