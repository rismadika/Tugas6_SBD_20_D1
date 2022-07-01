# TUGAS 6
* Nama      : Risma Dika Alvianti
* Nim       : 312010051
* kelas     : TI.20.D1
* Matkul    : Sistem Basis Data TUgas ke 6

# Soal
1. masuk ke database nama nim
2. lakukan proses backup dan recovery dengan sql
3. lakukan proses backup dan recovery dengan sqldump
4. tuliskan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam

# jawaban
1. masuk ke database risma_dika_alvianti_312010069

![p](ss/ss1.png)

2. lakukan proses backup dan recovery dengan sql

* proses backup :
![p](ss/ss2.png)

* data backup terdapat pada file c:\xampp/mysql\data\risma_dika_alvianti_312010051
!![p](ss/ss3.png)

* proses recovery :

* hapus tabel dan mencoba menampilkan tabel : 
![p](ss/ss4.png)

* kemudian hapus tabel dan dicoba lagi menampilakn tabel :
![p](ss/ss5.png)

3. lakukan proses backup dan recovery dengan sqldump

* proses backup :
![p](ss/ss6.png)

* proses recovery :
![p](ss/ss7.png)

![p](ss/ss8.png v)

4. tuliskan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam

* crontab –e
0 0 * * 7 myqldump -u root -p risma_dika_alvianti_312010051 > mahasiswa_312010051_backupdata2.sql

