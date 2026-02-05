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

刘成龙，同济大学交通学院研究员/副教授，交通科学与技术研究院副院长。入选国家自然科学基金B类（原国家优青项目）、上海35人青年科技引领计划、上海市启明星科技人才、中国公路学会青年托举人才等。主要从事道路工程与信息工程交叉方向研究，研究方向为交通基础设施数字化运维管理。担任联合国交通领域受聘顾问、世界交通运输大会（WTC）、美国交通运输委员会(TRB)、中国交通运输协会（CTA）等技术委员、节能与新能源汽车技术路线图主要执笔人、International Journal of Transportation Science and Technology（JCR-Q1）青年编委以及60余本SCI期刊的特邀审稿人。

研究成果在AIC、Transport Res. C、IEEE Trans. ITS、中国公路学报等高水平期刊会议发表研究论文100余篇，多项研究成果相继被遴选为IEEE ITSM封面论文、中国公路学报年度优秀论文、ESI高被引论文、ESI热点论文、中国知网高被引、高下载、高PCSI论文、交通部重大科技成果、COTA Best Presentation Award等。相关成果获授权中国、美国、英国、国际专利40余项，荣获中国专利优秀奖、上海市百强高价值专利，并实现了千万级成果转化与产业化应用，覆盖全国二十余省份应用里程超40万公里。获得上海市科技进步一等奖、中国公路学会科学技术特等奖/一等奖、中国交通运输协会科学进步一等奖、中国发明协会发明创新一等奖等奖励。

主讲人工智能科学与技术、交通数据分析、计算机视觉、交通科技竞赛等交叉学科课程，获同济大学青年教师竞赛一等奖。指导本科生、研究生获得全国交通科技大赛一等奖、SODIC全球开放数据应用创新大赛分赛道冠军、长三角数据开放创新应用大赛一等奖、全国互联网+大学生创新创业大赛银奖（上海市金奖）、等荣誉。指导的多位本科生、研究生毕业赴UC-Berkeley、Cambridge、清华大学、北京大学、同济大学等国内外一流高校深造。

研究方向：设施数字化感知、数字孪生、智慧城市、人工智能应用

主讲课程：
本科生：人工智能科学与技术（信息与智能网联类）、计算机视觉、智能交通基础、智能交通运输系统、运输经济学（中文/英文）、交通科技创新竞赛
研究生：交通数据分析与应用、交通可持续发展理论、环境友好型路面技术（联合国环境规划署）


