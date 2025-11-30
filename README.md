# PERTANYAAN 
## PERCOBAAN 1
1. Apakah fungsi tanpa parameter selalu harus bertipe void?
2. Apakah daftar menu pada program kafe dapat ditampilkan tanpa menggunakan fungsi Menu()? Modifikasi kode program tersebut untuk dapat menampilkan daftar menu tanpa menggunakan fungsi!
3. Jelaskan keuntungan menggunakan fungsi Menu() dibandingkan menulis semua perintah penampilan menu langsung di dalam fungsi main.
4. Uraikan secara singkat alur eksekusi program ketika fungsi Menu() dipanggil dari main (mulai dari program dijalankan sampai daftar menu tampil di layar).
**Jawaban:**
1. Tidak harus bertipe void, asalkan fungsi tersebut mengembalikan nilai.
2. Tidak bisa, karena harus memanggil fungsi Menu() di fungsi main
3. Fungsi memiliki kelebihan diantarannya adalah untuk mengurangi duplikasi kode serta mempermudah pemeliharaan program, hal ini cukup efektif karena hanya perlu untuk memanggil fungsi yang sudah ada.
4. Alur program :
- Program menjalankan fungsi main.
- Di dalam fungsi terdapat perintah Menu();.
- Program menjalankan fungsi Menu().
- print di dalam Menu() dieksekusi berurutan.