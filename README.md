Step 1
 Kumpulin data, atur jadi perkelas di excel (walaupun sekali pengiriman ada limit per 100 user, ini akan mempermudah kalo ada yang minta kirim email ulang)
 Pastiin buat 4 kolom yang wajib ada (nis, nama, link form, link qr code)
Step 2
 Buat Form yang isinya nama semua orang sesuai kelas (pake opsi pilihan) (langsung ctrl+c ctrl+v otomatis bisa langsung sekelas kok)
 <img width="1280" alt="image" src="https://github.com/user-attachments/assets/8622d287-c80c-44e3-a2de-acd2feafca8a" />
 Kalo udah, Tambahin opsi Hadir
 <img width="1280" alt="image" src="https://github.com/user-attachments/assets/bc28dfa4-b52a-45ff-9b65-69b7b24ecd78" />
 Klik titik tiga di pojok kanan, terus pilih yang ini
 <img width="1280" alt="image" src="https://github.com/user-attachments/assets/cc355227-9729-47b2-bb42-7eff23321166" />
 Klik sample kelas, klik hadir, terus dapatkan link (perkelas linknya beda!) (link ini untuk qr code nanti)
 <img width="1280" alt="image" src="https://github.com/user-attachments/assets/28dae648-bfb8-4a4e-a68a-1e99044740cf" />
Step 3<br>
 Tadi udah dapet link, develop linknya di excel.
 Buat format linknya jadi seperti ini
 <img width="1280" alt="image" src="https://github.com/user-attachments/assets/8cd0285c-e098-4fb6-b70d-999fba5d8ada" />
 Caranya,Buat dulu kolom lain (pecah-pecahin bagian ini), pastiin di link depan udah diganti jadi formResponse.
 Dibagian potongan kedua, ingat ya, setiap kelas beda
 Dibagian potongan ketiga, awalnya diantara nama adanya spasi, pakai find and replace " " untuk ganti jadi "="
 Dibagian potongan terakhir, semua sama kaya gitu
 <img width="941" alt="image" src="https://github.com/user-attachments/assets/5fe322a5-ffcd-402c-88d8-bb52f2ec5366" />
 Selanjutnya gabungin semua elemen yang tadi dipecah-pecah, pakai "=CONCAT()", kalo udah kegabung, hold dan pilih data itu, copy, terus paste as value
 Jika sudah fix, ubah link ini jadi qr code (pakai website, cari aja bulk qr code)
 ingat, saat diubah, atur format gambar yang urut, (contoh (img.1))
Step 4<br>
 Up qr code di github, sesuai kelasnya masing-masing.
 Jangan lupa buat up file gambar undangannya juga
 bagi 3 lagi kaya gini, sesuaiin angkanya saja,
 jika sudah, seperti biasa, gabungin pakai "=CONCAT()" dan paste as value
 <img width="600" alt="image" src="https://github.com/user-attachments/assets/605c7475-4602-4045-ac77-3557a3ebe6d8" />
Step 5<br>
 Jika sudah, buat file di spreadsheet.
 Disclaimer, karena batas pengiriman email maksimal 100 email perhari, buat 1 sheet jadi 100 email.
 Disini kalian terpaksa harus buat beberapa email, nyesuaiin kuantitas yang dibutuhin.
 Usahakan kirim email beberapa hari sebelum acaranya (berangsur juga) karena menurut saya, ini cukup aman dan memanage limit kirim email di akun-akun kalian.
 Jika sheet sudah diatur, klik extension lalu klik Apps Script
 Setelah di Apps Script, masukin code yang sudah dibuat (kayanya ini lebih support JS)
 (atur aja code nya dari source code, keterangan yang diubah-ubah udah ada slash commentnya)
 Jika sudah, debug saja dulu sebelum run, pastiin tidak ada kesalahan program
 kalau sudah fix, gasken di run ygy

 
