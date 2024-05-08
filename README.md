```bash
Kelompok 3      : - 312210290 / MUHAMMAD ALBEDRI
                  - 312210293 / MUHAMMAD DIN AL AYUBI
                  - 312210321 / YUDI FERMANA
                  - 312210328 / ROSWANDA NURAINI
Judul Project   : Absensi QR Code
Kelas           : TI. 22. A3
Mata Kuliah     : Pemrograman Web 2
Dosen Pengampu  : Agung Nugroho,S.Kom.,M.Kom
```
<h2>Demo Aplikasi, Domain, dan Laporan</h2>

1. Demo terlampir pada link youtube, klik pada logo di bawah ini:
   
[<img src=https://download.logo.wine/logo/YouTube/YouTube-Logo.wine.png width="120px">]()

2. Laporan PDF, klik pada logo di bawah ini:
   
[<img src=https://images.bisnis.com/posts/2021/01/14/1342816/drive.jpg width="120px">](https://drive.google.com/file/d/1JTDfpgfCj9n9tFQg2Wab7GQ4PRRiYrLZ/view?usp=drive_link)

<h3>A. Gambaran Umum Sistem Absensi QR Code</h3>

Aplikasi Web Sistem Absensi Sekolah Berbasis QR Code adalah sebuah proyek yang bertujuan untuk mengotomatisasi proses absensi di lingkungan sekolah menggunakan teknologi QR code. Aplikasi ini dikembangkan dengan menggunakan framework CodeIgniter 4 dan didesain untuk mempermudah pengelolaan dan pencatatan kehadiran siswa dan guru.
Sistem operator petugas absensi siswa membantu sekolah untuk mengelola kehadiran siswa dengan lebih efisien, memantau kepatuhan siswa terhadap aturan kehadiran, dan memberikan informasi yang berguna kepada orang tua atau wali siswa tentang kehadiran anak mereka di sekolah. Berikut adalah gambaran umum dari sistem ini:
1. Perangkat Kedatangan : Biasanya, sistem ini menggunakan perangkat keras seperti mesin absensi atau ponsel pintar dengan aplikasi khusus untuk merekam kehadiran siswa. Perangkat ini dapat berupa kartu identitas siswa, kode QR untuk pendaftaran kehadiran.
2. Identifikasi Siswa : Setiap siswa memiliki identitas unik dalam sistem, seperti nomor siswa atau kartu identitas. Ini digunakan untuk merekam kehadiran dengan akurat. Ini bisa berupa:
   - **Penggunaan ID atau Kartu Absensi**: Karyawan menggunakan kartu identifikasi atau kode akses untuk masuk dan keluar dari tempat kerja. Sistem ini membutuhkan pembaca kartu atau mesin sidik jari untuk mengidentifikasi karyawan.
   
   - **Penggunaan Sidik Jari atau Pengenalan Wajah**: Sistem ini menggunakan teknologi pengenalan biometrik seperti sidik jari atau pemindaian wajah untuk mengidentifikasi karyawan. Hal ini memastikan tingkat keamanan dan akurasi yang tinggi.
   
   - **Aplikasi atau Perangkat Lunak Absensi**: Beberapa organisasi menggunakan aplikasi seluler atau perangkat lunak desktop yang memungkinkan karyawan untuk mencatat kehadiran mereka sendiri, baik melalui pengisian formulir atau check-in/check-out digital.

3. **Perangkat Lunak Pengelolaan** : Terdapat perangkat lunak yang terhubung dengan perangkat keras untuk mengelola dan menyimpan data kehadiran siswa. Perangkat lunak ini dapat menghasilkan laporan kehadiran, memantau absensi siswa secara realtime, dan mengirimkan pemberitahuan kepada orang tua atau wali siswa jika siswa tidak hadir.
4. **Database Siswa** : Informasi tentang setiap siswa, seperti nama, kelas, dan informasi
kontak, disimpan dalam database untuk referensi dan pelacakan.
5. **Fitur Pemantauan dan Pelaporan** : Sistem ini dapat memberikan kemampuan
pemantauan langsung kepada guru, staf sekolah, atau administrator. Mereka dapat melihat kehadiran siswa secara real-time dan mengambil tindakan yang diperlukan jika ada siswa yang sering absen atau terlambat.
6. **Integrasi dengan Sistem Sekolah** : Beberapa sistem operator petugas absensi siswa dapat terintegrasi dengan sistem manajemen siswa yang lebih besar. Ini memungkinkan transfer data yang lebih mudah antara sistem absensi dan sistem lainnya, seperti sistem manajemen kelas atau administrasi sekolah.
7. **Keamanan Data** : Karena sistem ini mengelola informasi pribadi siswa, keamanan data sangat penting. Ini termasuk enkripsi data, akses terbatas, dan langkah-langkah keamanan lainnya untuk melindungi informasi siswa.

<h3>B. Kebutuhan Sistem</h3>

    a. Functional (Use Case)

![img](img/1.jpg)

    b. Non-Functional
    Kebutuhan non-fungsional dalam aplikasi web sistem absensi sekolah berbasis QR
    Code meliputi beberapa aspek yang tidak langsung terkait dengan fungsi utama aplikasi, tetapi sangat penting dalam pengembangan dan implementasinya. Berikut adalah beberapa contoh kebutuhan non-fungsional yang relevan:
1. Keamanan: Aplikasi harus memastikan keamanan data siswa dan guru dengan menggunakan protokol enkripsi yang kuat untuk melindungi informasi sensitif. Perlindungan terhadap serangan siber, seperti serangan brute force dan SQL injection, harus diimplementasikan.
2. Ketersediaan: Aplikasi harus tersedia 24/7 sehingga pengguna dapat mengaksesnya kapan saja. Hal ini dapat dicapai dengan menggunakan infrastruktur hosting yang handal dan memiliki keandalan tinggi, serta melakukan pemeliharaan rutin untuk mencegah downtime.
3. Kinerja: Aplikasi harus responsif dan dapat menangani beban pengguna yang besar, terutama pada saat jam sibuk seperti saat siswa tiba di sekolah. Optimisasi kinerja, seperti caching data dan penggunaan teknologi web yang efisien, harus diterapkan untuk memastikan waktu respons aplikasi tetap cepat.
4. Skalabilitas: Aplikasi harus dapat diskalakan secara horizontal untuk mengakomodasi pertumbuhan jumlah siswa dan pengguna. Ini berarti sistem harus mampu menangani peningkatan lalu lintas tanpa mengurangi kinerja atau ketersediaan.
5. Interoperabilitas: Aplikasi harus dapat berintegrasi dengan sistem lain yang digunakan di sekolah, seperti sistem informasi siswa dan sistem manajemen kelas. Ini memungkinkan pertukaran data yang lancar antara aplikasi absensi dan sistem lainnya.
6. Kepatuhan Regulasi: Aplikasi harus mematuhi regulasi dan kebijakan privasi data yang berlaku, seperti GDPR (General Data Protection Regulation) di Uni Eropa atau COPPA (Children's Online Privacy Protection Act) di Amerika Serikat. Perlindungan data pribadi siswa harus menjadi prioritas utama.
7. User Experience (UX): Antarmuka pengguna haruslah ramah pengguna dan mudah digunakan, baik oleh siswa, guru, staf sekolah, maupun orang tua siswa. Desain responsif juga diperlukan agar aplikasi dapat diakses dari berbagai perangkat, mulai dari desktop hingga ponsel pintar.
8. Dukungan Bahasa: Aplikasi harus mendukung berbagai bahasa untuk memfasilitasi pengguna yang berasal dari berbagai latar belakang dan wilayah.
9. Dukungan Teknis: Tim dukungan teknis harus tersedia untuk memberikan bantuan kepada pengguna dalam menangani masalah teknis dan pertanyaan terkait penggunaan aplikasi.
10. Backup dan Pemulihan Data: Sistem harus memiliki prosedur backup dan pemulihan data yang teratur untuk melindungi data dari kehilangan atau kerusakan yang tidak terduga.
    
<h3>C. Rancangan Sistem</h3>

![img](img/2.jpg)
<h3>D. Rancangan Basis Data (Data Model/ERD)</h3>

![img](img/3.jpg)
<h3>E. Prototype (Desain Mockup/Figma)</h3>

| Halaman Dashboard                                                                                                   |                                                           Tampilan Absen Masuk                                                           |
| --------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------: |
| ![img](img/6.jpg) | ![img](img/4.jpg) |

| Tampilan Absen Keluar                                                                                                   |                                                           Tampilan Login Petugas                                                           |
| --------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------: |
| ![img](img/5.jpg) | ![img](img/login.jpg) |

| Tampilan Dashboard Petugas                                                                                                   |                                                           Tampilan CRUD Siswa (Dengan Data Kelas)                                                           |
| --------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------: |
| ![img](img/6.jpg) | ![img](img/7.jpg) |

| Tampilan CRUD Guru (Dengan Data Kelas)                                                                                                   |                                                           Tampilan Ubah Data Kehadiran                                                           |
| --------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------: |
| ![img](img/8.jpg) | ![img](img/ubah.jpg) |

| Tampilan CRUD Data Siswa                                                                                                   |                                                           Tampilan CRUD Data Guru                                                           |
| --------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------: |
| ![img](img/9.jpg) | ![img](img/10.jpg) |

| Tampilan CRUD Data Kelas dan Jurusan                                                                                                   |                                                           Tampilan Generate QR Code                                                           |
| --------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------: |
| ![img](img/14.jpg) | ![img](img/11.jpg) |

| Tampilan Generate Laporan                                                                                                   |
| --------------------------------------------------------------------------------------------------------------------------- |
| ![img](img/12.jpg) |

<h3>F. Hasil Akhir (Demo program)</h3>

[<img src=img/download.png width="120px">]()
# Aplikasi Web Sistem Absensi Sekolah Berbasis QR Code

Aplikasi Web Sistem Absensi Sekolah Berbasis QR Code adalah sebuah proyek yang bertujuan untuk mengotomatisasi proses absensi di lingkungan sekolah menggunakan teknologi QR code. Aplikasi ini dikembangkan dengan menggunakan framework CodeIgniter 4 dan didesain untuk mempermudah pengelolaan dan pencatatan kehadiran siswa dan guru.

## Fitur Utama

- **QR Code scanner.** Setiap siswa/guru menunjukkan qr code kepada perangkat yang dilengkapi dengan kamera. Aplikasi akan memvalidasi QR code dan mencatat kehadiran siswa ke dalam database.
- **Login petugas.**
- **Dashboard petugas.** Petugas sekolah dapat dengan mudah memantau kehadiran siswa dalam periode waktu tertentu melalui tampilan yang disediakan.
- **QR Code generator.** Petugas yang sudah login akan men-generate qr code setiap siswa/guru secara otomatis. Setiap siswa akan diberikan QR code unik yang terkait dengan identitas siswa. QR code ini akan digunakan saat proses absensi.
- **Ubah data absen siswa/guru.** Petugas dapat mengubah data absensi setiap siswa/guru. Misalnya mengubah data kehadiran dari `tanpa keterangan` menjadi `sakit` atau `izin`.
- **Tambah, Ubah, Hapus(CRUD) data siswa/guru.**
- **Tambah, Ubah, Hapus(CRUD) data kelas.**
- **Lihat, Tambah, Ubah, Hapus(CRUD) data petugas.** (khusus petugas yang login sebagai **`superadmin`**).
- **Generate Laporan.** Generate laporan dalam bentuk pdf.

## Framework dan Library Yang Digunakan

- CodeIgniter 4
- [Material Dashboard Bootstrap 4](https://www.creative-tim.com/product/material-dashboard-bs4)
- [Myth Auth Library](https://github.com/lonnieezell/myth-auth)
- [Endroid QR Code Generator](https://github.com/endroid/qr-code)
- [ZXing JS QR Code Scanner](https://github.com/zxing-js/library)

### Persyaratan

- [Composer](https://getcomposer.org/).
- PHP dan MySQL atau [XAMPP](https://www.apachefriends.org/download.html) versi 8.1+ dengan mengaktifkan extension `-intl` dan `-gd`.
- Pastikan perangkat memiliki kamera/webcam untuk menjalankan qr scanner. Bisa juga menggunakan kamera HP dengan bantuan software DroidCam.

### Instalasi

- Unduh dan impor kode proyek ini ke dalam direktori proyek anda (htdocs).
- Jika belum memiliki file `.env`, rename file `.env.example` menjadi `.env` atau jalankan perintah berikut:

```shell
# linux & macos, git bash
composer run-script setup-env
# windows cmd/powershell
composer run-script setup-env-win
```

- (Opsional) Konfigurasi file `.env` untuk mengatur parameter seperti koneksi database dan pengaturan lainnya sesuai dengan lingkungan pengembangan Anda.
- (Opsional) Ganti/replace logo sekolah di `public/assets/img/logo_sekolah.jpg`.
- (Opsional) Konfigurasi file `app/Config/App.php` untuk mengubah base url sesuai dengan nama folder project.
- Penting ⚠️. Install dependencies yang diperlukan dengan cara menjalankan perintah berikut di terminal:

```shell
composer install
```

- Buat database `db_absensi` di phpMyAdmin / mysql
- Penting ⚠️. Jalankan migrasi database untuk membuat struktur tabel yang diperlukan. Ketikkan perintah berikut di terminal:

```shell
php spark migrate --all
```

- Buka file `vendor/myth/auth/src/Config/Auth.php`. Lalu ubah kedua baris berikut:

```php
public $requireActivation = 'Myth\Auth\Authentication\Activators\EmailActivator';

public $activeResetter = 'Myth\Auth\Authentication\Resetters\EmailResetter';
```

- ubah value menjadi `null`:

```php
public $requireActivation = null;

public $activeResetter = null;
```

- (Opsional) Masih di file yang sama, ubah baris berikut:

```php
public $views = [
    'login'           => 'Myth\Auth\Views\login', // baris ini
    'register'        => 'Myth\Auth\Views\register',
    'forgot'          => 'Myth\Auth\Views\forgot',
    'reset'           => 'Myth\Auth\Views\reset',
    'emailForgot'     => 'Myth\Auth\Views\emails\forgot',
    'emailActivation' => 'Myth\Auth\Views\emails\activation',
];
```

menjadi:

```php
public $views = [
    'login'           => '\App\Views\admin\login', // menggunakan tampilan login custom
    'register'        => 'Myth\Auth\Views\register',
    'forgot'          => 'Myth\Auth\Views\forgot',
    'reset'           => 'Myth\Auth\Views\reset',
    'emailForgot'     => 'Myth\Auth\Views\emails\forgot',
    'emailActivation' => 'Myth\Auth\Views\emails\activation',
];
```

- Jalankan web server.
- Lalu jalankan aplikasi di browser.
- Login menggunakan krendensial superadmin:

```
username : superadmin
password : superadmin
```

Jika ingin mengubah email, username & password dari superadmin

Buka file `app\Database\Migrations\2023-08-18-000004_AddSuperadmin.php` lalu ubah & sesuaikan kode berikut:

```php
// INSERT INITIAL SUPERADMIN
$email = 'adminsuper@gmail.com';
$username = 'superadmin';
$password = 'superadmin';
```

- Izinkan akses kamera.

## Kesimpulan

Dengan aplikasi web sistem absensi sekolah berbasis QR code ini, diharapkan proses absensi di sekolah menjadi lebih efisien dan terotomatisasi. Proyek ini dapat diadaptasi dan dikembangkan lebih lanjut sesuai dengan kebutuhan dan persyaratan sekolah Anda.
