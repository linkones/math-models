# math-models

个人数学建模代码库，收录常用建模、预测、优化、仿真、评价等模型模板，供比赛和学习使用。

## 目录结构
- `optimization/` 优化算法：线性规划、遗传算法、粒子群、动态规划等
- `regression/` 回归与拟合：线性回归、多项式回归、岭回归等
- `prediction/` 预测模型：ARIMA、LSTM、灰色预测等
- `clustering/` 聚类与降维：K-Means、层次聚类、PCA等
- `simulation/` 仿真模型：蒙特卡洛、微分方程仿真等
- `statistics/` 统计分析：描述性统计、假设检验等
- `utils/` 工具类：数据处理、可视化函数等

## 使用方法
1. 克隆仓库到本地：git clone https://github.com/linkones/math-models.git
2. 安装依赖：pip install -r requirements.txt
3.  调用示例（以线性回归为例）：
```python
from regression.linear_regression import linear_regression

X_train, y_train = ...
model = linear_regression(X_train, y_train)

