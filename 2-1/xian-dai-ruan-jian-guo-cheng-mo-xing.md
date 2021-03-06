# 现代软件过程模型



## 现代软件过程模型

 **现代软件过程模型指的是 `由于现代软件过程的发展 而提出的软件过程模型.`**



### 基于构件的开发模型

* **近年来得到广泛应用, 改变了大型软件开发方式.**
* **考虑的焦点是 `集成`, 而非实现.**
* **`构件 / 组件` \(Component\)**
  * **系统中模块化的 , 可更换的部分** 
  * **构件是独立的模块, 可以被另一个具有相同接口的构件可替换**
  * **实现特定的功能**
  * **对实现进行封装,  暴露一组接口 , 外部并不需要知道构件的具体实现内容,只需要使用接口,**
  * 例如 :  动态链接库\(.dll, .so\) , 浏览器插件等

![&#x57FA;&#x4E8E;&#x6784;&#x5EFA;&#x7684;&#x5F00;&#x53D1;&#x6A21;&#x578B;&#x7684;&#x4E24;&#x90E8;&#x5206;,  &#x7CFB;&#x7EDF;&#x5F00;&#x53D1;&#x548C;&#x6784;&#x4EF6;&#x5F00;&#x53D1;&#x4E0E;&#x7EF4;&#x62A4;](../.gitbook/assets/image%20%28218%29.png)

#### 基于构件的的开发可以分为四个阶段

* **第一阶段 .需求分析阶段** 
  * 确定软件要做什么 \(和其他模型相同\).
* **第二阶段. 构件分析**
  * 根据需求所搜构件
  * 如果没有完全匹配的构件, 则需要修改构件或者修改需求
* **第三阶段.系统设计**
  * 与其他过程模型不同
  * 考虑重用和集成
  * 如果没有可用的构件, 则设计新构件
* **第四阶段. 开发集成**
  * 将构件集成到系统中
  * 没有可重用的部分可用于开发新软件

### 适用场合

由于采用服用思想所以  **适用于系统之间有共性的情况.**

### 基于构件的开发模型的优缺点

* **优点**
  * 软件**`复用`**思想
  * 降低开发成本和风险, 加快开发进度, 提高软件质量
* **缺点**
  * 模型复杂
  * 商业构件不能修改, 会导致修改需求, 进而导致系统不能完全符合客户需求
  * 无法完全控制所开发系统的演化
  * 项目划分的好坏直接影响项目结果的好坏

