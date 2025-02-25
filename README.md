# praktikum_4_sistem_operasi
1. Lihat daftar secara lengkap pada direktori aktif, belokkan tampilan standard output ke file baru.

![Gambar WhatsApp 2025-02-26 pukul 01 07 13_67036981](https://github.com/user-attachments/assets/206e6332-c616-4846-8774-2af5ae4d134a)

Menampilkan isi direktori latihan5 secara lengkap dan menyimpannya ke daftar_latihan5.txt.

2. Lihat daftar secara lengkap pada direktori /etc/paswd, belokkan tampilan standard output ke file baru tanpa menghapus file baru sebelumnya.

![Gambar WhatsApp 2025-02-26 pukul 01 07 14_6a036424](https://github.com/user-attachments/assets/643db023-72ba-40d7-af5a-d9f3c87033e6)

Menyimpan informasi file /etc/passwd ke dalam daftar_passwd.txt tanpa menghapus data lama.

3. Urutkan file baru dengan cara membelokkan standard input.

![Gambar WhatsApp 2025-02-26 pukul 01 07 15_8f57e6ee](https://github.com/user-attachments/assets/5d2e05fb-1d6f-4748-81ee-26382cd2f910)

Mengurutkan isi daftar_latihan5.txt tanpa menyimpannya ke file baru.

4. Urutkan file baru dengan cara membelokkan standard input dan standard output ke file baru.urut.

![Gambar WhatsApp 2025-02-26 pukul 01 08 32_2c387e92](https://github.com/user-attachments/assets/caa1a00d-101d-4aa3-8464-9f817f5a2470)

Mengurutkan isi daftar_latihan5.txt dan menyimpan hasilnya ke baru.urut.

5. Buatlah direktori latihan6 sebanyak 2 kali dan belokkan standard error ke file rmdirerror.txt.

![Gambar WhatsApp 2025-02-26 pukul 01 08 33_d24e5f78](https://github.com/user-attachments/assets/7782be89-86a7-486d-9d5d-02975474203f)

Direktori latihan6 dibuat sekali. Jika Percobaan gagal karena latihan6 sudah ada, dan error maka disimpan ke rmdirerror.txt.

6. Urutkan kalimat berikut : Jakarta Bandung Surabaya Padang Palembang Lampung Dengan menggunakan notasi here document (<@@@ …@@@)

![Gambar WhatsApp 2025-02-26 pukul 01 08 34_7564b1b8](https://github.com/user-attachments/assets/e1eba628-5f0a-4115-a313-77662af96085)

Memasukkan daftar kota secara manual dan mengurutkannya langsung tanpa menyimpan ke file.

7. Hitung jumlah baris, kata dan karakter dari file baru.urut dengan menggunakan filter dan tambahkan data tersebut ke file baru.

![Gambar WhatsApp 2025-02-26 pukul 01 10 09_d9f58890](https://github.com/user-attachments/assets/406c51ee-3930-4886-af2c-446e26bf62ca)

Menghitung jumlah baris, kata, dan karakter dalam baru.urut. Menambahkan hasilnya ke hasil_wc.txt.

8. Gunakan perintah di bawah ini dan perhatikan hasilnya. $ cat /etc/passwd | sort | pr –n | grep tty03 $ find /etc –print | head $ head /etc/passwd | tail –5 | sort

![Gambar WhatsApp 2025-02-26 pukul 01 10 09_968de22f](https://github.com/user-attachments/assets/09f23acf-e054-480b-877a-aba35ff8356e)

Perintah ke 1 untuk Menampilkan isi /etc/passwd, mengurutkannya, lalu mencari entri dengan tty03. Perintah ke 2 untuk Menampilkan daftar file dalam /etc, tetapi hanya 10 baris pertama. dan Perintah ke 3 untuk Mengambil 10 baris pertama dari /etc/passwd, lalu menyaring 5 baris terakhir sebelum mengurutkannya.

9. Gunakan perintah $ who | cat | cat | sort | pr | head | cat | tail dan perhatikan hasilnya.

![Gambar WhatsApp 2025-02-26 pukul 01 10 10_052af7a2](https://github.com/user-attachments/assets/29d153e3-ec13-47be-be6b-ddb8a9d8230a)

- who > Menampilkan daftar pengguna yang sedang login. adin seat0 2025-02-23 19:11 (login screen) → Pengguna tamam login di seat0 pada 19:11. tamam tty2 2025-02-23 19:11 (tty2) → Pengguna adin login di tty2 pada 19:11.

cat | cat >Tidak mengubah output, hanya meneruskan data yang sama. sort > Mengurutkan daftar login berdasarkan abjad, tapi karena hanya ada satu user adin, urutan tetap sama. pr > Memformat output agar terlihat seperti dokumen dengan tambahan "Page 1" dan timestamp 2025-02-21 22:53. head > Mengambil beberapa baris pertama dari output. cat | tail > tail menampilkan bagian akhir dari hasil sebelumnya, sehingga tetap menampilkan seluruh output jika jumlah baris tidak terlalu banyak.

KESIMPULAN
Melalui latihan-latihan ini, pengguna dapat memahami dan mempraktikkan konsep dasar pengalihan input dan output di sistem operasi, yang esensial untuk pengelolaan file dan automasi tugas sehari-hari.
preview
