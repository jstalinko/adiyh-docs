---
sidebar_label: "Landing Page Blocks"
sidebar_position: 3
---

# Landing Page Blocks

- [ENGLISH](#english)
- [INDONESIAN](#indonesian)

---

## English

## Available Blocks & Shortcuts

These "Blocks" are code snippets you can use in the Landing Page Builder to fetch dynamic content. This includes visitor data, post content, and Asset Data.

### 1. General & Visitor Data

| Block Name       | Code Snippet       | Description                                 |
| :--------------- | :----------------- | :------------------------------------------ |
| **User IP**      | `{{$ip}}`          | Insert visitor IP address.                  |
| **User Agent**   | `{{$ua}}`          | Insert visitor user agent string.           |
| **Country Code** | `{{$countryCode}}` | Insert visitor country code (e.g., US, ID). |

### 2. Post Content

_Use these blocks if "Show Post in LP" is enabled in Campaign settings._

| Block Name       | Code Snippet           | Description                         |
| :--------------- | :--------------------- | :---------------------------------- |
| **Post Content** | `{{$post['content']}}` | Insert active post body content.    |
| **Post Title**   | `{{$post['title']}}`   | Insert active post title.           |
| **Post Excerpt** | `{{$post['excerpt']}}` | Insert active post summary/excerpt. |
| **Post URL**     | `{{$post['url']}}`     | Insert active post permalink.       |

### 3. Ads Placement

| Block Name    | Code Snippet                    | Description                                      |
| :------------ | :------------------------------ | :----------------------------------------------- |
| **Top Ad**    | `{{$ads['top']['content']}}`    | Insert content defined in "Top" ad placement.    |
| **Middle Ad** | `{{$ads['middle']['content']}}` | Insert content defined in "Middle" ad placement. |
| **Bottom Ad** | `{{$ads['bottom']['content']}}` | Insert content defined in "Bottom" ad placement. |

### 4. Asset Data (Dynamic Content)

_These blocks pull data from the [Asset Data](../campaign/asset-data.md) menu._

| Block Name          | Code Snippet                        | Description                                |
| :------------------ | :---------------------------------- | :----------------------------------------- |
| **Random Logo**     | `{{$lpdata['logo']['random']}}`     | Insert a random logo URL.                  |
| **All Logo**        | `{{$lpdata['logo']['all']}}`        | Insert all logo URLs (as array/list).      |
| **Random Keyword**  | `{{$lpdata['keywords']['random']}}` | Insert a random keyword.                   |
| **All Keyword**     | `{{$lpdata['keywords']['all']}}`    | Insert all keywords.                       |
| **Random Name**     | `{{$lpdata['name']['random']}}`     | Insert a random name.                      |
| **All Name**        | `{{$lpdata['name']['all']}}`        | Insert all names.                          |
| **Random Profile**  | `{{$lpdata['profile']['random']}}`  | Insert a random profile picture URL.       |
| **All Profile**     | `{{$lpdata['profile']['all']}}`     | Insert all profile picture URLs.           |
| **Random Image SS** | `{{$lpdata['ss']['random']}}`       | Insert a random background/screenshot URL. |
| **All Image SS**    | `{{$lpdata['ss']['all']}}`          | Insert all background/screenshot URLs.     |
| **Random Thumbs**   | `{{$lpdata['thumbs']['random']}}`   | Insert a random thumbnail URL.             |
| **All Thumbs**      | `{{$lpdata['thumbs']['all']}}`      | Insert all thumbnail URLs.                 |
| **Random Title**    | `{{$lpdata['title']['random']}}`    | Insert a random custom title.              |
| **All Title**       | `{{$lpdata['title']['all']}}`       | Insert all custom titles.                  |
| **Random Videos**   | `{{$lpdata['videos']['random']}}`   | Insert a random video URL.                 |
| **All Videos**      | `{{$lpdata['videos']['all']}}`      | Insert all video URLs.                     |

---

## Indonesian

## Blocks & Shortcuts yang Tersedia

"Blocks" di bawah ini adalah potongan kode (snippet) yang dapat Anda gunakan di Landing Page Builder untuk memanggil konten dinamis. Ini mencakup data pengunjung, konten artikel asli, dan Asset Data.

### 1. Data Umum & Pengunjung

| Nama Block       | Snippet Kode       | Deskripsi                                           |
| :--------------- | :----------------- | :-------------------------------------------------- |
| **User IP**      | `{{$ip}}`          | Memasukkan alamat IP pengunjung.                    |
| **User Agent**   | `{{$ua}}`          | Memasukkan user agent pengunjung.                   |
| **Country Code** | `{{$countryCode}}` | Memasukkan kode negara pengunjung (Contoh: ID, US). |

### 2. Konten Artikel (Post)

_Gunakan blocks ini jika "Show Post in LP" diaktifkan di pengaturan Campaign._

| Nama Block       | Snippet Kode           | Deskripsi                             |
| :--------------- | :--------------------- | :------------------------------------ |
| **Post Content** | `{{$post['content']}}` | Memasukkan isi artikel aktif.         |
| **Post Title**   | `{{$post['title']}}`   | Memasukkan judul artikel aktif.       |
| **Post Excerpt** | `{{$post['excerpt']}}` | Memasukkan ringkasan/excerpt artikel. |
| **Post URL**     | `{{$post['url']}}`     | Memasukkan link URL artikel aktif.    |

### 3. Penempatan Iklan (Ads)

| Nama Block    | Snippet Kode                    | Deskripsi                                         |
| :------------ | :------------------------------ | :------------------------------------------------ |
| **Top Ad**    | `{{$ads['top']['content']}}`    | Memasukkan konten iklan posisi "Top" (Atas).      |
| **Middle Ad** | `{{$ads['middle']['content']}}` | Memasukkan konten iklan posisi "Middle" (Tengah). |
| **Bottom Ad** | `{{$ads['bottom']['content']}}` | Memasukkan konten iklan posisi "Bottom" (Bawah).  |

### 4. Asset Data (Konten Dinamis)

_Blocks ini mengambil data dari menu [Asset Data](../campaign/asset-data.md)._

| Nama Block          | Snippet Kode                        | Deskripsi                                    |
| :------------------ | :---------------------------------- | :------------------------------------------- |
| **Random Logo**     | `{{$lpdata['logo']['random']}}`     | Memasukkan 1 URL logo secara acak.           |
| **All Logo**        | `{{$lpdata['logo']['all']}}`        | Memasukkan semua data logo.                  |
| **Random Keyword**  | `{{$lpdata['keywords']['random']}}` | Memasukkan 1 keyword acak.                   |
| **All Keyword**     | `{{$lpdata['keywords']['all']}}`    | Memasukkan semua data keyword.               |
| **Random Name**     | `{{$lpdata['name']['random']}}`     | Memasukkan 1 nama acak.                      |
| **All Name**        | `{{$lpdata['name']['all']}}`        | Memasukkan semua data nama.                  |
| **Random Profile**  | `{{$lpdata['profile']['random']}}`  | Memasukkan 1 URL foto profil acak.           |
| **All Profile**     | `{{$lpdata['profile']['all']}}`     | Memasukkan semua data foto profil.           |
| **Random Image SS** | `{{$lpdata['ss']['random']}}`       | Memasukkan 1 URL screenshot background acak. |
| **All Image SS**    | `{{$lpdata['ss']['all']}}`          | Memasukkan semua data screenshot background. |
| **Random Thumbs**   | `{{$lpdata['thumbs']['random']}}`   | Memasukkan 1 URL thumbnail acak.             |
| **All Thumbs**      | `{{$lpdata['thumbs']['all']}}`      | Memasukkan semua data thumbnail.             |
| **Random Title**    | `{{$lpdata['title']['random']}}`    | Memasukkan 1 judul custom acak.              |
| **All Title**       | `{{$lpdata['title']['all']}}`       | Memasukkan semua data judul custom.          |
| **Random Videos**   | `{{$lpdata['videos']['random']}}`   | Memasukkan 1 URL video acak.                 |
| **All Videos**      | `{{$lpdata['videos']['all']}}`      | Memasukkan semua data URL video.             |
