# DjangoTutor


- Menginstall Django via CMD

ketikan kode seperti ini di cmd kalian untuk menginsall django versi 2.2.12

![django1](https://user-images.githubusercontent.com/92988781/167986984-f9f90fa5-101d-4843-9f7d-d89c53898b8a.png)


- Membuat Project

kode dibawah berguna untuk membuat project atau folder yang nantinya digunakan untuk membuat aplikasi web menggunakan django

![django2](https://user-images.githubusercontent.com/92988781/167987519-b2a0690f-8458-4544-83fc-aeb7f1fcc579.png)

maka akan otomatis muncul folder myperpus seperti dibawah 

![django3](https://user-images.githubusercontent.com/92988781/167987813-1ca93fa3-7be6-4177-8568-9818e07c77a0.png)

![django4](https://user-images.githubusercontent.com/92988781/167987843-2f13e1a4-9028-4058-86c7-4f5c821c3cd9.png)

ketik perintah 'python manage.py runserver' untuk menjalankan host server untuk memulai dan mengambil alamat project

![django5](https://user-images.githubusercontent.com/92988781/167988411-53e80e4b-069f-4f5d-af41-eb4955000d8d.png)

- Basic Routing

alur basic routing yaitu, client melakukan request lalu di cek oleh URLconf kemudian dikirim ke view untuk menampilkan lalu si view mengembalikkan respon kepada client tersebut

![django6](https://user-images.githubusercontent.com/92988781/168028122-7de83c54-afb1-42f1-9c30-bbdee405e12a.png)

contoh tampilan

![django7](https://user-images.githubusercontent.com/92988781/168028625-bfcdc9f9-a86d-4eae-98ef-3b58c735e255.png)


- Membuat APPS

APPS adalah aplikasi pada django yang mempunyai model database, view template, dan URLconf

membuat APPS

![django8](https://user-images.githubusercontent.com/92988781/168030223-d6d8c03e-1052-4658-a199-f82ad33c8ec6.png)

isi dari folder apps yang sudah dibuat tadi

![django9](https://user-images.githubusercontent.com/92988781/168030998-7e956f10-24e0-4aaa-83a3-072df03a5a05.png)


- Membuat Views

Membuat views di folder myperpustakaan

![django10](https://user-images.githubusercontent.com/92988781/168084186-abe213b3-3199-4036-a5e7-92d3bd873120.png)

lalu di panggil di myperpus urls

![django11](https://user-images.githubusercontent.com/92988781/168084548-37c03294-a849-4c5f-ba5d-f5a8b2f8787d.png)

program terlihat lebih simpel.

membuat views baru yang bernama penerbit

![django12](https://user-images.githubusercontent.com/92988781/168086558-77da2b6c-1374-4846-a44b-e2f00e84dd4d.png)

![django13](https://user-images.githubusercontent.com/92988781/168086602-a1175a77-cd74-43f4-b48f-1bbc8cb4433e.png)

views

![django14](https://user-images.githubusercontent.com/92988781/168086671-4ae9f5ab-1d4e-4bed-bc1b-9740fd443c2a.png)

- TEMPLATES

Menggunakan templates lebih memanjakan mata dan membuat codingan lebih rapi dan memudahkan programmer membuat banyak file html.

membuat file html di folder templates (baru buat).

![django15](https://user-images.githubusercontent.com/92988781/168091044-e93a0f3e-485d-438b-ad26-81c94a25c845.png)

mengatur program di views

![django16](https://user-images.githubusercontent.com/92988781/168091174-53c8943e-9ae6-4503-a7a6-ca36cde74a46.png)

tampilan

![django17](https://user-images.githubusercontent.com/92988781/168091270-7dc02519-f359-480c-b70a-41cac45f359e.png)

- TEMPLATE LANGUAGE

SUBSTITUTE VARIABLE untuk menampilkan variabel yang dilempar ke views 

FILTER untuk memodifikasi variabel yang akan ditamplkan

TAGS untuk melakukan kontrol flow seperti looping, include, kondisi, dll untuk mengambil file eksternal

VIEWS

![django18](https://user-images.githubusercontent.com/92988781/168224612-91c603f5-c83f-4db2-957c-fa356ecb8ac8.png)

TEMPLATE

![django19](https://user-images.githubusercontent.com/92988781/168224685-c142ea98-ffcf-4c77-bd80-874e8a11a7f9.png)

TAMPILAN

![django20](https://user-images.githubusercontent.com/92988781/168224755-15f5a1b0-38b5-43b0-bcc3-422a8061b76d.png)

- TEMPLATE EXTANDING

 Atau memperluas template.
 
 KONSEP EXTANDING
 
 ![django21](https://user-images.githubusercontent.com/92988781/168230194-d34f1127-c224-4779-b5ae-fa5fe6d63599.png)

![django22](https://user-images.githubusercontent.com/92988781/168230447-28415eae-05c9-446c-b56c-3310a852f658.png)

![django23](https://user-images.githubusercontent.com/92988781/168230487-a18c767e-1a97-4b91-815c-321a5a799753.png)

![django24](https://user-images.githubusercontent.com/92988781/168230599-68080c3f-8ca3-4caa-be2a-6fdcb798c5cb.png)

![django25](https://user-images.githubusercontent.com/92988781/168230637-fdebbf34-7459-4106-85d6-74e8399a2adf.png)


jadi kita hanya menuliskan content langsung pada file buku, penerbit tidak perlu lagi menuliskan html yang begitu panjang


- STATIC FILES

Static files adalah kumpulan file css, js, dan image, yang berfungsi untuk mempercantik aplikasi yang akan dibuat menggunakan django

berikut settingan untuk static files agar dapat diakses

![django26](https://user-images.githubusercontent.com/92988781/168477111-4e3fa43b-e7ad-4427-b1ff-c52a7f0d78bf.png)

kemudian buat file css untuk mengubah background misalnya

![django27](https://user-images.githubusercontent.com/92988781/168477154-b1a8e324-30ab-42f3-95a7-8365bc5dc88c.png)

terus di panggil file css yang tadi di base.html

![django28](https://user-images.githubusercontent.com/92988781/168477176-bc8e888d-e7f9-4e9d-9ffb-42befb98ca33.png)

dan tampilan warna backgroundnya akan berubah

![django29](https://user-images.githubusercontent.com/92988781/168477227-db7d97b2-df8e-4061-8675-ec2324c78784.png)


- SETUP DATABASE

setting database

![django31](https://user-images.githubusercontent.com/92988781/168980219-db49565b-41f2-4a2a-9e40-38da324cf122.png)

melakukan inisiasi

![django30](https://user-images.githubusercontent.com/92988781/168979737-3cc61c2c-ef57-4d8e-9241-b470cc8e0c62.png)

nah ini artinya kita sudah melakukan inisiasi membuat tabel tabel kedalam database db.sqlite3 dan seterusnya kita sudah bisa mengisi data data ke dalam database dan juga kita sudah bisa membuat models.


- Models

models merupakan definitif dari database atau representasintabel pada database

contoh membuat tabel models di django

![django32](https://user-images.githubusercontent.com/92988781/168982528-70402c10-e713-4f82-a4f4-30735391be11.png)


proses migrate agar menjadi tabel didatabase 

![django33](https://user-images.githubusercontent.com/92988781/168982593-a9af64ef-b665-425c-a78e-67b45dab3d8d.png)

ini dia tabel yang telah dibuat tadi, buka menggunakan db browser

![django34](https://user-images.githubusercontent.com/92988781/168984720-2990915d-e3da-421d-b728-5e9b0920806b.png)

otomatis field id ditambahkan. saat kita membuat model kita tidak perlu membuat field id dengan primery key karena django yang buatkan.


- MODELS: FOREIGN KEY

foreign key ini berfungsi untuk membuat relasi antar tabel dalam database relasional

membuat foreign key

![django35](https://user-images.githubusercontent.com/92988781/169061228-b3675f34-3b10-47a3-8dd6-ed7d12c8e59d.png)

langsung kita migrasi

![django36](https://user-images.githubusercontent.com/92988781/169061349-83f8818a-d934-450b-a6ef-1684fe408729.png)


- DJANGO ADMIN

django admin ini berfungsi untuk memudahkan kita untuk melakukan proses CRUD sederhana untuk mengelola data pada model yang kita buat.

membuat admin account untuk login ke admin (buatnya di cmd dan ketikkan perintah dibawah

![django37](https://user-images.githubusercontent.com/92988781/169066615-49fcd8c6-89be-49ab-8429-c0228acace54.png)


tampilan awal ketika sudah login

![django38](https://user-images.githubusercontent.com/92988781/169066862-7e9156b2-71c1-41ae-bc82-6155f4194825.png)


kemudian kita menampilkan models yang kita buat tadi dengan cara memanggil file model ke admin

![django39](https://user-images.githubusercontent.com/92988781/169072548-d1d7ca44-0e20-4cf5-8aa6-ec08343897f0.png)


model model yang kita buat akan tampil di django admin

![django40](https://user-images.githubusercontent.com/92988781/169072970-4832a74d-b46c-4307-9e6f-d189e36ecfc6.png)


jika kita mengklik add maka kita diarahkan ke halaman yang dimana berisi form untuk menambahkan data yang sangat berguna dan memudahkan kita melakukan proses CRUD

![django41](https://user-images.githubusercontent.com/92988781/169074759-39704fa2-e011-44ac-86a5-10729452d088.png)


![django42](https://user-images.githubusercontent.com/92988781/169079203-e7fb80ae-cd79-48a5-aa0d-c6dc607a27ff.png)

datanya langsung ditampilkan ke dalam database

![django43](https://user-images.githubusercontent.com/92988781/169079492-88a7f720-10f4-473a-b62f-8f7cfe1c5907.png)

otomatis di model kelompok ditambahkan yang sudah dibuat dibagian kelompok_id

![django44](https://user-images.githubusercontent.com/92988781/169080323-46514cee-a21c-4c94-ad13-6d74aa069327.png)


- MODEL ADMIN

pada tahap ini kita akan melakukan costum sederhan misalnya menampilkan judul buku, pengarang, penerbit, dan lain lain. kita kan menampilkannya dibawah

![django46](https://user-images.githubusercontent.com/92988781/169095203-243e4e07-a25a-42fe-973d-507d0161b2a1.png)

program adminnya seperti berikut


![django45](https://user-images.githubusercontent.com/92988781/169095151-4ea281a9-3e02-44f7-9785-af6bd7a6b1cc.png)


- ORM (OBJECT-RELATIONAL MAPPING)

teknik yang digunakan dalam program untuk menggunakan basis data relasional sebagai data dengan bentuk objek.

kenapa django menyediakan ORM? karena kode python yang ditulis tidak campur aduk dengan kode sql

ORM ini betugas sebagai penghubung aplikasi yang dibuat menggunakan database relasional.


