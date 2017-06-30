# artificial-intelligent-in-robotics

circular motion : 建立汽车的运动模型，预测后一秒汽车的位置估计

first search ： 移动一步 | 0 | 0 | 1 | 0 | 0 | 0 |
                        | 0 | 0 | 1 | 0 | 0 | 0 |
                        | 0 | 0 | 0 | 0 | 1 | 0 |
                        | 0 | 0 | 1 | 1 | 1 | 0 |
                        | 0 | 0 | 0 | 0 | 1 | 0 |
                       1代表障碍物，0 代表路径， 每走一步cost = 1 ， 找到从[0,0]点到[5,4]点的运动轨迹
