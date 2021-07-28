Pengertian :
<br> Single-Responsibility Principle (SRP) adalah prinsip pemrograman komputer yang 
menyatakan bahwa setiap modul, kelas, atau fungsi dalam program komputer harus 
memiliki tanggung jawab atas satu bagian dari fungsi program tersebut dan harus 
merangkum bagian tersebut. Semua layanan modul, kelas, atau fungsi harus diselaraskan 
dengan tanggung jawab tersebut. Prinsip SRP yang dikemukakan oleh Robert C. Martin 
berbunyi, "Sebuah kelas seharusnya hanya memiliki satu alasan untuk berubah." Dalam 
beberapa kesempatan, ia juga berpendapat bahwa prinsipnya dikhususkan tentang peran atau aktor. 

Penjelasan :
Dalam tipe statis dan bahasa yang dikompilasi, beberapa alasan dapat menyebabkan 
beberapa perubahan yang tidak diinginkan. Jika ada dua alasan yang berbeda untuk 
perubahan, bisa dibayangkan bahwa dua tim yang berbeda mungkin bekerja pada kode 
yang sama untuk dua alasan yang berbeda sehingga dapat mengakibatkan tidak kompatibelnya 
modul dengan tim lain atau bagian lain dari aplikasi. Menentukan satu single responsibility 
suatu class atau modul seharusnya lebih kompleks daripada hanya melihat daftar periksa. 
Misalnya, satu petunjuk untuk menemukan alasan kita melakukan perubahan adalah menganalisis 
peserta untuk class kita. Pengguna aplikasi atau sistem yang kita kembangkan yang dilayani 
oleh modul tertentu akan menjadi orang yang meminta perubahan untuk itu. Mereka yang bertugas 
akan meminta perubahan. Dalam arti dari pemikiran ini, aktor menjadi sumber perubahan untuk 
keluarga fungsi yang melayani mereka. Ketika kebutuhan mereka berubah, keluarga fungsi yang 
spesifik juga harus berubah untuk mengakomodasi kebutuhan mereka.

Pencetus : Robert C. Martin
“Sebuah class sebaiknya hanya memiliki satu alasan untuk perubahan.”
“Responsibility adalah sebuah keluarga fungsi yang melayani satu aktor tertentu.”
“Aktor untuk responsibility adalah satu-satunya sumber perubahan untuk responsibility itu.”

Keuntungan :
Rancangan yang dihasilkan tetap dapat memberikan faktor kohesi yang tinggi. 
Kohesi dalam perangkat lunak merujuk pada pemahaman tentang seberapa dekat 
hubungan ketergantungan antara method (fungsi) dan atribut dalam sebuah class.  
Sebuah class akan memiliki kohesi tinggi jika menggunakan method-method dan 
variabel level class secara utuh untuk menyelesaikan suatu pekerjaan tertentu. 
Sebaliknya sebuah class dinilai memiliki kohesi yang rendah jika memiliki method-method 
yang disisipkan secara acak dan digunakan untuk memenuhi berbagai macam pekerjaan.
