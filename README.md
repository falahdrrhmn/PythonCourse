# Python Course

Baca file csv make python pandas
```py
import pandas as pd

csv_data = pd.read_csv(
    "https://storage.googleapis.com/dqlab-dataset/shopping_data.csv")

print(csv_data)
```
output nya data di file csvnya itu nanti

Baca file make heads
```py
# Membaca file dengan menggunakan head()
import pandas as pd

csv_data = pd.read_csv(
    "https://storage.googleapis.com/dqlab-dataset/shopping_data.csv")

print(csv_data.head())

csv_data = pd.read_csv(
    "https://storage.googleapis.com/dqlab-dataset/shopping_data.csv")

print(csv_data.head())

```

Melakukan akses data kolom

```py
# Melakukan akses data kolom
import pandas as pd

csv_data = pd.read_csv(
    "https://storage.googleapis.com/dqlab-dataset/shopping_data.csv")

print(csv_data["Age"])

```

Melakukan akses data baris
```py
# Melakukan akses data melalui baris

import pandas as pd

csv_data = pd.read_csv(
    "https://storage.googleapis.com/dqlab-dataset/shopping_data.csv")

print(csv_data.iloc[5])

```

Menampilkan suatu data dari baris dan kolom tertentu

```py
# Menampilkan suatu data dari baris dan kolom tertentu
import pandas as pd

csv_data = pd.read_csv(
    "https://storage.googleapis.com/dqlab-dataset/shopping_data.csv")

print(csv_data["Age"].iloc[1])
print("Cuplikan Dataset:")
print(csv_data.head())

```

Menampilkan data dalam range tertentu

```py
# Menampilkan data dalam range tertentu

import pandas as pd

csv_data = pd.read_csv(
    "https://storage.googleapis.com/dqlab-dataset/shopping_data.csv")

print("Menampilkan data ke 5 sampai kurang dari 10 dalam satu baris:")

print(csv_data.iloc[5:10])

```

Menampilkan informasi statistik dengan Numpy
```py
# Menampilkan informasi statistik dengan Numpy

import pandas as pd

csv_data = pd.read_csv(
    "https://storage.googleapis.com/dqlab-dataset/shopping_data.csv")

print(csv_data.describe(exclude=["O"]))

```

Tipe data python
```python
#tipe data Boolean
print(True)


#tipe data String
print("Ayo belajar Python")
print('Belajar Python Sangat Mudah di DQLAB')


#tipe data Integer
print(20)


#tipe data Float
print(3.14)


#tipe data List
print([1,2,3,4,5])
print(["satu", "dua", "tiga"])


#tipe data Tuple
print((1,2,3,4,5))
print(("satu", "dua", "tiga"))


#tipe data Dictionary
print({"nama":"Budi", 'umur':20})

#tipe data Dictionary dimasukan ke dalam variabel biodata
biodata = {"nama":"Andi", 'umur':21} #proses inisialisasi variabel biodata
print(biodata) #proses pencetakan variabel biodata yang berisi tipe data Dictionary
type(biodata) #fungsi untuk mengecek jenis tipe data. akan tampil <class 'dict'>
```

if statement python
```python
i = 10 #inisialisasi variable i yang memiliki nilai 10

if(i==10): #pengecekan nilai i apakah sama dengan 10
    print("ini adalah angka 10") #jika TRUE maka akan mencetak kalimat ini

```

```python
i = 10 #inisialisasi variable i yang memiliki nilai 10

if(i==10): #pengecekan nilai i apakah sama dengan 10
    print("ini adalah angka 10") #jika TRUE maka akan mencetak kalimat ini
else:
    print("bukan angka 10") #jika FALSE akan mencetak kalimat ini
```

```python
i = 5 #inisialisasi variable i yang memiliki nilai 10

if(i==10): #pengecekan nilai i apakah sama dengan 10
    print("ini adalah angka 10") #jika TRUE maka akan mencetak kalimat ini
else:
    print("bukan angka 10") #jika FALSE akan mencetak kalimat ini
```