# 📖 Educations
- *2010.09 - 2014.06*, [同济大学](https://www.tongji.edu.cn/), 交通工程, 学士.
- *2017.09 - 2018.09*, [华盛顿大学](https://www.washington.edu/), 土木环境工程, 联合培养博士.
- *2014.09 - 2019.06*, [同济大学](https://www.tongji.edu.cn/), 交通运输工程, 博士.

# 💻 Professional Experiences
- *2019.12 - 2022.12*, [同济大学](https://www.tongji.edu.cn/), 交通学院, 博士后.
- *2021.05 - 2024.03*, [同济大学](https://www.tongji.edu.cn/), 交通学院, 副研究员.
- *2023.02 - Present* , [同济大学](https://www.tongji.edu.cn/), 交通学院, 副教授.
- *2024.01 - Present* , [同济大学](https://www.tongji.edu.cn/), 交通科学与技术研究院, 副院长.
- *2024.03 - Present* , [同济大学](https://www.tongji.edu.cn/), 交通学院, 研究员.

# 🔍 Projects
- 🔥`New！`国家自然科学基金交叉科学部青年B类项目, 主持
- 🔥`New！`国家自然科学基金面上项目, 知识启发的生成式道路养护决策方法研究, 主持
- 国家重点研发计划(2023), 智能网联道路交通系统的能源自洽技术, 子课题主持
- 上海市科技创新行动计划(2023), 道路基础设施多维体征的数字化感知与评价方法研究, 主持
- 国家重点研发计划(2022), 弹性交通系统信息物理体系构建, 子课题主持
- 国家自然科学基金(2022), 众筹数据驱动的城市路网平整度感知方法研究, 主持
- 上海市科技创新行动计划(2021), 复杂地下道路韧性运行与智慧防灾关键技术研究与示范, 子课题主持
- 浙江省道桥检测与养护技术研究重点实验室基金(2021), 基于时空数据匹配的路面服役状态大数据评价技术, 主持
- 国家重点研发计划(2019), 港珠澳大桥智能化运维技术集成应用, 项目骨干


# 📰🔥 News

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
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="background-color: #d9534f; color: white; padding: 3px 8px; border-radius: 4px; font-size: 0.8em; vertical-align: middle; margin-right: 8px;">喜讯</span>
      <span style="vertical-align: middle;">刘成龙副教授获批国家自然科学基金交叉科学部青年B类项目</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>近日，国家自然科学基金委员会公布了2025年度项目评审结果，同济大学智能交通新兴计算与感知课题组（STEP）刘成龙副教授申报的国家自然科学基金青年科学基金B类项目（原国家优青项目）顺利获批。这是团队在交通基础设施数字化运维管理领域长期科研积累与创新贡献的充分肯定。</p>
      <p>刘成龙副教授长期致力于道路工程与信息工程交叉研究，在交通基础设施数字化感知、智能诊断与运维决策方面取得了系列创新成果，研究成果在AIC、Transport Res. C、IEEE Trans. ITS、中国公路学报等高水平期刊会议发表研究论文100余篇，多项研究成果相继被遴选为IEEE ITSM封面论文、中国公路学报年度优秀论文、ESI高被引论文、ESI热点论文、中国知网高被引、高下载、高PCSI论文、交通部重大科技成果、COTA Best Presentation Award等。相关成果获授权中国、美国、英国、国际专利40余项，荣获中国专利优秀奖、上海市百强高价值专利，并实现了千万级成果转化与产业化应用。获得上海市科技进步一等奖、中国公路学会科学技术一等奖、中国交通运输协会科学进步一等奖、中国发明协会发明创新一等奖等奖励。</p>
      <p>此次立项将进一步推动课题组在智能交通基础设施数字化与智慧运维方向的科研布局，助力我国交通基础设施高质量发展。课题组全体成员对刘成龙副教授表示热烈祝贺，并期待项目顺利实施，取得更多突破性成果。</p>
    </div>
  </div>

  <div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="vertical-align: middle;">团队与斯坦福大学合作成果发表于Nature子刊《Scientific Data》</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>团队联合斯坦福大学Martin Fischer教授团队共同完成的研究成果——《A Large-Scale Image Repository for Automated Pavement Distress Analysis and Degradation Trend Prediction》（大规模自动化路面病害分析与退化趋势预测图像库）及其配套数据集 PaveTrack，正式发表于Nature旗下期刊 Scientific Data。</p>
      <p>该论文的第一作者为同济大学交通运输工程学院2024级硕士研究生杨瀚霖，刘成龙副教授与杜豫川教授担任共同通讯作者。</p>
      <p>PaveTrack 数据集收录了来自中国与美国的近6万张路面病害图像，覆盖裂缝、坑槽、龟裂等10类病害，共计18万条精细标注信息。同时，团队首次公开了约9000张病害发育动态追踪图像，对165个道路位点进行了连续检测与跟踪，为深入揭示路面病害演化机理及退化趋势预测提供了坚实的数据支撑。</p>
      <p>目前，PaveTrack 数据集已在 Science Data Bank 正式开放，研究人员可通过以下<a href="https://doi.org/10.57760/sciencedb.20383">链接</a>获取。</p>
    </div>
  </div>

<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="vertical-align: middle;">团队成果《新一代智慧高速公路系统架构设计》入选2025领跑者5000（F5000）顶尖论文</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>近日，中国科学技术信息研究所发布了2025年度“领跑者5000-中国精品科技期刊顶尖学术论文”（简称F5000）入选名单。由团队杜豫川教授作为第一作者，刘成龙副教授作为通讯作者，在《中国公路学报》发表的《新一代智慧高速公路系统架构设计》一文入选2025领跑者5000（F5000）顶尖论文。</p>
      <p>该成果以前瞻性的系统思维重新定义了智慧高速的顶层架构，为国家高速公路的数字化转型和代际演进提供了具有前瞻性的理论框架和技术蓝图，此前，该成果已入选高被引、高影响、高PCSI论文，获得中国公路学报年度优秀论文。</p>
      <p>根据《中国科技论文与引文数据库》信息，采用定量分析（5年被引次数）和定性分析相结合的方法，对学术期刊的质量和影响力进行科学评价，遴选出精品科技期刊。每种精品期刊从5年间发表的论文中择优选取不超过20篇学术论文作为F5000的提名论文。提名论文再经过进一步遴选才能成为F5000论文。入选论文要求为各学科前1%高被引论文，且为原创性的科学研究或技术创新成果，能够反映期刊所在学科领域的最高学术水平。</p>
    </div>
  </div>

<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="vertical-align: middle;">团队成果“数字路长”智能管养平台入选“数据要素×交通AI+城市与交通典型案例”</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>近日，由同济大学智能交通新兴计算与感知课题组（STEP）自主研发的“数字路长”智能管养平台，成功入选由国家多部委联合评选的“数据要素×交通AI+城市与交通”典型案例。该评选面向全国，旨在发掘具有标杆意义的创新应用。此次全国共31个案例入选，“数字路长”平台的入选，标志着其创新价值与实践成效获得了国家层面的高度认可。</p>
      <p>“数字路长”平台由团队牵头，联合上海同陆云交通科技有限公司协力打造，构建了一套“感-联-算-控”一体化的交通基础设施数字治理新体系。平台深度融合物联网、大数据与人工智能技术，实现了对道路资产、路面病害、交通运行状态的全息感知与智能诊断，从根本上改变了传统依赖人工巡查、经验决策的粗放式管养模式。</p>
      <p>该项目直击传统路面管养中响应速度慢、监测盲区多等行业痛点，通过构建“数字路长”综合平台，成功打通了从海量数据采集、多维智能分析到科学决策支持的全链路闭环。该成果不仅仅是单点技术的落地应用，更以前瞻性的系统思维，为现代城市交通治理提供了一套可复制、可推广的数字化范本。此次入选标志着该平台在商业潜力与社会效益方面获得了双重肯定。团队将以此为契机，进一步深化数据要素在交通基础设施运维中的深度赋能，推动城市交通管养向数字化、智能化转型。</p>
    </div>
  </div>

<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="vertical-align: middle;">《交通科技竞赛》课程获评“国家一流本科课程（社会实践类）”</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>近日，教育部公布了国家级一流本科课程认定结果，由杜豫川、暨育雄、沈煜、刘成龙教授主讲的《交通科技竞赛》课程凭借其创新的教学模式与显著的育人成效，成功获批国家级一流本科课程（社会实践类）。这是团队在深化科教融合、探索创新型人才培养模式方面取得的又一重要突破。</p>
      <p>课程立足交通学科多学科交叉特质，设计了思维模式、技能拓展、创新活动三大教学模块，实现创新能力的“矩阵乘积式”培养，创新设置“揭榜挂帅”与“赛事贯通”的实践教学形式，组建校企导师联合培养机制，解决创新创业实践应用的“最后一公里”难题。</p>
      <p>课程的成功获评，是对其创新理念与卓越成效的高度认可。作为教育部“双万计划”的核心组成部分，这一称号代表了国家层面对本科课程质量的最高标准认定。评审过程极为严格，遵循“质量为本、优中选优”的原则，在数万门申报课程中，全国仅有不到6000门课程最终入选。《交通科技竞赛》正是凭借其彻底打破课堂与实践壁垒的“研赛结合”教学模式，精准契合了国家对拔尖创新人才培养的战略导向，从而在激烈的竞争中脱颖而出。</p>
      <p>此次获批国家一流课程，是对团队长期坚持立德树人、潜心教学改革的充分肯定。课题组将继续坚持以学生为中心，持续提升课程建设质量，为我国交通强国建设培养更多卓越工程人才。</p>
    </div>
  </div>

<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="vertical-align: middle;">团队发布垂直大模型“同济小图”，在河北实现行业应用突破</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>同济大学智能交通新兴计算与感知课题组（STEP）在交通垂直大模型领域取得重要工程化进展，自主研发的交通行业垂直大模型“同济小图”近期在河北省交通运输规划与管理部门成功部署应用，标志着通用人工智能（AI）技术在交通这一垂直行业的深度“驯化”与落地迈出了关键一步。</p>
      <p>“同济小图”针对交通行业政策法规繁杂、技术标准众多、知识更新迅速、决策分析多维等核心痛点，通过对海量行业文本、标准规范、技术报告和地理信息数据进行专业化训练与精调，使其具备了精准的语义理解、智能问答、报告生成与辅助决策能力。在河北的实际应用中，它有效解决了基层技术人员知识检索效率低、跨领域决策支持弱等长期难题，成为提升行业智能化水平的“专家级助手”。</p>
      <p>该项目的成功落地，不仅证明了团队将前沿AI算法与深厚行业知识深度融合的工程化能力，更为交通行业的数字化转型探索出一条切实可行的路径。它意味着大模型技术不再局限于通用场景，而是能够深度融合行业知识，为解决特定领域的复杂问题提供精准、可靠的“大脑”支持，具有重大的行业示范价值和广阔的推广前景。</p>
    </div>
  </div>

<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="vertical-align: middle;">团队自研“轻量化路面巡查系统”获新加坡陆路交通管理局（LTA）权威认证</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>同济大学智能交通新兴计算与感知课题组（STEP）在高端智能检测装备“出海”方面取得里程碑式突破。由团队自主研发的“轻量化路面巡查系统”，正式通过新加坡陆路交通管理局（Land Transport Authority, LTA）的严苛技术认证，获准在新加坡市场推广与应用。</p>
      <p>新加坡LTA以其国际公认的最高标准与最严苛的认证体系著称。此次认证的通过，是对该系统在检测精度、设备稳定性、数据可靠性及标准化程度等方面达到国际一流水准的权威背书。该系统创新性地集成了高精度视觉传感器与边缘计算AI单元，可在车辆正常行驶中无感化、高频次地完成路面病害自动化检测，具有成本低、效率高、易部署的显著优势。</p>
      <p>这不仅仅是一张市场准入证书，更是中国原创高端交通检测装备技术成功打入发达国家高端市场的关键一步，打破了该领域长期由国际巨头主导的技术与市场壁垒。它有力证明了团队的“轻量化”技术理念与工程方案具备极强的国际竞争力和全球普适性，为课题组后续开拓“一带一路”沿线乃至欧美高端市场奠定了坚实的基础，是中国智造“走出去”的生动实践。</p>
    </div>
  </div>

<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="vertical-align: middle;">团队承担联合国亚太经社会（UNESCAP）重大项目，贡献区域互联互通“中国方案”</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>同济大学智能交通新兴计算与感知课题组（STEP）积极参与全球交通治理，服务联合国可持续发展目标。刘成龙教授应联合国亚洲及太平洋经济社会委员会（UNESCAP）邀请，主持地域能力提升项目“Accelerating Collective Action in the Third Decade of the Programme of Action for Landlocked Developing Countries (2024–2034) through Strengthening Operational Connectivity along the Asian Highway Network and its Connections” 。</p>
      <p>该项目聚焦于解决内陆发展中国家的核心发展瓶颈，针对跨境物流效率低下与交通连通性不足等问题，提出可持续的智能立体交通系统建设方案。凭借在跨境交通走廊数字化、智慧物流和交通韧性提升领域的深厚积累，为覆盖超过14万公里的亚洲公路网提供了关键的数字化与智能化提升方案，助力制定提升亚洲公路网运输效率与可靠性的技术指南。</p>
      <p>联合国亚太经社会（UNESCAP）作为联合国系统中在亚太地区最重要、最具影响力的政府间综合性经济社会发展组织，其设立的项目旨在凝聚成员国共识，推动解决区域最紧迫的发展难题，代表该领域最高层次的国际合作与实践标准。通过将中国在交通基础设施数字化、智能化运维领域的先进经验与实践成果系统性地推向国际，团队为促进区域经济一体化、落实联合国2030年可持续发展议程贡献了不可或缺的“中国智慧”与“智库力量”。</p>
    </div>
  </div>

<div class="news-card">
    <div style="font-size: 1.2em; font-weight: bold; color: #333; margin-bottom: 10px;">
      <span style="vertical-align: middle;">团队获批高峰学科重点交叉项目，前瞻布局“低空经济”基础设施新赛道</span>
    </div>
    <div style="color: #555; font-size: 0.95em; line-height: 1.6;">
      <p>近日，依托同济大学高峰学科建设支持，刘成龙教授牵头的《无线电能驱动的电气化、模块化低空基础设施》项目正式获批立项。该项目敏锐捕捉“低空经济”这一国家战略新兴赛道的关键痛点，是交通工程与电气工程深度交叉融合的创新尝试。</p>
      <p>项目创造性地提出利用无线电能传输技术解决低空飞行器的能源补给难题，并正在探索一种全新的、模块化的基础设施形态。这一研究以前瞻性的视角，为未来三维立体交通网络的构建提供了重要的物理基础和理论支撑。</p>
      <p>该项目的启动实施，具有前瞻性的战略意义。它不仅是多学科深度交叉融合的典范，更是团队从传统地面交通向未来三维立体智慧交通网络进行前沿探索的关键布局。通过为解决低空飞行器的航程焦虑与充电难题提供原创性的“同济方案”，项目旨在为构建安全、高效、绿色的城市空中交通系统提供至关重要的物理基础与理论技术储备，助力我国在全球低空科技革命中占据先机。</p>
    </div>
  </div>
  
</div>

# 📝 Publications 
📃 Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src='/images/18.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE Transactions on Intelligent Transportation Systems

🔥`New！`[Engineering-Adaptive Pavement Maintenance Decision-Making Model: A Reinforcement Learning Approach From Expert Feedback](https://ieeexplore.ieee.org/abstract/document/10934967)

Wenyuan Cai, Yuchuan Du, Difei Wu, Zihang Weng, **Chenglong Liu\***

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src='/images/19.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Sensors

🔥`New！`[A Comprehensive Framework for Evaluating Cycling Infrastructure: Fusing Subjective Perceptions with Objective Data](https://doi.org/10.3390/s25041168)

Kefei Tian, Yifan Zheng, Zhongyu Sun, Zishun Yin, Kai Zhu, **Chenglong Liu\***

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src='/images/20.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Case Studies in Construction Materials

🔥`New！`[Comprehensive review on greenhouse gas emission assessment over the full life-cycle of pavement](https://doi.org/10.1016/j.cscm.2025.e04407)

Yuchuan Du, Ziyue Gao, **Chenglong Liu\***, Zihang Weng\*, Xiangyu Ren, Wenxiang Li

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src='/images/21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Measurement

🔥`New！`[Enhanced GPR signal interpretation via deep learning fusion for unveiling road subsurface conditions](https://doi.org/10.1016/j.measurement.2025.117007)

Shan Zhong, Difei Wu, Yuchuan Du, Yu Yan, **Chenglong Liu**, Zihang Weng, Guoqing Wang, Fei Xu

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2025</div><img src='/images/22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Computer‐Aided Civil and Infrastructure Engineering

🔥`New！`[A cooperative methodology for multi‐roller automation in pavement construction considering trajectory planning and collaborative operation](https://doi.org/10.1111/mice.13347)

Difei Wu, Sheng Zhong, Man Io Leong, Yishun Li, Boyuan Tian, **Chenglong Liu**, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src='/images/1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
International Journal of Pavement Engineering

🔥`New！`[Fast calibration for vibration-based pavement roughness measurement based on model updating of vehicle dynamics](https://www.tandfonline.com/doi/abs/10.1080/10298436.2023.2287688)

Difei Wu, **Chenglong Liu**,Bohao Qin, Sheng Zhong, Xiaoming Zhang, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src='/images/2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Automation in Construction

🔥`New！`[Advances in automatic identification of road subsurface distress using ground penetrating radar: State of the art and future trends](https://www.sciencedirect.com/science/article/pii/S0926580523004454)

**Chenglong Liu**, Yuchuan Du, Guanghua Yue, Yishun Li, Difei Wu, Feng Li

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='/images/3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE transactions on intelligent transportation systems

🔥`New！`[Fine-Grained Pavement Performance Prediction Based on Causal-Temporal Graph Convolution Networks](https://ieeexplore.ieee.org/abstract/document/10311071)

Wenyuan Cai, Andi Song, Yuchuan Du, **Chenglong Liu\***, Difei Wu, Feng Li

</div>
</div>

<details>
  <summary style="cursor: pointer; color: #007bff; font-weight: bold; margin: 20px 0;">👉 Click to view Past Publications (点击查看往期论文)</summary>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/4.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Computer‐Aided Civil and Infrastructure Engineering

[Spatiotemporal matching method for tracking pavement distress using high-frequency detection data](https://onlinelibrary.wiley.com/doi/abs/10.1111/mice.12947)

Ning Pan, Hao Liu, Difei Wu, **Chenglong Liu**, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Computer‐Aided Civil and Infrastructure Engineering

[Effective pavement skid resistance measurement using multi-scale textures and deep fusion network](https://onlinelibrary.wiley.com/doi/abs/10.1111/mice.12931)

**Chenglong Liu**, Nan Xu, Zihang Weng, Yishun Li, Yuchuan Du, Jing Cao

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='/images/6.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
International Journal of Transportation Science and Technology(IJTST)

[Enabling edge computing ability in view-independent vehicle model recognition](https://www.sciencedirect.com/science/article/pii/S204604302300028X)

**Chenglong Liu**, Ziyuan Pu, Yishun Li, Ying Jiang, Yinhai Wang, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='/images/7.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
中国公路学报

`封面热点论文`[探地雷达多特征融合的城市空洞自动识别方法研究](https://kns.cnki.net/kcms2/article/abstract?v=N5T8oFSaxGEJhL0CJQuYYdj0jekwNRpkOf29RxPE4BCzD9g-XHdsGhYbW-c6DBruvU4dl-YCoKnJU7AT2WPe1rBVj4vEwIh1DHjQBNQLSyq1ncGSIwsqahPqO6Rw6DvHkUI6K7QdBIqOTug69e80CQ==&uniplatform=NZKPT&language=CHS)

杜豫川, 岳光华, **刘成龙\***, 李峰, 蔡文才

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/8.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Automation in Construction

[Deep learning-based pavement subsurface distress detection via ground penetrating radar data](https://www.sciencedirect.com/science/article/pii/S0926580522003892)

Yishun Li, **Chenglong Liu\***, Guanghua Yue, Qian Gao, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/9.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE transactions on intelligent transportation systems

[ConTrack Distress Dataset: A Continuous Observation for Pavement Deterioration Spatio-Temporal Analysis](https://ieeexplore.ieee.org/abstract/document/9899382)

Yishun Li, **Chenglong Liu\***, Qian Gao, Difei Wu, Feng Li, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/10.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
IEEE transactions on intelligent transportation systems

[A Response-Type Road Anomaly Detection and Evaluation Method for Steady Driving of Automated Vehicles](https://ieeexplore.ieee.org/abstract/document/9805658)

**Chenglong Liu**, Tong Nie, Yuchuan Du, Jing Cao, Difei Wu, Feng Li

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/11.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Automation in Construction

[Pavement texture depth estimation using image-based multiscale features](https://www.sciencedirect.com/science/article/pii/S0926580522002771)

Zihang Weng, Hui Xiang, Yuchao Lin, **Chenglong Liu**, Difei Wu, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/12.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
中国公路学报

`封面热点论文`[高速路网不停车收费车道优化布设方法](https://kns.cnki.net/kcms2/article/abstract?v=N5T8oFSaxGE5KG9OjMOws3MUL1wgDrlkfSj89QJrhfeWkrI2EhlezFAV_l19Bb0k_UV3okDPJjxg-14f6Anke1h9s5ZHoqwCwOJ2yJ-ORt72EXFVJYd2sDNG5eSZWZGdQOs_aPtVVCseO6NWVDoqeQ==&uniplatform=NZKPT&language=CHS)

**刘成龙**, 陶莎, 赵聪, 暨育雄, 杜豫川

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2020</div><img src='/images/13.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
International Journal of Pavement Engineering

[Mathematical insights into the relationship between pavement roughness and vehicle vibration](https://www.tandfonline.com/doi/abs/10.1080/10298436.2020.1830092)

**Chenglong Liu**, Difei Wu, Yishun Li, Shengchuan Jiang, Yuchuan Du

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/14.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
中国公路学报

`2023年度优秀论文、封面热点论文、高被引、高下载、高影响力论文`[新一代智慧高速公路系统架构设计](https://kns.cnki.net/kcms2/article/abstract?v=N5T8oFSaxGGw0wHSNKMvp4f2OMptvhq4A-cUocNQMXwE6VPu6ym5UDzZd4tu70FeQSz2xd43pjx2YQREQL0Nh03GipYcCuM3qDjGgRjcLT6OoTePi95LBVT4vxw7kXXlKSYi8sLU0AitgIHkw0EK9w==&uniplatform=NZKPT&language=CHS)

杜豫川, **刘成龙\***, 吴荻非, 赵聪

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021</div><img src='/images/15.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Automation in Construction

[Rapid pavement aggregate gradation estimation based on 3D data using a multi-feature fusion network](https://www.sciencedirect.com/science/article/pii/S092658052100501X)

Zihang Weng, Gulnigar Ablat, Difei Wu, **Chenglong Liu\***, Feng Li, Yuchuan Du, Jing Cao

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='/images/16.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transportation Research Part C

`ESI(1%)`[Comfortable and energy-efficient speed control of autonomous vehicles on rough pavements using deep reinforcement learning](https://www.sciencedirect.com/science/article/pii/S0968090X21004757)

Yuchuan Du, Jing Chen, Cong Zhao, **Chenglong Liu**, Feixiong Liao, Ching-Yao Chan

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021</div><img src='/images/17.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Transportation Research Part C: Emerging Technologies

`ESI (1%), ESI(0.1%), COTA Best Presetation Award, 交通部重大科技成果(论文类)`[Large-scale pavement roughness measurements with vehicle crowdsourced data using semi-supervised learning](https://www.sciencedirect.com/science/article/pii/S0968090X21000784)

**Chenglong Liu**, Difei Wu, Yishun Li, Yuchuan Du

</div>
</div>
</details>

# 📚 Patents
- 🔥`New！`A method for leakage detection of underground corridor based on static infrared thermal image processing(GB2569751)
- 🔥`New！`Comfort-based self-driving planning method(US 11,447,150 B2)
- Method of controlling automated driving speed based on comfort level(WO/2018/122586)
- 🔥`New！`基于多车众筹振动数据的路网级平整度检测方法	ZL202210144895.0
- 🔥`New！`一种考虑碳排放的路网级全生命养护优化方法	ZL202210139768.1
- 一种基于关联规则分析的道路深层病害预警方法	ZL202110215728.6
- 一种振动式路面平整度测试车的标定方法	ZL202110661532.X
- 一种基于摩擦接触面预估的路面抗滑性能评价方法	ZL202110121825.X
- 一种路面损伤快速检测和自然数据集构建方法	ZL202110073970.4
- 一种基于多源特征融合的路面损伤数据时空分析方法	ZL202110074435.0


# 🏆 Honors and Awards
🏅 Honors
- 🔥`New！`	同济大学教学成果奖**二等奖**（2025）明体达用、智慧赋能：《交通数据分析与应用》课程建设与创新教学实践
- 🔥`New！`同济大学青年教师教学竞赛**一等奖**（2025）《计算机视觉》
- 🔥`New！`北京市科技进步奖**二等奖**（2025）《城市道路智能巡检与精细管养关键技术及工程应用》
- 🔥`New！`中国智能交通协会科技进步奖**二等奖**（2025）《高频数据驱动的生成式道路养护决策关键技术及应用》
- 🔥`New！`中国公路学会科技进步**一等奖**（2025）《在役公路网的“巡检-决策-养护”智能装备和系统研发及应用》
- 广东省科技进步**二等奖**（2024）《城市道路多维运行风险泛在感知与管养决策关键技术及应用》
- 江西省科技进步**二等奖**（2024）《高速公路数智养护技术研究与应用》
- 中国公路学会科学技术奖**特等奖**(2023) 《距离高速公路智能建造与运维关键技术研究及应用》
- 《中国公路学报》年度**优秀论文**(2023) 《新一代智慧高速公路系统架构设计》
- 中国交通协会科技进步**一等奖**(2023) 《高速公路数智养护与决策平台建设关键技术研究及开发》
- 上海市**百强高价值专利**(2022) 《轻量化路面巡查系统》专利群，核心专利已完成300万转化
- 中国**专利优秀奖**(2021)，《一种基于重力加速度传感器的路面平整度检测方法》
- 江西公路科技进步**一等奖**(2021)《高速公路智慧管养技术研究与应用》
- 中国发明协会发明创新**一等奖**(2020) 《路面表观损伤智能快速巡检系统研发及应用》
- 上海市科技进步**一等奖**(2019) 《路面多维高频检测装备和智能养护技术及应用》
- 中国公路学会科学技术奖**一等奖**(2017)《轻量化沥青路面行驶质量快速检测系统》

# 🧑‍💻 People
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

