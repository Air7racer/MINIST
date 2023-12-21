```markdown
# 简单卷积神经网络用于MNIST手写数字分类

这个仓库包含了一个使用PyTorch实现的简单卷积神经网络（CNN），用于对MNIST手写数字数据集进行分类。代码包括训练和测试过程，以及保存训练好的模型的选项。

## 环境要求

确保已安装以下依赖项：

- Python 3.x
- PyTorch
- torchvision
- matplotlib
- tqdm

您可以使用以下命令安装所需的软件包：

```bash
pip install torch torchvision matplotlib tqdm
```

## 使用方法

1. **克隆仓库：**

   ```bash
   git clone https://github.com/Air7racer/MINIST.git
   cd your-repository
   ```

2. **安装依赖项：**

   确保已安装所需的软件包：

   ```bash
   pip install -r requirements.txt
   ```

3. **训练模型：**

   要训练模型，请运行以下命令：

   ```bash
   python main.py
   ```

   训练脚本将在MNIST数据集上训练Simple CNN指定数量的时期。训练进度，包括损失和准确性，将显示在控制台中。


4. **评估模型：**

   训练完成后，在测试集上评估模型。测试准确性将打印到控制台。


5. **可视化训练进度：**


   可视化训练进度，将显示训练损失和准确性随迭代次数的变化

  

6. **保存模型：**


   模型将保存为 `mnist_cnn_model.pth`。

7. **可选：调整超参数**

   您可以在相应的脚本中修改学习率、批处理大小和时期数等超参数。


8. **自测**
  运行如下代码
 ```bash
   python self_test.py
   ```
9. **修改自测图片样例**
```bash
   input_image_path = ''
   ```
  代码中路径修改为您希望对其进行识别的图片路径
## 致谢

- 本代码基于PyTorch和torchvision库。

欢迎根据需要自定义代码并尝试不同的架构和超参数！

**注意：** 在运行代码之前，请确保已安装Python和所需的软件包。
