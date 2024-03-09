# Latihan View & ViewGroup

## 📚Rangkuman singkat 📚:
### Pada dasarnya, semua elemen antar pengguna (UI) di aplikasi Android dibangun menggunakan dua buah komponen inti, yaitu View dan ViewGroup.
<img src="https://github.com/sarif03/view-viewGroupApp/blob/main/screenshot_komponen%20turunan%20View&ViewGroup.png?raw=true" width="800">

- View merupakan komponen dasar yang tampil di layar dan dapat digunakan untuk berinteraksi dengan pengguna. Contoh komponen turunan dari View adalah TextView, Button, ImageView, RadioButton, Checkbox, dll.
ViewGroup adalah sebuah View spesial yang mewadahi objek-objek View lainnya dan berguna untuk mengatur posisinya.

- ViewGroup adalah sebuah View spesial yang mewadahi objek-objek View lainnya dan berguna untuk mengatur posisinya.
Contoh komponen ViewGroup adalah:

 <img src="https://github.com/sarif03/view-viewGroupApp/blob/main/screenshot_ViewGroup.png?raw=true" width="">

- LinearLayout digunakan untuk menempatkan komponen-komponen di dalamnya secara horizontal atau vertikal.
- RelativeLayout digunakan untuk menempatkan masing-masing komponen secara fleksibel dan relatif terhadap komponen yang lainnya. Misalnya komponen A di sebelah kanan komponen B atau komponen A rata tengah dengan parent-nya.
- FrameLayout digunakan untuk membuat komponen menjadi menumpuk atau saling menutupi satu dengan yang lainnya, dan biasanya digunakan untuk menampung fragment.
- TableLayout digunakan untuk menyusun komponen dalam baris dan kolom tanpa garis terlihat

- ScrollView digunakan untuk membuat komponen di dalamnya dapat digeser (scroll) secara vertikal maupun horizontal. Di dalamnya hanya boleh ada satu layout ViewGroup, tidak boleh lebih.
- Untuk menambahkan gambar ke drawable, copy paste gambar dari explorer ke folder drawable. Pilih folder drawable (bukan drawable-v24) untuk mendukung semua versi Android. 
Ingat bahwa nama file yang ada di dalam resource drawable harus menggunakan huruf kecil dan underscore saja.

- sp/dp : sp(digunakan khusus untuk ukuran font/teks) & dp (digunakan untuk mengisi nilai selain font/teks)

