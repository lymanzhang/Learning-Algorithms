## 在python中调用matplotlib的实践
### 开发环境
- pycharm

```

"""
Simple demo of a scatter plot.
"""

import numpy as np
import matplotlib.pyplot as plt

N = 50
x = np.random.rand(N)
y = np.random.rand(N)
colors = np.random.rand(N)
area = np.pi * (15 * np.random.rand(N))**2  # 0 to 15 point radii

plt.scatter(x, y, s=area, c=colors, alpha=0.5)

plt.show()

```
输出如下图所示
![plot](https://github.com/lymanzhang/LearningPythonProgramming/blob/master/python%E4%B8%AD%E8%BF%9B%E8%A1%8Cmatplotlib%E8%B0%83%E7%94%A8/plot.PNG)
