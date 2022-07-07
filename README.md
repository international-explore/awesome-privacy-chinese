# 国内隐私技术交流
旨在收集和分享隐私技术相关的一些信息，涵盖且不限于业内白皮书，隐私计算技术，隐私相关创业企业，相关法规，英文词汇，相关新闻等。

# 内容目录
   * [隐私法规](#隐私法规) - 全球主要隐私法规收集
   * [隐私组织](#隐私组织) - 全球主要隐私管理和认证机构
   * [相关白皮书](#相关白皮书) - 隐私和隐私计算相关白皮书
   * [隐私创业企业](#隐私创业企业) - 基于隐私创业的相关企业
   * [大厂隐私中心](#大厂隐私中心) - 各大厂的隐私中心，设计理念和宗旨
   * [隐私新技术](#隐私新技术) - 隐私相关的新技术，隐私计算、隐私检测等
   * [相关工具](#相关工具) - 隐私相关的一些工具
   * [书籍视频](#书籍) - 隐私相关数据推荐
   * [网站外链](#网站外链) - 隐私相关重要新闻、资源外链
   * [📙 英语词汇](./PrivacyGlossary.md) - 隐私相关的基础英语词汇
   * [🗞️ 相关新闻](./news.md) - 隐私相关时事新闻收集
    * [2022 年 4 月隐私新闻](./news/202204.md)
    * [2022 年 5 月隐私新闻](./news/202205.md)
    * [2022 年 6 月隐私新闻](./news/202206.md)
    * [2022 年 7 月隐私新闻](./news/202207.md)

## 隐私法规
 * 全球法规查询：
   * [data protection laws around the world](https://www.dlapiperdataprotection.com/) 全球隐私保护法规查询
   * [Map of the level of data protection](https://www.cnil.fr/en/data-protection-around-the-world) 全球隐私保护严重程度查询
 * 重要海外法规
   * GDPR - 欧盟隐私法规，也是全球隐私的标杆法规，颁布于2016年 | [官网](https://gdpr-info.eu/) | [GDPR中文PDF](./files/laws/欧盟《通用数据保护条例》GDPR-高质量译文(全)%20.pdf)  | [awesome GDPR](https://github.com/bakke92/awesome-gdpr#readme)
   * CCPA - 加州消费者隐私保护法规，是美国隐私保护的代表法规，颁布于2018年 | [官网](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=201720180AB375)   
   * LGPD - 巴西隐私保护法，整体效仿GDPR，生效与2020年 | [官网](https://www.gov.br/cidadania/pt-br/acesso-a-informacao/lgpd) | [LGPD中文PDF](./files/laws/巴西通用数据保护法_译文.pdf) | [政府工具包](https://www.gov.br/governodigital/pt-br/governanca-de-dados/guias-operacionais-para-adequacao-a-lgpd)
   * PPC  - 日本的隐私保护法，2020年更新 | [官网](https://www.ppc.go.jp/en/legal/)  
   * PDPA - 新加坡的个人隐私保护法 | [官网](https://www.pdpc.gov.sg/Overview-of-PDPA/The-Legislation/Personal-Data-Protection-Act)   
   * PoPIA- 南非的隐私保护法，颁布于2013年 | [官网](https://www.justice.gov.za/inforeg/legal/InfoRegSA-act-2013-004.pdf) 
   * HIPAA- 美国针对医疗和保险行业的隐私保障法规，于1996颁布 | [官网](https://www.hhs.gov/hipaa/index.html) | [developers guide](https://github.com/truevault/hipaa-compliance-developers-guide)
   * ADPPA- 美国数据隐私和保护法案，20220606发布草案 | [相关网站](https://thehill.com/policy/technology/3522026-why-a-bipartisan-data-privacy-proposal-faces-an-uphill-battle/)
   * PDPA - 泰国个人数据保护法，20220607生效 | [官网-pdf](https://thainetizen.org/wp-content/uploads/2019/11/thailand-personal-data-protection-act-2019-en.pdf)
  
 * 国内三大法规
   * [《个人保护法》- 2021/11/01](http://www.npc.gov.cn/npc/c30834/202108/a8c4e3672c74491a80b53a172bb753fe.shtml) | [个保法十大亮点](https://mp.weixin.qq.com/s/EOEYNAeG5Cxq3e3G4Mk87g) | [个保法专家解读](https://mp.weixin.qq.com/s/8-CTTz2Iv4bOlCbPbvNl5w)
   * [《网络安全法》- 2017/06/01](http://www.cac.gov.cn/2016-11/07/c_1119867116.htm) | [网络安全法解读](http://www.mca.gov.cn/article/zt_gjaqr2021/zjjd/202104/20210400033201.shtml) | [网信办解读网络安全法](http://www.cac.gov.cn/2020-05/03/c_1590051734208776.htm)
   * [《数据安全法》- 2021/09/01](http://www.npc.gov.cn/npc/c30834/202106/7c9af12f51334a73b56d7938f99a788a.shtml) | [数据安全法解读](http://www.cac.gov.cn/2021-06/15/c_1625341228851523.htm)
  
 * 隐私相关条例
   * [《个人信息出境标准合同规定》- 2022/06/30](http://www.moj.gov.cn/pub/sfbgw/lfyjzj/lflfyjzj/202206/t20220630_458805.html) 中国个人信息出境的SCC，需要注意第四条排除项，大厂基本都不满足
   * [《数据网络安全管理条例》- 2021/11/14](http://www.cac.gov.cn/2021-11/14/c_1638501991577898.htm) |  [网络数据安全管理条例学习](https://mp.weixin.qq.com/s?__biz=MzIwNTA4NjAxMw==&mid=2648971266&idx=1&sn=12be3b5cab15294ff4530022831dec35&chksm=8f26f450b8517d462e0bce18fbf1e5898e475f8ce50d5ec621758e6893dc3948e20ee72d0742&token=557650794&lang=zh_CN#rd)
   * [《数据网络安全管理条例》- 2021/11/14](http://www.cac.gov.cn/2021-11/14/c_1638501991577898.htm) |  [网络数据安全管理条例学习](https://mp.weixin.qq.com/s?__biz=MzIwNTA4NjAxMw==&mid=2648971266&idx=1&sn=12be3b5cab15294ff4530022831dec35&chksm=8f26f450b8517d462e0bce18fbf1e5898e475f8ce50d5ec621758e6893dc3948e20ee72d0742&token=557650794&lang=zh_CN#rd)
   * [《互联网信息服务算法推荐管理规定》 - 2022/03/01](http://www.cac.gov.cn/2022-01/04/c_1642894606364259.htm) | [官方解读](https://mp.weixin.qq.com/s/z6lPpeZ5RJXAeMjo7l2NGA)
   * [《关键信息基础设施安全管理条例》- 2021/09/01](http://www.gov.cn/zhengce/content/2021-08/17/content_5631671.htm) | [官方答记者问](https://mp.weixin.qq.com/s/7epChMnwiZU3mUV_dGawqA)
   * [《网络安全审查办法》- 2022/02/15](http://www.cac.gov.cn/2022-01/04/c_1642894602182845.htm) | [官方答记者问](https://mp.weixin.qq.com/s/Avfc4EbEAEKkuo0CTDH7sQ)
   * [《汽车数据安全管理若干规定》 - 2021/10/01](http://www.cac.gov.cn/2021-08/20/c_1631049984897667.htm) | [官方答记者问](https://mp.weixin.qq.com/s/rxL7pUJV3P7sGAFqdjTZoA)
   * [《数据出境安全评估办法》-2021/10/29](http://www.moj.gov.cn/pub/sfbgw/lfyjzj/lflfyjzj/202110/t20211029_440268.html)
  
 * 重要业内标准
   * [IEEE SA P3117 首个隐私计算互联互通标准 - 2022-06](https://sagroups.ieee.org/3117/) 主要由信通院等牵头，旨在打破计算孤岛，实现互联互通
   * [个人信息跨境处理活动安全认证规范 - 2022-06](https://www.tc260.org.cn/front/postDetail.html?id=20220624175016) 标准委员会出的，主要针对个人信息跨境处理的原则
 * 重要认证指南
   * [PCI-DSS](https://www.pcisecuritystandards.org/pdfs/chinese_simplified_pci_dss_audit_procedures_v1-1.pdf) 支付卡服务的全球认证
   * [ISO 27001:2013](https://www.iso.org/standard/54534.html) 侧重信息安全，针对信息安全的管理体系、要求和风险处置等
   * [ISO 27701:2019](https://www.iso.org/standard/71670.html) 侧重隐私安全，在可识别信息控制者和个人可识别信息处理者进行规范和指导，一般和27001一起过
   * SOC审计：系统和组织控制(System and Organization Controls，SOC)报告是由AICPA发布的标准管理的报告，与提供服务的服务组织相关
     * [SOC 1](https://us.aicpa.org/interestareas/frc/assuranceadvisoryservices/aicpasoc1report) 概述于认证协议标准声明(SSAE) 18，SOC 1关注的是服务组织的内部控制
     * [SOC 2](https://us.aicpa.org/interestareas/frc/assuranceadvisoryservices/aicpasoc2report) SOC 2是一个受限使用报告，关注的是与AICPA的信任服务标准(TSCs)概述的`合规和运营`相关
     * [SOC 3](https://us.aicpa.org/interestareas/frc/assuranceadvisoryservices/aicpasoc3report) SOC 3是一个通用使用报告，细节不多，可以由服务组织自由分发，是个较好的营销工具。
  

## 隐私组织
 * 监管机构查询：[List of DPAs](https://pdpecho.com/the-list/) 
 * 欧洲重要机构 
   * [EDPB- European Data Protection Board](https://edpb.europa.eu/edpb_en)
   * [EDPS- European Data Protection Supervisor](https://edps.europa.eu/_en)
   * [ENISA - European Union Agency for Network and Information Security ](https://www.enisa.europa.eu/topics/data-protection)
   
 * 其他重要机构
   * [IAPP - International Association of Privacy Professionals ](https://iapp.org/) -国际隐私专业人员协会
   * [W3C Privacy Interest Group ](https://www.w3.org/Privacy/) - 主要针对web 隐私
   * [CUPS - CyLab Usable Privacy and Security Laboratory ](https://cups.cs.cmu.edu/) - 隐私和安全一些可用性的前沿研究
   * [EPIC - Electronic Privacy Information Center](https://epic.org/) - 美国提倡隐私保护组织
   * [FPF - Future of Privacy Forum](https://fpf.org/) - 未来隐私技术交流研究
   
## 相关白皮书
  * 国内白皮书（评分纯属个人意见，5分推荐，4分值得一读，3分有时间就看看，2分不值得，1分垃圾）
    * [2022-财经&社科院-《个性化广告合规发展研究报告》](./files/whitepaper/2022-财经-个性化广告合规发展研究报告.pdf)
      * **3分** | 产品三个关键点：告知和用户同意,opt-out,避免直接定位人；使用还是隐私计算
    * [2022-德勤-《2022技术趋势（中文版）》](./files/whitepaper/2022技术趋势（中文版）-德勤-2022.pdf)
      * **3分** | 第一章重点介绍了了数据跨界和共享，三个关键词：机遇、易用性和隐私，落脚点还是隐私计算
    * [2022-ECC-《边缘学习：隐私计算白皮书》](./files/whitepaper/2022-ECC-边缘学习：隐私计算白皮书.pdf) 
      * **4分** | 对边缘计算、隐私计算的基础概念介绍比较清晰，可以做为比较好的入门
    * [2022-腾讯-《数据安全产业大数据白皮书》](./files/whitepaper/2022-腾讯-数字安全产业大数据白皮书.pdf) 
      * **3分** | 涉猎阅读型，简介了全球安全产业的发展和现状，以及主要上市公司
    * [2022-工业协会-《广东省新型数据中心发展白皮书》](./files/whitepaper/2022-工业协会-广东省新型数据中心发展白皮书.pdf) 
      * **3分** | 数据中心核心点集约、高效、绿色、安全，重点第六章介绍趋势中提到安全可信和隐私性。
    * [2021-腾讯-《腾讯隐私计算白皮书2021》](./files/whitepaper/2021-腾讯隐私计算白皮书2021.pdf)
      * **4分** | 介绍隐私计算的概念、现状以及主要算法，可以作为不错的入门学习
    * [2021-德勤-《移动应用个人信息保护白皮书》](./files/whitepaper/2021-10德勤移动应用个人信息保护白皮书.pdf) 
      * **3分** | 结合oppo现状介绍移动端信息保护的整体框架，可以作为体系化设计的参考
    * [2021-信通院-《隐私保护计算技术研究报告》](./files/whitepaper/2020-信通院-隐私保护计算技术研究报告.pdf) 
    * [2021-安永-《全球数据合规与隐私科技发展报告》](./files/whitepaper/2021-安永-全球数据合规与隐私科技发展报告.pdf)
    * [2021-阿里云-《数据安全隐私保护》白皮书](./files/whitepaper/2021-阿里云-数据安全隐私保护白皮书.pdf)
    * [2021-工行-《隐私计算推动金融业数据生态建设》白皮书](./files/whitepaper/2021-11《隐私计算推动金融业数据生态建设》白皮书.pdf)
    * [2021-微众&毕马威-《隐私计算行业研究报告》白皮书](./files/whitepaper/2021-微众&毕马威-隐私计算行业研究报告.pdf)
    * [2021-CB INSIGHT-《中国隐私计算技术与市场发展研究报告》](./files/whitepaper/2021-12中国隐私计算技术与市场发展研究报告.pdf)
    * [2021-移动-《隐私计算白皮书》](./files/whitepaper/2021-移动-隐私计算白皮书.pdf)
    * [2021-隐私计算联盟-《隐私计算法律与合规研究白皮书》](./files/whitepaper/2021-隐私计算联盟-隐私计算法律与合规研究白皮书.pdf)
    * [2021-甲子光年-《隐私计算行业研究报告》](./files/whitepaper/2021-甲子光年-隐私计算行业研究报告.pdf)
    * [2021-交通银行-《隐私计算金融应用蓝皮书》](./files/whitepaper/2021-交通银行-隐私计算金融应用蓝皮书.pdf)
    * [2021-信通院-《中国算力发展指数白皮书》](./files/whitepaper/2021-信通院-中国算力发展指数白皮书.pdf)
    * [2021-信通院-《数据安全风险分析及应对策略研究》](./files/whitepaper/2021-信通院-数据安全风险分析及应对策略研究.pdf)

  * 海外白皮书
    * [2021-Uber-《ESG report》](./files/whitepaper/2021-Uber-ESG-Report.pdf) 
      * **4分** | uber esg的进展和报告，涉及整体隐私的设计和理念
    * [2021-aws-《risk and compliance white_paper》](./files/whitepaper/2021_AWS_Risk_and_Compliance_Whitepaper.pdf) 
      * **3分** | aws合规的一些简介，偏产品和功能介绍，干货较少，下同
    * [2020-aws-《aws security white_paper》](./files/whitepaper/2020-AWS_Security_Whitepaper.pdf) 
    * [2019-apple-《safari privacy white paper》](./files/whitepaper/2019-apple-Safari_White_Paper_Nov_2019.pdf) 
      * **3分** | 苹果safari隐私白皮书，重点介绍了浏览器的一些隐私功能 
 

## 隐私创业企业
 * 海外创业公司
   * [incountry - 数据本地化](https://incountry.com/) | 理念：GLOBAL APPS, LOCAL COMPLIANCE 
   * [adzapier - CMP同意管理](https://adzapier.com/) |理念：have access to meaningful data, while still respecting each individual consumer's right to privacy 
   * [cloaked - 号码和邮箱保护](https://www.cloaked.app/) |理念：Never feel forced to share your personal phone number or email. 
   * [getvisibility - 数据标注分级和保护](https://www.getvisibility.com/) | 理念：发现、分级、保护
   * [duckduckgo.com - 隐私搜索引擎](https://duckduckgo.com/) | 理念：我们从不存储你的个人信息 
   * [consentmanager - CMP](https://www.consentmanager.net/) | 重心： Higher Acceptance-Rates & Lower Bounce-Rate
     
 * 国内创业公司
   * [数牍科技 - 隐私计算](https://www.sudoprivacy.com/) | 理念：安全高性能的隐私计算平台 
   * [洞见科技 - 隐私计算](https://www.insightone.cn/) | 理念：让数据价值安全释放 - 网信国家队"中电科"投资。
   * [星云clustar - 数据高效融合](https://www.sudoprivacy.com/) | 理念：数融有道 数智无界 
   * [富数科技 - 安全计算](https://www.fudata.cn/) | 理念：构建数据安全桥梁、保护隐私，释放价值 
   * [翼方健数 - 安全计算](https://www.basebit.ai/) | 理念：隐私安全计算加速数据要素流动，激活数据共享价值 
   * [华控清交 - 安全计算](https://www.tsingj.com/) | 理念：让数据安全融合，使信任变得简单 
   * [原语科技 - 隐私计算](https://www.primihub.com/) | 目前平台已经在github开源：[primihub](https://github.com/primihub/primihub)
   


## 大厂隐私中心
 * 海外大厂隐私
   * [apple隐私中心](https://www.apple.com.cn/privacy/) | 隐私是每个人的基本权利，同时也是 Apple 的一项核心价值观。
   * [google隐私中心](https://policies.google.com/?hl=zh-CN) | We keep more people safe online than anyone else in the world |[隐私原则](https://safety.google/principles/?hl=zh_CN)。 
   * [uber新隐私中心](https://privacy.uber.com/privacy/center) | Your trust is important to us | [隐私原则](https://www.uber.com/global/en/privacy/overview) 
   * [facebook新隐私中心](https://www.facebook.com/privacy/center)   
   * [aws隐私中心](https://aws.amazon.com/cn/compliance/data-privacy/) | 通过透明度赢取信任
   * [tiktok隐私中心](https://www.tiktok.com/safety/en/) |创造一个让每个人都感到安全和舒适的温馨环境
   * [twitter隐私中心](https://privacy.twitter.com/en) |Control your Twitter experience

 * 国内大厂隐私
    * [腾讯隐私中心](https://privacy.qq.com/home) |腾讯视用户信息安全与隐私保护为自己的生命线 
    * [华为隐私中心](https://consumer.huawei.com/cn/privacy/) |华为用创新科技保护你的隐私
    * [小米隐私中心 ](https://privacy.miui.com/) |小米一直将用户的信息安全和隐私保护视为我们的生存之本。
    * [阿里隐私中心](https://privacy.alibabagroup.com/#/home) |安全有责 隐私有界 
    * [阿里云隐私中心](https://security.aliyun.com/trust) |云即信任 
    * [百度隐私中心](http://privacy.baidu.com/)  | 同意，透明，可控

## 隐私新技术
   
 * 隐私计算
   * [primihub](https://github.com/primihub/primihub) 支持多方计算和隐私学习的一个开源平台
 
 * 隐私存储
   * [immudb](https://github.com/codenotary/immudb)  零信任数据库，初步看自带留痕和加密

 * 端隐私技术  
   * [android 隐私沙盒技术](https://developer.android.com/design-for-safety/ads)   
 
 * 隐私体系学习
   * CIPT认证脑图
     * [chapter1-privacy 脑图](./files/CIPT/chapter1-privacy.png)
     * [chapter2-1 Engineer&Privacy 脑图](./files/CIPT/chapter2-1%20Engineer&%20Privacy.png)
     * [chapter2-2 Engineer&Privacy 脑图](./files/CIPT/chapter2-2%20Engineer%20&%20Privacy.png)
    

## 相关工具
  
  * 隐私
    * [Android 隐私沙盒](https://developer.android.google.cn/design-for-safety/privacy-sandbox) - 保护隐私同时为移动应用打造高效的个性化广告体验，[当前进度](https://developer.android.google.cn/design-for-safety/privacy-sandbox/progress-updates/latest)
    * [GDPR-checklist](https://github.com/privacyradius/gdpr-checklist) - GDPR的一个检查工具，目前看相对简单
    * [website-evidence-collector](https://github.com/EU-EDPS/website-evidence-collector) - EDPS的网页收集和隐私分析服务
    * [European web analytics services](https://european-alternatives.eu/category/web-analytics-services) - 隐私一个网页分析服务
    * [privacy tools](https://www.privacytools.io/) - 隐私相关工具合集
  * 检索
     * [searx: Privacy-respecting metasearch engine](https://github.com/searx/searx) - 隐私防追踪检索引擎
     * [DuckDuckGo](https://duckduckgo.com/) - 非追踪检索
  * 扫描
    * [dataDog- sensitive data scanner](https://www.datadoghq.com/product/sensitive-data-scanner/) - datadog敏感数据扫描，敏感数据包含token等
  * 网络
     * [ipleak](https://ipleak.net/) - 检查IP泄露工具
     * [Browser Leaks ](https://browserleaks.com/) - 检查浏览器泄露信息工具
     * [DNS Leaks ](https://www.dnsleaktest.com/) - 检查DNS泄露信息工具
  * 脱敏
      * [google homomorphic](https://github.com/google/fully-homomorphic-encryption) - google 同态加密
      * [google differential-privacy](https://github.com/google/differential-privacy) - google 差分隐私
      * [bytedance godlp](https://github.com/bytedance/godlp) - 头条go dlp
* 政策
    * [gihub policy](https://github.com/github/site-policy)  - github开源了所有的政策包
    * [Medium's Policies and Guidelines](https://github.com/Medium/medium-policy)  - 中小型的隐私政策包
    * [Employee IP](https://github.com/github/balanced-employee-ip-agreement/blob/main/Employee_IP_Laws.md)  - 员工IP和知识产权相关的法规

## 书籍
   * 英文书籍
     * [data-privacy](https://www.manning.com/books/data-privacy)
   
   * 中文书籍
   
   * 英文视频
     * [TED - Why Privacy Matters](https://www.ted.com/talks/glenn_greenwald_why_privacy_matters) - by Glenn Greenwald
     * [TED - Online Privacy Doesn't Exist ](https://www.youtube.com/watch?v=LgWrD3EJ1Do) - 数据导致的意想不到的危险，作者：Denelle Dixon
     * [TED - Data is the new gold, who are the new thieves? ](https://www.youtube.com/watch?v=XNF-rGiGb50) - 数据利用，作者：Tijmen Schep
     

## 网站外链
 * github
   * [awesome-sec-talks](https://github.com/PaulSec/awesome-sec-talks) - 安全相关的讲座，组织和会议
   * [awesome-privacy](https://github.com/pluja/awesome-privacy) - 英文隐私相关有意思内容
   * [awesome-security](https://github.com/sbilly/awesome-security) - 英文安全相关有意思内容
   * [awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection) - 英文攻击检测相关
   * [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - 引文自托管服务相关
   * [mac os 安全和隐私指南](https://github.com/drduh/macOS-Security-and-Privacy-Guide/blob/master/README-cn.md) - mac os的隐私安全指南 
 * 政府相关
    * [人民数保](https://pdc.peopleyun.cn/home) - 人民网提供的二次数据上链和确权、共享的平台，目前非常初期。 | [PDC白皮书](https://pdc.peopleyun.cn/dataSourceCentre?tabIndex=1)
    * [singpass](https://www.singpass.gov.sg/main) - 新加坡的政府个人数据存储网站，做的相对比较完整，类似于国内人民数保和韩国Mydata
 * 标准相关网站
   * [W3C privacy](https://www.w3.org/Privacy/) - W3C隐私工作组
   * [pixelprivacy](https://pixelprivacy.com/resources/) - 在线隐私指南
   * [privacytools](https://www.privacytools.io/) - 隐私指南：使用加密和隐私工具对抗监视
 * 新闻相关网站
   * [spreadprivacy](https://spreadprivacy.com/) -duckduckgo官方blog
   * [OWASP Top Ten](https://owasp.org/www-project-top-ten/) - top 10 web security risk


   