![image](https://github.com/03053020ITE/ship-detection/blob/master/abstract.PNG)






![image](https://github.com/03053020ITE/ship-detection/blob/master/7.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/1.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/2.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/3.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/4.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/5.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/6.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/8.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/traditional%20unet%20image.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/traditional%20unet%20prdeict%20image.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/rgb%20unet%20image.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/rgb%20unet%20prdeict%20image.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20image.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20train.PNG)


![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20prdeict%20image.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20prdeict%20image2.PNG)

![image](https://github.com/03053020ITE/ship-detection/blob/master/simplify%20unet%20prdeict%20image3.PNG)

* Mask R-CNN and COCO pre-trained weights
利用 Mask R-CNN 和 COCO 的預訓練權重來成功訓練並預測
```
maskship.ipynb
```
* 數據儲存
將只有船隻的圖片保存下來，存入兩個資料夾內

```
imagetomask.ipynb
```
* 使用Traditional Unet、RGB Unet、Simplify Unet架構
應用Traditional Unet、RGB Unet、Simplify Unet共三種架構、兩種數據集進行訓練(all、only have ship)，實現了三種不同的像素分割技術

```
unet.ipynb
``` 

* 數據擴增 (Data_Augmentation)
改寫程式碼增加數據擴充技術

```
unet_data_augmentation.ipynb
``` 
