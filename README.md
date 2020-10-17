# LatihanVCS
Tugas bahasa pemrograman

Nama    : Asri Liya Astuti

NIM     : 312010104

Kelas   : TI.20.B.1

Dosen   : Agung Nugroho, S.Kom, M.Kom


##Jika Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah.

  $ git --version
  
 ![Screenshot (15)](https://user-images.githubusercontent.com/72993076/96336627-5ebf9d00-10ab-11eb-92d8-97ddf7e1dabe.png)

	
        	



#PERINTAH DASAR GIT

1.	git init, perintah untuk membuat repository local.
2.	git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
3.	git commit, perintah untuk menyimpan perubahan kedalam database git.
4.	git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
5.	git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
6.	git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).
7.	git pull, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository.
	


#TUTORIAL PENGGUNAAN GIT

1.	Buat folder terlebih dahulu di Windows Explorer.
2.	Untuk penggunaan git pertama masuk ke folder yang akan digunakan. Klik kanan dan pilih Git Bash.
Buat direktory project praktikum pertama dengan nama practice1. 

        $ mkdir latihan1 

        $ cd latihan1
	
	![Screenshot (9)](https://user-images.githubusercontent.com/72993076/96337430-5c604180-10b1-11eb-948f-677d1c0c20aa.png)

             
3.	Setelah itu, jalankan perintah git init, untuk membuat repository local.

        ![Screenshot (10)](https://user-images.githubusercontent.com/72993076/96337938-c9c1a180-10b4-11eb-8955-28d22b948d6e.png)

             
4.	Buat satu file bernama README.md.

        $ echo “# Practice 1” >> README.md

        File README.md berhasil dibuat.
	
        ![Screenshot (10)](https://user-images.githubusercontent.com/72993076/96337957-f37ac880-10b4-11eb-8191-cfce9e03649a.png)

             
5.	Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add.

        $ git add README.md

	File README.md berhasil ditambahkan.
	
       ![Screenshot (11)](https://user-images.githubusercontent.com/72993076/96338013-79970f00-10b5-11eb-9c33-7d20838d0af6.png)
             
6.	Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah 
git commit -m “komentar commit”.

        $ git commit -m “File pertama saya”
	
	![Screenshot (12)](https://user-images.githubusercontent.com/72993076/96337614-9d0c8a80-10b2-11eb-974e-0ab9998d350d.png)
	
	


7.	Untuk menambahkan remote repository server, gunakan perintah git remote add origin [url]

        $ git remote add origin https://github.com/asriliya/asriliyaa.git
	
        ![Screenshot (16)](https://user-images.githubusercontent.com/72993076/96338061-bb27ba00-10b5-11eb-9c72-280beb2db90e.png)
        

	

8.	Untuk mengirim perubahan pada local repository ke server gunakan perintah git push.

        $ git push -u origin master

	Perintah ini akan meminta memasukkan username dan password pada akun github.com
	
         ![Screenshot (17)](https://user-images.githubusercontent.com/72993076/96337969-186f3b80-10b5-11eb-8cf8-d3afc80a23b3.png)
	 
	 
 #Melihat hasilnya pada server repository
 
•	Buka laman github.com, arahkan pada repositorinya.

•	Maka perubahan akan terlihat pada laman tersebut

       ![Screenshot (18)](https://user-images.githubusercontent.com/72993076/96337981-36d53700-10b5-11eb-9fdc-b72641b80726.png)

 

9.	Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
Untuk melakukan cloning, gunakan perintah git clone [url].

