## 1-資料清理數據前處理

### D1 資料介紹與評估資料
挑戰是什麼?動手分析前請三思

### D2 EDA-1/讀取資料EDA: Data summary
* 探索式資料分析(Exploratory Data Analysis，簡稱EDA)
* 如何讀取資料以及萃取出想要了解的信息

### D3 3-1如何新建一個 dataframe?
* 從頭建立一個 dataframe 
### 3-2 如何讀取其他資料? (非 csv 的資料)
* 如何讀取不同形式的資料 (如圖檔、純文字檔、json 等)

### D4 EDA: 欄位的資料類型介紹及處理
了解資料在 pandas 中可以表示的類型

### D5 EDA資料分佈
用統計方式描述資料

### D6 EDA: Outlier 及處理
偵測與處理例外數值點：
1. 透過常用的偵測方法找到例外 
2. 判斷例外是否正常 (推測可能的發生原因)

### D7 常用的數值取代：中位數與分位數連續數值標準化
偵測與處理例外數值 
1. 缺值或例外取代 
2. 數據標準化

### D8 DataFrame operationData frame merge/常用的 DataFrame 操作
1. 常見的資料操作方法 
2. 資料表串接

### D9 程式實作 EDA: correlation/相關係數簡介
1. 了解相關係數 
2. 利用相關係數直觀地理解對欄位與預測目標之間的關係

### D10 EDA from Correlation
深入了解資料，從 correlation 的結果下手

### D11 EDA: 不同數值範圍間的特徵如何檢視/繪圖與樣式Kernel Density Estimation (KDE)
1. 如何調整視覺化方式檢視數值範圍 
2. 美圖修修 - 轉換繪圖樣式

### D12 EDA: 把連續型變數離散化
EDA: 把連續型變數離散化

### D13 程式實作 把連續型變數離散化
深入了解資料，從簡化後的離散變數下手

### D14 Subplots
探索性資料分析 - 資料視覺化 - 多圖檢視 
1. 將數據分組一次呈現 
2. 把同一組資料相關的數據一次攤在面前

### D15 Heatmap & Grid-plot
探索性資料分析 - 資料視覺化 - 熱像圖 / 格狀圖 
1. 熱圖：以直觀的方式檢視變數間的相關性 
2. 格圖：繪製變數間的散佈圖及分布

### D16 模型初體驗 Logistic Regression
在我們開始使用任何複雜的模型之前，有一個最簡單的模型當作 baseline 是一個好習慣

## 2-資料科學特徵工程技術
### D17 特徵工程簡介
介紹機器學習完整步驟中，特徵工程的位置以及流程架構

### D18 特徵類型
特徵工程依照特徵類型，做法不同，大致可分為數值/類別/時間型三類特徵

### D19 數值型特徵-補缺失值與標準化
數值型特徵首先必須填補缺值與標準化，在此複習並展示對預測結果的差異

### D20 數值型特徵 - 去除離群值
數值型特徵若出現少量的離群值，則需要去除以保持其餘數據不被影響

### D21 數值型特徵 - 去除偏態
數值型特徵若分布明顯偏一邊，則需去除偏態以消除預測的偏差

### D22 類別型特徵 - 基礎處理
介紹類別型特徵最基礎的作法 : 標籤編碼與獨熱編碼

### D23 類別型特徵 - 均值編碼
類別型特徵最重要的編碼 : 均值編碼，將標籤以目標均值取代

### D24 類別型特徵 - 其他進階處理
類別型特徵的其他常見編碼 : 計數編碼對應出現頻率相關的特徵，雜湊編碼對應眾多類別而無法排序的特徵

### D25 時間型特徵
時間型特徵可抽取出多個子特徵，或周期化，或取出連續時段內的次數

## 3-機器學習基礎模型建立

## 4-機器學習調整參數

## 5-非監督式機器學習

## 6-深度學習理論與實作

## 7-初探深度學習使用 Keras

## 8-深度學習應用卷積神經網路
