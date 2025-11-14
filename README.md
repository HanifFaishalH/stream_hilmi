Hanif Faishal Hilmi
TI-3F
Absen 15

# Jobsheet 12: Streams

## Praktikum  5: Multiple stream subscriptions

### Soal 10

- Jelaskan mengapa error itu bisa terjadi ?

Error bisa terjadi karena numberStreamController.stream sedang dipakai lebih dari satu listener. Stream default adalah single subsciption, sehingga hanya boleh punya 1 listener.

### Soal 11

- Jelaskan mengapa hal itu bisa terjadi ?
Karena, streamnya diubah menjadi BroadcastStream. Karena telah diubah, stream bisa punya banyak listener sehingga stream tidak error ketika dilisten ulang.

- Capture hasil praktikum Anda berupa GIF dan lampirkan di README.
![p5_s10.gif](asset/praktikum5/p5_s10.gif)