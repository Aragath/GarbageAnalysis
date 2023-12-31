# 垃圾數據分析


https://github.com/Aragath/GarbageAnalysis/assets/54591654/82802847-de9e-4d7c-a766-6f3a2b485077


https://github.com/Aragath/GarbageAnalysis/assets/54591654/0c0a6545-6867-4ae5-978c-ca693fd6db6f



## Target
使用PLOTLY和DASH將111年臺南市資源回收成果統計做可視化

## Datasets
### 來源：
取得自政府資料開放平臺中之[臺南市資源回收成果統計(111年)](https://data.gov.tw/dataset/150240)頁面，提供機構為臺南市政府環境保護局

### 介紹：
上述頁面提供111年間每個月在不同類型的垃圾與其回收方式的重量統計，共12個月、23種垃圾類型，與3種回收方式：
* 類型：紙類、紙容器、鋁箔包、鋁容器、鐵容器、其他金屬製品、塑膠容器、包裝用發泡塑膠、其他塑膠製品、輪胎、玻璃容器、其他玻璃製品、照明光源、乾電池、鉛蓄電池、家電、資訊物品、光碟片、行動電話(含充電器)、農藥容器及特殊環境用藥容器、舊衣類、食用油、其他
* 回收方式：環保單位自行清運、環保單位委託清運、公私處所自行或委託清運

## 內容：
### Garbage Analysis - Static
由於使用PLOTLY時的結果無法在Github上呈現，因此這裡將圖表由可互動轉為靜止，方便閱讀。而DASH部分由於需要建立Flask app，則需將整個筆記本下載後在local端使用

### Garbage Analysis
為主要筆記本，可將url複製後至[nbviewer](https://nbviewer.org/)呈現，即可使用PLOTLY的互動圖表。而同樣DASH部分由於需要建立Flask app，則需將整個筆記本下載後在local端使用。
