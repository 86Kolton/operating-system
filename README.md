# operating-system
进程管理、磁盘管理、内存管理|操作系统实验<br>
软件：操作系统实验汇总展示<br>
工具：Visual Stdio 2017<br>
语言：C\C++、   图形化工具：MFC<br>
程序登陆界面：<br>
   ![Image text](https://github.com/kinnisoy/operating-system/blob/master/photos/d61c315c851ed7f688c683155dedf51.png)
进程管理<br>
  ![Image text]( https://github.com/kinnisoy/operating-system/blob/master/photos/5b31d1b6c0308fab9501958e66f7f11.png)

内存管理<br>
  ![Image text](https://github.com/kinnisoy/operating-system/blob/master/photos/e435cf3ca4b8d19ec6b200b290f2dd3.png)
磁盘管理<br>
  ![Image text]( https://github.com/kinnisoy/operating-system/blob/master/photos/adf9cbc29b7376e1d34eab170da03f9.png)
思路：<br>
1.创建登陆界面，模态化弹窗，阻塞进程，登陆完成后，关掉该dialog，程序继续运行，显示主程序界面<br>

2.【进程管理】<br>
	a)从文件中读取初始化进程列表<br>
	b)新建进程使用弹窗<br>
	c)点击调度按钮，默认使用动态优先算法，结果显示在右侧文本框。<br>

3	【内存管理】<br>
a)	默认两个分区：操作系统、可分配空闲分区<br>
b)	分配状态1表示已分配、0表示未分配或尚可分配<br>
c)	分配弹窗输入申请分配控件，0或者超过可分配大小都会提示。（友好型处理）<br>
d)	回收弹窗输入回收分区的编号即可回收该分区。<br>
e)	点击上方算法，即可选中对应算法，默认使用首次适应算法。<br>
<br>
4	【磁盘管理】<br>
a)	用户自定义键入磁道数量和当前磁道位置。<br>
b)	在order.ini文件初始磁道序列，确保磁道序列满足用户键入的磁道个数。<br>
c)	确认后，即可在磁道序列窗口显示已加载的磁道序列。<br>
d)	点击选择对应的磁道管理算法。<br>
e)	点击调度后，调度结果信息则会显示在右侧窗口。<br>

5	【关于】<br>
	此程序为操作系统实验最终展示平台，由于作者本人水平有限，该程序还有一些冗余代码和部分未发现的bug。<br>
	本应用仅供操作系统和MFC的学习参考使用，请下载24h内删除。<br>
