# 模型的表現監控 Performance Monitoring   

![Python](https://img.shields.io/badge/Python-3.10.12-blue.svg) ![Numpy](https://img.shields.io/badge/NumPy-1.26.4-range.svg) ![Pandas](https://img.shields.io/badge/Pandas-2.2.2-range.svg) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.1-range.svg) ![ScikitLearn](https://img.shields.io/badge/ScikitLearn-1.5.2-range.svg)     

### 前言  
在機器學習的實務中，ML 模型的訓練通常只是第一步，在 ML 模型訓練完成且部署上線後，如何確保 ML 模型在未知數據中，它的預測表現仍維持良好的水準，係保證 ML 模型的品質與長期有效的關鍵議題。

在迴歸問題中的模型監控，有下列二項重點 :  
- 在監控 ML 模型時，關注模型的預測能力指標，例如 : MAE、MAPE 等。  
- 在監控 ML 模型時，當預測能力指標超出預期的變大變差時，意味著兩種可能性 : 過擬合或模型飄移，後續皆須模型再訓練。
  

### ML 模型監控
- 概念說明與 Python 範例程式碼   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YenLinWu/Daily_Work_of_Data_Science/blob/Dev/Performance_Monitoring/Performance_Monitoring.ipynb)  :point_left:      
- [實務札記](https://medium.com/@yenlinwu1112/ml-performance-monitoring-6f414194bed3)  
- [ML 監控觀念與策略 - 隨手指南](https://github.com/YenLinWu/Daily_Work_of_Data_Science/blob/Dev/Performance_Monitoring/ML%E6%A8%A1%E5%9E%8B%E7%9B%A3%E6%8E%A7%E7%9A%84%E8%A7%80%E5%BF%B5%E8%88%87%E7%AD%96%E7%95%A5%E6%8C%87%E5%8D%97.pdf)  
      
</br>

Back to [資料科學的日常研究議題](https://github.com/YenLinWu/Daily_Work_of_Data_Science/blob/main/README.md#%E8%B3%87%E6%96%99%E7%A7%91%E5%AD%B8%E7%9A%84%E6%97%A5%E5%B8%B8)
