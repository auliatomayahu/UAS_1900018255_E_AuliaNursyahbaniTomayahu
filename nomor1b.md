Pengertian :
<br> Open/Closed Principle. Open for extension artinya desain class 
sehingga ketika menambahkan fungsi baru harus dapat ditambahkan. 
Close for modification artinya sebuah class yang telah didevelop, 
harusnya tidak dimodifikasi lagi kecuali karena bug. Hal ini bisa 
dicapai dengan mengabstraksikan dependency-dependencynya. Karena 
sebenarnya, client tidak perlu tahu detail implementasinya seperti 
apa, tetapi hanya perlu tahu objeknya tersebut bisa apa. Dengan abstraksi 
yang bagus, akan membuat code menjadi less coupled serta memiliki 
adaptivitas yang bagus terhadap perubahan. Ringkasnya, semisal kita 
punya suatu projek yang sudah berjalan, dengan menerapkan OCP dengan 
benar, kita bisa saja menambah fitur baru tanpa harus menyenggol code 
lama yang sudah ada sebelumnya (extending the existing system, but not 
changing them). Kuncinya ada di abstraksi, jika kita terbiasa membangun 
sebuah software dengan abstraksi yang bagus, maka hal ini bisa dilakukan.

Keuntungan
<br> Open/Closed Principle sebagai pedoman untuk keseluruhan desain kelas 
dan antarmuka dan bagaimana pengembang dapat membangun kode yang memungkinkan 
perubahan dari waktu ke waktu. Prinsip terbuka/tertutup memastikan bahwa kode 
yang kita buat terbuka untuk ekstensi tetapi tertutup untuk modifikasi. Jadi 
kita secara efektif melarang perubahan di masa mendatang pada kelas dan rakitan 
yang dibuat dan memaksa pemrogram baru untuk membuat kelas baru yang dapat 
dihubungkan ke titik ekstensi. Terdapat juga pendekatan yang disarankan untuk 
mengidentifikasi bagian dari persyaratan yang mungkin berubah atau yang sangat 
sulit untuk diterapkan.
