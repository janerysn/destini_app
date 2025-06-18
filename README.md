# destini_app

Uji Aplikasi<br>
1.	Jalankan aplikasi (flutter run).<br>
 <img src ="https://github.com/user-attachments/assets/48bcccc9-2bcb-4015-a1f0-f71d3c4c8687" width= "400px"><br>
 <img src ="https://github.com/user-attachments/assets/95602025-e8ac-4fc3-b734-d548bf0a792c" width= "400px"><br>
 <img src ="https://github.com/user-attachments/assets/03094689-81f6-4061-88f5-39144804a533" width= "400px"><br>
2.	Penjelasan.<br>
Aplikasi Destini App adalah aplikasi cerita interaktif berbasis Flutter, di mana pengguna menentukan alur cerita berdasarkan pilihan yang mereka ambil.
Komponen utama aplikasi:
- DestiniApp adalah root widget yang menjalankan aplikasi dengan tema gelap dan halaman utama StoryPage.
- StoryPage adalah StatefulWidget yang menampilkan teks cerita (storyBrain.getStory()) dan dua tombol pilihan (getChoice1() dan getChoice2()).
- Pilihan yang ditekan oleh pengguna akan memicu perubahan cerita melalui method nextStory(), yang mengatur alur cerita berdasarkan input pilihan (1 atau 2).
- storyBrain adalah instance dari class StoryBrain (diimpor dari file story_brain.dart) yang mengelola data cerita, pilihan, dan logika alur.
- Tombol kedua menggunakan widget Visibility untuk menyembunyikan tombol saat hanya ada satu pilihan yang tersedia di akhir cerita.
Aplikasi ini merupakan contoh sederhana aplikasi choose-your-own-adventure dengan pengelolaan state berbasis logika cerita yang dipisahkan di class StoryBrain.
