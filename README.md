# 安装/重装系统


本文通过详细介绍系统安装/重装的方法，即使是从出生到现在就没碰过电脑的人，90%也能学会安装/重装系统(*如果你没看懂这句话，可以先往后看*)

## 一· 什么是电脑

> 这一段话是给亿点也不懂的人解释的，如果你不是这样的人，那么请直接跳过这一段无聊的解释...(因为我写着就无聊，我不想让懂的人在经历无聊的折磨)

### 电脑简介

计算机（computer）俗称电脑，是现代一种用于高速计算的电子计算机器，可以进行数值计算，又可以进行逻辑计算，还具有存储记忆功能。是能够按照程序运行，自动、高速处理海量数据的现代化智能电子设备。  
由硬件系统和软件系统所组成，没有安装任何软件的计算机称为裸机。可分为超级计算机、工业控制计算机、网络计算机、个人计算机、嵌入式计算机五类，较先进的计算机有生物计算机、光子计算机、量子计算机等。  

### 各部分硬件介绍

#### 1. 主板
主板：连接所有其他设备的设备，是其他设备的载体，主板主要是为CPU、内存、显卡、硬盘等提供平台，相当于人体的躯干，关联着各个器官。



#### 2. CPU
CPU：中央处理单元(Cntral Pocessing Uit)的缩写，也叫处理器，是计算机的运算核心和控制核心。人靠大脑思考，电脑靠CPU来运算、控制。让电脑的各个部件顺利工作，起到协调和控制作用。



#### 3. 硬盘
硬盘：存储资料和软件等数据的设备，有容量大，断电数据不丢失的特点。也被人们称之为“数据仓库”。



#### 4. 内存
内存：1. 负责硬盘等硬件上的数据与CPU之间数据交换处理；2. 缓存系统中的临时数据。3. 断电后数据丢失。



#### 5. 显卡
显卡：显示器想要呈现画面，显卡是关键。简单来说，就是负责在显示屏上显示一切信息。打个比方，它就像是人的眼睛，没有了它，电脑就无法驱动形成图像了。显卡性能好，电脑的图形处理能力就高，尤其在玩游戏时更能发现这个（所以很多游戏会要求显卡性能）。对玩家而言，最好选择独立显卡。不过，如果不玩大型游戏，CPU内置核心显卡也基本能满足要求。缺点： 系统功耗有所加大，发热量也较大，额外购买

> “集成显卡” 与 “独立显卡”的区别:  
  
> 集成显卡是集成在主板或CPU里面的显卡，集成在CPU里面的显卡又叫做核心显卡。  
> 独立显卡是以独立板卡形式存在，可在具备显卡接口的主板上自由插拔的显卡。  

主要区别：

* 集成显卡一般不带有显存，工作时需要占用系统的一部分内存作为显存，而内存作为显存无论时速度还是带宽都与独立显卡存在一定的差距，所以性能较低也是正常的。另外因为内存被 
  占用，所以对电脑整体的性能也会有一定影响。  

* 独立显卡有自己单独的显存，不占用系统的内存，并且当自带的显存不够用时也可以共享内存作为显存。在技术上领先于集成显卡，独显拥有一套独立的运行环境，核心运算有更大的发 
  挥空间，从而性能相对于集成显卡来说有较大的提升。  

* 集成显卡有价格低廉、兼容性好的优点，性能满足基本的办公以及小型的游戏，如果不玩大型3D游戏与作图、视频等，在购机时可以选择不需要独立显卡。  



#### 6. 电源
电源：将电压220伏的市电转换为低等电压，然后送到主板及各个硬件！供电！电脑运行需要电力，而电源就是为此供电的，也可以说它在为电脑提供一切动力。电源决定了电脑的稳定性。它和人体心脏功能类似，都是提供动力的核心。


## 二· 电脑中的系统

### 系统简介

> 这一段话是给亿点也不懂的人解释的，如果你......，那么请直......(都能明白省略号....)

操作系统（Operating System，OS）是指控制和管理整个计算机系统的硬件和软件资源，并合理地组织调度计算机的工作和资源的分配，以提供给用户和其他软件方便的接口和环境，它是计算机系统中最基本的系统软件。

