# CIFAR-10 分类

本仓库包含一个Jupyter Notebook，用于在CIFAR-10数据集上训练和评估深度学习模型。CIFAR-10数据集包含60000张32x32彩色图像，分为10类，每类6000张图像。

## 目录
- [安装](#安装)
- [使用方法](#使用方法)
- [Notebook结构](#notebook结构)
- [许可证](#许可证)

## 安装

要运行此Notebook，您需要安装所需的依赖项。您可以运行以下命令来安装这些依赖项：

```bash
pip install -r requirements.txt
```
确保创建一个包含以下内容的requirements.txt文件：

```makefile
d2l
pandas==2.0.3
jupyter==1.0.0
matplotlib==3.7.2
ipywidgets
notebook
nbconvert
qtconsole
jupyter-console
ipykernel
```

## 使用方法
克隆此仓库到本地机器。

```bash
git clone https://github.com/your-username/cifar10-classification.git
cd cifar10-classification
```
安装所需的依赖项。
```bash
pip install -r requirements.txt
```
打开Jupyter Notebook。
```bash
jupyter notebook CIFAR10.ipynb
```
依次运行Notebook中的单元格，以在CIFAR-10数据集上训练和评估模型。

## Notebook结构
`CIFAR10.ipynb` Notebook的结构如下：

### 安装依赖项
- 第一个单元格安装所需的Python包。

### 导入和配置
- 导入必要的库并配置设置。

### 数据加载和预处理
- 加载CIFAR-10数据集并执行归一化等预处理步骤。

### 模型定义
- 定义深度学习模型的架构（例如卷积神经网络）。

### 模型训练
- 在训练集上训练模型，并在验证集上进行验证。

### 模型评估
- 在测试集上评估训练好的模型，并可视化结果。

### 可视化
- 可视化样本预测结果和训练历史。

## 许可证
此项目根据MIT许可证授权 - 有关详细信息，请参阅[LICENSE](LICENSE)文件。
