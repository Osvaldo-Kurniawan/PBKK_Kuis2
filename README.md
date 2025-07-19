# Aplikasi pendataan surat menyurat

Aplikasi ini dirancang untuk memudahkan pengguna dalam melakukan manajemen dan pendataan surat-menyurat. Menggunakan framework CodeIgniter, aplikasi ini memiliki fungsi dasar CRUD (Create, Read, Update, Delete) untuk memanipulasi data persuratan. Berikut adalah deskripsi fitur-fitur utama beserta fitur pendukung:

Fitur Utama:

- Pendataan Surat Masuk dan Keluar

  Untuk memenuhi kebutuhan pendataan, aplikasi ini menyediakan menu "Inbox" dan "Sent" mirip dengan fitur pada aplikasi email umumnya. Pada menu "Inbox," akan ditampilkan semua surat yang ditujukan kepada departemen pemilik akun, sementara menu "Sent" berisi surat yang telah dikirimkan oleh departemen pemilik akun terkait. Surat akan ditampilkan dalam bentuk daftar yang dapat diklik untuk melihat versi PDF terkait.

- Upload File Pengiriman ke Bagian yang Bertanggung Jawab

  Dalam pengiriman surat, pengguna diharuskan mengisi formulir yang mencakup beberapa detail surat seperti subjek (judul), penerima, dan mengunggah file surat dalam format PDF. Surat hanya akan diterima oleh pengguna yang terkait dengan departemen yang sesuai.

- Pemberian Nomor Surat

  Pemberian nomor surat akan dilakukan secara otomatis dalam basis data di phpMyAdmin. Setiap surat baru akan diberikan ID yang unik.

- Pencatatan dan Pengarsipan Surat Keluar

  Setiap surat yang dikirim dapat di-reply, sehingga pada "Inbox," akan muncul keterangan "Reply from" yang mencantumkan ID surat yang di-reply bersama dengan isi surat balasan.

- Pencarian Surat Masuk dan Surat Keluar

  Fitur pencarian memungkinkan pengguna untuk mencari surat berdasarkan kriteria tertentu.

Fitur tambahan :

- Login/logout

  Karena sistem memiliki departemen dan kriteria masing masing dan pengiriman surat memerlukan yang dituju secara spesifik maka akun harus dibuat untuk mengantisipasi kesalahan pengiriman surat.


Demo dan penjelasan : 

https://www.youtube.com/watch?v=zXkXtyRwMo4

Dokumentasi :

<img width="1019" height="525" alt="image" src="https://github.com/user-attachments/assets/bc4bc7cf-0815-457a-a0a9-0c9a8a40021a" />

<img width="1018" height="527" alt="image" src="https://github.com/user-attachments/assets/f8861045-080a-45a8-8b2b-9fee7cc72b25" />

<img width="1018" height="522" alt="image" src="https://github.com/user-attachments/assets/f54402e6-be91-4b12-bfd4-3d561e77abeb" />

<img width="1006" height="525" alt="image" src="https://github.com/user-attachments/assets/d528051b-dedc-4880-b857-34b0fc42f178" />
