Pemrograman Web

Laporan Praktikum Layout Website menggunakan HTML

Gede Troy Wiswama Bhareswara

NIM : 42430052

FAKULTAS TEKNIK DAN INFORMATIKA PROGRAM STUDI TEKNOLOGI INFORMASI


1. PENDAHULUAN

HyperText Markup Language (HTML) merupakan bahasa markup standar yang digunakan untuk membangun dan menampilkan halaman web. HTML berfungsi untuk menentukan struktur dasar dari sebuah halaman, seperti teks, gambar, tautan, tabel, hingga formulir. Dengan HTML, konten dapat ditata sehingga dapat dipahami dan ditampilkan oleh browser.
Seiring perkembangan web, konsep HTML Semantik diperkenalkan untuk meningkatkan keterbacaan dan makna dari kode yang ditulis. HTML semantik adalah penggunaan elemen HTML yang sesuai dengan arti atau fungsinya, misalnya header, nav, article, section, dan footer. Elemen-elemen ini tidak hanya mempermudah pengembang dalam mengorganisir layout halaman web, tetapi juga membantu mesin pencari (SEO) dan teknologi bantu (assistive technology) memahami struktur konten dengan lebih baik.
Dalam praktikum pembuatan layout pemrograman web, pemahaman mengenai HTML dan HTML semantik sangat penting. Dengan memanfaatkan elemen semantik, layout yang dibuat akan lebih terstruktur, mudah dipelihara, serta meningkatkan aksesibilitas dan pengalaman pengguna


2. PEMBAHASAN

Pada praktikum ini, HTML digunakan sebagai dasar untuk menyusun struktur halaman web. Elemen-elemen dasar seperti html, head, dan body dipakai untuk membentuk kerangka utama. Selanjutnya, penerapan HTML semantik dilakukan dengan memanfaatkan elemen seperti header untuk bagian kepala halaman, nav untuk navigasi, section untuk isi utama, table untuk membuat table pada HTML, tr (table row) untuk membuat baris pada tabel, td (table data) untuk membuat sel data didalam baris tabel, article untuk konten mandiri, aside untuk konten tambahan atau pendukung, serta footer untuk bagian bawah halaman.

<img width="776" height="457" alt="Screenshot 2025-10-01 115007" src="https://github.com/user-attachments/assets/dbb7530c-62ae-4f66-904c-17ba11d2d3c4" />

Kode (index.html) HTML ini saya gunakan untuk membuat struktur halaman profil sekolah dengan menggunakan elemen semantik agar lebih rapi dan mudah dipahami. Pada bagian header, saya menampilkan judul serta deskripsi singkat sekolah, lalu di nav saya buat menu navigasi untuk berpindah ke halaman beranda, tentang, berita, dan kontak. Bagian utama halaman saya letakkan di main dengan article yang berisi sambutan, logo sekolah, serta penjelasan visi pendidikan. Lali di aside saya tambahkan informasi singkat seperti tahun berdirinya sekolah, akreditasi, dan jumlah siswa dalam bentuk daftar. Saya menggunakan elemen-elemen semantik ini karena ingin struktur halaman lebih jelas, mudah dibaca oleh pengguna maupun (SEO) mesin pencari, serta memudahkan saya dalam mengelola kode ke depannya.


<img width="552" height="422" alt="Screenshot 2025-10-01 192104" src="https://github.com/user-attachments/assets/2e38de5d-2090-47c1-826f-c19118b4f1ae" />

Kode (tentang.html) di atas saya gunakan untuk menampilkan struktur organisasi sekolah dalam bentuk tabel di dalam halaman web. Saya membuat bagian section dengan judul "Struktur Organisasi" menggunakan h2, lalu menampilkan tabel dengan atribut border="1" agar memiliki garis pembatas. Di dalam tabel, baris pertama tr berisi judul kolom "Jabatan" dan "Nama" yang ditulis dengan tag th. Setelah itu, saya menambahkan beberapa baris tr lagi yang masing-masing berisi jabatan, seperti Kepala Sekolah, Wakil Kepala Kesiswaan, dan Wakil Kepala Sarana dan Prasarana, beserta nama orang yang menjabat menggunakan td. Dengan kode ini, saya bisa menampilkan data jabatan dan nama dalam format tabel yang rapi dan mudah dibaca.


<img width="548" height="305" alt="Screenshot 2025-10-01 192337" src="https://github.com/user-attachments/assets/e8bbdfb6-1a81-4daf-9893-5eaed8389c42" />

Kode (kontak.html) di atas saya gunakan untuk membuat sebuah formulir sederhana berjudul "Formulir Saran & Kritik". Di dalam tag form, saya menambahkan beberapa input, yaitu untuk memasukkan nama dengan input type="text", email dengan input type="email", serta pesan menggunakan textarea. Masing-masing input diberi label label agar pengguna tahu data apa yang harus diisi, dan saya tambahkan atribut id serta name supaya data tersebut bisa dikenali saat dikirim. Untuk berpindah baris, saya memakai tag br. Terakhir, saya menambahkan tombol kirim button type="submit" agar pengguna bisa mengirim data yang mereka isi di formulir. 


<img width="1879" height="640" alt="Screenshot 2025-10-01 192007" src="https://github.com/user-attachments/assets/18d12569-2b4a-43b0-b13d-1a79e52265e8" />

Tampilan index.html



<img width="1161" height="497" alt="Screenshot 2025-10-01 192014" src="https://github.com/user-attachments/assets/c812c3b9-ae16-40bb-ad19-d4a60bd4aa07" />

Tampilan tentang.html



<img width="846" height="501" alt="Screenshot 2025-10-01 193659" src="https://github.com/user-attachments/assets/b56de507-3aa7-4c07-b267-59a4dc72dccd" />

Tampilan berita.html



<img width="512" height="569" alt="Screenshot 2025-10-01 192025" src="https://github.com/user-attachments/assets/1dfde191-577d-4ef8-954b-bfe61705d399" />

Tampilan kontak.html



3. KESIMPULAN

Kesimpulan dari praktikum ini adalah saya berhasil membuat layout website profil sekolah dengan HTML semantik sehingga struktur halaman lebih rapi, jelas, dan mudah dipahami. Melalui index.html, tentang.html, berita.html, dan kontak.html, saya mempraktikkan penggunaan elemen semantik, tabel, serta form, yang membuat website lebih teratur dan berfungsi. Dengan praktikum ini, saya semakin memahami pentingnya penggunaan HTML semantik dalam pembuatan website.


