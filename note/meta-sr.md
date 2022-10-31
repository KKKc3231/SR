# Meta-SR

用的作者训练1000次的model，作者只给了训练好的Meta-RDN在不同数据集下不同scale的超分结果

![image-20221026133940757](C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026133940757.png)

## Set5

- `scale=1.5`（PSNR:41.472，SSIM:0.9785）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221025221624842.png" alt="image-20221025221624842" style="zoom:50%;" />

- `scale=2.0`（PSNR:38.230，SSIM:0.9610）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221025222854567.png" alt="image-20221025222854567" style="zoom:50%;" />

- `scale=2.5`（PSNR:36.179，SSIM:0.9442）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026234315479.png" alt="image-20221026234315479" style="zoom:50%;" />

- `scale=3.0`（PSNR:34.731，SSIM:0.9296）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027001154469.png" alt="image-20221027001154469" style="zoom:50%;" />

- `scale=3.5`（PSNR:33.616，SSIM:0.9147）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026232916480.png" alt="image-20221026232916480" style="zoom:50%;" />

- `scale=4.0`（PSNR:32.510，SSIM:0.8986）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026234424023.png" alt="image-20221026234424023" style="zoom:50%;" />

## Set14

- `scale=1.5`（PSNR:37.519，SSIM：0.9601）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027004308661.png" alt="image-20221027004308661" style="zoom:50%;" />

- `scale=2.0`（PSNR：34.027，SSIM:0.9204）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026142948402.png" alt="image-20221026142948402" style="zoom:50%;" />

- `scale=2.5`（PSNR:31.896，SSIM:0.8814）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027000932524.png" alt="image-20221027000932524" style="zoom:50%;" />

- `scale=3.0`（PSNR：30.582，SSIM：0.8465）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026133650065.png" alt="image-20221026133650065" style="zoom:50%;" />

- `scale=3.5`（PSNR:29.598，SSIM:0.8140）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027000153424.png" alt="image-20221027000153424" style="zoom:50%;" />

- `scale=4.0`（PSNR：28.860，SSIM：0.7878）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026134817409.png" alt="image-20221026134817409" style="zoom:50%;" />

## B100

- `scale=1.5`（PSNR:35.868，SSIM:0.9544）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026235346018.png" alt="image-20221026235346018" style="zoom:50%;" />

- `scale=2.0` （PSNR: 32.360，SSIM: 0.9011）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026193019801.png" alt="image-20221026193019801" style="zoom:50%;" />

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026200400538.png" alt="image-20221026200400538" style="zoom:50%;" />

- `scale 2.5`（PSNR:30.481，SSIM:0.8509）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026214912760.png" alt="image-20221026214912760" style="zoom:50%;" />

- `scale 3.0`（PSNR: 29.282，SSIM: 0.8089 ）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026192949284.png" alt="image-20221026192949284" style="zoom:50%;" />

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026200325086.png" alt="image-20221026200325086" style="zoom: 50%;" />

- `scale 3.5`（PSNR:28.442，SSIM:0.7730）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026214537425.png" alt="image-20221026214537425" style="zoom:50%;" />

- `scale 4.0` （PSNR: 27.759 ，SSIM: 0.7419）

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221026192840902.png" alt="image-20221026192840902" style="zoom:50%;" />

# ArbSR

## 同一放大倍率

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027202928078.png" alt="image-20221027202928078" style="zoom: 67%;" />

### `Set5`

- scale1=[1.5，2.0，2.5，3.0，3.5，4.0]，scale2=[1.5，2.0，2.5，3.0，3.5，4.0]

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027200645181.png" alt="image-20221027200645181" style="zoom:67%;" />

### `Set14`

- scale1=[1.5，2.0，2.5，3.0，3.5，4.0]，scale2=[1.5，2.0，2.5，3.0，3.5，4.0]

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027203529022.png" alt="image-20221027203529022" style="zoom:50%;" />

### `B100`

- scale1=[1.5，2.0，2.5，3.0，3.5，4.0]，scale2=[1.5，2.0，2.5，3.0，3.5，4.0]

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027222909813.png" alt="image-20221027222909813" style="zoom:67%;" />

## 不同放大倍率

跑的实验结果与论文中采取的缩放比例大小一致

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027202836401.png" alt="image-20221027202836401" style="zoom: 67%;" />

### `Set5`

- scale1=[1.5，1.5，1.6]，scale2=[4.0，3.5，3.05]

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027203621466.png" alt="image-20221027203621466" style="zoom:67%;" />

### `Set14`

- scale1=[4.0，3.5，3.5]，scale2=[2.0，2.0，1.75]

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027210951648.png" alt="image-20221027210951648" style="zoom:67%;" />

### `B100`

- scale1=[4.0，1.5，3.5]，scale2=[1.4，3.0，1.45]

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221027221256337.png" alt="image-20221027221256337" style="zoom:67%;" />

# LIIF

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221028141752236.png" alt="image-20221028141752236" style="zoom: 67%;" />

## Set5

scale：x2, x3, x4, x6, x8, x12

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221028142334780.png" alt="image-20221028142334780" style="zoom:67%;" />

## Set14

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221028142948873.png" alt="image-20221028142948873" style="zoom:67%;" />

## B100

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221028143031665.png" alt="image-20221028143031665" style="zoom:67%;" />

## Urban100

<img src="C:\Users\HP\AppData\Roaming\Typora\typora-user-images\image-20221028152454764.png" alt="image-20221028152454764" style="zoom:67%;" />

