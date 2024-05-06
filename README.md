**2.1. Original code of broadcast chat.**  
![server](image.png)
![client](image-1.png)
Setelah menjalankan server menggunakan perintah `cargo run --bin server`, serta setiap klien menggunakan perintah `cargo run --bin client`, dari hasil keluaran di atas terlihat bahwa semua klien dan server menerima pesan obrolan dari setiap klien yang terhubung. Ketika seorang klien mengetikkan pesan di baris perintah, teks tersebut akan dikirim ke server dan kemudian diteruskan ke semua klien yang sedang terhubung.