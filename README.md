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

檔案：`hw3.ipynb`

- 主題：Fashion-MNIST 服飾分類 DNN
- 資料集：Fashion-MNIST，共 10 種服飾類別
- 網路結構：784 → 512 → 256 → 128 → 10
- Activation：ReLU、Softmax
- Loss：Categorical Crossentropy
- Optimizer：Adam
- 包含資料預處理、模型訓練、Accuracy、Loss、預測結果與 Confusion Matrix
- 測試資料準確率：約 90.16%
- 儲存訓練完成的模型
