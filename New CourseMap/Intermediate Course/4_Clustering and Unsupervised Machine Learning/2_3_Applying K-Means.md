# 2_3_Applying K-Means

![covervideo](http://bit.ly/makeaicovervideo)

#### **Description :**

Pada video kali ini kita akan melakukan pemodelan menggunakan K-Means berdasarkan data yang dimiliki menggunakan syntax sebagai berikut. 
```
model_kme = KMeans(n_clusters= 2)
model_kme_2 = KMeans(n_clusters= 4)

X = data_clu[['Distance_Feature','Speeding_Feature']]
model_kme.fit(X)
model_kme_2.fit(X)
```
```
pred_kme = model_kme.predict(X)
pred_kme_2 = model_kme_2.predict(X)
pred_kme
```
dari `pred_kme` tersebut maka kita dapat melihat hasil dari pemodelan _clustering_ yang telah kita buat.