系统开机后，操作系统（OS）被加载到RAM(内存)。注意：操作系统≠操作环境


### 系统的功能

#### 1．处理器管理  
处理器是完成运算和控制的设备。在多道程序运行时，每个程序都需要一个处理器，而一般计算机中只有一个处理器。操作系统的一个功能就是安排好处理器的使用权，也就是说，在每个时刻处理器分配给哪个程序使用是操作系统决定的。  
  
#### 2．存储管理  
计算机的内存中有成千上万个存储单元，都存放着程序和数据。何处存放哪个程序，何处存放哪个数据．都是由操作系统来统一安排与管理的。这是操作系统的存储功能。  
  
#### 3．设备管理  
计算机系统中配有各种各样的外部设备。操作系统的设备管理功能采用统一管理模式，自动处理内存和设备间的数据传递，从而减轻用户为这些设备设计输入输出程序的负担。  
  
#### 4．作业管理  
作业是指独立的、要求计算机完成的一个任务。操作系统的作业管理功能包括两点尸是在多道程序运行IC现货商时，使得备用户合理地共享计算机系统资源22是提供给操作人员一套控制命令用来控制程序的运行  
  
#### 5．文件管理  
计算机系统中的程序或数据都要存放在相应存储介质上。为了便于管理，操作系统招相关的信息集中在一起，称为文件。操作系统的文件管理功能就是负责这些文件的存储、检索、更新、保护和共享 

### 系统的分类

#### 1.Microsoft Windows
Microsoft Windows是美国微软公司以图形用户界面为基础研发的操作系统 [13]，主要运用于计算机、智能手机等设备。共有普通版本、服务器版本（Windows Server）、手机版本（Windows Phone等）、嵌入式版本（Windows CE等）等子系列，是全球应用最广泛的操作系统之一。  
Microsoft Windows于1983年开始研发，最初的研发目标是在MS-DOS(命令行界面)的基础上提供一个多任务的图形用户界面，后续版本则逐渐发展成为主要为个人电脑和服务器用户设计的操作系统，并最终获得了世界个人电脑操作系统的垄断地位  

#### 2.Linux
Linux，一般指GNU/Linux（单独的Linux内核并不可直接使用，一般搭配GNU套件，故得此称呼），是一种免费使用和自由传播的类UNIX操作系统，其内核由林纳斯·本纳第克特·托瓦兹（Linus Benedict Torvalds）于1991年10月5日首次发布，它主要受到Minix和Unix思想的启发，是一个基于POSIX的多用户、多任务、支持多线程和多CPU的操作系统。它支持32位和64位硬件，能运行主要的Unix工具软件、应用程序和网络协议。  
Linux继承了Unix以网络为核心的设计思想，是一个性能稳定的多用户网络操作系统。Linux有上百种不同的发行版，如基于社区开发的debian、archlinux，和基于商业开发的Red Hat Enterprise Linux、SUSE、Oracle Linux等。  

#### 3.macOS
macOS是一套由苹果开发的运行于Macintosh系列电脑上的操作系统。macOS是首个在商用领域成功的图形用户界面操作系统。  
macOS是基于XNU混合内核的图形化操作系统，一般情况下在普通PC上无法安装的操作系统。网上也有在PC上运行的macOS（Hackintosh）。  
另外，疯狂肆虐的电脑病毒几乎都是针对Windows的，由于macOS的架构与Windows不同，所以很少受到电脑病毒的袭击。  


## 三·重装系统

### 重装系统与安装系统的区别

主要区别:
* 重装是在有系统的情况下安装系统
* 安装实在无系统的情况下安装系统

详细区别:  
重装系统一般是在可用系统内运行镜像内的setup.exe进行系统内重装系统，还有一种就是原系统不能使用，这是后叫重装系统或安装系统就没区别了，因为硬盘内有系统文件，说明有系统，所以可以叫重装系统；虽然有系统，但无法使用，无法进行系统内安装，需要执行和安装系统一样的系统外安装操作，所以也可以叫做安装系统。  
  
安装系统一般是指硬盘是新的或无分区/无系统的情况下执行全新安装系统，过程会更复杂一些，叫做安装系统。

### 进行重装

#### 1.下载镜像

点击[此处]()
