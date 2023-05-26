# fuck-nku-physics-experiments

> 当我们迫于学校的教学计划，被迫选一些看上去比较没用的课程时，总会听到一些充满善意的劝慰：“这些知识多学一些也没有什么不好，没准哪天就能用得到呢！”这种话乍听起来仿佛很有道理，但实际上却是不折不扣的谎言。  
> 连高中教学都已经文理分家，作为一名大学生，我们更应当对自己的将来有一个最基本的规划。令人遗憾的是，学校教务部门经常异想天开地把一些八竿子打不着的课程推到我们面前，以为让机动学院的学生同时掌握心理学和化学实验，就能打造出所谓的复合型人才。我们之所以拒绝学习那些对自己不是特别有用的知识，是因为这些知识对我们的价值太低。  
> 事务对我们都会有影响，其价值必须定量，而非定性地讨论。出去义务扫马路可以陶冶你的情操，还可以锻炼身体。坐在家里背单词背一天你可以学会数百个新单词，提升英语水平。按照上面提到的“善意的逻辑”，这两者各有好处，仿佛难以取舍。但是我想在实际操作中，不会有人认为前者对你的益处更大。  
> 说道理大家都清楚，但是在实际生活中，我们却总能见到某些组织的头目派手下同学站在食堂门口发传单，以“锻炼大家的社会实践能力”。我们也能见到不少同学东一榔头西一棒槌地学了许多与自己职业规划毫无关系的课程，美其名曰“扩充知识面”。  
> 在打着各种华丽口号的诱惑面前，我们要保持清醒，并且时刻告诫自己  
> 总有更值得做的事。  
> ----《SJTU生存手册》  

本仓库旨在提供针对南开张春玲版《大学基础物理实验》的全套解决方案，包括但不限于数据处理excel和预习题。  
无论你是本校学生想要为这个项目添砖加瓦建言献策，亦或是外校学生想在此基础上改动以适应自己的教材版本，欢迎一切fork，issue，pull request以及交流合作。如果您发现了错误或不足，请务必提出issue或直接联系笔者，在下感激不尽。(qq:792405142) 

# ☢ CAUTION!! ☢ CAUTION!! ☢
于整个仓库而言，考虑到这一课程可能采取的反制措施（包括但不限于大改实验或者换教材），笔者希望这个仓库能活得长一点，**不因为大家的实验报告中明显的雷同迹象而暴露**。  
于每个使用者的gpa而言，为了避免对雷同实验报告的抄袭指控（严重者会直接挂零），笔者也强烈建议**使用时请尽量不在实验报告中留下明显痕迹，不要作死。**  
- 为了世界和平，**不要在任何互联网的公开场合，尤其是课程教学有关人员能看到的场合宣传本仓库。**   
- 为了减轻可能的怀疑，**实验报告中尽量不要出现这个仓库中excel的任何影子（包括但不限于直接复制粘贴excel表格原表到实验报告中，或采用仓库中的表格格式或者配色等）**，笔者仅希望这些excel仅仅用来输入和输出数据，成为数值计算的工具，而不是实验报告的排版辅助工具。
- 本仓库大部分新发布的excel尚在育碧阶段，不排除出现bug的可能性，任何由本仓库导致的抄袭指控或者计算错误等一切责任自负。
- 本仓库暂时并不打算处理保留有效数位，单元格只会输出浮点数，请自行保留正确的数位。

# WHY Excel??
- 使用方便，不需要编译环境，不需要用文本或命令行输入数据，输完的实验数据可以直接复制到word里，可以直接画图，部分表格可以反复移植复用（如不确定度）。
- 维护方便，不需要做源代码阅读理解也不需要写注释，单元格可以直接编辑公式，函数可读性强。
- 其实就是懒。

# 寻找志愿维护者
本人精力有限，故希望能得到其他志愿维护者的协助。可以学学基本操作之后贡献一些excel代码，可以用表格验算做过一遍的数据，把计算结果的正误反馈给我，可以贡献一些自己的实验报告和预习题答案，也可以改进优化表格排版，欢迎一切fork，issue，pull request以及交流合作。(qq:792405142)  

# Tips

- excel中的绝大部分物理量名称与张春玲版《大学基础物理实验》完全一致，可对照书本，尤其是书本上的数据处理表格填入数据。
- 大框架来自：https://www.bilibili.com/video/BV13T411g7J1?p=1 的农大版，特向该视频p主juebukeyi致谢。
- 不逆天的实验绪论课：https://www.bilibili.com/video/BV13T411g7J1?p=2 都！给！我！听！！
- 主要用到的excel函数教学：https://www.bilibili.com/video/av201021490 以及用于计算置信系数t代替查表的ROUND(TINV(1-置信度,自由度),2)。
- excel绘图教程：https://www.bilibili.com/video/BV14b4y1b7Jj

# Tested(基本上没bug)

- [x] 力学部分全部实验（hotfix 5.18：碰撞实验的e值计算有大问题，已换源）
- [x] 电学部分全部实验
- [x] 光学部分全部实验
当前版本bug已经很少了,出现的问题大多数是使用问题,后期会加大力度改善使用引导方面的内容.

# 一点doc

- 考虑到本校物理实验教学内容，ppt和教材可能的变化，本仓库可能需要23级的学弟帮忙维护，所以可编辑性和可移植性会较为重要，也方便外校学生fork后自行改编。
- 考虑到可能的抄袭指控和暴露的风险，本仓库暂时不打算包含任何实验报告样例。
- 暂时并不打算用ROUND在excel中保留小数数位，更不打算直接采用保留小数位数的单元格格式，因为这会极大地削弱可编辑性和可移植性，预计后期会补完。

# Todo

- [x] 补全17个实验的excel（4.23更新：全部实验的数据处理已经更新完毕）
- [ ] 使公式处于只读状态防止误操作改动公式
- [ ] 预习题答案/预习题库（这东西太逆天了）
- [ ] 对模糊不清的物理量含义加以说明
- [ ] 物理量保留位数的提示
- [ ] 便于格式优化，后续维护和更新的规范doc
- [ ] 用于参考的实验数据(单独的sheet)
- [ ] 在excel内置描点作图功能

# 友链

https://github.com/JFYStudy/NKU_experiment-report 实验报告LATEX版。  
https://github.com/shesl-meow/PhysicsAnalysis 无名南开学长的贡献，使用cpp。  
https://github.com/Lunaticsky-tql/NKU_PhysicExp 同届大佬的项目,使用python.  
https://github.com/feixukeji/PhyX 科大的项目，内附详细的文档和在线数据处理工具。  
https://github.com/nkuflw/nku-physics-exp 实验报告word版，爆了无数金币还把金币开源了的伟皇致以最高的敬意敬意敬意敬意敬意敬意敬意  
以上。

# License

Licensed by GPL v3.

# Stage EX

Author: Axolyz.  
Website: https://github.com/Axolyz/fuck-university-physics-experiments.  
Stars, issues & contributes are welcomed.  
**本仓库已远程接入荷取科技自主研发的妖怪之山信仰系统，点上一颗star即可为守矢神社提供一个大信仰点，Sanae会召唤大奇迹保佑你今天骑车顺风。**  
[![ppG6bVg.jpg](https://s1.ax1x.com/2023/03/17/ppG6bVg.jpg)](https://imgse.com/i/ppG6bVg)  
