# Laporan Praktikum - Analisis HTTP Request & Response

## Identitas Mahasiswa
- **Nama:** Muhammad Aril Saputra
- **NPM:** 2440304029

---

## Tabel Analisis HTTP Request & Response

| Method & Endpoint | Status | Content-Type | Ukuran | Fungsi Request |
| :--- | :---: | :--- | :---: | :--- |
| `GET /api/time` | `200 OK` | `application/json` | 917 B | Menampilkan response waktu dari API |
| `GET /images/icon.png` | `200 OK` | `image/webp` | 3.55 KB | Menampilkan gambar atau logo dari BMKG |
| `GET https://cdn.userway.org/widget.js` | `200 OK` | `gzip` | 0 B | Memanggil atau mengunduh library UI/UX UserWay |
| `GET /favicon.ico` | `200 OK` | `image/vnd.microsoft.icon` | 15.41 KB | Memanggil dan menampilkan favicon website |
| `GET /_nuxt/DcDKemvJ.js` | `200 OK` | `application/javascript` | 977 B | Library/Script dari framework Nuxt.js |

---

## Rincian Pengamatan DevTools Network

1. **`GET /api/time`**
   - **URL / Host:** `www.bmkg.go.id`
   - **Initiator:** `BTObmttz.js:4 (fetch)`
   - **Tipe Data:** `json`
   - **Ukuran:** `917 B (Transfer: 35 B)`
   - **Status:** `200 OK`
   - **Fungsi:** Menampilkan response data waktu dari API backend BMKG.

2. **`GET /images/icon.png`**
   - **URL / Host:** `www.bmkg.go.id`
   - **Tipe Data:** `img / webp`
   - **Ukuran:** `3.55 kB (cached)`
   - **Status:** `200 OK`
   - **Fungsi:** Memuat file aset logo/ikon visual pada halaman web BMKG.

3. **`GET https://cdn.userway.org/widget.js`**
   - **URL / Host:** `cdn.userway.org`
   - **Initiator:** `CW89u0be.js:18 (script)`
   - **Tipe Data:** `js`
   - **Ukuran:** `0 B (cached)`
   - **Status:** `200 OK`
   - **Fungsi:** Mengunduh dan mengaktifkan skrip widget aksesibilitas UI/UX pihak ketiga (UserWay).

4. **`GET /favicon.ico`**
   - **URL / Host:** `www.bmkg.go.id`
   - **Tipe Data:** `img / vnd.microsoft.icon`
   - **Ukuran:** `15.41 kB (cached)`
   - **Status:** `200 OK`
   - **Fungsi:** Menampilkan ikon tab browser (favicon) resmi website BMKG.

5. **`GET /_nuxt/DcDKemvJ.js`**
   - **URL / Host:** `www.bmkg.go.id`
   - **Initiator:** Script
   - **Tipe Data:** `js / application/javascript`
   - **Ukuran:** `977 B (cached)`
   - **Status:** `200 OK`
   - **Fungsi:** Bundle skrip JavaScript frontend dari framework Nuxt untuk fungsionalitas interaktif web.

---

## H. Refleksi Mahasiswa

### 1. Konsep apa yang paling Anda pahami pada praktikum ini?
> Saya memahami bagaimana cara browser bekerja untuk memanggil, menampilkan, serta mengelola isi konten request maupun response yang diberikan oleh server website ke browser pengguna.

### 2. Kesalahan/masalah apa yang ditemukan dan bagaimana cara menyelesaikannya?
> Dalam pengerjaan ini saya tidak menemukan masalah sama sekali.

### 3. Bukti apa yang menunjukkan bahwa hasil Anda sudah benar?
> Bukti bahwa data atau hasil sudah benar dapat dilihat dari status response `200 OK` pada Network Inspector/DevTools, di mana browser berhasil menerima seluruh response dan aset dari server website.

### 4. Jika menggunakan AI, bagian apa yang dibantu dan bagaimana Anda memverifikasinya?
> Tidak ada. Saya tidak menggunakan AI.
