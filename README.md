# labpy03
# **latihan1.py**
```python
import random
n=str(input("masukan nilai N: "))
for x in range (1,6):
 print("data ke:",x,"=>",random.uniform(0.0,0.5))
print('selesai')
```
# **penjelasan algoritma**

- [x] masukan nilai N =5

- [x] gunakan for range (untuk mengulang data dari 1-5)

- [x] cetak data dan memasukan (random.uniform kurang dari 0.5)

- [x] jika selesai RUN/jalankan programnya.

# **output**
![screenshot 26](https://user-images.githubusercontent.com/46512724/52929877-c1154700-3378-11e9-98c2-b70862ae0ed4.png)

# **latihan2.py**
```python
max=0
while True:
	a=int(input("masukan bilangan:"))
	if a ==0:
		break
	if a>max:
		max=a
print("bilangan terbesar:",max)
```
# **penjelasan algoritma**
- [x] masukan max=0

- [x] gunakan while True (untuk perulangan tak terbatas. jika bilangan tersebut bukan nol ,maka akan terus berulang ).

- [x] gunakan if (jika memasukan bilangan nol maka perulangan  akan berhenti).

- [x] selanjutnya,gunakan if (untuk mencari nilai max = bilangan terbesar,lalu run/jalankan programnya).

# **output**

![screenshot 23](https://user-images.githubusercontent.com/46512724/52930177-08500780-337a-11e9-8658-ba76fe9c3aec.png)


# **program1.py**
```python
a = 100000000

for x in range(1,9):
    if(x>=1 and x<=2):
        b =a*0
        print("Laba Bulan ke-",x," :",b)
    if(x>=3 and x<=4):
        c=a*0.1
        print("Laba Bulan ke-",x," :",c)
    if(x>=5 and x<=7):
        d=a*0.5
        print("Laba Bulan ke-",x," :",d)
    if(x==8):
        e=a*0.2
        print("Laba Bulan ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\ntotal : ", total)     
```
# **penjelasan algoritma**
- [x] masukkan nilai a

- [x] gunakan for untuk perulangan dari 1 sampai 8

- [x] lalu gunakan if pertama untuk menentukan laba bulan ke 1 dan ke 2.masukan variabel (b) kalikan nilai (a) dengan data bulan 1 dan 2.
cetak (x) dan (b)

- [x] lalu gunakan if kedua untuk menentukan laba bulan ke 3 dan ke 4.masukan variabel (b) kalikan nilai (a) dengan data bulan 3 dan 4.
cetak (x) dan (c)

- [x] lalu gunakan if ketiga untuk menentukan laba bulan ke 5 sampai ke 7.masukan variabel (b) kalikan nilai (a) dengan data bulan 5 sampai 7.
cetak (x) dan (d)

- [x] lalu gunakan if keempat untuk menentukan laba bulan ke 8.masukan variabel (b) kalikan nilai (a) dengan data bulan 8.
cetak (x) dan (e)

- [x] lalu total keseluruhan.

- [x] cetak total



# **output**
![screenshot 24](https://user-images.githubusercontent.com/46512724/52929895-d5594400-3378-11e9-8e0d-5cf9b69ef337.png)

