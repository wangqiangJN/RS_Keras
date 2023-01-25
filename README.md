# RS_Keras
TF2.x+Keras+tf.feature_column训练推荐算法

# why this project?
1. 对数据中缺失值、异常值处理
2. id类特征列进行embedding、连续性特征分桶做one-hot再做embedding、交叉特征
3. 排序模型算法搭建
4. 训练测试验证模型

### 每个模型有两个文件：model.ipynb和model.py,方便测bug和运行
## 数据集
数据集使用搜狐算法大赛大赛推荐数据：https://www.biendata.xyz/competition/sohu_2022/?source=xyFaye_959


## 1.数据处理EDA
1. 缺失值处理
2. 异常值处理
3. 连续数值归一化

## 2.特征工程
1. id类特征做embedding
2. 连续数值分桶->one-hot->embedding
3. 交叉特征

## 3.模型搭建
1. Wide&Deep
2. DeepFM
3. DIN
4. BST

## 4.训练测试评估
