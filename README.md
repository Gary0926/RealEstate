# 不動產實價登錄之應用—透過隨機森林進行房價預測

使用隨機森林進行房價預測

## 工作描述
- 數據處理：特徵轉換、處理空值與異常值，刪除不必要特徵，確保數據一致性。創造新特徵
- 資料視覺化：了解各特徵分布，判斷是否有離群值或異常值，或是資料是否有線性關係。
- 模型建立：使用隨機森林進行預測。
- 模型評估：使用 RMSE（均方根誤差）、MAE（平均絕對誤差）等指標來衡量模型的表現。
- 超參數調整：觀察 max_depth、n_estimators、max_features 等參數對預測結果的影響，透過 GridSearchCV 或 RandomizedSearchCV 找到最佳參數。
- 特徵重要性分析：分析哪些變數對於房價預測影響最大，例如「屋齡」、「建物型態」等。
- 成果展示：訓練好的隨機森林模型可用來預測未來房價。

## 資料來源：[內政部的不動產資料供應系統](https://plvr.land.moi.gov.tw/Login_input?authfailed=true#)
![不動產資料供應系統](photo/不動產資料供應系統.png)

## 使用技術與套件
- 數據處理：Numpy、Pandas
- 資料視覺化：Matplotlib
- 模型建立：scikit-learn、RandomForestRegressor、RandomizedSearchCV

