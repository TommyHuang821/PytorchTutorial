# PytorchTutorial 實作課程

課程內容皆以jupyter note方式呈現。

## Class 0: 數據型態簡介<br>
**內容概述:** <br>
- 結構化數據和非結構化數據簡介<br>

*教材: [Data Structure.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/00_Data%20Structure.ipynb) <br>

## Class 1: 資料庫取得 <br>
**內容概述:** <br>
主要介紹公開資料(UCI database，kaggle等)的來源，和怎麼用pytorch來讀取/下載pytorch內建的資料庫<br>
1. 開源結構化數據範例: scikit-learn
2. Pytorch平台提供的數據範例torchvision
3. 私有結構化資料(Iris Dataset)
4. 私有非結構化資料(水果資料庫)

*教材: [database.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/01_database.ipynb) <br>


## Class 2: 利用Pytorch建立Dataset和Dataloader<br>
**內容概述:** <br>
怎麼利用pytorch建立自有資料集的dataset和dataloader<br>

1. Pytorch dataloader: 讀取結構化資料<br>
*教材: [Dataloader-1_Structure data.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/02_Dataloader-1_Structure%20data.ipynb) <br>

2. Pytorch dataloader: 讀取非結構化資料<br>
 2.1 當dataset是torch vision提供的寫法<br>
 2.2 當dataset是私有資料庫的寫法。<br>
 2.3 如何將資料丟到CUDA<br>
 
*教材: [Dataloader-2_CustomDataset.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/02_Dataloader-2_CustomDataset.ipynb) <br>
   補充資料:[pytorch_dataloader_linux.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/02_pytorch_dataloader_linux.ipynb)

## Class 3: 利用Pytorch進行梯度下降更新<br>
**內容概述:** <br>
怎麼利用pytorch的函數進行梯度計算，和梯度更新<br>

*教材: [pytorch_Gradient.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/03_pytorch_Gradient.ipynb) <br>

## Class 4: 在pytorch建立卷積、池化和激活函數和自定義運算架構方式<br>
**內容概述:** <br>
怎麼利用pytorch的函數進行梯度計算，和梯度更新<br>
1. Pytorch-卷積運作與參數生成<br>
*教材: [04_pytorch_operators_conv.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/04_pytorch_operators_conv.ipynb) <br>

2. Pytorch- Pool、Activation function和宣告自己想建立的結構<br>
*教材: [04_pytorch_operators.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/04_pytorch_operators.ipynb) <br>

## Class 5: 利用Pytorch模組torchvision進行資料擴增(Data Augmentation)<br>
**內容概述:** <br>
怎麼利用Pytorch提供之torchvision data augumentation技巧進行資料擴增<br>

*教材: [Pytorch_dataAug.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/05_Pytorch_dataAug.ipynb) <br> 

## Class 6: Pytorch進行圖像分類模型訓練<br>
**內容概述:** <br>
1. Pytorch進行圖像分類: 利用MLP和CNN模型進行私有資料庫訓練<br>
利用課程Class 01介紹「私有非結構化資料(水果資料庫)」的Fruits 360資料來進行圖像分類範例。<br>
採用<br>
1.1. MLP: Multilayer perceptron (多層感知機)，在深度學習每一層的perceptron則稱為Fully connection。<br>
1.2. CNN: Convolutional Neural Network (卷積神經網路)<br>
進行分類模型學習。<br>
*教材: [pytorch_classification.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/06_pytorch_classification.ipynb) <br> 

2. Pytorch進行圖像分類: 有沒有用Data augumention訓練模型是否真的有影響，以CIFAR-10為例。<br>
這邊我們將拿CIFAR-10的資料來訓練和測試看看Data Augumention對於模型的影響。<br>
- 番外篇1:我們拿西瓜、蘋果和香蕉的圖片來這兩個模型inference看看。<br>
- 番外篇2: lr_scheduler是什麼?<br>
*教材: [pytorch_classification_DataAugumention.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/06_pytorch_classification_DataAugumention.ipynb) <br> 

## Class 7: Pytorch進行圖像分類 - 手刻ResNet-18和Torchvision匯入<br>
**內容概述:** <br>
怎麼一層一層手刻ResNet-18，以及如何利用torchvision modelzo直接匯入模型和導入pretrain。<br>
並且以CIFAR10為例進行訓練。<br>
*教材: [pytorch_classification_resnet.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/07_pytorch_classification_resnet.ipynb) <br> 
