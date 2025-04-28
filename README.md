# Arsitektur-Multiprocessor
![image](https://github.com/user-attachments/assets/9d4280d0-9c48-4181-8bd7-6496e3e04990)
## Arsitektur multiprosessor terdiri dari dua jenis:
## 1. Multiprocessing Simetris
Penjelasan: Pada arsitektur ini, semua prosesor (CPU) memiliki akses yang sama ke memori utama (MEM) melalui jalur bus yang sama. Masing-masing CPU memiliki cache sendiri untuk menyimpan data sementara, yang mempercepat akses data yang sering digunakan.

Fungsi:

Semua prosesor memiliki peran yang setara (simetris) dan mampu menjalankan tugas yang sama.

Digunakan untuk sistem yang memerlukan kinerja tinggi, seperti server, karena setiap prosesor dapat bekerja secara paralel.

## 2. Multiprocessing Asimetris
Penjelasan: Dalam arsitektur ini, terdapat CPU utama (Main CPU) yang mengendalikan akses ke memori utama dan bertugas mengoordinasikan pekerjaan. Prosesor lainnya adalah sub-CPU, yang memiliki memori lokal masing-masing untuk menyimpan data terkait tugas mereka.

Fungsi:

Main CPU berfungsi sebagai pengendali utama, sedangkan sub-CPU digunakan untuk tugas tertentu (spesialisasi).

Cocok untuk sistem tertanam (embedded systems) di mana beberapa tugas dapat dikhususkan untuk prosesor tertentu.
