# simplephp_crud_step
Step by step install CRUD example of SimplePHP Framework

### 1. download 3 file zip dan 1 file sql
### 2. buat sebuah folder di xampp/htdocs, beri nama: webapp
### 3. copy ke-4 file hasil download ke dalam folder webapp
### 4. extract ke-3 file di dalam folder webapp dgn pilihan:
   extract here
### 5. buka folder webapp dengan VS Code
### 6. buka terminal di dalam VS Code, ketik:
```
composer require vlucas/phpdotenv
```
### 7. buka folder modul perawat:
   pindahkan file:
   Perawat.php -> folder controllers
   PerawatModel.php -> folder models   
   pindahkan folder: perawat -> root project
### 8. Buka phpmyadmin
Buat sebuah database baru, beri nama: webapp
### 9. Import tabel perawat.sql
### 10.Edit file .env
```
   DB_DATABASE=webapp
   BASE_URL=http://localhost/webapp/
```
simpan ulang file .env
### 11.Test di Browser:
```
http://localhost/webapp/perawat
```
