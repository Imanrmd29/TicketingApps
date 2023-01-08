# TicketingApps
Aplikasi Pemesanan Tiket nonton bioskop yang dimana menggunakan beberapa fitur seperti costumview.
Alur dari Custom View (pewarisan kelas View) ketika digunakan kurang lebih 
![Alur](https://user-images.githubusercontent.com/101419944/211205533-5a37c2e3-0f2c-42df-a3d5-931568e4ccd3.jpeg)
# Berikut keterangan dari gambar tersebut:

Start : Sebuah Custom View telah siap untuk dipanggil dalam sebuah tampilan.
View Initialize : Proses terjadinya inisialisasi dari pemanggilan Custom View. Anda bisa mengatur proses inisialisasi tersebut melalui konstruktor.
View Dimension : Digunakan untuk mengatur dimensi (baik lebar atau panjang) dari sebuah Custom View melalui metode onMeasure(). Selain itu, kita juga bisa menetapkan dimensi dari masing-masing object yang akan digambar dalam Canvas.
View size changed : Digunakan untuk mendefinisikan perubahan yang terjadi. Jika Custom View yang telah didefinisikan terdapat perubahan sewaktu-waktu, Anda dapat memperbarui dimensi dari masing-masing object melalui metode onSizeChanged.
Determine child view layout : Digunakan untuk menentukan mengatur view lain yang akan ditampilkan dalam Custom View melalui metode onLayout.
RenderView : Digunakan untuk menggambar object ke dalam Canvas melalui metode onDraw.
User Operation : Proses interaksi pengguna dengan Custom View. Anda dapat memanggil fungsi invalidate untuk memperbarui status yang diberikan pengguna. 
Finish : Proses akhir dari sebuah Custom View. Biasanya proses tersebut terjadi Custom View berada dalam Activity atau Fragment yang akan berakhir.
