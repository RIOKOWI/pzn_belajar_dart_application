## DEPENDENCY

- ketika kita membutuhkan library di apliaksi dart, kita bisa tambahkan dependency tersebut di file pubspec.yaml pada bagian dependencies
- misal kita akan coba tambahkan dependencies library yang sudah kita buat

DOWNLOAD DEPENDENCY
- setelah kita tambahkan dependency di file pubspec.yaml, selanjutnya kita perlu download dependency tersebut ke local kita dengan perintah :
    dart pub get
- semua dependency akan di download ke local di folder HOME/pub-cache/


## IMPORT

- setelah kita menambah dan download depedency ke aplikasi, selanjutnya kita bisa gunakan library depedency tersebut menggunakan import.

IMPORT AS
- kadang saat melakukan import beberapa packages, ada kalanya terdapat conflict, misal ada function dengan nama yang sama, atau class dengan nama yang sama
- pada kasus seperti ini, salah satu hal yang cocok adalah membuat prefix untuk packages yang kita import
- untuk menambah prefix atau alias, kita bisa gunakan kata kunci as diikuti nama prefix/alias nya setelah import
- ketika menggunakan import As, maka kita wajib menggunakan prefix/alias tersebut sebelum memanggil function atau class yang terdpat di packages tersebut.

contoh di file :
