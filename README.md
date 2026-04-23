## Daftar 17 Halaman Interaktif
 
### Publik (4 halaman)
1. **Landing Page** — hero stats live, 3 program unggulan, CTA transparansi & registrasi
2. **Transparansi Publik** — peta stilistik dengan 5 pin klikable, top 5 kecamatan, distribusi kategori
3. **Login & Portal** — role selector Admin/Perusahaan, form auto-fill untuk demo
4. **Registrasi Perusahaan** — wizard 3-step (Data PT → PIC & Kontak → Upload Dokumen)
### Baperida Admin (8 halaman)
5. **Dashboard Baperida** — 4 stat card, bar chart 12 bulan animate, activity feed, 4 quick-action card
6. **Manajemen Perusahaan** — tabel data 8 perusahaan dengan filter live, search, pagination, export
7. **Katalog Program** — 8 program dengan filter kategori, search, 4 opsi sort
8. **Forum Matchmaking** — 4 tab (Sesi Aktif/Menunggu/Selesai/Arsip), live session panel dengan peserta commit
9. **MoU & PKS** — status summary (Aktif/Menunggu/Expired/Draft), document list dengan chip type & status
10. **Monitoring Program** — timeline milestone vertikal, progres 60%, gallery bukti 4 sekolah
11. **Laporan & Analytics** — KPI cards, donut chart kategori, line chart SVG tren bulanan, insight otomatis
12. **CSR Award** — podium top 3, leaderboard lengkap 8 perusahaan
### Perusahaan (3 halaman)
13. **Dashboard Perusahaan** — Gold Award badge, 4 stat card, komitmen aktif dengan progress bar
14. **Katalog Perusahaan (AI-Rec)** — banner rekomendasi AI, match score 95%/88%/82%, sort Rekomendasi
15. **Detail Program + Letter of Intent** — hero program, deskripsi, matchmaking status, wizard LoI 4-step
### Account (2 halaman)
16. **Notifikasi & Inbox** — 4 tab (Semua/Belum/Matchmaking/Sistem), 6 notifikasi dengan icon berwarna
17. **Pengaturan Profil** — sidebar 7 menu setting, profile card, form info personal + Keamanan
## Fitur Interaktif yang Bekerja
 
### Navigasi Terkoneksi
- Klik logo **SICSR BL** → Landing
- Tombol **Masuk** → Login → (setelah login) Dashboard sesuai role
- **Sidebar Admin** → 10 menu item, semua klikable ke halaman nyata
- **Bell icon 🔔** di topbar → Notifikasi
- **Avatar dropdown** → Profil & Pengaturan
- **Breadcrumb** di Detail Program → kembali ke Katalog
- Link **"Daftar Perusahaan"** di Login & Landing footer → Registrasi
### Form & Input Live
- **Login**: email & password auto-fill saat switch role
- **Katalog Program**: search bar live filter, 6 filter chip kategori, 4 opsi sort
- **Katalog PT (AI)**: sort by Rekomendasi (by match score), Rp tertinggi, dll
- **Manajemen Perusahaan**: filter by status/jenis, search by nama
- **MoU & PKS**: filter by tipe dokumen
- **Notifikasi**: filter by kategori (Semua/Belum/Matchmaking/Sistem)
- **Registrasi Perusahaan**: 3-step wizard dengan state persist antar step
- **Letter of Intent**: 4-step wizard, multi-select checkbox kontribusi, review final, submit dengan toast success
### Interaktivitas Visual
- **Bar chart dashboard**: staggered animation delay per bar
- **Line chart SVG**: di Laporan dengan polyline + dots
- **Progress bars**: smooth width transition
- **Card hover**: lift effect shadow
- **Peta transparansi**: klik pin → tooltip info muncul, ring effect active pin
- **Modal LoI**: backdrop blur, scale-in animation
- **Stat cards**: slide-up staggered animation saat load
- **Podium CSR Award**: varying heights berdasarkan rank
- **Toast notifications**: slide-up dari kanan bawah saat action
## Demo Navigator (Tombol ⚙ Pojok Kiri Bawah)
 
