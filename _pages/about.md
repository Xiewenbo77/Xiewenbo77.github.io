---
permalink: /
title: "谢文博-上海大学"
author_profile: true
redirect_from: 
  - /about/
  - /about.html 
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🙋‍♂️ <font color="#2F4F4F">个人简介</font>
谢文博，教授，博士 / 硕士生导师，任职于上海大学机电工程与自动化学院 / 无人艇工程研究院。上海市海外高层次人才相关领域研究骨干，长期从事无人系统智能控制与自主航行相关研究，担任团队无人系统研究领域主要负责人。主持军委科技委 GF 项目、国家自然科学基金面上 / 青年项目、黑龙江省优秀青年科学基金、中国博士后基金面上项目等10 余项纵向 / 横向课题，科研经费累计超千万元；作为骨干成员参与国家重大科技专项、工信部高科技船舶科研项目等，总经费达 1.28 亿元。已发表学术论文 60 余篇，其中 SCI 源期刊论文 30 余篇（第一 / 通讯作者 20 余篇），ESI 高被引论文 2 篇，入选IEEE Transactions on Fuzzy Systems“Most Popular Paper” 1 篇；授权国家发明专利 20 余项。

现任IEEE Power & Energy Society 智能电网与新技术委员会（中国）常务理事，中国指挥与控制学会智能控制与系统专委会、大模型与决策智能专业委员会委员，中国造船工程学会（水面无人装备专委会）高级会员，中国人工智能学会会员，IEEE Control Systems Society/IEEE Information Electronics Society 会员，《中国舰船研究》青年编委。曾赴澳大利亚阿德莱德大学开展博士后访学研究，与澳大利亚、英国、法国、巴西等多国高校知名学者保持紧密国际合作。

<span class='anchor' id='pub'></span>

# 📝 <font color="#2F4F4F">主要研究领域</font>
1.	无人系统自主规划、决策与控制：针对无人艇、无人气垫船、无人跨域航行器等海空无人设备的路径规划、避障、航行控制、靠离泊控制、动力定位控制、自主决策等自主智能方面进行研究；
2.	海空跨域无人集群：针对无人机、无人艇等各类无人系统构成的异构无人集群协同目标跟踪、规划、避障、编队、决策、博弈与控制领域，多无人艇对接、多无人拖轮协同作业等集群智能方面进行研究；
3.	无人系统端到端自主航行：针对自动驾驶、无人艇、无人机等各类无人系统，搭建“感知-规划”/“感知-控制”端到端系统，开展智能生成、深度学习和强化学习相关算法研究；
4.	海空跨域仿真系统：针对各类海空无人装备的具体应用场景，搭建用于无人系统训练和学习的仿真系统，从事强化学习、深度学习、虚实迁移等方面的研究；
5.	智能控制理论：针对T-S/多项式模糊系统，海上廊桥自稳系统，卫星低重力地面模拟系统等各类复杂非线性系统的控制方法进行研究。

# 🙋‍♂️ <font color="#2F4F4F">成果展示</font>
## 1. 无人系统自主规划、决策与控制

### 欠驱动无人艇控制
针对浮标型无人艇定点控位问题，考虑以环境干扰横向作用力作为非受控横荡无人艇动力学外部输入，围绕基于环境最优艏向定点控位控制策略展开深入研究，并通过某型无人艇进行海试实验，结果表明控制精度和系统能耗均得到较大幅度优化。
<div style="margin:15px 0; padding:10px; background:#f8f9fa; border-radius:8px;">
<div style="display:flex; justify-content:space-between; gap:10px; margin-bottom:10px;">
<img src="images/research1-1.png" alt="欠驱动无人艇定点控位" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research1-2.png" alt="动力定位控制系统" style="width:49%; height:auto; border-radius:4px;">
</div>
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">欠驱动无人艇最优艏向控制策略</p>
</div>

### 无人气垫船
针对无人气垫船的垫升系统和智能自主航行控制系统进行探究，并结合旋翼无人机的构型，搭建了旋翼机-气垫船一体化无人系统，为海空跨域无人集群的发展增加了重要的一类设备。
<div style="margin:10px 0; padding:8px; background:#f8f9fa; border-radius:6px;">
<img src="images/research1-3.png" alt="旋翼机-气垫船无人系统1" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research1-4.png" alt="旋翼机-气垫船无人系统2" style="width:49%; height:auto; border-radius:4px;">
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">旋翼机-气垫船无人系统</p>
</div>

