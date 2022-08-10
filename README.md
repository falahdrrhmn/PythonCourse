# PythonCourse

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
