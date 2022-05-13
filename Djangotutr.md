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

TAGS untuk melakukan kontrol flow seperti looping, include, kondisi, dll

VIEWS

![django18](https://user-images.githubusercontent.com/92988781/168224612-91c603f5-c83f-4db2-957c-fa356ecb8ac8.png)

TEMPLATE

![django19](https://user-images.githubusercontent.com/92988781/168224685-c142ea98-ffcf-4c77-bd80-874e8a11a7f9.png)

TAMPILAN

![django20](https://user-images.githubusercontent.com/92988781/168224755-15f5a1b0-38b5-43b0-bcc3-422a8061b76d.png)
