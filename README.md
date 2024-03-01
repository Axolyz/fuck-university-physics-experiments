# fuck⭐nku⭐physics⭐experiments

**本仓库已远程接入荷取科技自主研发的妖怪之山信仰系统，点上一颗star⭐即可为守矢神社提供一个大信仰点，Sanae会召唤大奇迹保佑你今天骑车顺风。**

---

本仓库旨在提供针对南开张春玲版《大学基础物理实验》的全套解决方案，包括但不限于数据处理excel和预习题。  
无论你是本校学生想要为这个项目添砖加瓦建言献策，亦或是外校学生想在此基础上改动以适应自己的教材版本，欢迎一切交流合作，fork，issue，pull request，以及小窗（qq792405142）。如果您发现了错误或不足，请务必提出issue或直接联系笔者，在下感激不尽。  
ps. 笔者事情也有点多，戳小窗很可能不会及时处理合并到主分支，最好直接走git的流程大家都方便。

# 果然，大物实验，该杀！！！

- 仓库分为三个分支,rm分支已废弃,protect分支使公式处于保护状态防止误操作改动公式,除此之外和main分支无区别,可手动通过审阅-取消保护工作表取消公式保护,main分支也可手动通过审阅-保护工作表开启公式保护.
- release为protect分支的内容.
- excel中的大部分物理量名称与张春玲版《大学基础物理实验》一致，可对照书本，尤其是书本上的数据处理表格填入数据。
- 大框架来自：https://www.bilibili.com/video/BV13T411g7J1?p=1 的农大版，特向该视频p主juebukeyi致谢。
- 不逆天的实验绪论课：https://www.bilibili.com/video/BV13T411g7J1?p=2 都！给！我！听！！
- 主要用到的excel函数教学：https://www.bilibili.com/video/av201021490 以及用于计算置信系数t代替查表的ROUND(TINV(1-置信度,自由度),2)。
- excel绘图教程：https://www.bilibili.com/video/BV14b4y1b7Jj
- 小标题定型文灵感来自：https://www.bilibili.com/video/BV1gC4y1P7t3

# ♡谁叫你随便用的！变态！！

- 本人的此门课最终给分很差,然而已知的用了这个数据处理表格的其他同学分数表现却很好,这已经不是普通的物理实验了,必须要出重拳!!(同样境遇的还有隔壁做latex模板的JFY同学)
- 本仓库暂时不能处理保留有效数位，单元格只会输出浮点数，请自行保留正确的数位,**这一点很可能成为助教罚分的重要依据**
- 对于每个使用者而言，为了避免对雷同实验报告的抄袭指控（严重者会直接挂零），笔者建议**使用时请尽量不在实验报告中留下明显痕迹。实验报告中尽量不要出现这个仓库中excel的影子。也最好不要在课程人员能看见的地方使用和宣传。**

# ♡笨...笨蛋！连为什么要用excel这点事情都不清楚吗！

笔者考察过一些使用cpp，matlab或者python的同类项目（友链里有），但发现可读性实在太差，使用引导要做好了才能用，最后选择了excel。
- 使用方便，不需要编译环境，不需要用文本或命令行输入数据，输完的实验数据可以直接复制到word里，可以直接画图，部分表格可以反复移植复用（如不确定度）。
- 维护方便，不需要做源代码阅读理解也不需要写注释，实验大改了也能改完接着用，单元格可以直接编辑公式，函数可读性强。
- 懒。

# ♡人家才...才不是想和你一起维护项目呢！！

本人精力有限，故希望能得到其他志愿维护者的协助。可以学学基本操作之后贡献一些excel代码，可以用表格验算数据，把计算结果的正误反馈给我，可以贡献一些自己的实验报告和预习题答案，也可以改进优化表格排版，欢迎一切交流合作，fork，issue，pull request，以及小窗（qq792405142），笔者打算完善的事情写在下面的todo一栏中了。
- 考虑到本校物理实验每年教学内容，ppt和教材可能的变化（甚至据我所知有的实验每个助教讲的都不一样），表格公式的可编辑性和可移植性会较为重要，也方便外校学生fork后自行改编。
- 本仓库暂时不打算包含实验报告样例。
- 笔者事情也有点多，戳小窗很可能不会及时处理合并到主分支，最好直接走git的流程大家都方便。

# ♡要做的事情不...不能再多了！

