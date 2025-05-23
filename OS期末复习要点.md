# 操作系统引论

## 操作系统的目标

1.方便性
2.有效性
3.可扩充性
4.开放性

> 其中方便性和有效性是设计OS时最重要的两个目标

## 操作系统的作用

用户可以通过三种方式使用计算机，即通过**命令方式**、**系统调用方式**和**图标-窗口方式**来实现与操作系统的通信，并取得它的服务。

## 单道批处理系统

为实现对作业的连续处理，需要先把一批作业以脱机方式输入到磁带上，并在系统中配上监督程序，在它的控制下，使这批作业能一个接一个地连续处理。

> 单道批处理系统的主要缺点是，系统中的资源得不到充分的利用。

## 多道批处理系统

在该系统中，用户所提交的作业先存放在外存上，并排成一个队列，称为“后备队列”。然后由作业调度算法，从后备队列中选择若干个作业调入内存，使它们共享CPU和系统中的各种资源。

> 多道批处理的优缺点：
> 1.资源利用率高
> 2.系统吞吐量大：CPU和其他资源保持忙碌状态；仅当作业完成时或运行不下去时才进行切换，**系统开销小**。
> 3.平均周转时间长
> 4.无交互能力

操作系统是一组能有效组织和管理计算机硬件和软件资源，合理地对各类作业进行调度，以方便用户使用的程序的集合。

## 分时系统

用户需要人-机交互和共享主机，于是引入了分时系统

转而采用作业直接进入内存和采用轮转运行的方式

> 分时操作系统的特征
（1）多路性：允许多个用户共享一台计算机，显著地提高了资源的利用率
（2）独立性
（3）及时性
（4）交互性

## 实时系统

实时系统是指系统能及时响应外部事件的请求，在规定的时间内完成对该事件的处理，并控制所有的实时任务协调统一地运行。

实时系统的类型：工业（武器）控制系统（火炮的自动控制系统、飞机的自动驾驶系统、导弹的制导系统等）、信息查询系统、多媒体系统、嵌入式系统。

### 实时系统的类型

（1）周期性实时任务和非周期性实时任务：非周期性实时任务无明显的周期性，但都必须联系着一个截止时间，或称为最后期限。它可以分为：开始截止时间（指某任务在某时间以前必须开始执行）和完成截止时间（指某任务在某时间以前必须完成）。

（2）硬实时任务和软实时任务。
**硬实时任务**：是指系统必须满足任务对截止时间的要求；**软实时任务**:也联系着一个截止时间，但并不严格，若偶尔错过了任务截止时间，对系统的影响也不会太大。

> 实时系统的特征
（1）及时性（快速的响应时间）
（2）确定性
（3）可靠性

## 并发（Concurrence）

- 并行性：两个或多个事件在**同一时刻**发生

- 并发性：两个或多个事件在**同一时间间隔**内发生



# 进程的描述与控制

# 处理及调度与死锁

# 存储器管理

# 虚拟存储器

# 输入输出系统

# 文件管理

# 磁盘存储器的管理方式

# 操作系统接口

# 多处理机操作系统

# 多媒体操作系统

# 保护和安全
