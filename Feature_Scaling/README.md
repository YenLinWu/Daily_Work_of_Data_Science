# 特徵縮放 Feature Scaling  

![Python](https://img.shields.io/badge/Python-3.10.12-blue.svg) ![Numpy](https://img.shields.io/badge/NumPy-1.25.2-range.svg) ![Pandas](https://img.shields.io/badge/Pandas-1.5.3-range.svg) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.1-range.svg) ![Seaborn](https://img.shields.io/badge/Seaborn-0.13.1-range.svg) ![ScikitLearn](https://img.shields.io/badge/ScikitLearn-1.2.2-range.svg)   

### 前言  
在資料科學領域中，資料前處理的過程，係訓練模型前提升資料品質的關鍵步驟。特徵縮放(Feature Scaling)是資料前處理的其中一種技巧，它能幫助我們更客觀理解與比較數據，避免因為多個特徵間不同的數值範圍尺度，造成我們解讀與判斷的偏差，另外，對於一些基於距離或梯度收斂的機器學習演算法，特徵縮放也能提升模型的訓練效率，與確保模型的預測。   
  
以[紅酒資料集](https://archive.ics.uci.edu/dataset/109/wine)為範例，訓練一個支援向量分類 SVC 模型，其決策邊界會受到特徵的數值範圍所影響，藉由特徵縮放的前處理手法，能有效降低不同特徵的尺度對模型的影響，請參閱下圖。   

<p align="left">
      <img src="./imgs/Decision_Boundary_of_SVC_without_Standardization.png"  width="40%" height="40%">
      <img src="./imgs/Decision_Boundary_of_SVC_with_Standardization.png"  width="39%" height="39%">
</p>

### 特徵縮放的介紹與 Python 實作程式碼   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YenLinWu/Daily_Work_of_Data_Science/blob/Dev/Feature_Scaling/Feature_Scaling.ipynb)  :point_left:   
    
Back to [資料科學的日常研究議題](https://github.com/YenLinWu/Daily_Work_of_Data_Science/blob/Dev/README.md#%E7%A0%94%E7%A9%B6%E8%AD%B0%E9%A1%8C)
