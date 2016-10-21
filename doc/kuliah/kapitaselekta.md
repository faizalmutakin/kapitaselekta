kapitaselekta!

latar belakang:
penjelasan ssh,dan membuat sshkey!
mengenal organization di github!
cara upload file ke github!

isi
	membahas sedikit tentang github ,github ini sering gunakan oleh
seorang developer untuk mengupload kodingan dan untuk membuat suatu
organisai,github ini bisa digunakan juga untuk mengedit code dimana 
kode tersebut sudah kita upload sebelumnya. 
	SSH adalah autentifikasi akun github ke pc yang kita gunakan
pada saat kita melakulak upload kerevisitori kita tidak perlu masukan
password dan username.

cara membuat ssh
1login ke link github 
2.klik sebelah kanan dekat profile diatas kanan pilih seting
4.pada setting klik menu ssh
5.klik new
6.isi title
7.jalankan gitbush
8.ketikan perintah (ssh-keygen -t rsa -b 4096 -C "email github anda")
9.lalu enter, dan enter sampai memintak masukan kembali kode
10.masukan code berikut (cat ~/.ssh/id_rsa.pub)
11.dan enter copy,kode yang keluar ke key digithub tadi.

organization pada github adalah sebuah organisasi yang membuat kita
bisa berkolaborasi dengan user lain menggunakan github, dan tentunya
user dapat berkolaborasi harus ada pada organization yang sama.
berikut langkah-langkah upload file pada github:

-buat revisitory terlebih dahulu
-buat folder yang akan kita upload dan klik kanan masuk gitbashhere
-ketikan perintah seperti berikut;
1.git init
2.git remote add origin link repository
3.git pull origin master
4.git status
5.git add folder/file
6.git status
7.git add folder/file (perintah ini digunakan apabila file kita berada pada suatu foder)
8.git status (jika muncul:On branch master Changes to be committed) langsung ke
9.git commit -m "komen"
10.git status (jika muncul:nothing to commit, working tree clean) langsung ke
11.git push origin master
