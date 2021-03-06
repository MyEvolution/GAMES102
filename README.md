## GAMES 102
Assignments of GAMES 102. Website of GAMES 102: [Geometry Modeling and Processing](http://staff.ustc.edu.cn/~lgliu/Courses/GAMES102_2020/default.html).
### Assignment 1
Use python to implement polynomial interpolation, gaussian interpolation, polynomial regression and ridge regression. Type command:
```
python fit.py
```
It will eject a window that you can put your own points. After setting your points,  close the window. It will eject another window that shows the fitting results with different colors. The results will be like:

![](./hw1.png)

### Assignment 2
Use pytorch to build a RBFNet to fit some points. See demo:
![](./rbfnet.gif)

### Assignment 3

Use parameterization to fit an arbitrary curve, which does not have to be a function. Use Taichi for visualization.
![](./hw3.gif)

**Note that there were some bugs of foley parameterization, which have been fixed. However, the gif has not been updated yet.**

### Assignment 4

Implementation of 7 kinds of curve. 
- Natural cubic spline
- End slope spline
- G1-0
- G1-1
- G0
- Bezier
- Bezier interpolation

More details can refer to `hw4/report.pdf`.

![](./hw4.gif)

### Assignment 5

Implementation of subdivision curve. 
- Chaikin
- Uniform Cubic B Spline
- 4-point interpolation

More details can refer to `hw5/report.pdf`.

![](./hw5.gif)

### Assignment 6
More details can refer to `hw6/report.pdf`.

### Assignment 7
![](./hw7.gif)

More details can refer to `hw7/report.pdf`.

### Assignment 8
![](./hw8.gif)

More details can refer to `hw8/report.pdf`.

### Assignment 9
#### Quadric Edge Collapse Decimation and Clustering Decimation
![](./hw9/armadlillo.jpg)

![](./hw9/dragon.jpg)

![](./hw9/bunny.jpg)

More details can refer to `hw9/report.pdf`.

### Assignment 10
#### RBF Reconstruction and Poisson Reconstruction
![](./hw10.gif)

More details can refer to `hw10/report.pdf`.

Code can refer to https://github.com/MyEvolution/Dragon