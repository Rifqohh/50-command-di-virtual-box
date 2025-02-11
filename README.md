# 50 Command di Ubuntu

Dokumentasi ini mencakup 50 perintah penting yang sering digunakan di Ubuntu, lengkap dengan deskripsi dan screenshot.

## 📂 Dasar Navigasi & Manipulasi File
1. **pwd** – Menampilkan direktori saat ini  
   ![pwd](https://github.com/user-attachments/assets/aed090eb-3e2a-445b-ae17-02ef750ceca2)
2. **ls** – Menampilkan daftar file dalam direktori  
   ![ls](https://github.com/user-attachments/assets/48e9f778-2fc8-4c64-8dae-ee0e2e4c49f9)
3. **cd [direktori]** – Pindah ke direktori lain  
   ![cd](https://github.com/user-attachments/assets/c8c630e6-1dc0-4ada-8042-2d91363bbe2d)
4. **mkdir [nama_folder]** – Membuat folder baru  
   ![mkdir](https://github.com/user-attachments/assets/56a570af-d75e-45f4-b26b-01d11ffc63e6)
5. **rmdir [nama_folder]** – Menghapus folder kosong  
   ![rmdir](https://github.com/user-attachments/assets/677da3e5-de5b-4372-8d84-7b21863400b2)
6. **rm [nama_file]** – Menghapus file  
   ![rm](https://github.com/user-attachments/assets/8413c00c-9078-4be8-b42a-805f36ec9cc7)
## Pengelolaan File & Teks
11. cat [nama_file] – Menampilkan isi file
    ![Screenshot from 2025-02-11 15-44-12](https://github.com/user-attachments/assets/9cc5bbde-f8fd-435d-83c3-0956794ef364)
12. head [nama_file] – Menampilkan beberapa baris pertama file
    ![Screenshot from 2025-02-11 15-44-54](https://github.com/user-attachments/assets/1e849674-ba50-49b9-86db-2f7ee2dd392a)
13. tail [nama_file] – Menampilkan beberapa baris terakhir file
    ![Screenshot from 2025-02-11 15-46-28](https://github.com/user-attachments/assets/6d42baad-3365-4180-916d-e6925a9bfbf5)
14. nano [nama_file] – Mengedit file dengan Nano
    ![Screenshot from 2025-02-11 15-49-09](https://github.com/user-attachments/assets/b1b9cce0-b5cb-4701-a304-e32eb799575c)
15. vim [nama_file] – Mengedit file dengan Vim
    ![Screenshot from 2025-02-11 15-49-47](https://github.com/user-attachments/assets/8f1a60e4-2606-47f8-83a5-75770fd88683)
16. echo "teks" > file.txt – Menulis teks ke file
    ![Screenshot from 2025-02-11 15-51-45](https://github.com/user-attachments/assets/ce73fc20-4884-4bc4-ba5f-37abe4738b09)
17. echo "teks" >> file.txt – Menambahkan teks ke file
    ![image](https://github.com/user-attachments/assets/adbe9259-ed26-4d35-901f-c4cacd27d3bd)
18. grep "kata" file.txt – Mencari kata dalam file
    ![image](https://github.com/user-attachments/assets/5ad700de-a3a1-4bd7-af94-eb8467facdda)
19. find /path -name "file.txt" – Mencari file dalam direktori
    ![image](https://github.com/user-attachments/assets/d26101f9-3f0e-4135-bb7e-e8b6ff2eaeba)
20.  locate file.txt – Mencari file di sistem
    ![Screenshot from 2025-02-11 15-56-17](https://github.com/user-attachments/assets/b00e0427-e69d-4b18-bcfa-d9645b68c697)
## Manajemen Sistem
21. whoami – Menampilkan user yang sedang login
    ![Screenshot from 2025-02-11 16-02-38](https://github.com/user-attachments/assets/15182b15-9929-4ed6-a51c-0d0d70817bac)
22. who – Menampilkan user yang sedang login ke sistem
    ![Screenshot from 2025-02-11 16-03-06](https://github.com/user-attachments/assets/9435f2dc-5d09-4c42-907e-ad8a76105c66)
23. id – Menampilkan informasi user ID dan grup
    ![image](https://github.com/user-attachments/assets/587dc005-f449-4264-b5d6-cc38d26a8464)
24. uname -a – Menampilkan informasi sistem
    ![image](https://github.com/user-attachments/assets/441ecfb0-e5ac-40cb-880e-2f964699dd36)
25. df -h – Menampilkan penggunaan disk
    ![Screenshot from 2025-02-11 16-05-28](https://github.com/user-attachments/assets/1319c16e-85e2-4959-ad46-0c6ace609535)
26. du -sh [folder] – Menampilkan ukuran folder
    ![Screenshot from 2025-02-11 16-07-03](https://github.com/user-attachments/assets/4faf0b90-30b3-48c7-b35e-20c88b1aebb8)
27. top – Menampilkan proses yang berjalan
    ![image](https://github.com/user-attachments/assets/badd79d3-f07d-4909-85d0-ad4e0a7e4d7d)
28.  htop – Menampilkan proses dalam tampilan interaktif
    ![image](https://github.com/user-attachments/assets/b8dcbc02-b202-4d61-b365-c8d7842f2f8a)
29. ps aux – Menampilkan daftar proses yang berjalan
    ![Screenshot from 2025-02-11 16-10-10](https://github.com/user-attachments/assets/ba83f604-f4c8-462d-b3a0-364d26bf4ba0)
30. kill [PID] – Menghentikan proses berdasarkan PID
    ![Screenshot from 2025-02-11 16-10-45](https://github.com/user-attachments/assets/31bf6372-e278-405e-8055-288bc66b47f0)
## Jaringan & Keamanan
31. ping google.com – Mengecek koneksi internet
    ![Screenshot from 2025-02-11 16-11-58](https://github.com/user-attachments/assets/e79bac77-6686-4895-9faa-e1ca7ab807ef)
32. wget [URL] – Mengunduh file dari URL
   ![Screenshot from 2025-02-11 16-11-58](https://github.com/user-attachments/assets/b3ca2178-14c2-40ae-81d5-866ecc0df390)
33. curl [URL] – Mengakses konten dari URL
    ![image](https://github.com/user-attachments/assets/ce350bd6-9824-4f2e-a94e-a8fb973a74a3)
34. ifconfig – Menampilkan konfigurasi jaringan
 ![Screenshot from 2025-02-11 16-13-39](https://github.com/user-attachments/assets/538656b4-46ee-44fe-909b-c7a2737ba685)
35. ip a – Menampilkan informasi IP address
    ![Screenshot from 2025-02-11 16-14-15](https://github.com/user-attachments/assets/729151fd-a832-4d9e-98a6-5a7eeef2240f)
36. netstat -tulnp – Menampilkan port yang digunakan
    ![Screenshot from 2025-02-11 16-14-51](https://github.com/user-attachments/assets/a351aa1b-4fa3-4753-baa1-acf4efcd824d)
37. ssh user@ip_address – Masuk ke server melalui SSH
    ![Screenshot from 2025-02-11 16-15-35](https://github.com/user-attachments/assets/08f2cb7d-0afa-4b53-8faa-ff3f840a4a75)
38. scp file user@ip:/path – Mengirim file melalui SSH
    ![Screenshot from 2025-02-11 16-16-12](https://github.com/user-attachments/assets/975dcfdb-6e50-4670-a35a-aea120c1da3c)
39. ufw enable – Mengaktifkan firewall
    ![Screenshot from 2025-02-11 16-17-07](https://github.com/user-attachments/assets/c1f57b2c-d96f-431d-86a9-95a5d9e04c53)
40. ufw allow 22 – Membuka port 22 (SSH)
    ![image](https://github.com/user-attachments/assets/e42ea6f6-2590-4af8-95a2-bb6d29b95ccc)
## Manajemen Paket & Pengguna
41. sudo apt update – Memperbarui daftar paket
   ![Screenshot from 2025-02-11 16-20-20](https://github.com/user-attachments/assets/5a9c0d01-b872-48d4-96a4-2b0f90cc0859)
42. sudo apt upgrade – Menginstal pembaruan sistem
    ![image](https://github.com/user-attachments/assets/c29809a7-672a-47ae-b14d-f9ab8fc2bb6a)
43. sudo apt install [paket] – Menginstal paket
    ![Screenshot from 2025-02-11 16-24-24](https://github.com/user-attachments/assets/475e2e44-dc90-46d3-91b3-86b8af120677)
44. sudo apt remove [paket] – Menghapus paket
    ![Screenshot from 2025-02-11 16-24-55](https://github.com/user-attachments/assets/c06ba44b-daaf-4932-80ff-9bc8dba365ce)
45. dpkg -i [file.deb] – Menginstal paket dari file .deb
    ![Screenshot from 2025-02-11 16-26-59](https://github.com/user-attachments/assets/76c14ab5-f8f6-4750-88fd-85498a20a86d)
46. snap install [paket] – Menginstal aplikasi dari Snap
    ![Screenshot from 2025-02-11 16-28-13](https://github.com/user-attachments/assets/21cb8451-03c5-4243-aad0-737fb0a67423)
47. adduser [username] – Menambah user baru
    ![Screenshot from 2025-02-11 16-28-59](https://github.com/user-attachments/assets/779610ae-9a3a-4bb5-9f10-22ce06f06158)
48. deluser [username] – Menghapus user
    ![image](https://github.com/user-attachments/assets/58f21cfd-8555-44fe-b239-74b9b45727e7)
49.  passwd [username] – Mengubah password user
    ![image](https://github.com/user-attachments/assets/93a47be9-edd7-4729-9f4d-132d84aeb072)
50. history – Menampilkan daftar command yang sudah digunakan
    ![Screenshot from 2025-02-11 16-31-25](https://github.com/user-attachments/assets/d02e3c48-43fd-49b4-a062-fa4eab84036e)


    
