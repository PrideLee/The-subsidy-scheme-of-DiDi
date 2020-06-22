# "Internent+" Based Subsidy Scheme of Didi Taxi Optimization
- As a hot issue attended by all society, the difficulty in taking a taxi has been affecting citizens' transportation for many years. With internent technology developed rapidly, many ridesharing apps was developed, thus through optimizing subsidy scheme to attract more drivers and optimize the dipatch scheme of taxies which will be helpful to alleviate above problem.
- Taking ShenZhen as a sample and crawling taxies driving information from ridesharing websites. In addition, define supply and demand ratio of taxies, taxi ownership (ten thousands people), the ratio of unoccupied taxies as well to investigate the matching degree between taxi sources and public requirement in different time and geographical location.
- Based on psycholological model and fuzzy mathematics, building membership function to reflect the relation between subsides and driver, passenger statisfaction. Furthermore, we also consider companies cost to adjust and optimize the subsidy aimed at rush hour and remote areas. Our subsidy scheme can balance the benefit of drivers, passengers and software companies well.

**You can dowmload the full report from [here](https://github.com/PrideLee/The-subsidy-scheme-of-DiDi/blob/master/%E5%9F%BA%E4%BA%8E%E2%80%9C%E4%BA%92%E8%81%94%E7%BD%91%2B%E2%80%9D%E7%9A%84%E5%87%BA%E7%A7%9F%E8%BD%A6%E8%A1%A5%E8%B4%B4%E6%96%B9%E6%A1%88%E4%BC%98%E5%8C%96%E7%A0%94%E7%A9%B6.pdf)**

## 项目介绍

随着“互联网+”时代的到来，各种打车软件应运而生，如何设计最优的出租车补贴方案以缓解打车难有着现实的研究意义和价值。为此我们搜集相关数据，利用数学建模的方法，研究了“互联网+”时代的出租车资源配置问题，主要工作如下：

（1）利用网络爬虫技术爬取相关平台出租车行驶数据，然后按照时间、地理位置、行驶状态进行归类整理，选择出租车总量供需比 、出租车拥有量（万人）、出租车空驶率三项指标对深圳市出租车匹配程度进行研究，建立出租车资源供求匹配程度模型。

（2）建立补贴方案吸引力模型，对“缓解打车难”的帮助程度进行评估。本文假设吸引力越大，软件使用越广泛，对“缓解打车难”帮助越大。首先，以每笔补贴金额为指标，利用模糊数学中隶属函数建立补贴金额与吸引力隶属关系式，同时结合各平台出租车补贴方案，求得当单笔补贴方案。同时考虑补贴方案随时间的推移，其吸引力发生变化，构建修正模型，得到补贴方案的综合吸引力模型。

（3）构建评价补贴方案合理性模型。该模型主要由平台经营成本，用户满意度和吸引力三因素决定。用户满意度受到补贴金额影响，因为当补贴金额较高时，司机将会拒载沿边扬招乘客而使其满意度下降。利用非线性规划求解模型，得到最优补贴结果。对于偏远地区、拥堵路段的打车难问题，本文还考虑在原有模型基础上进行扩展以权衡司机、平台以及用户三方利益。
 

<div align=center><img width="500" height="500" src="https://github.com/PrideLee/The-subsidy-scheme-of-DiDi/blob/master/taxi_distribution.png"/></div>
