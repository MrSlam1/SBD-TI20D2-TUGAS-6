# SBD-TI20D2-TUGAS-6
Nama : Slamet <br>
NIM : 312010241 <br>
Kelas : TI20D2 <br>
# Daftar Tugas
1. Login Database <br>
2. Backup dan Recovery dengan SQL <br>
3. Backup dan Recovery dengan MySQLDUMP <br>
4. Menulis Script Cronjob <br>
# Backup dan Recovery Dengan SQL
<img src = 'login.png' img>
<img src = 'delete fk.png' img>
<img src = 'berobat.png' img>
<img src = 'dokter.png' img>
<img src = 'obat.png' img>
<img src = 'pasien.png' img>
<img src = 'resep.png' img>
<img src = 'users.png' img> <br>
# Backup dan Recovery dengan MySQLDUMP
<img src = 'mysqldump.png' img> <br>
# Script Cronjob
CRONTAB-E <br>
0 0 * * 0 MySQLDUMP –u root –p klinik_312010241 > b_klinik_312010241.sql
