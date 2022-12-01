# Tugas 7

## Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya

- Stateless widget adalah widget statis yang tidak dapat mengalami perubahan nilai dari state yang ada
- Stateful widget adalah widget dinamis yang dapat mengalami perubahan berdasarkan nilai state yang ada

## Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya

- Scaffold: widget yang menyimpan seluruh widget yang akan ditampilkan dan berlaku sebagai widget utama

- Center: widget yang berfungsi sebagai layout yang mengatur child widget nya ke tengah

- Container: widget yang berfungsi sebagai layout dari children widget nya.

- Row: widget yang berfungsi sebagai layout dari children widget nya dengan arah horizontal 

- Column: widget yang berfungsi sebagai layout dari children widget nya dengan arah vertikal

- Text : widget yang berfungsi untuk menampilkan tulisan

- Visibility: widget yang berfungsi untuk mengatur apakah suatu child widget nya ditampilkan atau tidak

- FloatingActionButton: widget yang berfungsi sebagai fab button yang biasanya melayang pada layar

## Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut

Fungsi setState() adalah untuk melakukan build ulang pada stateful widget jika ada perubahan nilai atau ada object yang berubah dari state .

## Jelaskan perbedaan antara const dengan final

final dan const merupakan keyword/kata kunci yang dapat digunakan untuk membuat variabel yang bersifat immutable. Perbedaan final dan const variable adalah nilai dari const variable sudah diberikan secara eksplisit saat compile time, sedangkan final tidak mengharuskan variabel memiliki nilai secara eksplisit pada saat compile time.

## Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas

1. Mengimplementasi fungsi _decrementCounter() untuk mengurangi sebanyak satu angka counter saat tombol - diklik
2. Menambahkan FloatingActionButton pada bottomLeft layar.
3. Menambahkan Text yang menampilkan nilai dan paritas dari counter saat ini.
4. Menambahkan style sehingga teks berwarna biru saat angka bernilai ganjil dan berwarna merah saat angka bernilai genap
5. Melakukan add-commit-push ke repositori baru di GitHub dengan nama pbp-flutter-lab

# Tugas 8

## Jelaskan perbedaan Navigator.push dan Navigator.pushReplacement

Perbedaannya adalah Navigator.push setelah berpindah halaman dapat kembali ke halaman sebelumnya sedangkan Navigator.pushReplacement setelah berpindah halaman tidak dapat kembali ke halaman sebelumnya.

## Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya

- Row : menampilakan tampilan horizontal pada children
- Container : widget yang digunakan untuk membungkus widget lain 
- Scaffold : widget yang digunakan untuk membuat halamat di flutter
- Appbar : menampilkan toolbar di flutter.
- Center : memposisikan widget child di tengah
- Column : memposisikan widget chlidren secara vertikal
- Drawer : panel untuk navigasi
- Text : menampilkan sebuah string
- TextFormField : input form berupa string
- Form : membuat form
- DateTime: widget representatif dari sistem penanggalan


## Sebutkan jenis-jenis event yang ada pada Flutter (contoh: onPressed)

- onPressed() : event yang menjalankan suatu fungsi ketika sebuah button di-click
  
- onTap() : event yang menjalankan suatu fungsi ketika sebuah widget di-click satu kali
  
- onChanged() : event yang menjalankan  suatu fungsi ketika suatu value pada sebuah widget diubah.
  
- onSaved() : event yang menjalankan suatu fungsi ketika sebuah form disimpan

## Jelaskan bagaimana cara kerja Navigator dalam "mengganti" halaman dari aplikasi Flutter

`Navigator` mengganti halaman dengan memanfaatkan sebuah `Stack`. Halaman yang ditampilkan di paling atas (dilihat oleh user) adalah halaman yang terdapat pada top of stack. Mengganti halaman dapat memanfaatkan `push` untuk menimpa halaman sebelumnya, `pushReplacement` untuk mengganti halaman sebelumnya, `pop` untuk menghapus halaman yang sedang ditampilkan ke user.

## Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas

1. Membuat file drawer.dart
2. Membuat file budget.dart 
3. Membuat file form.dart 
4. Membuat file data.dart

