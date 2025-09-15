# 50 Perintah Linux Red Hat dan Cara Pengujiannya  

📌 **Mata Kuliah:** Sistem Operasi  
👤 **Nama:** Novira Alya Mischa  
🆔 **NIM:** 09011182429007  
🏫 **Kelas:** SK3A  

---

## 📖 Deskripsi  
Repository ini berisi dokumentasi mengenai **50 perintah dasar Linux (Red Hat)** beserta cara pengujiannya.  
Materi ini dibuat sebagai tugas mata kuliah **Sistem Operasi**.  

---

## 📂 50 Perintah Linux  


# 1. Melihat direktori saat ini
pwd

# 2. Melihat isi direktori
ls

# 3. Melihat isi direktori dengan detail
ls -l

# 4. Melihat file tersembunyi
ls -a

# 5. Membuat direktori
mkdir namafolder

# 6. Membuat direktori sekaligus dalam satu jalur
mkdir -p folder1/folder2/folder3

# 7. Pindah direktori
cd namafolder

# 8. Kembali ke direktori sebelumnya
cd ..

# 9. Membuat banyak file sekaligus
touch file1.txt file2.txt file3.txt

# 10. Membuat file kosong
touch namafile.txt

# 11. Menulis isi file
echo "isi teks" > file.txt

# 12. Menambah isi file tanpa menghapus
echo "tambahan teks" >> file.txt

# 13. Melihat isi file
cat file.txt

# 14. Melihat isi file per halaman
less file.txt

# 15. Menampilkan 1 baris pertama file
head -n 1 file.txt

# 16. Menampilkan 1 baris terakhir file
tail -n 1 file.txt

# 17. Menampilkan isi file secara real-time
tail -f file.txt

# 18. Menyalin file
cp file1.txt file2.txt

# 19. Menyalin direktori
cp -r folder1 folder2

# 20. Memindah/rename file
mv file1.txt filebaru.txt

# 21. Menghapus file
rm file.txt

# 22. Menghapus folder kosong
rmdir folderkosong

# 23. Menghapus folder berisi file
rm -r namafolder

# 24. Melihat manual perintah
man ls

# 25. Melihat waktu sekarang
date

# 26. Melihat kalender
cal

# 27. Melihat siapa yang login
who

# 28. Melihat nama user saat ini
whoami

# 29. Melihat informasi user
id

# 30. Melihat semua user yang login
w

# 31. Melihat sistem sedang dipakai siapa saja
users

# 32. Melihat sistem hostname
hostname

# 33. Melihat IP address
ifconfig

# 34. Mengecek koneksi internet
ping google.com

# 35. Mengetahui lokasi file
find / -name file.txt

# 36. Mengetahui letak perintah
which ls

# 37. Melihat proses yang berjalan
ps aux

# 38. Menampilkan nama kernel
uname

# 39. Menampilkan lama system berjalan
uptime

# 40. Menampilkan penggunaan disk
df -h

# 41. Menampilkan ukuran folder/file
du -sh namafolder

# 42. Mengecek memori
free -h

# 43. Mengecek versi kernel
uname -r

# 44. Mengecek semua detail kernel
uname -a

# 45. Mengecek versi OS
cat /etc/os-release

# 46. Menampilkan daftar perangkat block
lsblk

# 47. Melihat shell yang digunakan
echo $SHELL

# 48. Menampilkan jumlah baris, kata, dan karakter pada file
wc file.txt

# 49. Mengecek variable PATH
echo $PATH

# 50. Membersihkan layar terminal
clear
