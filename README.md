![alt text](https://f.top4top.io/p_3555iayar1.png?raw=true)

🧠 Apa itu CMS Checker?

Tujuannya adalah mengecek apakah website menggunakan CMS seperti WordPress, Joomla, Drupal, dll. Ini sangat berguna untuk orang yang ingin mengklasifikasi atau menganalisis website, seperti untuk SEO, pentest, atau scraping.

💻 RDP/VPS Cocok?
✅ Iya! Sangat cocok.
Jika kamu menjalankan ini di RDP/VPS:
1. Kecepatan download halaman lebih cepat 🌐
2. Bisa jalanin dengan thread tinggi (misal 50-100+) 🚀
3. Tidak terganggu koneksi internet lokalmu ⚡

💡 Apakah Ini "Fast Thread"?
✅ Ya, ini menggunakan fast threading via ThreadPoolExecutor.
Tapi kecepatan bergantung pada:
1. Koneksi jaringan 💻
2. Jumlah thread yang dipilih 🔁
3. Respons server target 🌐
4. Spesifikasi RDP/VPS kamu 🖥️

🤖 Kenapa Pakai Threading itu Cepat?

Bayangkan kamu punya 1000 website yang mau dicek :
1. Kalau tanpa threading: ➡️ 1 URL per 5 detik = 5000 detik (~1.5 jam) 😴
2. Kalau pakai 50 thread: ➡️ 50 URL dalam 5 detik = 1000 URL hanya dalam ±100 detik (1-2 menit) 🚀🔥

📌 Tips

1. Gunakan thread 10-100 tergantung kekuatan RDP/VPS kamu.
2. Jangan terlalu tinggi (misal >200) karena bisa membuat rate limit atau ban IP.

🧹 Filter Duplikat di Tools Ini

Di dalam kode tools ini, ada fungsi khusus buat menghapus URL yang sama supaya URL yang diproses cuma satu kali saja

Kesimpulan Filter Duplikat di Tools ini :
1. Membuat proses scanning CMS lebih cepat dan efisien
2. Menghindari pengecekan website yang sama berkali-kali
3. Membuat hasil output dan log jadi bersih dan rapi
4. Menggunakan metode sederhana dan efektif dengan dict.fromkeys + lowercase
   
🎁 Kesimpulan

🛠️ Script ini adalah alat CMS detector cepat berbasis threading, cocok untuk:
1. 🎯 Analis website
2. 🛡️ Pentester
3. 🔍 Scraper
4. 📈 SEO specialist

✅ Cocok dijalankan di:
1. 🖥️ PC lokal (dengan koneksi bagus)
2. ☁️ VPS / RDP (lebih cepat & stabil)
3. 📈 Pakai ThreadPoolExecutor untuk mempercepat proses secara asinkron/paralel
