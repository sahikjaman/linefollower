PRARORO BOT_Projek line follower
Robot line follower yang dirancang agar dapat mengikuti lintasan apapun. Robot ini menggunakan berbagai komponen mekanik dan elektrik untuk menjalankan tugasnya dengan efisien. Tegangan keseluruhan operasi robot ini adalah 12 volt, yang diperoleh dari tiga baterai 18650 yang disusun secara seri dengan masing-masing baterai memiliki kapasitas 3000mAh.

Robot ini dilengkapi dengan dua motor DC gearbox kuning, yang masing-masing beroperasi pada tegangan 3-10V. Motor ini memiliki kecepatan maksimum 200 rpm dan torsi 0.5 Nm, cukup untuk menggerakkan robot dengan stabil dan mampu mengangkut beban sekitar 500 gram. Motor-motor ini dihubungkan ke roda berdiameter 65 mm yang terbuat dari karet, memberikan cengkeraman yang baik dan stabilitas yang diperlukan saat mengikuti garis, dengan satu roda caster kecil untuk memberikan dukungan dan stabilitas tambahan.

Sistem kontrol robot menggunakan mikrokontroler Arduino nano yang mengimplementasikan algoritma if. Algoritma ini memastikan robot dapat mengikuti garis dengan presisi dan pergerakan yang halus. Untuk mendeteksi garis, robot ini menggunakan qtr-8 analog sensor yang memiliki 8 kanal input analog. Sensor-sensor ini mengirimkan data ke mikrokontroler, yang kemudian memproses data tersebut untuk mengatur kecepatan dan arah motor melalui driver motor L298N. Driver ini mampu menangani arus hingga 2 Ampere per channel, yang cukup untuk motor DC gearbox kuning yang digunakan.

gambar desain robot
![Picture1](https://github.com/user-attachments/assets/02cf36f1-d2cb-430a-ac17-17eb0015c873)

gambar lintasan
![Gambar WhatsApp 2024-08-28 pukul 20 09 01_316bd31c](https://github.com/user-attachments/assets/fe16a085-b4d6-4cfb-9972-e34e20b5341a)