Panel floating yang mengelompokkan 17 halaman ke 4 kategori:
- **PUBLIK** (4 halaman)
- **BAPERIDA** (8 halaman)
- **PERUSAHAAN** (3 halaman)
- **ACCOUNT** (2 halaman)
Plus switch persona Admin ↔ Perusahaan tanpa logout. Sangat berguna untuk demo agar tidak harus navigate step-by-step saat presenter ingin "jump" ke halaman tertentu.
 
## Skenario Demo untuk Rapat OPD
 
### Skenario A: Perspektif Publik (3 menit)
1. Buka `prototype.mhabibalgifari.site`
2. Landing — hero live stats, 3 program unggulan
3. Klik **Jelajahi Peta** → Transparansi Publik
4. Klik pin kecamatan → tooltip info muncul
5. Scroll ke bawah → Distribusi kategori donut
**Pesan utama:** "Warga Bandar Lampung bisa monitor realisasi CSR perusahaan di kecamatannya secara real-time"
 
### Skenario B: Perspektif Baperida Admin (8 menit — tour lengkap)
1. Landing → Masuk → pilih **Admin/OPD** → Dashboard Baperida
2. Dashboard — tunjukkan stat card animasi, bar chart 12 bulan, activity feed live
3. Sidebar klik **Perusahaan** → tabel 8 perusahaan, demo filter "Verifikasi", search "PLN"
4. Sidebar klik **Katalog Program** → demo filter "Pendidikan", sort "Anggaran tertinggi"
5. Klik card program → **Detail + Matchmaking status** → klik **Buat LoI** → demo wizard 4 step → Submit
6. Sidebar klik **Matchmaking** → tunjukkan live session dengan 3 peserta commit
7. Sidebar klik **MoU & PKS** → status cards + document list
8. Sidebar klik **Laporan** → KPI, donut chart, line chart SVG, insight otomatis
9. Sidebar klik **CSR Award** → podium top 3
**Pesan utama:** "Baperida punya kontrol end-to-end atas seluruh siklus CSR kota — entry, match, approve, monitor, report, apresiasi"
 
### Skenario C: Perspektif Perusahaan (4 menit)
1. Klik ⚙ pojok kiri → switch persona **Perusahaan**
2. Klik Dashboard PT → Gold Award badge, komitmen aktif
3. Klik **Katalog** → banner AI rekomendasi dengan match score per program
4. Klik card 95% match → Detail → Submit LoI
**Pesan utama:** "Perusahaan dapat dashboard personal, CSR Award untuk reputational benefit, dan AI rekomendasi program yang match dengan fokus CSR mereka"
 
### Skenario D: Tour Quick via Demo Navigator (5 menit)
Untuk audiens yang ingin lihat semua dalam waktu terbatas:
1. Klik ⚙ → buka Demo Navigator
2. Jump cepat: Landing → Dashboard → Matchmaking → MoU → Laporan → Award → Katalog PT → Detail + LoI
3. Setiap halaman cukup 30 detik deskripsi singkat
## Tips Teknis
 
- **Tampilan mobile:** F12 → toggle device toolbar (Ctrl+Shift+M di Chrome), pilih iPhone/Galaxy
- **Fullscreen presentation:** F11
- **Backup offline:** simpan file di USB flash, buka langsung tanpa internet (saat pertama load butuh internet untuk CDN, setelah itu bisa offline sampai di-refresh)
- **QR Code untuk OPD:** generate dari qr-code-generator.com, tempel di ruang rapat agar OPD bisa buka di HP mereka
## Keterbatasan yang Perlu Pak Sampaikan
 
1. **Data dummy** — semua angka mockup. Real data akan datang dari SIPD/Sakti/registrasi perusahaan
2. **Tidak ada persistent state** — refresh akan reset form input dan filter
3. **Beberapa form submit** pakai toast placeholder (bukan database asli)
4. **AI rekomendasi** di Katalog PT — nilai match score hardcoded, belum dihitung AI nyata (bisa di-aktifkan dengan integrasi Claude API di iterasi berikutnya)
