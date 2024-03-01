# proj324-An-Online-Examination-System-for-Intelligent-Proposition
# 面向操作系统课程的基于智能命题的在线考试系统

## 项目描述

在线考试系统中的命题问题是困扰一线教师的难题，同学在学习过程中也希望通过在线练习来检验学习效果。智能命题软件可针对操作系统课教学的主要知识点，自动生成题目，在线回答后自动完成批改和给出参考答案，可减少教师命题工作量，改善同学进行练习的体验。

智能命题包括基本概念填空题、基本算法选择题、综合知识解答题三个部分[1,2]。填空题命题算法参考文献[3]。基本算法选择题命题算法参考文献[4][5]。

要求综合知识至少给出以下算法的智能命题、答题用户界面和自动评分、答案和评分标准的显示[3-5]。

* 进程调度算法RR q=n；n∈[1,4]，
* 页面置换算法：OPT(Optimal)、LRU、Clock；
* 磁盘调度算法：SSTF、SCAN、CSCAN、N-Step-SCAN、N-Step-CSCAN；
* 银行家算法

该题目的详细描述请参见“[面向操作系统课程的基于智能命题的在线考试系统](https://cloud.tsinghua.edu.cn/d/69a38db9a8ec4c52b574/files/?p=%2F20240229-谢印宝-考试系统.pdf)”

## 预期目标

* 设计N（N≥500）个考生同时在线考试，难度相当和相似度高的且题目不能完全相同；
* 设计综合知识算法在线答题的用户界面；
* 设计公平、公正的自动评分，按列评分，保存考生的电子试卷；
* 设计参考答案和评分标准的显示格式；

## 特征

* 构建和实现按命题算法命题与随机发放机制。
* 实现对应考生的试题、答案和评分标、电子试卷和成绩的存储机制。
* 实现操作系统课程在线异卷考试、自动评分，交卷后显示答案和评分标准，按考生信息自动记录成绩。
* 文档、代码、问题、答疑交互过程都开放和开源的。

## 已有参考资料

[1] 汤小丹, 王红玲, 姜华，等. 计算机操作系统(慕课版)(M). 北京: 人民邮电出版社，2021.

[2] William Stallings. Operating systems : internals and design principles(Ninth Edition). New Jersey: Pearson Education, Inc., 2017.

[3] 谢印宝，吴志勇. 基于Agent的操作系统学习与考试系统[J]. 山东理工大学学报( 自然科学版),2019,33(4):32-36. 

[4] 谢印宝. 基于多智能代理的试题库设计与实现[J]. 软件工程, 2021,24(5):17-21. 

[5] 操作系统学习与考试系统(XOSCATS)_系统资源-CSDN https://download.csdn.net/download/AppleMechanic/86409624

[6] 源程序资源https://gitee.com/xie-yinbao/XOSCATS.git

## 赛题分类

教学支撑大类

未归类的教学支撑

## 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
* 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

中等

## License

GPL-3.0 License

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

* 谢印宝
  * 单位：山东理工大学
  * email： xieyinbao@163.com
* 姓名：向勇
  * 单位：清华大学
  * github ID： [https://github.com/xyongcn](https://github.com/xyongcn#tdsub)
  * email： [xyong@tsinghua.edu.cn](mailto:xyong@tsinghua.edu.cn#tdsub)
