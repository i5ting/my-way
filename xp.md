# 为XP（极限编程）说几句

今天学习了ac研究院张老师的技术管理方面的，公司目前主推的是RUP（IBM的一种方法），是采取user case（用例）驱动的
他课讲的非常好，业务构件和技术组件的关系，vrm版本之间的区别，各年度重点 说的都非常到位，                                                                                                             
张老师貌似很不喜欢XP，他认为他是不可行的。举了几个失败的例子，这点我不是很认同，各有优势，课上没有说，在这里写几句

XP是agile（敏捷开发）的一种，它不是说开发人员为了不写文档而愿意采取这种方式。
我对XP的理解和agile有一些关系，敏捷开发提倡的是一种迭代式的开发，它主要是以测试驱动（TDD）的方式来进行
在这些人的眼中，通过测试越早发现bug，修复的代价越小，这和软件工程的理论也是一样的。

TDD改变了一种开发方式
以前会考虑怎么用去实现这个功能，现在的时候我会把我先分析出大致应该如何实现
然后围绕一核心功能，把其他的代码（没完成的，算稍微正规点的伪代码吧）写出来，这样我有一个整体的理解在里面，
比如说我很容易去判断采用哪种设计模式更好，再有一个我的结构定了，再写东西的时候不是一点一点去堆，从这点上看，设计是受控的。、

XP的结对编程（in pair），不知道有多少人有体会？
我和大学的一个朋友尝试过一次，还是很成功的，当时我没带电脑，在他那里，所以我们只能用一台电脑
当时有一个算法，要的比较急，所以我们必须尽快做，首先他有一个想法，我们沟通一下，然后他开始实行，
写了20分钟左右，，它觉得差不多了，我看了一下觉得里面需要改进，它的某些逻辑不太对，然后我写代码，他在边上边看边想
如此2个多小时完成了那个算法。
感慨颇多~~~~~~~

诚如张老师所说敏捷开发要求水平相处无几，不然确实很难配合，再有最重要的是沟通
没有【足够的沟通】，称不上敏捷

各位可能要问了，我说的XP,为什么我一直在讲TDD的内容呢？
答案是TDD是kent beck提出来，jUnit是他写出来的，其实还有很多单元测试框架与此类似，XP也是他提出来的，
二者有必然联系吗？
答案是肯定的，没有演进，哪有辉煌啊~~~~~~~~~~哈哈

RUP是面向用例的，也就是说，它在软件开发的最初就受控了，这点对【大型】公司来讲是非常重要的，
这是它的优点，
它的缺点是应变性查。需求变更了，它要从头去梳理，在tdd的时候会立马有反应，而RUP要一系列过程的。
哈哈，有个词，是尾大不掉
需求变更的越快，付出的代价越小。我觉着这是rup的一个弊端。









