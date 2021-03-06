# 04 Import Package and Data

![covervideo](http://bit.ly/makeaicovervideo)

#### **Description :**

_Dataset untuk Latihan pada Bab ini bisa di download di : 
[athlete_events.csv](https://drive.google.com/file/d/1M5KLfA9DpVWiKqVQ9bwjFJWcl0yl-9TX/view?usp=sharing)_

Sebelum kita meng-import data lebih baik kita import package yang digunakan untuk Data Science yaitu pandas dan numpy. 

Data yang digunakan untuk Data Visulisasi kali ini yaitu menggunakan Olympic Games 1896 sampai 2016. 


```
import pandas as pd
import numpy as np

df = pd.read_csv('data/athlete_events.csv')
df.head()
```
*Output :*

| ID | Name                     | Sex | Age  | Height | Weight | Team           | NOC | Games       | Year | Season | City      | Sport         | Event                            | Medal |
|----|--------------------------|-----|------|--------|--------|----------------|-----|-------------|------|--------|-----------|---------------|----------------------------------|-------|
| 1  | A Dijiang                | M   | 24.0 | 180.0  | 80.0   | China          | CHN | 1992 Summer | 1992 | Summer | Barcelona | Basketball    | Basketball Men's Basketball      |       |
| 2  | A Lamusi                 | M   | 23.0 | 170.0  | 60.0   | China          | CHN | 2012 Summer | 2012 | Summer | London    | Judo          | Judo Men's Extra-Lightweight     |       |
| 3  | Gunnar Nielsen Aaby      | M   | 24.0 |        |        | Denmark        | DEN | 1920 Summer | 1920 | Summer | Antwerpen | Football      | Football Men's Football          |       |
| 4  | Edgar Lindenau Aabye     | M   | 34.0 |        |        | Denmark/Sweden | DEN | 1900 Summer | 1900 | Summer | Paris     | Tug-Of-War    | Tug-Of-War Men's Tug-Of-War      | Gold  |
| 5  | Christine Jacoba Aaftink | F   | 21.0 | 185.0  | 82.0   | Netherlands    | NED | 1988 Winter | 1988 | Winter | Calgary   | Speed Skating | Speed Skating Women's 500 metres |       |

Seperti yang terlihat bahwa data terdiri dari 15 variabel yaitu ID, Name, Sex, Age, dll.