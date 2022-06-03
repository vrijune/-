# MATLAB SKILLS 3

（1）平面网格数据的生成
是使用矩阵运算生成，定位两个顶点然后形成平面网格


可以使用的等式是 X = ones(size(y))*x;
Y = y*ones(size(x));

平面网格数据的生成：
绘制三维曲面的mesh函数和surf函数
fmesh函数和fsurf函数
![image](https://user-images.githubusercontent.com/81022107/166135979-3b781805-ebc5-4518-9690-8dd43284dda3.png)

（2）meshgrid函数进行矩阵生成
[X,Y] = meshgrid(x,y);
其中，参数x，y为向量，存储网格点坐标的X,Y为矩阵

>> x = 2 : 6;
>> y = (3:8)';

(3)对于平面网格数据的修改


