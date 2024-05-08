# 機器學習模型指標的關係 - 迴歸問題 

![Python](https://img.shields.io/badge/Python-3.10.12-blue.svg) ![Numpy](https://img.shields.io/badge/NumPy-1.23.5-range.svg) ![Pandas](https://img.shields.io/badge/Pandas-1.5.3-range.svg) ![Matplotlib](https://img.shields.io/badge/Matplolib-3.7.1-range.svg) ![ScikitLearn](https://img.shields.io/badge/ScikitLearn-1.2.2-range.svg)   

### 目的  
針對機器學習模型的解釋能力指標 R2 與預測能力指標 MAE、RMSE，探討兩能力指標的相對應大小關係，以協助大家在訂定指標的目標時，能有明確的概念且訂定出更具體適用的指標目標。

### 指標間的關係
- MAE 小於等於 RMSE
- MAE/Sigma 小於等於 (1-R2)^(1/2)  
  關係推導與 Python 範例程式碼   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YenLinWu/Daily_Work_of_Data_Science/blob/Dev/MAE_and_R2/MAE_Sigma_R_Squared.ipynb)  :point_left:  
  
<p align="left">
      <img src="./imgs/MAE_Sigma_R2.png"  width="60%" height="60%">
</p>
  
- 機器學習迴歸問題中，模型指標的目標訂定，建議步驟 :    
  Step 1: 決定解釋能力指標的下限目標  
  Step 2: 計算預測誤差 MAE/Sigma 的最大範圍  
  Step 3: 決定預測誤差 MAE/Sigma 的目標範圍  

      
Back to [資料科學的日常研究議題](https://github.com/YenLinWu/Daily_Work_of_Data_Science/blob/main/README.md#%E8%B3%87%E6%96%99%E7%A7%91%E5%AD%B8%E7%9A%84%E6%97%A5%E5%B8%B8)
