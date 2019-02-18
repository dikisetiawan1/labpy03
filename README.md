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

- [x] gunakan for range ,untuk mengulang data 

- [x] cetak data dan memasukan random.uniform kurang dari 0.5

- [x] jika selesai RUN/jalankan programnya.
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
- [x] masukan max=0

- [x] gunakan while True,untuk perulangan tak terbatas,setelah itu masukan bilangan.

- [x] if jika memasukan 0 akan berhenti

- [x] gunakan if untuk mencari nilai max=bilangan terbesar,lalu run/jalankan programnya.

![screenshot 23](https://user-images.githubusercontent.com/46512724/52930177-08500780-337a-11e9-8658-ba76fe9c3aec.png)


# **program1.py**
```python
a = 100000000

for x in range(1,9):
    if(x>=1 and x<=2):
        b = a*0
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
![screenshot 24](https://user-images.githubusercontent.com/46512724/52929895-d5594400-3378-11e9-8e0d-5cf9b69ef337.png)

