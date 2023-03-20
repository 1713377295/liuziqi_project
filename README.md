# <p align="center">基于Python的六子棋人机对战软件</p>

## <p align="center">摘要</p>
   >六子棋是一种新型的黑白棋博弈棋种，被誉为“目前最公平”的博弈棋种，相对于五子棋和围棋来讲，六子棋的历史特别短，但是优点在于对双方都公平，没有其他的规则限制。本次我们使用Python进行六子棋的算法开发与实现。<br>
关键词：Python 六子棋 公平

## <p align="center">abstracts</p>
   >Romoku is a new type of black and white chess game chess, known as the "fairest" game at present, compared to Gomoku and Go, the history of Rokumoku is particularly short, but the advantage is that it is fair to both sides, there are no other rules restrictions. This time, we use Python for the algorithm development and implementation of six-backgammon.<br>
keyword:Python Romoku fair

## <p align="center">参考文献</p>
>[1]段浴,王宛宛.基于人工智能的六子棋博弈平台研究与实现[J].科技创新与应用,2022,12(19):24-26+31.<br>
[2]邓银莹,常郝.并行思想的六子棋博弈搜索算法设计[J].电子世界,2021(10):146-147.<br>
[3]王鸿菲,王静文,李媛.基于PVS算法的六子棋博弈系统的研究[J].智能计算机与应用,2021,11(02):97-100.<br>
[4]何轩,洪迎伟,王开译,彭耶萍.机器博弈中搜索策略和估值函数的设计——以六子棋为例[J].电脑知识与技术,2019,15(34):53-54+61.<br>
[5]何轩,洪迎伟,王开译,彭耶萍.机器博弈主要技术分析——以六子棋为例[J].电脑知识与技术,2019,15(33):172-173.<br>
[6]高强,徐心和.证据计数法在落子类机器博弈中的应用[J].东北大学学报(自然科学版),2016,37(08):1070-1074+1103.<br>
[7]李学俊,王小龙,吴蕾,刘慧婷.六子棋中基于局部“路”扫描方式的博弈树生成算法[J].智能系统学报,2015,10(02):267-272.<br>
[8]周新林,李淑琴,张晨光,赵学智,薛炜明.六子棋博弈系统设计与实现[J].软件导刊,2015,14(03):92-94.<br>
[9]于江明,袁斌杰,何灿辉,段琢华.六子棋博弈系统中机器学习算法设计与研究[J].韶关学院学报,2014,35(10):17-22.<br>
[10]张小川,候鑫磊,涂飞.博弈机器人的行为规划[J].重庆理工大学学报(自然科学),2014,28(04):99-103.<br>
[11]徐长明,马宗民,徐心和,李新星.面向机器博弈的即时差分学习研究[J].计算机科学,2010,37(08):219-223.<br>
[12]黄继平,苗华,张栋.用遗传算法实现六子棋评估函数参数优化[J].重庆工学院学报(自然科学版),2009,23(11):85-89.<br>
[13]黄继平,张栋,苗华.六子棋智能博弈系统的研究与实现[J].电脑知识与技术,2009,5(25):7198-7200.<br>
[14]徐长明,马宗民,徐心和.一种新的连珠棋局面表示法及其在六子棋中的应用[J].东北大学学报(自然科学版),2009,30(04):514-517.<br>
[15]李果.基于遗传算法的六子棋博弈评估函数参数优化[J].西南大学学报(自然科学版),2007(11):138-142.<br>
[16]黄晨.棋类游戏中的先行权[J].智能系统学报,2007(03):91-94.<br>

##<p align="center">可行性分析</p>
  由于六子棋发明不久，目前在学术界引起的关注较少。但是六子棋是一种新颖、有趣、易学难精的棋。由于每人每次下两步(第一步除外)，所以它的对攻性强，可变性大，棋路开阔，且又免去了五子棋繁杂的禁手，因此极受大众欢迎。在公平性上进行拓展，就会发现，如果想要实现人机对弈的绝对公平，就需要六子棋算法可以精准的算到每一步的落点并且和人的思想同步。
 ![image](https://user-images.githubusercontent.com/126448556/226250109-70378e00-6b57-4e65-a818-8ef9b560c1a2.png)

图2-1 六子棋程序流程图

##<p align="center">需求概述</p>
  本系统主体使用python语言进行编写，python语言有很多库文件可以进行使用，后续开发AI对弈，需要python的神经网络模块，所以基础部分也同样使用python进行编写，主要使用的库文件是pygame库。

###<p align="center">系统可行性</p>
  基于PyCharm开发的python程序，后期可以和神经网络模块进行很好的结合，便于调用数据量庞大的运算模块，同时语言选择是使用python，本系统需要进行的计算量十分的庞大，而python虽然比JAVA和C的实用性差一点，但是满足本系统的需求。
###<p align="center">经济可行性</p>
本程序是基于PyCharm开发的python程序，且程序并不是十分的复杂，主体是算法部分，开发周期较短，在经济上是可行的，所以系统在开发人力、财力要求不高，具有经济可行性。
（1）工作量估算
在软件开发阶段需要使用到的人力工作量百分比如下表2-1所示。
表2-1毕业设计过程管理系统各个开发阶段的人力百分比
任务	人力（%）
可行性研究	4
需求分析	10
概要设计和详细设计	24
编码和测试	62
总计	100

（2）成本估算
在软件开发阶段需要其他一次性支出如下表2-2所示。
表2-2软件开发过程中各个开发阶段的一次性支出
项目	费用（元）
软件需求分析	1500
软件设计	2500
程序编码	5000
软件测试软件维护	7500
培训费及软件开发人员费用	13000

表2-3软件开发过程中成本估算
项目	成本估计（元/年）
时间和人力成本	8000
域名及服务器购买	2000
第三方服务成本	3000
软件维护	5000
合计	18000
（3）效益
表2-4软件开发过程各个开发阶段的收益
项目	收益（元/年）
一次性收益	20000
经常性收益	10000
不可定量收益	无
企业定制服务	20000
总计	50000
（4）收益/投资比
一次性支出：29500元
经常性支出：18000元/年
收益：50000/年
收益/投资比（五年内）：50000*5/（29500+18000*5）=2.0920
（5）投资回收期估算
会议管理系统的基础建设成本约为29500元，第一年内收入为50000元，软件投资回收期约为
                      29500/50000=0.59（年）
                      
###<p align="center">技术可行性</p>
  六子棋博弈程序采用PyCharm的pygame库进行开发，从技术角度来说，硬件环境搭建和软件环境开发都可以实现，难度不是很大。
先构建六子棋博弈的核心算法，再逐步在此基础上搭建框架，使用PyCharm搭建程序的前端。
