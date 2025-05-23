![gurt:yo](image.png)

Pada eksperimen ini, saya menjalankan satu server dan tiga client untuk chat berbasis WebSocket. Server dijalankan di port 2000, dan masing-masing client berhasil terhubung dan mengirimkan pesan. Ketika satu client mengirim pesan, pesan tersebut berhasil dikirim ke seluruh client lainnya, menandakan bahwa broadcast berjalan dengan baik.

![kevin:sybau](image2.png)

Pada eksperimen kali ini, kita menjalankan server pada port yang berbeda dari sebelumnya(```TcpListener::bind``` untuk server dan ```ClientBuilder::from_uri``` untuk client), setelah port diubah, program masih dapat berjalan lancar dan komunikasi antara client dan server masih tetap real-time. 