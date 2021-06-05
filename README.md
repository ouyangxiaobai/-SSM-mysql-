# -SSM-mysql-
可自定义评教系统（教学质量评估系统）设计与实现（SSM）毕业论文+设计源码+mysql文件
​
下载地址：https://download.csdn.net/download/qq_31293575/18340399

下载地址：https://download.csdn.net/download/qq_31293575/18340399

可自定义评教系统设计与实现

摘  要

评教是当今提高教学质量非常重要的方法之一。在互联网时代，评教信息化也是当前发展的趋势，相比传统的评教形式，在线评教系统具有准确，及时，成本低等众多的优点。通过对当前一些评教系统的调研发现普遍存在着指标单一，权重平均，统计简单等不足。并在此基础上设计并实现了可自定义评教系统来提高教学评估的效果。

本文主要研究如何来设计和实现使用灵活的可自定义的评教系统来完成学校的评教工作。通过将数据导入系统来生成评教元数据，以降低数据维护的成本。实现自定义的评教指标用于衡量教学效果，评教结果的数据统计直观明了，从多方面来反馈教学中出现的问题，使得评教系统能够在促进教学中发挥更重要的作用。

本系统通过使用Spring框架和MySql数据库来提供开发环境，开发过程遵循MVC体系架构和软件工程的思想，通过需求分析，整体设计，详细设计，编码和测试来保障本系统高质量的完成。在安全方面，系统提供了更方便的权限管理和更细粒度的访问控制。同时对系统的可扩展性和并发访问进行了讨论。

关键词　评教系统，Spring框架，数据统计

Design and Realization of a Customized Teaching Evaluation System

Abstract

Evaluation of teaching is one of the most important way to improve the quality of teaching. In the Internet age, informatization is the mainstreams of the teaching evaluation development, compared with the traditional evaluation form, online teaching evaluation system with accurate, timely, lower cost and many advantages. Through the investigation of the current teaching evaluation system, we can found that those systems has some deficiencies such as single index, weight average, lack of result statistics and so on. So a customized evaluation system is designed and implemented to improve the effect of the teaching  evaluation .

This paper mainly studies how to design and implement the use of flexible and customized evaluation system to complete the work of the school evaluation. To reduce the cost of data maintenance, the data import module is used to generate metadata. Implement custom evaluation indicators to measure the teaching effect. Data statistics of the evaluation result is detailed and clear, from many aspects to show the problems appeared in the teaching. Making the system play a more important role in promoting teaching effect.

The system use the spring framework and MySQL database to provide development environment , the development process follow the principals of the MVC and the thought of software engineering , through the requirement analysis, overall design, detailed design, coding and testing to ensure the quality of the system. In the security aspect, the system provides convenient privilege management and fine - grained access control. And the system scalability and concurrent access is discussed in the paper.

Keywords　 Evaluation system, Spring Framework , Data statistics

目  录

摘要 I

Abstract II

第1章 绪论 1

1.1 课题背景 1

1.2 研究意义 1

1.3 国内外研究现状分析 2

1.3.1 评教指标的过于简单化 2

1.3.2 评教指标的权重过于平均 2

1.3.3 评教结果的可信度和缺乏科学的数据分析 2

1.4 系统开发的主要目标和内容 3

1.4.1 开发目标 3

1.4.2 开发内容 3

第2章 系统开发技术路线 4

2.1 技术架构 4

2.2 使用框架和技术介绍 5

2.2.1 Spring 5

2.2.2 Spring MVC 5

2.2.3 MySql 6

2.2.4 MyBatis 7

2.3 本章小结 7

第3章 需求分析 8

3.1 总体需求 8

3.2 系统功能需求分析 8

3.2.1 角色和用例图 8

3.2.2 功能模块划分 11

3.2.3 数据流向 12

3.3 系统非功能性需求分析 13

3.3.1 性能需求 13

3.3.2 界面需求 14

3.3.3 可行性分析 14

3.4 本章小结 15

第4章 系统设计 16

4.1 整体设计 16

4.2 系统设计思路 17

4.2.1 充分考虑系统的稳定性和扩展性。 17

4.2.2 合理的数据库设计和充分的性能优化。 17

4.3 登陆模块设计 18

4.4 基本信息管理模块设计 19

4.4.1 管理员管理 19

4.4.2 权限管理 20

4.4.3 评教相关信息管理 21

4.5 评教模块设计 21

4.5.1 评教指标设计 22

4.5.2 评教批次设计 23

4.5.3 评教流程设计 24

4.5.4 评教结果展示设计 25

4.6 数据导入设计 26

4.7 系统数据库设计 27

4.7.1 数据实体关系 27

4.7.2 数据表结构设计 28

4.8 本章小结 30

第5章 系统实现 31

5.1 系统功能模块实现 31

5.1.1 系统登陆 31

5.1.2 评教指标管理 33

5.1.3 评教流程 34

5.1.4 数据导入 35

5.2 安全和稳定性实现 37

5.2.1 数据效验 37

5.2.2 XSS漏洞攻击防范 38

5.2.3 并发访问 39

5.3 系统测试 39

5.3.1 单元测试 39

5.3.2 功能测试 40

5.3.3 性能测试 40

5.4 本章小结 42

结论 43

致谢 44

参考文献 45

附录 46

附录A 46

附录B 56

附录C 65

      

​
