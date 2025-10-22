jawaban percobaan 1
1. Sebutkan dan tunjukkan masing-masing komponen perulangan FOR pada kode program Percobaan 1!
jawab; for (int i = 1; i <= 10; i++) 
-inisialisasi; int i=1 menentukan mulai hitung dari 1
-kondisi; i <=10 mengecek apakah perulangan lanjut
-update; i++ menambah nilai i tiap perulangan 

2. Mengapa variabel tertinggi diinisialisasi O dan terendah diinisialisasi 100? Apa yang terjadi jika variabel tertinggi diinisialisasi 100 dan terendah diinisialisasi 0?
jawab; Karena nilai mahasiswa berkisar antara 0–100.
Tertinggi dibuat 0 supaya bisa diganti jika ada nilai lebih besar,
terendah dibuat 100 supaya bisa diganti jika ada nilai lebih kecil.
Kalau dibalik, hasilnya salah karena tidak akan ada nilai yang melebihi 100 atau kurang dari 0

3. Jelaskan fungsi dan alur kerja dari potongan kode berikut!
if (nilai } tertinggi) { tertinggi nilai; if (nilai terendah) ( terendah } nilai;
jawab; fungsinya untuk mencari dan menyimpan nilai paling tinggi dan paling rendah 
alur kerjanya setiap kali user memasukkan nilai,jika nilai lebih besar maka ubah tertinggi menjadi nilai, jika nilai lebih kecil maka ubah terendah menjadi nilai 

jawabahn percobaan 2
1. Pada potongan kode berikut, tentukan maksud dan kegunaan dari sintaks berikut:
if (nilai || nilai > 100) {
} System.out.println(x: "Nilai tidak valid. Masukkan lagi nilai yang valid!"); continue;
jawab; 
a. nilai < 0 || nilai > 100 (untuk mengecek apakah nilai di luar batas valid 0-100)
b. continue (melewati sisa kode di perulangan dan langsung lanjut ke perulangan berikutnya,Jadi kalau nilai tidak valid, program ulangi input untuk mahasiswa yang sama)

2. Mengapa sintaks i++ dituliskan di akhir perulangan WHILE? Apa yang terjadi jika posisinya dituliskan di awal perulangan WHILE?
jawab; Karena i++ menandakan perpindahan ke mahasiswa berikutnya. Jika i++ ditulis di awal, maka perulangan akan melewatkan mahasiswa pertama, dan jumlah input tidak sesuai kurang satu

3. Apabila jumlah mahasiswa yang dimasukkan adalah 19, berapa kali perulangan WHILE akan berjalan?
jawab; Karena perulangan dimulai dari i = 0 dan kondisi i < jml,
maka perulangan berjalan sebanyak 19 kali (dari i = 0 sampai i = 18)

jawaban percobaan 3
1. Pada penggunaan DO-WHILE ini, apabila nama pelanggan yang dimasukkan pertama kali adalah "batal", maka berapa kali perulangan dilakukan?
jawab;tidak mengulang, karena belum mencapai value untuk melalukan DO-WHILE 

2. Sebutkan kondisi berhenti yang digunakan pada perulangan DO-WHILE tersebut!
Jawab; jika input sama dengan "batal" (huruf besar atau kecil tidak masalah), maka perulangan dihentikan menggunakan break

3. Apa fungsi dari penggunaan nilai true pada kondisi DO-WHILE?
jawab; Nilai true berarti perulangan berjalan tanpa batas (infinite loop).
Perulangan hanya akan berhenti jika ada perintah break di dalamnya, seperti pada saat pelanggan mengetik "batal"

4. Mengapa perulangan DO-WHILE tersebut tetap berjalan meskipun tidak ada komponen inisialisasi dan update?
jawab; Karena DO-WHILE tidak butuh inisialisasi dan update khusus.
Perulangannya jalan terus selama kondisinya true dan dihentikan pakai break