A) Adapun Bootstrap hadir untuk membantu developer dalam membuat situs web dan aplikasi web dengan desain responsif dan tampilan yang bagus. Framework ini juga menyediakan kumpulan CSS, JavaScript, dan font yang dapat digunakan sebagai dasar untuk membuat situs web yang terlihat baik di seluruh perangkat, termasuk desktop, tablet, dan ponsel.Bootstrap digunakan untuk mengimplementasikan berbagai pilihan warna, ukuran, font, layout, yang ada dalam framework ke dalam website. Framework ini juga menawarkan beberapa komponen JavaScript dalam bentuk plugin jQuery sehingga pengguna bisa menggunakan beberapa fitur interaktif, seperti dialog box, tooltips, carousel, dan lain-lain.

B) 2. Memasang Bootstrap
Ada beberapa cara untuk memasang atau menggunakan Bootstrap pada project, yaitu:
1. Menggunakan CDN (Content Delivery Network), yaitu dengan menambahkan link CSS dan JavaScript Bootstrap dari internet ke dalam file HTML.
2. Mengunduh file Bootstrap, kemudian menghubungkan file CSS dan JavaScript Bootstrap yang telah diunduh ke dalam project.
3. Menggunakan package manager, seperti npm, untuk memasang Bootstrap ke dalam project.

C) 3. Grid dan Breakpoint
Grid adalah sistem tata letak Bootstrap yang digunakan untuk mengatur posisi dan lebar elemen pada halaman website. Grid Bootstrap menggunakan sistem 12 kolom yang dapat diatur menggunakan class seperti container, row, dan col.
Breakpoint adalah batas ukuran layar yang digunakan untuk menyesuaikan tampilan website pada perangkat dengan ukuran berbeda, seperti HP, tablet, dan komputer.
Contoh class breakpoint Bootstrap:
- col-sm-6 — mengatur lebar kolom pada layar berukuran kecil dan lebih besar.
- col-md-4 — mengatur lebar kolom pada layar berukuran sedang dan lebih besar.
- col-lg-3 — mengatur lebar kolom pada layar berukuran besar dan lebih besar.

D) Class Bootstrap
Berikut lima class Bootstrap beserta kegunaannya:
Class	Kegunaan
container	Membuat wadah untuk mengatur dan membatasi lebar konten.
row	Membuat baris untuk menampung kolom dalam sistem grid.
col	Membuat kolom untuk mengatur tata letak konten.
btn btn-primary	Membuat tombol dengan warna utama biru.
text-center	Membuat teks rata tengah.
img-fluid	Membuat gambar responsif agar menyesuaikan ukuran wadahnya.
d-flex	Mengaktifkan Flexbox untuk mengatur tata letak elemen.


E) Gambar Responsif
Agar foto atau gambar pada website responsif dan menyesuaikan ukuran layar perangkat, kita dapat menggunakan class img-fluid yang disediakan oleh Bootstrap.
Contoh penggunaan:
<img src="gambar.jpg" class="img-fluid" alt="Gambar">

Class img-fluid membuat gambar memiliki lebar maksimum sebesar 100% dari wadahnya dan tinggi otomatis mengikuti proporsi gambar. Dengan demikian, gambar tidak melampaui lebar wadah dan dapat menyesuaikan ukuran layar perangkat.
