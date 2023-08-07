# 基于论文摘要的文本分类与关键词抽取挑战赛 Task 1
本教程会带领大家项目制学习，由浅入深，逐渐进阶。从跑通最简的Baseline，精读Baseline，到底层算法原理与进阶实践技巧的学习，千里之行，始于足下，从这里，开启你的 AI 学习之旅吧!  
# 塞题解析
## 赛题背景
医学领域的文献库中蕴含了丰富的疾病诊断和治疗信息，如何高效地从海量文献中提取关键信息，进行疾病诊断和治疗推荐，对于临床医生和研究人员具有重要意义。
## 赛事任务
机器通过对论文摘要等信息的理解，判断该论文是否属于医学领域的文献。
## 任务示例：
输入：
论文信息，格式如下：
Inflammatory Breast Cancer: What to Know About This Unique, Aggressive Breast Cancer.，
[Arjun Menta, Tamer M Fouad, Anthony Lucci, Huong Le-Petross, Michael C Stauder, Wendy A Woodward, Naoto T Ueno, Bora Lim]，
Inflammatory breast cancer (IBC) is a rare form of breast cancer that accounts for only 2% to 4% of all breast cancer cases. Despite its low incidence, IBC contributes to 7% to 10% of breast cancer caused mortality. Despite ongoing international efforts to formulate better diagnosis, treatment, and research, the survival of patients with IBC has not been significantly improved, and there are no therapeutic agents that specifically target IBC to date. The authors present a comprehensive overview that aims to assess the present and new management strategies of IBC.，
Breast changes; Clinical trials; Inflammatory breast cancer; Trimodality care.
输出：
是
## 赛题数据集
训练集与测试集数据为CSV格式文件，各字段分别是标题、作者、摘要、关键词。
## 评价指标
本次竞赛的评价标准采用F1_score，分数越高，效果越好。
