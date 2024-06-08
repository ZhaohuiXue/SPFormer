先运行AutoEncoder.py训练对应数据集的自编码器，手动保存loss最低的那个，接着记录下对应.pt的路径。接着运行main.py进行对应数据集的模型训练和测试，注意需要先把autoencoder的路径正确写入对应的的字典变量内。
AutoEncoder.py训练降维自编码并保存
data.py高光谱图像数据处理脚本
loop_train_test.py循环训练测试，并将模型权重保存在save\models中，训练结果保存在save\results中
loss_function.py需要用到的损失函数
main.py主程序
SelfPoolingTransformer.py模型文件
visualization.py读取数据并进行可视化

environment required:
python >=3.6
torch >= 1.10.2
cuda >= 11.1.1