- [x] 力学部分全部实验（hotfix 5.18：碰撞实验的e值计算有大问题，已换源）
- [x] 电学部分全部实验
- [x] 光学部分全部实验
- [x] 补全17个实验的excel（4.23更新：全部实验的数据处理已经更新完毕）
- [x] 使公式处于只读状态防止误操作改动公式
- [ ] 预习题答案/预习题库（这东西太逆天了）
  > 做完预习题留个底发过来就行，最好整理好成word或者txt，答案不要求完全准确，可以事后再完善
- [ ] 补全物理量的单位和写法，使其和南开课本尽量吻合
- [ ] 对表格中只有一个字母表示，模糊不清的物理量在表头加上文字说明
- [ ] 助教给的实验讲义或者流程（今年的）
  > 拍照留底发过来就行，最好扫描处理一下
- [ ] 标明或直接在公式中处理物理量保留位数
  > 关于保留小数的问题（这是目前比较大的问题），有三种方式可用，第一种是直接采用保留小数位数的数字格式/单元格格式，第二种是用TEXT(A1,"0.000")这样格式的函数在excel中保留小数数位（不能用round因为不会显示末尾补齐的0），第三种是直接在表头写明保留几位但实际输出还是原始不保留位数的样子，本人更倾向于第三种做法（前两种多少有点更改和移植的困难，而且这样能始终保持浮点输出不舍入，确保精度够高），当然也欢迎不像笔者这么懒的维护者搞个pr把前两种实现了。
- [ ] 便于格式优化，后续维护和更新的规范doc
- [ ] 用于参考的实验数据(单独的sheet)
  > 把做完实验的表格数据留个底给我就行，当然数据最好别太离谱
- [ ] 在所有需要绘图的excel中内置描点作图功能
  > 参见上面的excel画图教学
- [ ] 终极目标：https://github.com/feixukeji/PhyX 像科大这样做成在线版的

# ♡最喜欢大家了！！！

https://github.com/JFYStudy/NKU_experiment-report 实验报告LATEX版。  
https://github.com/shesl-meow/PhysicsAnalysis 无名南开学长的贡献，使用cpp。  
https://github.com/Lunaticsky-tql/NKU_PhysicExp 同届大佬的项目,使用python.  
https://github.com/feixukeji/PhyX 科大的项目，内附详细的文档和在线数据处理工具。  
https://github.com/nkuflw/nku-physics-exp 实验报告word版。  
以上。

# ♡如果和我一起开源的话...也不是不可以哦～

Licensed by GPL v3.

# ♡什么？在想...我的事？

Authored by Axolyz.  
Posted on https://github.com/Axolyz/fuck-university-physics-experiments.  
Welcome for stars, issues & contributions.  

[![ppG6bVg.jpg](https://s1.ax1x.com/2023/03/17/ppG6bVg.jpg)](https://imgse.com/i/ppG6bVg)  

> 当我们迫于学校的教学计划，被迫选一些看上去比较没用的课程时，总会听到一些充满善意的劝慰：“这些知识多学一些也没有什么不好，没准哪天就能用得到呢！”这种话乍听起来仿佛很有道理，但实际上却是不折不扣的谎言。  
> 连高中教学都已经文理分家，作为一名大学生，我们更应当对自己的将来有一个最基本的规划。令人遗憾的是，学校教务部门经常异想天开地把一些八竿子打不着的课程推到我们面前，以为让机动学院的学生同时掌握心理学和化学实验，就能打造出所谓的复合型人才。我们之所以拒绝学习那些对自己不是特别有用的知识，是因为这些知识对我们的价值太低。  
> 事务对我们都会有影响，其价值必须定量，而非定性地讨论。出去义务扫马路可以陶冶你的情操，还可以锻炼身体。坐在家里背单词背一天你可以学会数百个新单词，提升英语水平。按照上面提到的“善意的逻辑”，这两者各有好处，仿佛难以取舍。但是我想在实际操作中，不会有人认为前者对你的益处更大。  
> 说道理大家都清楚，但是在实际生活中，我们却总能见到某些组织的头目派手下同学站在食堂门口发传单，以“锻炼大家的社会实践能力”。我们也能见到不少同学东一榔头西一棒槌地学了许多与自己职业规划毫无关系的课程，美其名曰“扩充知识面”。  
> 在打着各种华丽口号的诱惑面前，我们要保持清醒，并且时刻告诫自己  
> 总有更值得做的事。  
> ----《SJTU生存手册》  
