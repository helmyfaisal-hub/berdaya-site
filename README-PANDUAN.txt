BERDAYA.SITE — HOMEPAGE V1
==========================
Website statis (HTML/CSS/JavaScript), tanpa database, tanpa build, tanpa API key.

CARA UPLOAD HOSTINGER
1. Login https://hpanel.hostinger.com/.
2. Buka Websites -> Dashboard/Kelola di domain berdaya.site.
3. Buka Files -> File Manager -> Access files of berdaya.site.
4. Pastikan folder yang terbuka adalah public_html untuk domain utama.
5. Backup dahulu file website lama bila sudah ada.
6. Upload berdaya-site.zip lalu klik Extract / Ekstrak.
7. PENTING: index.html, style.css, app.js, quotes.js, projects.js, favicon.svg harus berada LANGSUNG di public_html. BUKAN di public_html/berdaya-site/.
8. Kunjungi https://berdaya.site, refresh dengan Ctrl+F5.
9. Bila domain belum terbuka, cek nameserver/domain pointing dan SSL di dashboard Hostinger.

CARA EDIT
- Quotes: buka quotes.js, tambah atau perbaiki teks dan rujukan.
- Subdomain: buka projects.js, ubah URL dan set active:true setelah website subdomain tersedia.
- Warna/tampilan: edit style.css; konten dan kerangka: index.html.
- Durasi rotasi: ubah const INTERVAL=30000 pada awal app.js (dalam milidetik).
- Periksa ejaan, terjemahan, referensi ayat dan hadis untuk setiap konten baru.

CATATAN
- Pustaka awal bersifat lokal/kurasi, bukan feed acak dari internet.
- Quotes diacak antarkonten dengan menghindari pengulangan langsung.
- Contoh subdomain di projects.js sengaja NONAKTIF agar tidak mengantar pengguna ke 404.
- Memasang berkas ini pada situs yang sudah menggunakan WordPress atau Hostinger Website Builder bisa menimpa homepage. Backup dan pastikan memilih website bertipe empty/custom HTML.
- Tampilan menggunakan Google Fonts; apabila jaringan memblokir font maka ada fallback Georgia/sans-serif.
