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
