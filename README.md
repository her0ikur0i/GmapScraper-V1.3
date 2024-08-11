# GmapScraper-V1.3

Penjelasan Optimasi:
Mengurangi Jumlah Data: Jumlah data maksimum per query dikurangi dari 200 menjadi 100 untuk mengurangi beban memori.
Scroll Optimasi: Proses scrolling telah dioptimasi dengan penyesuaian jumlah data yang di-scroll setiap kali dan interval waktu antar scroll.
Random Delays: Menambahkan delay acak antar query untuk mengurangi kemungkinan terdeteksi sebagai bot oleh Google.
Keamanan dan Monitoring: Kode dioptimalkan untuk mengelola memori dengan lebih baik, termasuk membersihkan objek yang tidak lagi digunakan dan menangani file secara efisien.
Dengan optimasi ini, seharusnya dapat mengurangi kemungkinan browser crash dan mengelola penggunaan memori dengan lebih baik tanpa meningkatkan RAM fisik.
