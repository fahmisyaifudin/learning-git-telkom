# Belajar Git Telkom Web Developer

## Install GIT

Linux 

```bash
apt-get install git
```
Windows [Download] (https://git-scm.com/download/win)

Konfigurasi Awal

```bash
git config --global user.name "Fahmi Syaifudin"
git config --global user.email fahmisyaifudin@example.com
```

## Membuat Repository Awal di Github

1. Klik New Repository

![image] (/img/1.png)

2. Berikan nama dan deskripsi (optional) pada repository, centang public/private, aku centang public agar repository ini bisa diakses semua orang

![image] (/img/2.png)

3. Tulis perintah berikut pada Git bash (windows), terminal (linux)

```bash
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/fahmisyaifudin/learning-git-telkom.git
git push origin master
```
(sesuaikan dengan nama project sampeyan ya...)

## Clone (Mengambil Repository dari Github)

git clone https://github.com/fahmisyaifudin/learning-git-telkom.git

(kita pakek https aja ya)
                
## Practice


### Practice 1
1. Silahkan clone project ini https://github.com/fahmisyaifudin/learning-git-telkom.git
2. Tambahkan Perubahan pada PANITIA.md dan tulis nama kalian disitu
3. Commit dan push ke master
4. Tulis analisa dari percobaan diatas :)

### Practice 2
1. Pada direktori yang sama, silahkan pull pada branch master

```bash
git pull origin master
```
2. Tulis analisa dari percobaan diatas :)

### Practice 3
1. Buat branch baru beri nama "revisi-namakalian"

```bash
git checkout -b "revisi-namakalian"
```

2. Rubah isi proposal bebas bisa di content/LATARBELAKANG.md, content/TUJUAN.md, content/PELAKSANAAN.md, content/BIAYA.md

3. Push branch kalian ke repository ku

```bash
git push origin "revisi-namakalian"
```