### 动力定位控制系统
针对复杂海况下的船舶动力定位作业任务，考虑推进器推力受限和各类故障，研究船舶低频运动状态观测、高精度定位、循迹跟踪作业、喷泵无人艇自主靠离泊等功能，在进行实船实验过程中，与Kongsberg公司产品进行传感器完全失效时的短时（5分钟）定位控制实验，漂移距离明显降低，控制精度得到大幅提高。
<div style="margin:10px 0; padding:8px; background:#f8f9fa; border-radius:6px;">
<img src="images/research1-5.png" alt="动力定位船舶与控制系统1" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research1-6.png" alt="动力定位船舶与控制系统2" style="width:49%; height:auto; border-radius:4px;">
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">动力定位船舶与控制系统</p>
</div>

## 2.海空跨域无人集群

### 无人系统集群博弈
针对无人艇集群博弈，综合DoS攻击和追捕、围堵、驱离等具体任务，利用Nash均衡方法，对集群、博弈等策略展开了深入研究，取得了一定效果。
<div style="margin:10px 0; padding:8px; background:#f8f9fa; border-radius:6px;">
<img src="images/research2-1.png" alt="无人艇集群博弈策略1" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research2-2.png" alt="无人艇集群博弈策略2" style="width:49%; height:auto; border-radius:4px;">
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">无人艇集群博弈与对接队形变换策略</p>
</div>

### 无人拖船系统
针对大型船舶进出港时的拖轮拖拽作业问题，综合考虑受限水域环境、系统参数不确定性、运动学约束以及障碍物规避等实际问题，围绕智能无人拖船的路径规划、运动控制以及推力分配策略等问题展开了深入研究，取得了良好效果。
<div style="margin:10px 0; padding:8px; background:#f8f9fa; border-radius:6px;">
<img src="images/research2-3.png" alt="智能多无人拖船1" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research2-4.png" alt="智能多无人拖船2" style="width:49%; height:auto; border-radius:4px;">
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">智能多无人拖船系统</p>
</div>

### 无人船“海上列车”
针对多无人艇航行过程中进行组合编队问题，研究组建“海上列车”的协同运动控制过程，综合考虑运动学和动力学约束、多艇间水动力相互影响，海浪导致高频运动不利于对接等因素，解决多艇逼近和对接运动过程的规划与控制问题。
<div style="margin:10px 0; padding:8px; background:#f8f9fa; border-radius:6px;">
<img src="images/research2-5.png" alt="无人艇组建 “海上列车”1" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research2-6.png" alt="无人艇组建 “海上列车”2" style="width:49%; height:auto; border-radius:4px;">
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">无人艇组建 “海上列车”</p>
</div>

## 3.自主智能与智能控制

### 感知-规划-控制端到端方法
针对感知-规划研究端到端设计方法，以保证无人系统能够在感知和决策层面获得全局最优解；同时对规划-控制研究端到端设计方法，保证规划层面能充分考虑无人平台动力学特性。
<div style="margin:10px 0; padding:8px; background:#f8f9fa; border-radius:6px;">
<img src="images/research3-1.png" alt="视觉感知-规划端到端在虚拟环境下的自主驾驶案例" style="width:49%; height:auto; border-radius:4px;">

<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">视觉感知-规划端到端在虚拟环境下的自主驾驶案例</p>
</div>

### 模糊控制理论研究
针对非线性系统的鲁棒等控制问题，基于T-S/多项式模糊系统，研究观测器-控制器结构的输出反馈设计问题，以及在稳定性分析中更有效引入隶属度函数信息并增强鲁棒性的方法，在国际上获得了一定的认可。
<div style="margin:10px 0; padding:8px; background:#f8f9fa; border-radius:6px;">
<img src="images/research3-2.png" alt="各类T-S/多项式模糊系统隶属度信息使用策略1" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research3-3.png" alt="各类T-S/多项式模糊系统隶属度信息使用策略2" style="width:49%; height:auto; border-radius:4px;">
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">各类T-S/多项式模糊系统隶属度信息使用策略</p>
</div>

