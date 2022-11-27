# Pytorch Tutorial 實作課程

## 作者 Author
![image](https://user-images.githubusercontent.com/25295252/204134360-67946cc4-e3fe-4c73-a994-b84e5e4098af.png)<br>
<span> - &copy; 黃志勝 Chih-Sheng (Tommy) Huang (<a href="https://github.com/TommyHuang821">Github</a>) (<a href="https://sites.google.com/site/chihshenghuang821">個人網頁</a>) (<a href="https://medium.com/@chih-sheng-huang821">Medium文章</a>) </span>  

## 目錄 
  * [Class 0: 數據型態簡介<br>](https://github.com/TommyHuang821/PytorchTutorial#class-0-%E6%95%B8%E6%93%9A%E5%9E%8B%E6%85%8B%E7%B0%A1%E4%BB%8B)
  * [Class 1: 資料庫取得 <br>](https://github.com/TommyHuang821/PytorchTutorial#class-1-%E8%B3%87%E6%96%99%E5%BA%AB%E5%8F%96%E5%BE%97-)
  * [Class 2: 利用Pytorch建立Dataset和Dataloader<br>](https://github.com/TommyHuang821/PytorchTutorial#class-2-%E5%88%A9%E7%94%A8pytorch%E5%BB%BA%E7%AB%8Bdataset%E5%92%8Cdataloader)
  * [Class 3: 利用Pytorch進行梯度下降更新<br>](https://github.com/TommyHuang821/PytorchTutorial#class-3-%E5%88%A9%E7%94%A8pytorch%E9%80%B2%E8%A1%8C%E6%A2%AF%E5%BA%A6%E4%B8%8B%E9%99%8D%E6%9B%B4%E6%96%B0)
  * [Class 4: 在pytorch建立卷積、池化和激活函數和自定義運算架構方式<br>](https://github.com/TommyHuang821/PytorchTutorial#class-4-%E5%9C%A8pytorch%E5%BB%BA%E7%AB%8B%E5%8D%B7%E7%A9%8D%E6%B1%A0%E5%8C%96%E5%92%8C%E6%BF%80%E6%B4%BB%E5%87%BD%E6%95%B8%E5%92%8C%E8%87%AA%E5%AE%9A%E7%BE%A9%E9%81%8B%E7%AE%97%E6%9E%B6%E6%A7%8B%E6%96%B9%E5%BC%8F)
  * [Class 5: 利用Pytorch模組torchvision進行資料擴增(Data Augmentation)<br>](https://github.com/TommyHuang821/PytorchTutorial#class-5-%E5%88%A9%E7%94%A8pytorch%E6%A8%A1%E7%B5%84torchvision%E9%80%B2%E8%A1%8C%E8%B3%87%E6%96%99%E6%93%B4%E5%A2%9Edata-augmentation)
  * [Class 6: Pytorch進行圖像分類模型訓練<br>](https://github.com/TommyHuang821/PytorchTutorial#class-6-pytorch%E9%80%B2%E8%A1%8C%E5%9C%96%E5%83%8F%E5%88%86%E9%A1%9E%E6%A8%A1%E5%9E%8B%E8%A8%93%E7%B7%B4)
  * [Class 7: Pytorch進行圖像分類 - 手刻ResNet-18和Torchvision匯入<br>](https://github.com/TommyHuang821/PytorchTutorial#class-7-pytorch%E9%80%B2%E8%A1%8C%E5%9C%96%E5%83%8F%E5%88%86%E9%A1%9E---%E6%89%8B%E5%88%BBresnet-18%E5%92%8Ctorchvision%E5%8C%AF%E5%85%A5)
  * [Class 8: Pytorch-AutoEncoder<br>](https://github.com/TommyHuang821/PytorchTutorial#class-8-pytorch-autoencoder)
  * [Class 9: Generative Adversarial Network(GAN)<br>](https://github.com/TommyHuang821/PytorchTutorial#class-9-generative-adversarial-networkgan)

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

## Class 8: Pytorch-AutoEncoder<br>
**內容概述:** <br>
- 介紹Auto-Encoder (AE)
- 利用Pytorch進行MNIST的AutoEncoder
- 可視覺化方式觀察Embedding feature的分布。<br>

內有補充內容: Flatten在pytorch怎麼做<br>

*教材: [Pytorch_AutoEncoder.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/08_Pytorch_AutoEncoder.ipynb) <br> 

## Class 9: Generative Adversarial Network(GAN)<br>
**內容概述:** <br>
- 介紹Generative Adversarial Network (AE)
- Pytorch手把手進行DCGAN實作，以MNIST資料庫為例
DCGAN: Deep Convolutional Generative Adversarial Networks

*教材: [Pytorch_DCGAN.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/09_Pytorch_DCGAN.ipynb) <br>

## 授權 License
<a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/tw/88x31.png" /></a> (CC BY-NC-SA 4.0)<br />本教學課程適用 <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Attribution-NonCommercial-ShareAlike 4.0 International</a> 授權方式。

※ 轉載、改作、分享請附上以下內容：
 - 如有轉載、改作、分享，請註明出處，source: https://github.com/TommyHuang821/PytorchTutorial
