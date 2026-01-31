---
sidebar_label: "Create Campaign"
sidebar_position: 2
---

# Create Campaign

- [ENGLISH](#english)
- [INDONESIAN](#indonesian)

---

## English

## Create Campaign Guide

After filling in the [Asset Data](./asset-data.md), the next step is to create a Campaign.  
The Campaign allows you to configure how your landing page looks, who can see it, and how it behaves.

---

## How to Create a Campaign

1. **Go to WordPress Dashboard**
2. Navigate to **ADIYH → Campaign**
3. Click the **Add New Campaign** button
4. Fill in the required fields below
5. Click **Publish** or **Save** to make your campaign live.

---

## Campaign Form Explanation

### 1. General & Design

- **Slug**: The unique identifier for your campaign URL. Used to access your campaign (e.g., `http://your-site.com/slug`).
- **Theme**: The design template for your campaign. You can select multiple themes, and they will be displayed randomly to visitors.

### 2. Targeting & Security

- **Cloaking URL**: The safe URL displayed to **bots or non-targeted visitors**. Used to hide your real campaign/money page from unwanted traffic.
- **Lock Referer**: Whitelist allowed referers. Supports wildcard `*`.  
  _Example:_ `google.com` or `*.google.com`. Leave blank to allow all referers.
- **Lock Browser**: Whitelist specific browsers allowed to view the campaign.
- **Lock Country**: Whitelist visitor countries. Select specific countries or choose **ALLOW ALL** to accept traffic from everywhere.
- **Max Visit**: Maximum number of visits allowed per IP address. Useful for preventing bot flooding. Set to `0` to disable.
- **Block VPN**: Automatically block visitors detected using a VPN.
- **Adiyh Cloaking Signature**: Enable this if you use **hideiyh.pw (ACS)**. Ensures the campaign can ONLY be visited via your ACS URL.

### 3. Content & Behavior

- **Target Posts**: The destination URL(s) for valid, targeted visitors.  
  _Example:_ If a visitor matches your Country/Browser rules, they are redirected here. Multiple URLs will be rotated randomly.
- **Show Post in LP**: Displays article content inside the campaign landing page (fetched from Target Posts).
- **Auto Translate LP**: Automatically translates the campaign content to the visitor's local language.
- **Auto Scroll & Timer**: Automatically scrolls the page to the bottom and back up. You can set the timer delay for when this action starts.
- **Auto Refresh & Timer**: Automatically refreshes the page after a set time delay.
- **Auto Refresh URL**: Automatically refreshes the page to the specified URL after a set time delay, if not set it will refresh to the same URL.
- **Double Campaign & Slug**: Activates a secondary campaign sequence.
  - The second campaign triggers on **mouseover**.
  - After **10 seconds**, the visitor is redirected to the second campaign slug.
- **Ads Follow Pointer**: Causes the ad to float and follow the user's mouse cursor movement.

### 4. Ads Placement

Select ads created in **Ads Setting** (where `display_in = plugin`).

- **Ads Top**: Displays ads in the **TOP** position (supports Popup).
- **Ads Middle**: Displays ads in the **MIDDLE** position (supports Popup).
- **Ads Content**: Displays ads **BETWEEN POST PARAGRAPHS**. Only active if **"Show Post in LP"** is enabled.
- **Ads Bottom**: Displays ads in the **BOTTOM** position.

---

## Indonesian

## Panduan Membuat Campaign

Setelah mengisi [Asset Data](./asset-data.md), langkah selanjutnya adalah membuat Campaign.  
Campaign memungkinkan Anda mengatur tampilan landing page, target pengunjung, dan perilaku halaman.

---

## Cara Membuat Campaign

1. **Masuk ke Dashboard WordPress**
2. Buka menu **ADIYH → Campaign**
3. Klik tombol **Add New Campaign**
4. Isi kolom yang tersedia sesuai penjelasan di bawah
5. Klik **Publish** atau **Save** untuk membuat campaign live.

---

## Penjelasan Form Campaign

### 1. Umum & Desain

- **Slug**: Pengenal unik untuk URL campaign Anda. Contoh: `http://situs-anda.com/slug`.
- **Theme**: Desain tampilan (tema) campaign. Anda dapat memilih beberapa tema sekaligus untuk ditampilkan secara acak.

### 2. Target & Keamanan

- **Cloaking URL**: URL "aman" yang akan ditampilkan kepada **bot atau pengunjung yang tidak sesuai target**. Berguna untuk menyembunyikan halaman asli Anda.
- **Lock Referer**: Membatasi akses hanya dari referer tertentu. Mendukung wildcard `*`.  
  _Contoh:_ `google.com` atau `*.google.com`. Kosongkan untuk mengizinkan semua referer.
- **Lock Browser**: Memilih browser tertentu yang diizinkan mengakses campaign.
- **Lock Country**: Memilih negara asal pengunjung yang diizinkan. Pilih **ALLOW ALL** untuk semua negara.
- **Max Visit**: Batas maksimal kunjungan per alamat IP. Berguna mencegah spam/bot. Isi `0` untuk nonaktifkan.
- **Block VPN**: Memblokir pengunjung yang terdeteksi menggunakan VPN.
- **Adiyh Cloaking Signature**: Aktifkan jika menggunakan **hideiyh.pw (ACS)**. Campaign hanya bisa diakses melalui URL ACS.

### 3. Konten & Perilaku

- **Target Posts**: URL tujuan untuk pengunjung asli (valid visitor).  
  _Contoh:_ Pengunjung dari negara yang diizinkan akan diarahkan ke sini. Jika ada banyak URL, akan dipilih acak.
- **Show Post in LP**: Menampilkan artikel di dalam landing page (diambil dari Target Posts).
- **Auto Translate LP**: Menerjemahkan bahasa campaign secara otomatis mengikuti bahasa pengunjung.
- **Auto Scroll & Timer**: Halaman otomatis menggulir (scroll) ke bawah dan atas. Anda bisa mengatur waktu jeda (timer) sebelum scroll dimulai.
- **Auto Refresh & Timer**: Halaman otomatis memuat ulang (refresh) setelah waktu tertentu.
- **Auto Refresh URL**: Halaman otomatis memuat ulang (refresh) ke URL yang ditentukan setelah waktu tertentu, jika tidak diisi maka akan memuat ulang ke URL yang sama.
- **Double Campaign & Slug**: Mengaktifkan skenario dua campaign.
  - Campaign kedua aktif saat ada gerakan mouse (**mouseover**).
  - Setelah **10 detik**, pengunjung diredirect ke slug campaign kedua.
- **Ads Follow Pointer**: Membuat iklan melayang mengikuti pergerakan kursor mouse pengunjung.

### 4. Penempatan Iklan (Ads)

Pilih iklan yang sudah dibuat di menu **Ads Setting** (dengan status `display_in = plugin`).

- **Ads Top**: Menampilkan iklan di posisi **ATAS** (bisa Popup).
- **Ads Middle**: Menampilkan iklan di posisi **TENGAH** (bisa Popup).
- **Ads Content**: Menampilkan iklan **DI ANTARA PARAGRAF**. Hanya aktif jika **"Show Post in LP"** aktif.
- **Ads Bottom**: Menampilkan iklan di posisi **BAWAH**.
