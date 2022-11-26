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
然後怎麼利用pytorch建立自有資料集的dataset和dataloader<br>

1. Pytorch dataloader: 讀取結構化資料<br>
*教材: [Dataloader-1_Structure data.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/02_Dataloader-1_Structure%20data.ipynb) <br>

2. Pytorch dataloader: 讀取非結構化資料<br>
 2.1 當dataset是torch vision提供的寫法<br>
 2.2 當dataset是私有資料庫的寫法。<br>
 2.3 如何將資料丟到CUDA<br>
 
*教材: [Dataloader-2_CustomDataset.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/02_Dataloader-2_CustomDataset.ipynb) <br>
   補充資料:[pytorch_dataloader_linux.ipynb](https://github.com/TommyHuang821/PytorchTutorial/blob/main/Code/02_pytorch_dataloader_linux.ipynb)

