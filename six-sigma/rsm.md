# 响应曲面设计 \(Response surface methodology, RSM\)

## 目的

实验优化

与其他实验设计对比（2因子为例）

* 2因子2水平（2^2）析因设计：四个实验点（-1，-1）（-1，1）（1，1）（1，-1），回归方程不包含二次项，回归方程可用于生成响应曲面。方程包括不交叉项时，等高线是直线；方程包括交叉项时，等高线是曲线。
* 二因子中心复合设计：每个2个水平（-1，-1）（-1，1）（1，1）（1，-1）+ 中心点（0，0）。
* RSM：2因子2水平 + 5次重复中心点（0，0）+ 四个坐标轴上的点（-α，0）（α，0）（1，α）（-1，α）。相比2因子3水平设计，可保持可旋转性。
* 2因子3水平（3^2）析因设计：每个3个水平（-1，0，1）共9次实验。



** Number of Runs Required by Central Composite and Box-Behnken Designs **

| Number of Factors 因子个数 |  Central Composite 中心复合 |  Box-Behnken  |
| :--- | :--- | :--- |
| 2 | 13 \(5 center points\)  | - |
| 3 |  20 \(6 centerpoint runs\)  | 15 |
| 4 |  30 \(6 centerpoint runs\)  | 27 |
| 5 |  33 \(fractional factorial\) or 52 \(full factorial\)  | 46 |
| 6 |  54 \(fractional factorial\) or 91 \(full factorial\)  | 54 |



**Determining α for Rotatability（可旋转性）**

| Number of Factors 因子个数 | Factorial Portion | Scaled Value for α Relative to ±1  |
| :--- | :--- | :--- |
| 2 | 2^2 | 2^\(2/4\)=1.414 |
| 3 | 2^3 | 2^\(3/4\)=1.682 |
| 4 | 2^4 | 2^\(4/4\)=2 |
| 5 | 2^\(5-1\) | 2^\(4/4\)=2 |
| 5 | 2^5 | 2^\(5/4\)=2.378 |
| 6 | 2^\(6-1\) | 2^\(5/4\)=2.378 |
| 6 | 2^6 | 2^\(6/4\)=2.828 |



