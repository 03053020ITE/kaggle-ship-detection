# Airbus Ship Detection Challenge
![image](https://github.com/03053020ITE/ship-detection/blob/master/abstract.PNG)
![image](https://github.com/03053020ITE/ship-detection/blob/master/7.PNG)
首先使用`maskship.ipynb` 利用 Mask R-CNN and COCO pre-trained weights 來成功訓練並成功預測
![image](https://github.com/03053020ITE/ship-detection/blob/master/1.PNG)
![image](https://github.com/03053020ITE/ship-detection/blob/master/5.PNG)
![image](https://github.com/03053020ITE/ship-detection/blob/master/6.PNG)
![image](https://github.com/03053020ITE/ship-detection/blob/master/7.PNG)

```
maskship.ipynb
```

將只有船隻的圖片給保存下來，並將其存入資料夾

```
imagetomask.ipynb
```
應用Traditional Unet、RGB Unet、Simplify Unet共三種架構、兩種數據集進行訓練(all、only have ship)，實現了三種不同的像素分割技術完成此專案

```
unet.ipynb
``` 