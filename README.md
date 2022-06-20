                                                                       LAPORAN PRAKTIKUM 13
                                                                 FRAMEWORK LANJUTAN (MODUL LOGIN)
                                                                         PEMROGRAMAN WEB
Nama		: Rafi Hanif R.
NIM		: 312010358
Kelas		: TI.20.A.2
Mata Kuliah	: Pemrograman Web

PENDAHULUAN
Segala Puji bagi Tuhan Semesta Alam yang telah memberikan kita berbagai macam ni’mat yaitu Ni’mat Iman, Ni’mat Islam, serta Ni’mat sehat Wal ‘afiat sehingga saya bisa menyusun Laporan Praktikum 13 ini dengan baik dan benar. Dan semoga saya sendiri dan para dosen juga selalu di dalam lindungan-Nya, Aamin yarabbal ‘aalamiin.
Dalam pembuatan Laporan Praktikum 13 ini
TUJUAN
1.	Mahasiswa mampu memahami konsep dasar Auth dan Filter. 
2.	Mahasiswa mampu memahami konsep dasar Login System. 
3.	Mahasaswa mampu membuat modul login menggunakan Framework Codeigniter 4. 

LANDASAN TEORI 

BAHAN-BAHAN
-	Visual Studio Code
-	Xampp (Apache dan MySQL)
-	Google Chrome
CARA-CARA 
1.	Buka Xampp Control Panel dan aktifkan pada bagian Apache dan MySQL seperti dibawah berikut.
 ![image](https://user-images.githubusercontent.com/102600434/174604739-5e6b92e3-5777-41d3-a3ac-11ed6ab641dc.png)

2.	Kemudian buka browser dan ketik http://localhost/phpmyadmin untuk membuat database dan tabel, lalu ketik seperti dibawah ini untuk membuat database baru lalu klik go, setelah itu klik database yang bernama “login” > lalu klik SQL dan ketik kode untuk membuat tabelnya > lalu klik go jika sudah selesai.
![image](https://user-images.githubusercontent.com/102600434/174604784-a3f6ee2c-7052-4d4c-bf82-1d7ab604dbab.png)        ![image](https://user-images.githubusercontent.com/102600434/174604817-81d6385e-195e-4fc6-ba8f-68897383d96f.png)

![image](https://user-images.githubusercontent.com/102600434/174604858-4fe8de8d-d7fc-456f-bb3d-42616bf86de0.png)        ![image](https://user-images.githubusercontent.com/102600434/174604918-0210f312-b6ec-4ca3-960c-2c4e16aab15d.png)
  
![image](https://user-images.githubusercontent.com/102600434/174604948-63f5dba3-fff9-4c59-8b14-0259ddc360a1.png)

3.	Buka Visual Studio Code lalu buatlah file baru dengan nama UserModel.php didalam folder lab11_ci/ci4/app/Models seperti dibawah ini, lalu ketikkan kodenya seperti berikut.
    ![image](https://user-images.githubusercontent.com/102600434/174605016-3a242045-4dcb-42b9-858b-20d120826e11.png)    ![image](https://user-images.githubusercontent.com/102600434/174605060-05e92f9e-5be9-4e18-bcff-625df85f953b.png)

    ![image](https://user-images.githubusercontent.com/102600434/174605088-0d1d1021-e4c3-4469-860a-ff7b1e34b9a0.png)    ![image](https://user-images.githubusercontent.com/102600434/174605134-e557d2d1-fadf-4a63-93a8-87b54a38fb37.png)

    ![image](https://user-images.githubusercontent.com/102600434/174605163-13a695a4-e2eb-464c-b96b-ec24904a75a7.png)

 
Lalu save dengan cara menekan shortcut pada keyboard CTRL + S 

4.	Kemudian untuk membuat Controller User baru, buatlah file baru dengan nama User.php didalam folder lab11_ci/ci4/app/Controller seperti dibawah ini, lalu ketikkan kodenya seperti berikut.
    ![image](https://user-images.githubusercontent.com/102600434/174605271-27940d29-3cf7-4c80-9b80-cd2c665a5de5.png)       ![image](https://user-images.githubusercontent.com/102600434/174605343-8caf73d2-2875-4adf-ab5e-d51b6a7962b2.png)

    ![image](https://user-images.githubusercontent.com/102600434/174605369-bfcce51b-3116-4076-abfb-cc191f084c6d.png)       ![image](https://user-images.githubusercontent.com/102600434/174605476-74aac26f-6394-4d3e-a437-465f9ab57a79.png)

    ![image](https://user-images.githubusercontent.com/102600434/174605516-02d27549-e6db-40ec-ab1c-9272c2c63b67.png)
    
    ![image](https://user-images.githubusercontent.com/102600434/174605575-746bb5fd-cef1-40f0-acf6-251598dd6e33.png)

Lalu save dengan cara menekan shortcut pada keyboard CTRL + S 

5.	Untuk membuat View Login buat folder baru dengan nama User didalam folder lab11_ci/ci4/app/Views dibawah ini kemudian buat file dengan nama login.php lalu ketikkan kodenya seperti berikut.
    ![image](https://user-images.githubusercontent.com/102600434/174605650-b47fda42-2460-43ba-a2cc-f79e3115ee47.png)        ![image](https://user-images.githubusercontent.com/102600434/174605690-957422cc-5ac4-4b8b-a4ee-c200dc30847b.png)

    ![image](https://user-images.githubusercontent.com/102600434/174605721-1f2bd1b6-6f4b-4dcf-9c5f-f1838e7deca8.png)        ![image](https://user-images.githubusercontent.com/102600434/174605812-db5a6d4b-2e1c-41ba-a0db-0ce49af490e1.png)

    ![image](https://user-images.githubusercontent.com/102600434/174605858-93492900-797e-45ae-8ba3-a92f949ea480.png)
    
    ![image](https://user-images.githubusercontent.com/102600434/174605958-90c504b3-20c0-494e-8b07-da8e91e34cb9.png)
  
Lalu save dengan cara menekan shortcut pada keyboard CTRL + S

KESIMPULAN




