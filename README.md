# Fragment
Fragment adalah komponen UI yang mempresentasikan tampilan pada layar. Fragment juga merupakan bagian dari sebuah activity yang mana sebuah fragment tidak akan ada bila tidak ada sebuah activity karena fragment membutuhkan akses dari activity untuk dapat dijalankan.

Kelebihan yang didapatkan bila menggunakan fragment adalah sebagai berikut:

- Tidak perlu memasukkan nama file fragment ke dalam “AndroidManifest” yang diperlukan oleh activity.

- Fungsi yang berada pada activity dapat langsung digunakan dalam fragment tersebut tanpa harus membuat ulang. Contoh: pada saat back, fragment hanya perlu memanggil fungsi “getactivity"

Berikut beberapa poin penting tentang fragment yang perlu untuk kita ketahui, yaitu :

- Fragment dibuat dengan kombinasi file XML Layout dan kelas java seperti Activity.

- Fragment memiliki layout, perilaku, dan life-cyclenya sendiri.

- Fragment dapat di “add” atau “remove” dalam suatu activity saat activity dalam keadaan running.

- Fragment berdiri dan bergantung pada suatu activity dan life-cyclenya dipengaruhi oleh lifecycle activity itu sendiri (Ketika activity pause, fragment juga pause. Ketika activity destroyed, semua fragment akan destroyed)

- Fragment dapat berperilaku seperti activity dalam hal stack. Yaitu dengan penggunaan back stack pada fragment. Fragment baru akan ditambahkan ke stack. Jika kita menekan tombol back, maka akan kembali ke stack fragment yang ditambahkan sebelumnya.

# Intro Slider
Intro Slider merupakan tampilan beberapa slide yang bisa di geser oleh user sebelum masuk ke menu utama pada sebuah aplikasi atau dengan nama lain Layar Perkenalan Aplikasi.

Pada Intro slider biasanya memiliki navigasi skip dan next. User juga dapat menavigasi melalui setiap slide menggunakan gerakan mengusap layar HP atau menggunakan tombol next.

# Penerapan Intro Slider
Halaman pertaman

![WhatsApp Image 2021-03-19 at 21 26 24](https://user-images.githubusercontent.com/60589822/111801307-68ba2600-88ff-11eb-9167-28629b0ad103.jpeg)

Halaman kedua

![WhatsApp Image 2021-03-19 at 21 26 24 (1)](https://user-images.githubusercontent.com/60589822/111801318-6bb51680-88ff-11eb-9d12-405e7c8cc69f.jpeg)

Halaman ketiga

![WhatsApp Image 2021-03-19 at 21 26 25](https://user-images.githubusercontent.com/60589822/111801273-5fc95480-88ff-11eb-9572-730aceb83f8b.jpeg)

Halaman Keempat


![WhatsApp Image 2021-03-19 at 21 26 25 (1)](https://user-images.githubusercontent.com/60589822/111801283-62c44500-88ff-11eb-8c3b-24641ef9df2f.jpeg)

# Penerapan Fragment Setelah Masuk Aplikasi
![WhatsApp Image 2021-03-19 at 21 26 22](https://user-images.githubusercontent.com/60589822/111801286-65269f00-88ff-11eb-8bcb-b11ce3092cbd.jpeg)
![WhatsApp Image 2021-03-19 at 21 26 23](https://user-images.githubusercontent.com/60589822/111801301-6788f900-88ff-11eb-8e33-9967342e4c76.jpeg)
