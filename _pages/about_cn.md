---
permalink: /cn/
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about_cn/
  - /about_cn.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

赵聪，同济大学交通学院副教授，加州大学伯克利分校联合培养博士，研究方向为AI + 交通信息与控制、车路协同与自动驾驶。入选中国科协青年人才托举工程、上海市青年科技启明星人才（A类）、东方英才青年人才等。担任中国公路学会自动驾驶工作委员会委员、世界交通运输大会自动驾驶路车协作技术委员会委员等。曾在国家发展改革委挂职锻炼，参编现代综合交通发展“十五五”规划、公路发展“十五五”规划，《节能与新能源汽车技术路线图3.0》智能网联汽车部分主要执笔人，积极服务国家战略与行业高质量发展。

近五年，以一作/通讯在交通、车辆、人工智能、控制、管理等学科交叉期刊发表论文45篇，其中一区Top期刊论文（IF≥7.4）21篇，ESI高被引论文11篇、热点论文2篇，入选《中国公路学报》（影响因子学科第一）年度优秀论文、交通运输重大科技创新成果（论文类）等。以第一发明人授权中国发明专利15项、英国专利6项，部分专利以授权使用的方式实现成果转化。参编上海市地方标准《港口自动驾驶集装箱卡车运行技术要求》，中国汽车工程学会国内首套车路协同自动驾驶系统功能可信性测评方法系列标准（共5部）、中国智能交通协会《弹性交通信息物理系统架构城市交通》等标准规范。成果受到国内外同行广泛关注，得到中国工程院院士、美国工程院院士、欧洲科学院院士、加拿大工程院院士、IEEE Fellow等专家的正面引用评价。

面向智慧港口、智慧高速、自主泊车等应用需求明确、区域边界可控的典型场景，将基础研究成果“可信感知-协同认知-领航控制”进行产学研协同模块化开发、系统集成与推广应用，创新研发形成室内外一体化泊位级导航系统和自主代客泊车系统，在北上广深等城市100余个大型停车场规模化应用；有效支撑港口自动化运输系统研发及体系化建设，成功落地上海港（吞吐量连续15年世界第一）、秘鲁钱凯港（“一带一路”标志性工程）等国内外重要港口。作为主要完成人的项目“城市停车全域数字化与管理智能化关键技术及应用”获上海市科技进步一等奖（排名第2，2022）、“智能路网交通全息可信感知与动静协同调控关键技术及应用”获中国发明协会发明创新一等奖（排名第1，2024）。

主讲交通数据分析、运输经济学、交通科技竞赛等交叉学科课程。指导本科生获得全国交通科技大赛一等奖、全国高校智能交通创新与创业大赛一等奖等荣誉。指导的多位本科生、研究生毕业赴UC-Berkeley、MIT、清华大学、北京大学等国内外一流高校深造。

