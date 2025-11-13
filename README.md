Hanif Faishal Hilmi
TI-3F
Absen 15

# Jobsheet 12: Streams

## Praktikum 3: Injeksi data ke streams

### Soal 8

- Jelaskan maksud kode langkah 1-3 tersebut!
    - langkah 1: menambahkan variabel StreamTransformer
    - langkah 2: menambahkan StreamTransformer ke initState. Setiap angka yang masuk ke stream, akan dikali 10. Jika stream menerima error, transformer akan mengganti error dengan -1, Jika stream selesai, listener tidak menerima event lagi.
    - langkah 3: jika tombol ditekan, akan menghasilkan angka random. method addNumberToSink() akan mengirimkan angka ke stream. Transformer akan mengalikan angka dengan 10. Listener menerima event yang telah dihitung dan setState() akan menampilkan angka tersebut di UI.
- Capture hasil praktikum Anda berupa GIF dan lampirkan di README.