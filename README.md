# 图像风格迁移

## 依赖

- [NumPy](http://docs.scipy.org/doc/numpy-1.10.1/user/install.html)
- [Tensorflow](https://www.tensorflow.org/versions/r0.8/get_started/os_setup.html)
- [Keras](https://keras.io/#installation)
- [OpenCV](https://opencv-python-tutroals.readthedocs.io/en/latest/)

## 用法

下载预训练的 VGG19 [模型](https://github.com/foamliu/Neural-Style-Transfer/releases/download/v1.0/imagenet-vgg-verydeep-19.mat)放入 pretrained-model 目录，然后执行：

```bash
$ python main.py
```

### 内容图片
![image](https://github.com/Liu-Vince/Neural-Style-Transfer/blob/main/images/content.jpg)

### 风格图片
![image](https://github.com/Liu-Vince/Neural-Style-Transfer/blob/main/images/style.jpg)

### 合成图片
![image](https://github.com/Liu-Vince/Neural-Style-Transfer/blob/main/images/output.png)
