## created by 21343058_Muhammad Farel Fahlevi

kita akan membahas konsep dari classes dan 
bagaimana menggunakan class dan anggotanya. Perubahan dan pemilihan object
juga akan dibahas. Sekarang, kita akan fokus dalam menggunakan class yang telah
dijabarkan dalam Java Class library, kita akan membahas nanti tentang bagaimana 
membuat class sendiri.

Latihan 1: Pass By Value
Pass By Value dan Pass By Reference merupakan metode dalam mengirimkan parameter ke dalam sebuah fungsi, dimana didalam java disebut Behavior/Method . Pass By Value melewatkan parameter berdasarkan nilainya.
Disini nilai parameter aktual akan dilewatkan pada saat pemanggilan method akan disalin ke parameter formal sehingga perubahan nilai pada method, tidak akan berpengaruh terhadap argument yang digunakan untuk memanggil method tersebut. Dengan kata lain, perubahan nilai tersebut hanya akan dikenali pada method yang bersangkutan saja.

Latihan 2 : Pass By Reference
Pass By Reference melewatkan parameter berdasarkan referensinya. Pada cara ini , referensi dari argumen (bukan nilai argumen) akan dilewatkan kedalam parameter formal, bukan disalin.
Dengan demikian, nilai yang digunakan di dalam method akan sama dengan nilai yang di tunjuk referensi.
Melalui cara ini setiap perubahan nilai yang terjadi pada method juga akan berpengaruh terhadap argumen yang digunakan untuk memanggilnya.

Perbandingan Object
Metode equals() membandingkan dua String berdasarkan kontennya. Sehingga, apabila dua buah String memiliki huruf-huruf yang sama, diurutan yang sama dan besar-kecil yang sama maka dua String ini akan dianggap sama.
Pada Latihan ini,kita membandingkan 2 buah String yaitu, str1 dan str2 dengan simbol "==".

Latihan 4 : Pemanggilan Method Menggunakan Parameter
Dilanjutkan dengan membuat class baru untuk melanjutkan class diatas.
class baru hanya dapat mengakses kelas induk,jika class induk tidak private
