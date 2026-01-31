---
sidebar_label: "Add Ads"
sidebar_position: 1
---

# Add New Ads

- [ENGLISH](#english)
- [INDONESIAN](#indonesian)

---

## English

## Create New Ad Unit

This guide explains how to add and configure new ad units in ADIYH. Creating ad units allows you to place them dynamically across your campaigns or website.

### How to Add Ads

1. Go to **ADIYH → Ads Setting**.
2. Click the **Add New Ads** button.
3. A modal/popup window will appear with the ad configuration form.

---

### Ad Settings Explanation

#### 1. Name

Give your ad a unique name for identification. This name will appear in the **Create Campaign** form when you select ads.

#### 2. Type

Select the type of ad content:

- **Code**: For raw HTML, JS scripts, or ad tags (e.g., Google AdSense, banners).
- **URL**: For direct destination links (e.g., direct offers, affiliate links).

#### 3. Opacity

Sets the transparency level of the ad.

- **Range**: `0` to `1` (e.g., `0.5` is 50% transparent).
- **Note**: The lower the number, the more transparent the ad becomes. This setting **does not apply** if Type is set to `URL`.

#### 4. Display In

Determines where this ad unit is available to be used:

- **Plugin**: The ad will be available for selection inside **Campaigns** (Landing Pages).
- **Website**: The ad will be displayed on the Main Website (global WordPress site).

#### 5. Placement

Select the specific position for the ad based on the **Display In** selection:

**If Display In = Website:**

- **After `<body>`**: Placing Ads after body tag html.
- **Before Post**: Placed before the article content begins.
- **After Post**: Placed after the article content ends.
- **Between Post Paragraph 1**: Inserted after the 1st paragraph.
- **Between Post Paragraph 4**: Inserted after the 4th paragraph.

**If Display In = Plugin:**

- **Top**: Top of the landing page.
- **Middle**: Middle of the landing page.
- **Bottom**: Bottom of the landing page.
- **Between Post Paragraph**: Inside the article content (Only active if _"Show Post in LP"_ is enabled in Campaign).
- **Popup**: Displays as a popup overlay.
- **Fullscreen**: Displays as a full-page overlay.

#### 6. Content

Input the actual content of your ad based on the chosen **Type**:

- If `Type: Code` → Paste your `<script>` tags, `<iframe>`, or raw HTML here.
- If `Type: URL` → Paste the destination URL link here.

---

## Indonesian

## Membuat Iklan Baru

Panduan ini menjelaskan cara menambahkan dan mengatur unit iklan baru di ADIYH. Membuat unit iklan memungkinkan Anda menempatkannya secara dinamis di seluruh campaign atau website Anda.

### Cara Menambah Iklan

1. Masuk ke **ADIYH → Ads Setting**.
2. Klik tombol **Add New Ads**.
3. Jendela modal/popup akan muncul dengan formulir pengaturan iklan.

---

### Penjelasan Pengaturan Iklan

#### 1. Name

Berikan nama unik sebagai identitas iklan. Nama ini akan muncul di formulir **Create Campaign** saat Anda memilih iklan.

#### 2. Type

Pilih jenis konten iklan:

- **Code**: Untuk kode HTML mentah, script JS, atau tag iklan (contoh: Google AdSense, banner).
- **URL**: Untuk link tujuan langsung (contoh: direct offer, link afiliasi).

#### 3. Opacity

Mengatur tingkat transparansi iklan.

- **Rentang**: `0` sampai `1` (contoh: `0.5` adalah 50% transparan).
- **Catatan**: Semakin kecil angkanya, semakin transparan iklannya. Pengaturan ini **tidak berlaku** jika Type adalah `URL`.

#### 4. Display In

Menentukan di mana unit iklan ini tersedia untuk digunakan:

- **Plugin**: Iklan akan tersedia untuk dipilih di dalam **Campaigns** (Landing Page).
- **Website**: Iklan akan ditampilkan di Website Utama (situs WordPress global).

#### 5. Placement

Pilih posisi spesifik untuk penempatan iklan berdasarkan pilihan **Display In**:

**Jika Display In = Website:**

- **After `<body>`**: Ditempatkan setelah tag html body.
- **Before Post**: Ditempatkan sebelum konten artikel dimulai.
- **After Post**: Ditempatkan setelah konten artikel berakhir.
- **Between Post Paragraph 1**: Disisipkan setelah paragraf pertama.
- **Between Post Paragraph 4**: Disisipkan setelah paragraf keempat.

**Jika Display In = Plugin:**

- **Top**: Bagian atas landing page.
- **Middle**: Bagian tengah landing page.
- **Bottom**: Bagian bawah landing page.
- **Between Post Paragraph**: Di dalam konten artikel (Hanya aktif jika _"Show Post in LP"_ aktif di Campaign).
- **Popup**: Tampil sebagai popup overlay.
- **Fullscreen**: Tampil sebagai overlay layar penuh.

#### 6. Content

Masukkan isi sebenarnya dari iklan Anda berdasarkan **Type** yang dipilih:

- Jika `Type: Code` → Tempel tag `<script>`, `<iframe>`, atau raw HTML di sini.
- Jika `Type: URL` → Tempel link URL tujuan di sini.
