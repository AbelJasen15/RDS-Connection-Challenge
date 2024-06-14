1. pertama kita memlilih RDS, kemnudia kita setup database dengan user dan password yang kita tentukan
2. setelah setup behasil, kemudian kita harus melihat settingan untuk network tersebut, apakah sudah 1 subnet dengan instance yang kita inginkan arahkan.
3. lalu masuk ke "Connected compute resources" arahkan db yang telah kita buat ke instance.
4. login ke instance dan coba untuk mengkoneksikan dengan rd yang telah kita buat
5. pastikan port database 3306
6. coba remote dengan perintah "mysql -h database-1.cxwy2y2my8cl.us-east-1.rds.amazonaws.com -P 3306 -u admin -p"
7. lalu masukan password yang telah kita setup di awal
--------------------------------------------------------------
<center><img src="https://raw.githubusercontent.com/AbelJasen15/RDS-Connection-Challenge/main/ss.ss.png" /></center>
