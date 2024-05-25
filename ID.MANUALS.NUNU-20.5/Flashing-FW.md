## Mem-*flash* Firmware

Melakukan pembaruan firmware ialah memungkinkan melalui program terpisah, tetapi itu bahkan lebih
sederhana dan mudah melalui program peramban web yang berbasis Chromium: Edge, Opera, dsb.

1. Gunakan kabel pemrograman dengan tipe konektor Kenwood K-plug
   ([Baofeng](https://www.baofengradio.com/products/baofeng-programming-cable), dsb.), dan sambungkan USB ke komputer;
2. Matikan radio dengan memutar knob ke kanan hingga "klik";
3. Hidupkan radio dalam mode pemrograman dengan menekan dan tahan tombol PTT, lalu putar knob ke kiri. Kemudian,
   lepaskan PTT dan pastikan jacklight menyala stabil yang menandakan radio sedang dalam mode pemrograman;
4. Sambungkan K-plug kabel pemrograman ke radio dengan "pas" untuk memastikan radio terhubung dengan baik;
5. Pada peramban web komputer Anda, buka halaman URL https://kamilsss655.github.io/uvtools/?firmwareURL=https://github.com/kamilsss655/uv-k5-firmware-custom/releases/download/v.20.5/firmware.packed.bin
   dan tunggu beberapa saat hingga log menunjukkan keluaran sebagai berikut.
   ```
   Loading file from url: https://github.com/kamilsss655/uv-k5-firmware-custom/releases/download/v.20.5/firmware.packed.bin

   CRC check passed...
   Detected firmware version: *NUNU v.20.5
   Firmware uses 99.08% of available memory (60872/61439 bytes).
   ```
   Kemudian, klik "Flash firmware" dan muncul jendela, pilih USB serial yang sesuai dan klik sambungkan.
   Jacklight radio akan menyala berkedip yang menandakan radio sedang dalam pembaruan firmware;
6. Tunggu hingga persentase proses 100% dengan "Successfully flashed firmware." pada antarmuka log dari peramban web;
7. Ketika selesai, putuskan sambungan kabel pemrograman yang menghubungkan radio dengan komputer. Kemudian,
   lakukan pengaturan ulang radio (ALL reset) dengan pergi ke parameter `Reset` pada menu.

_**It Works Like A Charm!**_
