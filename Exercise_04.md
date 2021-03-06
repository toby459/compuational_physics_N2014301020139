#第四次作业
##Chapter1 Problem5
Consider again a decay problem with two types of nuclei A and B, but now suppose that nuclei of typw A decay into type B, while nuclei of type B decay into type A. Strictly speaking, this is not a "decay" process, since it is possible for the type B nuclei to turn back into type A. A better analogy would be a resonance in which a system can tunnel or move back and forth between two states A and B which have equal energies. The corresponding rate equations are <br>
![](https://github.com/toby459/compuational_physics_N2014301020139/blob/master/File_2/QQ%E5%9B%BE%E7%89%8720161009180342.png)<br>
where for simplicity we have assumed that the two types of decay are characterized by the same time constant ![](http://latex.codecogs.com/gif.latex?%7B%5Ctau%20%7D). Solve the system of equations for the numbers of nuclei, ![](http://latex.codecogs.com/gif.latex?N_%7BA%7D) and ![](http://latex.codecogs.com/gif.latex?N_%7BB%7D), as functions of time. Consider different initial confitions, such as ![](http://latex.codecogs.com/gif.latex?N_%7BA%7D%3D100), ![](http://latex.codecogs.com/gif.latex?N_%7BB%7D%3D0), etc., and take ![](http://latex.codecogs.com/gif.latex?%5Ctau%20%3D1) s. Show that your numerical results are consistent with the idea that the system reaches a steady state in which ![](http://latex.codecogs.com/gif.latex?N_%7BA%7D) and ![](http://latex.codecogs.com/gif.latex?N_%7BB%7D) are constant. In such a steady state, the time derivatives ![](http://latex.codecogs.com/gif.latex?%7B%5Cmathrm%7Bd%7D%20N_%7BA%7D%7D/%7B%5Cmathrm%7Bd%7D%20t%7D) and ![](http://latex.codecogs.com/gif.latex?%7B%5Cmathrm%7Bd%7D%20N_%7BB%7D%7D/%7B%5Cmathrm%7Bd%7D%20t%7D) should vanish.<br>
##摘要
考虑两个可以互相转化的核A和B,  一开始只有100个A粒子，观察5秒之间的衰变情况，用matplotlib模拟出衰变图。
##作业结果
[代码](https://github.com/toby459/compuational_physics_N2014301020139/blob/master/code.py)<br>
图像<br>
![](https://github.com/toby459/compuational_physics_N2014301020139/blob/master/File_2/exercise04.png)<br>
##总结
图像与预期结果基本一致，程序基本上就是依葫芦画瓢。<br>
最后致谢蔡老师的屁屁踢和余剑桥同学的指导。
