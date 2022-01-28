# DCGAN


## 环境要求

- Python3.5+
- TensorFlow== 2.0.0a0  `pip3 install tensorflow-gpu==2.0.0a0`
- TensorLayer=2.1.0		`pip3 install tensorlayer==2.1.0`

## 运行方式

第一步，下载全新的人脸数据集：

链接：https://pan.baidu.com/s/1eyB3UNP83M1FwHliWHdwxQ 
提取码：r4n1 

将数据集放在项目根目录的 `data` 文件夹下。

第二步，训练网络：

```python
python train.py
```

## 实验结果

CelebA数据集训练结果如下：

![image-20220129001221673](.\img\result.png)

