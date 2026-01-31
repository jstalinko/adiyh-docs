---
sidebar_label: "Create Shortlink"
sidebar_position: 2
---

# Create Shortlink

- [ENGLISH](#english)
- [INDONESIAN](#indonesian)

---

## English

## How to Create a Shortlink

1. Go to **ADIYH → Shortlink**.
2. Click the **Add Shortlink** button.
3. Fill in the configuration form as described below.

### Shortlink Settings

1. **Shortlink Slug**  
   You can either leave this blank to generate a **Randomized** slug or create a **Customizable** short URL (e.g., `mysite.com/promo`).

2. **Rules (Traffic Split)**  
   This section allows you to define where the traffic goes.
   - **URL**: Input your destination Target URL(s).
   - **Traffic %**: Set the percentage of traffic for this specific URL.  
     _(Example: If you have two URLs, you can set 50% for each to split traffic evenly)._

3. **Manipulate Referer (Beta)**  
   _Optional_. This feature attempts to manipulate the HTTP referer visible to the target site.
   - It performs a standard standard request using custom HTTP headers (cURL) with the spoofed referer.
   - Then, it redirects the real visitor to the target URL.
   - **Note**: This does not directly change the visitor's browser history behavior but simulates the referer on the server-side request before redirection.

---

## Indonesian

## Cara Membuat Shortlink

1. Masuk ke **ADIYH → Shortlink**.
2. Klik tombol **Add Shortlink**.
3. Isi formulir konfigurasi seperti dijelaskan di bawah ini.

### Pengaturan Shortlink

1. **Shortlink Slug**  
   Anda bisa membiarkannya kosong untuk membuat slug **Acak (Random)** atau membuat URL pendek **Custom** sesuai keinginan (contoh: `mysite.com/promo`).

2. **Rules (Pembagian Traffic)**  
   Bagian ini memungkinkan Anda menentukan ke mana traffic akan diarahkan.
   - **URL**: Masukkan URL Target tujuan Anda.
   - **Traffic %**: Tentukan persentase traffic untuk URL ini.  
     _(Contoh: Jika Anda punya dua URL, Anda bisa atur masing-masing 50% untuk membagi traffic secara merata)._

3. **Manipulate Referer (Beta)**  
   _Opsional_. Fitur ini mencoba memanipulasi HTTP referer yang terlihat oleh situs target.
   - Sistem melakukan request standar menggunakan custom HTTP header (cURL) dengan referer palsu.
   - Kemudian, sistem mengarahkan pengunjung asli ke URL target.
   - **Catatan**: Ini tidak mengubah perilaku browser visitor secara langsung, tetapi mensimulasikan referer pada request sisi server sebelum redirect dilakukan.
