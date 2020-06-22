# "Internent+" Based Subsidy Scheme of Didi Taxi Optimization
- As a hot issue attended by all society, the difficulty in taking a taxi has been affecting citizens' transportation for many years. With internent technology developed rapidly, many ridesharing apps was developed, thus through optimizing subsidy scheme to attract more drivers and optimize the dipatch scheme of taxies which will be helpful to alleviate above problem.
- Taking ShenZhen as a sample and crawling taxies driving information from ridesharing websites. In addition, define supply and demand ratio of taxies, taxi ownership (ten thousands people), the ratio of unoccupied taxies as well to investigate the matching degree between taxi sources and public requirement in different time and geographical location.
- Based on psycholological model and fuzzy mathematics, building membership function to reflect the relation between subsides and driver, passenger statisfaction. Furthermore, we also consider companies cost to adjust and optimize the subsidy aimed at rush hour and remote areas. Our subsidy scheme can balance the benefit of drivers, passengers and software companies well.

**You can dowmload the full report from [here](https://github.com/PrideLee/The-subsidy-scheme-of-DiDi/blob/master/%E5%9F%BA%E4%BA%8E%E2%80%9C%E4%BA%92%E8%81%94%E7%BD%91%2B%E2%80%9D%E7%9A%84%E5%87%BA%E7%A7%9F%E8%BD%A6%E8%A1%A5%E8%B4%B4%E6%96%B9%E6%A1%88%E4%BC%98%E5%8C%96%E7%A0%94%E7%A9%B6.pdf)**

## 项目介绍

“打车难”问题是国民关注的热点问题之一。随着“互联网+”时代的到来，各种打车软件应运而生，并推出了多种出租车补贴方案，各种补贴方案是否能缓解打车难，仍有待研究。为此我们搜集相关数据，利用数学建模的方法，研究了“互联网+”时代的出租车资源配置问题，主要工作如下： 
（1）利用网络爬虫技术爬取相关平台出租车行驶数据，并剔除空间、状态上不合理的值。然后按照时间、经纬度、行驶状态进行归类整理。建立出租车资源供求匹配程度模型。这里选择出租车总量供需比 、出租车拥有量（万人） 、出租车空驶率三项指标对深圳市出租车匹配程度进行研究。首先，基于出租车总量供需比研究出租车的供求匹配程度，通过查找资料得到出租车需求量的测定模型，代入数据得到深圳市出租车需求量为26110辆，与实际出租车供给量15035辆作比，求得出租车总量供需比为0.5758，表明2011年深圳市出租车总量的供需匹配程度较差。然后，基于出租车拥有量（万人）研究不同空间出租车的供求匹配程度，数据中深圳市各地区载客点数目比重可评估各地区出租车供给量，与该地区常住人口数（万人）求比值，得到深圳市不同空间出租车拥有量（万人），其中罗湖区、福田区和南山区的出租车拥有量大，出租车供求匹配程度高，而坪山新区和光明新区的出租车拥有量小，出租车供求匹配程度低。最后，基于出租车空驶率研究不同时间出租车资源的供求匹配程度。将一天分为24个时间单位，由数据得到各时间段的空驶时间和运营时间，两者相比得到各时间段的小时平均空驶率，其中在23:00—7:00出租车空驶率最高，出租车供求匹配程度较低，而在8:00—10:00和14:00—18:00空驶率较低，出租车供求匹配程度较高。 
（2）通过建立补贴方案吸引力模型，对“缓解打车难”的帮助程度进行评估。这里认为吸引力越大，软件使用越广泛，对“缓解打车难”帮助越大。首先，以每笔补贴金额为指标，利用模糊数学中隶属函数建立补贴金额与吸引力隶属关系式，其中吸引力因子为6.414。结合各公司出租车补贴方案，求得当单笔补贴方案为10元和2元时吸引力分别为0.91220，0.0927。由于补贴方案随时间的推移，其吸引力会发生变化，构建修正模型，得到补贴方案的综合吸引力模型，求得在每笔补贴方案为10元和2元时其值分别为：6.4880,0.6595。 
（3）设计打车软件补贴方案，并评价方案的合理性。其实质是构建评价补贴方案合理性模型。该模型主要由公司经营成本，顾客满意度和吸引力三因素决定。顾客满意度受到补贴金额影响，因为当补贴金额较高时，司机将会拒载沿边扬招乘客而使其满意度下降。利用非线性规划求解该模型，得到每笔补贴6.53元时结果最优。对于偏远地区、拥堵路段的打车难问题，本文通过建立司机满意度模型并与公司成本的实际相结合，得到对单个出租车的月补贴为860—1035元较合适。  


<div align=center><img width="500" height="500" src="https://github.com/PrideLee/The-subsidy-scheme-of-DiDi/blob/master/taxi_distribution.png"/></div>
