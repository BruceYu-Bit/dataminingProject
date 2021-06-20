# dataminingProject
数据挖掘大作业

数据下载地址：https://tianchi.aliyun.com/competition/entrance/231694/information

简介：
在本次大作业中，我们需要利用比赛提供的数据来自经过沙箱程序模拟运行后的 API 指令序列，全为 Windows 二进制可执行程序，经过脱敏处理；样本数据均来自互联网，其中恶意文件的类型有感染型病毒、木马程序、挖矿程序、DDos 木马、勒索病毒等，共 6 亿条数据进行处理分析，最终训练模型分析得到某种类型文件所属的病毒类型。我们这里采用了三种方式
（1）基线模型：特征工程+LightGBM模型
（2）提升模型：TextCNN
（3）提升模型：pivot特征+LightGBM模型
最终通过不断的对模型的探索，取得了较好的结果。
