<div align="center">
  
# DIRGANTARA FLIGHT
Website maskapai penerbangan terpercaya yang mengantarkan Anda ke seluruh penjuru Indonesia dengan nyaman dan aman.

<img width="958" height="1600" alt="image" src="https://github.com/user-attachments/assets/3c166815-6e7f-45d1-ba90-ee958b7c2ed3" />


<br>
<br>

## ⭐ Fitur Unggulan Dirgantara Flight
</div>

### 👥 User 

- Pengalaman terbaik untuk perjalanan Anda <br>
- Dapatkan harga terbaik dengan sistem pembayaran yang fleksibel <br>
- Standar keamanan internasional untuk kenyamanan Anda <br>
- Komitmen on-time performance terbaik di kelasnya <br>

<img width="1240" height="1202" alt="Screenshot_29-9-2026_20019_127 0 0 1" src="https://github.com/user-attachments/assets/95757ace-e1a8-4494-8e59-12698740b7b4" />

<br>

### 👤 Admin
- Memantau akun para _admin_ dan _user_ 
- Memantau pesanan tiket _user_
- Memantau jadwal keberangkatan yang tersedia
- Dapat mengelola kota keberangkatan dan tujuan  

<img width="1240" height="1558" alt="image" src="https://github.com/user-attachments/assets/626dd85a-bfe3-4b60-bbea-2995c5ae795a" />


<br>

<div align="center"> 
  
## ❓ Cara menggunakan: 

</div>
<br>

Website ini dapat diakses secara _local_. Pastikan prasyarat berikut telah terinstal di sistem Anda:

| Komponen | Versi | Link Download |
|----------|-------|---------------|
| **Laragon** / XAMPP | Latest | [laragon.org](https://laragon.org/download/) / [apachefriends.org](https://www.apachefriends.org) |
| **Git** | Latest | [git-scm.com](https://git-scm.com/downloads) |
| **Laravel** | `v12` | [laravel.com/docs/12.x](https://laravel.com/docs/12.x) |
| **PHP** | `v8.3.21` | [php.net](https://www.php.net/downloads) |

<br>

 💡 **Catatan:** 
> - Disarankan menggunakan **Laragon** untuk pengalaman pengembangan yang lebih ringan dan modern

<br>

### Cara menjalankan website di local:
#### 1. Instalasi
- Buka terminal Laragon (disarankan), atau terminal lainnya.
- Arahkan ke folder yang akan Anda gunakan untuk menyimpan folder, contoh: ```cd C:\laragon\www```
- Jalankan perintah <i>clone</i>: ```git clone https://github.com/Makheswara-1606/airline <br>```

#### 2. _Run website:_
Setelah proses _clone_ selesai, Anda dapat me-_running_ website tersebut dengan langkah berikut:
- Buka terminal Laragon (disarankan), atau terminal lainnya.
- Arahakan ke folder hasil _clone_, contoh: ```cd C:\laragon\www\airline```
- Jalankan perintah ```npm run dev```
- Buka tab baru pada terminal, lalu jalankan lagi perintah ```php artisan serve```
- Setelah itu, Anda dapat membuka link yang seperti ini ``` INFO  Server running on [http://127.0.0.1:8000]``` dengan CTRL + Click

<br>

💡 **Catatan:** 
> - Seringkali ada error saat pertama kali di _run_, maka disarankan untuk jalankan ```install composer``` terlebih dahulu.

<br>

<div align="center">

  ## 📂 Struktur Folder
  
</div>

```text
📂 app                  
📂 bootstrap       
📂 config          
📂 database             
📂 public          
📂 resources            
📂 routes               
📂 storage           
📂 tests             
📄 .editorconfig     
📄 .env.example      
📄 .gitattributes    
📄 .gitignore        
📄 README.md         
📄 artisan           
📄 composer.json     
📄 composer.lock     
📄 package-lock.json 
📄 package.json      
📄 phpunit.xml       
📄 postcss.config.js 
📄 tailwind.config.js
📄 vite.config.js    
```

<br>

### 💡 Catatan:
> - Folder `vendor/`, `node_modules/`, dan file `.env` **tidak boleh di-upload ke GitHub**. Pastikan file `.gitignore` sudah mengaturnya.
> - Untuk menjalankan proyek, copy `.env.example` menjadi `.env`, lalu jalankan `php artisan key:generate`.
