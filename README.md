# PERTANYAAN 
## PERCOBAAN 1
1. Apakah fungsi tanpa parameter selalu harus bertipe void?
2. Apakah daftar menu pada program kafe dapat ditampilkan tanpa menggunakan fungsi Menu()? Modifikasi kode program tersebut untuk dapat menampilkan daftar menu tanpa menggunakan fungsi!
3. Jelaskan keuntungan menggunakan fungsi Menu() dibandingkan menulis semua perintah penampilan menu langsung di dalam fungsi main.
4. Uraikan secara singkat alur eksekusi program ketika fungsi Menu() dipanggil dari main (mulai dari program dijalankan sampai daftar menu tampil di layar).
### Jawaban:
1. Tidak harus bertipe void, asalkan fungsi tersebut mengembalikan nilai.
2. Tidak bisa, karena harus memanggil fungsi Menu() di fungsi main
3. Fungsi memiliki kelebihan diantarannya adalah untuk mengurangi duplikasi kode serta mempermudah pemeliharaan program, hal ini cukup efektif karena hanya perlu untuk memanggil fungsi yang sudah ada.
4. Alur program :
- Program menjalankan fungsi main.
- Di dalam fungsi terdapat perintah Menu();.
- Program menjalankan fungsi Menu().
- print di dalam Menu() dieksekusi berurutan.

## PERCOBAAN 2
1. Apakah kegunaan parameter di dalam fungsi?
2. Jelaskan mengapa pada percobaan ini fungsi Menu() menggunakan parameter namaPelanggan dan isMember?
3. Apakah parameter sama dengan variabel? Jelaskan.
4. Jelaskan bagaimana cara kerja parameter isMember pada fungsi Menu(). Apa perbedaan output ketika isMember bernilai true dan ketika false?
5. Apa yang akan terjadi jika memanggil fungsi Menu() tanpa menyertakan parameter namaPelanggan dan isMember?
6. Modifikasi kode di atas dengan menambahkan parameter baru kodePromo (String). Jika kodePromo adalah "DISKON50", tampilkan berikan diskon 50%. Jika kodePromo adalah "DISKON30", tampilkan berikan diskon 30%. Jika tidak ada kode promo yang berlaku, tampilkan kode invalid.
7. Berdasarkan fungsi Menu() di atas, jika nama pelanggan adalah "Budi", pelanggan tersebut member, dan menggunakan kode promo "DISKON30", tuliskan satu baris perintah pemanggilan fungsi menu yang benar.
8. Menurut Anda, apakah penggunaan parameter namaPelanggan dan isMember pada fungsi Menu() membuat program lebih mudah dibaca dan dikembangkan dibandingkan jika nilai-nilai tersebut ditulis langsung di dalam fungsi tanpa parameter? Jelaskan alasan Anda.
### Jawaban:
1. Parameter di dalam fungsi berfungsi untuk memanggil nilai dari luar fungsi ke dalam fungsi.
2. Apabila tidak menggunakan parameter, String NamaPelanggan dan isMember harus ditulis manual dalam fungsi
3. Berbeda, parameter adalah variabel khusus yang digunakan untuk menerima nilai diluar fungsi. Sedangkan variabel digunakan di dalam sintaks biasa.
4. Parameter digunakan untuk mengetahui apakah pelanggan adalah member atau bukan. Jika isMember == true, kondisi if akan dijalankan.
5. Akan terjadi error pada program, karena fungsi Menu() harus mengembalikan nilai kepada fungsi main.
6. Sudah saya modifikasi.
7. Sudah saya modifikasi.
8. Iya, bisa digunakan tanpa mengubah isi fungsi dan apabila ingin menambah parameter lain lebih mudah.