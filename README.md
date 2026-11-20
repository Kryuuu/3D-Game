<div align="center">

# 🤖 Jaga Server 3D

### Tower defense 3D + mancing 3D dalam **satu file HTML**. Tanpa install, tanpa server, langsung main.

[![Three.js](https://img.shields.io/badge/Three.js-r160-black?logo=threedotjs&logoColor=white)](https://threejs.org/)
[![HTML5](https://img.shields.io/badge/HTML5-single--file-E34F26?logo=html5&logoColor=white)](https://github.com/Kryuuu/codero-defend)
[![Stages](https://img.shields.io/badge/stage-20-blueviolet)](#-mode--stage)
[![Ikan](https://img.shields.io/badge/ikan-12_spesies-0ea5e9)](#-ikan)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#-lisensi)

**[▶️ Main Sekarang](#-cara-main) · [🎣 Mode Mancing](#-mode-mancing-3d) · [💾 Kode Backup](#-kode-backup--pindah-device)**

</div>

---

## 🎮 Tentang Game

**Jaga Server 3D** adalah game tower defense 3D yang dibuat dengan [Three.js](https://threejs.org/) — seluruh gamenya hidup di **satu file `index.html`**. Bangun pasukan robot penjaga server, hadang gelombang virus yang menyerang, jawab kuis untuk bonus koin, lalu santai sejenak dengan **mode mancing 3D** yang lengkap: RNG ikan, pancingan bertingkat, aquarium pajangan, sampai sistem jual ikan.

> Dulu dikenal sebagai *Codero: Jaga Server* — kini dengan nama dan identitas barunya.

---

## ✨ Fitur Utama

| | |
|---|---|
| 🗼 **Tower Defense 3D** | 20 stage, 3 mode kesulitan, 4 robot menara dengan animasi tembak |
| 🦠 **Musuh Virus** | 4 tipe virus 3D — termasuk *attacker* yang balik menyerang menaramu |
| 🧠 **Kuis Edukasi** | Matematika, Coding, Logika & Umum — benar dapat bonus, salah kena potong |
| 🎣 **Mode Mancing 3D** | Kolam besar, 12 spesies ikan RNG, mini-game timing, 5 tier pancingan |
| 🌌 **Langit Hidup** | Bintang berkelip, bintang jatuh, planet yang bisa diklik, black hole, tata surya |
| 🎵 **Musik Chiptune** | Musik latar prosedural WebAudio — mode menu, battle, dan mancing yang berbeda |
| 📱 **Mobile Friendly** | Fullscreen, joystick virtual, tombol aksi ala game mobile |
| 💾 **Kode Backup** | Pindahkan seluruh progres ke HP / laptop lain dengan satu kode |

---

## 🗼 Tower Defense

Bangun robot penjaga di 12 *pad* yang tersedia di setiap stage. Setiap stage punya **layout jalur yang berbeda** — dari Jalur Klasik sampai Benteng Terakhir. Virus berjalan dari portal spawn menuju server; kalau server kebobolan, nyawa berkurang.

### 🤖 Menara

| Menara | Harga | Damage | Jangkauan | Kecepatan | Peran |
|---|---|---|---|---|---|
| 🟡 **Blaster** | 🪙 50 | 12 | 115 | 2,0/detik | Serangan cepat, andalan di awal |
| 🔵 **Sniper** | 🪙 100 | 40 | 210 | 0,7/detik | Jarak sangat jauh, damage besar |
| ❄️ **Frost** | 🪙 75 | 4 | 105 | 1,5/detik | Memperlambat virus **45%** |
| 💚 **Healer** | 🪙 80 | +18 HP | 200 | tiap 2 detik | Memulihkan HP menara di sekitarnya |

> Semua menara bisa di-*upgrade* sampai **Lv 3** (HP menara naik tiap level), dijual kembali 70%, dan bisa ditempatkan dengan **klik atau drag & drop**.

### 🦠 Musuh

| Virus | HP | Kecepatan | Reward | Ciri khas |
|---|---|---|---|---|
| 🔴 **Normal** | 30 | 48 | 🪙 8 | Virus standar |
| 🟠 **Fast** | 18 | 84 | 🪙 10 | Kecil dan sangat cepat |
| 🟣 **Tank** | 130 | 28 | 🪙 25 | Besar, HP tebal, makan **2 nyawa** |
| 🟧 **Attacker** | 70 | 42 | 🪙 15 | Berhenti dan **menyerang menaramu** (mulai wave 4) |

### 🎚️ Mode & Stage

| Mode | Nyawa | Koin Awal | HP Virus | Kecepatan Virus |
|---|---|---|---|---|
| 😌 **Santai** | 15 | 🪙 200 | ×0,85 | ×1,0 |
| ⚔️ **Normal** | 10 | 🪙 150 | ×1,0 | ×1,0 |
| 💀 **Sulit** | 6 | 🪙 120 | ×1,3 | ×1,1 |

- **20 stage** dengan layout jalur berbeda — progres terbuka satu per satu, skor terbaik tersimpan per stage.
- **Refund + bonus:** saat pindah stage, semua koin yang terpakai dikembalikan 100% **plus bonus kemenangan** (100 + 10 × stage yang diselesaikan). Tidak ada uang yang terbuang.
- **Kuis tiap clear stage:** jawab soal Matematika / Coding / Logika / Umum untuk bonus koin. Kalah? Kuis *retry* menentukan nasibmu — **salah 3× dan kamu mengulang dari Stage 1**.

### 🎮 Kontrol (Tower Defense)

| Aksi | PC | Mobile |
|---|---|---|
| Pilih menara | Klik kartu / tombol `1`–`4` | Tap kartu |
| Bangun menara | Klik pad / drag kartu ke pad | Tap pad / drag kartu |
| Mulai wave | `Spasi` / tombol ▶ | Tombol ▶ |
| Putar kamera | Drag kiri | Drag 1 jari |
| Geser kamera | Mode ✋ Geser / drag kanan | Mode ✋ Geser |
| Zoom | Scroll | Cubit |

---

## 🎣 Mode Mancing 3D

Capek jaga server? Masuk ke **🎣 Mancing** dari menu utama. Kolam besar, 4 dermaga, dan 12 spesies ikan menunggu — dari Ikan Mas sampai **Ikan Paus Legendaris 800 cm**.

### 🐟 Ikan

| Ikan | Rarity | Ukuran | Nilai Jual |
|---|---|---|---|
| 🐟 Ikan Mas · 🐡 Ikan Lele · 🐠 Ikan Nila · 🐡 Mas Koki | Biasa | 3–60 cm | dari 🪙 10 |
| 🐟 Ikan Gurame · 🐠 Ikan Koi · 🐟 Ikan Patin · 🐠 Ikan Cupang | Jarang | 3–70 cm | dari 🪙 25 |
| 🐉 Ikan Arwana | Langka | 30–80 cm | dari 🪙 60 |
| 🦈 Ikan Hiu · 🐙 Ikan Pari | Epik | 80–250 cm | dari 🪙 150 |
| 🐋 **Ikan Paus** | **Legendaris** | **300–800 cm** | dari 🪙 400 |

- **Varian mutasi:** setiap ikan bisa muncul sebagai **RAKSASA** (×1,8 ukuran, ×3 harga) atau **Mini** (×0,5 ukuran).
- **Mini-game timing:** saat STRIKE, pasang jarum yang menyapu di zona hijau — makin langka ikannya, makin sempit zonanya dan makin banyak putarannya.
- **Ikan dipegang di atas kepala** setelah dapat, bisa dipamerkan dari koleksi. 🎣

### 🎣 Pancingan

| Pancingan | Harga | Luck | Mutasi | Desain 3D |
|---|---|---|---|---|
| 🎋 Bambu | Gratis | +0% | +0% | Kayu tan polos |
| 🪵 Jati | 🪙 150 | +10% | +2% | Kayu coklat tua, cincin emas |
| 🎣 Fiber | 🪙 400 | +25% | +5% | Karbon gelap, cincin cyan menyala |
| ⚙️ Titanium | 🪙 1.000 | +45% | +10% | Perak metalik, aksen biru menyala |
| 👑 Legenda Samudra | 🪙 2.500 | +80% | +20% | Batang emas + bola samudra menyala |

> Setiap pancingan punya **desain 3D yang berbeda** di tangan robot — bukan sekadar statistik.

### 📍 Spot Mancing

| Spot | Bonus Luck |
|---|---|
| Dermaga Utama (selatan) | +0% |
| Batu Karang (timur) | +10% |
| Teratai Sunyi (barat) | +15% |
| Air Dalam (utara) | +25% |

Jalani karaktermu (WASD / joystick) ke spot yang kamu mau — kamera selalu terkunci mengikuti karakter. Luck spot **ditambah** luck pancingan untuk peluang ikan langka.

### 💰 Ekonomi Mancing

- **Jual satuan** dari kartu koleksi atau langsung dari modal hasil tangkapan.
- **💰 Jual Semua** — jual semua ikan non-favorit sekaligus (dengan konfirmasi 2 langkah).
- **⭐ Favorit** — tandai ikan kesayanganmu, dijamin tidak ikut terjual.
- **🐠 Aquarium 3D** — pajang sampai 5 ikan di aquarium kaca di tepi kolam, ikanmu berenang melingkar di dalamnya.

---

## 🌌 Dunia 3D

- **Langit malam yang hidup:** 210 bintang berkelip, bintang jatuh berkala, 3 nebula lembut.
- **Planet yang bisa diklik:** Planet Jingga, Planet Cincin, dan Bulan Kelabu mengorbit arena — klik untuk ledakan partikel dan **bonus +5 koin** (cooldown 20 detik per planet).
- **Black hole** di cakrawala selatan dengan cakram akresi berputar dan partikel yang tersedot masuk — bisa diklik juga.
- **Tata surya mini** di latar menu utama, dengan kamera sinematik yang terbang saat membuka menu.
- **Portal spawn ungu** berdenyut, jalur bercahaya cyan, dan beam cahaya + cincin hologram di atas server.

---

## 🚀 Cara Main

**Tidak perlu install apa pun.**

1. Download atau clone repo ini:
   ```bash
   git clone https://github.com/Kryuuu/codero-defend.git
   ```
2. Buka `index.html` di browser (Chrome / Edge / Firefox / Safari).
3. Main! 🎮

> ⚠️ Game ini memuat **Three.js r160 dari CDN** (jsDelivr), jadi butuh koneksi internet saat bermain. Selain itu gamenya berjalan 100% lokal di browsermu — tanpa server, tanpa akun.

**Tips:** aktifkan GitHub Pages di repo ini (Settings → Pages → Branch `main`) supaya gamenya bisa dimainkan langsung dari `https://kryuuu.github.io/codero-defend/`.

---

## 💾 Kode Backup — Pindah Device

Progres tersimpan otomatis di `localStorage` browser — **per device**, tanpa sinkronisasi server. Untuk memindahkan progres ke HP / laptop lain:

1. Di perangkat lama: buka **⚙️ Pengaturan** → **💾 Kode Backup** → **📤 Buat & Salin Kode**.
2. Kirim kodenya (format `JS3D-...`) ke perangkat lain.
3. Di perangkat baru: buka **⚙️ Pengaturan** → tempel kode di kolom yang sama → **📥 Pulihkan dari Kode**.
4. Game memuat ulang — stage, skor, koleksi ikan, koin, pancingan, dan pengaturanmu sudah pindah. ✅

> Kode backup berisi seluruh data simpananmu. Jangan dibagikan ke orang yang tidak kamu percaya.

### 🗄️ Struktur Save (`localStorage`)

| Key | Isi |
|---|---|
| `codero3d` | Stage terbuka, skor terbaik per stage, mode kesulitan |
| `codero3d-settings` | Musik, efek suara, kualitas grafis, mode kamera |
| `codero3d-fish` | Koleksi ikan, koin mancing, pancingan, aquarium, favorit |

---

## 🖼️ Screenshot

<!-- Taruh screenshot gameplay di sini, misalnya:
<p align="center">
  <img src="docs/gameplay-tower.jpg" width="45%" alt="Tower Defense">
  <img src="docs/gameplay-fishing.jpg" width="45%" alt="Mode Mancing">
</p>
-->

_Screenshot menyusul — gamenya sendiri sudah bisa langsung dimainkan._

---

## 🛠️ Teknologi

- **Three.js r160** — rendering 3D (via CDN jsDelivr)
- **WebAudio API** — musik chiptune prosedural + efek suara, tanpa file audio
- **Vanilla JS + CSS** — tanpa framework, tanpa build step
- **localStorage** — penyimpanan progres lokal

Seluruh game — logika, grafis, musik, dan UI — ada dalam **satu file HTML** (~270 KB).

---

## 🏆 Kredit

**Dibuat oleh [Nvy](https://nvy.my.id)** — dibantu **Elaina** 🤖

Dibangun dengan Three.js · © 2026 Nvy

---

## 📄 Lisensi

Proyek ini dirilis di bawah lisensi **MIT** — bebas digunakan, dimodifikasi, dan dibagikan, dengan tetap mencantumkan kredit pembuatnya.