### 海上廊桥
针对恶劣海洋环境下，船舶之间以及船舶与海上工程平台之间的人员物资转运问题，综合考虑运动学和动力学约束，海浪的随机干扰以及廊桥表面的未知时变负载等因素，对基于混联等机构的海上廊桥控制问题进行了深入研究，取得了良好效果。
<div style="margin:10px 0; padding:8px; background:#f8f9fa; border-radius:6px;">
<img src="images/research3-4.png" alt="海上运转廊桥1" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research3-5.png" alt="海上运转廊桥2" style="width:49%; height:auto; border-radius:4px;">
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">海上运转廊桥</p>
</div>

# 📝 <font color="#4A708B">代表性成果</font>

1. Zhenglin Li, Wenbo Zheng, Le Yang, Liyan Ma, Yang Zhou, Yan Peng. MonoAux: Fully Exploiting Auxiliary Information and Uncertainty for Monocular 3D Object Detection. Cyborg and Bionic Systems, 2024, 5: 0097.
2. Jiasen Wang, Zhenglin Li, Ke Sun, Xianyuan Liu, Yang Zhou. DVPE: Divided View Position Embedding for Multi-View 3D Object Detection. In Proceedings of the Thirty-Third International Joint Conference on Artificial Intelligence, pp. 6877-6885. 2024.
3. Zhenglin Li, Tianxin Yuan, Liyan Ma, Yang Zhou, Yan Peng. Target Detection for USVs by Radar-vision Fusion with Swag-robust Distance-aware Probabilistic Multi-modal Data Association, IEEE Sensors Journal, 2024, 5: 20177 – 20187.
4. Zhenglin Li, Lyudmila S. Mihaylova, Olga Isupova, and Lucile Rossi. "Autonomous flame detection in videos with a Dirichlet process Gaussian mixture color model." IEEE Transactions on Industrial Informatics, 2017, vol. 14, no. 3: 1146-1154.
5. Xiang Liu, Zhenglin Li, Yang Zhou, Yan Peng, Jun Luo. Camera–Radar Fusion with Modality Interaction and Radar Gaussian Expansion for 3D Object Detection. Cyborg and Bionic Systems, 2024, 5: 0079.
6. Zhenglin Li, Lyudmila Mihaylova, and Le Yang. "A deep learning framework for autonomous flame detection." Neurocomputing, 2021, 448 : 205-216.
7. Chuan Lin, Guangjie Han, Qiuzi Tao, Li Liu, Syed Bilal Hussain Shah, Tongwei Zhang. Underwater Equipotential Line Tracking Based on Self-Attention Embedded Multiagent Reinforcement Learning Toward AUV-Based ITS. IEEE Transactions on Intelligent Transportation Systems, 2023, 24(8): 8580–8591.
8. Ke Sun, Zhenglin Li. Sparse Data Injection Attacks on Smart Grid: An Information-Theoretic Approach. IEEE Sensors Journal, 2022, 22(14): 14553–14562.
9. Zhenglin Li, Mahnaz Arvaneh, Heather E. Elphick, Ruth N. Kingshott, Lyudmila S. Mihaylova. A Dirichlet Process Mixture Model for Autonomous Sleep Apnea Detection Using Oxygen Saturation Data. 2020 IEEE 23rd International Conference on Information Fusion (FUSION), 2020, pp. 1–8.
10. Wenbo Zheng, Zhenglin Li, Wenbo Xie, Songyi Zhong, Tianxin Yuan, Yan Peng. SCON: Semantic Cross-Modal Data Association Offset Estimation Network for Radar-Vision Feature Fusion. 2024 IEEE International Conference on Unmanned Systems (ICUS), 2024, pp. 1516–1520.


<span class='anchor' id='project'></span>

# 📝 <font color="#4A708B">科研项目（主持与在研项目）</font>

1. **军委科技委“XXXXXX”项目子课题**，XX环境理解与XX安全控制技术研究，主持，505万元
2. **国家自然科学基金青年项目**，面向未知多变场景的视觉自主火灾监测，30万元，负责人
3. **上海市启明星培育（扬帆专项）**，基于无人艇的海洋温盐场重构及传感器部署智能规划，20万元，负责人

# 📝 <font color="#4A708B">联系方式</font>

- **邮箱**：[zhenglin_li@shu.edu.cn](mailto:zhenglin_li@shu.edu.cn)
- **地址**：上海市，上海大学未来技术学院/人工智能研究院
