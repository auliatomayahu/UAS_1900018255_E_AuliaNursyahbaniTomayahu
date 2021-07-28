1. Jika setiap class secara langsung menggunakan class lain maka akan 
melanggar prinsip Open/Closed. Jadi, sebisa mungkin kita memiliki kode 
yang berubah ketika fungsi utamanya berubah tetapi tidak berubah ketika 
fitur baru ditambahkan. Nah selanjutnya yang akan terjadi ketika menambahkan 
class baru yang mengimplementasi interface adalah munculnya fitur-fitur 
tambahan dan perubahan terhadap requirement. Dalam hal ini, prinsip Open 
Close Principle dibutuhkan dengan membatasi perubahan pada class yang telah 
didevelop sebelumnya sehingga tidak menimbulkan bug baru terhadap code yang telah 
ada. OCP sendiri dapat dilakukan dengan menggunakan interface ataupun abstract class.

2. Class yang meng-Implements suatu Interface maka class tersebut harus 
meng-Override Method yang ada pada Interface. Interface sendiri merupakan 
sekumpulan method yang dibuat tapi belum ada operasi di dalam tubuh method 
tersebut serta bisa diturunkan atau diwariskan kepada class yang ingin memakai 
method yang ada dalam masing-masing interface tersebut dengan keyword extends 
(interface yang didefinisikan). Dan juga sebuah class mengimplementasi satu 
interface yang sudah dibuat dengan keyword implements.
