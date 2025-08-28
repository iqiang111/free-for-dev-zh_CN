# free-for-Zh_CN.dev

开发人员和开源作者现在有许多提供免费套餐的服务，但找到它们需要时间来做出明智的决定。

这是具有免费开发人员层级的软件（SaaS、PaaS、IaaS 等）和其他产品的列表。

此特定列表的范围仅限于基础设施开发人员（系统管理员、DevOps 从业者等）可能认为有用的东西。我们喜欢那里的所有免费服务，但最好把它放在主题上。有时这是一条灰线，所以这是固执己见的;如果我不接受你的贡献，请不要感到被冒犯。

此列表来自 1600+ 人完成的拉取请求、评论、想法和工作。还可以通过发送[拉取请求](https://github.com/ripienaar/free-for-dev)来添加更多服务或删除其产品已更改或已停用的服务来提供帮助。

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

**注意** ：此列表仅适用于即服务产品，不适用于自承载软件。要获得资格，服务必须提供免费套餐，而不仅仅是免费试用。如果免费套餐是时间桶，则必须至少为一年。我们也从安全角度考虑了免费套餐，所以 SSO 很好，但我不会接受将 TLS 限制为付费套餐的服务。

# 目录

* [主要云提供商的始终免费限制](#主要云提供商)
* [云管理解决方案](#云管理解决方案)
* [分析、事件和统计](#分析、事件和统计)
* [API、数据和机器学习](#API、数据和机器学习)
* [工件存储库](#工件存储库)
* [BaaS](#baas)
* [低代码平台](#低代码平台)
* [CDN 和保护](#CDN-和保护)
* [CI 和 CD](#CI-和-CD)
* [CMS 系统](#CMS-系统)
* [代码生成](#代码生成)
* [代码质量](#代码质量)
* [代码搜索和浏览](#代码搜索和浏览)
* [崩溃和异常处理](#崩溃和异常处理)
* [地图上的数据可视化](#地图上的数据可视化)
* [托管数据服务](#托管数据服务)
* [设计和用户界面](#设计和用户界面)
* [设计灵感](#设计灵感)
* [开发博客网站](#开发博客网站)
* [DNS](#域名系统)
* [Docker 相关](#Docker-相关)
* [域](#域)
* [教育和职业发展](#教育和职业发展)
* [电子邮件](#电子邮件)
* [功能切换管理平台](#功能切换管理平台)
* [字体](#字体)
* [形式](#形式)
* [生成式人工智能](#生成式人工智能)
* [IaaS](#iaas)
* [IDE 和代码编辑](#IDE-和代码编辑)
* [国际手机号码验证 API 和 SDK](#国际手机号码验证-API-和-SDK)
* [问题跟踪和项目管理](#问题跟踪和项目管理)
* [日志管理](#日志管理)
* [移动应用程序分发和反馈](#移动应用程序分发和反馈)
* [管理体系](#管理体系)
* [消息传递和流媒体](#消息传递和流媒体)
* [杂项](#杂项)
* [监测](#监测)
* [PaaS](#paas)
* [包构建系统](#包构建系统)
* [支付和计费集成](#支付和计-费集成)
* [隐私管理](#隐私管理)
* [屏幕截图 API](#屏幕截图-API)
* [Flutter 相关和构建 IOS 应用程序，无需 Mac](#Flutter-相关和构建-IOS-应用程序，无需-Mac)
* [搜索](#搜索)
* [安全性和 PKI](#安全性和-PKI)
* [身份验证、授权和用户管理](#身份验证、授权和用户管理)
* [源代码存储库](#源代码存储库)
* [存储和介质处理](#存储和介质处理)
* [隧道、WebRTC、Web 套接字服务器和其他路由器](#隧道、WebRTC、Web-套接字服务器和其他路由器)
* [测试](#测试)
* [团队和协作工具](#团队和协作工具)
* [翻译管理](#翻译管理)
* [流浪者相关](#流浪者相关)
* [访客会话记录](#访客会话记录)
* [虚拟主机](#虚拟主机)
* [评论平台](#评论平台)
* [基于浏览器的硬件仿真](#基于浏览器的硬件仿真)
* [远程桌面工具](#远程桌面工具)
* [游戏开发](#游戏开发)
* [其他免费资源](#其他免费资源)

## 主要云提供商

* [谷歌云平台](https://cloud.google.com)

  * App Engine - 每天 28 个前端实例小时，每天 9 个后端实例小时
  * Cloud Firestore - 每天 1GB 存储空间、50,000 次读取、20,000 次写入、20,000 次删除
  * Compute Engine - 每月 1 个非抢占式 e2-micro、30GB 硬盘、5GB 快照存储（仅限于某些区域）、1 GB 网络出口从北美到所有区域目标（不包括中国和澳大利亚）
  * 云存储 - 5GB、1GB 网络出口
  * Cloud Shell - 基于 Web 的 Linux shell/主 IDE，具有 5GB 的持久性存储。每周限制 60 小时
  * Cloud Pub/Sub - 每月 10GB 的消息
  * Cloud Functions - 每月 200 万次调用（包括后台调用和 HTTP 调用）
  * Cloud Run - 每月 200 万个请求，360,000 GB 秒的内存，180,000 vCPU 秒的计算时间，每月 1 GB 的北美网络出口
  * Google Kubernetes Engine - 一个区域集群不收取集群管理费。每个用户节点均按标准 Compute Engine 定价收费
  * BigQuery - 每月 1 TB 的查询，每月 10 GB 的存储空间
  * Cloud Build - 每天 120 分钟构建
  * 云源存储库 - 最多 5 个用户、50 GB 存储、50 GB 出口
  * [Google Colab](https://colab.research.google.com/) - 免费的 Jupyter Notebooks 开发环境。
  * [Firebase Studio](https://firebase.studio)Google Firebase Studio（以前称为 Project IDX）。在 Google Cloud 上运行的在线 VSCode。
  * 完整、详细的列表 - [https://cloud.google.com/free](https://cloud.google.com/free)
* [亚马逊云科技](https://aws.amazon.com)

  * [CloudFront](https://aws.amazon.com/cloudfront/) - 每月 1TB 出口和每月 2M 函数调用
  * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 10 个自定义指标和 10 个警报
  * [CodeBuild](https://aws.amazon.com/codebuild/) - 每月 100 分钟的构建时间
  * [CodeCommit](https://aws.amazon.com/codecommit/) - 5 个活跃用户，50GB 存储空间，每月 10000 个请求
  * [CodePipeline](https://aws.amazon.com/codepipeline/) - 每月 1 个活动管道
  * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL 数据库
  * [EC2](https://aws.amazon.com/ec2/) - 每月 750 小时的 t2.micro 或 t3.micro（12 个月）。每月 100GB 出口
  * [EBS](https://aws.amazon.com/ebs/) - 每月 30GB 通用 （SSD） 或磁性 （12mo）
  * [弹性负载均衡](https://aws.amazon.com/elasticloadbalancing/) \- 每月 750 小时（12 个月）
  * [RDS](https://aws.amazon.com/rds/) - 每月 750 小时的 db.t2.micro、db.t3.micro 或 db.t4g.micro、20GB 通用 （SSD） 存储、20GB 存储备份（12 个月）
  * [S3](https://aws.amazon.com/s3/) - 5GB 标准对象存储、20K 获取请求和 2K 放置请求（12 个月）
  * [Glacier](https://aws.amazon.com/glacier/) - 10GB 长期对象存储
  * [Lambda](https://aws.amazon.com/lambda/) - 每月 100 万个请求
  * [SNS](https://aws.amazon.com/sns/) - 每月 100 万次发布
  * [SES](https://aws.amazon.com/ses/) - 每月 3.000 条消息（12 个月）
  * [SQS](https://aws.amazon.com/sqs/) - 100 万个消息队列请求
  * 完整、详细的列表 - [https://aws.amazon.com/free/](https://aws.amazon.com/free/)
* [Microsoft Azure](https://azure.microsoft.com)

  * [虚拟机](https://azure.microsoft.com/services/virtual-machines/) \- 1 个 B1S Linux 虚拟机、1 个 B1S Windows 虚拟机（12 个月）
  * [应用服务](https://azure.microsoft.com/services/app-service/) \- 10 个 Web、移动或 API 应用（60 CPU 分钟/天）
  * [函数](https://azure.microsoft.com/services/functions/) \- 每月 100 万个请求
  * [开发测试实验室](https://azure.microsoft.com/services/devtest-lab/) \- 实现快速、简单和精益的开发测试环境
  * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 个对象
  * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 每月 50,000 个存储用户
  * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 个活动用户，无限制的专用 Git 存储库
  * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) — 10 个免费并行作业，无限分钟，适用于 Linux、macOS 和 Windows 的开源
  * [Microsoft IoT 中心](https://azure.microsoft.com/services/iot-hub/) \- 每天 8,000 条消息
  * [负载均衡器](https://azure.microsoft.com/services/load-balancer/) \- 1 个免费的公共负载均衡 IP （VIP）
  * [通知中心](https://azure.microsoft.com/services/notification-hubs/) \- 100 万个推送通知
  * [带宽](https://azure.microsoft.com/pricing/details/bandwidth/) \- 每月 15GB 入站（12 个月）和 5GB 出口
  * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 25GB 存储和 1000 RU 的预配吞吐量
  * [静态 Web 应用程序](https://azure.microsoft.com/pricing/details/app-service/static/) — 使用免费的 SSL、身份验证/授权和自定义域构建、部署和托管静态应用程序和无服务器功能
  * [存储](https://azure.microsoft.com/services/storage/) \- 5GB LRS 文件或 Blob 存储 （12 个月）
  * [认知服务](https://azure.microsoft.com/services/cognitive-services/) \- 具有免费层（包括有限事务）的 AI/ML API（计算机视觉、翻译器、人脸检测、机器人等）
  * [认知搜索](https://azure.microsoft.com/services/search/#features) \- 基于 AI 的搜索和索引服务，免费提供 10,000 个文档
  * [Azure Kubernetes 服务](https://azure.microsoft.com/services/kubernetes-service/) \- 托管 Kubernetes 服务，免费群集管理
  * [事件网格](https://azure.microsoft.com/services/event-grid/) \- 100K 作/月
  * 完整、详细的列表 - [https://azure.microsoft.com/free/](https://azure.microsoft.com/free/)
* [Oracle 云](https://www.oracle.com/cloud/)

  * 计算
    * 2 个基于 AMD 的计算虚拟机，每个虚拟机具有 1/8 OCPU 和 1 GB 内存
    * 4 个基于 Arm 的 Ampere A1 内核和 24 GB 内存，可用作一个虚拟机或最多 4 个虚拟机
    * 实例在[被视为空闲](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)时将被回收
  * 块存储卷 - 2 个卷，总共 200 GB（用于计算）
  * 对象存储 - 10 GB
  * 负载均衡器 - 1 个 10 Mbps 的实例
  * 数据库 - 2 个数据库，每个数据库 20 GB
  * 监控 - 5 亿个摄取数据点，10 亿个检索数据点
  * 带宽 - 每月 10 TB 出口，在基于 x64 的 VM 上速度限制为 50 Mbps，在基于 ARM 的 VM 上限制为 500 Mbps \* 核心计数
  * 公共 IP - 2 个 IPv4 用于虚拟机，1 个 IPv4 用于负载均衡器
  * 通知 - 每月 100 万个交付选项，每月发送 1000 封电子邮件
  * 完整、详细的列表 - [https://www.oracle.com/cloud/free/](https://www.oracle.com/cloud/free/)
* [IBM 云](https://www.ibm.com/cloud/free/)

  * Cloudant 数据库 - 1 GB 的数据存储
  * Db2 数据库 - 100MB 的数据存储
  * API Connect - 每月 50,000 个 API 调用
  * 可用性监控 - 每月 300 万个数据点
  * 日志分析 - 500MB 的每日日志
  * 完整、详细的列表 - [https://www.ibm.com/cloud/free/](https://www.ibm.com/cloud/free/)
* [Cloudflare](https://www.cloudflare.com/)

  * [应用程序服务](https://www.cloudflare.com/plans/) \- 无限数量域的免费 DNS、DDoS 防护、CDN 以及免费 SSL、防火墙规则和页面规则、WAF、机器人缓解、免费不限流量速率限制 - 每个域 1 个规则、分析、电子邮件转发
  * [零信任和 SASE](https://www.cloudflare.com/plans/zero-trust-services/) - 最多 50 个用户、24 小时活动日志记录、三个网络位置
  * [Cloudflare 隧道](https://www.cloudflare.com/products/tunnel/) \- 您可以在使用[快速隧道](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/)时将通过隧道本地运行的 HTTP 端口公开到随机子域 trycloudflare.com 无需帐户。 [零信任](https://www.cloudflare.com/products/zero-trust/)免费计划中的更多功能（TCP 隧道、负载平衡、VPN）。
  * [Workers](https://developers.cloudflare.com/workers/) - 在 Cloudflare 的全球网络上免费部署无服务器代码 - 每天 100k 个请求。
  * [Workers KV](https://developers.cloudflare.com/kv) - 每天 100k 个读取请求，每天 1000 个写入请求，每天 1000 个删除请求，每天 1000 个列表请求，1 GB 存储数据
  * [R2](https://developers.cloudflare.com/r2/) - 每月 10 GB，每月 100 万次 A 类作，每月 1000 万次 B 类作
  * [D1](https://developers.cloudflare.com/d1/) - 每天读取 500 万行，每天写入 100k 行，1 GB 存储
  * [页面](https://developers.cloudflare.com/pages/) \- 在 Cloudflare 快速、安全的全球网络上开发和部署您的 Web 应用程序。500 个月度构建、100 个自定义域、集成 SSL、无限可访问席位、无限预览部署以及通过 Cloudflare Workers 集成的全栈功能。
  * [队列](https://developers.cloudflare.com/queues/) \- 每月 100 万次作
  * [TURN](https://developers.cloudflare.com/calls/turn/) – 每月 1TB 的免费（传出）流量。

**[⬆️ 返回首页](#目录)**

## 云管理解决方案

* [Brainboard](https://www.brainboard.co) - 用于端到端可视化构建和管理云基础设施的协作解决方案。
* [Cloud 66](https://www.cloud66.com/) - 个人项目免费（包括一个部署服务器、一个静态站点），Cloud 66 为您提供在任何云上构建、部署和扩展应用程序所需的一切，而无需为“服务器”而烦恼。
* [Pulumi](https://www.pulumi.com/) — 现代基础设施即代码平台，允许您使用熟悉的编程语言和工具来构建、部署和管理云基础设施。
* [terraform.io](https://www.terraform.io/) — Terraform 云。免费远程状态管理和团队协作，最多可容纳 500 个资源。
* [scalr.com](https://scalr.com/) - Scalr 是 Terraform 自动化和集成 （TACO） 产品，用于在 Terraform 管理的基础结构和配置上更好地协作和自动化。完整的 Terraform CLI 支持、OPA 集成和分层配置模型。没有 SSO 税。包括所有功能。每月最多免费使用 50 次运行。
* [deployment.io](https://deployment.io) - Deployment.io 帮助开发人员在 AWS 上自动部署。在我们的免费套餐中，开发人员（单个用户）可以部署无限的静态站点、Web 服务和环境。我们每月免费提供 20 次作业执行，免费层中包含预览版和自动部署。

**[⬆️ 返回首页](#目录)**

## 源代码存储库

* [Bitbucket](https://bitbucket.org/) — 无限的公共和私有 Git 存储库，最多可容纳 5 个用户，带有 CI/CD 的管道
* [chiselapp.com](https://chiselapp.com/) — 无限的公共和私有 Fossil 存储库
* [codebasehq.com](https://www.codebasehq.com/) — 一个免费项目，空间为 100 MB，有两个用户
* [Codeberg](https://codeberg.org/) — 免费和开源项目（具有无限协作者）的无限公共和私有 Git 存储库。由 [Forgejo](https://forgejo.org/) 提供支持。使用 [Codeberg Pages](https://codeberg.page/) 进行静态网站托管。使用 [Codeberg 的 CI](https://docs.codeberg.org/ci/) 进行 CI/CD 托管。使用 [Codeberg Translate](https://translate.codeberg.org/) 翻译托管。包括包和容器托管、项目管理和问题跟踪
* [GitGud](https://gitgud.io) — 无限的私有和公共存储库。永远免费。由 GitLab 和 Sapphire 提供支持。未提供 CI/CD。
* [GitHub](https://github.com/) — 无限的公共存储库和无限的私有存储库（具有无限的协作者）。包括 CI/CD、开发环境、静态托管、包和容器托管、项目管理和 AI Copilot
* [gitlab.com](https://about.gitlab.com/) — 无限的公共和私有 Git 存储库，最多有 5 个协作者。包括 CI/CD、静态托管、容器注册表、项目管理和问题跟踪
* [framagit.org](https://framagit.org/) — Framagit 是 Framasoft 基于 Gitlab 软件的软件锻造，包括 CI、静态页面、项目页面和问题跟踪。
* [heptapod.net](https://foss.heptapod.net/) — Heptapod 是 GitLab 社区版的一个友好分支，为 Mercurial 提供支持
* [ionicframework.com](https://ionicframework.com/appflow) - 使用 Ionic 开发应用程序的存储库和工具;你还有一个离子存储库
* [NotABug](https://notabug.org) — NotABug.org 是一个免费软件代码协作平台，用于基于 Git 的免费许可项目
* [OSDN](https://osdn.net/) - OSDN.net 是一项面向开源软件开发人员的免费服务，提供 SVN/Git/Mercurial/Bazaar/CVS 存储库。
* [Pagure.io](https://pagure.io) — Pagure.io 是一个免费的开源软件代码协作平台，适用于基于 Git 的 FOSS 许可项目
* [perforce.com](https://www.perforce.com/products/helix-teamhub) — 免费的 1GB 云和 Git、Mercurial 或 SVN 存储库。
* [pijul.com](https://pijul.com/) - 无限制的免费开源分布式版本控制系统。它的显着特点是基于完善的补丁理论，这使得它易于学习、使用和分发。解决了 git/hg/svn/darcs 的许多问题。
* [plasticscm.com](https://plasticscm.com/) — 对个人、OSS 和非营利组织免费
* [projectlocker.com](https://projectlocker.com) — 一个免费的私有项目（Git 和 Subversion），空间为 50 MB
* [RocketGit](https://rocketgit.com) — 基于 Git 的存储库托管。无限的公共和私有存储库。
* [savannah.gnu.org](https://savannah.gnu.org/) - 作为自由软件项目的协作软件开发管理系统（用于 GNU 项目）
* [savannah.nongnu.org](https://savannah.nongnu.org/) - 作为自由软件项目（用于非 GNU 项目）的协作软件开发管理系统

**[⬆️ 返回首页](#目录)**

## API、数据和机器学习

* [JSONGrid](https://jsongrid.com) - 免费工具，可将复杂的 JSON 数据可视化、编辑、过滤成漂亮的表格网格。通过链接链接保存和共享 JSON 数据。
* [Zerosheets](https://zerosheets.com) - 将您的 Google 表格电子表格转换为功能强大的 API，以快速开发原型、网站、应用程序等。每月免费提供 500 个请求。
* [知识产权。城市](https://ip.city) — 每天 100 个免费 IP 地理定位请求
* [抽象 API](https://www.abstractapi.com) — 适用于各种用例的 API 套件，包括 IP 地理位置、性别检测或电子邮件验证。
* [Apify](https://www.apify.com/) — 网络抓取和自动化平台，可为任何网站创建 API 并提取数据。现成的抓取工具、集成代理和定制解决方案。免费计划，每月包含 5 美元的平台积分。
* [APITemplate.io](https://apitemplate.io) - 使用简单的 API 或自动化工具（如 Zapier 和 Airtable）自动生成图像和 PDF 文档。不需要 CSS/HTML。免费计划每月附带 50 张图像和三个模板。
* [APIToolkit.io](https://apitoolkit.io) - 充分了解 API 和后端中发生的情况所需的所有工具。具有自动 API 合约验证和监控功能。免费计划涵盖每天最多有 10,000 个请求的服务器。
* [APIVerve](https://apiverve.com) - 免费即时访问超过 120+ 个 API，这些 API 在构建时充分考虑了质量、一致性和可靠性。免费计划每月最多涵盖 50 个 API 代币。（可能被删除，2025-06-25）
* [Arize AI](https://arize.com/) - 用于模型监控和导致根本问题（如数据质量和性能漂移）的机器学习可观察性。最多免费提供两种型号。
* [Maxim AI](https://getmaxim.ai/) - 模拟、评估和观察您的 AI 代理。Maxim 是一个端到端的评估和可观测性平台，可帮助团队可靠地交付 AI 代理，速度提高 3E5 倍。独立开发者和小型团队永久免费（3 个席位）。
* [Beeceptor](https://beeceptor.com) - 在几秒钟内模拟休息 API、虚假 API 响应等等。每天免费 50 个请求、公共仪表板、开放终结点（任何拥有仪表板链接的人都可以查看提交和答案）。
* [BigDataCloud](https://www.bigdatacloud.com/) - 为现代网络提供快速、准确和免费（无限制或最多 10K-50K/月）的 API，例如 IP 地理定位、反向地理编码、网络洞察、电子邮件和电话验证、客户信息等。
* [浏览 AI](https://www.browse.ai) — 提取和监控网络上的数据。每月免费 1k 积分，等于 1k 并发请求。
* [BrowserCat](https://www.browsercat.com) - 用于自动化、抓取、AI 代理 Web 访问、图像/pdf 生成等的无头浏览器 API。免费计划，每月 1k 请求。
* [Calendarific](https://calendarific.com) - 面向 200 多个国家/地区的企业级公共假期 API 服务。免费计划包括每月 500 个电话。
* [Canopy](https://www.canopyapi.co/) - 用于 Amazon.com 产品、搜索和类别数据的 GraphQL API。免费计划包括每月 100 个电话。
* [Clarifai](https://www.clarifai.com) — 用于自定义人脸识别和检测的图像 API。能够训练人工智能模型。免费计划每月有 1,000 个电话。
* [Cloudmersive](https://cloudmersive.com/) — 实用 API 平台，可完全访问广泛的 API 库，包括文档转换、病毒扫描等，每月 600 次调用，仅限北美 AZ，最大文件大小为 2.5MB。
* [Colaboratory](https://colab.research.google.com) — 带有 Nvidia Tesla K80 GPU 的免费基于 Web 的 Python 笔记本环境。
* [CometML](https://www.comet.com/site/) - 用于实验跟踪、模型生产管理、模型注册和完整数据沿袭的 MLOps 平台，涵盖从训练到生产的工作流程。对个人和学者免费。
* [Commerce Layer](https://commercelayer.io) - 可组合的商务 API，可以从任何前端构建、下单和管理订单。开发人员计划允许每月 100 个订单和最多 1,000 个免费 SKU。
* [Composio](https://composio.dev/) - AI 代理和法学硕士的集成平台。在代理互联网上集成超过 200+ 工具。
* [转换工具](https://conversiontools.io/) \- 用于文档、图像、视频、音频和电子书的在线文件转换器。REST API 可用。Node.js、PHP、Python 的库。支持高达 50 GB 的文件（对于付费计划）。免费套餐受文件大小 （20MB） 和转换次数（30 次/天，300 次/月）的限制。
* [国家-州-城市微服务 API](https://country-state-city.rebuscando.info/) - API 和微服务提供广泛的信息，包括国家、地区、省、市、邮政编码等。免费套餐包括每天最多 100 个请求。
* [耦合器](https://www.coupler.io/) \- 在应用程序之间同步的数据集成工具。它可以创建实时仪表板和报告，转换和作值，以及收集和备份见解。免费计划仅限于一个用户、数据连接、数据源和数据目标。还需要手动数据刷新。
* [CraftMyPDF](https://craftmypdf.com) - 使用拖放编辑器和简单的 API 从可重复使用的模板自动生成 PDF 文档。免费计划每月附带 100 个 PDF 和三个模板。
* [Crawlbase](https://crawlbase.com/) — 在没有代理、基础设施或浏览器的情况下抓取和抓取网站。我们为您解决验证码并防止您被阻止。前 1000 个电话是免费的。
* [CurlHub](https://curlhub.io) — 用于检查和调试 API 调用的代理服务。免费计划包括每月 10,000 个请求。
* [CurrencyScoop](https://currencyscoop.com) - 用于金融科技应用程序的实时货币数据 API。免费计划包括每月 5,000 个电话。
* [Cube](https://cube.dev/) - Cube 帮助数据工程师和应用程序开发人员访问新式数据存储中的数据，将其组织成一致的定义，并将其交付给每个应用程序。使用 Cube 的最快方法是使用 Cube Cloud，它的免费套餐限制为每天 1,000 个查询。
* [Data Dead Drop](https://datadeaddrop.com) - 简单、免费的文件共享。数据在访问后会自我销毁。通过浏览器或您最喜欢的命令行客户端上传和下载数据。
* [Data Fetcher](https://datafetcher.com) - 无需代码即可将 Airtable 连接到任何应用程序或 API。类似 Postman 的界面，用于在 Airtable 中运行 API 请求。与数十个应用程序的预构建集成。免费计划包括每月 100 次运行。
* [Dataimporter.io](https://www.dataimporter.io) - 用于连接、清理数据并将其导入 Salesforce 的工具。免费计划包括每月多达 20,000 条记录。
* [Datalore](https://datalore.jetbrains.com) - Jetbrains 的 Python 笔记本。包括每月 10 GB 的存储空间和 120 小时的运行时间。
* [数据挖掘器](https://dataminer.io/) \- 用于从网页 CSV 或 Excel 中提取数据的浏览器扩展（Google Chrome、MS Edge）。免费计划每月为您提供 500 页。
* [Datapane](https://datapane.com) - 用于在 Python 中构建交互式报表并将 Python 脚本和 Jupyter Notebook 部署为自助服务工具的 API。
* [DB-IP](https://db-ip.com/api/free) - 免费的 IP 地理定位 API，每个 IP 每天有 1k 请求。CC-BY 4.0 许可证下的 lite 数据库也是免费的。
* [数据库设计器](https://www.dbdesigner.net/) — 基于云的数据库模式设计和建模工具，具有 2 个数据库模型和每个模型 10 个表的免费入门计划。
* [DeepAR](https://developer.deepar.ai) — 具有一个 SDK 适用于任何平台的增强现实面部滤镜。免费计划提供多达 10 个每月活跃用户 （MAU） 并跟踪多达 4 张面孔
* [Deepnote](https://deepnote.com) - 一种新的数据科学笔记本。Jupyter 与实时协作兼容并在云中运行。免费套餐包括无限的个人项目、具有 5GB RAM 和 2vCPU 的无限基本机器以及最多拥有 3 名编辑的团队。
* [Disease.sh](https://disease.sh/) — 一个免费的 API，为构建与 Covid-19 相关的有用应用程序提供准确的数据。
* [Doczilla](https://www.doczilla.app/) — SaaS API 支持直接从 HTML/CSS/JS 代码生成屏幕截图或 PDF。免费计划允许每月 250 个文档。
* [Doppio](https://doppio.sh/) — 托管 API，用于使用顶级渲染技术生成和私下存储 PDF 和屏幕截图。免费计划每月允许 400 个 PDF 和屏幕截图。
* [drawDB](https://drawdb.app/) — 免费的开源在线数据库图编辑器，无需注册。
* [dreamfactory.com](https://dreamfactory.com/) — 用于移动、Web 和 IoT 应用程序的开源 REST API 后端。连接任何 SQL/NoSQL 数据库、文件存储系统或外部服务，它会立即创建一个具有实时文档和用户管理功能的综合 REST API 平台。
* [Duply.co](https://duply.co) — 从 API 和 URL 创建动态图像，设计模板一次并重复使用。免费套餐提供 20 个免费积分。
* [DynamicDocs](https://advicement.io) - 基于 LaTeX 模板生成带有 JSON 到 PDF API 的 PDF 文档。免费计划允许每月 50 次 API 调用并访问模板库。
* [Efemarai](https://efemarai.com) - ML 模型和数据的测试和调试平台。可视化任何计算图。免费本地使用。
* [ERD 实验室](https://www.erdlab.io) — 为开发人员制作的免费基于云的实体关系图 （ERD） 工具。免费试用包括 2 个项目，每个项目有 10 张桌子。
* [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免费的基于 Web 的 HTTP 客户端，用于发送 HTTP 请求。
* [导出 SDK](https://exportsdk.com) - 带有拖放模板编辑器的 PDF 生成器 API，提供 SDK 和无代码集成。免费计划每月有 250 个页面、无限用户和三个模板。
* [file.coffee](https://file.coffee/) - 一个平台，您可以在其中存储最多 15MB/文件（30/MB 文件，带帐户）。
* [财务数据](https://financialdata.net/) \- 股票市场和财务数据 API。免费计划每天允许 300 个请求。
* [FormatJSONOnline.com](https://formatjsononline.com) - 一个免费的、基于浏览器的工具，用于立即格式化、验证、比较和缩小 JSON 数据。
* [FraudLabs Pro](https://www.fraudlabspro.com) — 筛选订单交易是否存在信用卡支付欺诈。此 REST API 将根据订单的输入参数检测所有可能的欺诈特征。免费微型计划每月有 500 笔交易。
* [GeoDataSource](https://www.geodatasource.com) - 位置搜索服务使用纬度和经度坐标查找城市名称。每月最多可免费查询 500 次。
* [Geolocated.io](https://geolocated.io) — 具有多大洲服务器的 IP 地理定位 API，提供每天 2,000 个请求的免费计划。
* [Glitterly](https://glitterly.app/) - 以编程方式从基本模板生成动态图像。Restful API 和无代码集成。免费套餐每月提供 50 张图像和五个模板。
* [Hex](https://hex.tech/) - 用于笔记本、数据应用和知识库的协作数据平台。免费社区层，最多包含五个项目。
* [Hook0](https://www.hook0.com/) - Hook0 是一种开源 Webhook 即服务 （WaaS），可让在线产品轻松提供 Webhook。每天最多可发送 100 个事件，并免费保留 7 天的历史记录。
* [Hoppscotch](https://hoppscotch.io) - 一个免费、快速且美观的 API 请求构建器。
* [huggingface.co](https://huggingface.co) - 为 Pytorch、TensorFlow 和 JAX 构建、训练和部署 NLP 模型。每月最多可释放 30k 输入字符。
* [Hybiscus](https://hybiscus.dev/) - 使用简单的声明式 API 构建 pdf 报告。14 天免费套餐包括 50 个单页报告，能够自定义调色板和字体。
* [Invantive Cloud](https://cloud.invantive.com/) — 使用 Invantive SQL 或 OData4（通常是 Power BI 或 Power Query）访问 70 多个（云）平台，例如 Exact Online、Twinfield、ActiveCampaign 或 Visma。包括数据复制和交换。面向开发人员和实施顾问的免费计划。对数据量有限的特定平台免费。
* [ipaddress.sh](https://ipaddress.sh) — 获取不同[格式](https://about.ipaddress.sh/)的公共 IP 地址的简单服务。
* [ip-api](https://ip-api.com) — IP 地理定位 API，免费用于非商业用途，无需 API 密钥，免费计划限制为同一 IP 地址 45 次/分钟。
* [ipbase.com](https://ipbase.com) - IP 地理定位 API - 永久免费计划，涵盖 150 个每月请求。
* [IP Geolocation —](https://ipgeolocation.io/) IP Geolocation API - 面向开发人员的永久免费计划，每天有 1,000 个请求限制。
* [IP 地理定位 API](https://www.abstractapi.com/ip-geolocation-api) — 抽象的 IP 地理定位 API - 允许 1,000 个免费请求。
* [IPLocate](https://www.iplocate.io) — IP 地理定位 API，每天免费最多 1,000 个请求。包括代理/VPN/托管检测、ASN 数据、IP 到公司等。IPLocate 还以 CSV 或 GeoIP 兼容的 MMDB 格式提供可免费下载的 IP 到国家和 IP 到 ASN 数据库。
* [IP2Location](https://www.ip2location.com) — 免费增值 IP 地理定位服务。LITE 数据库可供免费下载。在服务器中导入数据库，进行本地查询，确定城市、坐标、ISP 信息。
* [IP2Location.io](https://www.ip2location.io/) — 免费增值、快速、可靠的 IP 地理定位 API。获取城市、坐标、ISP 等数据。免费计划包括每月 50k 积分。IP2Location.io 还每月提供 500 个免费的 WHOIS 和托管域名查找。查看域名注册详细信息并查找托管在特定 IP 上的域名。升级到付费计划以获得更多功能。
* [ipapi](https://ipapi.co/) - Kloudend， Inc 的 IP 地址定位 API - 基于 AWS 构建的可靠地理定位 API，受到财富 500 强的信赖。免费套餐提供每月 30k 次查找（1k/天），无需注册。
* [ipapi.is](https://ipapi.is/) - 由开发人员提供的可靠 IP 地址 API，适用于具有现有最佳托管检测功能的开发人员。免费计划无需注册即可提供 1000 次查找。
* [IPinfo](https://ipinfo.io/)：快速、准确、免费（每月最多 50k）的 IP 地址数据 API。提供包含地理位置、公司、运营商、IP 范围、域、滥用联系人等详细信息的 API。所有付费 API 都可以免费试用。
* [IPQuery](https://ipquery.io) — 为开发人员提供无限的 IP API，没有速率限制或定价。
* [IPTrace](https://iptrace.io) — 一个简单得令人尴尬的 API，每月提供 50,000 次免费查找，为您的企业提供可靠且有用的 IP 地理位置数据。
* [JSON2Video](https://json2video.com) - 一个视频编辑 API，用于以编程方式或无代码方式自动执行视频营销和社交媒体视频。
* [JSON IP](https://getjsonip.com) — 返回请求的客户端的公共 IP 地址。免费套餐无需注册。使用 CORS，可以直接从浏览器使用客户端 JS 请求数据。对于服务监控客户端和服务器 IP 的更改很有用。无限请求。
* [JSON Serve](https://jsonserve.com/) — 一项免费服务，可帮助开发人员存储 JSON 对象并在其应用程序中使用该 JSON 作为 REST API。
* [JSONing](https://jsoning.com/api/) — 从 JSON 对象创建虚假的 REST API，并自定义 HTTP 状态代码、标头和响应正文。
* [JSONSwiss](https://www.jsonswiss.com/) - JSONSwiss 是一个功能强大的在线 JSON 查看器、编辑器和验证器。使用 AI 驱动的修复、树视图、表格视图、12+ 编程语言的代码生成、将 json 转换为 csv、xml、yaml、属性等，格式化、可视化、搜索和作 JSON 数据。
* [konghq.com](https://konghq.com/) — API 市场以及强大的私有和公共 API 工具。使用免费套餐时，某些功能（例如监控、警报和支持）受到限制。
* [Kreya](https://kreya.app) — 免费的 gRPC GUI 客户端，用于调用和测试 gRPC API。可以通过服务器反射导入 gRPC API。
* [轻微](https://www.lightly.ai/) — 使用正确的数据改进机器学习模型。免费使用多达 1000 个样本的数据集。
* [LoginLlama](https://loginllama.app) - 一个登录安全 API，用于检测欺诈和可疑登录并通知您的客户。每月 1,000 次登录免费。
* [MailboxValidator](https://www.mailboxvalidator.com) — 使用真实邮件服务器连接来确认有效电子邮件的电子邮件验证服务。免费 API 计划每月有 100 次验证。
* [市场数据 API](https://www.marketdata.app) - 提供股票、期权、共同基金等的实时和历史财务数据。永久免费 API 层允许每天免费处理 100 个 API 请求。
* [Meteosource Weather API](https://www.meteosource.com/) — 用于当前和预测天气数据的全球天气 API。预报基于更多天气模型的机器学习组合，以实现更高的准确性。免费计划每天提供 400 个电话。
* [microlink.io](https://microlink.io/) – 它将任何网站转换为数据，例如元标记规范化、美容链接预览、抓取功能或屏幕截图即服务。每天 50 个请求，每天免费。
* [Mindee](https://developers.mindee.com) – Mindee 是一款功能强大的 OCR 软件和 API 优先平台，可帮助开发人员通过使用计算机视觉和机器学习对关键信息进行数据识别来标准化文档处理层，从而实现应用程序工作流程的自动化。免费套餐每月提供 500 页。
* [Mintlify](https://mintlify.com) — API 文档的现代标准。美观且易于维护的 UI 组件、应用内搜索和交互式游乐场。1 位编辑免费。
* [MockAPI](https://www.mockapi.io/) — MockAPI 是一个简单的工具，可让您使用 RESTful 接口快速模拟 API、生成自定义数据和执行作。MockAPI 旨在成为原型设计/测试/学习工具。一个项目/每个项目 2 个资源免费。
* [Mockfly](https://www.mockfly.dev/) — Mockfly 是一款值得信赖的 API 模拟和功能标志管理开发工具。通过直观的界面快速生成和控制模拟 API。免费套餐每天提供 500 个请求。
* [Mocki](https://mocki.io) - 一种工具，可用于创建同步到 GitHub 存储库的模拟 GraphQL 和 REST API。简单的 REST API 无需注册即可免费开发和使用。
* [Mocko.dev](https://mocko.dev/) — 免费代理您的 API，选择要在云中模拟的端点并检查流量。加快开发和集成测试。
* [Mocky](https://designer.mocky.io/) - 一个简单的 Web 应用程序，用于生成用于模拟 HTTP 请求的自定义 HTTP 响应。也可作为[开源](https://github.com/julien-lafont/Mocky)使用。
* [Mock N Roll](https://mpcknroll.me/) - 免费模拟 API 服务 — 一个强大的工具，可以模拟真实的 API 响应，而不会出现后端延迟。非常适合前端开发人员、QA 测试人员和 DevOps 团队。 [存储库](https://github.com/haerulmuttaqin/mocknroll-web) 。
* [microenv.com](https://microenv.com) — 为开发人员创建虚假的 REST API，可以在 docker 容器中生成代码和应用程序。
* [多出口 IP 地址检查器](https://ip.alstra.ca/) — 一个免费且简单的工具，用于检查跨多个节点的出口 IP 地址，并了解您的 IP 在全球不同地区和服务中的显示情况。对于测试基于规则的 DNS 拆分工具（如控制 D）非常有用。
* [Namekit](https://namekit.app/) - 人工智能驱动的域名发现 - 立即查找可用的标准价格名称。免费每日查询。
* [新闻 API](https://newsapi.org) — 使用代码在 Web 上搜索新闻，并获取 JSON 结果。开发人员每天免费获得 100 个查询。文章有 24 小时延迟。
* [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API - 每月 100 个免费请求。
* [OCR.Space](https://ocr.space/) — OCR API 解析图像和 pdf 文件，这些文件以 JSON 格式返回文本结果。每月 25,000 个请求是免费的，文件大小限制为 1MB。
* [OpenAPI3 设计器](https://openapidesigner.com/) — 免费直观地创建 Open API 3 定义。
* [parsehub.com](https://parsehub.com/) — 从动态站点中提取数据，将动态网站转换为 API，五个项目免费。
* [Parseur](https://parseur.com) — 每月 20 个免费页面：从 PDF、电子邮件中提取数据。人工智能驱动。完整的 API 访问权限。
* [PDFBolt](https://pdfbolt.com) - 以开发人员为中心的 PDF 生成 API，在设计时考虑到了隐私。它提供受 Stripe 启发的文档，并包括每月 500 次免费 PDF 转换。
* [pdfEndpoint.com](https://pdfendpoint.com) - 使用简单的 API 轻松将 HTML 或 URL 转换为 PDF。每月免费转换一百次。
* [PDF-API.io](https://pdf-api.io) - PDF 自动化 API、可视化模板编辑器或 HTML 到 PDF、动态数据集成以及使用 API 进行 PDF 渲染。免费计划附带一个模板，每月 100 个 PDF。
* [Pixela](https://pixe.la/) - 免费的日流数据库服务。所有作均由 API 执行。还可以使用热图和折线图进行可视化。
* [Postman](https://postman.com) — 借助 API 开发协作平台 Postman，简化工作流程并更快地创建更好的 API。永久免费使用 Postman 应用程序。Postman 云功能也永久免费，但有一定的限制。
* [Insomnia](https://insomnia.rest) - 用于设计和测试 API 的开源 API 客户端，支持 REST 和 GraphQL
* [PrefectCloud](https://www.prefect.io/cloud/) — 一个完整的数据流自动化平台。免费计划包括 5 个已部署的工作流和每月 500 分钟的无服务器计算额度。
* [预设云](https://preset.io/) \- 托管的 Apache Superset 服务。对最多 5 名用户的团队永久免费，具有无限的仪表板和图表、无代码图表生成器和协作 SQL 编辑器。
* [PromptLoop](https://www.promptloop.com/) - PromptLoop 提供 10 倍的 AI 网页抓取，采用时间接近零，在现有工作流程上节省 85%+ 时间，运行速度比手动研究快 4 倍，不折不扣，并包括用于所有研究任务的 REST API 端点。每月前 1,000 个积分免费。
* [Public-API Github 存储库](https://github.com/public-apis/public-apis) — 免费公共 API 列表。
* [Rapidapi](https://rapidapi.com/) - 世界上最大的 API 中心数以百万计的开发人员找到并连接到数千个 API，使用有趣的挑战（带有解决方案）和交互式示例进行 API 开发。
* [Rendi](https://rendi.dev) - FFmpeg API - 用于 FFmpeg 的 REST API，无需处理基础设施即可在线运行 FFmpeg。免费套餐，每月处理配额和 4 个可用 vCPU。
* [RequestBin.com](https://requestbin.com) — 创建一个可以向其发送 HTTP 请求的免费端点。发送到该端点的任何 HTTP 请求都将与关联的有效负载和标头一起记录，以便您可以观察来自 Webhook 和其他服务的建议。
* [reqres.in](https://reqres.in) - 一个免费托管的 REST-API，随时可以响应您的 AJAX 请求。
* [Roboflow](https://roboflow.com) - 创建和部署自定义计算机视觉模型，无需任何机器学习经验。免费套餐包括每月 30 个积分。
* [ROBOHASH](https://robohash.org/) - 从任何文本生成独特而酷炫的图像的 Web 服务。
* [Scraper 的代理](https://scrapersproxy.com) — 用于抓取的简单 HTTP 代理 API。匿名抓取，无需担心限制、阻止或验证码。每月前 100 次成功抓取免费，包括 javascript 渲染（如果您联系支持人员，则更多可用）。
* [刮痧蚂蚁](https://scrapingant.com/) — 无头 Chrome 抓取 API 和免费检查代理服务。Javascript 渲染、高级轮换代理、避免验证码。免费 10,000 个 API 积分。
* [Simplescraper](https://simplescraper.io) — 每次作后触发您的 Webhook。免费计划包括 100 个云抓取积分。
* [Select Star](https://www.selectstar.com/) - 是一个智能数据发现平台，可自动分析和记录您的数据。免费轻量级，包含 2 个数据源、最多 1,000 个表和 25 个用户。
* [Sheetson](https://sheetson.com) - 立即将任何 Google 表格转换为 RESTful API。提供免费计划，包括每张 1,000 行免费行。
* [Siterelic](https://siterelic.com/) - Siterelic API 可让您截取屏幕截图、审核网站、TLS 扫描、DNS 查找、测试 TTFB 等。免费计划每月提供 100 个 API 请求。
* [SerpApi](https://serpapi.com/) - 实时搜索引擎抓取 API。返回 Google、YouTube、必应、百度、沃尔玛和许多其他计算机的结构化 JSON 结果。免费计划包括每月 100 次成功的 API 调用。
* [SmartParse](https://smartparse.io) - SmartParse 是一个数据迁移和 CSV 到 API 平台，提供节省时间和成本的开发人员工具。免费套餐包括每月 300 个处理单元、浏览器上传、数据隔离、断路器和作业警报。
* [Sofodata](https://www.sofodata.com/) - 从 CSV 文件创建安全的 RESTful API。上传 CSV 文件并通过其 API 立即访问数据，从而加快应用程序开发速度。免费计划包括每月 2 个 API 和 2,500 次 API 调用。您不需要信用卡。
* [YourGPT CSV 转 JSON](https://yourgpt.ai/tools/csv-to-json) — 一款快速、免费且注重隐私的在线工具，可直接在浏览器中轻松将 CSV 文件转换为结构化 JSON 数据。
* [Sqlable](https://sqlable.com/) - 免费在线 SQL 工具的集合，包括 SQL 格式化程序和验证器、SQL 正则表达式测试器、虚假数据生成器和交互式数据库游乐场。
* [Stoplight](https://stoplight.io/) - 用于协作设计和记录 API 的 SaaS。免费计划提供免费的设计、模拟和文档工具。
* [Supportivekoala](https://supportivekoala.com/) — 允许您通过模板根据输入自动生成图像。免费计划允许您每月最多创建 50 张图像。
* [Svix](https://www.svix.com/) - Webhook 即服务。每月免费发送多达 50,000 条消息。
* [Tavily AI](https://tavily.com/) - 用于在线搜索和快速洞察和综合研究的 API，具有组织研究结果的能力。免费套餐每月 1000 个请求，无需信用卡。
* [IP API](https://theipapi.com/) - IP 地理定位 API，每天有 1000 个免费请求。提供有关 IP 地址位置的信息，包括国家、城市、地区等。
* [TinyMCE](https://www.tiny.cloud) - 富文本编辑 API。核心功能免费，可无限使用。
* [Tomorrow.io 天气 API](https://www.tomorrow.io/weather-api/) - 提供免费的天气 API 计划。提供准确和最新的天气预报，包括全球覆盖、历史数据和天气监测解决方案。
* [Treblle](https://www.treblle.com) - Treblle 帮助团队构建、交付和管理 API。具有高级 API 日志聚合、可观察性、文档和调试功能。您可以免费获得所有功能，但免费套餐每月最多可请求 250k。
* [UniRateAPI](https://unirateapi.com) – 590+ 种货币和加密货币的实时汇率。免费计划提供无限制的 API 调用，非常适合开发人员和金融应用程序。
* [vatcheckapi.com](https://vatcheckapi.com) - 简单且免费的增值税号验证 API。每月 150 次免费验证。
* [WeatherXu](https://weatherxu.com/) — 全球天气数据，包括当前状况、每小时和每日预报以及通过我们的 API 提供的天气警报。集成 AI 模型和 ML 系统来分析和组合多个天气模型，以提高预报准确性。免费套餐包括每月 10,000 次 API 调用。
* [Webhook Store](https://www.openwebhook.io) - 用于存储第三方 Webhook 并在本地主机上调试它们的工具（ngrok 样式）。开源且可自托管。免费个人域名*用户名* .github.webhook.store，免费公共域名 *anything.webhook.store*。
* [WebScraping.AI](https://webscraping.ai) - 具有内置解析、Chrome 渲染和代理的简单网页抓取 API。每月 2000 次免费 API 调用。
* 权[重和偏差](https://wandb.ai) — 开发人员优先的 MLOps 平台。通过试验跟踪、数据集版本控制和模型管理，更快地构建更好的模型。免费套餐仅适用于个人项目，包括 100 GB 的存储空间。
* [What The Diff](https://whatthediff.ai) - 人工智能驱动的代码审查助手。免费计划每月限制为 25,000 个代币（~10 个 PR）。
* [wolfram.com](https://wolfram.com/language/) — 云中内置的基于知识的算法。
* [wrapapi.com](https://wrapapi.com/) — 将任何网站转换为参数化 API。每月 30k API 调用。
* [Zenscrape](https://zenscrape.com/web-scraping-api) — 具有无头浏览器、住宅 IP 和简单定价的网络抓取 API。每月 1000 次免费 API 调用，并为学生和非营利组织提供额外积分。
* [Zipcodebase](https://zipcodebase.com) - 免费的邮政编码 API，访问全球邮政编码数据。每月 5,000 个免费请求。
* [Zipcodestack](https://zipcodestack.com) - 免费的邮政编码 API 和邮政编码验证。每月一万个免费请求。
* [Zuplo](https://zuplo.com/) - 用于设计、构建 API 并将其部署到 Edge 的免费 API 管理平台。在几分钟内将 API 密钥身份验证、速率限制、开发人员文档和货币化添加到任何 API。OpenAPI 原生且完全可编程，使用 Web 标准 API 和 Typescript。免费计划提供多达 10 个项目、无限的生产边缘环境、每月 1M 个请求和 10GB 出口。
* [DiffJSON](https://diffjson.com) - 一个在线工具，用于比较两个 JSON 数据结构之间的差异，帮助您快速定位 JSON 数据中的差异。

**[⬆️ 返回首页](#目录)**

## 工件存储库

* [Artifactory](https://jfrog.com/start-free/) - 一个工件存储库，支持多种包格式，如 Maven、Docker、Cargo、Helm、PyPI、CocoaPods 和 GitLFS。包括包扫描工具 XRay 和 CI/CD 工具 Pipelines（以前称为 Shipppable），每月 2,000 CI/CD 分钟的免费套餐。
* [central.sonatype.org](https://central.sonatype.org) — Apache Maven、SBT 和其他构建系统的默认工件存储库。
* [cloudrepo.io](https://cloudrepo.io) - 基于云的、私有和公共的、Maven 和 PyPi 存储库。开源项目免费。
* [cloudsmith.io](https://cloudsmith.io) — 简单、安全和集中的存储库服务，适用于 Java/Maven、RedHat、Debian、Python、Ruby、Vagrant 等。免费套餐 + 开源免费。
* [jitpack.io](https://jitpack.io/) — GitHub 上 JVM 和 Android 项目的 Maven 存储库，公共项目免费。
* [repsy.io](https://repsy.io) — 1 GB 免费私有/公共 Maven 存储库。
* [Gemfury](https://gemfury.com) — Maven、PyPi、NPM、Go Module、Nuget、APT 和 RPM 存储库的私有和公共工件存储库。公共项目免费。
* [paperspace](https://www.paperspace.com/) — 构建和扩展 AI 模型，开发、训练和部署 AI 应用程序，免费计划：公共项目、5Gb 存储、基本实例。
* [RepoForge](https://repoforge.io) - 用于 Python、Debian、NPM 包和 Docker 注册表的私有云托管存储库。开源/公共项目的免费计划。
* [RepoFlow](https://repoflow.io) - RepoFlow 通过支持 npm、PyPI、Docker、Go、Helm 等简化包管理。免费试用 10GB 存储空间、10GB 带宽、100 个套餐和云中无限用户，或仅供个人使用。

**[⬆️ 返回首页](#目录)**

## 团队和协作工具

* [3Cols](https://3cols.com/) - 一个免费的基于云的代码片段管理器，用于个人和协作代码。
* [Bitwarden](https://bitwarden.com) — 个人、团队和商业组织存储、共享和同步敏感数据的最简单、最安全的方式。
* [Braid](https://www.braidchat.com/) — 专为团队设计的聊天应用程序。免费用于公共访问组、无限用户、历史记录和集成。此外，它还提供了一个自托管的开源版本。
* [cally.com](https://cally.com/) — 找到开会的最佳时间和日期。使用简单，非常适合小型和大型团体。
* [Calendly](https://calendly.com) — Calendly 是用于连接和安排会议的工具。免费计划为每位用户提供 1 个日历连接和无限会话。还提供桌面和移动应用程序。
* [Discord](https://discord.com/) — 与公共/私人房间聊天。Markdown 文本、语音、视频和屏幕共享功能。无限用户免费。
* [Fibo](https://fibo.dev) - 一款适用于敏捷团队的免费在线实时 Scrum 扑克工具，可让无限成员估计故事点以加快规划速度。
* [电报](https://telegram.org/) — Telegram 适合所有想要快速、可靠的消息传递和通话的人。业务用户和小型团队可能会喜欢大型群组、用户名、桌面应用程序和强大的文件共享选项。
* [DevToolLab](https://devtoollab.com) — 在线开发人员工具，可免费访问所有基本工具，能够为每个工具自动保存一个条目、标准处理速度和社区支持。
* [Dubble](https://dubble.so/) — 免费的分步指南创建器。截取屏幕截图、记录流程并与您的团队合作。还支持异步屏幕录制。
* [Duckly](https://duckly.com/) — 与您的团队实时交谈和协作。将编程与 IDE、终端共享、语音、视频和屏幕共享配对。小团队免费。
* [Dyte](https://dyte.io) - 对开发人员最友好的实时视频和音频 SDK，具有协作插件以提高生产力和参与度。免费套餐包括每月 10,000 分钟的实时视频/音频使用量。
* [evernote.com](https://evernote.com/) — 用于组织信息的工具。共享您的笔记并与他人一起工作
* [Fibery](https://fibery.io/) — 互联工作空间平台。单个用户免费，最多 2 GB 磁盘空间。
* [flock.com](https://flock.com) — 为您的团队提供更快的沟通方式。免费、无限的消息、频道、用户、应用程序和集成
* [聚会](https://www.gather.town/) \- 一种更好的在线见面方式。Gather 以完全可定制的空间为中心，让您与社区共度时光就像现实生活一样简单。最多 10 个并发用户免费。
* [gokanban.io](https://gokanban.io) - 基于语法，无需注册看板，可快速使用。免费，没有限制。
* [flat.social](https://flat.social) - 用于团队会议和欢乐时光社交的交互式可定制空间。无限次会议，最多可免费 8 个并发用户。
* [GitDalies](https://gitdailies.com) - 团队在 GitHub 上的提交和拉取请求活动的每日报告。包括推送可视化工具、对等识别系统和自定义警报生成器。免费套餐具有无限用户、三个存储库和 3 个警报配置。
* [gitter.im](https://gitter.im/) — Chat，用于 GitHub。无限的公共和私人房间，最多 25 人的团队免费
* [Hackmd.io](https://hackmd.io/) - 用于 Markdown 格式文档/文件的实时协作和编写工具。与 Google Docs 类似，但适用于 Markdown 文件。免费，无限数量的“笔记”，但私人笔记和模板的协作者（受邀者）数量[将受到限制](https://hackmd.io/pricing) 。
* [hangouts.google.com](https://hangouts.google.com/) — 一个地方可以免费进行所有对话，需要一个 Google 帐户
* [HeySpace](https://hey.space) - 具有聊天、日历、时间线和视频通话功能的任务管理工具。最多 5 位用户免费。
* [helplightning.com](https://www.helplightning.com/) — 通过增强现实帮助视频。免费，无需分析、加密、支持
* [ideascale.com](https://ideascale.com/) — 允许客户提交想法和投票，1 个社区中的 25 名成员免费
* [冰屋](https://www.igloosoftware.com/) — 用于共享文档、博客、日历等的内部门户。最多 10 位用户免费。
* [Keybase](https://keybase.io/) — Keybase 是 Slack 的 FOSS 替代品;它可以确保每个人的聊天和文件安全，从家庭到社区再到公司。
* [Google Meet](https://meet.google.com/) — 使用 Google Meet 满足您企业的在线视频会议需求。Meet 提供安全、易于加入的在线会议。
* [/meet for Slack](https://meetslack.com) - 在任何频道、群组或 DM 中使用 /meet 直接从 Slack 启动 Google 会议。免费，没有任何限制。
* [Livecycle](https://www.livecycle.io/) — Livecycle 是一个包容性协作平台，可使跨职能产品团队和开源项目的工作流程顺畅无阻。
* [Lockitbot](https://www.lockitbot.com/) — 在 Slack 中保留和锁定共享资源，如房间、开发环境、服务器等。最多免费 2 个资源
* [标记](https://www.markup.io/) — 标记可让您直接在网站、PDF 和图像之上收集反馈。
* [Proton Pass](https://proton.me/pass) — 密码管理器，内置电子邮件别名、2FA 身份验证器、共享和密钥。可在 Web、浏览器扩展、移动应用程序和桌面上使用。
* [Visual Debug](https://visualdebug.com) - 一种可视化反馈工具，用于更好的客户端与开发沟通
* [meet.jit.si](https://meet.jit.si/) — 免费一键视频对话和屏幕共享
* [Microsoft Teams](https://products.office.com/microsoft-teams/free) — Microsoft Teams 是一个基于聊天的数字中心，它通过单一体验将对话、内容和应用集中在一个位置。最多 500 名用户免费。
* [Miro](https://miro.com/) - 适用于分布式团队的可扩展、安全、跨设备和企业级协作白板。使用免费增值计划。
* [nootiz](https://www.nootiz.com/) - 收集和管理任何网站上视觉反馈的首选工具
* [Notion](https://www.notion.so/) - Notion 是一款笔记和协作应用程序，支持 Markdown，集成了任务、wiki 和数据库。该公司将该应用程序描述为用于记笔记、项目管理和任务管理的一体化工作区。除了跨平台应用程序外，它还可以通过大多数网络浏览器访问。
* [Nuclino](https://www.nuclino.com) - 一个轻量级的协作 wiki，用于存储团队的所有知识、文档和笔记。免费计划具有所有基本功能、最多 50 个项目和 5GB 存储空间。
* [OnlineInterview.io](https://onlineinterview.io/) - 免费的代码面试平台，带有嵌入式视频聊天、绘图板和在线代码编辑器，您可以在其中在浏览器上编译和运行代码。您只需单击一下即可创建远程面试室。
* [Quidlo 时间表](https://www.quidlo.com/timesheets) \- 一个简单的团队时间表和时间跟踪应用程序。免费计划具有最多 10 个用户的时间跟踪和生成报告功能。
* [PageShare.dev](https://www.pageshare.dev) - 将可视化评审功能添加到 GitHub 拉取请求中，无需部署网站。每月最多免费 10 页，总共 100MB 存储空间。
* [Pendulums](https://pendulums.io/) - Pendulums 是一款免费的时间跟踪工具，通过易于使用的界面和有价值的统计数据，帮助您更好地管理时间。
* [Pumble](https://pumble.com) - 免费的团队聊天应用程序。无限的用户和消息历史记录，永久免费。
* [Raindrop.io](https://raindrop.io) - 适用于 macOS、Windows、Android、iOS 和 Web 的私密且安全的书签应用程序。免费无限书签和协作。
* [element.io](https://element.io/) — 基于 Matrix 构建的去中心化开源通信工具。群聊、直接消息传递、加密文件传输、语音和视频聊天，以及与其他服务的轻松集成。
* [Rocket.Chat](https://rocket.chat/) - 具有全渠道功能、矩阵联合、与其他应用程序的桥接、无限消息传递和完整消息传递历史记录的开源通信平台。
* [seafile.com](https://www.seafile.com/) — 私有或云存储、文件共享、同步、讨论。云版只有 1 GB
* [Sema](https://www.semasoftware.com/) - 免费的开发人员组合工具，能够将多个存储库的贡献合并和快照到单个报告中。
* [通过浏览器共享屏幕](https://screensharing.net) \- 免费的屏幕共享工具，直接从浏览器与协作者共享您的屏幕，无需下载或注册。免费。
* [Slab](https://slab.com/) — 面向团队的现代知识管理服务。最多 10 位用户免费。
* [slack.com](https://slack.com/) — 无限用户免费，但有一些功能限制
* [Spectrum](https://spectrum.chat/) - 免费创建公共或私人社区。
* [StatusPile](https://www.statuspile.com/) - 状态页的状态页。您能跟踪上游提供商的状态页面吗？
* [Stickies](https://stickies.app/) - 用于头脑风暴、内容管理和笔记的视觉协作应用程序。最多 3 面墙免费、无限用户和 1 GB 存储空间。
* [堆栈](https://betterstacks.com/) \- 具有集成注释、链接和文件存储的内容工作区，用于导航信息过载。永久免费的个人计划。
* [talky.io](https://talky.io/) — 免费群组视频聊天。匿名。点对点。无需插件、注册或付款
* [Teamhood](https://teamhood.com/) - 免费的项目、任务和问题跟踪软件。支持带有泳道和完整 Scrum 实现的看板。具有集成的时间跟踪功能。对五个用户和三个项目组合免费。
* [Teamplify](https://teamplify.com) - 通过团队分析和智能每日站立会议改进团队发展流程。包括适用于远程优先团队的全功能休假管理。最多 5 名用户的小团体免费。
* [Tefter](https://tefter.io) - 具有强大 Slack 集成的书签应用程序。对开源团队免费。
* [电传打字机](https://teletype.oorja.io/) — 共享终端、语音、代码、白板等。开发人员无需登录即可进行端到端加密协作。
* [TimeCamp](https://www.timecamp.com/) - 无限用户的免费时间跟踪软件。轻松与 Jira、Trello、Asana 等 PM 工具集成。
* [Huly](https://huly.io/) - 多合一项目管理平台（替代 Linear、Jira、Slack、Notion、Motion） - 无限用户，每个工作区 10GB 存储空间，10GB 视频（音频）流量。
* [Teamcamp](https://www.teamcamp.app) - 面向软件开发公司的一体化项目管理应用程序。
* [twist.com](https://twist.com) — 一款异步友好的团队通信应用程序，对话保持井井有条且切中主题。提供免费和无限制计划。为符合条件的团队提供折扣。
* [tldraw.com](https://tldraw.com) — 免费的开源白板和图表工具，具有智能箭头、捕捉、便签和 SVG 导出功能。用于协作编辑的多人游戏模式。还提供免费的官方 VS Code 扩展。
* [BookmarkOS.com](https://bookmarkos.com) - 在可自定义的在线桌面中免费提供一对一书签管理器、选项卡管理器和任务管理器，并具有文件夹协作功能。
* [typetalk.com](https://www.typetalk.com/) — 通过网络或移动设备上的即时消息与您的团队分享和讨论想法
* [拖船](https://tugboat.qa) \- 预览每个拉取请求，自动和按需。对所有人免费，非营利组织免费提供 Nano 层级。
* [whereby.com](https://whereby.com/) — 一键式视频对话，免费（以前称为 appear.in）
* [windmill.dev](https://windmill.dev/) - Windmill 是一个开源开发人员平台，可从最少的 Python 和 Typescript 脚本快速构建生产级多步骤自动化和内部应用程序。作为免费用户，您最多可以创建三个非高级工作区并成为其成员。
* [vadoo.tv](https://vadoo.tv/) — 视频托管和营销变得简单。只需单击一下即可上传视频。记录、管理、共享等。免费套餐每月最多提供 10 个视频、1 GB 存储空间和 10 GB 带宽
* [userforge.com](https://userforge.com/) - 相互关联的在线角色、用户故事和上下文映射。帮助最多 3 个角色和两个协作者保持设计和开发自由同步。
* [wistia.com](https://wistia.com/) — 视频托管，具有观看者分析、高清视频交付和营销工具，可帮助了解您的访问者、25 个视频和 Wistia 品牌播放器
* [wormhol.org](https://www.wormhol.org/) — 简单的文件共享服务。与任意数量的对等方共享高达 5GB 的无限文件。
* [Wormhole](https://wormhole.app/) - 通过端到端加密共享高达 5GB 的文件长达 24 小时。对于大于 5 GB 的文件，它使用点对点传输直接发送您的文件。
* [zoom.us](https://zoom.us/) — 提供安全视频和 Web 会议附加组件。免费计划限制为 40 分钟。
* [Zulip](https://zulip.com/) — 具有独特的类似电子邮件的线程模型的实时聊天。免费计划包括 10,000 条消息的搜索历史记录和高达 5 GB 的文件存储。此外，它还提供了一个自托管的开源版本。
* [robocorp.com](https://robocorp.com) - 用于为自动化运营提供支持的开源堆栈。免费试用云功能并实施简单的自动化。机器人工作 240 分钟/月，10 次助手运行，存储 100 MB。
* [Fleep.io](https://fleep.io/) — Fleep 是 Slack 的替代品。它为小型团队提供免费计划，具有完整的消息历史记录、无限制的 1：1 对话、1 个群组对话和 1 GB 文件存储空间。
* [Chanty.com](https://chanty.com/) — Chanty 是 Slack 的另一种选择。它为小型团队（最多 10 人）提供永久免费计划，包括无限的公共和私人对话、可搜索的历史记录、无限的 1：1 音频通话、无限的语音消息、十个集成以及每个团队 20 GB 的存储空间。
* [ruttl.com](https://ruttl.com/) — 用于收集数字反馈和审查网站、PDF 和图像的最佳一体化反馈工具。
* [Mattermost](https://mattermost.com/) — 技术团队的安全协作。免费计划，包含无限频道、剧本、板、用户、10GB 存储空间等。
* [Webvizio](https://webvizio.com) — 网站反馈工具、网站审查软件和错误报告工具，用于简化直接在实时网站和 Web 应用程序、图像、PDF 和设计文件上执行任务的 Web 开发协作。
* [Pullflow](https://pullflow.com) — Pullflow 提供了一个 AI 增强平台，用于跨 GitHub、Slack 和 VS Code 进行代码审查协作。
* [Webex](https://www.webex.com/) — 免费计划的视频会议，每次会议提供 40 分钟，有 100 名与会者。
* [RingCentral](https://www.ringcentral.com/) — 免费计划的视频会议，每次会议提供 50 分钟，有 100 名参与者。
* [GitBook](https://www.gitbook.com/) — 用于捕获和记录技术知识的平台 — 从产品文档到内部知识库和 API。个人开发人员的免费计划。
* [TransferNow](https://www.transfernow.net/) — 最简单、最快、最安全的传输和共享文件界面。发送照片、视频和其他大文件，无需强制订阅。
* [paste.sh](https://paste.sh/) — 这是一个基于 JavaScript 和 Crypto 的简单粘贴站点。
* [Revolt.chat](https://revolt.chat/) —[Discord](https://discord.com/) 的开源替代品，尊重您的隐私。它还免费拥有 Discord 的大多数专有功能。Revolt 是一款安全快速的多合一应用程序，同时 100% 免费。所有功能都是免费的。与大多数主流聊天应用程序不同，它们还具有（官方和非官方）插件支持。
* [腾讯 RTC](https://trtc.io/) — 腾讯实时通信（TRTC）提供群组音频/视频通话解决方案。第一年免费 10,000 分钟/月。
* [Pastefy](https://pastefy.app/) - 美观而简单的 Pastebin，具有可选的客户端加密、多选项卡粘贴、API、突出显示的编辑器等。
* [SiteDots](https://sitedots.com/) - 直接在您的网站上分享网站项目的反馈，无需仿真、画布或解决方法。功能齐全的免费套餐。

**[⬆️ 返回首页](#目录)**

## CMS 系统

* [acquia.com](https://www.acquia.com/) — 托管 Drupal 网站。面向开发人员的免费套餐。还提供免费的开发工具（例如 Acquia Dev Desktop）。
* [内容丰富](https://www.contentful.com/) — 无头 CMS。云中的内容管理和交付 API。附带一个免费的社区空间，其中包括 5 个用户、25K 记录、48 种内容类型、2 个区域设置。
* [Cosmic](https://www.cosmicjs.com/) — 无头 CMS 和 API 工具包。面向开发人员的免费个人计划。
* [Crystallize](https://crystallize.com) — 支持电子商务的无头 PIM。内置 GraphQL API。免费版本包括无限用户、1000 个目录项、5 GB/月带宽和 25k/月 API 调用。
* [DatoCMS](https://www.datocms.com/) - 为小型项目提供免费套餐。DatoCMS 是一个基于 GraphQL 的 CMS。在较低级别，您每月有 100k 的通话。
* [Directus](https://directus.io) — 无头 CMS。一个完全免费的开源平台，用于在本地或云中管理资产和数据库内容。没有限制或付费专区。
* [FrontAid](https://frontaid.io/) — 将 JSON 内容直接存储在 Git 存储库中的无头 CMS。没有限制。
* [kontent.ai](https://www.kontent.ai) - 一个内容即服务平台，可为您提供所有无头 CMS 优势，同时为营销人员提供支持。开发人员计划为两个用户提供无限的项目，每个项目有两个环境、500 个内容项、两种具有交付和管理 API 的语言以及自定义元素支持。您可以使用更详细的计划来满足您的需求。
* [棱镜](https://www.prismic.io/) — 无头 CMS。具有完全托管和可扩展 API 的内容管理界面。社区计划为一个用户提供无限的 API 调用、文档、自定义类型、资产和区域设置。下一个项目所需的一切。更大的免费计划可用于开放内容/开源项目。
* [Sanity.io](https://www.sanity.io/) - 具有开源编辑环境和实时托管数据存储的结构化内容平台。无限项目。每个项目免费包含无限的管理员用户、三个非管理员用户、两个数据集、500K API CDN 请求、10GB 带宽和 5GB 资产。
* [sensenet](https://sensenet.com) - API 优先的无头 CMS，为各种规模的企业提供企业级解决方案。开发人员计划提供三个用户、500 个内容项、三个内置角色、25+5 种内容类型、完全可访问的 REST API、文档预览生成和 Office Online 编辑。
* [TinaCMS](https://tina.io/) — 替换 Forestry.io。支持 Markdown、MDX 和 JSON 的开源 Git 支持的无头 CMS。基本优惠是免费的，有两个用户可用。
* [GatsbyjsCMS](https://www.gatsbyjs.com/) - Gatsby 是一个快速灵活的框架，它使使用任何 CMS、API 或数据库构建网站变得有趣。构建和部署无头网站，以吸引更多流量、更好地转化并赚取更多收入！
* [Hygraph](https://hygraph.com/) - 为小型项目提供免费套餐。GraphQL 第一个 API。从传统解决方案转向 GraphQL 原生无头 CMS - 并首先提供全渠道内容 API。
* [Squidex](https://squidex.io/) - 为小型项目提供免费套餐。API / GraphQL 优先。开源并基于事件溯源（自动处理每个更改）。
* [InstaWP](https://instawp.com/) - 在几秒钟内启动一个 WordPress 网站。具有 5 个活动站点、500 MB 空间、48 小时站点到期的免费套餐。
* [Storyblok](https://www.storyblok.com) - 适用于开发人员和营销人员的无头 CMS，可与所有现代框架配合使用。社区（免费）层提供管理 API、可视化编辑器、十个来源、自定义字段类型、国际化（无限语言/区域设置）、资产管理器（最多 2500 个资产）、图像优化服务、搜索查询、Webhook + 250GB 流量/月包括。
* [WPJack](https://wpjack.com) - 在不到 5 分钟的时间内在任何云上设置 WordPress！免费套餐包括 1 台服务器、2 个站点、免费 SSL 证书和无限的 cron 作业。没有时间限制或过期——您的网站，您的方式。

**[⬆️ 返回首页](#目录)**

## 代码生成

* [Appinvento](https://appinvento.io/) — AppInvento 是一个免费的无代码应用程序构建器。在自动生成的后端代码中，用户可以完全访问源代码以及无限的 API 和路由，从而实现广泛的集成。免费计划包括三个项目、五个表格和一个 Google 附加组件。
* [Cody AI](https://sourcegraph.com/cody) - Cody 是一款编码 AI 助手，它使用 AI 和对代码库的深刻理解来帮助您更快地编写和理解代码。Cody 为开发人员提供了 LLM 的选择（包括本地推理），支持各种 IDE，支持所有流行的编程语言，并有免费计划。免费计划每月为开发人员提供 20 条聊天消息（使用 Claude 3 Sonnet 作为 LLM）和 500 个自动完成（使用 Starcoder 16b）。
* [DhiWise](https://www.dhiwise.com/) — 利用 DhiWise 的创新代码生成技术，将 Figma 设计无缝转换为动态的 Flutter 和 React 应用程序，优化您的工作流程并帮助您比以往更快地打造卓越的移动和 Web 体验。
* [Metalama](https://www.postsharp.net/metalama) - 仅适用于 C#。Metalama 在编译过程中动态生成代码样板，以便您的源代码保持干净。它对开源项目是免费的，其商业友好的免费套餐包括三个方面。
* [Supermaven](https://www.supermaven.com/) — Supermaven 是一款适用于 VSCode、JetBrains 和 Neovim 的快速 AI 代码补全插件。免费层提供无限制的内联完成。
* [tabnine.com](https://www.tabnine.com/) — Tabnine 通过提供从世界上所有代码中学到的见解，帮助开发人员更快地创建更好的软件。插件可用。
* [v0.dev](https://v0.dev/) — v0 使用 AI 模型根据简单的文本提示生成代码。它基于 shadcn/ui 和 Tailwind CSS 生成复制和粘贴友好的 React 代码，人们可以在他们的项目中使用。每一代至少需要 30 个学分。您从 1200 个积分开始，每月获得 200 个免费积分。

**[⬆️ 返回首页](#目录)**

## 代码质量

* [beanstalkapp.com](https://beanstalkapp.com/) — 用于编写、审查和部署代码的完整工作流程）、一个用户的免费帐户以及一个具有 100 MB 存储空间的存储库
* [browserling.com](https://www.browserling.com/) — 实时交互式跨浏览器测试，在 Vista 下以 1024 x 768 分辨率使用 MS IE 9 仅免费 3 分钟会话
* [codacy.com](https://www.codacy.com/) — 针对 PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 的自动代码审查，免费用于无限的公共和私有存储库
* [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - 用于 DevOps 的自动化基础设施即代码审查工具与 GitHub、Bitbucket 和 GitLab（甚至是自托管）集成。除了标准语言外，它还分析 Ansible、Terraform、CloudFormation、Kubernetes 等。（开源免费）
* [CodeBeat](https://codebeat.co) — 支持多种语言的自动代码审查平台。通过 Slack 和电子邮件集成永久免费用于公共存储库。
* [codeclimate.com](https://codeclimate.com/) — 自动代码审查，开源免费，组织拥有的私有存储库无限制（最多 4 个协作者）。学生和机构也免费。
* [codecov.io](https://codecov.io/) — 代码覆盖率工具 （SaaS），开源免费和一个免费的私有存储库
* [CodeFactor](https://www.codefactor.io) — Git 的自动代码审查。免费版本包括无限用户、公共存储库和一个私有存储库。
* [coderabbit.ai](https://coderabbit.ai) — 与 GitHub/GitLab 集成的 AI 驱动的代码审查工具。免费套餐包括 200 个文件/小时、每小时 3 条评论和 50 个对话/小时。开源项目永久免费。
* [codescene.io](https://codescene.io/) - CodeScene 根据开发人员处理代码的方式确定技术债务的优先级，并可视化团队耦合和系统掌握等组织因素。开源免费。
* [CodSpeed](https://codspeed.io) - 在您的 CI 管道中自动跟踪性能。在部署之前捕获性能回归，这要归功于精确且一致的指标。开源项目永久免费。
* [coveralls.io](https://coveralls.io/) — 显示测试覆盖率报告，开源免费
* [Dareboost](https://dareboost.com) - 每月 5 份关于 Web 性能、可访问性和安全性的免费分析报告
* [deepcode.ai](https://www.deepcode.ai) — DeepCode 基于 AI 发现错误、安全漏洞、性能和 API 问题。DeepCode 的分析速度使我们能够实时分析您的代码，并在您点击 IDE 中的保存按钮时提供结果。支持的语言包括 Java、C/C++、JavaScript、Python 和 TypeScript。与 GitHub、BitBucket 和 GitLab 集成。开源和私有存储库以及最多 30 名开发人员免费。
* [deepscan.io](https://deepscan.io) — 用于自动查找 JavaScript 代码中的运行时错误的高级静态分析，开源免费
* [DeepSource](https://deepsource.io/) - DeepSource 持续分析源代码更改，查找并修复按安全性、性能、反模式、错误风险、文档和样式分类的问题。与 GitHub、GitLab 和 Bitbucket 的本机集成。
* [DiffText](https://difftext.com) - 立即找到两个代码块之间的差异。完全免费使用。
* [eversql.com](https://www.eversql.com/) — EverSQL - 用于数据库优化的 #1 平台。自动获得对数据库和 SQL 查询的重要见解。
* [gerrithub.io](https://review.gerrithub.io/) — 免费为 GitHub 存储库进行 Gerrit 代码审查
* [gocover.io](https://gocover.io/) — 任何 [Go](https://golang.org/) 包的代码覆盖率
* [goreportcard.com](https://goreportcard.com/) — Go 项目的代码质量，开源免费
* [gtmetrix.com](https://gtmetrix.com/) — 优化网站的报告和全面建议
* [holistic.dev](https://holistic.dev/) - 用于 Postgresql 优化的 #1 静态代码分析器。性能、安全性和架构数据库问题自动检测服务
* [houndci.com](https://houndci.com/) — GitHub 上关于代码质量的评论提交，开源免费
* [Moderne.io](https://app.moderne.io) — 自动源代码重构。Moderne 提供框架迁移、带修复的代码分析以及无与伦比的大规模代码转换，因此开发人员可以花时间构建新事物，而不是维护旧事物。开源免费。
* [reviewable.io](https://reviewable.io/) — GitHub 存储库的代码审查，公共或个人存储库免费。
* [parsers.dev](https://parsers.dev/) - 抽象语法树解析器和中间表示编译器即服务
* [scan.coverity.com](https://scan.coverity.com/) — Java、C/C++、C# 和 JavaScript 的静态代码分析，开源免费
* [scrutinizer-ci.com](https://scrutinizer-ci.com/) — 连续检测平台，开源免费
* [semanticdiff.com](https://app.semanticdiff.com/) — GitHub 拉取请求和提交的编程语言感知差异，公共存储库免费
* [shields.io](https://shields.io) — 开源项目的优质元数据徽章
* [sonarcloud.io](https://sonarcloud.io) — Java、JavaScript、C/C++、C#、VB.NET、PHP、Objective-C、Swift、Python、Groovy 甚至更多语言的自动源代码分析，开源免费
* [SourceLevel](https://sourcelevel.io/) — 自动代码审查和团队分析。开源和最多 5 名协作者的组织免费。
* [webceo.com](https://www.webceo.com/) — SEO 工具，但也提供代码验证和不同类型的设备
* [zoompf.com](https://zoompf.com/) — 修复网站的性能，详细分析

**[⬆️ 返回首页](#目录)**

## 代码搜索和浏览

* [libraries.io](https://libraries.io/) — 32 个不同包管理器的搜索和依赖更新通知，开源免费
* [Namae](https://namae.dev/) - 搜索各种网站，如 GitHub、Gitlab、Heroku、Netlify 等，以查找您的项目名称的可用性。
* [searchcode.com](https://searchcode.com/) — 全面的基于文本的代码搜索，开源免费
* [tickgit.com](https://www.tickgit.com/) — 显示 `TODO` 注释（和其他标记）以识别值得返回改进的代码区域。
* [CodeKeep](https://codekeep.io) - 用于代码片段的 Google Keep。组织、发现和共享代码片段，具有强大的代码截图工具、预设模板和链接功能。

**[⬆️ 返回首页](#目录)**

## CI 和 CD

* [AccessLint](https://github.com/marketplace/accesslint) — AccessLint 将自动化的 Web 可访问性测试引入您的开发工作流程。它免费用于开源和教育目的。
* [appcircle.io](https://appcircle.io) — 一个企业级移动 DevOps 平台，可自动构建、测试和发布移动应用程序存储，以实现更快、更高效的发布周期。每次构建最长构建时间 30 分钟免费，每月 20 次构建和 1 次并发构建。
* [appveyor.com](https://www.appveyor.com/) — 适用于 Windows 的 CD 服务，开源免费
* [LocalOps](https://localops.co/) - 在 30 分钟内在 AWS/GCP/Azure 上部署您的应用。在任何云上设置标准化应用环境，这些环境具有内置的持续部署自动化和高级可观测性。免费计划允许 1 个用户和 1 个应用程序环境。
* [Argonaut](https://argonaut.dev/) - 在几分钟内在您的云上部署应用程序和基础设施。支持在 Kubernetes 和 Lambda 环境中部署自定义和第三方应用程序。免费套餐允许 5 个域和 2 个用户使用无限的应用程序和部署。
* [bitrise.io](https://www.bitrise.io/) — 用于移动应用程序（本机或混合）的 CI/CD。每月 200 次免费构建，构建时间 10 分钟，还有两名团队成员。OSS 项目获得 45 分钟的构建时间、+1 并发和无限的团队规模。
* [buddy.works](https://buddy.works/) — 一个 CI/CD，有 5 个免费项目和 1 个并发运行（120 次执行/月）
* [搭建风筝](https://buildkite.com) CI Pipelines 免费供 3 位用户和 5k 作业分钟/月使用。Test Analytics 免费开发人员层包括每月 100k 次测试执行，开源项目包含更多免费内容。
* [bytebase.com](https://www.bytebase.com/) — 数据库 CI/CD 和 DevOps。免费 20 个以下用户和 10 个数据库实例
* [CircleCI](https://circleci.com/) — 全面的免费计划，包含适用于 GitHub、GitLab 和 BitBucket 存储库的托管 CI/CD 服务中的所有功能。多个资源类、Docker、Windows、Mac OS、ARM 执行器、本地运行器、测试拆分、Docker 层缓存和其他高级 CI/CD 功能。免费提供长达 6000 分钟/月的执行时间、无限的协作者、私有项目中的 30 个并行作业以及开源项目中高达 80,000 分钟的免费构建分钟。
* [cirrus-ci.org](https://cirrus-ci.org) - 公共 GitHub 存储库免费
* [cirun.io](https://cirun.io) - 公共 GitHub 存储库免费
* [codefresh.io](https://codefresh.io) — 终身免费计划：1 个构建、一个环境、共享服务器、无限的公共存储库
* [codemagic.io](https://codemagic.io/) - 每月免费 500 分钟构建时间
* [codeship.com](https://codeship.com/) — 每月 100 个私有构建，五个私有项目，开源无限制
* [deploybot.com](https://www.deploybot.com/) — 1 个存储库，具有 10 个部署，开源免费
* [deployhq.com](https://www.deployhq.com/) — 1 个项目，每日部署 10 次（30 分钟/月）
* [无人机](https://cloud.drone.io/) \- Drone Cloud 使开发人员能够跨多个架构运行持续交付管道，包括 x86 和 Arm（32 位和 64 位），所有这些都在一个地方
* [LayerCI](https://layerci.com) — 用于全栈项目的 CI。一个具有 5GB 内存和 3 个 CPU 的全栈预览环境。
* [semaphoreci.com](https://semaphoreci.com/) — 开源免费，每月 100 个私有版本
* [Squash Labs](https://www.squash.io/) — 为每个分支创建一个 VM，并使应用可从唯一 URL、无限的公共和专用存储库、最大 2 GB 的 VM 大小提供。
* [styleci.io](https://styleci.io/) — 仅限公共 GitHub 存储库
* [Mergify](https://mergify.io) — GitHub 的工作流自动化和合并队列 — 公共 GitHub 存储库免费
* [Make](https://www.make.com/en) — 工作流自动化工具允许您使用 UI 连接应用程序并自动执行工作流。它支持许多应用程序和最流行的 API。公共 GitHub 存储库免费，免费层级为 100 Mb、1000 次作和 15 分钟的最小间隔。
* [Shipfox](https://shipfox.io/) - 运行 GitHub 作的速度提高 2 倍，每月免费运行 3.000 分钟。
* [Spacelift](https://spacelift.io/) - 基础设施即代码的管理平台。免费计划功能：IaC 协作、Terraform 模块注册表、ChatOps 集成、使用 Open Policy Agent 的持续资源合规性、使用 SAML 2.0 的 SSO 以及对公共工作人员池的访问：最多 200 分钟/月
* [microtica.com](https://microtica.com/) - 具有现成基础设施组件的启动环境，在 AWS 上免费部署应用程序，并支持您的生产工作负载。免费套餐包括 1 个环境（在您的 AWS 账户上）、2 个 Kubernetes 服务、每月 100 分钟的构建分钟数和 20 个月的每月部署。
* [Nx Cloud](https://nx.dev/ci) - Nx Cloud 通过远程缓存、跨机器分配任务甚至自动拆分 e2e 测试运行等功能，加快了 CI 上的 monorepos。它附带一个免费计划，最多可容纳 30 名贡献者，其中包括慷慨的 150k 积分。
* [blacksmith](https://www.blacksmith.sh/) - GitHub Actions 的托管性能运行器，每月提供 3,000 分钟的免费分钟，无需信用卡。
* [Terramate](https://terramate.io/) - Terramate 是基础设施即代码 （IaC） 工具（如 Terraform、OpenTofu 和 Terragrunt）的编排和管理平台。最多免费 2 个用户，包括所有功能。
* [Terrateam](https://terrateam.io) - GitOps 优先的 Terraform 自动化，具有拉取请求驱动的工作流、通过自托管运行器进行项目隔离以及用于有序作的分层运行。最多 3 位用户免费。

**[⬆️ 返回首页](#目录)**

## 测试

* [Applitools.com](https://applitools.com/) — 针对 Web、本机移动和桌面应用程序的智能视觉验证。与几乎所有自动化解决方案（如 Selenium 和 Karma）和远程运行器（Sauce Labs、Browser Stack）集成。开源免费。单个用户的免费套餐，每周检查点有限。
* [Appetize](https://appetize.io) — 直接在浏览器中在此基于云的 Android 手机/平板电脑模拟器和 iPhone/iPad 模拟器上测试您的 Android 和 iOS 应用程序。免费套餐包括两个并发会话，每月使用 30 分钟。应用程序大小没有限制。
* [Apptim](https://apptim.com) — 一种移动测试工具，使没有性能工程技能的人能够评估应用程序的性能和用户体验 （UX）。使用您自己的设备的桌面版本是 100% 免费的，可在 iOS 和 Android 上进行无限制的测试。
* [Argos](https://argos-ci.com) - 面向开发人员的开源可视化测试。无限项目，每月有 5,000 张屏幕截图。开源项目免费。
* [Bencher](https://bencher.dev/) - 一个连续的基准测试工具套件，用于捕获 CI 性能回归。所有公共项目免费。
* [browserstack.com](https://www.browserstack.com/) — 手动和自动浏览器测试， [开源免费](https://www.browserstack.com/open-source?ref=pricing)
* [BugBug](https://bugbug.io/) - 用于 Web 应用程序的轻量级测试自动化工具。它易于学习，不需要编码。您可以在自己的计算机上免费运行无限的测试。您还可以获得云监控和 CI/CD 集成，但需支付额外的月费。
* [Checkly](https://checklyhq.com) - 用于现代 DevOps 的代码优先综合监视。以传统提供商的一小部分价格监控您的 API 和应用程序。由监控即代码工作流程和剧作家提供支持。为开发人员提供慷慨的免费套餐。
* [checkbot.io](https://www.checkbot.io/) — 浏览器扩展程序，测试您的网站是否遵循 50+ 搜索引擎优化、速度和安全最佳实践。小型网站的免费套餐。
* [CORS-Tester](https://cors-error.dev/cors-tester/) - 开发人员和 API 测试人员的免费工具，用于检查给定域的 API 是否启用了 CORS 并识别差距。获取可作的见解。
* [cypress.io](https://www.cypress.io/) - 对在浏览器中运行的任何内容进行快速、简单和可靠的测试。Cypress Test Runner 始终免费且开源，没有任何限制和限制。Cypress Dashboard 对开源项目免费，最多可容纳 5 个用户。
* [Cypress Recorder by Preflight](https://cypress.preflight.com/) - 在浏览器上创建人工智能驱动的赛普拉斯测试/POM 模型。它是开源的，除了人工智能部分。它免费用于五个月的测试创建，包括自我修复脚本、电子邮件和视觉测试。
* [everystep-automation.com](https://www.everystep-automation.com/) — 记录和重播在 Web 浏览器中执行的所有步骤并创建脚本，免费且选项更少
* [Gremlin — Gremlin](https://www.gremlin.com/gremlin-free-software) 的混沌工程工具允许您安全可靠地将故障注入系统，以便在弱点导致面向客户的问题之前发现它们。Gremlin Free 提供对多达 5 台主机或容器的关机和 CPU 攻击的访问。
* [gridlastic.com](https://www.gridlastic.com/) — Selenium Grid 测试，免费计划最多可同时运行 4 个 Selenium 节点/10 个网格启动/4,000 个测试分钟/月
* [katalon.com](https://katalon.com) - 提供一个测试平台，可以帮助不同测试成熟度级别的各种规模的团队，包括 Katalon Studio、TestOps（+ 可视化测试免费）、TestCloud 和 Katalon Recorder。
* [Keploy](https://keploy.io/) - Keploy 是一个面向开发人员的功能测试工具包。记录 API 调用会生成 API （KTest） 和模拟或存根 （KMocks） 的 E2E 测试。它对开源项目是免费的。
* [knapsackpro.com](https://knapsackpro.com) - 通过在任何 CI 提供程序上的最佳测试套件并行化来加快测试速度。拆分 Ruby，JavaScript 在并行 CI 节点上进行测试以节省时间。长达 10 分钟测试文件的免费计划和开源项目的免费无限计划。
* [lambdatest.com](https://www.lambdatest.com/) — 对 selenium 和 cypress 进行手动、可视化、屏幕截图和自动浏览器测试， [开源免费](https://www.lambdatest.com/open-source-cross-browser-testing-tool)
* [loadmill.com](https://www.loadmill.com/) - 通过分析网络流量自动创建 API 和负载测试。每月免费模拟多达 50 个并发用户，最长可达 60 分钟。
* [lost-pixel.com](https://lost-pixel.com) - 针对您的 Storybook、Ladle、Histoire 故事和 Web 应用程序进行整体视觉回归测试。无限的团队成员，开源完全免费，每月 7,000 个快照。
* [octomind.dev](https://www.octomind.dev/) - 通过 AI 辅助测试用例生成自动生成、运行和维护 Playwright UI 测试
* [percy.io](https://percy.io) - 将视觉测试添加到任何 Web 应用、静态网站、样式指南或组件库。无限的团队成员、演示应用程序和无限的项目，每月 5,000 个快照。
* [qase.io](https://qase.io) - 开发和 QA 团队的测试管理系统。管理测试用例、编写测试运行、执行测试、跟踪缺陷并衡量影响。免费套餐包括所有核心功能，500MB 可用于附件和最多 3 个用户。
* [重复](https://repeato.app/)基于计算机视觉和人工智能构建的无代码移动应用程序测试自动化工具。适用于本机应用程序、Flutter、React-native、Web、ionic 和更多应用程序框架。免费计划仅限于 iOS 的 10 次测试和 Android 的 10 次测试，但包括付费计划的大部分功能，包括无限制的测试运行。
* [请求](https://requestly.com/)用于拦截、重定向和模拟 HTTP 请求的开源 Chrome 扩展程序。具有[调试器](https://requestly.com/products/web-debugger/) 、 [模拟服务器](https://requestly.com/products/mock-server/) 、[API 客户端](https://requestly.com/products/api-client/)和[会话记录](https://requestly.com/products/session-book/)功能。重定向 URL、修改 HTTP 标头、模拟 API、注入自定义 JS、修改 GraphQL 请求、生成模拟 API 端点、使用网络和控制台日志记录会话。在免费套餐中创建最多 10 条规则。开源免费。
* [seotest.me](https://seotest.me/) — 免费的页面 SEO 网站测试器。每天 10 次免费网站抓取。有用的 SEO 学习资源和建议，了解如何改进任何网站的页面 SEO 结果，无论技术如何。
* [snippets.uilicious.com](https://snippets.uilicious.com) - 它类似于 CodePen，但用于跨浏览器测试。UI-licious 允许您编写用户故事等测试，并提供一个免费平台 - UI-licious Snippets - 允许您在 Chrome 上运行无限次测试，每次测试运行最多 3 分钟无需注册。发现错误？您可以将唯一的 URL 复制到测试中，以向开发人员展示如何重现错误。
* [SSR（服务器端渲染）检查器](https://www.crawlably.com/ssr-checker/) \- 通过直观地比较页面的服务器渲染版本与常规版本，检查任何 URL（服务器端渲染）的 SSR（服务器端渲染）。
* [TestCollab](https://testcollab.com) - 一款用户友好的测试管理软件，其免费计划包括 Jira 集成、无限项目、使用 CSV/XLSx 导入测试用例、时间跟踪和 1 GB 文件存储。
* [testingbot.com](https://testingbot.com/) — Selenium 浏览器和设备测试， [开源免费](https://testingbot.com/open-source)
* [Testspace.com](https://testspace.com/) - 用于发布自动测试结果的仪表板和用于使用 GitHub 将手动测试作为代码实现的框架。该服务[对开源免费](https://github.com/marketplace/testspace-com) ，每月有 450 个结果。
* [tesults.com](https://www.tesults.com) — 测试结果报告和测试用例管理。与流行的测试框架集成。开源软件开发人员、个人、教育工作者和初学者小团队可以申请基本免费项目之外的折扣和免费产品。
* [UseWebhook.com](https://usewebhook.com) - 从浏览器捕获和检查 Webhook。转发到 localhost，或从历史记录中重播。免费使用。
* [Vaadin](https://vaadin.com) — 使用 Java 或 TypeScript 构建可扩展的 UI，并使用集成的工具、组件和设计系统来更快地迭代、更好地设计并简化开发过程。无限项目，五年免费维护。
* [websitepulse.com](https://www.websitepulse.com/tools/) — 各种免费的网络和服务器工具。
* [webhook-test.com](https://webhook-test.com) - 在集成期间使用唯一 URL 调试和检查 Webhook 和 HTTP 请求。完全免费，您可以创建无限的 URL 并接收推荐。
* [webhook.site](https://webhook.site) - 使用自定义 URL 验证 Webhook、出站 HTTP 请求或电子邮件。临时 URL 和电子邮件地址始终免费。
* [webhookbeam.com](https://webhookbeam.com) - 设置 Webhook 并通过推送通知和电子邮件对其进行监控。

**[⬆️ 返回首页](#目录)**

## 安全性和 PKI

* [aikido.dev](https://www.aikido.dev) — 涵盖 SCA、SAST、CSPM、DAST、机密、IaC、恶意软件、容器扫描、EOL 的一体化应用安全平台,...免费计划包括两个用户，扫描 10 个存储库、1 个云、2 个容器和 1 个域。
* [alienvault.com](https://www.alienvault.com/open-threat-exchange/reputation-monitor) — 发现网络中受损的系统
* [Altcha.org](https://altcha.org/anti-spam) - 由自然语言处理和机器学习提供支持的网站和 API 的垃圾邮件过滤器。免费计划包括每个域每天 200 个请求。
* [atomist.com](https://atomist.com/) — 一种更快、更方便的方式来自动化各种开发任务。现在处于测试阶段。
* [cloudsploit.com](https://cloudsploit.com/) — Amazon Web Services （AWS） 安全与合规性审计和监控
* [公有云威胁情报](https://cloudintel.himanshuanand.com/) — 针对公有云基础设施的高置信度入侵指标 （IOC），一部分可在 github （[https://github.com/unknownhad/AWSAttacks）](https://github.com/unknownhad/AWSAttacks) 上找到。完整列表可通过 API 获得
* [CodeNotary.io](https://www.codenotary.io/) — 开源平台，具有不可磨灭的证据，可对代码、文件、目录或容器进行公证
* [crypteron.com](https://www.crypteron.com/) — 云优先、开发人员友好的安全平台可防止 .NET 和 Java 应用程序中的数据泄露
* [CyberChef](https://gchq.github.io/CyberChef/) — 一个简单、直观的 Web 应用程序，用于分析和解码/编码数据，而无需处理复杂的工具或编程语言。就像密码学和加密的瑞士军刀。所有功能均可免费使用，没有限制。如果您想自托管，请开源。
* [DAS](https://signup.styra.com/) — Styra DAS 免费、全生命周期策略管理，用于创建、部署和管理开放策略代理 （OPA） 授权
* [Datree](https://www.datree.io/) — 开源 CLI 工具，通过确保清单和 Helm 图表遵循最佳实践以及组织的策略来防止 Kubernetes 配置错误
* [依赖于](https://dependabot.com/) Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git 子模块和 GitHub Actions 的自动依赖项更新。
* [DJ 检查](https://djcheckup.com) — 使用这个免费的自动检查工具扫描您的 Django 网站是否存在安全漏洞。从 Pony Checkup 网站分叉而来。
* [多普勒](https://doppler.com/) — 用于应用程序密钥和配置的通用密钥管理器，支持同步到各种云提供商。五个用户免费，具有基本的访问控制。
* [Dotenv](https://dotenv.org/) — 快速安全地同步您的 .env 文件。停止通过 Slack 和电子邮件等不安全的渠道共享您的 .env 文件，并且再也不会丢失重要的 .env 文件。最多 3 名队友免费。
* [GitGuardian](https://www.gitguardian.com) — 通过自动机密检测和修复，将机密排除在源代码之外。扫描您的 git 存储库以查找 350+ 类型的机密和敏感文件 – 对 25 名或以下开发人员的个人和团队免费。
* [我被骗了吗？](https://haveibeenpwned.com)— 用于获取有关违规信息的 REST API。
* [hostedscan.com](https://hostedscan.com) — 用于 Web 应用程序、服务器和网络的在线漏洞扫描程序。每月十次免费扫描。
* [Infisical](https://infisical.com/) — 开源平台，可让您管理整个团队和基础设施中的开发人员机密：从本地开发到暂存/生产第三方服务的任何地方。最多 5 名开发人员免费。
* [Internet.nl](https://internet.nl) — 测试 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE 等现代互联网标准
* [keychest.net](https://keychest.net) - 使用集成的 CT 数据库进行 SSL 到期管理和证书购买
* [letsencrypt.org](https://letsencrypt.org/) — 免费的 SSL 证书颁发机构，具有所有主要浏览器信任的证书
* [meterian.io](https://www.meterian.io/) - 监控 Java、Javascript、.NET、Scala、Ruby 和 NodeJS 项目是否存在依赖项中的安全漏洞。一个私人项目免费，开源项目无限。
* [Mozilla Observatory](https://observatory.mozilla.org/) — 查找并修复您网站中的安全漏洞。
* [opswat.com](https://www.opswat.com/) — 计算机、设备、应用程序、配置的安全监控，免费 25 个用户和 30 天历史记录用户。
* [openapi.security](https://openapi.security/) - 快速检查任何基于 OpenAPI / Swagger 的 API 的安全性的免费工具。您无需注册。
* [pixee.ai](https://pixee.ai) - Automated Product Security Engineer 作为免费的 GitHub 机器人，可将 PR 提交到您的 Java 代码库以自动解决漏洞。其他语言即将推出！
* [pyup.io](https://pyup.io) — 监控 Python 依赖项是否存在安全漏洞并自动更新它们。一个私人项目免费，开源项目无限。
* [qualys.com](https://www.qualys.com/community-edition) — 查找 Web 应用程序漏洞，审计 OWASP 风险
* [report-uri.io](https://report-uri.io/) — CSP 和 HPKP 违规报告
* [seclookup.com](https://www.seclookup.com/) - Seclookup API 可以丰富 SIEM 中的域威胁指标，提供有关域名的全面信息，并改进威胁检测和响应。在这里[免费获取](https://account.seclookup.com/) 50K 查找。
* [snyk.io](https://snyk.io) — 可以查找并修复开源依赖项中的已知安全漏洞。对开源项目进行无限制的测试和修复。您的私人项目每月仅限 200 次测试。
* [ssllabs.com](https://www.ssllabs.com/ssltest/) — 对任何 SSL Web 服务器的配置进行深入分析
* [SOOS](https://soos.io) - 免费、无限制的开源项目 SCA 扫描。在发布前检测并修复安全威胁。使用简单有效的解决方案保护您的项目。
* [堆栈鹰](https://www.stackhawk.com/)在整个管道中自动执行应用程序扫描，以便在安全漏洞进入生产环境之前发现并修复它们。单个应用程序的无限扫描和环境。
* [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免费网站安全检查和恶意软件扫描程序
* [Protectumus](https://protectumus.com) - 免费的网站安全检查、网站防病毒和 PHP 服务器防火墙 （WAF）。免费层中注册用户的电子邮件通知。
* [TestTLS.com](https://testtls.com) - 测试 SSL/TLS 服务的安全服务器配置、证书、链等。不仅限于 HTTPS。
* [threatconnect.com](https://threatconnect.com) — 威胁情报：它专为开始了解网络威胁情报的个人研究人员、分析师和组织而设计。最多免费 3 个用户
* [tinfoilsecurity.com](https://www.tinfoilsecurity.com/) — 自动漏洞扫描。免费计划允许每周进行 XSS 扫描
* [Ubiq Security](https://ubiqsecurity.com/) — 使用三行代码和自动密钥管理对数据进行加密和解密。一个应用程序免费，每月最多 1,000,000 次加密。
* [Virgil Security](https://virgilsecurity.com/) — 用于在数字解决方案中实施端到端加密、数据库保护、物联网安全等的工具和服务。对于最多 250 个用户的应用程序免费。
* [Vulert](https://vulert.com) - Vulert 持续监控您的开源依赖项是否存在新漏洞，并建议修复，而无需安装或访问您的代码库。开源项目免费。
* [Escape GraphQL Quickscan](https://escape.tech/) - 对 GraphQL 端点进行一键式安全扫描。免费，无需登录。
* [HasMySecretLeaked](https://gitguardian.com/hasmysecretleaked) - 免费搜索公共 GitHub 存储库、要点、问题和评论中的 2000 万个暴露的机密
* [Project Gatekeeper](https://gatekeeper.binarybiology.top/) - 一个多合一的 SSL 工具包，提供各种功能，如私钥和 CSR 生成器、SSL 证书解码器、证书匹配器和订购 SSL 证书。我们为用户提供使用 CNAME 记录而不是 TXT 记录从 Let's Encrypt、Google Trust 和 BuyPass 生成免费 SSL 证书。

**[⬆️ 返回首页](#目录)**

## 身份验证、授权和用户管理

* [Aserto](https://www.aserto.com) - 应用程序和 API 的细粒度授权即服务。释放多达 1000 个 MAU 和 100 个授权者实例。
* [asgardeo.io](https://wso2.com/asgardeo) - 无缝集成 SSO、MFA、无密码身份验证等。包括用于前端和后端应用的 SDK。免费提供多达 1000 个 MAU 和 5 个身份提供商。
* [Auth0](https://auth0.com/) — 托管 SSO。免费计划包括 25,000 个 MAU、无限的社交连接、自定义域等。
* [Authgear](https://www.authgear.com) - 在几分钟内将无密码、OTP、2FA、SSO 引入您的应用程序。包括所有前端。释放高达 5000 个 MAU。
* [Authress](https://authress.io/) — 身份验证登录和访问控制，任何项目的无限身份提供者。Facebook、谷歌、Twitter 等。前 1000 次 API 调用是免费的。
* [Authy](https://authy.com) - 在多个设备上进行双因素身份验证 （2FA），并带有备份。Google Authenticator 的直接替代品。最多 100 次成功身份验证免费。
* [Cerbos Hub](https://www.cerbos.dev/product-cerbos-hub) - 用于创作、测试和部署访问策略的完整授权管理系统。细粒度授权和访问控制，每月最多免费 100 个活跃主体。
* [文员](https://clerk.com) — 用户管理、身份验证、2FA/MFA、用于登录、注册、用户配置文件等的预构建 UI 组件。每月最多免费 10,000 名活跃用户。
* [Cloud-IAM](https://www.cloud-iam.com/) — Keycloak 身份和访问管理即服务。最多免费 100 个用户和一个领域。
* [Corbado](https://www.corbado.com/) — 将密钥优先身份验证添加到新的或现有的应用程序。无限 MAU 免费。
* [Descope](https://www.descope.com/) — 高度可定制的 AuthN 流，具有无代码和 API/SDK 方法，每月免费 7,500 个活跃用户，50 个租户（最多 5 个 SAML/SSO 租户）。
* [duo.com](https://duo.com/) — 网站或应用程序的双因素身份验证 （2FA）。十个用户免费，所有身份验证方法，无限制，集成，硬件令牌。
* [Kinde](https://kinde.com/) - 简单、强大的身份验证，您可以在几分钟内与您的产品集成。开始使用 7,500 个免费 MAU 所需的一切。
* [logintc.com](https://www.logintc.com/) — 通过推送通知进行双因素身份验证 （2FA），对 10 个用户免费、VPN、网站和 SSH
* [MojoAuth](https://mojoauth.com/) - MojoAuth 可以在几分钟内在您的网络、移动设备或任何应用程序上轻松实施无密码身份验证。
* [Okta](https://developer.okta.com/signup/) — 用户管理、身份验证和授权。每月活跃用户最多 100 人免费。
* [onelogin.com](https://www.onelogin.com/) — 身份即服务 （IDaaS）、单点登录身份提供商、云 SSO IdP、三个公司应用程序和五个个人应用程序，用户不受限制
* [Ory](https://ory.sh/) - AuthN/AuthZ/OAuth2.0/Zero Trust 托管安全平台。永久免费的开发者帐户，具有所有安全功能、无限的团队成员、200 个每日活跃用户和 25k/mo 权限检查。
* [Permit.io](https://permit.io) - Auhtorization-as-a-service provider 平台，支持 RBAC、ABAC 和 ReBAC，用于具有实时更新和无代码策略 UI 的可缩放微服务。每月 1000 个活跃用户免费套餐。
* [第二阶段](https://phasetwo.io) \- Keycloak 开源身份和访问管理。免费领域多达 1000 个用户，最多 10 个 SSO 连接，利用第二阶段的 Keycloak 增强容器，其中包括[组织](https://phasetwo.io/product/organizations/)扩展。
* [SSOJet](https://ssojet.com/) - 添加企业 SSO，而无需重新构建身份验证。免费计划包括无限的每月活跃用户、无限的组织、2 个 SSO 和 2 个 SCIM 连接。
* [Stytch](https://www.stytch.com/) - 一个一体化平台，提供用于身份验证和欺诈预防的 API 和 SDK。免费计划包括 10,000 个每月活跃用户、无限组织、5 个 SSO 或 SCIM 连接以及 1,000 个 M2M 代币。
* [堆栈身份验证](https://stack-auth.com) — 不糟糕的开源身份验证。对开发人员最友好的解决方案，只需五分钟即可开始使用。免费自托管，或提供托管 SaaS 版本，每月有 10k 免费活跃用户。
* [SuperTokens](https://supertokens.com/) - 原生集成到您的应用程序中的开源用户身份验证 - 使您能够快速入门，同时控制用户和开发人员体验。最多 5000 个 MAU 免费。
* [Warrant](https://warrant.dev/) — 为您的应用托管企业级授权和访问控制服务。免费套餐包括每月 100 万个 API 请求和 1,000 个 authz 规则。
* [ZITADEL Cloud](https://zitadel.com) — 适合您的交钥匙用户和访问管理，支持多租户 （B2B） 用例。最多可免费处理 25,000 个经过身份验证的请求，并具有所有安全功能（OTP、无密码、策略等无付费专区）。
* [PropelAuth](https://propelauth.com) — 只需几行代码即可立即向任何规模的公司出售，最多可免费获得 200 名用户和 10k 交易电子邮件（带有水印品牌：“Powered by PropelAuth”）。
* [Logto](https://logto.io/) - 开发、保护和管理产品的用户身份 - 用于身份验证和授权。最多 5,000 个 MAU 免费，并提供开源自托管选项。
* [WorkOS](https://workos.com/) - 免费用户管理和身份验证，最多可容纳 100 万 MAU。支持邮箱+密码、社交认证、Magic Auth、MFA 等。

**[⬆️ 返回首页](#目录)**

## 移动应用程序分发和反馈

* [TestApp.io](https://testapp.io) - 确保您的移动应用程序正常工作的首选平台。免费计划：一个应用程序、分析、无限版本和安装以及反馈收集。
* [Loadly](https://loadly.io) - iOS 和 Android 测试版应用程序分发服务提供完全免费的服务，无限下载、高速下载和无限上传。
* [Diawi](https://www.diawi.com) - 将 iOS 和 Android 应用程序直接部署到设备。免费计划：应用程序上传、受密码保护的链接、1 天到期、十次安装。
* [InstallOnAir](https://www.installonair.com) - 通过无线方式分发 iOS 和 Android 应用程序。免费计划：无限上传，私人链接，访客有效期 2 天，注册用户有效期 60 天。
* [GetUpdraft](https://www.getupdraft.com) - 分发移动应用程序进行测试。免费计划包括一个应用程序项目、三个应用程序版本、500 MB 存储空间和每月 100 个应用程序安装。
* [Appho.st](https://appho.st) - 移动应用程序托管平台。免费计划包括五个应用程序、50 次每月下载和最大 100 MB 的文件大小。

**[⬆️ 返回首页](#目录)**

## 管理体系

* [bitnami.com](https://bitnami.com/) — 在 IaaS 上部署准备好的应用程序。免费管理 1 个 AWS 微实例
* [Esper](https://esper.io) — 适用于具有 DevOps 的 Android 设备的 MDM 和 MAM。100 台设备免费，只需一个用户许可证和 25 MB 应用程序存储空间。
* [jamf.com](https://www.jamf.com/) — 适用于 iPad、iPhone 和 Mac 的设备管理，三台设备免费
* [Miradore](https://miradore.com) — 设备管理服务。及时了解您的设备群并免费保护无限的设备。免费计划提供基本功能。
* [moss.sh](https://moss.sh) - 帮助开发人员部署和管理其 Web 应用和服务器。每月免费最多 25 个 git 部署
* [runcloud.io](https://runcloud.io/) - 服务器管理主要集中在 PHP 项目上。最多 1 台服务器免费。
* [ploi.io](https://ploi.io/) - 服务器管理工具，可轻松管理和部署您的服务器和站点。一台服务器免费。
* [xcloud.host](https://xcloud.host) — 具有用户友好界面的服务器管理和部署平台。一台服务器可免费使用套餐。
* [serveravatar.com](https://serveravatar.com) — 通过自动配置管理和监控基于 PHP 的 Web 服务器。一台服务器免费。

**[⬆️ 返回首页](#目录)**

## 消息传递和流媒体

* [Ably](https://www.ably.com/) - 具有存在、持久性和保证交付的实时消息传递服务。免费计划包括每月 3m 条消息、100 个峰值连接和 100 个峰值通道。
* [cloudamqp.com](https://www.cloudamqp.com/) — RabbitMQ 即服务。小狐猴计划：每月最多 100 万条消息，最多 20 个并发连接，最多 100 个队列，最多 10,000 条排队消息，不同可用区中的多个节点
* [courier.com](https://www.courier.com/) — 用于推送、应用内、电子邮件、聊天、短信和其他消息传递渠道的单一 API，具有模板管理和其他功能。免费计划包括每月 10,000 条消息。
* [Engage](https://engage.so/) - 适用于 SaaS 的一体化客户参与和自动化工具（电子邮件、推送、短信、产品导览、横幅等）。每月最多 1,000 名活跃用户免费。
* [engagespot.co](https://engagespot.co/) — 面向开发人员的多渠道通知基础设施，具有预构建的应用内收件箱和无代码模板编辑器。免费计划包括每月 10,000 条消息。
* [HiveMQ](https://www.hivemq.com/mqtt-cloud-broker/) - 将您的 MQTT 设备连接到云原生 IoT 消息传递代理。永久免费连接多达 100 台设备（无需信用卡）。
* [knock.app](https://knock.app) – 面向开发人员的通知基础设施。通过单个 API 调用发送到多个渠道，例如应用内、电子邮件、短信、Slack 和推送。免费计划包括每月 10,000 条消息。
* [NotificationAPI.com](https://www.notificationapi.com/) — 在 5 分钟内将用户通知添加到任何软件。免费计划包括每月 10,000 条通知 + 100 条短信和自动呼叫。
* [Novu.co](https://novu.co) — 面向开发人员的开源通知基础设施。用于在一个地方管理所有通信渠道的简单组件和 API：电子邮件、短信、直接、应用内和推送。免费计划包括每月 30,000 条通知，保留期 90 天。
* [pusher.com](https://pusher.com/) — 实时消息服务。每天最多可同时连接 100 个连接和 200,000 条消息免费
* [scaledrone.com](https://www.scaledrone.com/) — 实时消息服务。每天最多可同时连接 20 个连接和 100,000 个活动免费
* [synadia.com](https://synadia.com/ngs) — [NATS.io](https://nats.io) 即服务。全局、AWS、GCP 和 Azure。永久免费，具有 4k 消息大小、50 个活动连接和每月 5GB 数据。
* [pubnub.com](https://www.pubnub.com/) - Swift、Kotlin 和 React 每月 100 万笔交易。事务可能包含多条消息。
* [eyeson API](https://developers.eyeson.team/) - 基于 WebRTC（SFU、MCU）构建视频平台的视频通信 API 服务。允许实时数据注入、视频布局、录制、功能齐全的托管 Web UI（快速入门）或自定义 UI 包。为每月 1000 分钟会议的[开发人员提供免费套餐](https://apiservice.eyeson.com/api-pricing) 。
* [webpushr](https://www.webpushr.com/) - 网络推送通知 - 最多 10k 订阅者免费、无限制推送通知、浏览器内消息传递
* [httpSMS](https://httpsms.com) - 使用您的 Android 手机作为 SMS 网关发送和接收短信。每月免费发送和接收多达 200 条消息。
* [EMQX Serverless](https://www.emqx.com/en/cloud/serverless-mqtt) - 可在几秒钟内获得可扩展且安全的无服务器 MQTT 代理。1M 会话分钟/月永久免费（无需信用卡）。
* [Pocket Alert](https://pocketalert.app) - 向您的 iOS 和 Android 设备发送推送通知。通过 API 或 Webhook 轻松集成并保持对警报的完全控制。免费计划：每天向 1 台设备和 1 个应用程序发送 50 条消息。
* [SuprSend](https://www.suprsend.com/) - SuprSend 是一种通知基础设施，它通过 API 优先的方法简化您的产品通知。使用单个通知 API 在多个渠道上创建和传递事务性、crons 和参与度通知。在免费计划中，您每月会收到 10,000 条通知，包括不同的工作流节点，例如摘要、批处理、多渠道、首选项、租户、广播等。
* [SMSGate](https://sms-gate.app) - 适用于 Android™ 的 SMS 网关支持使用云路由通过您的设备发送和接收 SMS 消息。完全免费的云服务（建议在每天超过 10,000 条消息时发出通知，以保持所有用户的质量）。

**[⬆️ 返回首页](#目录)**

## 日志管理

* [bugfender.com](https://bugfender.com/) — 每天免费提供多达 100k 行日志，保留 24 小时
* [logentries.com](https://logentries.com/) — 每月最多 5 GB 免费，保留 7 天
* [loggly.com](https://www.loggly.com/) — 单个用户免费，200MB/天，保留 7 天
* [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-siem/) — 由 Manage Engine 提供支持的日志管理服务。免费计划提供 50 GB 存储空间，具有 15 天的存储保留和 7 天的搜索。
* [sumologic.com](https://www.sumologic.com/) — 每天最多 500 MB 免费，保留 7 天
* [log.dog](https://log.dog/) — LogDog 是一个带有 Web UI 的远程调试/日志记录 SDK（iOS 和 Android）。实时捕获所有日志、请求和事件，并允许拦截它们。每月免费提供最多 100MB 的日志
* [logflare.app](https://logflare.app/) — 每个应用程序每月最多可输入 12,960,000 个条目，免费，保留 3 天
* [logtail.com](https://logtail.com/) — 基于 ClickHouse 的 SQL 兼容日志管理。每月最多免费 1 GB，保留三天。
* [logzab.com](https://logzab.com/) — 审计跟踪管理系统。每月免费 1,000 个用户活动日志，保留 1 个月，最多 5 个项目。
* [openobserve.ai](https://openobserve.ai/) - 200 GB 摄取/月免费，保留 15 天

**[⬆️ 返回首页](#目录)**

## 翻译管理

* [AutoLocalise.com](https://www.autolocalise.com/) — 无需管理翻译文件即可立即本地化。每月最多 10,000 个字符免费，语言不限。
* [crowdin.com](https://crowdin.com/) — 无限的项目、无限的字符串和开源协作者
* [gitlocalize.com](https://gitlocalize.com) - 私有和公共存储库免费且无限制
* [Lecto](https://lecto.ai/) - 具有免费套餐的机器翻译 API（30 个免费请求，每个请求 1000 个翻译字符）。与 Loco Translate Wordpress 插件集成。
* [lingohub.com](https://lingohub.com/) — 最多免费 3 个用户，开源始终免费
* [localazy.com](https://localazy.com) - 免费 1000 个源语言字符串、无限语言、无限贡献者、启动和开源交易
* [Localeum](https://localeum.com) - 免费最多 1000 个字符串、一个用户、无限语言、无限项目
* [Localit](https://localit.io) – 快速、对开发人员友好的本地化平台，具有无缝且免费的 GitHub/GitLab 集成、AI 辅助和手动翻译以及慷慨的免费计划（包括 2 个用户、500 个密钥和无限项目）。
* [localizely.com](https://localizely.com/) — 开源免费
* [Loco](https://localise.biz/) — 最多免费 2000 个翻译，无限翻译人员，10 种语言/项目，1000 个可翻译资产/项目
* [oneskyapp.com](https://www.oneskyapp.com/) — 最多 5 位用户的有限免费版，开源免费
* [POEditor](https://poeditor.com/) — 释放多达 1000 个字符串
* [SimpleLocalize](https://simplelocalize.io/) - 免费提供多达 100 个翻译密钥、无限字符串、无限语言、启动优惠
* [Texterify](https://texterify.com/) - 单个用户免费
* [Tolgee](https://tolgee.io) - 免费 SaaS 产品，翻译有限，永久免费的自托管版本
* [transifex.com](https://www.transifex.com/) — 开源免费
* [Translation.io](https://translation.io) - 开源免费
* 翻译 [\- 免费](https://translized.com)最多 1000 个字符串，一个用户，无限语言，无限项目
* [webtranslateit.com](https://webtranslateit.com/) — 释放多达 500 根字符串
* [weblate.org](https://weblate.org/) — 对于自由项目免费，免费层和无限自托管本地最多有 10,000 个字符串源。
* [免费 PO 编辑器](https://pofile.net/free-po-editor) — 对所有人免费
* [Lingo.dev](https://lingo.dev) – 用于 Web 和移动本地化的开源 AI 驱动的 CLI。自带 LLM，或通过 Lingo.dev 管理的本地化引擎每月使用 10,000 个免费单词。

**[⬆️ 返回首页](#目录)**

## 监测

* [alerty.ai](https://www.alerty.ai) - 免费 APM 和 FE、BE、DB 等监控 + 免费代理运行。
* [appdynamics.com](https://www.appdynamics.com/) — 24 小时指标免费，应用程序性能管理代理仅限于 1 个 Java、1 个 .NET、1 个 PHP 和 1 个 Node.js
* [appneta.com](https://www.appneta.com/) — 免费，数据保留 1 小时
* [appspector.com](https://appspector.com/) - 远程 iOS/Android/Flutter 调试的任务控制。少量流量使用免费（64MB 日志）。
* [assertible.com](https://assertible.com) — 自动化 API 测试和监控。适用于团队和个人的免费计划。
* [更好的堆栈](https://betterstack.com/better-uptime) \- 在单个产品中实现正常运行时间监控、事件管理、待命调度/警报和状态页面。免费计划包括十台显示器，检查频率为 3 分钟，状态页面。
* [bleemeo.com](https://bleemeo.com) - 免费 3 台服务器、5 台正常运行时间监视器、无限用户、无限仪表板、无限警报规则。
* [checklyhq.com](https://checklyhq.com) - 面向开发者的开源 E2E / 综合监控和深度 API 监控。免费计划，一个用户和 10k API 和网络/1.5k 浏览器检查运行。
* [cloudsploit.com](https://cloudsploit.com) — AWS 安全和配置监控。免费：无限的按需扫描、无限的用户、无限的存储帐户。订阅：自动扫描、API 访问等。
* [Core Web Vitals 历史记录](https://punits.dev/core-web-vitals-historical/) \- 查找 URL 或网站的核心 Web Vitals 历史记录。
* [cronitor.io](https://cronitor.io/) - cron 作业、网站、API 等的性能洞察和正常运行时间监控。具有五台显示器的免费套餐。
* [datadoghq.com](https://www.datadoghq.com/) — 最多 5 个节点免费
* [deadmanssnitch.com](https://deadmanssnitch.com/) — 监控 cron 作业。一个免费的告密者（监视器），如果您推荐其他人注册，则更多
* [downtimemonkey.com](https://downtimemonkey.com/) — 60 个正常运行时间监视器，每隔 5 分钟一次。电子邮件、Slack 警报。
* [economize.cloud](https://economize.cloud) — Economize 通过组织云资源来优化和报告云基础设施成本，帮助揭开云基础设施成本的神秘面纱。每月在 Google Cloud Platform 上花费高达 5,000 美元即可免费。
* [elastic.co](https://www.elastic.co/solutions/apm) — 为 JS 开发人员提供即时性能洞察。免费，24 小时数据保留
* [fivenines.io](https://fivenines.io/) — 通过实时仪表板和警报进行 Linux 服务器监控 — 以 60 秒的间隔永久免费，最多 5 台受监控服务器。无需信用卡。
* [Grafana Cloud](https://grafana.com/products/cloud/) - Grafana Cloud 是一个可组合的可观测性平台，它将指标和日志与 Grafana 集成在一起。免费：3 个用户、10 个仪表板、100 个警报、Prometheus 和 Graphite 中的指标存储（10,000 个系列，14 天保留）、Loki 中的日志存储（50 GB 日志，14 天保留）
* [healthchecks.io](https://healthchecks.io) — 监控您的 cron 作业和后台任务。最多 20 张支票免费。
* [incidenthub.cloud](https://incidenthub.cloud/) — 云和 SaaS 状态页面聚合器 - 20 个监视器和 2 个通知通道（Slack 和 Discord）永久免费。
* [inspector.dev](https://www.inspector.dev) - 不到一分钟即可获得完整的实时监控仪表板，并提供永久免费套餐。
* [instatus.com](https://instatus.com) - 在 10 秒内获得漂亮的状态页面。永久免费，拥有无限的订阅者和无限的团队。
* [instrumentalapp.com](https://instrumentalapp.com) - 美观且易于使用的应用程序和服务器监控，具有多达 500 个指标和 3 小时的免费数据可见性
* [keychest.net/speedtest](https://keychest.net/speedtest) - 针对 Digital Ocean 的独立速度测试和 TLS 握手延迟测试
* [letsmonitor.org](https://letsmonitor.org) - SSL 监控，最多 5 台显示器免费
* [linkok.com](https://linkok.com) - 在线断开链接检查器，对于最多 100 页的小型网站免费，对于开源项目完全免费。
* [loader.io](https://loader.io/) — 有限制的免费负载测试工具
* [Middleware.io](https://middleware.io/) - 中间件可观测性平台提供对应用和堆栈的完整可见性，因此您可以大规模监视和诊断问题。他们有一个供开发社区使用的永久免费计划，允许对多达 1M 个日志事件进行日志监控，为最多 2 台主机提供基础设施监控和 APM。
* [MonitorMonk](https://monitormonk.com) - 具有漂亮状态页面的极简正常运行时间监控。永久免费计划为 10 个网站或 api 端点提供 HTTPS、关键字、SSL 和响应时间监控，并提供 2 个仪表板/状态页面。
* [netdata.cloud](https://www.netdata.cloud/) — Netdata 是一个用于收集实时指标的开源工具。这是一个不断发展的产品，也可以在 GitHub 上找到！
* [newrelic.com](https://www.newrelic.com) — New Relic 可观测性平台，旨在帮助工程师创建更完美的软件。从单体到无服务器，您可以检测所有内容，然后分析、故障排除和优化整个软件堆栈。免费套餐提供每月 100GB 的免费数据摄取、一个免费的完全访问用户和无限制的免费主要用户。
* [nixstats.com](https://nixstats.com) - 一台服务器免费。电子邮件通知、公共状态页面、60 秒间隔等。
* [OnlineOrNot.com](https://onlineornot.com/) - OnlineOrNot 提供网站和 API 的正常运行时间监控，监控 cron 作业和计划任务。还提供状态页面。前五次检查间隔为 3 分钟是免费的。免费套餐通过 Slack、Discord 和电子邮件发送警报。
* [OntarioNet.ca CN 测试](https://cntest.ontarionet.ca) — 检查网站在中国是否被防火墙屏蔽。它通过比较中国服务器与美国服务器检测到的 DNS 结果和 ASN 信息来识别 DNS 污染。
* [opsgenie.com](https://www.opsgenie.com/) — 强大的警报和待命管理，用于运营始终在线的服务。最多免费 5 个用户。
* [paessler.com](https://www.paessler.com/) — 强大的基础设施和网络监控解决方案，包括警报、强大的可视化功能和基本报告。最多可释放 100 个传感器。
* [pagecrawl.io](https://pagecrawl.io/) - 监控网站更改，最多 6 台显示器免费，每日检查。
* [pagerly.io](https://pagerly.io/) - 管理 Slack 上的待命（与 Pagerduty、OpsGenie 集成）。最多免费 1 个团队（一个团队是指一个随叫随到的团队）
* [pageradar.io](https://pageradar.io/) — 监控网站的核心 Web Vitals、SEO 更改和正常运行时间。免费计划包括 5 个 URL、每日 Core Web Vitals 监控、10 个 HTML/SEO 更改监控器、167 个国家/地区的会员链接监控和电子邮件警报。
* [pagertree.com](https://pagertree.com/) - 用于警报和待命管理的简单界面。最多免费 5 个用户。
* [phare.io](https://phare.io/) - 正常运行时间监控免费，最多可监控多达 100,000 个事件，适用于无限的项目和无限的状态页面。
* [pingbreak.com](https://pingbreak.com/) — 现代正常运行时间监控服务。检查无限的 URL 并通过 Discord、Slack 或电子邮件获取停机通知。
* [Pingmeter.com](https://pingmeter.com/) - 5 个正常运行时间监视器，间隔 10 分钟。监控 SSH、HTTP、HTTPS 和任何自定义 TCP 端口。
* [pingpong.one](https://pingpong.one/) — 具有监控功能的高级状态页面平台。免费层包括一个带有 SSL 子域的公共可自定义状态页面。Pro 计划免费提供给开源项目和非营利组织。
* [Pulsetic](https://pulsetic.com) - 10 台显示器、6 个月的历史正常运行时间/日志、无限的状态页面和自定义域！无限时间和无限免费电子邮件提醒。您不需要信用卡。
* [robusta.dev](https://home.robusta.dev/) — 基于 Prometheus 的强大 Kubernetes 监控。自带 Prometheus 或安装一体化捆绑包。免费套餐最多包括 20 个 Kubernetes 节点。通过 Slack、Microsoft Teams、Discord 等发出警报。与 PagerDuty、OpsGenie、VictorOps、DataDog 和许多其他工具集成。
* [sematext.com](https://sematext.com/) — 免费提供 24 小时指标、无限服务器、十个自定义指标、500,000 个自定义指标数据点、无限仪表板、用户等。
* [简单的可观测性](https://simpleobservability.com) — 在统一的指标和日志平台上进行强大的服务器监控，无需复杂的设置。一台服务器免费。
* [sitemonki.com](https://sitemonki.com/) — 网站、域名、Cron 和 SSL 监控，每个类别免费 5 个监视器
* [sitesure.net](https://sitesure.net) - 网站和 cron 监控 - 免费 2 个监视器
* [skylight.io](https://www.skylight.io/) — 前 100,000 个请求免费（仅限 Rails）
* [Servervana](https://servervana.com) - 高级正常运行时间监控，支持大型项目和团队。提供 HTTP 监控、基于浏览器的监控、DNS 监控、域监控、状态页面等。免费套餐包括 10 个 HTTP 监视器、1 个 DNS 监视器和一个状态页面。
* [speedchecker.xyz](https://probeapi.speedchecker.xyz/) — 性能监控 API，检查 Ping、DNS 等。
* [Squadcast.com](https://squadcast.com) - Squadcast 是一款端到端事件管理软件，旨在帮助您推广 SRE 最佳实践。永久免费计划最多可供 10 位用户使用。
* [stathat.com](https://www.stathat.com/) — 免费开始使用十个统计数据，无过期
* [statuscake.com](https://www.statuscake.com/) — 网站监控，无限制免费测试
* [statusgator.com](https://statusgator.com/) — 状态页面监控，免费 3 个监视器
* [SweetUptime](https://dicloud.net/sweetuptime-server-uptime-monitoring/) — 服务器监控、正常运行时间监控、DNS 和域监控。免费监控 10 台服务器、10 台正常运行时间和 10 个域。
* [syagent.com](https://syagent.com/) — 非商业免费服务器监控服务、警报和指标。
* [thousandeyes.com](https://www.thousandeyes.com/) — 网络和用户体验监控。免费提供主要网络服务的 3 个地点和 20 个数据馈送
* [UptimeObserver.com](https://uptimeobserver.com) - 获得 20 个正常运行时间监视器，间隔为 5 分钟，并可自定义状态页面 - 甚至用于商业用途。通过电子邮件和 Telegram 享受无限制的实时通知。无需信用卡即可开始。
* [uptimetoolbox.com](https://uptimetoolbox.com/) — 免费监控五个网站，间隔 60 秒，公共状态页面。
* [zenduty.com](https://www.zenduty.com/) — 面向网络运营、站点可靠性工程和 DevOps 团队的端到端事件管理、警报、待命管理和响应编排平台。最多 5 位用户免费。
* [RoboMiri.com](https://robomiri.com/) - RoboMiri 是一款稳定的正常运行时间监视器，提供广泛的监视器：cronjob、关键字、网站、端口、ping。25 次正常运行时间检查，免费 3 分钟间隔检查。通过电话、短信、电子邮件和 Webhook 发出警报。
* [Wachete](https://www.wachete.com) - 监控五页，每 24 小时检查一次。
* [Xitoring.com](https://xitoring.com/) — 正常运行时间监控：20 个免费，Linux 和 Windows Server 监控：5 个免费，状态页面：1 个免费 - 移动应用程序、多个通知渠道等等！

**[⬆️ 返回首页](#目录)**

## 崩溃和异常处理

* [CatchJS.com](https://catchjs.com/) - 带有屏幕截图和点击跟踪的 JavaScript 错误跟踪。开源项目免费。
* [Bugsink](https://www.bugsink.com/) — 与 Sentry-SDK 兼容的错误跟踪。每月最多可免费 5,000 个错误，或自托管时无限制使用。
* [bugsnag.com](https://www.bugsnag.com/) — 首次试用后每月最多 2,000 次错误免费
* [elmah.io](https://elmah.io/) — Web 开发人员的错误记录和正常运行时间监控。开源项目的免费小型企业订阅。
* [拥抱](https://embrace.io/) — 移动应用程序监控。对于每年拥有多达 100 万个用户会话的小型团队免费。
* [exceptionless](https://exceptionless.com) — 实时错误、功能、日志报告等。每月 3k 个活动/1 个用户免费。开源且易于自托管，可无限使用。
* [GlitchTip](https://glitchtip.com/) — 简单的开源错误跟踪。与开源 Sentry SDK 兼容。每月免费 1000 个活动，也可以无限制地自行托管
* [honeybadger.io](https://www.honeybadger.io) - 异常、正常运行时间和 cron 监控。小型团队和开源项目免费（每月 12,000 个错误）。
* [memfault.com](https://memfault.com) — 云设备可观测性和调试平台。[Nordic](https://app.memfault.com/register-nordic)、[NXP](https://app.memfault.com/register-nxp) 和 [Laird](https://app.memfault.com/register-laird) 设备免费提供 100 台设备。
* [rollbar.com](https://rollbar.com/) — 异常和错误监控，免费计划，每月 5,000 个错误，无限用户，保留 30 天
* [sentry.io](https://sentry.io/) — Sentry 实时跟踪应用程序异常，并有一个小型免费计划。每月 5k 错误免费/1 个用户，如果自托管则不受限制使用
* [公理](https://axiom.co/) — 存储高达 0.5 TB 的日志，保留期为 30 天。包括与 Vercel 等平台的集成以及使用电子邮件/Discord 通知程序进行高级数据查询。
* [Semaphr](https://semaphr.com) — 适用于您的移动应用程序的免费多合一终止开关。
* [Jam](https://jam.dev) - 一键开发者友好的错误报告。无限果酱的免费计划。
* [空格](https://whitespace.dev) – 直接在浏览器中一键报告错误。免费计划，无限录音供个人使用。

**[⬆️ 返回首页](#目录)**

## 搜索

* [algolia.com](https://www.algolia.com/) — 托管搜索解决方案，具有抗错别字、相关性和 UI 库，可轻松创建搜索体验。免费的“构建”计划包括 1M 文档和 10K 搜索/月。还免费提供[开发人员文档搜索](https://docsearch.algolia.com/) 。
* [bonsai.io](https://bonsai.io/) — 免费 1 GB 内存和 1 GB 存储空间
* [CommandBar](https://www.commandbar.com/) - 统一搜索栏即服务、基于 Web 的 UI 小部件/插件，允许用户搜索产品中的内容、导航、功能等，这有助于可发现性。每月活跃用户最多 1,000 人免费，命令无限制。
* [Orama Cloud](https://orama.com/pricing) — 免费 3 个索引、100K 文档/索引、无限制的全文/矢量/混合搜索、60 天分析
* [searchly.com](http://www.searchly.com/) — 免费 2 个索引和 20 MB 存储空间
* [easysitesearch.com](https://easysitesearch.com/) — 搜索小部件和 API，具有基于网络爬虫的自动索引。免费无限制搜索，最多 50 个子页面。

**[⬆️ 返回首页](#目录)**

## 教育和职业发展

* [FreeCodeCamp](https://www.freecodecamp.org/) - 开源平台，提供数据分析、信息安全、Web 开发等方面的免费课程和认证。
* [Odin 项目](https://www.theodinproject.com/) \- 免费的开源平台，其课程侧重于用于 Web 开发的 JavaScript 和 Ruby。
* [免费专业简历模板和编辑器](https://www.overleaf.com/latex/templates/tagged/cv) \- 免费平台，拥有大量经验丰富的专业人士的简历模板，随时可以完全克隆和编辑并下载，ATS 优化。
* [DeepLearning.AI 短期课程](https://www.deeplearning.ai/short-courses/) \- 由行业领先专家提供的免费短期课程，让您在一小时或更短的时间内获得最新的生成式 AI 工具和技术的实践经验。
* [LabEx](https://labex.io) - 通过交互式实验室和实际项目培养 Linux、DevOps、网络安全、编程、数据科学等方面的技能。
* [Roadmap.sh](https://roadmap.sh) - 免费学习路线图，涵盖从区块链到用户体验设计的各个方面的开发。
* [思科网络学院，全民技能](https://skillsforall.com/) \- 提供网络安全、网络和 Python 等主题的免费认证课程。
* [麻省理工学院 OpenCourseWare](https://ocw.mit.edu/) - 麻省理工学院 OpenCourseWare 是一个在线出版物，收录了 2,500 多门麻省理工学院课程的材料，与世界各地的学习者和教育工作者自由分享知识。Youtube 频道可在 [@mitocw](https://www.youtube.com/@mitocw/featured) 找到
* [W3Schools](https://www.w3schools.com/) - 提供有关 HTML、CSS、JavaScript 等 Web 开发技术的免费教程。
* [可汗学院](https://www.khanacademy.org/computing/computer-programming) \- 用于学习基础和高级 HTML/CSS、JavaScript 和 SQL 的免费在线指南。
* [全栈开放](https://fullstackopen.com/en/) – 关于使用 React、Node.js、GraphQL、TypeScript 等进行现代 Web 开发的免费大学水平课程。完全在线和自定进度。
* [edX](https://www.edx.org/) - 提供来自 4,000 所领先机构（包括哈佛大学和麻省理工学院）的 250 多门免费在线课程，专门研究计算机科学、工程和数据科学。
* [Django-tutorial.dev](https://django-tutorial.dev) - 学习 Django 作为他们的第一个框架的免费在线指南，并提供免费的 dofollow 反向链接到用户撰写的文章。
* [DevNet Academy](https://devnet-academy.com/) – 针对 Cisco DevNet Expert / CCIE Automation 认证的免费自定进度培训。涵盖 Python Click 和 Flask-RESTx。

**[⬆️ 返回首页](#目录)**

## 电子邮件

* [10minutemail](https://10minutemail.com) - 用于测试的免费临时电子邮件。
* [AhaSend](https://ahasend.com) - 交易电子邮件服务，每月免费 1000 封电子邮件，免费计划中具有无限的域、团队成员、Webhook 和消息路由。
* [AnonAddy](https://anonaddy.com) - 开源匿名邮件转发，免费创建无限的邮件别名
* [Antideo](https://www.antideo.com) — 免费套餐中每小时 10 个 API 请求，用于电子邮件验证、IP 和电话号码验证。不需要信用卡。
* [Brevo](https://www.brevo.com/) — 9,000 封电子邮件/月，300 封电子邮件/天免费
* [OneSignal](https://onesignal.com/) — 10,000 封电子邮件/月，无需信用卡。
* [Bump](https://bump.email/) - 免费 10 个 Bump 电子邮件地址，一个自定义域
* [Burnermail](https://burnermail.io/) – 免费 5 个 Burner 电子邮件地址、1 个邮箱、7 天邮箱历史记录
* [Buttondown](https://buttondown.email/) — 时事通讯服务。最多 100 个订阅者免费
* [CloudMailin](https://www.cloudmailin.com/) - 通过 HTTP POST 和事务性出站的传入电子邮件 - 每月 10,000 封免费电子邮件
* [Contact.do](https://contact.do/) — 链接中的联系表单（联系表单的位）
* [debugmail.io](https://debugmail.io/) — 为开发人员提供易于使用的测试邮件服务器
* [DNSExit](https://dnsexit.com/) - 您域下最多 2 个电子邮件地址免费，并具有 100MB 的存储空间。IMAP、POP3、SMTP、SPF/DKIM 支持。
* [EmailLabs.io](https://emaillabs.io/en) — 每月免费发送多达 9,000 封电子邮件，每天最多发送 300 封电子邮件。
* [EmailOctopus](https://emailoctopus.com) - 每月最多 2,500 名订阅者和 10,000 封电子邮件免费
* [EmailJS](https://www.emailjs.com/) – 这不是整个电子邮件服务器;这只是一个电子邮件客户端，您可以使用它直接从客户端发送电子邮件，而无需暴露您的凭据，免费套餐每月有 200 个请求、2 个电子邮件模板、高达 50Kb 的请求、有限的联系人历史记录。
* [EtherealMail](https://ethereal.email) - Ethereal 是一种虚假的 SMTP 服务，主要针对 Nodemailer 和 EmailEngine 用户（但不限于）。这是一项完全免费的反交易电子邮件服务，消息永远不会被送达。
* [Temp-Mail.org](https://temp-mail.org/en/) - 临时/一次性邮件生成：利用一系列各种域。每次重新加载页面时，电子邮件地址都会刷新。它是完全免费的，不包括其服务的任何定价。
* [TempMailDetector.com](https://tempmaildetector.com/) - 每月免费验证多达 200 封电子邮件，看看电子邮件是否是临时的。
* [Emailvalidation.io](https://emailvalidation.io) - 每月 100 次免费电子邮件验证
* [FakeMailGenerator.com](https://www.fakemailgenerator.com/) - 德国临时/一次性邮件生成器。支持 10 个域名，同时让您可以自由创建无限地址。（包括广告）但除此之外，该服务不包含任何定价，它是完全免费的。
* [forwardemail.net](https://forwardemail.net) — 自定义域的免费电子邮件转发。使用您的域名创建和转发无限数量的电子邮件地址（ **注意** ：如果您使用 .casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、.lat、.loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work TLD，则必须付费）
* [模仿电子邮件](https://imitate.email) \- 沙盒电子邮件服务器，用于跨构建/qa 和 ci/cd 测试电子邮件功能。免费帐户每天永久收到 15 封电子邮件。
* [ImprovMX](https://improvmx.com) – 免费电子邮件转发。
* [EForw](https://www.eforw.com) – 一个域的免费电子邮件转发。接收和发送来自您域的电子邮件。
* [收件箱应用程序](https://inboxesapp.com) — 每天最多创建 3 封临时电子邮件，然后在完成后从方便的 Chrome 扩展程序中删除它们。非常适合测试注册流程。
* [inboxkitten.com](https://inboxkitten.com/) - 免费的临时/一次性电子邮件收件箱，最多可自动删除 3 天的电子邮件。开源，可以自托管。
* [mail-tester.com](https://www.mail-tester.com) — 测试电子邮件的 DNS/SPF/DKIM/DMARC 设置是否正确，每月免费 20 个。
* [dkimvalidator.com](https://dkimvalidator.com/) - 测试电子邮件的 DNS/SPF/DKIM/DMARC 设置是否正确，roundsphere.com 免费服务
* [mailcatcher.me](https://mailcatcher.me/) — 捕获邮件并通过 Web 界面提供邮件。
* [mailchannels.com](https://www.mailchannels.com) - 具有 REST API 和 SMTP 集成的电子邮件 API，每月最多可免费发送 3,000 封电子邮件。
* [Mailcheck.ai](https://www.mailcheck.ai/) - 阻止用户使用临时电子邮件地址注册，每小时 120 个请求（每月 ~86,400 个）
* [Mailchimp](https://mailchimp.com/) — 每月免费 500 名订阅者和 1,000 封电子邮件。
* [Maildroppa](https://maildroppa.com) - 最多 100 个订阅者和无限的电子邮件以及免费的自动化。
* [MailerLite.com](https://www.mailerlite.com) — 1,000 名订阅者/月，12,000 封电子邮件/月免费
* [MailerSend.com](https://www.mailersend.com) — 电子邮件 API、SMTP、每月 3,000 封电子邮件免费用于交易电子邮件
* [mailinator.com](https://www.mailinator.com/) — 免费的公共电子邮件系统，您可以在其中使用任何您想要的收件箱
* [Mailjet](https://www.mailjet.com/) — 每月免费 6,000 封电子邮件（每天发送 200 封电子邮件的限制）
* [Mailnesia](https://mailnesia.com) - 免费的临时/一次性电子邮件，自动访问注册链接。
* [mailsac.com](https://mailsac.com) - 用于临时电子邮件测试的免费 API、免费公共电子邮件托管、出站捕获、电子邮件到 Slack/websocket/webhook（每月 1,500 个 API 限制）
* [Mailtrap.io](https://mailtrap.io/) — 用于开发的假 SMTP 服务器，免费计划，一个收件箱，100 封邮件，没有团队成员，每秒两封电子邮件，没有转发规则。
* [Mail7.io](https://www.mail7.io/) — QA 开发人员的免费临时电子邮件地址。使用 Web 界面或 API 立即创建电子邮件地址。
* [临时电子邮件](https://www.momentaryemail.com/) — 免费的临时电子邮件地址。在网站上或通过 RSS 提要阅读传入的电子邮件。
* [Mutant Mail](https://www.mutantmail.com/) – 免费 10 个电子邮件 ID、1 个域、1 个邮箱。所有电子邮件 ID 的单个邮箱。
* [Outlook.com](https://outlook.live.com/owa/) - 免费的个人电子邮件和日历。
* [Parsio.io](https://parsio.io) — 免费电子邮件解析器（转发电子邮件、提取数据、发送到您的服务器）
* [pepipost.com](https://pepipost.com) — 第一个月免费 30k 封电子邮件，然后每天前 100 封电子邮件免费。
* [Plunk](https://useplunk.com) - 每月免费 3K 封电子邮件
* 邮[戳](https://postmarkapp.com/) \- 每月 100 封电子邮件免费，无限制的 DMARC 每周摘要。
* [Proton Mail](https://proton.me/mail) - 具有内置端到端加密功能的免费安全电子邮件帐户服务提供商。免费 1GB 存储空间。
* [Queuemail.dev](https://queuemail.dev) — 可靠的电子邮件传递 API。免费套餐（每月 10,000 封电子邮件）。异步发送。使用多个 SMTP 服务器。黑名单、日志记录、跟踪、Webhook 等。
* [QuickEmailVerification](https://quickemailverification.com)：每天免费验证 100 封电子邮件，免费套餐以及其他免费 API，如 DEA Detector、DNS Lookup、SPF Detector 等。
* [重新发送](https://resend.com) \- 面向开发人员的事务性电子邮件 API。3,000 封电子邮件/月，100 封电子邮件/天免费，一个自定义域。
* [寄件人](https://www.sender.net)每月最多 15,000 封电子邮件，最多 2,500 名订阅者
* [Sendpulse](https://sendpulse.com) — 500 个订阅者/月，每月免费 15,000 封电子邮件
* [SimpleLogin](https://simplelogin.io/) – 开源、自托管的电子邮件别名/转发解决方案。免费 5 个别名，无限带宽，无限回复/发送。教育人员（学生、研究人员等）免费。
* [Substack](https://substack.com) — 无限制的免费时事通讯服务。收费后开始付款。
* [Sweego](https://www.sweego.io/) - 面向开发人员的欧洲事务性电子邮件 API。每天免费 500 封电子邮件。
* [外卖](https://takeout.bysourfruit.com) \- 不断更新的电子邮件服务，使发送电子邮件变得容易。每月免费发送 500 封交易电子邮件。
* [temp-mail.io](https://temp-mail.io) — 免费的一次性临时电子邮件服务，可同时发送多封电子邮件并转发
* [tinyletter.com](https://tinyletter.com/) — 5,000 名订阅者/月免费
* [Touchlead](https://touchlead.app) - 一种多用途营销自动化工具，具有潜在客户管理、表单生成器和自动化功能。对有限数量的潜在客户和自动化免费
* [trashmail.com](https://www.trashmail.com) - 免费的一次性电子邮件地址，具有转发和自动地址过期功能
* [Tuta](https://tuta.com/) - 免费的安全电子邮件帐户服务提供商，内置端到端加密，无广告，无跟踪。免费 1GB 存储空间，一个日历（Tuta 也有[付费计划](https://tuta.com/pricing) 。Tuta 也是部分[开源](https://github.com/tutao/tutanota)的，因此您可以自托管。
* [Verifalia](https://verifalia.com/email-verification-api) — 具有邮箱确认和一次性电子邮件地址检测器的实时电子邮件验证 API;每天 25 次免费电子邮件验证。
* [verimail.io](https://verimail.io/) — 批量和 API 电子邮件验证服务。每月 100 次免费验证
* [Zoho](https://www.zoho.com) — 最初是一家电子邮件提供商，但现在提供一套服务，其中一些有免费计划。具有免费计划的服务列表：
  * [电子邮件](https://zoho.com/mail) 5 位用户免费。5GB/用户和 25 MB 附件限制，一个域。
  * [Zoho Assist](https://www.zoho.com/assist) — Zoho Assist 的永久免费计划包括一个并发远程支持许可证和访问 5 个无人值守的计算机许可证，无限期可供专业人员和人员使用。
  * [冲刺](https://zoho.com/sprints) 5 个用户免费，5 个项目和 500MB 存储空间。
  * [文档](https://zoho.com/docs) — 5 位用户免费，上传限制为 1 GB，存储空间为 5GB。Zoho Office 套件（Writer、Sheets 和 Show）捆绑在一起。
  * [项目](https://zoho.com/projects) — 3 个用户免费，2 个项目和 10 MB 附件限制。同样的计划也适用于 [Bugtracker](https://zoho.com/bugtracker)。
  * [连接](https://zoho.com/connect) — 团队协作免费，可供 25 位用户免费使用，拥有 3 个组、3 个自定义应用程序、3 个看板、3 个手册和 10 个集成以及频道、活动和论坛。
  * [会议](https://zoho.com/meeting) — 最多有 3 名会议参与者和 10 名网络研讨会与会者的会议。
  * [Vault](https://zoho.com/vault) — 个人可以访问密码管理。
  * [Showtime](https://zoho.com/showtime) — 另一款会议软件，用于培训最多 5 名与会者的远程会议。
  * [笔记本](https://zoho.com/notebook) — Evernote 的免费替代品。
  * [Wiki](https://zoho.com/wiki) — 三个用户免费，拥有 50 MB 存储空间、无限页面、zip 备份、RSS 和 Atom 提要、访问控制和可自定义的 CSS。
  * [订阅](https://zoho.com/subscriptions) — 定期计费管理免费，适用于 20 个客户/订阅和 1 个用户，所有付款托管均由 Zoho 完成。存储最后 40 个订阅指标
  * [结帐](https://zoho.com/checkout) — 产品计费管理，有 3 个页面和多达 50 笔付款。
  * [桌面](https://zoho.com/desk) — 客户支持管理，包括三个代理、私人知识库和电子邮件工单。与 [Assist](https://zoho.com/assist) 集成，适用于一名远程技术人员和 5 台无人值守的计算机。
  * [Cliq](https://zoho.com/cliq) — 具有 100 GB 存储空间、无限用户、每个频道 100 个用户和 SSO 的团队聊天软件。
  * [活动](https://zoho.com/campaigns) \- 电子邮件营销
  * [表单](https://zoho.com/forms) \- 表单创建者
  * [签名](https://zoho.com/sign) \- 无纸化签名
  * [调查](https://zoho.com/surveys) \- 在线调查
  * [预订](https://zoho.com/bookings) \- 预约安排
* [Maileroo](https://maileroo.com) - 面向开发人员的 SMTP 中继和电子邮件 API。每月 5,000 封电子邮件、无限域、免费电子邮件验证、黑名单监控、邮件测试器等。

**[⬆️ 返回首页](#目录)**

## 功能切换管理平台

* [ConfigCat](https://configcat.com) - ConfigCat 是一项以开发人员为中心的功能标志服务，具有无限的团队规模、出色的支持和合理的价格标签。免费计划每月最多 10 个标志、两个环境、1 个产品和 500 万个请求。
* [Flagsmith](https://flagsmith.com) - 自信地发布功能;管理跨 Web、移动和服务器端应用程序的功能标志。使用我们的托管 API，部署到您自己的私有云，或在本地运行。
* [GrowthBook](https://growthbook.io) - 具有内置贝叶斯统计分析引擎的开源功能标志和 A/B 测试提供商。最多 3 位用户免费，无限的功能标志和实验。
* [Hypertune](https://www.hypertune.com) - 类型安全功能标志、A/B 测试、分析和应用配置，具有 Git 风格的版本控制和同步、内存中、本地标志评估。最多 5 名团队成员免费，具有无限的功能标志和 A/B 测试。
* [糖蜜](https://www.molasses.app) \- 强大的功能标志和 A/B 测试。最多释放 3 个环境，每个环境有 5 个功能标志。
* [Toggled.dev](https://www.toggled.dev) - 企业级、可缩放的多区域功能切换管理平台。免费计划最多 10 个标志、两个环境、无限请求。SDK、分析仪表板、发布日历、Slack 通知和所有其他功能都包含在无尽的免费计划中。
* [Statsig](https://www.statsig.com) - 用于功能管理、A/B 测试、分析等的强大平台。其慷慨的免费计划提供无限的席位、标志、实验和动态配置，每月支持多达 100 万个活动。
* [Abby](https://www.tryabby.com) - 开源功能标志和 A/B 测试。配置为代码和全类型化的 Typescript SDK。与 Next.js 和 React 等框架的强大集成。慷慨的免费套餐和廉价的扩展选项。

**[⬆️ 返回首页](#目录)**

## 字体

* [dafont](https://www.dafont.com/) - 本网站上提供的字体是其作者的财产，可以是免费软件、共享软件、演示版或公共领域。
* [Everything Fonts](https://everythingfonts.com/) - 提供多种工具;@font 面、单位转换器、字体添加器和字体提交器。
* [Font Squirrel](https://www.fontsquirrel.com/) - 获得商业工作许可的免费字体。手工选择这些字体并以易于使用的格式呈现它们。
* [Google 字体](https://fonts.google.com/) \- 许多免费字体可以通过下载或指向 Google CDN 的链接轻松快速地安装在网站上。
* [FontGet](https://www.fontget.com/) - 有多种字体可供下载，并使用标签整齐地排序。
* [Fontshare](https://www.fontshare.com/) - 是一项免费的字体服务。这是一个不断增长的专业级字体集合，100% 免费供个人和商业使用。
* [Befonts](https://befonts.com/) - 提供多种独特的字体供个人或商业用途。
* [网页字体](https://fontofweb.com/) \- 识别网站上使用的所有字体及其使用方式。
* [兔子](https://fonts.bunny.net)以隐私为导向的 Google 字体
* [FontsKey](https://www.fontskey.com/) - 提供免费和商业付费字体供个人使用，并可输入文本进行快速过滤。
* [fonts.xz.style](https://fonts.xz.style/) 免费开源服务，用于使用 CSS 将字体系列交付到网站。
* [字体老师](https://fontsensei.com/)由用户标记的开源 Google 字体。带有 CJK（中文、日文、韩文）字体标签。

**[⬆️ 返回首页](#目录)**

## 形式

* [Feathery](https://feathery.io) - 功能强大、对开发人员友好的表单生成器。构建注册和登录、用户入职、支付流程、复杂的财务应用程序等。免费计划允许每月最多提交 250 次和五个活动表格。
* [表单数据](https://form-data.com) \- 无代码表单后端。垃圾邮件过滤器、电子邮件通知和自动回复、Webhook、zapier、重定向、AJAX 或 POST 等。免费计划提供无限的表单、每月 20 次提交以及额外的 2000 次带有表单数据徽章的提交。
* [FabForm](https://fabform.io/) - 面向智能开发人员的表单后端平台。免费计划每月允许提交 250 个表单。友好的现代 GUI。与 Google 表格、Airtable、Slack、电子邮件等集成。
* [Form.taxi](https://form.taxi/) — HTML 表单提交的端点。具有通知、垃圾邮件拦截器和符合 GDPR 的数据处理功能。基本使用的免费计划。
* [Formcarry.com](https://formcarry.com) - HTTP POST 表单端点，免费计划允许每月提交 100 次。
* [formingo.co](https://www.formingo.co/)\- 静态网站的简单 HTML 表单。您无需注册帐户即可免费开始。免费计划允许每月提交 500 次和可自定义的回复电子邮件地址。
* [FormKeep.com](https://www.formkeep.com/) - 无限表单，每月提交 50 次、垃圾邮件防护、电子邮件通知以及可以导出 HTML 的拖放式设计器。其他功能包括自定义字段规则、团队以及与 Google 表格、Slack、ActiveCampaign 和 Zapier 的集成。
* [formlets.com](https://formlets.com/) — 在线表单、每月无限制的单页表单、每月 100 次提交、电子邮件通知。
* [formspark.io](https://formspark.io/) - 表格到电子邮件服务，免费计划允许无限表格，每月提交 250 次，由客户帮助团队提供支持。
* [Formspree.io](https://formspree.io/) — 使用 HTTP POST 请求发送电子邮件。免费套餐限制每个表单每月提交 50 次。
* [Formsubmit.co](https://formsubmit.co/) — HTML 表单的简单表单端点。永远免费。无需注册。
* [Formlick.com](https://formlick.com) - 终身优惠的 Typeform 替代品。用户可以创建 1 个免费表格并接收无限次提交。在高级版中，用户可以创建无限的表单和无限的提交。
* [getform.io](https://getform.io/) - 面向设计师和开发人员的表单后端平台，1 个表单，50 次提交，单个文件上传，100MB 文件存储。
* [HeroTofu.com](https://herotofu.com/) - 具有机器人检测和加密存档的表单后端。通过 UI 将提交内容转发到电子邮件、Slack 或 Zapier。使用您自己的前端。不需要服务器代码。免费计划每月提供无限的表格和 100 次提交。
* [HeyForm.net](https://heyform.net/) - 拖放在线表单生成器。免费套餐可让您创建无限的表单并收集无限的提交内容。带有预构建模板、反垃圾邮件和 100MB 文件存储。
* [Tally.so](https://tally.so/) - 99% 的所有功能都是免费的。免费套餐可让您拥有：无限的表单、无限的提交、电子邮件通知、表单逻辑、收款、文件上传、自定义感谢页面等等。
* [Hyperforms.app](https://hyperforms.app/) — 在几秒钟内创建一个用于电子邮件的表单等，无需后端代码。个人帐户每月最多可免费提交 50 次表单。
* [Kwes.io](https://kwes.io/) - 功能丰富的表单端点。适用于静态站点。免费计划包括最多 1 个网站，每月最多提交 50 次。
* [Pageclip](https://pageclip.co/) - 免费计划允许一个站点、一个表单和每月 1,000 次提交。
* [Qualtrics 调查](https://qualtrics.com/free-account) — 使用这个一流的工具创建专业的表格和调查。50+ 专家设计的调查模板。免费帐户限制为 1 个活动调查、100 个响应/调查和 8 种响应类型。
* [Screeb](https://screeb.app/) - 用于解码用户行为的应用内调查和产品分析。永久免费计划允许 500 个每月活跃用户、无限的响应和事件、许多集成、导出和定期报告。
* [smartforms.dev](https://smartforms.dev/) - 为您的网站提供强大而简单的表单后端，永久免费计划允许每月提交 50 次、250MB 文件存储、Zapier 集成、CSV/JSON 导出、自定义重定向、自定义响应页面、Telegram 和 Slack 机器人、单封电子邮件通知。
* [Survicate](https://survicate.com/) — 从所有来源提取反馈，并使用一种工具发送后续调查。利用 AI 自动分析反馈并提取见解。免费电子邮件、网站、产品内或移动调查、AI 调查创建者和 25 个月回复。
* [staticforms.xyz](https://www.staticforms.xyz/) - 免费集成 HTML 表单，无需任何服务器端代码。用户提交表单后，将向您注册的地址发送一封包含表单内容的电子邮件。
* [stepFORM.io](https://stepform.io) - 测验和表单生成器。免费计划有五种表格，每个表格最多 3 个步骤，每月 50 个回复。
* [Typeform.com](https://www.typeform.com/) — 在网站上包含设计精美的表单。免费计划只允许每个表单有十个字段和 100 个每月回复。
* [WaiverStevie.com](https://waiverstevie.com) - 带有 REST API 的电子签名平台。您可以使用 Webhook 接收通知。免费计划为签名文档添加水印，但允许无限信封 + 签名。
* [Web3Forms](https://web3forms.com) - 静态和 JAMStack 网站的联系表单，无需编写后端代码。免费计划允许每月无限的表单、无限的域和 250 次提交。
* [WebAsk](https://webask.io) - 调查和表单生成器。免费计划每个帐户有三项调查、每月 100 份回复和每项调查十个元素。
* [Wufoo](https://www.wufoo.com/) - 在网站上使用的快速表单。免费计划每月提交的次数限制为 100 次。
* [formpost.app](https://formpost.app) - 免费、无限制的表格到电子邮件服务。免费设置自定义重定向、自动回复、Webhook 等。
* [Formester.com](https://formester.com) - 在您的网站上共享和嵌入外观独特的表单 - 对创建的表单数量或计划限制的功能没有限制。每月免费获得多达 100 份提交。
* [SimplePDF.eu](https://simplepdf.eu/embed) - 在您的网站上嵌入 PDF 编辑器，并将任何 PDF 转换为可填写的表单。免费计划允许无限的 PDF，每个 PDF 提交三个。
* [forms.app](https://forms.app/) — 创建具有条件逻辑、自动分数计算器和 AI 等强大功能的在线表单。使用免费计划收集多达 100 个回复，将您的表单嵌入到网站上，或通过链接使用它们。
* [Qualli](https://usequalli.com) - 应用内调查，专为移动设备设计。使用 Qualli AI 制作完美的问题。您可以在我们的免费计划中试用它，最高可达 500 MAU，创建无限的表单和触发器。
* [Sprig](https://sprig.com/) - 每月 1 次产品内调查或带重播的调查，具有 GPT 支持的 AI 分析。
* [feedback.fish](https://feedback.fish/) - 免费计划允许收集总共 25 个反馈提交。易于与提供的 React 和 Vue 组件集成。
* [Vidhook](https://vidhook.io/) - 使用具有高回复率的令人愉快的调查收集反馈。免费计划包括 1 个活动调查、每个调查 25 个回复和可自定义的模板。

**[⬆️ 返回首页](#目录)**

## 生成式人工智能

* [Zenable](https://zenable.io) - 使用策略即代码构建的护栏，即时自动修复 Cursor、Windsurf 和 Copilot 等工具的输出，以满足公司的质量和合规性标准。免费层包括每天对 MCP 服务器的 100 次工具调用，以及每天通过 GitHub 应用程序进行 25 次免费自动拉取请求审查。
* [关键词 AI](https://keywordsai.co) - 最好的 LLM 监控平台。一种格式，用 2 行代码调用 200+ 个 LLM。每月 10,000 个免费请求，平台功能 0 美元！
* [Portkey](https://portkey.ai/) - 用于 Gen AI 应用程序的控制面板，具有可观测性套件和 AI 网关。每月免费发送和记录多达 10,000 个请求。
* [Braintrust](https://www.braintrustdata.com/) - 生成式 AI 的评估、提示场和数据管理。免费计划每周提供多达 1,000 个私有评估行。
* [Findr](https://www.usefindr.com/) - 通用搜索，可让您一次搜索所有应用程序。搜索助手，可让您使用您的信息回答问题。免费计划提供无限制的统一搜索和 5 个每日副驾驶查询。
* [ReportGPT](https://ReportGPT.app) - 人工智能驱动的写作助手。整个平台都是免费的，只要您带上自己的 API 密钥。
* [Clair](https://askclair.ai/) - 临床人工智能参考。学生可以免费使用专业工具套件，其中包括开放搜索、临床摘要、医学审查、药物相互作用、ICD-10 代码和管理。此外，还可以免费试用专业套件。
* [Langtrace](https://langtrace.ai) - 使开发人员能够跟踪、评估、管理提示和数据集，并调试与 LLM 应用程序性能相关的问题。它为任何 LLM 创建开放的遥测标准跟踪，这有助于可观测性并可与任何可观测性客户端配合使用。免费计划提供 50K 跟踪/月。
* [LangWatch](https://langwatch.ai) - 一个 LLMOps 平台，帮助 AI 团队测量、监控和优化 LLM 应用程序，以提高可靠性、成本效益和性能。借助强大的 DSPy 组件，我们支持工程师和非技术团队之间的无缝协作，以微调和生产 GenAI 产品。免费计划包括所有平台功能、1k 跟踪/月和 1 个工作流程 DSPy 优化器。[#opensource](https://github.com/langwatch/langwatch)
* [Comet Opik](https://www.comet.com/site/products/opik/) - 在开发和生产生命周期中评估、测试和交付 LLM 应用程序。[#opensource](https://github.com/comet-ml/opik/)
* [Langfuse](https://langfuse.com/) - 开源 LLM 工程平台，可帮助团队协作调试、分析和迭代其 LLM 应用程序。永久免费计划包括每月 50k 观察和所有平台功能。[#opensource](https://github.com/langfuse/langfuse)
* [Pollinations.AI](https://pollinations.ai/) - 易于使用的免费图像生成 AI，提供免费 API。无需注册或 API 密钥，并且有多个选项可集成到网站或工作流程中。[#opensource](https://github.com/pollinations/pollinations)
* [Othor AI](https://othor.ai/) - 一种 AI 原生快速、简单且安全的替代方案，可替代流行的商业智能解决方案，如 Tableau、Power BI 和 Looker。Othor 利用大型语言模型 （LLM） 在几分钟内交付定制商业智能解决方案。永久免费计划为一个用户提供一个工作区和五个数据源连接，对分析没有限制。[#opensource](https://github.com/othorai/othor.ai)
* [OpenRouter](https://openrouter.ai/models?q=free) - 提供各种免费的 AI 模型，包括 DeepSeek R1、V3、Llama 和 Moonshot AI。这些模型在自然语言处理方面表现出色，适合多样化的开发需求。请注意，虽然这些模型可以免费使用，但它们受到速率限制。此外，OpenRouter 还提供付费模型来满足更高级的要求，例如 Claude、OpenAI、Grok、Gemini 和 Nova。
* [Mediaworkbench.ai](https://mediaworkbench.ai) - MediaWorkbench.ai 为 Azure OpenAI、DeepSeek 和 Google Gemini 模型提供 100,000 个免费单词，使用户能够访问用于代码生成、深入研究和图像创建的强大工具。
* [音频增强器](https://voice-clone.org/tools/audio-enhancer) — 人工智能驱动的音频增强器 SaaS，可消除噪音和回声，同时保持自然的声音清晰度。完全免费：无限一键增强，无需登录，支持 MP3/WAV/FLAC

**[⬆️ 返回首页](#目录)**

## CDN 和保护

* [bootstrapcdn.com](https://www.bootstrapcdn.com/) — 用于引导、引导和 fontawesome.io 的 CDN
* [cdnjs.com](https://cdnjs.com/) — 简单。快。可靠。最好的内容交付。cdnjs 是一种免费的开源 CDN 服务，受到超过 11% 的网站的信任，由 Cloudflare 提供支持。
* [developers.google.com](https://developers.google.com/speed/libraries/) — Google 托管库是最受欢迎的开源 JavaScript 库的内容分发网络
* [Stellate](https://stellate.co/) - Stellate 是一款适用于 GraphQL API 的超快速、可靠的 CDN，并且对两项服务免费。
* [jsdelivr.com](https://www.jsdelivr.com/) — 一个免费、快速且可靠的开源 CDN。支持 npm、GitHub、WordPress、Deno 等。
* [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) — Microsoft Ajax CDN 托管流行的第三方 JavaScript 库，例如 jQuery，并使您能够轻松地将它们添加到 Web 应用程序中
* [ovh.ie](https://www.ovh.ie/ssl-gateway/) — 免费 DDoS 保护和 SSL 证书
* [Skypack](https://www.skypack.dev/) — 100% 原生 ES 模块 JavaScript CDN。每个域每月 100 万个请求免费。
* [raw.githack.com](https://raw.githack.com/) — 现代替代 **rawgit.com**，使用 Cloudflare 简单地托管文件
* [section.io](https://www.section.io/) — 一种启动和管理完整 Varnish Cache 解决方案的简单方法。据称，一个站点永久免费
* [statically.io](https://statically.io/) — 用于 Git 存储库（GitHub、GitLab、Bitbucket）、WordPress 相关资产和图像的 CDN
* [toranproxy.com](https://toranproxy.com/) — Packagist 和 GitHub 的代理。永远不会失败 CD。免费供个人使用，一个开发人员，不支持
* [UNPKG](https://unpkg.com/) — npm 上所有内容的 CDN
* [weserv](https://images.weserv.nl/) — 图像缓存和调整大小服务。使用全球缓存动态作图像。
* [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) — 免费 DDoS 保护
* [Gcore](https://gcorelabs.com/) 全球内容交付网络，每月 1 TB 和 100 万个请求免费和免费 DNS 托管
* [CacheFly](https://portal.cachefly.com/signup/free2023) - 每月高达 5 TB 的免费 CDN 流量、19 个核心 PoP、1 个域和通用 SSL。

**[⬆️ 返回首页](#目录)**

## PaaS

* [anvil.works](https://anvil.works) - 除了 Python 之外什么都没有的 Web 应用程序开发。免费套餐，具有无限应用程序和 30 秒超时。
* [appwrite](https://appwrite.io) - 无限项目，没有项目暂停（支持 websockets）和身份验证服务。免费套餐中每个项目 1 个数据库、3 个存储桶、5 个函数。
* [configure.it](https://www.configure.it/) — 移动应用开发平台，两个项目免费，功能有限，但无资源限制
* [codenameone.com](https://www.codenameone.com/) — 面向 Java/Kotlin 开发人员的开源、跨平台、移动应用开发工具链。免费用于商业用途，项目数量不限
* [deco.cx](https://www.deco.cx/en/dev) - 边缘原生前端平台，具有从 TypeScript 代码自动生成的可视化 CMS。内置 A/B 测试、内容细分和实时分析。非常适合内容繁重的企业电子商务网站。每月免费最多 5k 页面浏览量或开源/个人项目。
* [Deno Deploy](https://deno.com/deploy) - 在全球边缘运行 JavaScript、TypeScript 和 WebAssembly 的分布式系统。免费套餐包括每天 100,000 个请求和每月 100 GiB 的数据传输。
* [domcloud.co](https://domcloud.co) – Linux 托管服务，提供带有 GitHub、SSH 和 MariaDB/Postgres 数据库的 CI/CD。免费版本有 1 GB 存储空间和 1 GB 网络/月限制，并且仅限于免费域。
* [encore.dev](https://encore.dev/) — 使用静态分析的后端框架，提供自动基础设施、无样板代码等。包括业余爱好项目的免费云托管。
* [flightcontrol.dev](https://flightcontrol.dev/) - 使用 Git 推送式工作流程在您自己的 AWS 账户上部署 Web 服务、数据库等。免费套餐适用于在个人 GitHub 存储库上拥有 1 名开发人员的用户。AWS 成本通过 AWS 计费，但您可以使用积分和 AWS 免费套餐。
* [gigalixir.com](https://gigalixir.com/) - Gigalixir 提供一个永不休眠的免费实例和一个免费层 PostgreSQL 数据库，限制为 2 个连接、10， 000 行，并且没有 Elixir/Phoenix 应用程序的备份。
* [leapcell](https://leapcell.io/) - Leapcell 是一个可靠的分布式应用平台，提供无缝支持快速增长所需的一切。免费计划包括 100k 服务调用、10k 异步任务和 100k Redis 命令。
* [pipedream.com](https://pipedream.com) - 专为开发人员构建的集成平台。基于任何触发器开发任何工作流程。工作流是可以[免费](https://docs.pipedream.com/pricing/)运行的代码。无需管理服务器或云资源。
* [pythonanywhere.com](https://www.pythonanywhere.com/) — Cloud Python 应用托管。初学者帐户是免费的，your-username.pythonanywhere.com 域有 1 个 Python Web 应用程序，512 MB 私有文件存储，一个 MySQL 数据库
* [ampt.dev](https://getampt.com/) - Ampt 允许团队在 AWS 上构建、部署和扩展 JavaScript 应用程序，而无需复杂的配置或管理基础设施。免费预览版计划包括每小时 500 次调用、每天 2,500 次调用和每月 50,000 次调用。自定义域仅在付费计划中允许使用。
* [Koyeb](https://www.koyeb.com) - Koyeb 是一个对开发人员友好的无服务器平台，用于在全球范围内部署应用程序。通过基于 Git 的部署、本机自动缩放、全球边缘网络以及内置服务网格和发现，无缝运行 Docker 容器、Web 应用和 API。免费实例允许您在德国法兰克福或美国华盛顿特区部署 Web 服务。在法兰克福（德国）、华盛顿特区（美国）和新加坡提供免费的托管 Postgres 数据库。512MB 内存、2GB 存储空间和 0.1 CPU。
* [Napkin](https://www.napkin.io/) - 具有 500Mb 内存、默认超时 15 秒和每月 5,000 次免费 API 调用的 FaaS，速率限制为 5 次/秒。
* [流星云](https://www.meteor.com/cloud) — Galaxy 托管。Meteor 的 Meteor 应用程序平台即服务包括免费的 MongoDB 共享主机和自动 SSL。
* [Northflank](https://northflank.com) — 使用强大的 UI、API 和 CLI 构建和部署微服务、作业和托管数据库。从版本控制和外部 Docker 注册表无缝扩展容器。免费套餐包括两个服务、两个 cron 作业和 1 个数据库。
* [YepCode](https://yepcode.io) - 在无服务器环境中连接 API 和服务的一体化平台。它带来了 NoCode 工具的所有敏捷性和优势，但具有使用编程语言的所有功能。免费套餐包括 [1.000 个 yeps](https://yepcode.io/pricing/)。
* [WunderGraph](https://cloud.wundergraph.com) - 一个开源平台，允许您快速构建、交付和管理现代 API。内置 CI/CD、GitHub 集成和自动 HTTPS。 [免费计划](https://wundergraph.com/pricing)最多 3 个项目，1GB 出口，每月 300 分钟的构建时间
* [Zeabur](https://zeabur.com) - 一键部署您的服务。三项服务免费，每月 5 美元免费积分。
* [mogenius](https://mogenius.com) - 在 Kubernetes 上轻松构建、部署和运行服务。免费套餐支持将本地 Kubernetes 与 mogenius 连接起来，使个人开发人员能够在他们的机器上创建类似生产的测试环境。
* [DeployApps](https://deployapps.dev/) - 无服务器函数提供程序每月免费提供 100 万次函数调用、100GB 带宽和 10 个 cron 作业，专门用于非商业或学术用途。

**[⬆️ 返回首页](#目录)**

## BaaS

* [Activepieces](https://www.activepieces.com) - 构建自动化流，以在应用的后端将多个应用连接在一起。例如，在您的应用中触发事件时发送 Slack 消息或添加 Google 表格行。每月最多免费 5,000 个任务。
* [back4app.com](https://www.back4app.com) - Back4App 是一个基于 Parse Platform 的易于使用、灵活且可扩展的后端。
* [backendless.com](https://backendless.com/) — 移动端和 Web Baas，免费 1 GB 文件存储，推送通知 50,000 条/月，表中有 1000 个数据对象。
* [bismuth.cloud](https://www.bismuth.cloud/) — 我们的 AI 将在我们的函数运行时和托管存储上增强您的 Python API，在我们的在线编辑器中免费构建和托管，或使用您最喜欢的工具在本地构建和托管。
* [BMC 开发人员计划](https://developers.bmc.com/site/global/bmc_helix_platform/program/overview/index.gsp) — BMC 开发人员计划提供文档和资源，用于为您的企业构建和部署数字创新。访问全面的个人沙盒，其中包括平台、SDK 和可用于构建和定制应用程序的组件库。
* [connectycube.com](https://connectycube.com) - 无限聊天消息、p2p 语音和视频通话、文件附件和推送通知。最多 1000 个用户的应用程序免费。
* [convex.dev](https://convex.dev/) - 响应式后端即服务，托管您的数据（具有关系和可序列化 ACID 事务的文档）、无服务器函数和 WebSocket，以将更新流式传输到各种客户端。小型项目免费 - 最多 1M 条记录，每月 5M 次函数调用。
* [darklang.com](https://darklang.com/) - 托管语言与编辑器和基础设施相结合。在测试期间可访问，测试后计划提供慷慨的免费套餐。
* [Firebase](https://firebase.com) — Firebase 帮助您构建和运行成功的应用程序。免费 Spark 计划提供身份验证、托管、Firebase ML、实时数据库、云存储、测试实验室。A/B 测试、分析、应用分发、应用索引、云消息传递 （FCM）、Crashlytics、动态链接、应用内消息传递、性能监控、预测和远程配置始终免费。
* [Flutter Flow](https://flutterflow.io) — 无需编写任何代码即可构建您的 Flutter 应用程序 UI。还集成了 Firebase。免费计划包括对 UI Builder 和免费模板的完全访问权限。
* [getstream.io](https://getstream.io/) — 在几个小时而不是几周内构建可扩展的应用内聊天、消息传递、视频和音频以及提要
* [hasura.io](https://hasura.io/) — Hasura 可以扩展您现有的数据库，无论它托管在何处，并提供一个即时的 GraphQL API，可以安全地访问 Web、移动和数据集成工作负载。每月 1GB 的数据直通免费。
* [nhost.io](https://nhost.io) - 用于 Web 和移动应用的无服务器后端。免费计划包括 PostgreSQL、GraphQL （Hasura）、身份验证、存储和无服务器函数。
* [onesignal.com](https://onesignal.com/) — 无限制的免费推送通知。每月发送 10,000 封电子邮件，联系人不受限制，并可访问自动预热。
* [paraio.com](https://paraio.com) — 具有灵活身份验证、全文搜索和缓存功能的后端服务 API。一个应用程序免费，1GB 应用程序数据。
* [pubnub.com](https://www.pubnub.com/) — 每月最多 100 万条消息和 100 台每日活跃设备的免费推送通知
* [pushbots.com](https://pushbots.com/) — 推送通知服务。每月最多 150 万次推送免费
* [pushcrew.com](https://pushcrew.com/) — 推送通知服务。最多 2,000 名订阅者的无限通知
* [pusher.com](https://pusher.com/beams) — 免费、无限制的推送通知，每月活跃用户 2000 人。适用于 iOS 和 Android 设备的单一 API。
* [quickblox.com](https://quickblox.com/) — 用于即时消息、视频和语音通话以及推送通知的通信后端
* [restspace.io](https://restspace.io/) - 使用身份验证、数据、文件、电子邮件 API、模板等服务配置服务器，然后组合成管道并转换数据。
* [Salesforce 开发人员计划](https://developer.salesforce.com/signup) — 使用拖放工具以闪电般的速度构建应用程序。通过点击自定义您的数据模型。使用 Apex 代码更进一步。使用强大的 API 与任何内容集成。通过企业级安全性保持保护。通过点击或任何领先的 Web 框架自定义 UI。免费开发人员计划提供对完整 Lightning 平台的访问权限。
* [simperium.com](https://simperium.com/) — 即时自动将数据移动到任何地方，多平台，无限制地发送和存储结构化数据，每月最多 2,500 个用户
* [Supabase](https://supabase.com) — 用于构建后端的开源 Firebase 替代方案。免费计划提供身份验证、实时数据库和对象存储。
* [tyk.io](https://tyk.io/) — 具有身份验证、配额、监控和分析功能的 API 管理。免费云产品
* [zapier.com](https://zapier.com/) — 连接用于自动执行任务的应用程序。每 15 分钟 5 次 zaps，每月 100 个任务
* [IFTTT](https://ifttt.com) — 自动化您喜爱的应用程序和设备。免费 2 个小程序
* [集成](https://integrately.com) — 只需单击一下即可自动执行繁琐的任务。免费 100 个任务、15 分钟更新时间、五个活动自动化、Webhook。
* [LeanCloud](https://leancloud.app/) — 移动后端。1GB 数据存储，256MB 实例，3K API 请求/天，10K 推送/天免费。（API 与 Parse Platform 非常相似）
* [Claw.cloud](https://run.claw.cloud) - 一个 PaaS 平台，为拥有 180 天以上 GitHub 帐户的用户提供每月 5 美元的免费积分。非常适合托管应用程序、数据库等。（ [带有免费信用的注册链接](https://ap-southeast-1.run.claw.cloud/signin) ）。

**[⬆️ 返回首页](#目录)**

## 低代码平台

* [appsmith](https://www.appsmith.com/) — 用于构建管理面板、内部工具和仪表板的低代码项目。与 15+ 数据库和任何 API 集成。
* [Basedash](https://www.basedash.com) — 用于构建内部管理面板和仪表板的低代码平台。支持 SQL 数据库和 REST API。
* [BudiBase](https://budibase.com/) — Budibase 是一个开源低代码平台，可在几分钟内创建内部应用程序。支持 PostgreSQL、MySQL、MSSQL、MongoDB、Rest API、Docker、K8s
* [Clappia](https://www.clappia.com) — 一个低代码平台，旨在构建具有可定制移动和 Web 应用程序的业务流程应用程序。提供拖放界面、离线支持、实时位置跟踪以及与各种第三方服务集成等功能
* [DronaHQ](https://www.dronahq.com/) — DronaHQ - 一个低代码平台，可帮助工程团队和产品经理以 10 倍的速度构建内部工具、自定义用户旅程、数字体验、自动化、自定义管理面板、运营应用程序。
* [lil'bots](https://www.lilbots.io/) - 使用免费的内置 API（如 OpenAI、Anthropic、Firecrawl 等）在线编写和运行脚本。非常适合构建 AI 代理/内部工具并与团队共享。免费套餐包括对 API、AI 编码助手和每月 10,000 个执行积分的完全访问权限。
* [西门子低代码](https://www.mendix.com/) — 面向企业的快速应用程序开发、支持总用户的无限可访问沙盒环境、每个应用程序 0.5 GB 存储空间和 1 GB RAM。此外，免费套餐中允许使用 Studio 和 Studio Pro IDE。
* [outsystems.com](https://www.outsystems.com/) — 企业 Web 开发 PaaS 适用于本地或云，免费的“个人环境”产品允许无限代码和高达 1 GB 的数据库
* [ReTool](https://retool.com/) — 用于构建内部应用程序的低代码平台。Retool 具有高度可破解性。如果你能用 JavaScript 和 API 编写它，你可以在 Retool 中制作它。免费套餐每月最多允许五个用户、无限的应用程序和 API 连接。
* [Superblocks](https://superblocks.com/) — 专为开发人员和半技术团队设计的开放式企业应用程序平台。使用 AI 生成、可视化编辑和扩展代码。通过集成、身份验证、权限和审计日志进行集中治理。
* [ToolJet](https://www.tooljet.com/) — 用于构建业务应用程序的可扩展低代码框架。连接到数据库、云存储、GraphQL、API 端点、Airtable 等，并使用拖放式应用程序构建器构建应用程序。
* [UI Bakery](https://uibakery.io) — 低代码平台，可以更快地构建自定义 Web 应用程序。支持使用拖放构建 UI，并通过 JavaScript、Python 和 SQL 进行高度自定义。可作为云和自托管解决方案使用。最多 5 位用户免费。
* [manubes](https://www.manubes.com) - 强大的无代码云平台，专注于工业生产管理。每月有 100 万次工作流活动的用户免费（ [也提供德语版本](https://www.manubes.de) ）。

**[⬆️ 返回首页](#目录)**

## 虚拟主机

* [Alwaysdata](https://www.alwaysdata.com/) — 100 MB 免费网络托管，支持 MySQL、PostgreSQL、CouchDB、MongoDB、PHP、Python、Ruby、Node.js、Elixir、Java、Deno、自定义 Web 服务器，通过 FTP、WebDAV 和 SSH 访问;包括邮箱、邮件列表和应用程序安装程序。
* [Awardspace.com](https://www.awardspace.com) — 免费虚拟主机 + 免费短域、PHP、MySQL、应用程序安装程序、电子邮件发送和无广告。
* [Bohr](https://bohr.io) — 非商业项目免费 + 开发人员优先的部署和开发平台，可最大限度地减少基础设施麻烦并加快设置速度。
* [Bubble](https://bubble.io/) — 可视化编程，无需代码即可构建 Web 和移动应用程序，免费使用 Bubble 品牌。
* [dAppling Network](https://www.dappling.network/) - 用于 Web3 前端的去中心化网络托管平台，专注于增加正常运行时间和安全性，并为用户提供额外的接入点。
* [DigitalOcean](https://www.digitalocean.com/pricing) - 在应用平台入门层上免费构建和部署三个静态站点。
* [Drive To Web](https://drv.tw) — 从 Google Drive 和 OneDrive 直接托管到 Web。仅静态站点。永远免费。每个 Google/Microsoft 帐户一个站点。
* [Fenix Web Server](https://preview.fenixwebserver.com) - 一个开发人员桌面应用程序，用于在本地托管站点并公开（实时）共享它们。使用其漂亮的用户界面、API 和/或 CLI 随心所欲地工作。
* [免费托管](https://freehostingnoads.net/) — 使用 PHP 5、Perl、CGI、MySQL、FTP、文件管理器、POP 电子邮件、免费子域、免费域名托管、DNS 区域编辑器、网站统计、免费在线支持以及其他免费主机未提供的更多功能进行免费托管。
* [Freehostia](https://www.freehostia.com) — FreeHostia 提供免费托管服务，包括业界最佳的控制面板和 1 键安装 50+ 免费应用程序。即时设置。没有强制广告。
* [HelioHost](https://heliohost.org) — 非营利性免费虚拟主机，配备 Plesk 控制面板、PHP、Node.js、Python、Django、Flask、.NET、Perl、CGI、MySQL、PostgreSQL、SQLite、IMAP/POP3/SMTP 电子邮件、无限带宽、免费子域、免费 1000 MB 存储空间，可选择升级。
* [Kinsta 静态站点托管](https://kinsta.com/static-site-hosting/) — 使用 SSL 免费部署多达 100 个静态站点、自定义域、100 GB 每月带宽、260+ Cloudflare CDN 位置。
* [Lecturify](https://www.lecturify.net/index.en.html) - 具有 SFPT 访问权限的虚拟主机，用于文件上传和下载，提供 php。
* [Neocities](https://neocities.org) — 静态、1 GB 免费存储和 200 GB 带宽。
* [Netlify](https://www.netlify.com/) — 免费构建、部署和托管静态站点/应用程序，提供 100 GB 数据和 100 GB/月带宽。
* [PandaStack](https://www.pandastack.io/) — 开发人员的生态系统包括不同格式的网络托管（静态网络托管、基于容器的虚拟托管、wordpress 和许多其他托管应用程序，只需单击几下即可使用）。一个免费的虚拟主机（静态或容器）和一个具有 100GB 带宽和 300 分钟/月构建分钟的免费数据库。
* [pantheon.io](https://pantheon.io/) — Drupal 和 WordPress 托管、自动化 DevOps 和可扩展的基础设施。对开发商和代理机构免费。没有自定义域。
* [readthedocs.org](https://readthedocs.org/) — 免费文档托管，提供版本控制、PDF 生成等功能
* [render.com](https://render.com) — 统一云，使用免费 SSL、全球 CDN、专用网络、Git 自动部署以及 Web 服务、数据库和静态网页的完全免费计划来构建和运行应用程序和站点。
* [SourceForge](https://sourceforge.net/) — 免费查找、创建和发布开源软件
* [surge.sh](https://surge.sh/) — 面向前端开发人员的静态 Web 发布。具有自定义域支持的无限站点
* [telegra.ph](https://telegra.ph/) 使用 Quill 轻松创建网页
* [tilda.cc](https://tilda.cc/) — 一个站点，50 页，50 MB 存储空间，只有 170+ 可用的主要预定义块，没有字体，没有网站图标，也没有自定义域
* [Vercel](https://vercel.com/) — 每次 `git push` 时，使用免费 SSL、全局 CDN 和唯一的预览 URL 构建、部署和托管 Web 应用程序。非常适合 Next.js 和其他静态站点生成器。
* [Versoly](https://versoly.com/) — 专注于 SaaS 的网站构建器 - 无限的网站、70+ 块、五个模板、自定义 CSS、网站图标、SEO 和表单。没有自定义域。
* [Qoddi](https://qoddi.com) - 类似于 Heroku 的 PaaS 服务，具有以开发人员为中心的方法和包罗万象的功能。静态资产、暂存和开发人员应用的免费层。
* [FreeFlarum](https://freeflarum.com/) - 社区支持的免费 Flarum 托管，最多可容纳 250 名用户（捐款以去除页脚中的水印）。
* [MDB GO](https://mdbgo.com/) - 一个项目免费托管，具有两周的容器 TTL，每个项目 500 MB RAM，SFTP - 1G 磁盘空间。
* [帕特云](https://patr.cloud/) — 一个易于使用的云平台，在其付费服务中，它免费提供三个静态站点。
* [Serv00.com](https://serv00.com/) — 3 GB 免费虚拟主机，每日备份（7 天）。支持：Crontab 作业、SSH 访问、存储库（GIT、SVN 和 Mercurial），支持：MySQL、PostgreSQL、MongoDB、PHP、Node.js、Python、Ruby、Java、Perl、TCL/TK、Lua、Erlang、Rust、Pascal、C、C++、D、R 等等。

* [Sevalla](https://sevalla.com/) - 托管平台，旨在简化应用程序、数据库和静态网站的部署和管理 - 1GB 站点限制、100GB 免费带宽、600 免费构建分钟、每个帐户 100 个站点。

**[⬆️ 返回首页](#目录)**

## 域名系统

* [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - 免费的公共 DNS 解析器，快速且安全（加密您的 DNS 查询），由 Cloudflare 提供。对于绕过互联网提供商的 DNS 阻止、防止 DNS 查询间谍以及[阻止成人和恶意软件内容](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families)很有用。它也[可以通过 API 使用](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests) 。注意：只是一个 DNS 解析器，而不是 DNS 托管商。
* [1984.is](https://www.1984.is/product/freedns/) — 免费 DNS 服务，包含 API 和许多其他免费 DNS 功能。
* [cloudns.net](https://www.cloudns.net/) — 免费 DNS 托管多达 1 个域和 50 条记录
* [deSEC](https://desec.io) - 免费 DNS 托管，支持 API，设计时考虑到了安全性。在开源软件上运行，并受 [SSE](https://www.securesystems.de/) 支持。
* [dns.he.net](https://dns.he.net/) — 支持动态 DNS 的免费 DNS 托管服务
* [Zonomi](https://zonomi.com/) — 具有即时 DNS 传播功能的免费 DNS 托管服务。免费计划：1 个 DNS 区域（域名），最多 10 条 DNS 记录。
* [dnspod.com](https://www.dnspod.com/) — 免费 DNS 托管。
* [duckdns.org](https://www.duckdns.org/) — 免费套餐中最多有 5 个域的免费 DDNS。带有各种设置的配置指南。
* [Dynv6.com](https://dynv6.com/) — 免费的 DDNS 服务，支持 [API 并](https://dynv6.com/docs/apis)管理许多 DNS 记录类型（如 CNAME、MX、SPF、SRV、TXT 等）。
* [freedns.afraid.org](https://freedns.afraid.org/) — 免费 DNS 托管。此外，提供基于众多公共用户[贡献域](https://freedns.afraid.org/domain/registry/)的免费子域。注册后从“子域”菜单获取免费子域。
* [luadns.com](https://www.luadns.com/) — 免费 DNS 托管，三个域，所有功能都有合理的限制
* [namecheap.com](https://www.namecheap.com/domains/freedns/) — 免费 DNS。域数量无限制
* [nextdns.io](https://nextdns.io) - 基于 DNS 的防火墙，每月 300K 免费查询
* [noip.at](https://noip.at/) — 免费的 DDNS 服务，无需注册、跟踪、日志记录或广告。域无限制。
* [noip](https://www.noip.com/) — 一种动态 DNS 服务，最多允许 3 个主机名空闲，每 30 天确认一次
* [sslip.io](https://sslip.io/) — 免费 DNS 服务，当使用带有嵌入式 IP 地址的主机名进行查询时，该服务将返回该 IP 地址。
* [zilore.com](https://zilore.com/en/dns) — 5 个域的免费 DNS 托管。
* [zoneedit.com](https://www.zoneedit.com/free-dns/) — 免费 DNS 托管，支持动态 DNS。
* [zonewatcher.com](https://zonewatcher.com) — 自动备份和 DNS 更改监控。一个域名免费
* [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) – 华为免费 DNS 托管
* [赫茨纳](https://www.hetzner.com/dns-console) – Hetzner 的免费 DNS 托管，支持 API。
* [Glauca](https://docs.glauca.digital/hexdns/) – 最多 3 个域的免费 DNS 托管和 DNSSEC 支持
* [VolaryDDNS](https://volaryddns.net) - 免费的高性能 DDNS，无需订阅或广告
* [LocalCert](https://localcert.net) - 与公共 CA 兼容的免费 `.localcert.net` 子域，可在专用网络中使用

**[⬆️ 返回首页](#目录)**

## 域

* [pp.ua](https://nic.ua/) — 免费 pp.ua 子域。
* [us.kg](https://nic.us.kg/) - 免费 us.kg 子域。

**[⬆️ 返回首页](#目录)**

## IaaS

* [4EVERLAND](https://www.4everland.org/) — 兼容 AWS S3 - API、接口作、CLI 等上传方式，安全、便捷、高效地上传和存储来自 IPFS 和 Arweave 网络的文件。注册用户可以免费获得 6 GB 的 IPFS 存储空间和 300MB 的 Arweave 存储空间。任何小于 150 KB 的 Arweave 文件上传都是免费的。
* [backblaze.com](https://www.backblaze.com/b2/) — Backblaze B2 云存储。无限时间免费 10 GB（类似 Amazon S3）对象存储
* [filebase.com](https://filebase.com/) - 由区块链提供支持的 S3 兼容对象存储。5 GB 免费存储空间，无限期。
* [Tebi](https://tebi.io/) - S3 兼容对象存储。免费 25 GB 存储空间和 250GB 出站传输。
* [Idrive e2](https://www.idrive.com/e2/) - S3 兼容对象存储。每月 10 GB 免费存储空间和 10 GB 下载带宽。
* [C2 对象存储](https://c2.synology.com/en-us/pricing/object-storage) \- S3 兼容对象存储。每月 15 GB 免费存储空间和 15 GB 下载量。

**[⬆️ 返回首页](#目录)**

## 托管数据服务

* [Aiven](https://aiven.io/) - Aiven 在其开源数据平台上提供免费的 PostgreSQL、MySQL 和 Valkey（兼容 Redis）计划。单节点，1 个 CPU，1GB RAM，对于 PostgreSQL 和 MySQL，1GB 存储。轻松迁移到更广泛的计划或跨云。
* [airtable.com](https://airtable.com/) — 看起来像一个电子表格，但它是一个关系数据库，无限基数，1,200 行/基，1,000 个 API 请求/月
* [Astra](https://www.datastax.com/products/datastax-astra/) — 具有 [80GB 免费套餐](https://www.datastax.com/products/datastax-astra/pricing)的云原生 Cassandra 即服务
* [codehooks.io](https://codehooks.io/) — 易于使用的 JavaScript 无服务器 API/后端和 NoSQL 数据库服务，具有函数、Mongdb 式查询、键/值查找、作业系统、实时消息、工作队列、强大的 CLI 和基于 Web 的数据管理器。免费计划有 5GB 存储空间和每分钟 60/API 调用。包括 2 名开发人员。无需信用卡。
* [CrateDB](https://crate.io/) - 用于实时分析的分布式开源 SQL 数据库。 [免费层 CRFREE：](https://crate.io/lp-crfree) 具有 2 个 CPU、2 GiB 内存和 8 GiB 存储的单节点。每个组织一个集群，无需付款方式。
* [Upstash](https://upstash.com/) — 无服务器 Redis，免费套餐每天最多 10,000 个请求，最大数据库大小 256MB，并发连接 20 个
* [Couchbase Capella](https://www.couchbase.com/products/capella/) - 部署一个永久免费层的完全托管数据库集群，专为开发人员构建，以创建跨 IoT 到 AI 的下一代应用程序
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) — 免费套餐提供 512 MB
* [redsmin.com](https://www.redsmin.com/) — Redis 在线实时监控管理服务，免费监控 1 个 Redis 实例
* [redislabs](https://redislabs.com/try-free/) - 免费 30MB redis 实例
* [MemCachier](https://www.memcachier.com/) — 托管 Memcache 服务。免费提供高达 25MB、1 个代理服务器和基本分析
* [scalingo.com](https://scalingo.com/) — 主要是 PaaS，但提供 128MB 到 192MB 的 MySQL、PostgreSQL 或 MongoDB 免费套餐
* [SeaTable](https://seatable.io/) — 由 Seafile 团队构建的灵活、类似电子表格的数据库。无限表，2,000 行，1 个月版本控制，最多 25 名团队成员。
* [skyvia.com](https://skyvia.com/) — Cloud Data Platform 提供免费套餐，所有计划在测试期间都是完全免费的
* [StackBy](https://stackby.com/) — 一种工具，结合了电子表格的灵活性、数据库的强大功能以及与您喜爱的业务应用程序的内置集成。免费计划包括无限用户、十个堆栈和每个堆栈 2GB 的附件。
* [TiDB Cloud](https://en.pingcap.com/tidb-cloud/) — TiDB 是一个开源的兼容 MySQL 的分布式 HTAP RDBMS。TiDB Serverless 每月免费提供 5GB 行存储、5GB 列存储和 5000 万个请求单位 （RU）。
* [ChiselStrike 的 Turso](https://chiselstrike.com/) - Turso 是边缘数据库中的 SQLite 开发人员体验。Turso 提供永久免费入门计划、9 GB 总存储空间、多达 500 个数据库、最多 3 个位置、每月 10 亿行读取以及 SQLite 的本地开发支持。
* [InfluxDB](https://www.influxdata.com/) — 时间序列数据库，免费写入时间高达 3MB/5 分钟，读取时间长达 30MB/5 分钟，基数系列为 10,000 个
* [restdb.io](https://restdb.io/) - 一种快速、简单的 NoSQL 云数据库服务。通过 restdb.io，您可以获得模式、关系、自动 REST API（具有类似 MongoDB 的查询）以及用于处理数据的高效多用户管理 UI。免费计划允许每秒 3 个用户、2500 条记录和 1 个 API 请求。
* [CockroachDB Cloud](https://www.cockroachlabs.com/pricing/) — 免费套餐每月免费提供 5000 万 RU 和 10 GiB 存储（相当于 15 美元）。（ [什么是请求单位](https://www.cockroachlabs.com/docs/cockroachcloud/metrics-request-units.html) ）
* [Neo4j Aura](https://neo4j.com/cloud/aura/) — 托管原生图形 DBMS/分析平台，具有 Cypher 查询语言和 REST API。图大小限制（50k 节点，175k 关系）。
* [Neon](https://neon.tech/) — 托管 PostgreSQL、0.5 GB 存储（总计）、1 个项目、10 个分支、无限数据库、始终可用的主分支（5 分钟后自动挂起）、非主分支计算每月 20 小时的活动时间（总计）。
* [Prisma Postgres](https://prisma.io/postgres) - 基于单内核构建的超快速托管 Postgres，运行在裸机、1GB 存储、10 个数据库上，与 Prisma ORM 集成。
* [Dgraph Cloud](https://cloud.dgraph.io/pricing?type=free) — 使用 GraphQL API 的托管本机 Graph DBMS。每天数据传输限制为 1 MB。
* [Tinybird](https://tinybird.co) - 一个无服务器托管的 ClickHouse，通过 HTTP 进行无连接数据摄取，并允许您将 SQL 查询发布为托管 HTTP API。免费套餐没有时间限制，每天 10GB 存储 + 1000 个 API 请求。
* [TigerGraph Cloud](https://www.tigergraph.com/cloud/) — 托管的原生图形数据库管理系统/分析平台，具有类似 SQL 的图形查询语言和 REST API。一个免费实例，具有两个 vCPU、8GB 内存和 50GB 存储，在 1 小时不活动后休眠。
* [TerminusCMS](https://terminusdb.com/pricing) — TerminusDB 的托管免费服务，TerminusDB 是一个用 Prolog 和 Rust 编写的文档和图形数据库。开发人员免费，企业部署和支持付费服务。
* [filess.io](https://filess.io) - filess.io 是一个平台，您可以在其中免费创建以下 DBMS 的两个数据库，每个数据库最多 10 MB：MySQL、MariaDB、MongoDB 和 PostgreSQL。
* [xata.io](https://xata.io) - Xata 是一个无服务器数据库，内置了强大的搜索和分析功能。一个 API、多个类型安全的客户端库，并针对您的开发工作流程进行了优化。永久免费套餐对于业余开发者来说已经足够了，它附带三个 Xata 单元，请参阅网站了解单元定义。
* [8base.com](https://www.8base.com/) - 8base 是一个全栈低代码开发平台，专为 JavaScript 开发人员构建在 MySQL 和 GraphQL 之上以及无服务器后端即服务之上。它允许您使用 UI 应用程序构建器快速开始构建 Web 应用程序并快速扩展，免费层包括行：2,500、存储：500、无服务器计算：1Gb/h 和客户端应用程序用户：5。
* [Nile](https://www.thenile.dev/) — 用于 B2B 应用程序的 Postgres 平台。无限数据库，始终可用，无需关闭，1GB 存储（总计），5000 万个查询令牌，自动缩放，无限向量嵌入

**[⬆️ 返回首页](#目录)**

## 隧道、WebRTC、Web 套接字服务器和其他路由器

* [Pinggy](https://pinggy.io) — 使用单个命令即可获得本地主机的公共 URL，无需下载。HTTPS/TCP/TLS 隧道。免费计划的隧道寿命为 60 分钟。
* [conveyor.cloud](https://conveyor.cloud/) - Visual Studio 扩展，用于将 IIS Express 公开到本地网络或通过隧道公开到公共 URL。
* [Hamachi](https://www.vpn.net/) — LogMeIn Hamachi 是一项托管 VPN 服务，可让您通过免费计划安全地将类似 LAN 的网络扩展到分布式团队，该计划允许最多 5 人无限网络
* [Mirna Sockets](https://mirna.cloud/) - 免费的套接字即服务平台，在部署 Web 套接字服务器代码时为您提供 wss:// URL，还允许您监控其性能。
* [localhost.run](https://localhost.run/) — 通过隧道将本地运行的服务器公开到公共 URL。
* [localtunnel](https://theboroer.github.io/localtunnel-www/) — 通过隧道将本地运行的服务器公开到公共 URL。免费托管版本，开[源](https://github.com/localtunnel/localtunnel) 。
* [ngrok.com](https://ngrok.com/) — 通过隧道将本地运行的服务器公开到公共 URL。
* [cname.dev](https://cname.dev/) — 免费且安全的动态反向代理服务。
* [serveo](https://serveo.net/) — 将本地服务器公开给互联网。无需安装，无需注册。免费子域，无限制。
* [Radmin VPN](https://www.radmin-vpn.com/) — 通过支持 VPN 的类似 LAN 的网络将多台计算机连接在一起。无限对等。（滨町替代品）
* [segment.com](https://segment.com/) — 用于将事件转换和路由到其他第三方服务的中心。100,000 个事件/月免费
* 谷歌眩光 — stun:stun.l.google.com：19302
* Twilio 眩晕 — stun:global.stun.twilio.com：3478？transport=udp
* [Tailscale](https://tailscale.com/) — 零配置 VPN，使用开源 WireGuard 协议。安装在 MacOS、iOS、Windows、Linux 和 Android 设备上。个人使用的免费计划，有 100 台设备和三个用户。
* [webhookrelay.com](https://webhookrelay.com) — 管理、调试、扇出和代理所有 Webhook 到公共或内部（即本地主机）目的地。此外，通过获取公共 HTTP 端点 （ `https://yoursubdomain.webrelay.io <----> http://localhost:8080` ） 来公开通过隧道在专用网络中运行的服务器。
* [Hookdeck](https://hookdeck.com/pricing) — 从任何地方开发、测试和监控您的 Webhook。每月 100K 次请求和 100K 次尝试，保留三天。
* [Xirsys](https://www.xirsys.com/pricing/) — 无限 STUN 使用 + 每月 500 MB TURN 带宽，带宽上限，单个地理区域。
* [ZeroTier](https://www.zerotier.com) — FOSS 管理的虚拟以太网即服务。免费计划中 25 个客户端的无限端到端加密网络。桌面/移动/北美客户端;用于配置自定义路由规则和批准专用网络上新客户端节点的 Web 界面
* [LocalXpose](https://localxpose.io) — 反向代理，使您能够将本地主机服务器公开到互联网。免费计划的隧道寿命为 15 分钟。
* [Traefik-Hub](https://traefik.io/traefik-hub/) - 在本地发布，通过隧道将服务运行到公共自定义 URL，并通过访问控制保护它们。一个集群中的 5 项服务免费。
* [公开](https://expose.dev/) \- 通过安全隧道公开本地站点。免费计划包括欧盟服务器、随机子域和单用户。
* [btunnel](https://www.btunnel.in/) — 将本地主机和本地 tcp 服务器公开给 Internet。免费计划包括文件服务器、自定义 http 请求和响应标头、基本身份验证保护和 1 小时隧道超时。

**[⬆️ 返回首页](#目录)**

## 问题跟踪和项目管理

* [acunote.com](https://www.acunote.com/) — 最多 5 名团队成员的免费项目管理和 SCRUM 软件
* [asana.com](https://asana.com/) — 与协作者一起进行私人项目免费
* [待办事项列表](https://backlog.com) — 您的团队在一个平台上发布优秀项目所需的一切。免费计划提供 1 个项目，有 10 个用户和 100MB 的存储空间。
* [Basecamp](https://basecamp.com/personal) - 待办事项列表、里程碑管理、类似论坛的消息传递、文件共享和时间跟踪。最多 3 个项目、20 个用户和 1GB 存储空间。
* [bitrix24.com](https://www.bitrix24.com/) — Intranet 和项目管理工具。免费计划有 5GB，可供无限用户使用。
* [cacoo.com](https://cacoo.com/) — 在线实时图：流程图、UML、网络。免费最多 15 个用户/图表，25 张
* [Chpokify](https://chpokify.com/) — 基于团队的计划扑克，可节省冲刺估计时间。最多免费 5 个用户、免费 Jira 集成、无限视频通话、无限团队、无限会话。
* [clickup.com](https://clickup.com/) — 项目管理。带有云存储的免费高级版本。提供移动应用程序和 Git 集成。
* [Clockify](https://clockify.me) - 时间跟踪器和时间表应用程序，可让您跟踪跨项目的工作时间。无限用户，永久免费。
* [Cloudcraft](https://cloudcraft.co/) — 使用 Cloudcraft 可视化设计器在几分钟内设计出专业的架构图，该设计器通过智能组件对 AWS 进行了优化，并显示实时数据。免费计划为单个用户提供无限的私人图表。
* [Codegiant](https://codegiant.io) — 具有存储库托管和 CI/CD 的项目管理。免费计划提供无限的存储库、项目和文档，有 5 名团队成员。每月 500 个 CI/CD 分钟。每月 30000 个无服务器代码运行分钟数 1GB 存储库存储。
* [Confluence](https://www.atlassian.com/software/confluence) - Atlassian 的内容协作工具用于帮助团队高效协作和共享知识。最多可容纳 10 个用户的免费计划。
* [contriber.com](https://www.contriber.com/) — 可定制的项目管理平台、免费入门计划、五个工作区
* [Crosswork](https://crosswork.app/) - 多功能项目管理平台。最多 3 个项目免费，无限用户，1 GB 存储空间。
* [diagrams.net](https://app.diagrams.net/) — 本地存储在 Google Drive、OneDrive 或 Dropbox 中的在线图表。所有功能和存储级别均免费
* [freedcamp.com](https://freedcamp.com/) - 任务、讨论、里程碑、时间跟踪、日历、文件和密码管理器。具有无限项目、用户和文件存储的免费计划。
* [easyretro.io](https://www.easyretro.io/) — 简单直观的冲刺回顾工具。免费计划有三个公共委员会，每个委员会每月进行一次调查。
* [GForge](https://gforge.com) — 项目管理和问题跟踪工具集，适用于具有自有和 SaaS 选项的复杂项目。SaaS 免费计划为前五个用户提供免费和免费的开源项目。
* [gleek.io](https://www.gleek.io) — 面向开发人员的免费描述到图表工具。使用关键字创建非正式的 UML 类、对象或实体关系图。
* [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - GraphQL Inspector 输出两个 GraphQL 架构之间的更改列表。每个差异都经过精确解释，并标记为破坏性、非破坏性或危险性。
* [huboard.com](https://huboard.com/) — 针对 GitHub 问题进行即时项目管理，开源免费
* [Hygger](https://hygger.io) — 项目管理平台。免费计划提供无限的用户、项目和看板以及 100 MB 的存储空间。
* [Instabug](https://instabug.com) — 适用于移动应用程序的综合错误报告和应用内反馈 SDK。免费计划最多 1 个应用程序和一名成员。
* [WishKit](https://wishkit.io) — 收集 iOS/macOS 应用程序的应用内用户反馈，并根据用户投票确定功能的优先级。免费计划最多 1 个应用程序。
* [Ilograph](https://www.ilograph.com/) — 交互式图表，允许用户从多个角度和详细程度查看其基础设施。图表可以用代码表示。免费套餐有无限的私人图表，最多可容纳 3 个查看器。
* [Jira](https://www.atlassian.com/software/jira) — 许多企业环境中使用的高级软件开发项目管理工具。最多可容纳 10 个用户的免费计划。
* [kanbanflow.com](https://kanbanflow.com/) — 基于董事会的项目管理。免费、高级版本，提供更多选项
* [kanbantool.com](https://kanbantool.com/) — 基于看板的项目管理。免费计划有两个板和两个用户，没有附件或文件。
* [kan.bn](https://kan.bn/) - 功能强大、灵活的看板应用，可帮助你在一个位置组织工作、跟踪进度和交付结果。最多 1 个用户的免费计划，可无限的板、无限列表、无限的卡片。
* [Kitemaker.co](https://kitemaker.co) - 在产品开发过程的所有阶段进行协作，并跟踪 Slack、Discord、Figma 和 Github 上的工作。无限用户，无限空间。免费计划最多 250 个工作项。
* [Kiter.app](https://www.kiter.app/) - 让任何人组织他们的求职并跟踪面试、机会和联系。强大的网络应用程序和 Chrome 扩展程序。完全免费。
* [Kumu.io](https://kumu.io/) — 与动画、装饰、过滤器、聚类、电子表格导入等的关系映射。免费套餐允许无限的公共项目。图形大小不受限制。为学生提供免费的私人项目。如果您不想将文件公开在线（上传、编辑、下载、丢弃），则可以使用沙盒模式。
* [线性](https://linear.app/) — 具有简化界面的问题跟踪器。无限会员免费，文件上传大小不超过 10MB，250 期（不包括存档）
* [leiga.com](https://www.leiga.com/) — Leiga 是一款 SaaS 产品，它使用 AI 自动管理您的项目，帮助您的团队保持专注并释放巨大潜力，确保您的项目按计划进行。最多 10 个用户免费，20 个自定义字段，2GB 存储空间，AI 视频录制限制为 5 分钟/视频，自动化运行时间为 20 分钟/用户/月。
* [Lucidchart](https://www.lucidchart.com/) - 具有协作功能的在线图表工具。免费计划，包含三个可编辑文档、100 个专业模板和基本协作功能。
* [MeisterTask](https://www.meistertask.com/) — 团队的在线任务管理。最多免费 3 个项目和无限的项目成员。
* [MeuScrum](https://www.meuscrum.com/en) - 带有看板的免费在线 Scrum 工具
* [nTask](https://www.ntaskmanager.com/) — 项目管理软件，使您的团队能够协作、计划、分析和管理日常任务。基本计划永久免费，具有 100 MB 存储空间和五个用户/团队。无限的工作空间、会议、作业、时间表和问题跟踪。
* [Ora](https://ora.pm/) - 敏捷任务管理和团队协作。最多 3 个用户免费，文件限制为 10 MB。
* [pivotaltracker.com](https://www.pivotaltracker.com/) — 免费用于无限的公共项目和两个私有项目，其中总共有三个活跃用户（读写）和无限的被动用户（只读）。
* [plan.io](https://plan.io/) — 具有存储库托管和更多选项的项目管理。拥有 10 个客户和 500MB 存储空间的两个用户免费
* [Plane](https://plane.so/) - Plane 是一个简单、可扩展的开源项目和产品管理工具。无限会员免费，文件上传大小不超过 5MB，1000 期。
* [planitpoker.com](https://www.planitpoker.com/) — 免费在线规划扑克（估算工具）
* [point.poker](https://www.point.poker/) - 在线规划扑克（基于共识的估算工具）。对无限的用户、团队、会话、回合和投票免费。您无需注册。
* [ScrumFast](https://www.scrumfast.com) - Scrum 板具有非常直观的界面，最多可免费使用 5 个用户。
* [Shake](https://www.shakebugs.com/) - 适用于移动应用的应用内错误报告和反馈工具。免费计划，每个应用程序每月十个错误报告。
* [快捷方式](https://shortcut.com/) \- 项目管理平台。最多 10 位用户永久免费。
* [Tadum](https://tadum.app) - 专为定期会议设计的会议议程和会议记录应用程序，最多 10 人的团队免费
* [taiga.io](https://taiga.io/) — 面向初创企业和敏捷开发人员的项目管理平台，开源免费
* [Tara AI](https://tara.ai/) — 简单的冲刺管理服务。免费计划具有无限的任务、冲刺和工作区，没有用户限制。
* [targetprocess.com](https://www.targetprocess.com/) — 可视化项目管理，从看板和 Scrum 到几乎任何运营流程。无限用户免费，最多 1,000 个数据实体 { [更多详情](https://www.targetprocess.com/pricing/) }
* [taskade.com](https://www.taskade.com/) — 实时协作任务列表和团队大纲。免费计划有一个工作区，具有无限的任务和项目;1GB 文件存储;1 周项目历史;每个视频会议有五名与会者。
* [taskulu.com](https://taskulu.com/) — 基于角色的项目管理。最多免费 5 个用户。与 GitHub/Trello/Dropbox/Google Drive 集成
* [Teaminal](https://www.teaminal.com) - 适用于远程团队的站立、复古和冲刺规划工具。最多 15 位用户免费。
* [teamwork.com](https://teamwork.com/) — 项目管理和团队聊天。五个用户和两个项目免费。提供高级计划。
* [teleretro.com](https://www.teleretro.com/) — 简单有趣的回顾工具，带有破冰船、GIF 和表情符号。免费计划包括三个复古会员和无限会员。
* [testlio.com](https://testlio.com/) — 问题跟踪、测试管理和 Beta 测试平台。私人免费使用
* [terrastruct.com](https://terrastruct.com/) — 专门用于软件架构的在线图表制作工具。每个图表最多 4 层免费套餐。
* [todoist.com](https://todoist.com/) — 协作和个人任务管理。免费计划有：5 个活动项目、项目中的 5 个用户、最大 5MB 的文件上传、三个过滤器和一周的活动历史记录。
* [trello.com](https://trello.com/) — 基于董事会的项目管理。无限个人板，10 个团队板。
* [Tweek](https://tweek.so/) — 简单的每周待办事项日历和任务管理。
* [ubertesters.com](https://ubertesters.com/) — 测试平台、集成和众测试人员，2 个项目，5 名成员
* [维基工厂](https://wikifactory.com/) — 产品设计服务，包括项目、VCS 和问题。免费计划提供无限的项目和合作者以及 3GB 存储空间。
* [Yodiz](https://www.yodiz.com/) — 敏捷开发和问题跟踪。最多免费 3 个用户，无限项目。
* [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) — 用于 FOSS 项目和私有项目的免费托管 YouTrack （InCloud）（三个用户免费）。包括时间跟踪和敏捷板
* [zenhub.com](https://www.zenhub.com) — GitHub 中唯一的项目管理解决方案。对公共存储库、OSS 和非营利组织免费
* [zenkit.com](https://zenkit.com) — 项目管理和协作工具。最多 5 名成员免费，5 GB 附件。
* [Zube](https://zube.io) — 项目管理，免费计划适用于 4 个项目和 4 个用户。GitHub 集成可用。
* [Toggl](https://toggl.com/) — 提供两个免费的生产力工具。用于时间管理和跟踪应用程序的 [Toggl Track](https://toggl.com/track/) 提供免费计划，提供无缝的时间跟踪和报告，专为自由职业者而设计。它有无限的跟踪记录、项目、客户、标签、报告等。以及 [Toggl Plan](https://toggl.com/plan/) 用于任务规划，为独立开发人员提供免费计划，具有无限的任务、里程碑和时间表。
* [Sflow](https://sflow.io) — sflow.io 是一款项目管理工具，专为敏捷软件开发、营销、销售和客户支持而构建，特别适用于外包和跨组织协作项目。免费计划最多 3 个项目和 5 名成员。
* [Pulse.red](https://pulse.red) — 用于项目的免费简约时间跟踪器和时间表应用程序。

**[⬆️ 返回首页](#目录)**

## 存储和介质处理

* [AndroidFileHost](https://androidfilehost.com/) - 免费的文件共享平台，具有无限的速度、带宽、文件数量、下载次数等。它主要针对与 Android 开发相关的文件，如 APK 构建、自定义 ROM 和修改等。但似乎也接受任何其他文件。
* [borgbase.com](https://www.borgbase.com/) — Borg Backup 的简单且安全的异地备份托管。10 GB 可用备份空间和两个存储库。
* [icedrive.net](https://www.icedrive.net/) - 简单的云存储服务。10 GB 免费存储空间
* [sync.com](https://www.sync.com/) - 端到端云存储服务。5 GB 的免费存储空间
* [pcloud.com](https://www.pcloud.com/) - 云存储服务。高达 10 GB 的免费存储空间
* [sirv.com](https://sirv.com/) — 智能图像 CDN，具有动态图像优化和调整大小的功能。免费套餐包括 500 MB 的存储空间和 2 GB 的带宽。
* [cloudimage.io](https://www.cloudimage.io/en/home) — 完整的图像优化和 CDN 服务，在全球拥有 1500+ 个接入点。多种图像大小调整、压缩和水印功能。用于响应式图像、360 度图像制作和图像编辑的开源插件。免费月度计划，包含 25GB CDN 流量、25GB 缓存存储和无限转换。
* [cloudinary.com](https://cloudinary.com/) — 使用 Ruby、Python、Java、PHP、Objective-C 和更多库，为网站和应用程序上传图像、强大的作、存储和交付。免费套餐包括 25 个每月积分。一个积分等于 1,000 次图像转换、1 GB 存储或 1 GB CDN 使用量。
* [Dropshare](https://dropsha.re) - 零知识文件共享。通过 AES-256-GCM 加密、客户端处理和零服务器端数据访问实现端到端加密文件共享。免费上传最大 1GB 的文件，无需数据收集。
* [embed.ly](https://embed.ly/) — 提供用于在网页中嵌入媒体、响应式图像缩放以及从网页中提取元素的 API。每月最多 5,000 个 URL，每秒 15 个请求免费
* [filestack.com](https://www.filestack.com/) — 文件选取器、转换和交付，免费提供 250 个文件、500 次转换和 3 GB 带宽
* [file.io](https://www.file.io) - 2 GB 的文件存储空间。下载一次后，文件会自动删除。REST API 与存储交互。速率限制一个请求/分钟。
* [freetools.site](https://freetools.site/) — 免费在线工具。转换或编辑文档、图像、音频、视频等。
* [GoFile.io](https://gofile.io/) - 免费的文件共享和存储平台可以通过基于 Web 的 UI 和 API 使用。无限的文件大小、带宽、下载次数等。但是当文件变为非活动状态（超过十天没有下载）时，它将被删除。
* [gumlet.com](https://www.gumlet.com/) — 通过 CDN 托管、处理和流式传输图像和视频。为视频提供 250 GB/月和图像 30 GB/月的慷慨免费套餐。
* [image-charts.com](https://www.image-charts.com/) — 无限生成带水印的图像图表
* [Imgbot](https://github.com/marketplace/imgbot) — Imgbot 是一款友好的机器人，可以优化您的图像并节省您的时间。优化的图像意味着在不牺牲质量的情况下更小的文件大小。它是免费开源的。
* [ImgBB](https://imgbb.com/) — ImgBB 是一个无限的图像托管服务。将图像拖放到屏幕上的任何位置。32 MB/图像限制。上传图片后接收直接图片链接、BBCode 和 HTML 缩略图。登录以查看上传历史记录。
* [imgen](https://www.jitbit.com/imgen/) - 免费无限社交封面图生成 API，无水印
* [imgix](https://www.imgix.com/) - 图像缓存、管理和 CDN。免费计划包括 1000 个源图像、无限转换和 100 GB 带宽
* [kraken.io](https://kraken.io/) — 网站性能即服务的图像优化，免费计划文件大小不超过 1 MB
* [kvstore.io](https://www.kvstore.io/) — 键值存储服务。免费套餐允许 100 个密钥，1KB/密钥，100 次调用/小时
* [npoint.io](https://www.npoint.io/) — 具有协作模式编辑功能的 JSON 存储
* [nitropack.io](https://nitropack.io/) - 通过完整的前端优化（缓存、图像和代码优化、CDN）在自动驾驶仪上加快网站的速度。每月最多 5,000 次浏览量免费
* [otixo.com](https://www.otixo.com/) — 从一个地方加密、共享、复制和移动所有云存储文件。基本计划提供无限的文件传输，最大文件大小为 250 MB，并允许五个加密文件
* [packagecloud.io](https://packagecloud.io/) — 用于 YUM、APT、RubyGem 和 PyPI 的托管包存储库。有限的免费计划和开源计划可根据要求提供
* [getpantry.cloud](https://getpantry.cloud/) — 一个简单的 JSON 数据存储 API，非常适合个人项目、黑客马拉松和移动应用程序！
* [皮纳塔 IPFS](https://pinata.cloud) — 皮纳塔是在 IPFS 上上传和管理文件的最简单方法。我们友好的用户界面和 IPFS API 使 Pinata 成为平台、创作者和收藏家最简单的 IPFS 固定服务。1 GB 免费存储空间，以及对 API 的访问。
* [placekitten.com](https://placekitten.com/) — 一项快速简单的服务，用于获取小猫的照片以用作占位符
* [plot.ly](https://plot.ly/) — 绘制和共享您的数据。免费套餐包括无限的公共文件和十个私人文件
* [podio.com](https://podio.com/) — 您可以与最多五人的团队一起使用 Podio，并试用基本计划的功能，但用户管理除外
* [QRME。SH](https://qrme.sh) - 快速、美观的批量二维码生成器 - 无需登录、无水印、无广告。每次批量导出最多 100 个 URL。
* [QuickChart](https://quickchart.io) — 生成可嵌入的图像图表、图形和 QR 码
* [redbooth.com](https://redbooth.com) — P2P 文件同步，最多 2 位用户免费
* [resmush.it](https://resmush.it) — reSmush.it 是一个免费的 API，可提供图像优化。reSmush.it 已在最常见的 CMS 上实现，例如 WordPress、Drupal 或 Magento。reSmush.it 是最常用的图像优化 API，已经处理了超过 70 亿张图像，并且仍然是免费的。
* [Shotstack](https://shotstack.io) - 用于大规模生成和编辑视频的 API。每月免费提供最多 20 分钟的渲染视频
* [tinypng.com](https://tinypng.com/) — 用于压缩和调整 PNG 和 JPEG 图像大小的 API，每月免费提供 500 次压缩
* [transloadit.com](https://transloadit.com/) — 处理视频、音频、图像、文档的文件上传和编码。通过 GitHub Student Developer Pack 对开源、慈善机构和学生免费。商业应用程序可免费获得 2 GB 的试驾空间
* [twicpics.com](https://www.twicpics.com) - 响应式图像即服务。它提供图像 CDN、媒体处理 API 和前端库来自动优化图像。该服务每月最多可免费提供 3GB 流量。
* [uploadcare.com](https://uploadcare.com/hub/developers/) — Uploadcare 为媒体管道提供了基于尖端算法的终极工具包。所有功能都完全免费提供给开发人员：文件上传 API 和 UI、图像 CDN 和源服务、自适应交付和智能压缩。免费套餐有 3000 次上传、3 GB 流量和 3 GB 存储空间。
* [imagekit.io](https://imagekit.io) – 具有自动优化、实时转换和存储功能的图像 CDN，您可以在几分钟内与现有设置集成。免费计划包括每月高达 20GB 的带宽。
* [internxt.com](https://internxt.com) – Internxt Drive 是一种基于绝对隐私和毫不妥协的安全性的零知识文件存储服务。注册并永久免费获得 10 GB！
* [degoo.com](https://degoo.com/) – 基于 AI 的云存储，免费高达 20 GB、三台设备、5 GB 推荐奖金（90 天帐户不活动）。
* [MConverter.eu](https://mconverter.eu/) – 批量转换文件。支持多种文件格式，包括 [AVIF](https://mconverter.eu/convert/to/avif/) 等新格式。从视频中提取所有图像帧。每天最多可免费处理十个 100MB 文件，每批处理两个。
* [ImageEngine](https://imageengine.io/) – ImageEngine 是一个易于使用的全局图像 CDN。低于 60 秒的设置。AVIF 和 JPEGXL 支持、WordPress、Magento、React、Vue 插件等。在[此处](https://imageengine.io/developer-program/)申请您的免费开发者帐户。
* [DocsParse](https://docsparse.com/) – GPT 支持的 AI 将 PDF、图像处理为 JSON、CSV、EXCEL 格式的结构化数据。每月免费 30 个积分。
* [VaocherApp 二维码生成器](https://www.vaocherapp.com/qr-code-generator) – 轻松创建用于礼品卡、礼券和促销活动的自定义二维码。支持自定义样式、颜色、标志......
* [LibreQR](https://libreqr.com) — 专注于隐私且无跟踪的免费二维码生成器。免费使用，无需收集数据。
* [多拉ドロップ](https://doradrop.com) — Doradrop 是一个文件共享平台，具有无限存储空间和零广告。通过安全即时共享文件 - 无需登录。

**[⬆️ 返回首页](#目录)**

## 设计和用户界面

* [AllTheFreeStock](https://allthefreestock.com) - 免费库存图像、音频和视频的精选列表。
* [Float UI](https://floatui.com/) - 免费的 Web 开发工具，用于快速创建具有时尚设计的现代响应式网站，即使对于非设计师也是如此。
* [蚂蚁设计登陆页面](https://landing.ant.design/) \- 蚂蚁设计登陆页面提供了一个由蚂蚁动产的运动组件构建的模板。拥有丰富的首页模板，下载模板代码包，使用速度快。您还可以使用编辑器快速构建自己的专用页面。
* [Backlight](https://backlight.dev/) — Backlight 以开发人员和设计师之间的协作为核心，是一个完整的编码平台，团队可以在其中构建、记录、发布、扩展和维护设计系统。免费计划允许最多 3 名编辑在一个具有无限查看器的设计系统上工作。
* [BoxySVG](https://boxy-svg.com/app) — 一个可免费安装的 Web 应用程序，用于绘制 SVG 并以 SVG、PNG、jpeg 和其他格式导出。
* [Carousel Hero](https://carouselhero.com/) - 创建社交媒体轮播的免费在线工具。
* [Circum Icons](https://circumicons.com) - 一致的开源图标，例如 React、Vue 和 Svelte 的 SVG。
* [clevebrush.com](https://www.cleverbrush.com/) — 免费图形设计/照片拼贴应用程序。此外，他们还提供将其作为组件的付费集成。
* [cloudconvert.com](https://cloudconvert.com/) — 将任何内容转换为任何内容。支持的 208 种格式，包括视频和 gif。
* [CodeMyUI](https://codemyui.com) - 精心挑选的带有代码片段的网页设计和 UI 灵感集合。
* [ColorKit](https://colorkit.co/) - 在线创建调色板或从顶级调色板中获取灵感。
* [冷却器](https://coolors.co/) \- 调色板生成器。自由。
* [CMYK Pantone](https://www.cmyktopantone.com/) - 在几秒钟内免费轻松将 CMYK 值转换为最接近的 Pantone 颜色和其他颜色模型。
* [Branition](https://branition.com/colors) - 手工策划的调色板最适合品牌。
* [css-gradient.com](https://www.css-gradient.com/) - 快速生成自定义跨浏览器 CSS 渐变的免费工具。RGB 和 HEX 格式。
* [easyvectors.com](https://easyvectors.com/) — EasyVectors.com 是一款免费的 SVG 矢量艺术库。完全免费下载最好的矢量图形。
* [figma.com](https://www.figma.com) — 面向团队的在线协作设计工具;免费套餐包括无限的文件和查看器，最多有 2 个编辑器和三个项目。
* [Flyon UI](https://flyonui.com/) - Tailwind CSS 最简单的组件库。
* [framer.com](https://www.framer.com/) - Framer 可帮助您迭代下一个应用程序、网站或产品的界面创意并制作动画 - 从强大的布局开始。对于任何将 Framer 验证为专业原型设计工具的人：无限的查看器、最多 2 个编辑器和最多 3 个项目。
* [freeforcommercialuse.net](https://freeforcommercialuse.net/) — FFCU 无忧模特/财产授权书库存照片
* [渐变](https://www.gradientos.app) \- 使选择渐变变得快速而简单。
* [Icon Horse](https://icon.horse) – 从我们简单的 API 中获取任何网站的最高分辨率图标。
* [Iconoir](https://iconoir.com) – 一个开源图标库，拥有数千个图标，支持 React、React Native、Flutter、Vue、Figma 和 Framer。
* [图标 8](https://icons8.com) — 图标、插图、照片、音乐和设计工具。免费计划提供较低分辨率的有限格式。当您使用我们的资产时，链接到 Icons8。
* [landen.co](https://www.landen.co) — 为您的初创公司生成、编辑和发布精美的网站和登录页面。全部无需代码。免费套餐允许您拥有一个网站，完全可定制并在网络上发布。
* [Quant Ux](https://quant-ux.com/) - Quant Ux 是一种原型设计和设计工具。- 它是完全免费的，也是开源的。
* [lensdump.com](https://lensdump.com/) - 免费云图像托管。
* [Lorem Picsum](https://picsum.photos/) - 一个免费工具，易于使用，时尚的占位符。在我们的 URL 之后，添加您想要的图像尺寸（宽度和高度），您将获得一张随机图像。
* [LottieFiles](https://lottiefiles.com/) - 世界上最大的在线平台，为设计师、开发人员等提供世界上最微型的动画格式。访问适用于 Android、iOS 和 Web 的 Lottie 动画工具和插件。
* [MagicPattern](https://www.magicpattern.design/tools) — CSS 和 SVG 背景生成器的集合，以及用于渐变、图案和斑点的工具。
* [marvelapp.com](https://marvelapp.com/) — 设计、原型制作和协作，免费计划仅限于一个用户和项目。
* [Mindmup.com](https://www.mindmup.com/) — 免费无限的思维导图并将它们存储在云端。您的思维导图可以随时随地、即时地从任何设备使用。
* [Mockplus iDoc](https://www.mockplus.com/idoc) - Mockplus iDoc 是一款功能强大的设计、协作和交接工具。免费计划包括三个用户和五个具有所有可用功能的项目。
* [mockupmark.com](https://mockupmark.com/create/free) — 为社交媒体和电子商务创建逼真的 T 恤和服装模型，40 个免费模型。
* [Modeldraw.com](https://modeldraw.com) — 完整的图表平台，包括 UML、系统架构、流程图、思维导图和敏捷工作流程。与无限的团队成员实时协作，无需信用卡。
* [Mossaik](https://mossaik.app) - 免费的 SVG 图像生成器，具有不同的工具，如波浪、博客和图案。
* [movingpencils.com](https://movingpencils.com) — 快速的、基于浏览器的矢量编辑器。完全免费。
* [Octopus.do](https://octopus.do) — 可视化站点地图构建器。实时构建您的网站结构并快速共享以与您的团队或客户协作。
* [Pencil](https://github.com/evolus/pencil) - 使用 Electron 的开源设计工具。
* [Penpot](https://penpot.app) - 基于 Web 的开源设计和原型制作工具。支持 SVG。完全免费。
* [pexels.com](https://www.pexels.com/) - 用于商业用途的免费库存照片。有一个免费的 API，允许您按关键字搜索照片。
* [photopea.com](https://www.photopea.com) — 一个免费的高级在线设计编辑器，带有 Adobe Photoshop UI，支持 PSD、XCF 和 Sketch 格式（Adobe Photoshop、Gimp 和 Sketch App）。
* [pixlr.com](https://pixlr.com/) — 商业级别的免费在线浏览器编辑器。
* [Plasmic](https://www.plasmic.app/) - 一个快速、易于使用、强大的网页设计工具和页面构建器，可集成到您的代码库中。构建响应式页面或复杂组件;可选地使用代码进行扩展;并发布到生产站点和应用。
* [Pravatar](https://pravatar.cc/) - 生成一个随机/占位符的假头像，其 URL 可以直接在您的 Web/应用程序中进行热链接。
* [PNG 到 WebP 转换器](https://pngtowebpconverter.com/) \- 直接在浏览器中将 PNG 图像转换为 WebP 图像。无需上传，完全客户端处理，可实现最大程度的隐私和安全性。
* [Proto.io](https://www.proto.io) - 无需编码即可创建完全交互式的 UI 原型。免费套餐在免费试用期结束后可用。免费套餐包括一个用户、一个项目、五个原型、100MB 的在线存储空间和 proto.io 应用程序的预览。
* [resizeappicon.com](https://resizeappicon.com/) — 一项用于调整应用图标大小和管理应用图标的简单服务。
* [Rive](https://rive.app) — 创建精美的动画并将其发布到任何平台。个人永久免费。该服务是一个编辑器，还托管其服务器上的所有图形。它们还为许多平台提供运行时，以运行使用 Rive 制作的表示。
* [storyset.com](https://storyset.com/) — 使用此工具为您的项目创建令人难以置信的免费定制插图。
* [smartmockups.com](https://smartmockups.com/) — 创建产品模型，200 个免费模型。
* [Shadcn Studio](https://shadcnstudio.com/theme-editor) — 预览不同组件和布局的主题更改。
* [Tailark](https://tailark.com/) - 专为营销网站设计的现代、响应式、预构建的 UI 块的集合。
* [tabler-icons.io](https://tabler-icons.io/) — 超过 1500 个免费复制和粘贴 SVG 可编辑图标。
* [tweakcn](https://tweakcn.com/) — shadcn/ui 的漂亮主题。实时自定义颜色、排版等。
* [UI 头像](https://ui-avatars.com/) \- 根据名字生成带有首字母缩写的头像。URL 可以直接在您的 Web/应用程序中进行热链接。通过 URL 支持配置参数。
* [unDraw](https://undraw.co/) - 不断更新的精美 SVG 图像集合，您可以完全免费使用，无需注明出处。
* [unsplash.com](https://unsplash.com/) - 用于商业和非商业目的的免费库存照片（随心所欲的许可）。
* [vectr.com](https://vectr.com/) — 适用于 Web + 桌面的免费设计应用程序。
* [walkme.com](https://www.walkme.com/) — 企业级指导和参与平台，免费计划 3 次步行最多 5 步。
* [Webflow](https://webflow.com) - 具有动画和网站托管功能的所见即所得网站构建器。两个项目免费。
* [Updrafts.app](https://updrafts.app) - 所见即所得的网站构建器，用于基于 tailwindcss 的设计。非商业用途免费。
* [whimsical.com](https://whimsical.com/) - 协作流程图、线框图、便签和思维导图。最多创建 4 个免费板。
* [Zeplin](https://zeplin.io/) — 设计师和开发人员协作平台。显示设计、资产和样式指南。一个项目免费。
* [Pixelixe](https://pixelixe.com/) — 在线创建和编辑引人入胜、独特的图形和图像。
* [Responsively App](https://responsively.app) - 一个免费的开发工具，用于更快、更精确的响应式 Web 应用程序开发。
* [SceneLab](https://scenelab.io) - 在线模型图形编辑器，包含不断扩展的免费设计模板集合
* [xLayers](https://xlayers.dev) - 预览 Sketch 设计文件并将其转换为 Angular、React、Vue、LitElement、Stencil、Xamarin 等（[https://github.com/xlayers/xlayers](https://github.com/xlayers/xlayers) 免费开源）
* [葡萄滴](https://grapedrop.com/) — 基于 GrapesJS 框架的响应式、功能强大、SEO 优化的网页构建器。前五页免费，无限自定义域，所有功能和简单使用。
* [Mastershot](https://mastershot.app) - 完全免费的基于浏览器的视频编辑器。无水印，最高 1080p 导出选项。
* [独角兽平台](https://unicornplatform.com/) \- 带有托管功能的轻松登陆页面构建器。一个免费网站。
* [SVGmix.com](https://www.svgmix.com/) - 包含 300K+ 免费 SVG 图标、集合和品牌徽标的海量存储库。它在浏览器中有一个简单的矢量编辑程序，用于快速文件编辑。
* [svgrepo.com](https://www.svgrepo.com/) - 使用各种矢量库探索、搜索和查找最适合您的项目的图标或矢量。下载免费的 SVG 矢量以供商业用途。
* [haikei.app](https://www.haikei.app/) - Haikei 是一款 Web 应用程序，可生成独特的 SVG 形状、背景和图案 - 可与您的设计工具和工作流程一起使用。
* [Canva](https://canva.com) - 用于创建视觉内容的免费在线设计工具。
* [Superdesigner](https://superdesigner.co) - 一系列免费设计工具，只需点击几下即可创建独特的背景、图案、形状、图像等。
* [TeleportHQ](https://teleporthq.io/) - 低代码前端设计开发平台。TeleportHQ 是一个协作前端平台，可即时创建和发布无头静态网站。三个免费项目、无限协作者和免费代码导出。
* [vector.express](https://vector.express) — 快速轻松地转换您的 AI、CDR、DWG、DXF、EPS、HPGL、PDF、PLT、PS 和 SVG 矢量。
* [Vertopal](https://www.vertopal.com) - Vertopal 是一个免费的在线平台，用于将文件转换为各种格式。包括 JPG 到 SVG、GIF 到 APNG、PNG 到 WEBP、JSON 到 XML 等开发人员转换器。
* [okso.app](https://okso.app) - 简约的在线绘图应用程序。允许创建快速草图和视觉笔记。将草图导出为 PNG、JPG、SVG 和 WEBP。也可作为 PWA 安装。所有人免费使用（无需注册）。
* [Wdrfree SVG](https://wdrfree.com/free-svg) - 黑白免费 SVG 剪切文件。
* [Lucide](https://lucide.dev) - 免费的可定制且一致的 SVG 图标工具包。
* [Logo.dev](https://www.logo.dev) - 具有 44M+ 品牌的公司徽标 API，就像调用 URL 一样简单。前 10,000 次 API 调用是免费的。
* [MDBootstrap](https://mdbootstrap.com/) - 免费供个人和商业用途 Bootstrap、Angular、React 和 Vue UI 套件，包含 700 多个组件、令人惊叹的模板、1 分钟安装、广泛的教程和庞大的社区。
* [TW Elements](https://tw-elements.com/) - 使用 Tailwind CSS 重新创建的免费 Bootstrap 组件，但具有更好的设计和更多的功能。
* [DaisyUI](https://daisyui.com/) -- 免费。“使用 Tailwind CSS 但编写更少的类名”提供了按钮等组件。
* [Scrollbar.app](https://scrollbar.app) -- 简单的免费 Web 应用程序，用于为 Web 设计自定义滚动条。
* [css.glass](https://css.glass/) -- 用于使用 CSS 创建玻璃变形设计的免费 Web 应用程序。
* [hypercolor.dev](https://hypercolor.dev/) -- 精选的 Tailwind CSS 颜色渐变集合还提供了各种生成器来创建您自己的生成器。
* [iconify.design](https://icon-sets.iconify.design/) -- 100 多个图标包的集合，具有统一的界面。允许您跨包搜索图标，并将单个图标导出为 SVG 或流行的 Web 框架。
* [NextUI](https://nextui.org/) -- 免费。美观、快速、现代的 React 和 Next.js UI 库。
* [字形](https://glyphs.fyi/) \-- 免费，网络上最强大的图标，完全可编辑和真正的开源设计系统。
* [ShadcnUI](https://ui.shadcn.com/) -- 设计精美的组件，您可以将其复制并粘贴到您的应用程序中。定制。开源。
* [HyperUI](https://www.hyperui.dev/) -- 免费的开源 Tailwind CSS 组件。
* [日历图标生成器](https://calendariconsgenerator.app/) \-- 只需单击一下即可生成一整年的独特图标，完全免费
* [图像背景模糊器](https://imagebgblurer.com/) \-- 使用 Notion、Trello、Jira 等工具的图像源作为背景模糊，为图像生成模糊背景框架
* [Webstudio](https://webstudio.is/) -- Webflow 的开源替代品。免费计划在其域上提供无限的网站。五个具有自定义域的网站。一万次页面浏览量/月。2 GB 资产存储。
* [尿布](https://nappy.co/) ——黑人和棕色人种的美丽照片，免费。用于商业和个人用途。
* [Tailkits](https://tailkits.com/) -- 精选的 Tailwind 模板、组件和工具集合，以及用于代码、网格、框阴影等的有用生成器。
* [Tailcolors](https://tailcolors.com/) -- 一个漂亮的 Tailwind CSS v4 调色板。即时预览和复制完美的 Tailwind CSS 颜色类。
* [Excalidraw](https://excalidraw.com/) -- 一个免费的在线绘图文档网页，免费保存到本地和导出支持。
* [Lunacy](https://icons8.com/lunacy) -- 免费的图形设计工具，具有离线支持、内置资产（图标、照片、插图）和实时协作。免费套餐包括 10 个云文档、30 天历史记录、低分辨率资产和基本设计工具。
* [流](https://flows.sh/) \-- 一个完全可定制的产品采用平台，用于构建入职和用户参与体验。每月最多 250 名跟踪用户免费。

**[⬆️ 返回首页](#目录)**

## 设计灵感

* [阿巴德。](https://www.awwwards.com/)\- \[热门网站\] 展示所有设计最佳的网站（由设计师投票选出）。
* [Behance](https://www.behance.net/) - \[设计展示\] 设计师展示作品的地方。可使用 UI/UX 项目的类别进行过滤。
* [dribbble](https://dribbble.com/) - 【设计展示】独特的设计灵感，一般不是来自真实应用。
* [登陆](https://landings.dev/) \- \[网页截图\] 根据您的喜好找到最适合您的设计灵感的登陆页面。
* [Lapa Ninja](https://www.lapa.ninja/) - \[登陆页面 / UI KIts / Web 屏幕截图\] Lapa Ninja 是一个画廊，提供最好的 6025 个登陆页面示例、设计师免费书籍和来自网络上的免费 UI 套件。
* [LovelyLanding.net](https://www.lovelylanding.net/) - \[登陆页面设计\] 经常更新的登陆页面屏幕截图。包括台式机、平板电脑和移动设备屏幕截图。
* [Mobbin](https://mobbin.design/) - \[移动屏幕截图\] 使用我们的 50,000+ 完全可搜索的移动应用程序屏幕截图库，节省数小时的 UI 和 UX 研究时间。
* [Uiland Design](https://uiland.design/) - \[移动屏幕截图\] 探索来自非洲和世界领先公司的移动和 Web UI 设计。
* [移动模式](https://www.mobile-patterns.com/) \- \[移动屏幕截图\] 一个设计灵感库，包含最好的 UI UX 模式（iOS 和 Android），供设计师、开发人员和产品制造商参考。
* [页面流](https://pageflows.com/) \- \[移动/Web 视频和屏幕截图\] 跨许多移动和 Web 应用程序的完整流的视频。还包括屏幕截图。高度可搜索和索引。
* [Screenlane](https://screenlane.com/) - \[移动屏幕截图\]获得灵感并跟上最新的网络和移动应用程序 UI 设计趋势。可按模式和应用程序过滤。
* [scrnshts](https://scrnshts.club/) - \[手机截图\] 精心挑选的最佳应用商店设计截图合集。
* [Refero](https://refero.design/) - \[Web 屏幕截图\] 来自优秀 Web 应用程序的设计参考的标记和可搜索集合。

**[⬆️ 返回首页](#目录)**

## 地图上的数据可视化

* [IP 地理定位](https://ipgeolocation.io/) — 免费的 DEVELOPER 计划，每月 30K 请求。
* [carto.com](https://carto.com/) — 根据您的数据和公共数据创建地图和地理空间 API。
* [发条微型](https://clockworkmicro.com/) — 像发条一样工作的地图工具。每月五万个免费查询（地图瓦片、db2vector、高程）。
* [developers.arcgis.com](https://developers.arcgis.com) — 用于跨 Web、桌面和移动设备的地图、地理空间数据存储、分析、地理编码、路线等的 API 和 SDK。200 万个免费底图瓦片、20000 个未存储的地理编码、20000 条简单路线、5000 个行车时间计算以及每月 5GB 的免费瓦片 + 数据存储。
* [Foursquare](https://developer.foursquare.com/) - 来自 Places API 和 Pilgrim SDK 的位置发现、场地搜索和上下文感知内容。
* [geoapify.com](https://www.geoapify.com/) - 矢量和栅格地图图块、地理编码、地点、路线、等值线 API。每天三千个免费请求。
* [geocod.io](https://www.geocod.io/) — 通过 API 或 CSV 上传进行地理编码。每天 2,500 次免费查询。
* [geocodify.com](https://geocodify.com/) — 通过 API 或 CSV 上传进行地理编码和地理解析。每月 10k 免费查询。
* [geojs.io](https://www.geojs.io/) - 高可用性 REST/JSON/JSONP IP 地理位置查找 API。
* [giscloud.com](https://www.giscloud.com/) — 在线可视化、分析和共享地理数据。
* [graphhopper.com](https://www.graphhopper.com/) 为路由、路线优化、距离矩阵、地理编码和地图匹配提供了免费的开发人员包。
* [这里](https://developer.here.com/) — 用于地图和位置感知应用程序的 API 和 SDK。每月 250k 笔交易免费。
* [locationiq.com](https://locationiq.com/) — 地理编码、地图和路由 API。每天免费 5000 个请求。
* [mapbox.com](https://www.mapbox.com/) — 用于显示地图数据的地图、地理空间服务和 SDK。
* [maptiler.com](https://www.maptiler.com/cloud/) — 用于地图可视化的矢量地图、地图服务和 SDK。每周更新和四种地图样式的免费矢量图块。
* [nominatim.org](https://nominatim.org/) — OpenStreetMap 的免费地理编码服务，提供全局地址搜索功能和反向地理编码功能。
* [nextbillion.ai](https://nextbillion.ai/) - 地图相关服务：地理编码、导航（方向、路线、路线优化、距离矩阵）、地图 SDK（矢量、静态、移动 SDK）。每项服务指定[配额即可免费](https://nextbillion.ai/pricing) 。
* [opencagedata.com](https://opencagedata.com) — 地理编码 API，聚合 OpenStreetMap 和其他开放地理资源。每天 2,500 次免费查询。
* [osmnames](https://osmnames.org/) — 地理编码，搜索结果按相关维基百科页面的受欢迎程度排名。
* [positionstack](https://positionstack.com/) - 全球地点和坐标的免费地理编码。每月 25,000 个请求供个人使用。
* [stadiamaps.com](https://stadiamaps.com/) - 地图磁贴、路线、导航和其他地理空间 API。每天 2,500 个免费地图视图和 API 请求，用于非商业用途和测试。
* [maps.stamen.com](http://maps.stamen.com/) - 免费地图图块和图块托管。
* [ipstack](https://ipstack.com/) - 通过 IP 地址定位和识别网站访问者
* [Geokeo api](https://geokeo.com) - 具有语言更正等功能的地理编码 API。全球覆盖。每日 2,500 次免费查询

**[⬆️ 返回首页](#目录)**

## 包构建系统

* [build.opensuse.org](https://build.opensuse.org/) — 适用于多个发行版（SUSE、EL、Fedora、Debian 等）的软件包构建服务。
* [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) — Fedora 和 EL 的基于模拟的 RPM 构建服务。
* [help.launchpad.net](https://help.launchpad.net/Packaging) — Ubuntu 和 Debian 构建服务。

**[⬆️ 返回首页](#目录)**

## IDE 和代码编辑

* [3v4l](https://3v4l.org/) - 免费的在线 PHP shell 和片段共享站点，可在 300+ PHP 版本中运行您的代码
* [Android Studio](https://developer.android.com/studio) — Android Studio 提供了在各种类型的 Android 设备上构建应用的最快工具。开源 IDE 对所有人免费，是最好的 Android 应用程序开发。适用于 Windows、Mac、Linux 甚至 ChromeOS！
* [AndroidIDE](https://m.androidide.com/) — 一个开源 IDE，用于在 Android 设备上开发真正的、基于 Gradle 的 Android 应用程序。
* [Apache Netbeans](https://netbeans.apache.org/) — 开发环境、工具平台和应用程序框架。
* [apiary.io](https://apiary.io/) — 具有即时 API 模拟和生成文档的协作设计 API（免费，无限 API 蓝图和无限用户，只需一个管理员帐户和托管文档）。
* [BBEdit](https://www.barebones.com/) - BBEdit 是一款适用于 macOS 的流行且可扩展的编辑器。免费模式提供了[强大的核心功能集](https://www.barebones.com/products/bbedit/comparison.html)和高级功能的升级路径。
* [Binder](https://mybinder.org/) - 将 Git 存储库转换为交互式笔记本的集合。这是一项免费的公共服务。
* [BlueJ](https://bluej.org) — 专为初学者设计的免费 Java 开发环境，被全球数百万人使用。由 Oracle 和简单的 GUI 提供支持，可帮助初学者。
* [Bootify.io](https://bootify.io/) - 带有自定义数据库和 REST API 的 Spring Boot 应用程序生成器。
* [Brackets](http://brackets.io/) - Brackets 是一个专为 Web 开发设计的开源文本编辑器。它重量轻、易于使用且高度可定制。
* [cacher.io](https://www.cacher.io) — 带有标签并支持 100+ 编程语言的代码片段管理器。
* [Code：：Blocks](https://codeblocks.org) — 免费的 Fortran 和 C/C++ IDE。开源并在 Windows、macOS 和 Linux 上运行。
* [Cody](https://sourcegraph.com/cody) - 免费的 AI 编码助手，可以编写（代码块、自动完成、单元测试）、理解（了解整个代码库）、修复和查找您的代码。适用于 VS Code、JetBrains 和在线。
* [codiga.io](https://codiga.io/) — 编码助手，可让您直接在 IDE 中搜索、定义和重用代码片段。对个人和小型组织免费。
* [codesnip.com.br](https://codesnip.com.br) — 带有类别、搜索和标签的简单代码片段管理器。免费且无限制。
* [cocalc.com](https://cocalc.com/) — （以前称为 SageMathCloud，在 cloud.sagemath.com） — 云中的协作计算。浏览器访问完整的 Ubuntu，具有内置协作功能，预装了大量用于数学、科学、数据科学的免费软件：Python、LaTeX、Jupyter Notebooks、SageMath、scikitlearn 等。
* [code.cs50.io](https://code.cs50.io/) - Visual Studio Code for CS50 是 code.cs50.io 的一款 Web 应用，可为学生和教师调整 GitHub Codespaces。
* [codepen.io](https://codepen.io/) — CodePen 是 Web 前端的游乐场。
* [codesandbox.io](https://codesandbox.io/) — React、Vue、Angular、React 等的在线游乐场。
* [Components.studio](https://webcomponents.dev/) - 单独编码组件，在故事中可视化它们，测试它们，并在 npm 上发布它们。
* [Eclipse Che](https://www.eclipse.org/che/) - 面向开发团队的基于 Web 的 Kubernetes 原生 IDE，支持多语言。开源和社区驱动。红帽托管的在线实例可在 [workspaces.openshift.com](https://workspaces.openshift.com/) 获得。
* [fakejson.com](https://fakejson.com/) — FakeJSON 帮助您使用其 API 快速生成虚假数据。发出 API 请求，描述您想要什么以及您想要如何。API 以 JSON 形式返回所有内容。加快创意的上市过程，并伪造它，直到你成功为止。
* [ForgeCode](https://forgecode.dev/) — 适用于 Claude、GPT4 系列、Grok、Deepseek、Gemini 和所有前沿模型的 AI 配对程序员。与您的 CLI 本机协作，并与任何 IDE 无缝集成。免费套餐包括具有本地处理的基本 AI 模型访问权限。
* [GetVM](https://getvm.io) — 即时免费的 Linux 和 IDE chrome 侧边栏。免费层包括每天 5 个虚拟机。
* [GitPod](https://www.gitpod.io) — 用于 GitHub 项目的即时、可随时编码的开发环境。免费套餐包括 50 小时/月。
* [ide.goorm.io](https://ide.goorm.io) goormIDE 是云上的完整 IDE。多语言支持、通过功能齐全的基于 Web 的终端的基于 Linux 的容器、端口转发、自定义 URL、实时协作和聊天、共享链接、Git/Subversion 支持。还有更多功能（免费套餐包括每个容器 1GB RAM 和 10GB 存储空间，5 个容器插槽）。
* [JDoodle](https://www.jdoodle.com) — 60 多种编程语言的在线编译器和编辑器，提供 REST API 代码免费计划，每天最多可编译 200 个学分。
* [jetbrains.com](https://jetbrains.com/products.html) — 生产力工具、IDE 和部署工具（又名 [IntelliJ IDEA](https://www.jetbrains.com/idea/)、[PyCharm](https://www.jetbrains.com/pycharm/) 等）。学生、教师、开源和用户组的免费许可证。
* [jsbin.com](https://jsbin.com) — JS Bin 是前端 Web（HTML、CSS 和 JavaScript）的另一个游乐场和代码共享站点。它还支持 Markdown、Jade 和 Sass）。
* [jsfiddle.net](https://jsfiddle.net/) — JS Fiddle 是前端 Web 的游乐场和代码共享站点，支持协作。
* [JSONPlaceholder](https://jsonplaceholder.typicode.com/) 某些 REST API 端点以 JSON 格式返回一些虚假数据。如果您想在本地运行服务器，也可以使用源代码。
* [Lazarus](https://www.lazarus-ide.org/) — Lazarus 是一个与 Delphi 兼容的跨平台 IDE，用于快速应用程序开发。
* [MarsCode](https://www.marscode.com/) - 一个免费的人工智能驱动的基于云的 IDE。
* [micro-jaymock](https://micro-jaymock.now.sh/) - 用于生成虚假 JSON 数据的微型 API 模拟微服务。
* [mockable.io](https://www.mockable.io/) — Mockable 是一个简单的可配置服务，用于模拟 RESTful API 或 SOAP Web 服务。此联机服务允许您快速定义 REST API 或 SOAP 端点，并让它们返回 JSON 或 XML 数据。
* [mockaroo](https://mockaroo.com/) — Mockaroo 允许您生成 CSV、JSON、SQL 和 Excel 格式的真实测试数据。您还可以为后端 API 创建模拟。
* [Mocklets](https://mocklets.com) - 基于 HTTP 的模拟 API 模拟器，有助于模拟 API，以实现更快的并行开发和更全面的测试，并提供终身免费套餐。
* [Paiza](https://paiza.cloud/en/) — 在浏览器中开发 Web 应用程序，无需进行任何设置。免费计划提供一台服务器，每天 24 小时生存期和 4 小时运行时间，具有 2 个 CPU 内核、2 GB RAM 和 1 GB 存储空间。
* [Prepros](https://prepros.io/) - Prepros 可以编译开箱即用的 Sass、Less、Stylus、Pug/Jade、Haml、Slim、CoffeeScript 和 TypeScript，重新加载您的浏览器，并轻松开发和测试您的网站，以便您可以专注于使它们变得完美。您还可以只需点击几下即可添加自己的工具。
* [Replit](https://replit.com/) — 适用于各种程序语言的云编码环境。
* [SoloLearn](https://code.sololearn.com) — 非常适合运行代码片段的云编程游乐场。支持多种编程语言。运行代码不需要注册，但在他们的平台上保存代码时需要注册。还为初学者和中级编码人员提供免费课程。
* [stackblitz.com](https://stackblitz.com/) — 用于创建、编辑和部署全栈应用程序的在线/云代码 IDE。支持任何流行的基于 NodeJs 的前端和后端框架。创建新项目的短链接：[https://node.new](https://node.new)。
* [Sublime Text](https://www.sublimetext.com/) - Sublime Text 是一款流行、多功能且高度可定制的文本编辑器，用于编码和文本编辑任务。
* [Visual Studio Code](https://code.visualstudio.com/) - 重新定义和优化的代码编辑器，用于构建和调试新式 Web 和云应用程序。由 Microsoft 开发。
* [Visual Studio 社区](https://visualstudio.microsoft.com/vs/community/) — 功能齐全的 IDE，具有数千个扩展、跨平台应用程序开发（可用于 iOS 和 Android 的 Microsoft 扩展下载）、桌面、Web 和云开发、多语言支持（C#、C++、JavaScript、Python、PHP 等）。
* [VSCodium](https://vscodium.com/) - 社区驱动，没有遥测/跟踪，并且免费许可的 Microsoft 编辑器 VSCode 二进制分发
* [wakatime.com](https://wakatime.com/) — 使用文本编辑器插件量化有关您的编码活动的自我指标，免费有限计划。
* [Wave 终端](https://waveterm.dev/) \- Wave 是一个开源的跨平台终端，用于无缝工作流程。内联渲染任何内容。保存会话和历史记录。由开放的 Web 标准提供支持。MacOS 和 Linux。
* [WebComponents.dev](https://webcomponents.dev/) — 浏览器内 IDE，用于使用 58 个可用模板、支持故事和测试对 Web 组件进行单独编码。
* [PHPSandbox](https://phpsandbox.io/) — PHP 的在线开发环境
* [WebDB](https://webdb.app) - 免费高效的数据库 IDE。具有服务器发现、ERD、数据生成器、AI、NoSQL 结构管理器、数据库版本控制等功能。
* [Zed](https://zed.dev/) - Zed 是 Atom 和 Tree-sitter 的创建者推出的高性能多人代码编辑器。
* [OneCompiler](https://onecompiler.com/) - 免费在线编译器，支持 70+ 种语言，包括 Java、Python、C++、JavaScript。

**[⬆️ 返回首页](#目录)**

## 分析、事件和统计

* [Userbird](https://userbird.com) - 具有热图、会话记录和收入跟踪功能的 Google Analytics 替代方案。
* [Repohistory](https://repohistory.com) - 用于跟踪超过 14 天的 GitHub 存储库流量历史记录的漂亮仪表板。免费计划允许用户监控单个存储库的流量。
* [Dwh.dev](https://dwh.dev) - 数据云可观测性解决方案 （Snowflake）。免费供个人使用。
* [Hightouch - Hightouch](https://hightouch.com/) 是一个反向 ETL 平台，可帮助您将客户数据从数据仓库同步到 CRM、营销和支持工具。免费套餐为您提供一个将数据同步到的目标。
* [Avo](https://avo.app/) — 简化的分析发布工作流程。单一事实来源跟踪计划、类型安全的分析跟踪库、应用内调试器和数据可观测性，可在发布之前捕获所有数据问题。两名工作区成员免费，1 小时数据可观测性回溯。
* [分支](https://www.branch.io) — 移动分析平台。免费套餐为多达 10K 移动应用程序用户提供深度链接和其他服务。
* [人口普查](https://www.getcensus.com/) — 反向 ETL 和运营分析平台。将数据仓库中的 10 个字段同步到 60+ SaaS，如 Salesforce、Zendesk 或 Amplitude。
* [Clicky](https://clicky.com) — 网站分析平台。一个网站的免费计划，具有 3000 次浏览量分析。
* [Databox](https://databox.com) — 通过结合其他分析和 BI 平台的业务洞察和分析。免费计划提供 3 个用户、仪表板和数据源。11M 历史数据记录。
* [Hitsteps.com](https://hitsteps.com/) — 2,000 个网站每月 1 次浏览量
* [amplitude.com](https://amplitude.com/) — 每月 100 万个事件，最多 2 个应用程序
* [山羊计数器](https://www.goatcounter.com/) — GoatCounter 是一个开源网络分析平台，可作为托管服务（免费用于非商业用途）或自托管应用程序使用。它旨在提供易于使用且有意义的隐私友好型网络分析，作为 Google Analytics 或 Matomo 的替代品。免费套餐用于非商业用途，包括无限站点、六个月的数据保留和每月 100k 页面浏览量。
* [Google Analytics](https://analytics.google.com/) — Google Analytics （分析）
* [MetricsWave](https://metricswave.com) — 面向开发人员的隐私友好型 Google Analytics 替代方案。免费计划允许每月 1M 页面浏览量，无需信用卡。
* [Expensify](https://www.expensify.com/) — 费用报告，免费个人报告审批工作流程
* [getinsights.io](https://getinsights.io) - 注重隐私、无 cookie 的分析，每月最多可免费处理 3k 个事件。
* [heap.io](https://heap.io) — 自动捕获 iOS 或 Web 应用程序中的每个用户作。每月最多 10K 会话免费。
* [Hotjar](https://hotjar.com) — 网站分析和报告。免费计划允许每天 2000 次浏览量。100 个快照/天（最大容量：300 个）。三个快照热图可以存储 365 天。无限的团队成员。也在应用程序和独立调查中，带有屏幕截图的反馈小部件。免费套餐允许创建 3 个调查和 3 个反馈小部件，并每月收集 20 个回复。
* [敏锐](https://keen.io/) — 用于数据收集、分析和可视化的自定义分析。每月免费 1,000 个活动
* [Yandex.Datalens](https://datalens.yandex.com/) — Yandex Cloud 数据可视化和分析服务。该服务是免费提供的。对用户数量和请求数量没有限制。
* [Yandex.Metrica](https://metrica.yandex.com/) — 无限制的免费分析
* [Mixpanel](https://mixpanel.com/) — 每月 100,000 名跟踪用户、无限数据历史记录和席位、美国或欧盟数据驻留
* [Moesif](https://www.moesif.com) — REST 和 GraphQL 的 API 分析。（每月免费 500,000 次 API 调用）
* [optimizely.com](https://www.optimizely.com) — A/B 测试解决方案、免费入门计划、一个网站、1 个 iOS 和 1 个 Android 应用程序
* [Microsoft PowerBI](https://powerbi.com) — Microsoft 的业务见解和分析。免费计划提供 100 万个用户许可证的有限使用。
* 零[行](https://rowzero.io) \- 速度极快、互联的电子表格。直接连接到数据数据库、S3 和 API。即时导入、分析、绘制和共享数百万行。三个免费（永久）工作簿。
* [sematext.com](https://sematext.com/cloud/) — 每月最多可执行 50 K 次作、1 天数据保留、无限仪表板、用户等。
* [类似网络](https://similarweb.com) — 网络和移动应用程序分析。免费计划为每个指标提供五个结果，一个月的移动应用程序数据和 3 个月的网站数据。
* [StatCounter](https://statcounter.com/) — 网站查看器分析。用于分析 500 名最新访问者的免费计划。
* [Statsig](https://statsig.com) - 涵盖分析、功能标记和 A/B 测试的一体化平台。每月最多 1m 的计量事件免费。
* [Tableau 开发人员计划](https://www.tableau.com/developer) — 创新、创建并使 Tableau 完美地为您的组织工作。免费开发人员计划为 Tableau Online 提供个人开发沙盒许可证。该版本是最新的预发布版本，因此数据开发人员可以测试这个出色平台的每一个功能。
* [usabilityhub.com](https://usabilityhub.com/) — 在真人身上测试设计和模型并跟踪访客。一个用户免费，无限测试
* [woopra.com](https://www.woopra.com/) — 免费的用户分析平台，提供 500K 作、90 天数据保留、30+ 一键集成。
* [counter.dev](https://counter.dev) — 网络分析变得简单，因此对隐私友好。免费或通过捐赠支付您想要的费用。
* [PostHog](https://posthog.com) - 完整的产品分析套件免费每月最多可跟踪 1 万个事件。还提供每月 250 次回复的无限制应用内调查。
* [Uptrace](https://uptrace.dev) - 分布式跟踪工具，可帮助开发人员查明故障并找到性能瓶颈。有一个免费计划，为开源项目提供免费的个人订阅，并有一个开源版本。
* [Microsoft Clarity](https://clarity.microsoft.com/) - Clarity 是一款免费且易于使用的工具，可捕获真实用户如何使用您的网站。
* [Beampipe.io](https://beampipe.io) - Beampipe 是一款简单、注重隐私的 Web 分析。最多 5 个域免费，每月页面浏览量 10K。
* [Aptabase](https://aptabase.com) — 开源、隐私友好且简单的移动和桌面应用程序分析。适用于 Swift、Kotlin、React Native、Flutter、Electron 等的 SDK。每月最多可免费举办 20,000 个活动。
* [跟踪计划](https://www.trackingplan.com/) \- 自动检测数字分析、营销数据和像素问题，维护最新的跟踪计划，并促进无缝协作。将其部署到具有真实流量的生产环境中，或将分析覆盖率添加到回归测试中，而无需编写代码。
* [LogSpot](https://logspot.io) - 完全统一的 Web 和产品分析平台，包括可嵌入的分析小部件和自动化机器人（slack、telegram 和 webhooks）。免费计划包括每月 10,000 个活动。
* [Umami](https://umami.is/) - Google Analytics 的简单、快速、注重隐私的开源替代品。
* [TrackWith Dicloud](https://dicloud.net/trackwith-privacy-focused-analytics/) - 免费的轻量级、注重隐私的 Google Analytics 替代品。无限的页面浏览量、无限的访问者、无限的页面热图和目标跟踪。最多 3 个域免费，每个域 600 次会话重播。
* [AppFit](https://appfit.io) - AppFit 是一款全面的分析和产品管理工具，旨在促进分析和产品更新的无缝、跨平台管理。免费计划包括每月 10,000 个事件、产品日志和每周见解。
* [Seline](https://seline.so) - Seline 是一个简单且私人的网站和产品分析。无 Cookie、轻量级、独立。免费计划包括每月 3,000 个事件，并提供对我们所有功能的访问，例如仪表板、用户旅程、渠道等。
* [Peasy](https://peasy.so) - Peasy 是一款轻量级、注重隐私的网站和产品分析工具。免费计划包括每月 3,000 场活动。
* [Rybbit](https://rybbit.io) - Google Analytics 的开源且无 cookie 的替代方案，直观性提高了 10 倍。免费计划每月有 3,000 个活动。

**[⬆️ 返回首页](#目录)**

## 访客会话记录

* [Reactflow.com](https://www.reactflow.com/) — 每个站点：每天 1,000 次浏览、三个热图、三个小部件、免费错误跟踪
* [OpenReplay.com](https://www.openreplay.com) - 开源会话重播，使用用于 bug 重现的开发工具、用于实时支持的实时会话和产品分析套件。每月一千个会话，可访问所有功能和 7 天保留。
* [LogRocket.com](https://www.logrocket.com) - 每月 1,000 个会话，保留 30 天，错误跟踪，实时模式
* [FullStory.com](https://www.fullstory.com) — 每月 1,000 个会话，数据保留期为 1 个月，用户席位为 3 个。更多信息[在这里](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition) 。
* [hotjar.com](https://www.hotjar.com/) — 每个站点：每月 1,050 页浏览量，无限热图，数据存储三个月
* [inspectlet.com](https://www.inspectlet.com/) — 一个网站每月免费 2,500 次会话
* [Microsoft Clarity](https://clarity.microsoft.com/) - 会话录制完全免费，“无流量限制”，无项目限制，无采样
* [mouseflow.com](https://mouseflow.com/) — 一个网站每月免费 500 次会话
* [mousestats.com](https://www.mousestats.com/) — 一个网站每月免费 100 次会话
* [smartlook.com](https://www.smartlook.com/) — Web 和移动应用程序的免费套餐（1500 个会话/月）、三个热图、一个漏斗、1 个月的数据历史记录
* [howuku.com](https://howuku.com) — 跟踪用户交互、参与度和事件。每月最多 5,000 次访问免费
* [UXtweak.com](https://www.uxtweak.com/) — 记录和观察访问者如何使用您的网站或应用程序。小项目免费无限时间

**[⬆️ 返回首页](#目录)**

## 国际手机号码验证 API 和 SDK

* [numverify](https://numverify.com/) — 全局电话号码验证和查找 JSON API。100 个 API 请求/月
* [veriphone](https://veriphone.io/) — 在免费、快速、可靠的 JSON API 中进行全球电话号码验证。1000 个请求/月

**[⬆️ 返回首页](#目录)**

## 支付和计费集成

* [Qonversion](http://qonversion.io/) - 一体化跨平台订阅管理平台，提供分析、A/B 测试、Apple Search Ads、远程配置和增长工具，用于优化应用内购买和货币化。兼容 iOS、Android、React Native、Flutter、Unity、Cordova、Stripe 和 Web。每月免费提供高达 10 美元的跟踪收入。
* [ParityVend](https://www.ambeteco.com/ParityVend/) – 根据访客位置自动调整定价，以在全球范围内扩展您的业务并进入新市场（购买力平价）。免费计划包括每月 7,500 个 API 请求。
* [Glassfy](https://glassfy.io/) – iOS、Android、Stripe 和 Paddle 上的应用内订阅基础设施、实时订阅事件和开箱即用的货币化工具。每月免费高达 10 美元的收入。
* [Adapty.io](https://adapty.io/) – 具有开源 SDK 的一站式解决方案，用于将移动应用内订阅集成到 iOS、Android、React Native、Flutter、Unity 或 Web 应用程序。每月免费高达 10 美元的收入。
* [CoinMarketCap](https://coinmarketcap.com/api/) — 提供加密货币市场数据，包括最新的加密货币和法定货币汇率。免费套餐提供每月 10K 通话积分。
* [CurrencyFreaks](https://currencyfreaks.com/) — 提供当前和历史货币汇率。免费的 DEVELOPER 计划每月提供 1000 个请求。
* [CoinGecko](https://www.coingecko.com/en/api)：提供加密货币市场数据，包括最新的加密货币汇率和历史数据。演示 API 具有 30 次/分钟的稳定速率限制和每月 10,000 次调用的上限。
* [CurrencyApi](https://currencyapi.net/) — 实物和加密货币的实时货币汇率，以 JSON 和 XML 形式提供。免费套餐每月提供 1,250 个 API 请求。
* [currencylayer](https://currencylayer.com/) — 为您的企业提供可靠的汇率和货币兑换，每月免费 100 个 API 请求。
* [exchangerate-api.com](https://www.exchangerate-api.com) - 一个易于使用的货币转换 JSON API。免费套餐每天更新一次，每月限制为 1,500 个请求。
* [FraudLabsPRO](https://www.fraudlabspro.com) — 帮助商家防止支付欺诈和拒付。免费微型计划提供每月 500 次查询。
* [FxRatesAPI](https://fxratesapi.com) — 提供实时和历史汇率。免费套餐需要归因。
* [Moesif API 货币化](https://www.moesif.com/) \- 通过基于使用情况的计费从 API 中产生收入。连接到 Stripe、Chargebee 等。免费套餐每月提供 30,000 个事件。
* [Nami ML](https://www.namiml.com/) - 用于 iOS 和 Android 应用内购买和订阅的完整平台，包括无代码付费专区、CRM 和分析。免费使用运行 IAP 业务的所有基本功能。
* [RevenueCat](https://www.revenuecat.com/) — 用于应用内购买和订阅（iOS 和 Android）的托管后端。免费提供高达 2.5 美元/月的跟踪收入。
* [vatlayer](https://vatlayer.com/) — 即时增值税号验证和欧盟增值税税率 API，每月免费 100 个 API 请求
* [Currencyapi](https://currencyapi.com) — 免费的货币兑换和汇率数据 API。每月免费 300 个请求，每分钟 10 个请求供私人使用。

**[⬆️ 返回首页](#目录)**

## Docker 相关

* [canister.io](https://canister.io/) — 20 个免费私有存储库供开发人员使用，30 个免费私有存储库供团队构建和存储 Docker 镜像
* [容器注册表服务](https://container-registry.com/) \- 基于 Harbor 的容器管理解决方案。免费层为专用存储库提供 1 GB 的存储空间。
* [Docker Hub](https://hub.docker.com) — 一个免费的私有存储库和无限的公共存储库，用于构建和存储 Docker 镜像
* Play [with Docker](https://labs.play-with-docker.com/) — 一个简单、交互、有趣的 Docker 学习游乐场。
* [quay.io](https://quay.io/) — 使用无限的免费公共存储库构建和存储容器映像
* [ttl.sh](https://ttl.sh/) - 匿名和临时 Docker 镜像注册表

**[⬆️ 返回首页](#目录)**

## 流浪者相关

* [流浪者云](https://app.vagrantup.com) \- HashiCorp 流浪者云。流浪盒子托管。

**[⬆️ 返回首页](#目录)**

## 开发博客网站

* [BearBlog](https://bearblog.dev/) - 极简主义、由 Markdown 驱动的博客和网站构建器。
* [Dev.to](https://dev.to/) - 程序员分享想法并互相帮助成长的地方。
* [Hashnode](https://hashnode.com/) — 面向开发人员的无忧博客软件！
* [中等](https://medium.com/) — 更深思熟虑对您来说重要的事情。
* [AyeDot](https://ayedot.com/) — 以现代多媒体短格式迷你博客的形式免费与世界分享您的想法、知识和故事。

**[⬆️ 返回首页](#目录)**

## 评论平台

* [GraphComment](https://graphcomment.com/) - GraphComment 是一个评论平台，可帮助您从网站受众中建立一个活跃的社区。
* [话语](https://utteranc.es/) \- 基于 GitHub 问题构建的轻量级注释小组件。使用 GitHub 问题来获取博客评论、wiki 页面等！
* [Disqus](https://disqus.com/) - Disqus 是一个网络社区平台，被网络上数十万个网站使用。
* [Remarkbox](https://www.remarkbox.com/) - 开源托管评论平台，为“几个域的一名版主完全控制行为和外观”付费
* [IntenseDebate](https://intensedebate.com/) - 适用于 WordPress、Tumblr、Blogger 和许多其他网站平台的功能丰富的评论系统。

**[⬆️ 返回首页](#目录)**

## 屏幕截图 API

* [ApiFlash](https://apiflash.com) — 基于 Aws Lambda 和 Chrome 的屏幕截图 API。处理整页、捕获时间和视口尺寸。
* [microlink.io](https://microlink.io/) – 它将任何网站转换为数据，例如元标记规范化、美容链接预览、抓取功能或屏幕截图即服务。每天 250 个请求免费。
* [ScreenshotAPI.net](https://screenshotapi.net/) - 屏幕截图 API 使用简单的 API 调用来生成任何网站的屏幕截图。可扩展构建并在 Google Cloud 上托管。每月提供 100 张免费屏幕截图。
* [screenshotlayer.com](https://screenshotlayer.com/) — 捕获任何网站的高度可定制的快照。每月免费 100 个快照
* [screenshotmachine.com](https://www.screenshotmachine.com/) — 每月捕获 100 个快照、png、gif 和 jpg，包括全长捕获，而不仅仅是主页
* [PhantomJsCloud](https://PhantomJsCloud.com) — 浏览器自动化和页面渲染。免费套餐每天最多提供 500 页。自 2017 年起免费套餐。
* [Webshrinker.com](https://webshrinker.com) — Web Shrinker 提供网站截图和域智能 API 服务。每月免费 100 个请求。

**[⬆️ 返回首页](#目录)**

## Flutter 相关和构建 IOS 应用程序，无需 Mac

* [FlutLab](https://flutlab.io/) - FlutLab 是一款现代化的 Flutter 在线 IDE，是创建、调试和构建跨平台项目的最佳场所。使用 Flutter 构建 iOS（无需 Mac）和 Android 应用程序。
* [CodeMagic](https://codemagic.io/) - Codemagic 是一款完全托管和托管的移动应用程序 CI/CD。您可以使用基于 GUI 的 CI/CD 工具进行构建、测试和部署。免费套餐提供每月 500 分钟的免费时长，以及一个具有 2.3 GHz 和 8 GB RAM 的 Mac Mini 实例。
* [FlutterFlow](https://flutterflow.io/) - FlutterFlow 是一个基于浏览器的拖放界面，用于使用 Flutter 构建移动应用程序。

**[⬆️ 返回首页](#目录)**

## 用 Javascript 编写的基于浏览器的硬件仿真

* [JsLinux](https://bellard.org/jslinux) — 一个非常快速的 x86 虚拟机，能够运行 Linux 和 Windows 2k。
* [Jor1k](https://s-macke.github.io/jor1k/demos/main.html) — 一个能够运行 Linux 并支持网络的 OpenRISC 虚拟机。
* [v86](https://copy.sh/v86) — 一个 x86 虚拟机，能够将 Linux 和其他作系统直接运行到浏览器中。

**[⬆️ 返回首页](#目录)**

## 隐私管理

* [承载者](https://www.bearer.sh/) \- 通过审核和持续工作流帮助实施隐私设计，以便组织遵守 GDPR 和其他法规。免费套餐仅限于较小的团队和 SaaS 版本。
* [Osano](https://www.osano.com/) - 同意管理和合规平台，包含从 GDPR 表示到 cookie 横幅的所有内容。免费套餐提供基本功能。
* [Iubenda](https://www.iubenda.com/) - 隐私和 cookie 政策以及同意管理。免费套餐提供有限的隐私和 cookie 政策以及 cookie 横幅。
* [Cookiefirst](https://cookiefirst.com/) - Cookie 横幅、审计和多语言同意管理解决方案。免费套餐提供一次性扫描和单个横幅。
* [Ketch](https://www.ketch.com/) - 同意管理和隐私框架工具。免费套餐提供大多数功能，但访问者数量有限。
* [Concord](https://www.concord.tech/) - 完整的数据隐私平台，包括同意管理、隐私请求处理 （DSAR） 和数据映射。免费套餐包括核心同意管理功能，它们还为经过验证的开源项目免费提供更高级的计划。

**[⬆️ 返回首页](#目录)**

## 杂项

* [BackgroundStyler.com](https://backgroundstyler.com) - 创建代码、文本或图像的美观屏幕截图，以便在社交媒体上分享。
* [BinShare.net](https://binshare.net) - 创建和共享代码或二进制文件。可作为精美图像分享，例如 Twitter / Facebook 帖子或链接，例如聊天或论坛。
* [Blynk](https://blynk.io) — 一种带有 API 的 SaaS，用于控制、构建和评估物联网设备。免费开发者计划，配备 5 台设备、免费云和数据存储。还提供移动应用程序。
* [Bricks Note Calculator](https://free.getbricks.app/) - 一款笔记应用程序 （PWA），内置强大的多行计算器。
* [Carbon.now.sh](https://carbon.now.sh) - 以美观的类似屏幕截图的图像格式创建和共享代码片段。通常用于在 Twitter 或博客文章上美观地分享/炫耀代码片段。
* [Code Time](https://www.software.com/code-time) - VS Code、Atom、IntelliJ、Sublime Text 等中时间跟踪和编码指标的扩展。
* [Codepng](https://www.codepng.app) - 从您的源代码创建出色的快照以在社交媒体上分享。
* [CodeToImage](https://codetoimage.com/) - 创建代码或文本的屏幕截图以在社交媒体上分享。
* [Cronhooks](https://cronhooks.io/) - 安排准时或重复的 Webhook。免费计划允许 5 个临时时间表。
* [cron-job.org](https://cron-job.org) - 在线 cronjobs 服务。无限的工作是免费的。
* [datelist.io](https://datelist.io) - 在线预订/预约安排系统。每月最多免费 5 次预订，包括 1 个日历
* [域转发](https://domain-forward.com/) \- 转发任何 URL 或域的简单工具。每月最多免费 5 个域和 200k 请求。
* 元素 [— WordPress](https://elementor.com) 网站建设者。免费计划提供 40+ 基本小部件。
* [Exif 编辑器](https://exifeditor.io/) — 在浏览器中即时查看、编辑、拖动、分析图像/照片元数据 - 包括 GPS 位置和元数据。
* [Format Express](https://www.format-express.dev) - JSON / XML / SQL 的即时在线格式。
* [FOSSA](https://fossa.com/) - 针对第三方代码、许可证合规性和漏洞的可扩展端到端管理。
* [Hook Relay](https://www.hookrelay.dev/) - 轻松向应用添加 Webhook 支持：为您完成的队列、带回退的重试和日志记录。免费计划每天有 100 次交付、14 天保留和 3 个挂钩端点。
* [托管检查器](https://hostingchecker.co) \- 检查任何域、网站或 IP 地址的托管信息，例如 ASN、ISP、位置等。还包括多个托管和 DNS 相关工具。
* [kandi](https://kandi.openweaver.com/) — 快速启动应用程序开发：构建自定义函数和用例，并通过代码片段和开源库重用更快地完成应用程序。
* [Base64 解码器/编码器](https://devpal.co/base64-decode/) — 用于解码和编码数据的在线免费工具。
* [newreleases.io](https://newreleases.io/) - 接收来自 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM、Node.js Yarn、Ruby Gems、PHP Packagist、.NET NuGet、Rust Cargo 和 Docker Hub 的新版本的电子邮件、Slack、Telegram、Discord 和自定义 Webhook 通知。
* [OnlineExifViewer](https://onlineexifviewer.com/) — 立即在线查看照片的 EXIF 数据，包括 GPS 位置和元数据。
* [PDFMonkey](https://www.pdfmonkey.io/) — 在仪表板中管理 PDF 模板，使用动态数据调用 API，并下载 PDF。每月提供 300 份免费文档。
* [Pika 代码屏幕截图](https://pika.style/templates/code-image) — 使用扩展程序从代码片段和 VSCode 创建漂亮的、可自定义的屏幕截图。
* [QuickType.io](https://quicktype.io/) - 从 JSON、模式和 GraphQL 快速自动生成模型/类/类型/接口和序列化程序，以便使用任何编程语言快速安全地处理数据。将 JSON 转换为任何语言的华丽、类型安全的代码。
* [RandomKeygen](https://randomkeygen.com/) - 一款免费的移动友好工具，提供各种随机生成的密钥和密码，可用于保护任何应用程序、服务或设备。
* [ray.so](https://ray.so/) - 创建代码片段的精美图像。
* [readme.com](https://readme.com/) — 开源免费的精美文档变得简单。
* [redirection.io](https://redirection.io/) — 用于管理企业、营销和 SEO 的 HTTP 重定向的 SaaS 工具。
* [redirect.pizza](https://redirect.pizza/) - 通过 HTTPS 支持轻松管理重定向。免费计划包括 10 个来源和每月 100,000 次点击。
* [ReqBin](https://reqbin.com/) — 在线发布 HTTP 请求。常用的请求方法包括 GET、POST、PUT、DELETE 和 HEAD。支持标头和令牌身份验证。包括一个基本的登录系统，用于保存您的请求。
* [Smartcar API](https://smartcar.com) - 用于汽车定位、获取油箱、电池电量、里程表、解锁/锁门等的 API。
* [snappify](https://snappify.com) - 使开发人员能够创建令人惊叹的视觉效果。从精美的代码片段到完整的技术演示。免费计划包括一次最多 3 个快照，每月无限下载和 5 个人工智能驱动的代码解释。
* [日出和日落](https://sunrisesunset.io/api/) \- 获取给定经度和纬度的日出和日落时间。
* [superfeedr.com](https://superfeedr.com/) — 实时符合 PubSubHubbub 的提要、导出、分析。免费，定制更少
* [SurveyMonkey.com](https://www.surveymonkey.com) — 创建在线调查。在线分析结果。免费计划只允许每次调查 10 个问题和 100 个回复。
* [Tiledesk](https://tiledesk.com) - 创建聊天机器人和对话应用程序。为他们带来全渠道：从您的网站（实时聊天小部件）到 WhatsApp。具有无限聊天机器人的免费计划。
* [版本源](https://versionfeeds.com) — 用于您喜爱的软件版本的自定义 RSS 源。在一个提要中包含最新版本的编程语言、库或喜爱的工具。（前 3 次喂食免费）
* [videoinu](https://videoinu.com) — 在线创建和编辑屏幕录像和其他视频。
* [Webacus](https://webacus.dev) — 访问各种免费的开发人员工具，用于编码、解码和数据作。

**[⬆️ 返回首页](#目录)**

## 远程桌面工具

* [Getscreen.me](https://getscreen.me) — 2 台设备免费，会话数量和持续时间没有限制
* [Apache Guacamole™](https://guacamole.apache.org/) — 开源无客户端远程桌面网关
* [RemSupp](https://remsupp.com) — 按需支持和永久访问设备（每天免费 2 次）
* [RustDesk](https://rustdesk.com/) - 适合所有人的开源虚拟/远程桌面基础设施！
* [AnyDesk](https://anydesk.com) — 3 台设备免费，会话数量和持续时间没有限制

**[⬆️ 返回首页](#目录)**

## 游戏开发

* [itch.io](https://itch.io/game-assets) — 免费/付费资产，如精灵、图块集和角色包。
* [Gamefresco.com](https://gamefresco.com/) — 发现、收集和分享来自世界各地游戏艺术家的免费游戏资产。
* [GameDevMarket](https://gamedevmarket.net) — 免费/付费资产，如 2D、3D、音频、GUI。
* [OpenGameArt](https://opengameart.org) — 开源游戏资产，如音乐、声音、精灵和 gif。
* [CraftPix](https://craftpix.net) — 免费/付费资产，如 2D、3D、音频、GUI、背景、图标、图块集、游戏套件。
* [游戏图标](https://game-icons.net/) \- 根据 CC-BY 许可提供的免费可样式化的 SVG/PNG 图标。
* [LoSpec](https://lospec.com/) — 用于创建像素艺术和其他限制性数字艺术的在线工具，为您的游戏提供大量教程/托盘列表可供选择
* [ArtStation](https://www.artstation.com/) - 免费/付费 2D、3D 资产和音频、图标、图块集、游戏套件的 MarketPlace。此外，它还可用于展示您的艺术作品集。
* [Rive](https://rive.app/community/) - 社区资产以及使用其免费计划创建您自己的游戏资产。
* [Poly Pizza](https://poly.pizza/) - 免费的低多边形 3D 资产
* [3Dassets.one](https://3dassets.one/) - 超过 8,000 个免费/付费 3D 模型，以及用于制作纹理的 PBR 材质。
* [Kenney](https://www.kenney.nl/assets/) - 免费（CC0 1.0 通用许可）2D、3D、音频和 UI 游戏资产。
* [Poliigon](https://www.poliigon.com/) - 免费和付费纹理（具有可变分辨率）、模型、HDRI 和画笔。提供免费插件以导出到 Blender 等软件。
* [Freesound](https://freesound.org/) - 具有不同 CC 许可证的免费协作声音库提供商。

**[⬆️ 返回首页](#目录)**

## 其他免费资源

* [Wikimint Developer](https://developer.wikimint.com/p/tools.html) - 始终免费的 Web 开发人员工具，包括 CSS minify unminify、图像优化器、图像缩放器、大小写转换器、CSS 验证器、JavaScript 编译器、HTML 编辑器等。
* [ElevateAI](https://www.elevateai.com) - 每月免费获得长达 200 小时的音频转录。
* [get.localhost.direct](https://get.localhost.direct) — 更好的 `*.localhost.direct` 通配符公共 CA 签名的 SSL 证书，用于开发具有子域支持的本地主机
* [Framacloud](https://degooglisons-internet.org/en/) — 法国非营利组织 [Framasoft](https://framasoft.org/en/) 的自由/自由开源软件和 SaaS 列表。
* [github.com — 面向开发人员的 FOSS](https://github.com/tvvocold/FOSS-for-Dev) — 面向开发人员的免费开源软件中心。
* [GitHub Education](https://education.github.com/pack) — 面向学生的免费服务集合。需要注册。
* [Markdown 工具](https://markdowntools.com) \- 用于将 HTML、CSV、PDF、JSON 和 Excel 文件与 Markdown 进行转换的工具
* [Microsoft 365 开发人员计划](https://developer.microsoft.com/microsoft-365/dev-program) \- 获取为 Microsoft 365 平台构建解决方案所需的免费沙盒、工具和其他资源。该订阅是可续订的 90 天 [Microsoft 365 E5 订阅](https://www.microsoft.com/microsoft-365/enterprise/e5) （不包括 Windows）。如果您积极参与开发（使用遥测数据和算法进行测量），则会续订。
* [Pyrexp](https://pythonium.net/regex) — 免费的基于 Web 的正则表达式测试器和可视化工具，用于调试正则表达式。
* [面向开发人员的 RedHat](https://developers.redhat.com) — 免费访问专为开发人员提供的红帽产品，包括 RHEL、OpenShift、CodeReady 等。仅限个人计划。还提供免费电子书供参考。
* [sandbox.httpsms.com](https://sandbox.httpsms.com) — 免费发送和接收测试短信。
* [SimpleBackups.com](https://simplebackups.com/) — 直接存储到云存储提供商（AWS、DigitalOcean 和 Backblaze）中的服务器和数据库（MySQL、PostgreSQL、MongoDB）的备份自动化服务。提供 1 次备份的免费计划。
* [SnapShooter](https://snapshooter.com/) — 适用于 DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的备份解决方案，支持将数据库、文件系统和应用程序直接备份到基于 s3 的存储。提供免费计划，每天备份一个资源。
* [主题选择](https://themeselection.com/) — 精选高品质、现代设计、专业且易于使用的免费管理仪表板模板、HTML 主题和 UI 套件，以更快地创建您的应用程序！
* [Web.Dev](https://web.dev/measure/) — 这是一个免费工具，可让您查看网站的性能并改进 SEO 以在搜索引擎中获得更高的排名列表。
* [SmallDev.tools](https://smalldev.tools/) — 一款面向开发人员的免费工具，可让您编码/解码各种格式、缩小 HTML/CSS/Javascript、美化、以 JSON/CSV 和多种其他格式生成虚假/测试数据集以及更多功能。具有令人愉悦的界面。
* 通过 [Layercode 使用 CSV](https://layercode.com/usecsv) — 在几分钟内将 CSV 和 Excel 导入添加到您的 Web 应用程序。为您的用户提供愉快而强大的数据导入体验。无需任何信用卡详细信息即可免费开始，立即开始集成 UseCSV。您可以创建无限的导入器并上传最大 100Mb 的文件。
* [按钮生成器](https://markodenic.com/tools/buttons-generator/) — 您可以在项目中使用的 100+ 个按钮。
* [WrapPixel](https://www.wrappixel.com/) — 下载使用 Angular、React、VueJs、NextJS 和 NuxtJS 创建的高质量免费和高级管理仪表板模板！
* [Utils.fun](https://utils.fun/en) — 所有基于浏览器算力的离线日常和开发工具，包括水印生成、录屏、编解码、加解密、代码格式化等，都是完全免费的，不上传任何数据到云端进行处理。
* [IT 工具](it-tools.tech) \- 开发人员和 IT 人员的有用工具。
* [免费代码工具](https://freecodetools.org/) — 100% 免费的有效代码工具。Markdown 编辑器、代码缩小器/美化器、QR 码生成器、Open Graph 生成器、Twitter 卡片生成器等。
* [regex101](https://regex101.com/) — 免费此网站允许您测试和调试正则表达式 （regex）。它提供了正则表达式编辑器和测试器，以及用于学习正则表达式的有用文档和资源。
* [科迪工具](https://www.kodytools.com/dev-tools) — 100+ 开发工具，包括格式化程序、缩小器和转换器。
* [AdminMart](https://adminmart.com/) — 使用 Angular、Bootstrap、React、VueJs、NextJS 和 NuxtJS 创建的高质量免费和高级管理仪表板和网站模板！
* [Glob 测试器](https://globster.xyz/) — 一个允许您设计和测试 glob 模式的网站。它还提供了学习 glob 模式的资源。
* [SimpleRestore](https://simplerestore.io) - 无忧的 MySQL 备份恢复。将 MySQL 备份恢复到任何远程数据库，无需代码或服务器。
* [360Converter](https://www.360converter.com/) - 免费套餐，有用的网站，可转换：视频到文本，音频到文本，语音到文本，实时音频到文本，YouTube 视频到文本，添加视频字幕。也许它会在短视频转换或简短的 youtube 教程中有所帮助：）
* [QRCodeBest](https://qrcode.best/) - 使用 13 个模板、完全隐私和个人品牌创建自定义 QR 码。在 QRCode.Best 上具有跟踪像素、项目分类和无限团队席位的功能。
* [PostPulse](https://PostPulseAI.com) - 通过每月向 SEO 优化域发送 AI 制作的帖子，提升您的在线形象，提高您的 SEO 和网站排名免费计划允许您每月在我们的网站上手动发布一篇帖子。
* [PageTools](https://pagetools.co/) - 提供一套永久免费的人工智能工具，帮助您通过简单的一键式界面生成基本的网站策略、创建社交媒体简介、帖子和网页。
* [MySQL Visual Explain](https://mysqlexplain.com) - 易于理解且免费的 MySQL EXPLAIN 输出可视化工具，用于优化慢速查询。
* [Killer Coda](https://killercoda.com/) - 浏览器中的交互式游乐场，用于学习 Linux、Kubernetes、容器、编程、DevOps、网络
* [Axonomy 应用程序](https://axonomy-app.com/) \- 一个免费工具，用于创建、管理和与客户共享您的发票。每月 10 张免费发票。
* [表格格式转换器](https://www.tableformatconverter.com) \- 一个免费工具，用于将表格数据转换为不同的格式，例如 CSV、HTML、JSON、Markdown 等。

**[⬆️ 返回首页](#目录)**
