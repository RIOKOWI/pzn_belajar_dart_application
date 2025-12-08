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
lib\pzn_belajar_dart_application.dart
lib\import_as.dart

## COMPILE

DART PLATFORM
- teknologi compiler dart memungkinkan kita menjalankan aplikasi dengan beberapa cara
- Native Platform, untuk aplikasi dengan target perangkat mobile atau desktop. Dart menyertakan Dart VM dengan just-in-time (JIT) compilation dan ahead-of-time(AOT) untuk memproduksi kode mesin
- web Platform, untuk aplikasi dengan target web, Dart menyertakan development time controller(dartdevc) dan production time compiler (dart2js), keduanya melakukan kompilasi dari kode Dart ke JavaScript.
- di sini kita bahas dart native platfor dengan target perangkat desktop

CROSS PLATFORM SYSTEM
- Dart tidak mendukung kompilasi untuk target sistem operasi berbeda.
- oleh karena itu, jika kita ingin membuat distribusi file untuk sistem operasi berbeda, maka kita harus melakukannya di sistem operasi tersebu, misal mac untuk mac, linux untuk linux, dan windows untuk windows

DART COMPILE
- untuk melakukan kompilasi kode program kita menjadi distribusi file aplikasi desktop, kita bisa menggunakan perintah :

dart compile exe file.dart -o fileoutput

contoh di file :
app

## UPGRADE PACKAGES
