
# SISPROPEL

Aplikasi ini digunakan untuk Kepolisian menangani laporan masyarakat yang masuk dan untuk Rakyat supaya mudah untuk melaporkan suatu insiden.

## Ingin coba live demo?
Silahkan akses websitenya secara langsung disini:
https://sispropel.fallxyn.my.id
## Fitur

- Realtime CCTV Viewer
- Realtime Report Viewer
- Kirim Laporan Langsung
- Autentikasi User (Middleware)
- Notifikasi E-Mail with SMTP.
- Custom HTML E-Mail.
- Ubah Status Laporan.
- Selesai / Hapus Laporan.
- Simplified User Interface.
- Dark & Light Mode


## Jalankan Projek

Jalankan command dibawah ini untuk melakukan instalasi projek dan jika sudah, buka http://localhost:8000/ jika dijalankan secara lokal.

```bash
git clone https://github.com/malpraku/cekongkir
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```


## Screenshots

![Home](https://i.ibb.co/c1KB4NQ/Screenshot-2023-04-07-075822.png)
Home

![Login](https://i.ibb.co/RQ72M8W/Screenshot-2023-04-07-085854.png)
Authentication

![Admin Panel](https://i.ibb.co/L6RYgNN/Screenshot-2023-04-07-075936.png)
Operator Panel

![Report Panel](https://i.ibb.co/170MnLq/Screenshot-2023-04-07-075853.png)
Reporting Form
