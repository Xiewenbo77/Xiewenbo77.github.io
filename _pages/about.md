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

🙋‍♂️ <font color="#2F4F4F">成果展示</font>
## 1. **无人系统自主规划、决策与控制

### 欠驱动无人艇控制
针对浮标型无人艇定点控位问题，考虑以环境干扰横向作用力作为非受控横荡无人艇动力学外部输入，围绕基于环境最优艏向定点控位控制策略展开深入研究，并通过某型无人艇进行海试实验，结果表明控制精度和系统能耗均得到较大幅度优化。
<div style="margin:15px 0; padding:10px; background:#f8f9fa; border-radius:8px;">
<div style="display:flex; justify-content:space-between; gap:10px; margin-bottom:10px;">
<img src="images/research1-1.png" alt="欠驱动无人艇定点控位" style="width:49%; height:auto; border-radius:4px;">
<img src="images/research1-2.png" alt="动力定位控制系统" style="width:49%; height:auto; border-radius:4px;">
</div>
<p style="font-size:14px; color:#666; text-align:center; margin:5px 0 0;">欠驱动无人艇最优艏向控制策略海试航迹对比</p>
</div>

### 还恐吓跨域无人集群智能

### 视觉-毫米波雷达融合感知

<div class='paper-box'>
  <!-- 第一部分：视觉-毫米波雷达动态交互3D目标检测 -->
  <div>
    <p>视觉-毫米波雷达动态交互3D目标检测</p>
    <div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
      <figure style="text-align: center; margin: 0 5px; width: 48%;">
        <img src="images/img3.jpg" alt="图像3" style="width: 100%; height: auto; object-fit: contain;">
      </figure>
      <figure style="text-align: center; margin: 0 5px; width: 48%;">
        <img src="images/img4.jpg" alt="图像4" style="width: 100%; height: auto; object-fit: contain;">
      </figure>
    </div>
  </div>

  <!-- 第二部分：视觉光流与毫米波雷达融合的关键目标速度解构 -->
  <div>
    <p>视觉光流与毫米波雷达融合的关键目标速度解构</p>
    <div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
      <figure style="text-align: center; margin: 0 5px; width: 48%;">
        <video controls style="width: 100%; height: auto; object-fit: contain;">
          <source src="images/video2.mp4" type="video/mp4">
        </video>
      </figure>
      <figure style="text-align: center; margin: 0 5px; width: 48%;">
        <video controls style="width: 100%; height: auto; object-fit: contain;">
          <source src="images/video3.mp4" type="video/mp4">
        </video>
      </figure>
    </div>
  </div>
</div>


### 端到端系统

<div class='paper-box'>
  <video controls width="100%">
    <source src='images/output_2.mp4' type="video/mp4">
  </video>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/img11.jpg' alt="图像11" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">
- 大模型赋能垂直领域任务  
- 端到端信息交互优化集群协同  
- 减少累积误差，实现精确控制  
- 降低时间延迟，适应高动态水面场景  
- 船舶水动力学消除摇荡影响  
- 感知-规划端到端系统不确定性
</div>
</div>


## 2. **机器人训练数据生成与增强**：包括新视角图像合成、多模态数据生成、数据增强、风格迁移等；

<div class='paper-box'>
  <h3>3D目标检测的分割视角位置编码</h3>
  <div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
    <figure style="text-align: center; margin: 0 5px; width: 48%;">
      <img src="images/img5.jpg" alt="图像5" style="width: 100%; height: auto; object-fit: contain;">
    </figure>
    <figure style="text-align: center; margin: 0 5px; width: 48%;">
      <img src="images/img6.jpg" alt="图像6" style="width: 100%; height: auto; object-fit: contain;">
    </figure>
  </div>
  <div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
    <figure style="text-align:intrepreter: center; margin: 0 5px;">
      <img src="images/img7.jpg" alt="图像7" width="100%">
    </figure>
    <figure style="text-align: center; margin: 0 5px;">
      <img src="images/img8.jpg" alt="图像8" width="100%">
    </figure>
    <figure style="text-align: center; margin: 0 5px;">
      <img src="images/img9.jpg" alt="图像9" width="100%">
    </figure>
  </div>
  <p>将全局空间进行多层级分割，与虚拟视角空间对齐并进行位置编码，以低计算量实现全局注意力</p>
  <p style="font-size: smaller; margin-top: 10px;">DVPE: divided view position embedding for multi-view 3D object detection，IJCAI 2024（CCF A）</p>
</div>

## 3. **机器学习与计算机视觉**：包括信息融合、深度学习的不确定性量化与分析、大模型微调、增量学习/终身学习等。
### 环境感知不确定性建模

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/img11.jpg' alt="图像11" width="100%">
    </div>
  </div>
<div class='paper-box-text' markdown="1">
MonoAux: Fully Exploiting Auxiliary Information and Uncertainty for Monocular 3D Object Detection, Cyborg and Bionic System（IF 10.5), 2024
- 不确定性不可避免，不应忽视
- 量化不确定性对自动驾驶安全至关重要
- 考虑不确定性能有效提升感知精度
- 为预测、规划提供重要参考信息
</div>
</div>

<div class='paper-box'>
    <div style="display: flex; justify-content: space-between; margin-bottom: 10px;">
      <figure style="text-align: center; margin: 0 5px; width: 48%;">
        <img src="images/img10.jpg" alt="图像10" style="width: 100%; height: auto; object-fit: contain;">
        <figcaption>环境感知结果不确定性量化</figcaption>
      </figure>
      <figure style="text-align: center; margin: 0 5px; width: 48%;">
        <img src="images/img12.jpg" alt="图像12" style="width: 100%; height: auto; object-fit: contain;">
        <figcaption>引入不确定性有效改善小目标与部分遮挡目标的检测精度</figcaption>
      </figure>
    </div>
</div>




<span class='anchor' id='publication'></span>


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
