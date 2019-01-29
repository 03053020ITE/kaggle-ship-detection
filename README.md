## Abstract
本專題首先使用 kaggle Airbus Mask-RCNN and COCO transfer learning 程式碼訓練並成功預測，學習其數據轉換、數據擴增技術，並應用 Traditional Unet、RGB Unet、Simplify Unet 共三種架構、兩種數據集進行訓練 (all、only have ship)，實現了三種不同的像素分割技術完成此專案

### Mask R-CNN and COCO pre-trained weights
利用 Mask R-CNN 和 COCO 的預訓練權重來成功訓練並預測
```
maskship.ipynb
```
### 數據儲存
將只有船隻的圖片保存下來，存入兩個資料夾內

```
imagetomask.ipynb
```
### 使用Traditional Unet、RGB Unet、Simplify Unet架構
應用Traditional Unet、RGB Unet、Simplify Unet共三種架構、兩種數據集進行訓練(all、only have ship)，實現了三種不同的像素分割技術

```
unet.ipynb
``` 

### 數據擴增 (Data_Augmentation)
改寫程式碼增加數據擴充技術

```
unet_data_augmentation.ipynb
``` 

![image](https://github.com/03053020ITE/ship-detection/blob/master/7.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/1.PNG)

### 數據轉換

![image](https://github.com/03053020ITE/ship-detection/blob/master/2.PNG)

### 數據儲存
將全部有船的圖片取出分別放至 image 資料夾、label 資料夾

![image](https://github.com/03053020ITE/ship-detection/blob/master/3.PNG)

### 數據擴增
* 遙感圖像是多方向性俯拍，船隻朝向東、南、西、北都有可能
* 90倍數旋轉(0度、90度、180度、270度角)
* 影像模糊、銳化、亮度調整

![image](https://github.com/03053020ITE/ship-detection/blob/master/4.PNG)

### Loss

![image](https://github.com/03053020ITE/ship-detection/blob/master/5.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/8.PNG)

### 傳統 U-net

![image](https://github.com/03053020ITE/ship-detection/blob/master/traditional%20unet%20image.PNG)

### RGB U-net

![image](https://github.com/03053020ITE/ship-detection/blob/master/rgb%20unet%20image.PNG)

### 簡化版 U-net

![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20image.PNG)
```
Batchsize=2
Dataset= 28980(only have ship)
Epochs=50
Step for epochs=28980//2
Time= hours
Loss from 0.05299 to 0.0025
```
![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20train.PNG)

### Mask R-CNN predict

![image](https://github.com/03053020ITE/ship-detection/blob/master/6.PNG)

### 傳統 U-net predict

![image](https://github.com/03053020ITE/kaggle-ship-detection/blob/master/traditional%20unet%20prdeict%20image.PNG)

### RGB U-net predict

![image](https://github.com/03053020ITE/ship-detection/blob/master/traditional%20unet%20prdeict%20image.PNG)

### 簡化版 U-net predict

![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20prdeict%20image.PNG)

### 簡化版 U-net predict

![image](https://github.com/03053020ITE/ship-detection/blob/master/rgb%20unet%20prdeict%20image.PNG)

### 簡化版 U-net predict

![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20prdeict%20image2.PNG)

### 簡化版 U-net predict
![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20prdeict%20image3.PNG)

