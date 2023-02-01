# Logistics-Tracking-Car
This is a course design from Design &amp; Bulid Ⅰ(First Semester) and I am the leader of this project.

本项目是未来技术学院本科一年级设计与建造Ⅰ课程的课程设计，本项目模拟了产品从设计到实物的全过程，从需求出发设计循迹物流车，自行设计物流（物块）的投放装置并制作，设计循迹和启停逻辑并最终制作出一个能够循迹行驶，识别标志后定点投放，并在终点停车的物流车。我是本项目的组长。

***

进行项目规划、需求调研等准备工作后，我们开始进行物流车的详细设计。

![结构分解图](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picstru.png)



转向部分我们设计采用差速转向，投放装置初步设计为连杆机构推动物件，之后考虑到这种投放装置反复使用后可能出现的错位现象后，我们设计了一个更稳定的齿轮传动齿槽推动物件。之后使用Solidworks对自己设计的投放装置、电池槽等非标准件建模，再使用自己组装的3D打印机将其打印出来。

![投放机构1](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picth1.png)

![投放机构1](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picass.png)

![投放机构2](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picth2.png)

驱动装置方面，动力总成都使用电池供电；控制模块采用arduino；使用四个红外线探头探测前进路线上的轨迹，并设定了四个传感器的工作逻辑；使用L298N驱动前轮两个步进电机。

![驱动](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picass.png)

![逻辑](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/piccon.png)

拼装调试后，我们的小车顺利完成循迹行驶，识别标志后定点投放，并在终点停车的功能，之后我们对转向逻辑和代码中间隔时间（break）进行优化，使得物流车能够在最短时间内完成功能。

![总装图](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picdraw.png)

![整车1](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picz1.jpg)

![整车2](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picz2.jpg)

最终，我们的物流车在2021年《设计与建造》作品考核中取得优异成绩并获奖。（四宫格中蓝色衬衣、获奖者中右一为本人）

![awa](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picmatch.png)

![awa](https://github.com/LancashireLiu/Logistics-Tracking-Car/blob/main/picaward.jpg)