# 2026_DL_hws

深度學習課程作業。

## Homework 1

- 檔案：`hw1.ipynb`
- 主題：多層隱藏層全連接神經網路（DNN）
- 網路結構：6 → 5 → 4 → 4 → 3
- Activation：ReLU、ReLU、Sigmoid、Softmax
- 包含 Cross Entropy Error、`dnn(x)` 函數與 Gradio 互動介面

## Homework 2

- 檔案：`hw2.ipynb`
- 主題：批次輸入的多層全連接神經網路
- 輸入資料：5 筆資料，每筆 6 個特徵值
- 網路結構：6 → 5 → 4 → 4 → 3
- Activation：ReLU、ReLU、Sigmoid、Softmax
- 使用批次方式計算前向傳播
- 包含批次 Softmax 與平均 Cross Entropy Error

## Homework 3

- 檔案：`hw3.ipynb`
- 主題：Fashion-MNIST 服飾分類 DNN
- 資料集：Fashion-MNIST，共 10 種服飾類別
- 網路結構：784 → 512 → 256 → 128 → 10
- Activation：ReLU、Softmax
- Loss：Categorical Crossentropy
- Optimizer：Adam
- 包含資料預處理、模型訓練、Accuracy、Loss、預測結果與 Confusion Matrix
- 測試資料準確率：約 90.16%
- 儲存訓練完成的模型

## Homework 4

- 主題：CIFAR-10 圖片分類 CNN
- 資料集：CIFAR-10，共 10 種圖片類別
- Loss：Categorical Crossentropy
- Optimizer：Adam
- 包含資料預處理、模型訓練、Accuracy、Loss、預測結果與 Confusion Matrix

### HW4-1

- 檔案：`hw4-1.ipynb`
- 主題：建立基本 CNN 分類模型
- 訓練次數：20 epochs
- 測試資料準確率：約 63.97%

### HW4-2

- 檔案：`hw4-2.ipynb`
- 主題：修改 CNN 架構並加入 Dropout
- 網路架構：11 層 CNN
- 訓練次數：20 epochs
- 測試資料準確率：約 70.23%

### HW4-3

- 檔案：`hw4-3.ipynb`
- 主題：建立較深層的 CNN 模型
- 網路架構：19 層 CNN
- 訓練次數：50 epochs
- 測試資料準確率：約 77.10%

### 模型比較

| 模型 | Test Accuracy | Test Loss |
|---|---|---|
| HW4-1 | 63.97% | 1.5692 |
| HW4-2 | 70.23% | 0.9742 |
| HW4-3 | 77.10% | 0.7425 |

三個模型的測試準確率依序提高，其中 HW4-3 的準確率最高，但訓練後期仍有過度擬合的情況。
