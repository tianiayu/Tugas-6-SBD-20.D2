# TUGAS 6

KONEKSI BACKUP & RESTORE PADA MYSQL

Soal.
1.	Masuk ke databse adminklinik
2.	Lakukan proses backup dan recovery dengan sql dari database tugas seblumnya !
3.	Lakukan proses backup dan recovery dengan sqldump dari database tugas seblumnya !
4.	Tulisakan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam ! 
5.	Buat laporanya dan kirimkan di form tugas 6

Jawab : 


1). Database Klinik :

<img src="" img>
            
2). Proses Backup dan Recovery dengan SQL

2.1). Proses Backup SQL : 

<img src="" img>

2.2). Proses Recovery SQL :

<img src="" img>

3). Proses Backup dan Recovery dengan SQLDump

3.1). Proses Backup SQLDump :

<img src="" img>

3.2). Proses Recovery SQLDump :

<img src="" img>


4). Scrip Cron Job Backup otomatis setiap hari minggu jam 12 malam :

"mysql -u adminklinik -p 312010098 klinik_312010098 > backup2.sql"
