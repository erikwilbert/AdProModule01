# Reflection 1
Beberapa prinsip clean code dan secure code yang telah saya terapkan adalah sebagai berikut.
1. Nama variable, class, dan methods yang jelas, konsisten, dan tidak ambigu sehingga mudah untuk dipahami.
2. Setiap method atau function hanya memiliki 1 tugas tanpa ada beberapa tugas dikerjakan dalam 1 function atau method.
3. Tidak comment untuk code code yang terlihat membingungkan tetapi ditulis ulang hingga mudah dipahami.
4. Layout dan formatting yang konsisten antara semua file.
5. Penggunaan interface dan abstract method membantu menyembunyikan detail implementasi, mengurangi ketergantungan pada implementasi konkret.
6. Menerapkan arsitektur yang jelas dan konkret, setiap tanggung jawab terpisah (controller, service, repository), masing-masing memiliki tugas tersendiri dan readability serta maintainability.
7. Controller yang tidak mengandung logika kompleks, controller hanya sebagai perantara view dan service untuk menghandle http request.

Beberapa kesalahan yang masih ditemukan dan cara improve.
1. Tidak ada error handling yang jika terjadi error akan menyebabkan aplikasinya tidak berfungsi dengan baik, caranya adalah dengan menambahkan error handling dan juga membuat exception handler sendiri.
2. Masih ada return null pada beberapa method, caranya adalah dengan menambahkan beberapa exception untuk menghandle dan merespons jika returnnya adalah null.
3. Tidak ada input validation yang dapat menyebabkan data tidak valid, caranya adalah menambahkan validation setiap ada input form.