<span class='anchor' id='educations'></span>
# 📖 教育经历
- *2010.09 - 2014.07*, [同济大学](https://www.tongji.edu.cn/), 交通工程, 学士.
- *2014.09 - 2017.07*, [同济大学](https://www.tongji.edu.cn/), 交通运输工程, 硕士.
- *2018.11 - 2019.12*, [加州大学伯克利分校](https://www.berkeley.edu/), 交通研究院, 联合培养博士.
- *2017.09 - 2020.08*, [同济大学](https://www.tongji.edu.cn/), 交通运输工程, 博士.

<span class='anchor' id='professional-experiences'></span>
# 💻 工作经历
- *2020.11 - 2024.02*, [同济大学](https://www.tongji.edu.cn/), 交通学院, 博士后（导师：何积丰院士）.
- *2024.03 - Present* , [同济大学](https://www.tongji.edu.cn/), 交通学院, 副教授.
- *2025.01 - Present* , 国家发展和改革委员会, 基础设施发展司, 借调.

<span class='anchor' id='projects'></span>

# 🔍 科研项目
<!-- 补充你的项目内容 -->
- *年.月 - 年.月*, [项目名称](https://example.com/) (经费/级别), 角色, 项目描述.
- *年.月 - 年.月*, [项目名称](https://example.com/) (经费/级别), 角色, 项目描述.

<span class='anchor' id='-news'></span>

# 📰 新闻动态
<style>
/* 1. 新闻容器：弹性布局 */
.news-grid {
  display: flex;
  flex-wrap: wrap; /* 允许换行 */
  gap: 20px;       /* 卡片之间的间距 */
  margin-top: 20px;
  width: 100%;     /* 确保容器占满宽度 */
}

/* 2. 新闻卡片（预览状态） */
.news-card {
  /* 核心修改：强制宽度为50%减去一半间距 */
  width: calc(50% - 10px) !important; 
  background-color: #fcfcfc;
  border: 1px solid #eee;
  border-radius: 8px;
  padding: 20px;
  cursor: pointer;
  position: relative;
  overflow: hidden;
  height: 220px; 
  transition: all 0.3s ease;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  box-sizing: border-box; /* 确保内边距不撑大盒子 */
  margin-bottom: 0; /* 移除可能的默认下边距，由 gap 控制 */
}

.news-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 15px rgba(0,0,0,0.1);
  border-color: #d9534f;
}

.news-card::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 60px;
  background: linear-gradient(to bottom, rgba(252,252,252,0), rgba(252,252,252,1));
  pointer-events: none;
}

/* 3. 手机端适配：屏幕小于 768px 时强制变为单列 */
@media (max-width: 768px) {
  .news-card {
    width: 100% !important; /* 手机上强制占满一行 */
  }
}

/* 3. 模态框（弹窗背景） */
.news-modal-overlay {
  display: none; /* 默认隐藏 */
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.6); /* 半透明黑色背景 */
  z-index: 9999;
  justify-content: center;
  align-items: center;
  padding: 20px;
  backdrop-filter: blur(5px); /* 背景模糊效果 */
}

/* 4. 模态框内容区域（详细内容） */
.news-modal-content {
  background-color: #fff;
  width: 100%;
  max-width: 800px; /* 最大宽度 */
  max-height: 85vh; /* 最大高度不超过视窗的85% */
  overflow-y: auto; /* 内容多了可以滚动 */
  border-radius: 12px;
  padding: 40px;
  position: relative;
  box-shadow: 0 10px 30px rgba(0,0,0,0.3);
  animation: modalPop 0.3s ease-out;
}

/* 弹窗出来的动画 */
@keyframes modalPop {
  from { transform: scale(0.9); opacity: 0; }
  to { transform: scale(1); opacity: 1; }
}

/* 关闭按钮 */
.news-close-btn {
  position: absolute;
  top: 15px;
  right: 20px;
  font-size: 30px;
  color: #aaa;
  cursor: pointer;
  transition: color 0.2s;
  line-height: 1;
}

.news-close-btn:hover {
  color: #333;
}
</style>

<div class="news-grid">
<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 12px;">
      <span style="background-color: #d9534f; color: white; padding: 3px 8px; border-radius: 4px; font-size: 0.8em; vertical-align: middle; margin-right: 8px;">喜讯</span>
      <span style="vertical-align: middle;">课题组论文入选工程领域 ESI 全球 Top 1% 高被引论文和研究前沿核心论文</span>
    </div>
    <div style="color: #444; font-size: 0.95em; line-height: 1.8; text-align: justify;">
      <p style="margin-bottom: 15px;">
        根据基本科学指标库 ESI（Essential Science Indicators）最新统计数据，以课题组<strong>赵聪博士</strong>为第一作者，杜豫川教授为通讯作者，同济大学道路与交通工程教育部重点实验室为第一完成单位，发表在智能交通领域顶级国际期刊 <em>Transportation Research Part C: Emerging Technologies</em>（中科院一区，Top 期刊，IF: 9.022）的论文“Macroscopic modeling and dynamic control of on-street cruising-for-parking of autonomous vehicles in a multi-region urban road network”（2021年，128卷）入选<strong>工程领域 ESI 全球 TOP 1.0% 高被引论文和研究前沿核心论文</strong>。
      </p>
      <p>
        该研究聚焦城市“停车难”痛点问题，面向汽车智能化、网联化发展趋势，揭示了自动驾驶环境下路网静态停车与动态交通的交互影响规律，提出了中心化网联云调度的城市停车管理新范式。为实现区域供需动态平衡，减少停车巡游，论文提出了“区域间总量控制-区域内动态调度-车位级智能匹配”的三层调度框架，构建了动静一体的宏观交通分析模型，拓展了现有的理论体系。研究成果为智能网联环境下的城市停车管理提供了决策支持工具，具有广阔的应用前景。
      </p>
    </div>
</div>

<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 12px;">
      <span style="background-color: #d9534f; color: white; padding: 3px 8px; border-radius: 4px; font-size: 0.8em; vertical-align: middle; margin-right: 8px;">喜讯</span>
      <span style="vertical-align: middle;">杜豫川教授团队中科院一区、Top 期刊论文入选 ESI 全球 Top 1% 高被引论文</span>
    </div>
    <div style="color: #444; font-size: 0.95em; line-height: 1.8; text-align: justify;">
      <p style="margin-bottom: 15px;">
        根据基本科学指标库 ESI 最新统计数据，以同济大学智能交通新兴计算与感知研究课题组杜豫川教授为第一作者，<strong>赵聪博士</strong>为通讯作者，同济大学道路与交通工程教育部重点实验室为第一完成单位，发表在交通运输领域顶级国际期刊 <em>Transportation Research Part C: Emerging Technologies</em>（中科院一区，Top 期刊，IF: 9.022）的论文“Comfortable and energy-efficient speed control of autonomous vehicles on rough pavements using deep reinforcement learning”（2022年，134卷）入选<strong>工程领域 ESI 全球 TOP 1.0% 高被引论文</strong>。
      </p>
      <p>
        该研究面向车路协同自动驾驶环境，为提升车辆行驶的舒适性和节能性，率先利用海量路面数据和新兴深度强化学习算法，构建了一种高效的自动驾驶智能决策控制框架。研究创新性提出“最大舒适速度”概念，以表征自动驾驶车辆前方复杂的路面环境信息；进而利用深度强化学习方法构建速度决策模型，使用海量的实证路面数据和高可信的车路交互仿真环境训练深度神经网络参数。实验结果证明，相比于传统的模型预测控制方法，该模型在舒适度、节能和实时计算效率上分别提升了 8.22%、24.37% 和 94.38%，为车路协同环境下的速度决策控制提供了新思路。
      </p>
    </div>
</div>
</div>

<div style="height: 24px;"></div>
<span class='anchor' id='-publications'></span>
# 📝 发表论文
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src="{{ '/images/paper_35.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🔥`New！` [BELT-Fusion: Bayesian Evidential Late Fusion for Trustworthy V2X Perception](https://doi.org/10.1109/tits.2025.3625597)

Zhiguo Zhao, **Cong Zhao\***, Kun Chen, Yuxiong Ji\*, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src="{{ '/images/paper_34.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🔥`New！` [PMI-Transformer: Parking Memory Interaction Transformer for Vehicle Intent Prediction via Cooperative Vehicle-Infrastructure Systems](https://doi.org/10.1109/tits.2025.3614199)

**Cong Zhao**, Tianyi Ji\*, Andi Song, Yuxiong Ji, Chao Wang, Yuchuan Du\*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src="{{ '/images/paper_33.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🔥`New！` [Uncertainty-aware multi-vehicle detection and tracking using roadside 3D point clouds](https://doi.org/10.1109/tits.2025.3586875)

Kun Chen, **Cong Zhao\***, Yuxiong Ji\*, Chao Wang, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src="{{ '/images/paper_32.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🔥`New！` [A data-driven and kinematics-aware approach to reconstruct full-sample vehicle trajectories from low-quality roadside perception data](https://doi.org/10.1109/tits.2025.3580549)

Zimu Zeng, **Cong Zhao\***, Shiyu Wang, Yuxiong Ji, Chao Wang, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src="{{ '/images/paper_31.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transportmetrica A: Transport Science

🔥`New！` [A novel ellipsoidal safety potential field model for quantifying driving risk](https://doi.org/10.1080/23249935.2025.2522361)

Cailin Lei, **Cong Zhao\***, Kun Chen, Yuxiong Ji\*, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src="{{ '/images/paper_30.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Computer-Aided Civil and Infrastructure Engineering

🔥`New！` [Skill‐abstracting continual reinforcement learning for safe, efficient, and comfortable autonomous driving through vehicle–cloud collaboration](https://doi.org/10.1111/mice.13503)

Jing Chen, **Cong Zhao\***, Kun Gao\*, Yuxiong Ji, Yuchuan Du 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src="{{ '/images/paper_29.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🔥`New！` [Safety field-based vehicle-infrastructure cooperative perception for autonomous driving using 3d point clouds](https://doi.org/10.1109/tits.2025.3546980)

**Cong Zhao**, Delong Ding, Cailin Lei\*, Shiyu Wang, Yuxiong Ji\*, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src="{{ '/images/paper_28.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🔥`New！` [Accelerated Testing and Evaluation for Black-Box Autonomous Driving Systems via Adaptive Markov Chain Monte Carlo](https://doi.org/10.1109/tits.2024.3525059)

Yuxiong Ji, Zhongke Xu, **Cong Zhao\***, Kun Chen, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src="{{ '/images/paper_27.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
International Journal of Transportation Science and Technology

[Learning to search for parking like a human: A deep inverse reinforcement learning approach](https://doi.org/10.1016/j.ijtst.2024.11.007)

Shiyu Wang, Haiyan Yang, Yijia Tang, Jing Chen, **Cong Zhao\***, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src="{{ '/images/paper_26.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IET Intelligent Transport Systems

[Comfortable driving control for connected automated vehicles based on deep reinforcement learning and knowledge transfer](https://doi.org/10.1049/itr2.12540)

Chuna Wu, Jing Chen\*, Jinqiang Yao, Tianyi Chen, Jing Cao, **Cong Zhao\***

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src="{{ '/images/paper_25.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transportation Research Part B: Methodological

[Beyond centralization: Non-cooperative perimeter control with extended mean-field reinforcement learning in urban road networks](https://doi.org/10.1016/j.trb.2024.103016)

Xinghua Li, Xinyuan Zhang, Xinwu Qian, **Cong Zhao**, Yuntao Guo\*, Srinivas Peeta

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src="{{ '/images/paper_24.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Expert Systems with Applications

[A two-stage framework for parking search behavior prediction through adversarial inverse reinforcement learning and transformer](https://doi.org/10.1016/j.eswa.2024.124548)

Tianyi Ji, **Cong Zhao\***, Yuxiong Ji, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src="{{ '/images/paper_23.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Knowledge-Based Systems

[Multi-modal trajectory forecasting with Multi-scale Interactions and Multi-pseudo-target Supervision](https://doi.org/10.1016/j.knosys.2024.111903)

**Cong Zhao**, Andi Song, Zimu Zeng, Yuxiong Ji\*, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src="{{ '/images/paper_22.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

[Graph matching-based spatiotemporal calibration of roadside sensors in cooperative vehicle-infrastructure systems](https://doi.org/10.1109/tits.2024.3374281)

**Cong Zhao**, Delong Ding, Yupeng Shi, Yuxiong Ji\*, Yuchuan Du\*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src="{{ '/images/paper_21.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

[A rapid and convenient spatiotemporal calibration method of roadside sensors using floating connected and automated vehicle data](https://doi.org/10.1109/tits.2024.3366758)

**Cong Zhao**, Yupeng Shi, Yuchuan Du\*, Shengchuan Jiang, Yuxiong Ji, Xiangmo Zhao

</div>
</div>

<details>
  <summary style="cursor: pointer; color: #007bff; font-weight: bold; margin: 20px 0;">👉 Click to view Past Publications (点击查看往期论文)</summary>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src="{{ '/images/paper_20.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Tunnelling and Underground Space Technology

🏆`ESI高被引论文` [Understanding traffic bottlenecks of long freeway tunnels based on a novel location-dependent lighting-related car-following model](https://doi.org/10.1016/j.tust.2023.105098)

Shanchuan Yu, **Cong Zhao\***, Lang Song, Yishun Li, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src="{{ '/images/paper_19.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🏆`ESI高被引论文` [Data-driven indoor positioning correction for infrastructure-enabled autonomous driving systems: A lifelong framework](https://doi.org/10.1109/tits.2022.3233563)

**Cong Zhao**, Andi Song, Yifan Zhu, Shengchuan Jiang, Feixiong Liao, Yuchuan Du\*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src="{{ '/images/paper_18.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🏆`ESI高被引论文` [TriPField: A 3D potential field model and its applications to local path planning of autonomous vehicles](https://doi.org/10.1109/tits.2022.3231259)

Yuxiong Ji, Lantao Ni, **Cong Zhao\***, Cailin Lei, Yuchuan Du, Wenshuo Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src="{{ '/images/paper_17.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
International Journal of Environmental Research and Public Health

🏆`ESI高被引论文` [Safe, efficient, and comfortable autonomous driving based on cooperative vehicle infrastructure system](https://doi.org/10.3390/ijerph20010893)

Jing Chen, **Cong Zhao\***, Shengchuan Jiang, Xinyuan Zhang, Zhongxin Li, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src="{{ '/images/paper_16.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
International Journal of Environmental Research and Public Health

🏆`ESI高被引论文` [Analysis of perception accuracy of roadside millimeter-wave radar for traffic risk assessment and early warning systems](https://doi.org/10.3390/ijerph20010879)

**Cong Zhao**, Delong Ding, Zhouyang Du, Yupeng Shi, Guimin Su, Shanchuan Yu\*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src="{{ '/images/paper_15.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Computer-Aided Civil and Infrastructure Engineering

[A hierarchical framework for improving ride comfort of autonomous vehicles via deep reinforcement learning with external knowledge](https://doi.org/10.1111/mice.12934)

Yuchuan Du, Jing Chen, **Cong Zhao\***, Feixiong Liao, Meixin Zhu

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src="{{ '/images/paper_14.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IET Intelligent Transport Systems

[Identifying and correcting the errors of vehicle trajectories from roadside millimetre‐wave radars](https://doi.org/10.1049/itr2.12268)

Cailin Lei, **Cong Zhao**, Yuxiong Ji\*, Yu Shen, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_13.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transportation Research Part C: Emerging Technologies

[TrajGAT: A map-embedded graph attention network for real-time vehicle trajectory imputation of roadside perception](https://doi.org/10.1016/j.trc.2022.103787)

**Cong Zhao**, Andi Song, Yuchuan Du\*, Biao Yang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_12.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
中国公路学报

[智能网联环境下路侧感知单元数据质量在线监测框架](https://doi.org/10.19721/j.cnki.1001-7372.2022.03.023)

杜豫川, 师钰鹏, 都州扬, **赵 聪\***, 暨育雄

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_11.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Computers and Electrical Engineering

[A Lifelong Framework for Data Quality Monitoring of Roadside Sensors in Cooperative Vehicle-Infrastructure Systems](https://doi.org/10.1016/J.COMPELECENG.2022.108030)

Yuchuan Du, Yupeng Shi, **Cong Zhao\***, Zhouyang Du, Yuxiong Ji

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_10.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IET Intelligent Transport Systems

[Quantifying the Performance and Optimizing the Placement of Roadside Sensors for Cooperative Vehicle-Infrastructure Systems](https://doi.org/10.1049/itr2.12185)

Yuchuan Du, Fengqi Wang, **Cong Zhao\***, Yifan Zhu, Yuxiong Ji

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_09.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🏆`ESI高被引论文` [A novel direct trajectory planning approach based on generative adversarial networks and rapidly-exploring random tree](https://doi.org/10.1109/tits.2022.3164391)

**Cong Zhao**, Yifan Zhu, Yuchuan Du\*, Feixiong Liao, Ching-Yao Chan

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_08.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transportation Research Part C: Emerging Technologies

[Online parking assignment in an environment of partially connected vehicles: A multi-agent deep reinforcement learning approach](https://doi.org/10.1016/j.trc.2022.103624)

Xinyuan Zhang, **Cong Zhao\***, Feixiong Liao, Xinghua Li, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_07.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transportation Research Part C: Emerging Technologies

🏆`ESI高被引论文` [Comfortable and energy-efficient speed control of autonomous vehicles on rough pavements using deep reinforcement learning](https://doi.org/10.1016/j.trc.2021.103489)

Yuchuan Du, Jing Chen, **Cong Zhao\***, Chenglong Liu, Feixiong Liao, Ching-Yao Chan

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_06.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Journal of Transportation Engineering, Part A: Systems

🏆`ESI高被引论文` [From Search-for-Parking to Dispatch-for-Parking in an Era of Connected and Automated Vehicles: A Macroscopic Approach](https://doi.org/10.1061/jtepbs.0000640)

**Cong Zhao**, Jing Cao\*, Xinyuan Zhang, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src="{{ '/images/paper_05.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems, 23(11), 22278-22289.

🔥`ESI全球Top 0.1%热点论文` [A novel spatio-temporal synchronization method of roadside asynchronous MMW radar-camera for sensor fusion](https://doi.org/10.1109/tits.2021.3119079)

Yuchuan Du, Bohao Qin, **Cong Zhao\***, Yifan Zhu, Jing Cao, Yuxiong Ji

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021</div><img src="{{ '/images/paper_04.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
中国公路学报

[路侧感知车辆轨迹数据质量智能评估方法](https://doi.org/10.19721/j.cnki.1001-7372.2021.07.013)

杜豫川, 都州扬, 师钰鹏, **赵 聪\***, 暨育雄

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021</div><img src="{{ '/images/paper_03.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Journal of Advanced Transportation

[New generation of smart highway: Framework and insights](https://doi.org/10.1155/2021/9445070)

Chenglong Liu, Yuchuan Du\*, Yiheng Ge, Difei Wu, **Cong Zhao**, Yishun Li

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021</div><img src="{{ '/images/paper_02.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
中国公路学报

[基于多智能体深度强化学习的停车系统智能延时匹配方法](https://doi.org/10.19721/j.cnki.1001-7372.2022.07.022)

**赵 聪**, 张昕源, 李兴华, 杜豫川\*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021</div><img src="{{ '/images/paper_01.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transportation Research Part C: Emerging Technologies.

🏆`ESI全球TOP1.0%高被引论文` ⭐`研究前沿核心论文` [Macroscopic modeling and dynamic control of on-street cruising-for-parking of autonomous vehicles in a multi-region urban road network](https://doi.org/10.1016/j.trc.2021.103176)

**Cong Zhao**, Feixiong Liao\*, Jing Cao, Yuchuan Du\*

</div>
</div>
</details>

<span class='anchor' id='-patents'></span>

# 📚 专利
- A method of infrastructure-augmented cooperative perception for autonomous vehicles based on voxel feature aggregation(GB2628958)
- A method for multi-sensor multi-vehicle tracking based on image and motion feature matching(GB2628516)
- Radar and video data fusion method for vehicle tracking based on deep learning and feature similarity(GB2628517)
- A vehicle-road cooperative perception method for 3D object detection based on deep neural networks with feature sharing(GB2618936)
- On-board positioning device-based roadside millimeter-wave radar calibration method(GB2620877)
- Multi-target vehicle detection and re-identification method based on radar and video fusion(GB2619196)
- 🔥`New！`一种非完备感知数据下全域车辆轨迹构建方法 ZL202210763169.7
- 一种基于图匹配的车路协同系统多传感器时空标定方法 ZL202310021057.9
- 一种集群车辆运动轨迹预测方法 ZL202111474976.9
- 基于不确定性量化的路域全量全要素可信感知方法及系统 ZL202411902369.1
- 一种跨域车辆重识别及连续轨迹构建方法 ZL202210763102.3
- 一种基于双层模型的停车资源精细化管理优化方法 ZL202311201779.9
- 一种跨域路侧感知多车辆关联方法及系统 ZL202311239693.5
- 一种面向自主代客泊车场景的车辆运动轨迹预测方法 ZL202311335481.7
- 一种地下停车场盲区超视距感知及预警方法 ZL202311151480.7
- 一种面向路侧感知单元的车辆轨迹缺损数据修补方法 ZL202111427550.8
- 一种智能网联环境下路侧感知单元数据质量监测方法 ZL202111465443.4
- 一种道路交通感知轨迹数据的质量评估方法 ZL202110789522.4
- 一种路侧激光雷达点云坐标动态修正方法 ZL202110124242.1
- 一种车路协同环境下的自动驾驶横向控制方法 ZL202110131776.7
- 一种车路协同环境下的自动驾驶纵向决策控制方法 ZL202110131790.7

<span class='anchor' id='-honors-and-awards'></span>
# 🏆 荣誉奖项
🏅 荣誉


<span class='anchor' id='-people'></span>
# 🧑‍💻 团队成员
<style>
.people-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); /* 响应式布局 */
  gap: 20px;
  margin-bottom: 30px;
}
.person-card {
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  padding: 15px;
  background: #fff;
  transition: transform 0.2s;
}
.person-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
.person-name {
  font-weight: bold;
  font-size: 1.1em;
  color: #24292e;
  border-bottom: 1px solid #eee;
  padding-bottom: 8px;
  margin-bottom: 8px;
}
.person-desc {
  font-size: 0.9em;
  color: #586069;
  line-height: 1.5;
}
/* 招聘卡片样式 */
.hiring-card {
  border: 2px dashed #0366d6; /* 蓝色虚线框 */
  background: #f1f8ff;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  min-height: 100px;
  cursor: pointer;
}
.hiring-text {
  color: #0366d6;
  font-weight: bold;
}
</style>
<h3>Postdoc / Research Fellow</h3>
<div class="people-grid">
  <div class="person-card hiring-card">
    <div class="hiring-text">
      <i class="fas fa-user-plus"></i> Openings Available<br>
      <span style="font-size:0.8em; font-weight:normal;">We are looking for talented Postdocs.<br>Welcome to join us!</span>
    </div>
  </div>
</div>

<h3>PhD Students</h3>
<div class="people-grid">
  <div class="person-card hiring-card">
    <div class="hiring-text">
      <i class="fas fa-graduation-cap"></i> PhD Positions Open<br>
      <span style="font-size:0.8em; font-weight:normal;">Positions for PhD students are open.<br>Welcome to apply!</span>
    </div>
  </div>
</div>

<h3>Master Students</h3>
<div class="people-grid">
  
  <div class="person-card">
    <div class="person-name">
      <a href="https://henryyang-1.github.io/" target="_blank">Hanlin Yang (2024.9-)</a>
    </div>
    <div class="person-desc">
      Research interests: Intelligent transportation infrastructure and road maintenance decision-making.
    </div>
  </div>

  <div class="person-card">
    <div class="person-name">Jun Wan (2025.9-)</div>
    <div class="person-desc">
      Research interests: Traffic incident detection and road maintenance decision-making.
    </div>
  </div>

</div>
<h3>Undergraduate Students</h3>
<div class="people-grid">
  
  <div class="person-card">
    <div class="person-name">Enze Wang (2022.9-)</div>
    <div class="person-desc">
      Research interests: Automated road infrastructure inspection and maintenance augmented by LLM and embodied AI.
    </div>
  </div>

  <div class="person-card">
    <div class="person-name">Jingtai Luo (2022.9-)</div>
    <div class="person-desc">
      Research interests: AI-supported intelligent infrastructure and pavement defect detection algorithms.
    </div>
  </div>

</div>
<h3>Visiting Students</h3>
<div class="people-grid">
   <div class="person-card hiring-card" style="border-color: #aaa; background: #f9f9f9;">
    <div class="hiring-text" style="color: #666;">
       Open for Visiting Students
    </div>
  </div>
</div>


<div id="newsModal" class="news-modal-overlay">
  <div class="news-modal-content">
    <span class="news-close-btn">&times;</span>
    <div id="modalBody">
      </div>
  </div>
</div>

<script>
  // 获取元素
  var modal = document.getElementById("newsModal");
  var modalBody = document.getElementById("modalBody");
  var closeBtn = document.getElementsByClassName("news-close-btn")[0];
  var cards = document.querySelectorAll(".news-card");

  // 为每个卡片添加点击事件
  cards.forEach(function(card) {
    card.addEventListener("click", function() {
      // 1. 获取当前点击卡片的 HTML 内容
      var content = this.innerHTML;
      
      // 2. 将内容注入到模态框中
      modalBody.innerHTML = content;
      
      // 3. 显示模态框
      modal.style.display = "flex";
      
      // 4. 锁定背景滚动（可选）
      document.body.style.overflow = "hidden";
    });
  });

  // 关闭功能：点击关闭按钮
  closeBtn.onclick = function() {
    modal.style.display = "none";
    document.body.style.overflow = "auto"; // 恢复滚动
  }

  // 关闭功能：点击模态框外部空白区域
  window.onclick = function(event) {
    if (event.target == modal) {
      modal.style.display = "none";
      document.body.style.overflow = "auto"; // 恢复滚动
    }
  }
</script>


