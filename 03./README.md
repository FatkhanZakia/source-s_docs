| time                | author                                           |
| ------------------- | ------------------------------------------------ |
| 2020-06-28 12:06:00 | [Fatkhan Zakia](https://github.com/FatkhanZakia) |

# Cara Membuka MySql Database di Linux Deepin OS

- Yang pertama adalah, buka dulu terminal dengan cara tekan `ctrl+alt+T`, lalu matikan `apache2` dengan cara ketik `service apache2 stop` dan jangan lupa isikan password komputer anda.
  ![1](https://user-images.githubusercontent.com/35970373/84663896-f9ff0500-af47-11ea-800f-c5fee0ac5635.png)

- Kemudaian lakukan dengan perintah yang sama, ketikan `service mysql stop` untuk mematikan `mysql` dan jangan lupa isikan password komputer anda.
  ![2](https://user-images.githubusercontent.com/35970373/84664381-a93bdc00-af48-11ea-89a6-9335013da2b5.png)

- Kemudian lakukan perintah `cd /opt/lampp/` lalu ketik `ls` untuk melihat isi directory.
  ![3](https://user-images.githubusercontent.com/35970373/84665997-b9ed5180-af4a-11ea-9898-5b0068bf7f60.png)

- Setelah itu ketik `sudo ./manager-linux-x64.run` dan jangan lupa isi kan password anda.
  ![4](https://user-images.githubusercontent.com/35970373/84666241-08025500-af4b-11ea-84a1-0c20f3899998.png)

- Kemudian tampilannya seperti ini dan pilih `Manage Servers`
  ![5](https://user-images.githubusercontent.com/35970373/84666424-3d0ea780-af4b-11ea-8793-46f79c642c65.png)

- Lalu pilih `Start All` sampai beruah warna menjadi hijau.
  ![6](https://user-images.githubusercontent.com/35970373/84666748-ab536a00-af4b-11ea-8830-392df1372ae6.png)

- Kemudian yang terakhir adalah buka browser anda dan ketik `http://localhost/phpmyadmin/` . "Selamat anda sudah berhasil".
  ![7](https://user-images.githubusercontent.com/35970373/84667042-05ecc600-af4c-11ea-8655-e78bf15d27a4.png)

> **Note**:
> I hope you learn something
