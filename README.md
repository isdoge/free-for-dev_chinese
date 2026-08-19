# free-for.dev 中文汉化版

<!-- zh-localization-note -->
> [!IMPORTANT]
> ### AI 辅助汉化与版本说明
> 本仓库是上游 [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev) 的非官方中文汉化维护版，**仅同步并汉化上游 README**。
>
> - **AI 辅助汉化**：README 中文说明由 AI 辅助翻译与校对；服务名、产品名、项目名、Markdown 链接文字和 URL 原则上保持上游原文。
> - **内容贡献请提交到上游**：如需新增或删除服务、调整免费额度、链接、服务说明等内容，请直接前往上游 [ripienaar/free-for-dev](https://github.com/ripienaar/free-for-dev) 提交 Issue / Pull Request。待上游合并后，本仓库在后续同步中跟进并汉化。
> - **展示样式有调整**：本汉化版对 README 的阅读样式做了少量本地化调整，包括中文标题与目录、中文分类标题，以及使用 GitHub 原生 `<details>` / `<summary>` 折叠各分类的长服务列表；原英文锚点继续保留，便于兼容旧目录链接和外部引用。
> - **以上游和服务官网为准**：AI 翻译可能存在术语或语义偏差，服务免费额度也可能随时变化；如有差异，请以上游最新 README 及服务官网为准。

如今有许多服务为开发者和开源作者提供免费套餐，但要找到并逐一评估这些服务仍需要花费大量时间。

这是一个提供开发者免费套餐的软件（SaaS、PaaS、IaaS 等）及其他服务的列表。

本列表仅收录基础设施开发者（系统管理员、DevOps 从业者等）可能会用到的内容。我们也喜欢其他各类免费服务，但仍希望列表保持主题聚焦。某些项目是否属于收录范围难免存在灰色地带，因此判断会带有主观性；如果你的贡献未被接受，请不要介意。

本列表由 1600 多位贡献者通过 Pull Request、审查、建议及其他工作共同完成。你也可以提交 [Pull Requests](https://github.com/ripienaar/free-for-dev)，添加更多服务，或移除免费方案已变更、已经停止运营的服务。

[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/ripienaar/free-for-dev)

**注意**：本列表只收录“即服务”类产品，不收录需要自行托管的软件。符合条件的服务必须提供免费套餐，而不能只是免费试用；如果免费额度按时间提供，则至少应持续一年。我们也会从安全角度评估免费套餐，因此支持 SSO 没有问题，但不会接受仅在付费套餐中提供 TLS 的服务。

<a id="table-of-contents"></a>
# 目录

  * [主要云服务商永久免费额度](#major-cloud-providers)
  * [云管理解决方案](#cloud-management-solutions)
  * [分析、事件与统计](#analytics-events-and-statistics)
  * [API、数据与机器学习](#apis-data-and-ml)
  * [制品仓库](#artifact-repos)
  * [BaaS（后端即服务）](#baas)
  * [低代码平台](#low-code-platform)
  * [CDN 与防护](#cdn-and-protection)
  * [CI / CD](#ci-and-cd)
  * [CMS（内容管理系统）](#cms)
  * [代码生成](#code-generation)
  * [代码质量](#code-quality)
  * [代码搜索与浏览](#code-search-and-browsing)
  * [崩溃与异常处理](#crash-and-exception-handling)
  * [地图数据可视化](#data-visualization-on-maps)
  * [托管数据服务](#managed-data-services)
  * [设计与 UI](#design-and-ui)
  * [开发者博客平台](#dev-blogging-sites)
  * [DNS](#dns)
  * [Docker 相关](#docker-related)
  * [域名](#domain)
  * [教育与职业发展](#education-and-career-development)
  * [邮件](#email)
  * [功能开关管理平台](#feature-toggles-management-platforms)
  * [字体](#font)
  * [表单](#forms)
  * [生成式 AI](#generative-ai)
  * [IaaS（基础设施即服务）](#iaas)
  * [IDE 与代码编辑](#ide-and-code-editing)
  * [国际手机号码验证 API 与 SDK](#international-mobile-number-verification-api-and-sdk)
  * [问题跟踪与项目管理](#issue-tracking-and-project-management)
  * [日志管理](#log-management)
  * [移动应用分发与反馈](#mobile-app-distribution-and-feedback)
  * [管理系统](#management-system)
  * [消息与流处理](#messaging-and-streaming)
  * [其他](#miscellaneous)
  * [监控](#monitoring)
  * [PaaS（平台即服务）](#paas)
  * [软件包构建系统](#package-build-system)
  * [支付与计费集成](#payment-and-billing-integration)
  * [隐私管理](#privacy-management)
  * [截图 API](#screenshot-apis)
  * [Flutter 相关及无 Mac 构建 iOS 应用](#flutter-related-and-building-ios-apps-without-mac)
  * [搜索](#search)
  * [安全与 PKI](#security-and-pki)
  * [身份认证、授权与用户管理](#authentication-authorization-and-user-management)
  * [源代码仓库](#source-code-repos)
  * [存储与媒体处理](#storage-and-media-processing)
  * [隧道、WebRTC、WebSocket 服务器与其他路由](#tunneling-webrtc-web-socket-servers-and-other-routers)
  * [测试](#testing)
  * [团队与协作工具](#tools-for-teams-and-collaboration)
  * [翻译管理](#translation-management)
  * [访客会话录制](#visitor-session-recording)
  * [Web 托管](#web-hosting)
  * [评论平台](#commenting-platforms)
  * [远程桌面工具](#remote-desktop-tools)
  * [其他免费资源](#other-free-resources)

<a id="major-cloud-providers"></a>
## 主要云服务商

<details>
<summary>展开 / 收起服务列表</summary>

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 每天 28 小时前端实例时长、9 小时后端实例时长
    * Cloud Firestore - 1GB 存储空间；每天 50,000 次读取、20,000 次写入和 20,000 次删除
    * Compute Engine - 1 台不可抢占的 e2-micro 实例、30GB HDD、5GB 快照存储（仅限部分地区），每月从北美到所有地区目的地（中国和澳大利亚除外）提供 1GB 网络出站流量
    * Cloud Storage - 5GB 存储空间、1GB 网络出站流量
    * Cloud Shell - 基于 Web 的 Linux Shell/主要 IDE，含 5GB 永久存储空间，每周限用 60 小时
    * Cloud Pub/Sub - 每月 10GB 消息量
    * Cloud Functions - 每月 200 万次调用（包括后台调用和 HTTP 调用）
    * Cloud Run - 每月 200 万次请求、360,000 GB-秒内存、180,000 vCPU-秒计算时间，以及从北美出站的 1GB 网络流量
    * Google Kubernetes Engine - 1 个单可用区集群免收集群管理费；各用户节点按 Compute Engine 标准价格计费
    * BigQuery - 每月 1TB 查询量和 10GB 存储空间
    * Cloud Build - 每天 120 分钟构建时间
    * [Google Colab](https://colab.research.google.com/) - 免费的 Jupyter Notebooks 开发环境。
    * [Kaggle](https://www.kaggle.com/) - 提供 4 核 CPU 和 30GB RAM 的 Jupyter Notebooks 计算环境，不设每周使用时长上限。验证手机号后，可免费添加 1 块 Nvidia Tesla P100 GPU 或 2 块 Nvidia Tesla T4 GPU，每周最多使用 30 GPU 小时。完成身份验证后，可使用配有 96 核 CPU 和 330GB RAM 的 1 个 TPU v3-8，每周最多免费使用 20 小时。更多信息请查看 [Technical Specifications](https://www.kaggle.com/docs/notebooks#technical-specifications)。
    * [ChromeRemoteDesktop](https://remotedesktop.google.com/) - Google 提供的免费远程桌面应用，设备数量基本不受限制，但需要 Google 账号。
    * [Google AI Studio](https://aistudio.google.com/) - 可免费使用 Gemini 3.5 Flash、Gemini 3 Flash 和 Gemma 4 模型。Flash 免费套餐每分钟 5 次请求、每天 20 次请求、每分钟 25 万输入 Token；Gemma 4 免费套餐每分钟 30 次请求、每天 14,400 次请求，但每分钟输入 Token 仅 16,000。
    * 完整详细列表 - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - 每月 1TB 出站流量、1000 万次 HTTP 请求，以及每月 200 万次 Function 调用
    * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 10 个自定义指标和告警、100 万次 API 请求、5GB 日志数据摄取和 5GB 日志数据归档
    * [CodeBuild](https://aws.amazon.com/codebuild/) - 每月 100 分钟构建时间
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 5 个活跃用户、每个账户 5000 个仓库、每月 50GB 存储空间和 10000 次请求
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - 每月 1 条活跃流水线
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL 数据库
    * [Lambda](https://aws.amazon.com/lambda/) - 每月 100 万次请求
    * [SNS](https://aws.amazon.com/sns/) - 每月 100 万次发布
    * [SES](https://aws.amazon.com/ses/) - 每月 3000 条消息（6 个月）
    * [SQS](https://aws.amazon.com/sqs/) - 每月 100 万次消息队列请求
    * 完整详细列表 - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 个 Web、移动或 API 应用（每天 60 CPU 分钟）
    * [Functions](https://azure.microsoft.com/services/functions/) - 每月 100 万次请求
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - 快速、简便、精简地搭建开发与测试环境
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 个对象
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 每月可存储 50,000 名用户
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 个活跃用户、无限私有 Git 仓库
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) - 为 Linux、macOS 和 Windows 开源项目提供 10 个免费并行作业和无限构建时长
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 每天 8,000 条消息
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 750 小时、15GB 数据处理量和 5 条规则（12 个月）
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 100 万次推送通知
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 15GB 出站流量（12 个月）
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 25GB 存储空间和 1000 RU 预配吞吐量
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) - 构建、部署并托管静态应用与无服务器函数，免费提供 SSL、身份认证/授权及自定义域名
    * [Storage](https://azure.microsoft.com/services/storage/) - 100GB LRS 事务（Azure Files）、5GB Blob 存储、10GB LRS Archive Storage、2×64GB SSD（12 个月）
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML API（计算机视觉、翻译、人脸检测、机器人等），免费套餐包含有限事务量
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - 基于 AI 的搜索和索引服务，最多免费处理 10,000 份文档
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - 托管 Kubernetes 服务，免收集群管理费
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 每月 100,000 次操作
    * [Service Bus](https://azure.microsoft.com/products/service-bus/) - Standard 层基础单元提供 750 小时和 1300 万次操作（12 个月）
    * 完整详细列表 - https://azure.microsoft.com/free/

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * Compute
       - 2 台基于 AMD 的计算 VM，每台配备 1/8 OCPU 和 1GB 内存
       - 2 个基于 Arm 的 Ampere A1 核心及 12GB 内存，可作为 1 台 VM 使用，也可拆分为最多 2 台 VM
       - 实例在被[deemed idle](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)时会被回收
    * Block Volume - 2 个卷，共 200GB（供计算实例使用）
    * Object Storage - 10GB
    * Load balancer - 1 个 10Mbps 实例
    * Databases - 2 个数据库，每个 20GB
    * Monitoring - 5 亿个写入数据点、10 亿个读取数据点
    * Bandwidth - 每月 10TB 出站流量；x64 VM 限速 50Mbps，ARM VM 限速为 500Mbps × 核心数
    * Public IP - VM 可使用 2 个 IPv4，负载均衡器可使用 1 个 IPv4
    * Notifications - 每月 100 万次投递操作和 1,000 封邮件
    * 完整详细列表 - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloudant database - 1GB 数据存储
    * Db2 database - 100MB 数据存储
    * API Connect - 每月 50,000 次 API 调用
    * Availability Monitoring - 每月 300 万个数据点
    * Log Analysis - 每天 500MB 日志
    * 完整详细列表 - https://www.ibm.com/cloud/free/

  * [Cloudflare](https://www.cloudflare.com/)
    * [Application Services](https://www.cloudflare.com/plans/) - 无限域名的免费 DNS、DDoS 防护、CDN、免费 SSL、防火墙规则和页面规则、WAF、机器人防护、免费不限流量的速率限制（每个域名 1 条规则）、分析及邮件转发
    * [Zero Trust & SASE](https://www.cloudflare.com/plans/zero-trust-services/) - 最多 50 名用户、24 小时活动日志和 3 个网络位置
    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) - 可使用 [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/) 将本地 HTTP 端口通过隧道公开到 trycloudflare.com 的随机子域名，无需账号。[Zero Trust](https://www.cloudflare.com/products/zero-trust/) 免费方案还提供 TCP 隧道、负载均衡和 VPN 等更多功能。
    * [Workers](https://developers.cloudflare.com/workers/) - 在 Cloudflare 全球网络上免费部署无服务器代码，每天 100,000 次请求。
    * [Workers KV](https://developers.cloudflare.com/kv) - 每天 100,000 次读取、1,000 次写入、1,000 次删除和 1,000 次列表请求，另含 1GB 存储空间
    * [R2](https://developers.cloudflare.com/r2/) - 每月 10GB、100 万次 A 类操作和 1,000 万次 B 类操作
    * [D1](https://developers.cloudflare.com/d1/) - 每天读取 500 万行、写入 100,000 行，另含 1GB 存储空间
    * [Pages](https://developers.cloudflare.com/pages/) - 在 Cloudflare 快速、安全的全球网络上开发和部署 Web 应用。每月 500 次构建、100 个自定义域名、集成 SSL、无限席位、无限预览部署，并可通过 Cloudflare Workers 集成实现全栈功能。
    * [Queues](https://developers.cloudflare.com/queues/) - 每月 100 万次操作
    * [TURN](https://developers.cloudflare.com/calls/turn/) - 每月 1TB 免费出站流量。

  * [Zoho](https://www.zoho.com) - 最初是一家电子邮件服务商，现在已提供一整套服务，其中部分服务拥有免费方案。提供免费方案的服务包括：
    * [Catalyst by Zoho](https://catalyst.zoho.com) - 提供慷慨[free tier](https://catalyst.zoho.com/free-tier.html)的 PaaS/全栈云平台
    * [Zoho Apptics](https://www.zoho.com/apptics/) - 统一、可执行的产品分析平台，用于监控移动端、Web 和桌面应用性能，分析用户行为并收集反馈，提供长期免费的慷慨套餐。
    * [Email](https://zoho.com/mail) 免费供 5 名用户使用，每名用户 5GB，附件上限 25MB，支持 1 个域名。
    * [Zoho Assist](https://www.zoho.com/assist) - 永久免费方案包含 1 个并发远程支持许可证和 5 个无人值守电脑许可证，使用时长不限，可供专业或个人用途。
    * [Sprints](https://zoho.com/sprints) 免费供 5 名用户使用，支持 5 个项目和 500MB 存储空间。
    * [Docs](https://zoho.com/docs) - 免费供 5 名用户使用，单次上传上限 1GB，总存储 5GB，并附带 Zoho Office Suite（Writer、Sheets 与 Show）。
    * [Projects](https://zoho.com/projects) - 免费供 3 名用户使用，支持 2 个项目，附件上限 10MB。[Bugtracker](https://zoho.com/bugtracker) 使用相同套餐。
    * [Connect](https://zoho.com/connect) - 团队协作服务，免费供 25 名用户使用，含 3 个群组、3 个自定义应用、3 个看板、3 本手册、10 个集成，以及频道、活动和论坛。
    * [Meeting](https://zoho.com/meeting) - 会议最多 3 名参会者，网络研讨会最多 10 名观众。
    * [Vault](https://zoho.com/vault) - 个人用户可免费使用密码管理功能。
    * [Showtime](https://zoho.com/showtime) - 另一款远程培训会议软件，最多支持 5 名参会者。
    * [Notebook](https://zoho.com/notebook) - Evernote 的免费替代品。
    * [Wiki](https://zoho.com/wiki) - 免费供 3 名用户使用，含 50MB 存储、无限页面、ZIP 备份、RSS 与 Atom 订阅、访问控制和可自定义 CSS。
    * [Subscriptions](https://zoho.com/subscriptions) - 循环计费管理，免费支持 20 名客户/订阅和 1 名用户，支付托管均由 Zoho 完成，并保存最近 40 项订阅指标。
    * [Checkout](https://zoho.com/checkout) - 产品计费管理，支持 3 个页面和最多 50 笔付款。
    * [Desk](https://zoho.com/desk) - 客户支持管理，支持 3 名坐席、私有知识库和邮件工单。可与 [Assist](https://zoho.com/assist) 集成，提供 1 名远程技术人员和 5 台无人值守电脑。
    * [Cliq](https://zoho.com/cliq) - 团队聊天软件，含 100GB 存储、无限用户、每个频道 100 名用户及 SSO。
    * [Campaigns](https://zoho.com/campaigns) - 电子邮件营销
    * [Forms](https://zoho.com/forms) - 表单创建工具
    * [Sign](https://zoho.com/sign) - 无纸化签名
    * [Surveys](https://zoho.com/surveys) - 在线调查
     * [Bookings](https://zoho.com/bookings) - 预约排期

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="cloud-management-solutions"></a>
## 云管理解决方案

<details>
<summary>展开 / 收起服务列表</summary>

  * [Brainboard](https://www.brainboard.co) - 用于端到端可视化构建和管理云基础设施的协作解决方案。
  * [Cloud 66](https://www.cloud66.com/) - 个人项目免费（含 1 台部署服务器和 1 个静态站点），提供在任意云上构建、部署和扩展应用所需的一切功能，无需处理繁琐的服务器运维。
  * [deployment.io](https://deployment.io) - 帮助开发者自动化 AWS 部署。免费套餐中，单个开发者可部署无限静态站点、Web 服务和环境；每月免费执行 10 个作业，并包含预览和自动部署。
  * [Parsivex](https://www.parsivex.com) - 扫描 AWS 账户中的闲置 EC2、未挂载 EBS、规格过大的 RDS、过期快照、NAT 网关过度使用等。免费层每月可扫描 1 个 AWS 账户，并返回每月浪费总额及分类明细；付费计划提供逐项结果和定时复扫。
  * [Pulumi](https://www.pulumi.com/) - 现代基础设施即代码平台，可使用熟悉的编程语言和工具构建、部署及管理云基础设施。
  * [scalr.com](https://scalr.com/) - Terraform 自动化与协作（TACO）产品，用于改善 Terraform 管理的基础设施和配置协作及自动化。完整支持 Terraform CLI、OPA 集成和分层配置模型，不额外收取 SSO 费用，所有功能均包含在内，每月最多免费运行 50 次。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="source-code-repos"></a>
## 源代码仓库

<details>
<summary>展开 / 收起服务列表</summary>

  * [Bitbucket](https://bitbucket.org/) - 最多 5 名用户可使用无限公开和私有 Git 仓库，并提供 Pipelines CI/CD
  * [Codeberg](https://codeberg.org/) - 为自由及开源项目提供无限公开和私有 Git 仓库及无限协作者。基于 [Forgejo](https://forgejo.org/)，还提供 [Codeberg Pages](https://codeberg.page/) 静态网站托管、[Codeberg's CI](https://docs.codeberg.org/ci/) CI/CD、[Codeberg Translate](https://translate.codeberg.org/) 翻译托管，以及软件包/容器托管、项目管理和问题跟踪
  * [framagit.org](https://framagit.org/) - 基于 GitLab 的 Framasoft 软件开发平台，包含 CI、静态页面、项目页面和问题跟踪。
  * [GitGud](https://gitgud.io) - 无限私有和公开仓库，永久免费。基于 GitLab 与 Sapphire，包含 CI/CD、静态托管、容器注册表、项目管理和问题跟踪。
  * [GitHub](https://github.com/) - 无限公开和私有仓库（协作者数量不限），包含 CI/CD、开发环境、静态托管、软件包与容器托管、项目管理及 AI Copilot
  * [gitlab.com](https://about.gitlab.com/) - 无限公开和私有 Git 仓库，最多 5 名协作者，包含 CI/CD、静态托管、容器注册表、项目管理和问题跟踪
  * [heptapod.net](https://foss.heptapod.net/) - GitLab 社区版的友好分支，提供 Mercurial 支持
  * [pijul.com](https://pijul.com/) - 免费、无限制的开源分布式版本控制系统。其特色是基于严谨的补丁理论，易于学习、使用和分发，并解决了 git/hg/svn/darcs 的许多问题。
  * [projectlocker.com](https://projectlocker.com) - 1 个免费私有项目（Git 或 Subversion），含 50MB 空间
  * [RocketGit](https://rocketgit.com) - 基于 Git 的仓库托管，公开和私有仓库数量不限。
  * [savannah.gnu.org](https://savannah.gnu.org/) - 为自由软件项目提供协作式软件开发管理系统（面向 GNU 项目）
  * [savannah.nongnu.org](https://savannah.nongnu.org/) - 为自由软件项目提供协作式软件开发管理系统（面向非 GNU 项目）

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="apis-data-and-ml"></a>
## API、数据与机器学习

<details>
<summary>展开 / 收起服务列表</summary>

  * [Abstract API](https://www.abstractapi.com) - 面向多种用途的 API 套件，包括 IP 地理位置、电话号码验证和电子邮件验证。
  * [AlphaAI](https://alphai.io/developers) - 金融新闻 API 与 MCP 服务器。每篇文章都会按股票代码分析影响、归类并给出 1–10 的相关性评分，同时将 SEC Form 4 内幕交易申报转为评分事件。REST 和 MCP 免费套餐均提供每分钟 20 次、每天 100 次请求，无需信用卡。
  * [AnyHook](https://anyhook.net) - 入站 webhook 中继：将 Stripe、GitHub 或 LINE Bot webhook 指向它，每个事件会先存储再投递到处理器，端点离线时会自动重试，并保留可重放的日志。无需账户即可通过 API 创建端点。免费计划每月 3000 个事件、1 个应用、3 次重试、保留 3 天，无需信用卡。
  * [Apify](https://www.apify.com/) - Web 抓取与自动化平台，可为任意网站创建 API 并提取数据，提供现成爬虫、集成代理和定制方案。免费方案每月含 5 美元平台额度。
  * [APITemplate.io](https://apitemplate.io) - 通过简单 API 或 Zapier、Airtable 等自动化工具自动生成图片和 PDF，无需 CSS/HTML。免费方案每月 50 张图片和 3 个模板。
  * [APIVerve](https://apiverve.com) - 可免费即时访问 120 多个注重质量、一致性与可靠性的 API。免费方案每月最多 50 个 API Token。（可能已下线，2025-06-25）
  * [Arize AI](https://arize.com/) - 机器学习可观测性平台，用于模型监控以及定位数据质量和性能漂移等问题，最多可免费监控 2 个模型。
  * [Beeceptor](https://beeceptor.com) - 无代码云端多协议 API（REST、SOAP、gRPC 和 GraphQL）模拟与调试平台，可快速创建带规则逻辑、CRUD、有状态模拟、代理和 CORS 管理的服务器，加快集成与测试。免费方案每天 50 次请求，并提供公开仪表板/端点，任何持有仪表板 URL 的人都能查看提交的请求和响应。
  * [BigDataCloud](https://www.bigdatacloud.com/) - 为现代 Web 提供快速、准确且免费的 API（不限量或每月 10K–50K），涵盖 IP 地理位置、反向地理编码、网络洞察、电子邮件与电话验证、客户端信息等。
  * [Brave Search API](https://brave.com/search/api/) - 独立的 Web、新闻、图片、视频搜索及 AI/LLM 上下文 API，适合 RAG 流程和 AI Agent。免费套餐每月含 5 美元额度（验证时需要信用卡）。
  * [Browse AI](https://www.browse.ai) - 提取并监控网页数据。每月免费 1,000 积分，相当于 1,000 个并发请求。
  * [Calendarific](https://calendarific.com) - 覆盖 200 多个国家/地区的企业级公共节假日 API，免费方案每月 500 次调用。
  * [Canopy](https://www.canopyapi.co/) - 提供 Amazon.com 商品、搜索和分类数据的 GraphQL API，免费方案每月 100 次调用。
  * [CarAPI.dev](https://carapi.dev) - 综合汽车数据 API，支持 VIN 解码、失窃车辆检查、车辆估值、检查数据等。免费套餐可在全部 9 个端点上每月请求 100 次。
  * [CatchDoms](https://catchdoms.com) - 聚合 16 个市场的过期和即将删除域名列表，并补充反向链接、Trust Flow、Wayback 历史和质量评分等 SEO 数据。免费方案含 10 个解锁列表、5 个收藏和 3 个保存搜索；注册后 7 天 Pro 试用包含完整 REST API 和 MCP 服务器访问。
  * [Cloudmersive](https://cloudmersive.com/) - 实用 API 平台，可访问文档转换、病毒扫描等完整 API 库；每月 600 次调用，仅限北美可用区，最大文件 2.5MB。
  * [Colaboratory](https://colab.research.google.com) - 免费的 Web Python Notebook 环境，配备 Nvidia Tesla K80 GPU。
  * [CometML](https://www.comet.com/site/) - 用于实验跟踪、生产模型管理、模型注册及完整数据血缘的 MLOps 平台，覆盖从训练到生产的整个工作流。个人和学术用户免费。
  * [Commerce Layer](https://commercelayer.io) - 可组合商业 API，可从任意前端构建、创建和管理订单。开发者方案每月免费 100 个订单，最多 1,000 个 SKU。
  * [Composio](https://composio.dev/) - 面向 AI Agent 与 LLM 的集成平台，可连接 Agent 互联网中的 200 多种工具。
  * [Conversion Tools](https://conversiontools.io/) - 文档、图片、视频、音频和电子书在线文件转换器，提供 REST API 以及 Node.js、PHP、Python 库。付费方案最大支持 50GB；免费套餐受文件大小（20MB）和转换次数（每天 30 次、每月 300 次）限制。
  * [Country-State-City Microservice API](https://country-state-city.rebuscando.info/) - API 与微服务，提供国家、地区、省份、城市、邮政编码等大量信息，免费套餐每天最多 100 次请求。
  * [Coupler](https://www.coupler.io/) - 在应用间同步数据的数据集成工具，可创建实时仪表板和报告、转换处理数据并收集备份洞察。免费方案仅限 1 名用户、1 个数据连接、1 个数据源和 1 个目标，并且需要手动刷新数据。
  * [CraftMyPDF](https://craftmypdf.com) - 通过拖放编辑器和简单 API，使用可复用模板自动生成 PDF。免费方案每月 100 份 PDF 和 3 个模板。
  * [Cube](https://cube.dev/) - 帮助数据工程师和应用开发者访问现代数据存储，将数据组织为一致定义并交付给各种应用。使用 Cube 最快捷的方式是 Cube Cloud，其免费套餐每天最多 1,000 次查询。
  * [CurlHub](https://curlhub.io) - 用于检查和调试 API 调用的代理服务，免费方案每月 10,000 次请求。
  * [CurrencyScoop](https://currencyscoop.com) - 面向金融科技应用的实时货币数据 API，免费方案每月 5,000 次调用。
  * [CustomJS](https://www.customjs.io) - 提供 HTML 转 PDF、PDF 转 PNG/文本，以及 PDF 合并/提取等 API。免费套餐每月 600 次调用。
  * [Data Fetcher](https://datafetcher.com) - 无需代码即可将 Airtable 连接到任意应用或 API，提供类似 Postman 的 Airtable 内 API 请求界面，并预置数十种应用集成。免费方案每月 100 次运行。
  * [Data Miner](https://dataminer.io/) - 从网页提取 CSV 或 Excel 数据的浏览器扩展（Google Chrome、MS Edge），免费方案每月 500 页。
  * [Dataimporter.io](https://www.dataimporter.io) - 用于连接、清理数据并导入 Salesforce 的工具，免费方案每月最多 20,000 条记录。
  * [Datalore](https://datalore.jetbrains.com) - JetBrains 提供的 Python Notebook，每月含 10GB 存储空间和 120 小时运行时间。
  * [DB Designer](https://www.dbdesigner.net/) - 云端数据库模式设计与建模工具，免费入门方案支持 2 个数据库模型，每个模型 10 张表。
  * [DB-IP](https://db-ip.com/api/free) - 免费 IP 地理位置 API，每个 IP 每天 1,000 次请求；采用 CC-BY 4.0 许可证的 Lite 数据库同样免费。
  * [DeepAR](https://developer.deepar.ai) - 面向任意平台的增强现实人脸滤镜 SDK，免费方案最多 10 个每月活跃用户，并可跟踪最多 4 张人脸。
  * [Deepnote](https://deepnote.com) - 新型数据科学 Notebook，兼容 Jupyter，支持实时协作和云端运行。免费套餐包含无限个人项目、无限基础机器（5GB RAM、2 vCPU），团队最多 3 名编辑者。
  * [Compare JSON](https://comparejson.com) - 在线比较两个 JSON 数据结构差异的工具，可快速定位 JSON 数据差异。
  * [Disease.sh](https://disease.sh/) - 免费 API，提供用于构建 COVID-19 相关应用的准确数据。
  * [Doczilla](https://www.doczilla.app/) - 可直接从 HTML/CSS/JS 代码生成截图或 PDF 的 SaaS API，免费方案每月 250 份文档。
  * [Doppio](https://doppio.sh/) - 使用先进渲染技术生成并私密存储 PDF 和截图的托管 API，免费方案每月 400 份 PDF/截图。
  * [DocPenny](https://docpenny.com) - 基于模板的 HTML 转 PDF 文档生成服务，支持 Webhook 投递和积分计费。免费方案每月 50 积分，无需信用卡。
  * [Doqlo](https://doqlo.com/) - 通过 Web 应用或公共 API，从 CSV 批量填写和邮件合并 PDF 表单。免费方案每月 100 份输出 PDF。
  * [drawDB](https://drawdb.app/) - 免费开源的在线数据库图表编辑器，无需注册。
  * [DynamicDocs](https://advicement.io) - 基于 LaTeX 模板，通过 JSON 转 PDF API 生成文档。免费方案每月 50 次 API 调用，并可访问模板库。
  * [Earnings Feed](https://earningsfeed.com/api) - 实时 SEC 申报、内幕交易和机构持仓 API，免费套餐每分钟 15 次请求。
  * [Export SDK](https://exportsdk.com) - 提供拖放模板编辑器、SDK 和无代码集成的 PDF 生成 API。免费方案每月 250 页、无限用户和 3 个模板。
  * [ExtendsClass](https://extendsclass.com/rest-client-online.html) - 免费的 Web HTTP 客户端，用于发送 HTTP 请求。
  * [Financial Data](https://financialdata.net/) - 股票市场与金融数据 API，免费方案每天 300 次请求。
  * [finlight](https://finlight.me) - 实时金融新闻 API，支持实体解析（tickers、ISIN）和情绪标签，可通过 REST、WebSocket、webhooks 和 MCP server 使用。免费层 REST 与 MCP 每月各 5000 次请求，文章延迟 12 小时，无需信用卡。
  * [Firecrawl](https://www.firecrawl.dev/) - 抓取网站并转换为干净、适合 LLM 使用的 Markdown 或结构化数据的 API，可处理 JavaScript 渲染、代理和速率限制。免费方案每月 1,000 积分，无需信用卡。
  * [FormatJSONOnline.com](https://formatjsononline.com) - 免费浏览器工具，可即时格式化、验证、比较和压缩 JSON 数据。
  * [FraudLabs Pro](https://www.fraudlabspro.com) - 检查订单中的信用卡支付欺诈，REST API 会根据订单输入参数检测各种潜在欺诈特征。免费 Micro 方案每月 500 笔交易。
  * [FreeIPAPI](https://freeipapi.com) - 面向商业和非商业用户的免费、快速、可靠 JSON IP 地理位置 API。
  * [Geolocated.io](https://geolocated.io) - 具有多洲服务器的 IP 地理位置 API，免费方案每天 2,000 次请求。
  * [Hex](https://hex.tech/) - 用于 Notebook、数据应用和知识库的协作数据平台，免费社区套餐最多 5 个项目。
  * [Hook0](https://www.hook0.com/) - 开源 Webhooks 即服务（WaaS），便于在线产品提供 Webhook。每天可免费分发 100 个事件，并保留 7 天历史记录。
  * [Hoppscotch](https://hoppscotch.io) - 免费、快速且美观的 API 请求构建工具。
  * [HS Ping](https://hsping.com) - 多国 HS（协调制度）和 HTS（协调关税制度）编码查询 API，免费方案每天 100 次查询。
  * [huggingface.co](https://huggingface.co) - 使用 Pytorch、TensorFlow 和 JAX 构建、训练及部署 NLP 模型，每月最多 30,000 个输入字符免费。
  * [Insomnia](https://insomnia.rest) - 用于设计和测试 API 的开源客户端，支持 REST 与 GraphQL。
  * [Inngest](https://www.inngest.com) - 为 TypeScript、Python 和 Go 提供持久执行与事件驱动工作流。免费 Hobby 方案每月 50,000 次执行、5 个并发步骤、50 万个事件写入，无需信用卡。
  * [Invantive Cloud](https://cloud.invantive.com/) - 使用 Invantive SQL 或 OData4（通常配合 Power BI 或 Power Query）访问 Exact Online、Twinfield、ActiveCampaign、Visma 等 70 多个云平台，支持数据复制和交换。开发者与实施顾问免费，部分平台在数据量限制下也可免费使用。
  * [IP Geolocation API by ipwho.org](https://ipwho.org/) - 每天 2,000 次免费请求，提供快速、企业级但价格亲民的 API，受到开发者、企业、政府和教育机构用户信赖，服务器分布于 12 个以上地区。
  * [IP Geolocation API](https://www.abstractapi.com/ip-geolocation-api) - Abstract 提供的 IP 地理位置 API，含 1,000 次免费请求。
  * [IP Geolocation](https://ipgeolocation.io/) - 面向开发者的永久免费 IP 地理位置 API，每天限 1,000 次请求。
  * [ip-api](https://ip-api.com) - IP 地理位置 API，非商业用途免费，无需 API Key；免费方案同一 IP 每分钟限 45 次请求。
  * [IP.City](https://ip.city) - 每天 100 次免费 IP 地理位置请求。
  * [IP2Location.io](https://www.ip2location.io/) - 免费增值、快速可靠的 IP 地理位置 API，可获取城市、坐标、ISP、ASN、AS 等数据。免费方案每月 50,000 积分，另提供每月 500 次免费 WHOIS 和托管域名查询，可查看域名注册信息并查找托管在指定 IP 上的域名。更多功能需升级付费方案。
  * [Proxmint GeoIP](https://proxmint.com/tools/ip-lookup) — 免费的 IP → 国家/城市/ASN JSON API，无需 Key，开放 CORS，使用 MaxMind GeoLite2。
  * [ip2geo.dev](https://ip2geo.dev) - 将 IP 地址转换为城市、国家、时区、ASN 和货币等位置数据的 API，免费方案每月 1,000 次请求。
  * [ipaddress.sh](https://ipaddress.sh) - 以不同[formats](https://about.ipaddress.sh/)获取公网 IP 地址的简单服务。
  * [ipapi.is](https://ipapi.is/) - 由开发者为开发者打造的可靠 IP 地址 API，具备出色的托管检测能力。免费方案无需注册即可查询 1,000 次。
  * [ipapi](https://ipapi.co/) - Kloudend, Inc 提供的 IP 地址位置 API，基于 AWS 构建并受到 Fortune 500 企业信赖。免费套餐无需注册，每月 30,000 次查询（每天 1,000 次）。
  * [ipbase.com](https://ipbase.com) - IP 地理位置 API，永久免费方案每月 150 次请求。
  * [IPinfo](https://ipinfo.io/) - 快速、准确且免费的 IP 地址数据 API（每月最多 50,000 次），提供地理位置、公司、运营商、IP 段、域名、滥用联系人等信息。所有付费 API 均可免费试用。
  * [IPLocate](https://www.iplocate.io) - IP 地理位置 API，每天最多 1,000 次免费请求，包含代理/VPN/托管检测、ASN、IP 到公司等数据；另提供 CSV 或兼容 GeoIP 的 MMDB 格式免费 IP→国家和 IP→ASN 数据库。
  * [IPTrace](https://iptrace.io) - 极其简单的 API，每月提供 50,000 次免费查询，为企业返回可靠实用的 IP 地理位置数据。
  * [JSON IP](https://getjsonip.com) - 返回发起请求客户端的公网 IP。免费套餐无需注册；支持 CORS，可在浏览器中直接通过客户端 JavaScript 请求，适合监控客户端和服务器 IP 变化，请求次数不限。
  * [JSON to Table](https://jsontotable.org) - 将 JSON 转换为交互式表格，方便在线快速查看、编辑和分享。
  * [JSON2Video](https://json2video.com) - 视频编辑 API，可通过代码或无代码方式自动化生成营销和社交媒体视频。
  * [JSONGrid](https://jsongrid.com) - 免费工具，可将复杂 JSON 数据可视化、编辑并筛选成美观表格，还可通过链接保存和分享 JSON 数据。
  * [JSONing](https://jsoning.com/api/) - 从 JSON 对象创建模拟 REST API，并自定义 HTTP 状态码、Header 和响应正文。
  * [JSONSwiss](https://www.jsonswiss.com/) - 强大的在线 JSON 查看器、编辑器和验证器，可格式化、可视化、搜索和处理 JSON，支持 AI 修复、树视图、表格视图、12 种以上语言代码生成，以及 JSON 转 CSV、XML、YAML、Properties 等。
  * [KillBait API](https://killbait.com/api/doc) - 用户可提交 URL 进行内容评估，检测潜在标题党并对文章分类。API 适用于中等发布频率，每小时最多提交 1 次、每天 10 次；媒体合作方可申请更高限额。
  * [Kreya](https://kreya.app) - 免费 gRPC GUI 客户端，用于调用和测试 gRPC API，可通过服务器反射导入 gRPC API。
  * [LoginLlama](https://loginllama.app) - 登录安全 API，可检测欺诈和可疑登录并通知客户，每月前 1,000 次登录免费。
  * [Market Data API](https://www.marketdata.app) - 提供股票、期权、共同基金等实时和历史金融数据，永久免费 API 套餐每天 100 次请求。
  * [Maxim AI](https://getmaxim.ai/) - 模拟、评估并观测 AI Agent，提供端到端评估和可观测性，帮助团队更可靠、更快速地发布 AI Agent。独立开发者和小团队永久免费（3 个席位）。
  * [microlink.io](https://microlink.io/) - 将任意网站转换为数据，包括元标签规范化、美观链接预览、抓取和截图即服务。每天免费 50 次请求。
  * [Mintlify](https://mintlify.com) - 现代 API 文档标准，提供美观易维护的 UI 组件、应用内搜索和交互式 Playground，1 名编辑者免费。
  * [MockAPI](https://www.mockapi.io/) - 可快速模拟 API、生成自定义数据并通过 RESTful 接口执行操作的简单工具，适合原型、测试和学习。免费支持 1 个项目，每个项目 2 个资源。
  * [Mockerito](https://mockerito.com/) - 免费模拟 REST API 服务，覆盖电商、金融、医疗、教育、招聘、社交、股市、天气和航空等 9 个领域的真实数据。无需强制注册、无需 API Key、请求不限，非常适合前端原型、API 测试及 Web 开发教学。
  * [Mockfly](https://www.mockfly.dev/) - 可靠的 API 模拟与功能开关开发工具，可通过直观界面快速生成和控制模拟 API。免费套餐每天 500 次请求。
  * [Mocko.dev](https://mocko.dev/) - 代理你的 API，在云端选择要模拟的端点并检查流量，免费使用，可加快开发和集成测试。
  * [Multi-Exit IP Address Checker](https://ip.alstra.ca/) - 免费简单的工具，可从多个节点检查出口 IP，了解你的 IP 在不同全球地区和服务中的呈现方式，适合测试 Control D 等基于规则的 DNS 分流工具。
  * [NASdisks Drive Data API](https://www.nasdisks.com/data/) - 面向 NAS HDD/SSD 规格的免费免密钥、支持 CORS 的 API，提供逐型号 CMR/SMR 分类，以及基于 Backblaze Drive Stats 的年化故障率。返回 JSON 或 CSV，采用 CC BY 4.0，无需注册。
  * [News API](https://newsapi.org) - 通过代码搜索互联网新闻并获取 JSON 结果。开发者每天免费 100 次查询，文章延迟 24 小时。
  * [numlookupapi.com](https://numlookupapi.com) - 免费电话号码验证 API，每月 100 次请求。
  * [OCR.Space](https://ocr.space/) - OCR API，可解析图片和 PDF 并以 JSON 返回文本结果。每月免费 25,000 次请求，文件上限 1MB。
  * [OpenAPI3 Designer](https://openapidesigner.com/) - 免费可视化创建 OpenAPI 3 定义。
  * [Parseur](https://parseur.com) - 每月免费 20 页：从 PDF 和电子邮件中提取数据，支持 AI，并提供完整 API 访问。
  * [PDF-API.io](https://pdf-api.io) - PDF 自动化 API，提供可视化模板编辑器或 HTML 转 PDF、动态数据集成及 API 渲染。免费方案含 1 个模板，每月 100 份 PDF。
  * [PDFBolt](https://pdfbolt.com) - 面向开发者、注重隐私的 PDF 生成 API，文档风格类似 Stripe，每月包含 500 次免费 PDF 转换。
  * [Pexafy](https://pexafy.com) - 跨 9 个免费图片源（Unsplash、Pexels、Pixabay、Kaboompics 等）的语义图片搜索 API，将 900 万+ 图片统一为一种 JSON schema，无需分别集成。支持自然语言查询、反向图片搜索，以及颜色、方向和许可筛选。读取端点开放 CORS，可直接在浏览器运行。免费计划每月 5000 次 API 请求、1 个 key，无需应用审核。
  * [Pixela](https://pixe.la/) - 免费的日流数据库服务，所有操作均通过 API 完成，并支持热力图和折线图可视化。
  * [Posthook](https://posthook.io) - 定时触发未来 Webhook，支持自动重试、投递跟踪和失败告警。免费方案每月 1,000 个 Webhook。
  * [Postman](https://postman.com) - 用于 API 开发的协作平台，可简化工作流并更快构建更好的 API。Postman App 可永久免费使用，Postman 云功能在一定限制下同样永久免费。
  * [PrefectCloud](https://www.prefect.io/cloud/) - 完整的数据流自动化平台，免费方案包含 5 个已部署工作流和每月 500 分钟无服务器计算额度。
  * [Preset Cloud](https://preset.io/) - 托管的 Apache Superset 服务，最多 5 名用户的团队永久免费，包含无限仪表板和图表、无代码图表构建器及协作 SQL 编辑器。
  * [ProxySentry](https://proxysentry.io/) - 检测住宅代理与 VPN 的 IP API，通过 rapidapi.com 提供每月 10,000 次请求的免费套餐。
  * [Reducto](https://reducto.ai) - 将 PDF、XLSX、JPG、PPTX 等非结构化文档转换为结构化 JSON，可解析、提取数据并编辑 PDF 表单。免费套餐含 15,000 积分，超额按量付费。
  * [Rendi](https://rendi.dev) - FFmpeg REST API，无需管理基础设施即可在线运行 FFmpeg。免费套餐含每月处理额度和 4 个可用 vCPU。
  * [RequestBin.com](https://requestbin.com) - 创建可接收 HTTP 请求的免费端点，所有请求及其 Payload 和 Header 都会被记录，方便观察来自 Webhook 和其他服务的请求。
  * [ROBOHASH](https://robohash.org/) - 根据任意文本生成独特、有趣图片的 Web 服务。
  * [Scraper's Proxy](https://scrapersproxy.com) - 用于抓取的简单 HTTP 代理 API，可匿名抓取，无需担心限制、封禁或验证码。每月前 100 次成功抓取免费，并包含 JavaScript 渲染（联系支持可获得更多额度）。
  * [ScrapingAnt](https://scrapingant.com/) - 无头 Chrome 抓取 API 和免费已验证代理服务，支持 JavaScript 渲染、高级轮换代理及规避 CAPTCHA，免费提供 10,000 API 积分。
  * [SerpApi](https://serpapi.com/) - 实时搜索引擎抓取 API，可返回 Google、YouTube、Bing、Baidu、Walmart 等平台的结构化 JSON 结果。免费方案每月 100 次成功 API 调用。
  * [Simplescraper](https://simplescraper.io) - 每次操作后触发 Webhook，免费方案含 100 个云端抓取积分。
  * [Geekflare API](https://geekflare.com/api/) - 可将网站抓取为 Markdown、截图、扫描 TLS、查询 DNS、测试加载时间等。免费方案每月 500 API 积分（例如 500 次 DNS 查询、250 次网页抓取或 100 次截图），详见[credit mapping](https://docs.geekflare.com/api/api-credit-mapping)。
  * [SmartParse](https://smartparse.io) - 数据迁移与 CSV 转 API 平台，提供节省时间和成本的开发工具。免费套餐每月 300 个处理单元，并包含浏览器上传、数据隔离、熔断器和作业告警。
  * [Sofodata](https://www.sofodata.com/) - 从 CSV 文件创建安全 RESTful API。上传 CSV 后即可通过 API 访问数据，加快应用开发。免费方案含 2 个 API 和每月 2,500 次调用，无需信用卡。
  * [Sqlable](https://sqlable.com/) - 免费在线 SQL 工具集合，包括 SQL 格式化与验证、SQL 正则测试、模拟数据生成和交互式数据库 Playground。
  * [Svix](https://www.svix.com/) - Webhooks 即服务，每月可免费发送 50,000 条消息。
  * [Tavily AI](https://tavily.com/) - 面向在线搜索、快速洞察和综合研究的 API，可组织研究结果。免费套餐每月 1,000 次请求，无需信用卡。
  * [TemplateFox](https://pdftemplateapi.com) - PDF 生成 API，提供可视化模板编辑器、动态数据合并和 7 种语言 SDK。免费方案每月 60 份 PDF 和 3 个模板。
  * [The IP API](https://theipapi.com/) - IP 地理位置 API，每天 1,000 次免费请求，返回国家、城市、地区等 IP 位置信息。
  * [TinyMCE](https://www.tiny.cloud) - 富文本编辑 API，核心功能可无限免费使用。
  * [Tomorrow.io Weather API](https://www.tomorrow.io/weather-api/) - 提供免费天气 API 方案，覆盖全球，提供准确及时的天气预报、历史数据和天气监控解决方案。
  * [Treblle](https://www.treblle.com) - 帮助团队构建、发布和治理 API，提供高级 API 日志聚合、可观测性、文档和调试。所有功能免费，但免费套餐每月最多 250,000 次请求。
  * [Trophy](https://trophy.so) - Trophy 是面向消费类应用的游戏化层。通过预构建 API 和开源 UI 组件快速接入成就、连续打卡、积分、排行榜等功能。每月活跃用户不超过 1000 时免费。
  * [UniRateAPI](https://unirateapi.com) - 590 多种法币和加密货币的实时汇率，免费方案 API 调用不限，适合开发者和金融应用。
  * [vatcheckapi.com](https://vatcheckapi.com) - 简单免费的 VAT 号码验证 API，每月 150 次免费验证。
  * [vatnode](https://vatnode.dev) - 欧盟 VAT 号码验证 REST API，支持 VIES 和各国税务登记回退，并返回官方 VIES 查询编号以供审计。免费套餐每月 100 次验证，无需信用卡。
  * [WeatherXu](https://weatherxu.com/) - 通过 API 提供全球当前天气、逐小时/逐日预报和天气警报，结合 AI 与机器学习分析多个天气模型以提高准确度。免费套餐每月 10,000 次 API 调用。
  * [WebScraping.AI](https://webscraping.ai) - 内置解析、Chrome 渲染和代理的简单网页抓取 API，每月 2,000 次免费 API 调用。
  * [Weights & Biases](https://wandb.ai) - 开发者优先的 MLOps 平台，通过实验跟踪、数据集版本控制和模型管理更快构建更好模型。仅个人项目可用免费套餐，含 100GB 存储。
  * [What Is My IP](https://whatismyip.help) - 免费检查公网 IPv4、IPv6 和相关请求数据，提供多种 API 输出格式，适合自动化、脚本和网络故障排查。
  * [What The Diff](https://whatthediff.ai) - AI 代码审查助手，免费方案每月 25,000 Token（约 10 个 PR）。
  * [XFlux](https://www.xfluxapi.com) - X/Twitter 只读 REST API（资料、搜索、时间线）及账户监控。免费层每月 1000 次 API 调用、1 个 monitor，并可即时获得 API key。HTTP webhooks 仅在付费计划提供，起价 $19/月。
  * [wolfram.com](https://wolfram.com/language/) - 云端内置知识型算法。
  * [wrapapi.com](https://wrapapi.com/) - 将任意网站转换为参数化 API，每月 30,000 次 API 调用。
  * [Zenscrape](https://zenscrape.com/web-scraping-api) - 使用无头浏览器和住宅 IP 的网页抓取 API，定价简单。每月 1,000 次免费 API 调用，学生和非营利机构可获得额外积分。
  * [Zipcodebase](https://zipcodebase.com) - 免费邮政编码 API，可访问全球邮政编码数据，每月 5,000 次免费请求。
  * [Zip-Codes](https://www.zip-codes.com/api/) - 美国和加拿大邮政编码 REST API，支持地址验证、半径搜索和人口普查统计，每天 2,500 次免费请求。
  * [Zipcodestack](https://zipcodestack.com) - 免费邮政编码 API 与邮编验证服务，每月 10,000 次免费请求。
  * [Zuplo](https://zuplo.com/) - 免费 API 管理平台，可在边缘设计、构建和部署 API，几分钟内为任意 API 添加 API Key 认证、速率限制、开发者文档和商业化。原生支持 OpenAPI，并可使用 Web 标准 API 与 TypeScript 编程。免费方案最多 10 个项目、无限生产边缘环境、每月 100 万次请求和 10GB 出站流量。
  * [Metashot](https://metashot.io) — Open Graph（OG）社交预览图生成 API，可通过 URL 参数生成适用于 Twitter、LinkedIn 和 Facebook 的动态 1200×630 图片，并在 Cloudflare Workers 边缘缓存。免费套餐每月 1,000 次渲染，付费方案每月 12 美元起。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="artifact-repos"></a>
## 制品仓库

<details>
<summary>展开 / 收起服务列表</summary>

  * [Gemfury](https://gemfury.com) - 面向 Maven、PyPI、NPM、Go Module、NuGet、APT 和 RPM 的私有与公开制品仓库，公开项目免费。
  * [jitpack.io](https://jitpack.io/) - 面向 GitHub 上 JVM 和 Android 项目的 Maven 仓库，公开项目免费。
  * [paperspace](https://www.paperspace.com/) - 构建和扩展 AI 模型，开发、训练并部署 AI 应用。免费方案含公开项目、5GB 存储和基础实例。
  * [RepoFlow](https://repoflow.io) - 简化 npm、PyPI、Docker、Go、Helm 等软件包管理。云端免费方案含 10GB 存储、10GB 带宽、100 个软件包和无限用户；也可仅供个人使用地自托管。
  * [RepoForge](https://repoforge.io) - 面向 Python、Debian、NPM 软件包和 Docker 注册表的私有云托管仓库，开源/公开项目免费。
  * [repsy.io](https://repsy.io) - 1GB 免费私有/公开 Maven 仓库。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="tools-for-teams-and-collaboration"></a>
## 团队与协作工具

<details>
<summary>展开 / 收起服务列表</summary>

  * [3Cols](https://3cols.com/) - 面向个人和协作使用的免费云端代码片段管理器。
  * [BookmarkOS.com](https://bookmarkos.com) - 可在支持文件夹协作的自定义在线桌面中管理书签、标签页和任务的一体化工具。
  * [Braid](https://www.braidchat.com/) - 面向团队的聊天应用。公开访问群组免费，用户数、历史记录和集成都不限；另提供可自托管的开源版本。
  * [Calendly](https://calendly.com) - 用于连接日历和安排会议的工具。免费方案每名用户可连接 1 个日历，会议次数不限，并提供桌面和移动应用。
  * [cally.com](https://cally.com/) - 为会议寻找合适日期和时间，操作简单，适合小型和大型群组。
  * [cDox](https://cdox.ca) - 托管在加拿大的私密文档编辑器，可编写、格式化、协作和发布文档，并生成简洁公开链接。数据绝不用于 AI 训练。免费方案含 50MB 存储、最多 3 个公开链接，并可导出为 PDF、Word 和 Markdown。
  * [Chanty.com](https://chanty.com/) - Slack 的另一种替代方案。小团队（最多 10 人）可永久免费使用无限公开/私有对话、可搜索历史、无限一对一语音通话、无限语音消息、10 个集成和每团队 20GB 存储。
  * [DevToolLab](https://devtoollab.com) - 在线开发者工具，所有基础工具均可免费使用；每个工具可自动保存 1 条记录，提供标准处理速度和社区支持。
  * [Discord](https://discord.com/) - 支持公开/私密房间、Markdown 文本、语音、视频和屏幕共享，用户数量不限且免费。
  * [Dubble](https://dubble.so/) - 免费的分步指南创建工具，可截图、记录流程并与团队协作，也支持异步屏幕录制。
  * [Duckly](https://duckly.com/) - 与团队实时沟通协作，支持 IDE 结对编程、终端共享、语音、视频和屏幕共享，小团队免费。
  * [element.io](https://element.io/) - 基于 Matrix 构建的去中心化开源通信工具，支持群聊、私信、加密文件传输、语音和视频聊天，并可轻松集成其他服务。
  * [evernote.com](https://evernote.com/) - 信息整理工具，可分享笔记并与他人协作。
  * [Fibery](https://fibery.io/) - 互联工作空间平台，单用户免费，最多 2GB 磁盘空间。
  * [Fibo](https://fibo.dev) - 面向敏捷团队的免费在线实时 Scrum Poker 工具，支持无限成员评估故事点，加快规划。
  * [Fizzy](https://www.fizzy.do/) - 基于看板的项目管理和问题跟踪平台，可创建公开看板、配置 Webhook、使用卡片盖章并跟踪无限用户，1,000 个条目以内免费。
  * [flat.social](https://flat.social) - 用于团队会议和欢乐时光社交的可交互自定义空间，会议次数不限，最多 8 名并发用户免费。
  * [flock.com](https://flock.com) - 更快速的团队沟通方式，消息、频道、用户、应用和集成均可免费无限使用。
  * [GhostChat](https://ghostchat.dev) - 隐私优先的网站实时聊天组件（约 15KB，无 Cookie、无跟踪）。免费方案含 1 个站点、无限消息、30 天历史、Gmail 线程、快捷回复和推送通知。
  * [GitBook](https://www.gitbook.com/) - 用于收集和记录技术知识的平台，覆盖产品文档、内部知识库和 API，个人开发者可用免费方案。
  * [GitDailies](https://gitdailies.com) - 汇总团队在 GitHub 上的 Commit 和 Pull Request 活动日报，包含 Push 可视化、同伴认可系统和自定义告警构建器。免费套餐用户不限，支持 3 个仓库和 3 个告警配置。
  * [gitter.im](https://gitter.im/) - 面向 GitHub 的聊天服务，公开和私密房间不限，最多 25 人团队免费。
  * [gokanban.io](https://gokanban.io) - 基于语法、无需注册的快速看板，无任何限制且免费。
  * [Hackmd.io](https://hackmd.io/) - Markdown 文档/文件的实时协作与写作工具，类似面向 Markdown 的 Google Docs。“笔记”数量不限，但私密笔记和模板的协作者（受邀者）数量[will be limited](https://hackmd.io/pricing)。
  * [HeySpace](https://hey.space) - 集聊天、日历、时间线和视频通话于一体的任务管理工具，最多 5 名用户免费。
  * [Huly](https://huly.io/) - 一体化项目管理平台（Linear、Jira、Slack、Notion、Motion 的替代品），用户不限，每个工作区 10GB 存储和 10GB 视频/音频流量。
  * [Keybase](https://keybase.io/) - Slack 的 FOSS 替代品，可保护家庭、社区和公司成员的聊天与文件安全。
  * [Knocket](https://trtc.io/solutions/knocket) - 面向独立开发者和小团队的永久免费联系层：为网站和移动应用（iOS/Android/Flutter/React Native，可通过 WebView）提供实时聊天组件、可分享的联系页面（类似 Linktree，含社交链接、预约链接和博客），以及统一的 Telegram/邮件收件箱。可直接从 Telegram 回复，无需打开仪表板。还包含会议排期、多语言、明暗主题和开源 AI 自动回复 Agent，无广告、无席位限制。
  * [Linkinize](https://linkinize.com) - 面向团队的书签管理器，支持标签、多工作区和协作。免费方案含 4 个工作区和 10 名团队成员。
  * [Lockitbot](https://www.lockitbot.com/) - 在 Slack 中预订并锁定会议室、开发环境、服务器等共享资源，最多 2 个资源免费。
  * [meet.jit.si](https://meet.jit.si/) - 免费的一键视频通话和屏幕共享。
  * [Miro](https://miro.com/) - 面向分布式团队、可扩展、安全、跨设备且适合企业的协作白板，提供免费增值方案。
  * [Notion](https://www.notion.so/) - 支持 Markdown 的笔记与协作应用，集任务、Wiki 和数据库于一体。官方将其定位为笔记、项目管理和任务管理的一体化工作空间，除跨平台应用外，也可通过多数浏览器访问。
  * [Nuclino](https://www.nuclino.com) - 轻量协作式 Wiki，用于团队知识、文档和笔记。免费方案包含所有基础功能，最多 50 个条目和 5GB 存储。
  * [OnlineInterview.io](https://onlineinterview.io/) - 免费代码面试平台，内置视频聊天、画板和可在浏览器中编译运行代码的在线编辑器，一键即可创建远程面试房间。
  * [paste.sh](https://paste.sh/) - 基于 JavaScript 和加密技术的简单 Paste 站点。
  * [Pastefy](https://pastefy.app/) - 美观简单的 Pastebin，支持可选客户端加密、多标签 Paste、API、高亮编辑器等。
  * [Pendulums](https://pendulums.io/) - 免费时间跟踪工具，通过易用界面和实用统计帮助更好地管理时间。
  * [Proton Pass](https://proton.me/pass) - 内置电子邮件别名、2FA 验证器、共享和 Passkey 的密码管理器，提供 Web、浏览器扩展、移动端和桌面端。
  * [Pullflow](https://pullflow.com) - 在 GitHub、Slack 和 VS Code 之间提供 AI 增强的代码审查协作平台。
  * [Pumble](https://pumble.com) - 免费团队聊天应用，用户和消息历史均不限，永久免费。
  * [Quidlo Timesheets](https://www.quidlo.com/timesheets) - 简单的团队工时表与时间跟踪应用，免费方案最多 10 名用户，并提供时间跟踪和报告生成。
  * [Raindrop.io](https://raindrop.io) - 面向 macOS、Windows、Android、iOS 和 Web 的私密安全书签应用，书签和协作均可免费无限使用。
  * [Reezn.io](https://reezn.io/) - 面向团队的规范驱动开发工作流：把评审前移，在写代码前发现问题，而不是堆到代码审查阶段。随着使用会构建业务知识图谱，AI agents 可在后续功能中复用。免费计划包含 3 个席位、1 个项目、每月 5 个 features。
  * [Revolt.chat](https://revolt.chat/) - 尊重隐私的开源 [Discord](https://discord.com/) 替代品，免费提供 Discord 的大多数专有功能。应用安全、快速、完全免费，所有功能均免费，并支持官方和非官方插件。
  * [Rocket.Chat](https://rocket.chat/) - 开源通信平台，提供全渠道功能、Matrix 联邦、其他应用桥接、无限消息和完整消息历史。
  * [ruttl.com](https://ruttl.com/) - 一体化反馈工具，可收集数字反馈并审查网站、PDF 和图片。
  * [Screen Sharing via Browser](https://screensharing.net) - 免费屏幕共享工具，可直接在浏览器中与协作者共享屏幕，无需下载或注册。
  * [seafile.com](https://www.seafile.com/) - 私有或云存储、文件共享、同步和讨论，云版本仅含 1GB。
  * [SiteDots](https://sitedots.com/) - 直接在网站上分享网站项目反馈，无需模拟、画布或变通方案，免费套餐功能完整。
  * [Slab](https://slab.com/) - 面向团队的现代知识管理服务，最多 10 名用户免费。
  * [slack.com](https://slack.com/) - 用户数量不限，但免费方案有部分功能限制。
  * [StatusPile](https://www.statuspile.com/) - “状态页的状态页”，用于跟踪上游服务商的状态页。
  * [Stickies](https://stickies.app/) - 用于头脑风暴、内容整理和笔记的可视化协作应用，最多 3 面墙、无限用户和 1GB 存储免费。
  * [MeetBackdrops](https://meetbackdrops.com) - 为 Zoom、Microsoft Teams 和 Google Meet 提供免费高清虚拟背景，含 1,000 多个专业设计场景，无需注册。
  * [talky.io](https://talky.io/) - 免费群组视频聊天，匿名、点对点，无需插件、注册或付费。
  * [Teamcamp](https://www.teamcamp.app) - 面向软件开发公司的全功能一体化项目管理应用。
  * [Teamhood](https://teamhood.com/) - 免费项目、任务和问题跟踪软件，支持带泳道的看板、完整 Scrum 和集成时间跟踪。免费供 5 名用户使用，支持 3 个项目组合。
  * [Teamplify](https://teamplify.com) - 通过团队分析和智能每日站会改善团队开发流程，并为远程优先团队提供完整休假管理。最多 5 名用户的小团队免费。
  * [Telegram](https://telegram.org/) - 适合需要快速可靠消息和通话的用户。企业用户和小团队可使用大型群组、用户名、桌面应用和强大的文件共享功能。
  * [Tencent RTC](https://trtc.io/) - Tencent Real-Time Communication（TRTC）提供群组音视频通话解决方案，第一年每月免费 10,000 分钟。
  * [TimeCamp](https://www.timecamp.com/) - 无限用户的免费时间跟踪软件，可轻松集成 Jira、Trello、Asana 等项目管理工具。
  * [tldraw.com](https://tldraw.com) - 免费开源白板和图表工具，提供智能箭头、吸附、便签和 SVG 导出，并支持多人协作编辑；另有免费的官方 VS Code 扩展。
  * [transfernow](https://www.transfernow.net/) - 简单、快速且安全的文件传输与分享界面，无需强制订阅即可发送照片、视频和其他大文件。
  * [Tugboat](https://tugboat.qa) - 自动或按需预览每个 Pull Request，对所有用户免费，非营利组织可免费使用 Nano 套餐。
  * [twist.com](https://twist.com) - 异步友好的团队沟通应用，使对话保持有序并聚焦主题，提供免费和无限方案，符合条件的团队可享折扣。
  * [userforge.com](https://userforge.com/) - 互联的在线用户画像、用户故事和上下文映射，帮助设计与开发保持同步，最多 3 个用户画像和 2 名协作者免费。
  * [Visual Debug](https://visualdebug.com) - 改善客户与开发者沟通的可视化反馈工具。
  * [Webex](https://www.webex.com/) - 视频会议免费方案每次会议 40 分钟，最多 100 名参会者。
  * [Webvizio](https://webvizio.com) - 网站反馈、审查和缺陷报告工具，可直接在实时网站、Web 应用、图片、PDF 和设计文件上协作处理任务，简化 Web 开发协作。
  * [whereby.com](https://whereby.com/) - 免费的一键视频通话服务（原 appear.in）。
  * [windmill.dev](https://windmill.dev/) - 开源开发者平台，可用少量 Python 和 TypeScript 脚本快速构建生产级多步骤自动化和内部应用。免费用户最多可创建或加入 3 个非高级工作区。
  * [wistia.com](https://wistia.com/) - 视频托管服务，含观看分析、高清视频分发和营销工具，帮助了解访客。免费可托管 25 个视频，播放器带 Wistia 品牌。
  * [wormhol.org](https://www.wormhol.org/) - 简单文件分享服务，可与任意数量的对等端分享无限文件，单文件最多 5GB。
  * [Wormhole](https://wormhole.app/) - 通过端到端加密分享最大 5GB 文件，最长保留 24 小时；超过 5GB 时使用点对点传输直接发送。
  * [zoom.us](https://zoom.us/) - 安全的视频和 Web 会议，并提供扩展功能。免费方案每场会议限 40 分钟。
  * [Zulip](https://zulip.com/) - 采用类似电子邮件线程模型的实时聊天，免费方案含 10,000 条可搜索历史消息和最多 5GB 文件存储，另提供可自托管开源版本。
  * [RightFeature](https://rightfeature.com/) - 轻松收集客户反馈并转化为产品路线图，收集、排序和交付真正对用户重要的功能。
  * [Zeitio](https://zeitio.com/) - 面向自由职业者和小团队的时间跟踪与开票工具，免费方案含 1 名用户、3 个活跃项目和每月 3 张发票。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="cms"></a>
## CMS（内容管理系统）

<details>
<summary>展开 / 收起服务列表</summary>

  * [Contentful](https://www.contentful.com/) - 无头 CMS，提供云端内容管理和交付 API。免费 Community 空间含 5 名用户、25,000 条记录、48 种内容类型和 2 个区域设置。
  * [Cosmic](https://www.cosmicjs.com/) - 无头 CMS 与 API 工具包，为开发者提供免费个人方案。
  * [Crystallize](https://crystallize.com) - 支持电商的无头 PIM，内置 GraphQL API。免费版含无限用户、1,000 个目录条目、每月 5GB 带宽和 25,000 次 API 调用。
  * [DatoCMS](https://www.datocms.com/) - 为小型项目提供免费套餐。基于 GraphQL 的 CMS，低阶套餐每月可调用 100,000 次。
  * [Hygraph](https://hygraph.com/) - 为小型项目提供免费套餐，采用 GraphQL 优先 API，帮助从传统方案迁移到原生 GraphQL 的无头 CMS，并以 API 优先方式交付全渠道内容。
  * [Prismic](https://www.prismic.io/) - 无头 CMS，提供完整托管且可扩展的内容管理界面和 API。Community 方案为 1 名用户提供无限 API 调用、文档、自定义类型、资源和区域设置，满足下一项目所需。开放内容/开源项目还可申请更大免费方案。
  * [Sanity.io](https://www.sanity.io/) - 结构化内容平台，含开源编辑环境和实时托管数据存储。每个项目免费包含无限项目、无限管理员、3 名非管理员、2 个数据集、500,000 次 API CDN 请求、10GB 带宽和 5GB 资源。
  * [Solo](https://soloist.ai) - Mozilla 提供的免费 AI 网站生成器，只需少量输入即可为企业创建美观网站，支持免费自定义域名，无需信用卡。
  * [Squidex](https://squidex.io/) - 为小型项目提供免费套餐，API/GraphQL 优先，开源并基于事件溯源（自动版本化每次更改）。
  * [Storyblok](https://www.storyblok.com) - 面向开发者和营销人员、兼容所有现代框架的无头 CMS。Community 免费套餐包含 Management API、可视化编辑器、10 个来源、自定义字段类型、国际化（语言/区域不限）、资源管理器（最多 2,500 个资源）、图片优化服务、搜索查询、Webhook 和每月 250GB 流量。
  * [TinaCMS](https://tina.io/) - Forestry.io 的替代品，基于 Git 的开源无头 CMS，支持 Markdown、MDX 和 JSON。基础方案免费，可供 2 名用户使用。
  * [WPJack](https://wpjack.com) - 5 分钟内在任意云上搭建 WordPress。免费套餐含 1 台服务器、2 个站点、免费 SSL 证书和无限 Cron Job，无时间限制或到期时间。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="code-generation"></a>
## 代码生成

<details>
<summary>展开 / 收起服务列表</summary>

* [Appinvento](https://appinvento.io/) - 免费无代码应用构建器，可完整访问自动生成的后端源码，并支持无限 API 和路由。免费方案含 3 个项目和 5 张表。
* [DhiWise](https://www.dhiwise.com/) - 将 Figma 设计转换为动态 Flutter 和 React 应用，代码生成技术旨在优化生产级移动和 Web 体验的构建流程。
* [Karbon Sites](https://www.karbonsites.space) - AI 驱动的网站构建与编辑器，可从文字提示、草图或简历生成生产级前端代码。支持原生 Android（APK）导出，免费套餐每月 5 次生成；使用自定义 Gemini API Key 时不限次数。
* [Metalama](https://www.postsharp.net/metalama) - 面向 C# 的工具，在编译期间即时生成样板代码以保持源码简洁。开源项目免费；适合商业使用的免费套餐最多支持 3 个 Aspect。
* [Supermaven](https://www.supermaven.com/) - 面向 VS Code、JetBrains 和 Neovim 的高速 AI 代码补全插件，免费套餐提供无限行内补全，并专注超低延迟。
* [v0.dev](https://v0.dev/) - Vercel 创建的工具，使用 shadcn/ui 和 Tailwind CSS 生成可直接复制粘贴的 React 代码。采用积分制，初始提供 1,200 积分，每月再免费获得 200 积分。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="code-quality"></a>
## 代码质量

<details>
<summary>展开 / 收起服务列表</summary>

  * [beanstalkapp.com](https://beanstalkapp.com/) - 提供编写、审查和部署代码的完整工作流；免费账号支持 1 名用户和 1 个仓库，含 100MB 存储。
  * [codacy.com](https://www.codacy.com/) - 为 PHP、Python、Ruby、Java、JavaScript、Scala、CSS 和 CoffeeScript 提供自动代码审查，公开和私有仓库均可无限免费使用。
  * [Codeac.io](https://www.codeac.io/infrastructure-as-code.html?ref=free-for-dev) - 面向 DevOps 的自动化基础设施即代码审查工具，可集成 GitHub、Bitbucket 和 GitLab（包括自托管），除常见语言外还分析 Ansible、Terraform、CloudFormation、Kubernetes 等。（开源项目免费）
  * [codecov.io](https://codecov.io/) - SaaS 代码覆盖率工具，开源项目和 1 个私有仓库免费。
  * [CodeFactor](https://www.codefactor.io) - Git 自动代码审查，免费版含无限用户、公开仓库和 1 个私有仓库。
  * [coderabbit.ai](https://coderabbit.ai) - 集成 GitHub/GitLab 的 AI 代码审查工具，免费套餐每小时最多处理 200 个文件、3 次审查和 50 次对话；开源项目永久免费。
  * [CodSpeed](https://codspeed.io) - 在 CI 流水线中自动跟踪性能，通过精确一致的指标在部署前发现性能回退，开源项目永久免费。
  * [coveralls.io](https://coveralls.io/) - 展示测试覆盖率报告，开源项目免费。
  * [deepscan.io](https://deepscan.io) - 高级静态分析，可自动发现 JavaScript 代码中的运行时错误，开源项目免费。
  * [DeepSource](https://deepsource.io/) - 持续分析源码变更，发现并修复安全、性能、反模式、缺陷风险、文档和风格等类别的问题，原生集成 GitHub、GitLab 和 Bitbucket。
  * [DiffText](https://difftext.com) - 即时查找两段代码之间的差异，完全免费。
  * [eversql.com](https://www.eversql.com/) - 数据库优化平台，可自动获得有关数据库和 SQL 查询的重要洞察。
  * [gerrithub.io](https://review.gerrithub.io/) - 免费为 GitHub 仓库提供 Gerrit 代码审查。
  * [goreportcard.com](https://goreportcard.com/) - Go 项目代码质量服务，开源项目免费。
  * [gtmetrix.com](https://gtmetrix.com/) - 提供网站优化报告和详细建议。
  * [holistic.dev](https://holistic.dev/) - PostgreSQL 优化静态代码分析器，可自动检测数据库性能、安全和架构问题。
  * [houndci.com](https://houndci.com/) - 在 GitHub Commit 上发布代码质量评论，开源项目免费。
  * [reviewable.io](https://reviewable.io/) - GitHub 仓库代码审查工具，公开或个人仓库免费。
  * [scan.coverity.com](https://scan.coverity.com/) - Java、C/C++、C# 和 JavaScript 静态代码分析，开源项目免费。
  * [scrutinizer-ci.com](https://scrutinizer-ci.com/) - 持续检查平台，开源项目免费。
  * [semanticdiff.com](https://app.semanticdiff.com/) - 理解编程语言语义的 GitHub Pull Request 与 Commit Diff，公开仓库免费。
  * [shields.io](https://shields.io) - 为开源项目提供质量元数据徽章。
  * [sonarcloud.io](https://sonarcloud.io) - 自动分析 Java、JavaScript、C/C++、C#、VB.NET、PHP、Objective-C、Swift、Python、Groovy 等源码，开源项目免费。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="code-search-and-browsing"></a>
## 代码搜索与浏览

<details>
<summary>展开 / 收起服务列表</summary>

  * [CodeKeep](https://codekeep.io) - 面向代码片段的 Google Keep，可整理、发现和分享代码片段，包含预设模板、链接功能和强大的代码截图工具。
  * [libraries.io](https://libraries.io/) - 支持 32 种软件包管理器的搜索和依赖更新通知，开源项目免费。
  * [Namae](https://namae.dev/) - 在 GitHub、GitLab、Heroku、Netlify 等网站上检查项目名称是否可用。
  * [tickgit.com](https://www.tickgit.com/) - 汇总 `TODO` 注释及其他标记，找出值得后续改进的代码区域。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="ci-and-cd"></a>
## CI / CD

<details>
<summary>展开 / 收起服务列表</summary>

  * [appcircle.io](https://appcircle.io) - 企业级移动 DevOps 平台，自动完成移动应用构建、测试和商店发布，以提高发布效率。免费方案单次构建最长 30 分钟，每月 20 次构建和 1 个并发构建。
  * [appveyor.com](https://www.appveyor.com/) - Windows CD 服务，开源项目免费。
  * [bitrise.io](https://www.bitrise.io/) - 面向原生或混合移动应用的 CI/CD。每月 200 次免费构建，每次 10 分钟，支持 2 名团队成员；OSS 项目每次 45 分钟、增加 1 个并发且团队人数不限。
  * [buddy.works](https://buddy.works/) - CI/CD 平台，含 5 个免费项目和 1 个并发运行（每月 120 次执行）。
  * [Buildkite](https://buildkite.com) - CI Pipelines 对 3 名用户免费，每月 5,000 作业分钟；Test Analytics 开发者套餐每月含 100,000 次测试执行，开源项目还有更多免费额度。
  * [bytebase.com](https://www.bytebase.com/) - 数据库 CI/CD 与 DevOps，20 名以下用户和 10 个数据库实例以内免费。
  * [CircleCI](https://circleci.com/) - 面向 GitHub、GitLab 和 Bitbucket 仓库的托管 CI/CD，免费方案功能完整。支持多种资源类别、Docker、Windows、macOS、ARM Executor、本地 Runner、测试拆分、Docker Layer Cache 等高级功能。每月最多 6,000 分钟执行时间、无限协作者、私有项目 30 个并行作业，开源项目最多 80,000 免费构建分钟。
  * [cirun.io](https://cirun.io) - 公开 GitHub 仓库免费。
  * [codemagic.io](https://codemagic.io/) - 每月 500 分钟免费构建时间。
  * [deployhq.com](https://www.deployhq.com/) - 1 个项目，每天 10 次部署（每月 30 分钟构建时间）。
  * [LocalOps](https://localops.co/) - 30 分钟内将应用部署到 AWS/GCP/Azure，在任意云上搭建包含持续部署自动化和高级可观测性的标准化应用环境。免费方案允许 1 名用户和 1 个应用环境。
  * [Make](https://www.make.com/en) - 通过 UI 连接应用并自动化工作流，支持众多应用和主流 API。公开 GitHub 仓库免费；普通免费套餐含 100MB、1,000 次操作，最短执行间隔 15 分钟。
  * [Mergify](https://mergify.com) - GitHub 工作流自动化和合并队列，公开 GitHub 仓库免费。
  * [Nx Cloud](https://nx.dev/ci) - 通过远程缓存、跨机器分发任务和自动拆分端到端测试等功能加速 Monorepo CI。免费方案最多 30 名贡献者，含 150,000 积分。
  * [RunMyJob](https://runmyjob.io) - 通过实时弹性 Spike 实例更智能地运行 GitHub Actions 和 GitLab CI。免费套餐含 400 vCPU-分钟、800 GB-分钟和 10 个并发作业，高性能 Runner 每个作业提供 12 vCPU 与 32GB RAM。
  * [Shipfox](https://www.shipfox.io/) - 让 GitHub Actions 快 2 倍，每月免费 3,000 构建分钟。
  * [Spacelift](https://spacelift.io/) - 基础设施即代码管理平台。免费方案包含 IaC 协作、Terraform 模块注册表、ChatOps、基于 Open Policy Agent 的持续资源合规、SAML 2.0 SSO 和公共 Worker Pool，每月最多 200 分钟。
  * [Squash Labs](https://www.squash.io/) - 为每个分支创建 VM，并通过唯一 URL 提供应用访问。公开和私有仓库不限，VM 最大 2GB。
  * [Terramate](https://terramate.io/) - Terraform、OpenTofu 和 Terragrunt 等 IaC 工具的编排与管理平台，最多 2 名用户免费，包含全部功能。
  * [Terrateam](https://terrateam.io) - GitOps 优先的 Terraform 自动化，支持 Pull Request 驱动工作流、通过自托管 Runner 实现项目隔离及按顺序执行的分层运行。最多 3 名用户免费。
  * [Trigger.dev](https://trigger.dev) - 开源后台任务和 AI Agent 平台，提供持久任务、无超时和实时能力。免费方案每月 5 美元计算额度、20 个并发运行、无限任务、5 名团队成员、10 个计划任务和 1 天日志保留。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="testing"></a>
## 测试

<details>
<summary>展开 / 收起服务列表</summary>

  * [Appetize](https://appetize.io) - 直接在浏览器中的云端 Android 手机/平板模拟器和 iPhone/iPad 模拟器上测试 Android 与 iOS 应用。免费套餐含 2 个并发会话和每月 30 分钟使用时间，应用大小不限。
  * [Argos](https://argos-ci.com) - 面向开发者的开源视觉测试，项目数量不限，每月 5,000 张截图，开源项目免费。
  * [Bencher](https://bencher.dev/) - 用于发现 CI 性能回退的持续基准测试工具套件，所有公开项目免费。
  * [BugBug](https://bugbug.io/) - 轻量 Web 应用测试自动化工具，易学且无需编码。可在自己的电脑上免费无限运行测试；云监控和 CI/CD 集成需额外按月付费。
  * [checkbot.io](https://www.checkbot.io/) - 浏览器扩展，用于检查网站是否符合 50 多项 SEO、速度和安全最佳实践，小型网站可使用免费套餐。
  * [Checkly](https://checklyhq.com) - 面向现代 DevOps 的代码优先合成监控，以较低成本监控 API 和应用，采用 Monitoring as Code 与 Playwright 工作流，为开发者提供慷慨免费套餐。
  * [CORS-Tester](https://cors-error.dev/cors-tester/) - 免费工具，可检查 API 是否为指定域名启用 CORS 并识别缺口，提供可执行建议。
  * [cypress.io](https://www.cypress.io/) - 快速、简单且可靠地测试浏览器中运行的一切。Cypress Test Runner 永久免费开源且没有限制；Cypress Dashboard 对最多 5 名用户的开源项目免费。
  * [everystep-automation.com](https://www.everystep-automation.com/) - 记录并重放浏览器中的所有操作步骤并生成脚本，免费版功能较少。
  * [gridlastic.com](https://www.gridlastic.com/) - Selenium Grid 测试，免费方案最多 4 个并发 Selenium 节点、每月 10 次 Grid 启动和 4,000 测试分钟。
  * [katalon.com](https://katalon.com) - 为不同规模和测试成熟度的团队提供测试平台，包括 Katalon Studio、TestOps（含免费视觉测试）、TestCloud 和 Katalon Recorder。
  * [Keploy](https://keploy.io/) - 面向开发者的功能测试工具包，记录 API 调用后生成 API 端到端测试（KTests）和 Mock/Stub（KMocks），开源项目免费。
  * [Lastest](https://lastest.cloud) - 通过 AI 辅助的视觉验证和可信测试快速发布并避免破坏。永久免费方案含 1 个项目、每月 500 Runner 分钟、1 个并发运行，无需信用卡。
  * [loadmill.com](https://www.loadmill.com/) - 通过分析网络流量自动创建 API 和负载测试，每月可免费模拟最多 50 个并发用户，最长 60 分钟。
  * [lost-pixel.com](https://lost-pixel.com) - 面向 Storybook、Ladle、Histoire Story 和 Web 应用的完整视觉回归测试，团队成员不限，开源项目完全免费，每月 7,000 个快照。
  * [pagegym.com](https://pagegym.com) - 负载行为、页面速度分析与优化工具。免费方案每天 10 次测试、每周 5 个实验、每月最多写入 15GB 数据。
  * [percy.io](https://percy.io) - 为任意 Web 应用、静态站点、样式指南或组件库添加视觉测试，含无限团队成员、演示应用、无限项目和每月 5,000 个快照。
  * [qase.io](https://qase.io) - 面向开发和 QA 团队的测试管理系统，可管理测试用例、组合测试运行、执行测试、跟踪缺陷和衡量影响。免费套餐包含所有核心功能、500MB 附件空间和最多 3 名用户。
  * [Repeato](https://repeato.app/) - 基于计算机视觉和 AI 的无代码移动应用测试自动化工具，适用于原生应用、Flutter、React Native、Web、Ionic 等框架。免费方案限 10 个 iOS 测试和 10 个 Android 测试，但包含付费方案的大部分功能及无限测试运行。
  * [Requestly](https://requestly.com/) - 用于拦截、重定向和模拟 HTTP 请求的开源 Chrome 扩展，包含 [Debugger](https://requestly.com/products/web-debugger/)、[Mock Server](https://requestly.com/products/mock-server/)、[API Client](https://requestly.com/products/api-client/) 和 [Session Recording](https://requestly.com/products/session-book/)。可重定向 URL、修改 HTTP Header、模拟 API、注入自定义 JS、修改 GraphQL 请求、生成模拟 API 端点，并记录网络与控制台日志。免费套餐最多创建 10 条规则，开源项目免费。
  * [seotest.me](https://seotest.me/) - 免费站内 SEO 测试工具，每天可免费抓取 10 个网站，提供 SEO 学习资源和适用于任意技术栈的网站优化建议。
  * [Sherlo](https://sherlo.io) - React Native 应用的视觉回归测试。免费计划每月 1000 个 snapshots，支持 iOS 和 Android 模拟器。
  * [snippets.uilicious.com](https://snippets.uilicious.com) - 类似用于跨浏览器测试的 CodePen。UI-licious 可像编写用户故事一样写测试，并提供免费 UI-licious Snippets 平台；无需注册即可在 Chrome 上无限运行测试，每次最长 3 分钟。发现缺陷后可复制唯一测试 URL，向开发者展示复现方式。
  * [SSR (Server-side Rendering) Checker](https://www.crawlably.com/ssr-checker/) - 通过可视化比较页面的服务端渲染版本与常规版本，检查任意 URL 的 SSR。
  * [testingbot.com](https://testingbot.com/) - Selenium 浏览器和设备测试，[free for Open Source](https://testingbot.com/open-source)。
  * [Testspace.com](https://testspace.com/) - 用于发布自动化测试结果的仪表板，以及将手动测试实现为代码的框架。服务[free for Open Source](https://github.com/marketplace/testspace-com)，每月 450 个结果。
  * [tesults.com](https://www.tesults.com) - 测试结果报告和测试用例管理，可集成常用测试框架。开源开发者、个人、教育者和刚起步的小团队可申请超出基础免费项目范围的折扣或免费方案。
  * [UseWebhook.com](https://usewebhook.com) - 在浏览器中捕获和检查 Webhook，可转发至 localhost 或从历史记录重放，免费使用。
  * [Vaadin](https://vaadin.com) - 使用 Java 或 TypeScript 构建可扩展 UI，并通过集成工具、组件和设计系统加速迭代、改善设计和简化开发。无限项目，免费维护 5 年。
  * [webhook.site](https://webhook.site) - 使用自定义 URL 验证 Webhook、出站 HTTP 请求或邮件，临时 URL 和电子邮件地址始终免费。
  * [websitepulse.com](https://www.websitepulse.com/tools/) - 提供多种免费网络和服务器工具。
  * [kogiQA](https://kogiqa.com) - 无需选择器的 Web UI 自动化工具，每名开发者每月免费 500 个操作。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="security-and-pki"></a>
## 安全与 PKI

<details>
<summary>展开 / 收起服务列表</summary>

  * [aikido.dev](https://www.aikido.dev) - 一体化应用安全平台，覆盖 SCA、SAST、CSPM、DAST、Secrets、IaC、恶意软件、容器扫描、EOL 等。免费方案含 2 名用户、扫描 10 个仓库、1 个云、2 个容器和 1 个域名。
  * [CertKit](https://www.certkit.io/certificate-management) - 管理 SSL 证书签发、续期和监控，并搜索证书透明度日志。Beta 结束后可免费管理 3 张证书和 1 名用户。
  * [CertObserver CT Search](https://certobserver.com/ct-search) - 查找记录在证书透明度日志中的公开 SSL/TLS 证书。CT 搜索免费，但 CT 监控收费。
  * [CertPost](https://www.certpost.ai) - 实时 SSL/TLS 证书监控，支持 443 或自定义端口（SMTP/IMAP）。直接读取线上提供的证书，进行完整证书链验证，并在到期前通过 email 或 webhook 告警。免费层可永久免费监控 3 张证书。
  * [Corgea](https://corgea.com/) - 免费自主安全平台，可在 20 多种语言和框架中发现、验证并修复不安全代码和软件包。免费方案含 1 名用户和 2 个仓库。
  * [crypteron.com](https://www.crypteron.com/) - 云优先、开发者友好的安全平台，可防止 .NET 和 Java 应用发生数据泄露。
  * [CyberChef](https://gchq.github.io/CyberChef/) - 简单直观的 Web 应用，无需复杂工具或编程即可分析、解码和编码数据，如同密码学与加密领域的瑞士军刀。所有功能免费且不限使用，也可开源自托管。
  * [Datree](https://www.datree.io/) - 开源 CLI 工具，通过确保 Manifest 和 Helm Chart 符合最佳实践及组织策略，防止 Kubernetes 配置错误。
  * [Dependabot](https://dependabot.com/) - 自动更新 Ruby、JavaScript、Python、PHP、Elixir、Rust、Java（Maven 和 Gradle）、.NET、Go、Elm、Docker、Terraform、Git Submodule 和 GitHub Actions 依赖。
  * [DJ Checkup](https://djcheckup.com) - 免费自动检查 Django 站点中的安全缺陷，源自 Pony Checkup 项目分支。
  * [Doppler](https://doppler.com/) - 通用应用 Secret 与配置管理器，支持同步到多种云服务商，基础访问控制下最多 5 名用户免费。
  * [Dotenv](https://dotenv.org/) - 快速安全地同步 `.env` 文件，避免通过 Slack 和邮件等不安全渠道分享，也不再丢失重要 `.env` 文件。最多 3 名团队成员免费。
  * [GitGuardian](https://www.gitguardian.com) - 通过自动 Secret 检测和修复避免源码泄密，可扫描 Git 仓库中 350 多种 Secret 和敏感文件；个人及不超过 25 名开发者的团队免费。
  * [HasMySecretLeaked](https://gitguardian.com/hasmysecretleaked) - 免费搜索公开 GitHub 仓库、Gist、Issue 和评论中超过 2,000 万个已暴露 Secret。
  * [Have I been pwned?](https://haveibeenpwned.com) - 用于获取数据泄露信息的 REST API。
  * [HimitsuShell](https://himitsushell.com) - Shell 脚本 DRM 编译器，使用嵌入式 Shell 解释器和反调试技术将 Shell 脚本转换为混淆二进制文件（shc 的替代品），Web 版可免费无限使用。
  * [hostedscan.com](https://hostedscan.com) - 面向 Web 应用、服务器和网络的在线漏洞扫描器，每月 10 次免费扫描。
  * [Infisical](https://infisical.com/) - 开源平台，可在团队和基础设施各环节管理开发 Secret，从本地开发到预发布/生产和第三方服务均覆盖。最多 5 名开发者免费。
  * [inspect.software](https://inspect.software/) - 自动化开源仓库审计的公开记录，涵盖安全状况、可维护性、依赖健康和恶意包检查，并提供版本化方法论与等级徽章。免费层可访问全部公开报告；达到公共关注阈值的仓库会自动覆盖（≥500 stars、≥50 forks，或组织仓库且 ≥250 stars）；支持嵌入徽章，并提供 100 个初始 credits（可用于 5 次低于阈值仓库的检查）。
  * [Internet.nl](https://internet.nl) - 测试 IPv6、DNSSEC、HTTPS、DMARC、STARTTLS 和 DANE 等现代互联网标准。
  * [IntoDNS.ai](https://intodns.ai) - DNS 与邮件安全分析器，可检查 SPF、DKIM、DMARC、DNSSEC、BIMI、MTA-STS 和 40 多个黑名单，并通过 AI 给出说明与修复建议。完全免费，无需注册。
  * [letsencrypt.org](https://letsencrypt.org/) - 免费 SSL 证书颁发机构，证书受所有主流浏览器信任。
  * [meterian.io](https://www.meterian.io/) - 监控 Java、JavaScript、.NET、Scala、Ruby 和 NodeJS 项目的依赖安全漏洞。1 个私有项目免费，开源项目不限。
  * [Mozilla Observatory](https://observatory.mozilla.org/) - 查找并修复网站安全漏洞。
  * [Otterwatch](https://otterwatch.dev/) - 每日监控 SSL/TLS 证书，包括到期告警（提前 30/7/1 天）、证书链和 OCSP 吊销检查，以及证书透明度签发历史。5 个域名永久免费，无需信用卡。
  * [Protectumus](https://protectumus.com) - 免费网站安全检查、站点杀毒和 PHP 服务器防火墙（WAF），免费套餐注册用户可接收邮件通知。
  * [Public Cloud Threat Intelligence](https://cloudintel.himanshuanand.com/) - 针对公有云基础设施的高可信失陷指标（IOC）。部分内容可在 GitHub（https://github.com/unknownhad/AWSAttacks）获取，完整列表通过 API 提供。
  * [pyup.io](https://pyup.io/) - 监控 Python 依赖安全漏洞并自动更新。1 个私有项目免费，开源项目不限。
  * [qualys.com](https://www.qualys.com/community-edition) - 查找 Web 应用漏洞并审计 OWASP 风险。
  * [SikkerKey](https://sikkerkey.com) - 机器认证的 Secret 管理器，免费含 2 个项目、2 台已引导机器、20 个 Secret 和 7 天审计日志保留。
  * [Smart Grow Vault](https://vault.smart-grow.app/) - 安全的企业级环境变量和 Secret 管理平台，免费套餐每个项目最多 3 个应用和 150 个 Secret。
  * [Socket](https://socket.dev) - 为个人开发者、小团队和开源项目提供免费供应链安全，含免费应用和防火墙 CLI，保护代码免受脆弱或恶意依赖影响，可检测 70 多种供应链风险指标。
  * [ssllabs.com](https://www.ssllabs.com/ssltest/) - 深入分析任意 SSL Web 服务器配置。
  * [Sucuri SiteCheck](https://sitecheck.sucuri.net) - 免费网站安全检查和恶意软件扫描器。
  * [TestTLS.com](https://testtls.com) - 测试 SSL/TLS 服务的服务器配置、证书和证书链等安全性，不限于 HTTPS。
  * [Virgil Security](https://virgilsecurity.com/) - 为数字解决方案实现端到端加密、数据库保护、IoT 安全等的工具与服务，最多 250 名用户的应用免费。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="authentication-authorization-and-user-management"></a>
## 身份认证、授权与用户管理

<details>
<summary>展开 / 收起服务列表</summary>

  * [360username](https://360username.com/) - 免费在 90 多个社交平台搜索用户名并查找匹配账号。
  * [Aserto](https://www.aserto.com) - 面向应用和 API 的细粒度授权即服务，最多 1,000 MAU 和 100 个 Authorizer 实例免费。
  * [asgardeo.io](https://wso2.com/asgardeo) - 无缝集成 SSO、MFA、无密码认证等，并提供前后端 SDK。最多 1,000 MAU 和 5 个身份提供商免费。
  * [Auth0](https://auth0.com/) - 托管 SSO，免费方案含 25,000 MAU、无限社交登录、自定义域名等。
  * [Authgear](https://www.authgear.com) - 数分钟内为应用加入无密码认证、OTP、2FA 和 SSO，包含完整前端，最多 5,000 MAU 免费。
  * [Authress](https://authress.io/) - 身份认证登录与访问控制，可为任意项目使用无限身份提供商，包括 Facebook、Google、Twitter 等，前 1,000 次 API 调用免费。
  * [Authy](https://authy.com) - 多设备双因素认证（2FA），支持备份，可直接替代 Google Authenticator。最多 100 次成功认证免费。
  * [Cerbos Hub](https://www.cerbos.dev/product-cerbos-hub) - 完整授权管理系统，用于编写、测试和部署访问策略，提供细粒度授权和访问控制，最多 100 个每月活跃主体免费。
  * [Clerk](https://clerk.com) - 用户管理、身份认证、2FA/MFA，以及登录、注册、用户资料等预构建 UI 组件。免费方案含无限应用、每应用 50,000 MRU、3 个仪表板席位等。
  * [Cloud-IAM](https://www.cloud-iam.com/) - Keycloak 身份与访问管理即服务，最多 100 名用户和 1 个 Realm 免费。
  * [Descope](https://www.descope.com/) - 高度可定制的 AuthN 流程，同时支持无代码与 API/SDK 方式。每月 7,500 名活跃用户和 50 个 Tenant（最多 5 个 SAML/SSO Tenant）免费。
  * [duo.com](https://duo.com/) - 网站或应用的双因素认证（2FA），10 名用户免费，支持所有认证方式、无限集成和硬件 Token。
  * [Kinde](https://kinde.com/) - 简单可靠的身份认证，可在数分钟内集成到产品中，起步所需功能齐全，每月 7,500 MAU 免费。
  * [logintc.com](https://www.logintc.com/) - 通过推送通知实现双因素认证（2FA），10 名用户免费，适用于 VPN、网站和 SSH。
  * [Logto](https://logto.io/) - 开发、保护和管理产品用户身份，覆盖身份认证与授权。最多 5,000 MAU 免费，并提供开源自托管选项。
  * [MojoAuth](https://mojoauth.com/) - 数分钟内在 Web、移动或其他应用中轻松实现无密码认证。
  * [Okta](https://developer.okta.com/signup/) - 用户管理、身份认证和授权，最多 100 MAU 免费。
  * [Ory](https://ory.sh/) - AuthN/AuthZ/OAuth 2.0/零信任托管安全平台。开发者账号永久免费，包含所有安全功能、无限团队成员、每天 200 名活跃用户和每月 25,000 次权限检查。
  * [Permit.io](https://permit.io) - 授权即服务平台，通过实时更新和无代码策略 UI 为可扩展微服务提供 RBAC、ABAC 和 ReBAC。免费套餐含 1,000 MAU。
  * [Phase Two](https://phasetwo.io) - Keycloak 开源身份与访问管理。免费 Realm 最多 1,000 名用户、10 个 SSO 连接，使用 Phase Two 增强版 Keycloak 容器并包含 [Organization](https://phasetwo.io/product/organizations/) 扩展。
  * [PropelAuth](https://propelauth.com) - 只需几行代码即可立即向任意规模企业销售，最多 200 名用户和 10,000 封事务邮件免费，邮件带“Powered by PropelAuth”水印。
  * [Scalekit](https://scalekit.com) - 面向 B2B SaaS 的企业 SSO（SAML、OIDC）、SCIM Provisioning 和社交登录。免费套餐含 100 万 MAU、100 个组织、1 个 SSO 连接和 1 个 SCIM 连接。
  * [Stack Auth](https://stack-auth.com) - 开源且开发者友好的身份认证方案，5 分钟即可开始。可免费自托管，也提供含 10,000 MAU 的托管 SaaS 免费版。
  * [Stytch](https://www.stytch.com/) - 提供身份认证和欺诈防护 API/SDK 的一体化平台。免费方案含 10,000 MAU、无限组织、5 个 SSO 或 SCIM 连接及 1,000 个 M2M Token。
  * [SuperTokens](https://supertokens.com/) - 原生集成应用的开源用户认证方案，可快速起步并控制用户与开发者体验。最多 5,000 MAU 免费。
  * [WorkOS](https://workos.com/) - 最多 100 万 MAU 的免费用户管理和身份认证，支持邮箱密码、社交登录、Magic Auth、MFA 等。
  * [ZITADEL Cloud](https://zitadel.com) - 开箱即用的用户与访问管理，支持多租户 B2B 场景。最多 25,000 次认证请求免费，所有安全功能均无付费墙，包括 OTP、无密码和策略等。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="mobile-app-distribution-and-feedback"></a>
## 移动应用分发与反馈

<details>
<summary>展开 / 收起服务列表</summary>

  * [Appho.st](https://appho.st) - 移动应用托管平台，免费方案含 5 个应用、每月 50 次下载，最大文件 100MB。
  * [Diawi](https://www.diawi.com) - 将 iOS 和 Android 应用直接部署到设备。免费方案支持应用上传、密码保护链接、1 天有效期和 10 次安装。
  * [GetUpdraft](https://www.getupdraft.com) - 分发移动应用用于测试。免费方案含 1 个应用项目、3 个应用版本、500MB 存储和每月 100 次安装。
  * [InstallOnAir](https://www.installonair.com) - 通过 OTA 分发 iOS 和 Android 应用。免费方案支持无限上传、私密链接，访客链接 2 天有效，注册用户链接 60 天有效。
  * [Loadly](https://loadly.io) - iOS 和 Android Beta 应用分发服务，下载次数、上传次数不限并提供高速下载，完全免费。
  * [DistApp](https://distapp.app) - 管理和分发 Android、iOS 与桌面应用，适合测试或自行分发。免费方案含 2 个应用、1 个组织、100MB 存储和无限下载，也可自托管。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="management-system"></a>
## 管理系统

<details>
<summary>展开 / 收起服务列表</summary>

  * [bitnami.com](https://bitnami.com/) - 在 IaaS 上部署预配置应用，可免费管理 1 台 AWS Micro 实例。
  * [Esper](https://esper.io) - 面向 Android 设备、具备 DevOps 能力的 MDM 和 MAM。免费支持 100 台设备、1 个用户许可证和 25MB 应用存储。
  * [jamf.com](https://www.jamf.com/) - iPad、iPhone 和 Mac 设备管理，3 台设备免费。
  * [Miradore](https://miradore.com) - 设备管理服务，可持续了解设备群状态并免费保护无限设备；免费方案提供基础功能。
  * [ploi.io](https://ploi.io/) - 用于轻松管理和部署服务器与站点的服务器管理工具，1 台服务器免费。
  * [runcloud.io](https://runcloud.io/) - 主要面向 PHP 项目的服务器管理工具，最多 1 台服务器免费。
  * [serveravatar.com](https://serveravatar.com) - 通过自动配置管理和监控 PHP Web 服务器，1 台服务器免费。
  * [xcloud.host](https://xcloud.host) - 界面友好的服务器管理与部署平台，1 台服务器可用免费套餐。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="messaging-and-streaming"></a>
## 消息与流处理

<details>
<summary>展开 / 收起服务列表</summary>

  * [Ably](https://www.ably.com/) - 提供在线状态、持久化和可靠投递的实时消息服务。免费方案每月 300 万条消息、100 个峰值连接和 100 个峰值频道。
  * [cloudamqp.com](https://www.cloudamqp.com/) - RabbitMQ 即服务。Little Lemur 方案每月最多 100 万条消息、20 个并发连接、100 个队列、10,000 条排队消息，并支持位于不同可用区的多个节点。
  * [courier.com](https://www.courier.com/) - 通过单一 API 处理推送、应用内、邮件、聊天、短信等消息渠道，并提供模板管理等功能。免费方案每月 10,000 条消息。
  * [EMQX Serverless](https://www.emqx.com/en/cloud/serverless-mqtt) - 可在数秒内获得可扩展、安全的无服务器 MQTT Broker，每月 100 万会话分钟永久免费，无需信用卡。
  * [Engage](https://engage.so/) - 面向 SaaS 的一体化客户互动与自动化工具，支持邮件、推送、短信、产品导览、横幅等。每月最多 1,000 名活跃用户免费。
  * [engagespot.co](https://engagespot.co/) - 面向开发者的多渠道通知基础设施，内置应用内收件箱和无代码模板编辑器。免费方案每月 10,000 条消息。
  * [HiveMQ](https://www.hivemq.com/mqtt-cloud-broker/) - 将 MQTT 设备连接到云原生 IoT 消息 Broker，最多 100 台设备永久免费，无需信用卡。
  * [httpSMS](https://httpsms.com) - 将 Android 手机作为短信网关，通过 API 收发短信，每月最多 200 条免费。
  * [knock.app](https://knock.app) - 面向开发者的通知基础设施，只需一次 API 调用即可向应用内、邮件、短信、Slack 和推送等多渠道发送通知。免费方案每月 10,000 条消息。
  * [Novu.co](https://novu.co) - 面向开发者的开源通知基础设施，通过简单组件和 API 在一处管理邮件、短信、私信、应用内和推送渠道。免费方案每月 30,000 条通知，保留 90 天。
  * [Pingram.io](https://www.pingram.io/) - 5 分钟搭建通信基础设施。免费套餐含 100 条短信和通话、3,000 封邮件、推送、Slack、MS Teams、WhatsApp 等。
  * [Pocket Alert](https://pocketalert.app) - 向 iOS 和 Android 设备发送推送通知，可通过 API 或 Webhook 轻松集成并完全控制告警。免费方案每天向 1 台设备和 1 个应用发送 50 条消息。
  * [pubnub.com](https://www.pubnub.com/) - Swift、Kotlin 和 React 消息服务，每月 100 万次事务，每个事务可包含多条消息。
  * [pusher.com](https://pusher.com/) - 实时消息服务，最多 100 个并发连接和每天 200,000 条消息免费。
  * [scaledrone.com](https://www.scaledrone.com/) - 实时消息服务，最多 20 个并发连接和每天 100,000 个事件免费。
  * [SMSGate](https://sms-gate.app) - Android™ 短信网关，可通过设备和云路由收发短信。云服务完全免费；日用量超过 10,000 条时建议通知官方，以维持所有用户的服务质量。
  * [SuprSend](https://www.suprsend.com/) - API 优先的通知基础设施，可通过单一通知 API 创建并发送事务、Cron 和互动通知到多个渠道。免费方案每月 10,000 条通知，包含摘要、批处理、多渠道、偏好、租户、广播等工作流节点。
  * [synadia.com](https://synadia.com/ngs) - [NATS.io](https://nats.io) 即服务，覆盖全球及 AWS、GCP、Azure。永久免费，消息最大 4KB、50 个活跃连接、每月 5GB 数据。
  * [webpushr](https://www.webpushr.com/) - Web 推送通知，最多 10,000 名订阅者免费，推送通知不限，并支持浏览器内消息。
  * [vask](https://vask.dev) - 兼容 Pusher 的实时消息服务。Dev 套餐仅限本地开发，免费含 100 个并发连接、每月 100 万次广播、无限客户端事件和 32KB 消息大小。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="log-management"></a>
## 日志管理

<details>
<summary>展开 / 收起服务列表</summary>

  * [bugfender.com](https://bugfender.com/) - 每天最多 100,000 行日志免费，保留 24 小时。
  * [log.dog](https://log.dog/) - 面向 iOS 和 Android 的远程调试/日志 SDK，提供 Web UI，实时捕获所有日志、请求和事件并允许拦截。每月最多 100MB 日志免费。
  * [logflare.app](https://logflare.app/) - 每个应用每月最多 12,960,000 条记录免费，保留 3 天。
  * [logtail.com](https://logtail.com/) - 基于 ClickHouse、兼容 SQL 的日志管理，每月最多 1GB 免费，保留 3 天。
  * [logzab.com](https://logzab.com/) - 审计轨迹管理系统，每月免费 1,000 条用户活动日志，保留 1 个月，最多 5 个项目。
  * [ManageEngine Log360 Cloud](https://www.manageengine.com/cloud-siem/) - ManageEngine 提供的日志管理服务，免费方案含 50GB 存储、15 天存储保留和 7 天搜索。
  * [openobserve.ai](https://openobserve.ai/) - 每月免费写入 200GB，保留 15 天。
  * [Smart Grow Logs](https://logs.smart-grow.app/) - 集中式日志管理平台，支持端到端加密、实时告警和多平台 SDK。免费套餐每天最多 3,000 条日志。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="translation-management"></a>
## 翻译管理

<details>
<summary>展开 / 收起服务列表</summary>

  * [AutoLocalise.com](https://www.autolocalise.com/) - 无需管理翻译文件即可即时本地化，每月最多 10,000 字符免费，语言数量不限。
  * [crowdin.com](https://crowdin.com/) - 开源项目可使用无限项目、字符串和协作者。
  * [Free PO editor](https://pofile.net/free-po-editor) - 所有人均可免费使用。
  * [Lingo.dev](https://lingo.dev) - 面向 Web 和移动端本地化的开源 AI CLI，可自带 LLM，或通过 Lingo.dev 托管本地化引擎每月免费翻译 10,000 个单词。
  * [lingohub.com](https://lingohub.com/) - 最多 3 名用户免费，开源项目永久免费。
  * [Localhero.ai](https://localhero.ai) - 在每个 Pull Request 中自动生成符合品牌风格的翻译，并支持术语表和翻译记忆。免费方案含 1 个项目、每月 250 个翻译积分（约 4,000 个单词）。
  * [localazy.com](https://localazy.com) - 免费支持源语言 1,000 个字符串、无限语言和无限贡献者，并提供创业公司及开源优惠。
  * [Localit](https://localit.io) - 快速、开发者友好的本地化平台，可免费无缝集成 GitHub/GitLab，支持 AI 辅助与人工翻译。免费方案含 2 名用户、500 个 Key 和无限项目。
  * [localizely.com](https://localizely.com/) - 开源项目免费。
  * [Loco](https://localise.biz/) - 最多 2,000 条翻译免费，翻译者不限，每个项目 10 种语言、1,000 个可翻译资源。
  * [POEditor](https://poeditor.com/) - 最多 1,000 个字符串免费。
  * [SimpleLocalize](https://simplelocalize.io/) - 最多 100 个翻译 Key 免费，字符串和语言不限，并提供创业公司优惠。
  * [Texterify](https://texterify.com/) - 单用户免费。
  * [Tolgee](https://tolgee.io) - 提供翻译数量有限的免费 SaaS，以及永久免费自托管版本。
  * [transifex.com](https://www.transifex.com/) - 开源项目免费。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="monitoring"></a>
## 监控

<details>
<summary>展开 / 收起服务列表</summary>

  * [Pingzo](https://www.pingzoapp.com) - 免费套餐提供 1 个可用性/API 监控，15 分钟检查间隔和即时邮件告警。
  * [Accesserty Pulse](https://accesserty.com/en/pulse) - 监控真实网站上的交互信号和可检测无障碍风险，所有人均可使用免费方案，并提供 14 天 Pro 试用。
  * [AlertKick](https://www.alertkick.com) - 将服务器安全（Linux eBPF agent）、可用性监控、on-call 告警和状态页集成在一个产品中。免费层包含 10 个 uptime monitors 和 heartbeats，5 分钟检查间隔、7 天数据保留。
  * [assertible.com](https://assertible.com) - 自动 API 测试与监控，为团队和个人提供免费方案。
  * [Better Stack](https://betterstack.com/better-uptime) - 将可用性监控、事件管理、值班排期/告警和状态页整合于一款产品。免费方案含 10 个监控项、3 分钟检查频率和状态页。
  * [bleemeo.com](https://bleemeo.com) - 免费监控 3 台服务器和 5 个可用性端点，用户、仪表板和告警规则不限。
  * [checklyhq.com](https://checklyhq.com) - 面向开发者的开源端到端/合成监控和深度 API 监控。免费方案含 1 名用户、10,000 次 API/网络检查和 1,500 次浏览器检查运行。
  * [Core Web Vitals History](https://punits.dev/core-web-vitals-historical/) - 查询 URL 或网站的 Core Web Vitals 历史。
  * [cronitor.io](https://cronitor.io/) - 为 Cron Job、网站、API 等提供性能洞察和可用性监控，免费套餐含 5 个监控项。
  * [datadoghq.com](https://www.datadoghq.com/) - 最多 5 个节点免费。
  * [deadmanssnitch.com](https://deadmanssnitch.com/) - Cron Job 监控，免费 1 个 Snitch（监控项），邀请他人注册可获得更多。
  * [downtimemonkey.com](https://downtimemonkey.com/) - 60 个可用性监控，5 分钟间隔，支持邮件和 Slack 告警。
  * [drumbeats.io](https://drumbeats.io/) - Cron、心跳和可用性监控，带事件管理和状态页。免费支持最多 50 个监控、1 分钟间隔和无限团队席位。
  * [economize.cloud](https://economize.cloud) - 通过整理云资源，帮助理解、优化和报告云基础设施成本。每月 Google Cloud Platform 支出不超过 5,000 美元时免费。
  * [fivenines.io](https://fivenines.io/) - Linux 服务器监控，提供实时仪表板和告警；最多 5 台服务器、60 秒间隔永久免费，无需信用卡。
  * [FlareWarden](https://flarewarden.com) - 可用性、内容、依赖和 SSL 监控，支持多区域验证和状态页。免费方案含 15 个监控、5 分钟检查和 90 天历史。
  * [Grafana Cloud](https://grafana.com/products/cloud/) - 可组合可观测性平台，将指标和日志与 Grafana 集成。免费含 3 名用户、10 个仪表板、100 个告警；Prometheus 和 Graphite 指标存储（10,000 个序列，保留 14 天），以及 Loki 日志存储（50GB 日志，保留 14 天）。
  * [healthchecks.io](https://healthchecks.io) - 监控 Cron Job 和后台任务，最多 20 个检查免费。
  * [incidenthub.cloud](https://incidenthub.cloud/) - 云和 SaaS 状态页聚合器，20 个监控和 2 个通知渠道（Slack 与 Discord）永久免费。
  * [inspector.dev](https://www.inspector.dev) - 不到一分钟即可搭建完整实时监控仪表板，提供永久免费套餐。
  * [instatus.com](https://instatus.com) - 10 秒创建美观状态页，订阅者和团队不限，永久免费。
  * [isitdownstatus.com](https://isitdownstatus.com) – 免费公开 JSON API，返回 GitHub、Stripe、AWS 等 500 多项热门服务的实时状态，无需认证，支持 CORS。
  * [linkok.com](https://linkok.com) - 在线失效链接检查器，最多 100 页的小型网站免费，开源项目完全免费。
  * [loader.io](https://loader.io/) - 有限制的免费负载测试工具。
  * [MarionetteOps.com](https://www.marionetteops.com/) - 服务器监控、公开状态页和服务可用性监控。
  * [Middleware.io](https://middleware.io/) - 可观测性平台，可完整查看应用和技术栈，便于大规模监控和诊断。面向开发者社区提供永久免费方案，支持最多 100 万个日志事件、2 台主机的基础设施监控和 APM。
  * [MonitorMonk](https://monitormonk.com) - 极简可用性监控和美观状态页。永久免费方案可对 10 个网站或 API 端点进行 HTTPS、关键字、SSL 和响应时间监控，并提供 2 个仪表板/状态页。
  * [netdata.cloud](https://www.netdata.cloud/) - 收集实时指标的开源工具，持续开发中，也可在 GitHub 获取。
  * [newrelic.com](https://www.newrelic.com) - 帮助工程师构建更完善软件的可观测性平台，可检测从单体到无服务器的所有组件，并分析、排障和优化整个技术栈。免费套餐每月含 100GB 数据写入、1 名完整访问用户和无限基础用户。
  * [OnlineOrNot.com](https://onlineornot.com) - 为网站和 API 提供可用性监控，为 Cron Job 与计划任务提供监控，并提供状态页。前 5 个检查以 3 分钟间隔免费，免费套餐通过 Slack、Discord 和邮件发送告警。
  * [OntarioNet.ca CN Test](https://cntest.ontarionet.ca) - 检查网站是否被中国防火长城屏蔽，通过比较中国服务器与美国服务器检测的 DNS 结果和 ASN 信息识别 DNS 污染。
  * [pagecrawl.io](https://pagecrawl.io/) - 监控网站变化，最多 6 个监控项免费，每天检查。
  * [pagertree.com](https://pagertree.com/) - 简单的告警和值班管理界面，最多 5 名用户免费。
  * [phare.io](https://phare.io/) - 可用性监控，支持无限项目和无限状态页，最多 100,000 个事件免费。
  * [pingbreak.com](https://pingbreak.com/) - 现代可用性监控，可检查无限 URL，并通过 Discord、Slack 或邮件接收宕机通知。
  * [Pingmeter.com](https://pingmeter.com/) - 5 个可用性监控，10 分钟间隔，可监控 SSH、HTTP、HTTPS 和任意自定义 TCP 端口。
  * [pingpong.one](https://pingpong.one/) - 带监控的高级状态页平台。免费套餐含 1 个可自定义公开状态页和 SSL 子域名；开源项目及非营利组织可免费使用 Pro 方案。
  * [Prismix](https://prismix.dev) - 免费 REST API（GET /api/v1/statuses），返回 OpenAI、Anthropic、Gemini、Mistral 等 75 多项 AI 服务的实时运行状态，无需认证。[提供免费套餐，Pro 每月 10 美元]
  * [Pulsetic](https://pulsetic.com) - 免费包含 10 个监控、6 个月可用性/日志历史、无限状态页、自定义域名和无限邮件告警，永久有效且无需信用卡。
  * [robusta.dev](https://home.robusta.dev/) - 基于 Prometheus 的强大 Kubernetes 监控，可自带 Prometheus 或安装一体化套件。免费套餐最多 20 个 Kubernetes 节点，支持 Slack、Microsoft Teams、Discord 等告警，并可集成 PagerDuty、OpsGenie、VictorOps、DataDog 等工具。
  * [Runframe](https://runframe.io/) - 值班告警、事件管理及公开/私密状态页。免费方案含最多 5 名用户、1 个团队、1 个值班排期、基础状态页、事件生命周期和 Slack 原生事件响应。
  * [Servervana](https://servervana.com) - 面向大型项目和团队的高级可用性监控，支持 HTTP、浏览器、DNS、域名、状态页等。免费套餐含 10 个 HTTP 监控、1 个 DNS 监控和 1 个状态页。
  * [Simple Observability](https://simpleobservability.com) - 在统一平台中提供强大的服务器指标和日志监控，配置简单，1 台服务器免费。
  * [sitesure.net](https://sitesure.net) - 网站和 Cron 监控，2 个监控项免费。
  * [skylight.io](https://www.skylight.io/) - 前 100,000 次请求免费（仅 Rails）。
  * [statuscake.com](https://www.statuscake.com/) - 网站监控，测试数量不限，但免费版有功能限制。
  * [statusgator.com](https://statusgator.com/) - 状态页监控，3 个监控项免费。
  * [supaguard.app](https://supaguard.app/) - 从 20 多个全球地区执行合成监控。免费套餐每月 1,000 次浏览器检查，包含 AI 自愈和自动生成测试。
  * [superlog.sh](https://superlog.sh/) - 开源 OpenTelemetry 可观测性平台，覆盖 Trace、日志和指标，并由 AI Agent 调查事件。免费套餐每月含 100 万 Span、500 万条日志和 1,000 万个指标点，保留 30 天，无需信用卡；完全开源且可自托管。
  * [SweetUptime](https://dicloud.net/sweetuptime-server-uptime-monitoring/) - 服务器、可用性、DNS 和域名监控，可免费监控 10 台服务器、10 个可用性端点和 10 个域名。
  * [syagent.com](https://syagent.com/) - 非商业用途免费的服务器监控服务，提供告警和指标。
  * [UptimeObserver.com](https://uptimeobserver.com) - 提供 20 个可用性监控、5 分钟间隔和可自定义状态页，也可用于商业用途。支持无限实时邮件和 Telegram 通知，无需信用卡。
  * [uptimetoolbox.com](https://uptimetoolbox.com/) - 免费监控 5 个网站，3 分钟间隔，提供公开状态页。
  * [Wachete](https://www.wachete.com) - 监控 5 个页面，每 24 小时检查一次。
  * [Xitoring.com](https://xitoring.com/) - 可用性监控免费 20 个，Linux/Windows 服务器监控免费 5 台，状态页免费 1 个，并提供移动应用、多通知渠道等。
  * [UptimeRobot](https://uptimerobot.com/) - 面向业余项目的免费可用性监控，含 50 个监控、5 分钟检查间隔，支持 HTTP、Ping、端口和关键字监控。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="crash-and-exception-handling"></a>
## 崩溃与异常处理

<details>
<summary>展开 / 收起服务列表</summary>

  * [Axiom](https://axiom.co/) - 最多存储 0.5TB 日志并保留 30 天，包含 Vercel 等平台集成、高级数据查询及邮件/Discord 通知。
  * [Bugsink](https://www.bugsink.com/) - 兼容 Sentry SDK 的错误跟踪，每月最多 5,000 个错误免费，自托管则不限使用。
  * [bugsnag.com](https://www.bugsnag.com/) - 初始试用结束后每月最多 2,000 个错误免费。
  * [CatchJS.com](https://catchjs.com/) - 带截图和点击轨迹的 JavaScript 错误跟踪，开源项目免费。
  * [elmah.io](https://elmah.io/) - 面向 Web 开发者的错误日志和可用性监控，为开源项目提供免费 Small Business 订阅。
  * [Embrace](https://embrace.io/) - 移动应用监控，小团队每年最多 100 万用户会话免费。
  * [exceptionless](https://exceptionless.com/) - 实时错误、功能和日志报告等，每月 3,000 个事件、1 名用户免费；开源且易于自托管，自托管后不限使用。
  * [GlitchTip](https://glitchtip.com/) - 简单开源的错误跟踪，兼容开源 Sentry SDK，每月 1,000 个事件免费，也可自托管且不限量。
  * [honeybadger.io](https://www.honeybadger.io) - 异常、可用性和 Cron 监控，小团队和开源项目免费（每月 12,000 个错误）。
  * [Jam](https://jam.dev) - 一键创建开发者友好的缺陷报告，免费方案可创建无限 Jam。
  * [memfault.com](https://memfault.com) - 云端设备可观测性和调试平台，[Nordic](https://app.memfault.com/register-nordic)、[NXP](https://app.memfault.com/register-nxp) 和 [Laird](https://app.memfault.com/register-laird) 设备可免费使用 100 台。
  * [rollbar.com](https://rollbar.com/) - 异常和错误监控，免费方案每月 5,000 个错误、无限用户、保留 30 天。
  * [Semaphr](https://semaphr.com) - 移动应用的一体化免费 Kill Switch。
  * [sentry.io](https://sentry.io/) - 实时跟踪应用异常并提供小型免费方案，每月 5,000 个错误、1 名用户；自托管时不限使用。
  * [Whitespace](https://whitespace.dev) - 直接在浏览器中一键提交缺陷报告，个人使用的免费方案可无限录制。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="search"></a>
## 搜索

<details>
<summary>展开 / 收起服务列表</summary>

  * [algolia.com](https://www.algolia.com/) - 托管搜索解决方案，提供拼写容错、相关性和 UI 库，便于构建搜索体验。免费 Build 方案含 100 万份文档和每月 10,000 次搜索，另免费提供[developer documentation search](https://docsearch.algolia.com/)。
  * [bonsai.io](https://bonsai.io/) - 免费 1GB 内存和 1GB 存储。
  * [CommandBar](https://www.commandbar.com/) - 统一搜索栏即服务，通过 Web UI 组件/插件让用户在产品中搜索内容、导航和功能，提升可发现性。最多 1,000 MAU 免费，命令不限。
  * [searchly.com](https://www.searchly.com/) - 免费 2 个索引和 20MB 存储。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="education-and-career-development"></a>
## 教育与职业发展

<details>
<summary>展开 / 收起服务列表</summary>

  * [Cisco Networking Academy, Skills for All](https://skillsforall.com/) - 提供与认证对应的免费课程，涵盖网络安全、网络和 Python 等主题。
  * [CloudCertPrep](https://cloudcertprep.io) - 免费开源 AWS 认证模拟考试，CLF-C02 含 1,050 多道题，提供计时模拟考、领域练习、间隔重复和进度跟踪。
  * [CodeTrain](https://codetrain.ai) - AI 编程导师，在你自己的代码库上教学且不会替你编写代码。免费套餐每月 10 节浏览器课程，Python/JS 在客户端运行，无需信用卡。
  * [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) - 行业顶尖专家提供的免费短课，可在 1 小时内动手体验最新生成式 AI 工具和技术。
  * [DevNet Academy](https://devnet-academy.com/) - 面向 Cisco DevNet Expert/CCIE Automation 认证的免费自学课程，覆盖 Python Click 和 Flask-RESTx。
  * [Django-tutorial.dev](https://django-tutorial.dev) - 面向第一次学习框架者的免费 Django 在线指南，并为用户撰写的文章提供免费 Dofollow 反向链接。
  * [edX](https://www.edx.org/) - 可访问来自 Harvard、MIT 等 250 家领先机构的 4,000 多门免费在线课程，重点覆盖计算机科学、工程和数据科学。
  * [Exercism](https://exercism.org) - 非营利开源编程教育平台，覆盖 75 多种编程语言并提供真人指导，免费使用。
  * [Free Professional Resume Templates & Editor](https://www.overleaf.com/latex/templates/tagged/cv) - 免费平台，提供大量资深专业人士简历模板，可克隆、完整编辑和下载，并针对 ATS 优化。
  * [FreeCodeCamp](https://www.freecodecamp.org/) - 开源平台，提供数据分析、信息安全、Web 开发等免费课程和认证。
  * [Full Stack Open](https://fullstackopen.com/en/) - 大学级现代 Web 开发免费课程，涵盖 React、Node.js、GraphQL、TypeScript 等，完全在线并可自主安排进度。
  * [Interactive CV](https://interactive-cv.com) - AI 简历构建器，支持实时编辑和 ATS 优化。免费套餐可将简历自动转换为 Harvard、Europass 等高级模板、导出 PDF，并提供职位跟踪器、无限职位分析及带聊天/语音功能的简历分享。
  * [Khan Academy](https://www.khanacademy.org/computing/computer-programming) - 免费在线指南，用于学习基础和进阶 HTML/CSS、JavaScript 与 SQL。
  * [LabEx](https://labex.io) - 通过交互式实验和真实项目学习 Linux、DevOps、网络安全、编程、数据科学等技能。
  * [MIT OpenCourseWare](https://ocw.mit.edu/) - 在线发布 2,500 多门 MIT 课程资料，向全球学习者和教育者免费分享知识。YouTube 频道见 [@mitocw](https://www.youtube.com/@mitocw/featured)。
  * [Reactive Resume](https://rxresu.me) - 免费开源简历构建器，提供数十种模板，可导出 PDF、DOCX，并可选择生成公开分享链接。
  * [Roadmap.sh](https://roadmap.sh) - 免费学习路线图，覆盖从区块链到 UX 设计的各类开发领域。
  * [The Odin Project](https://www.theodinproject.com/) - 免费开源学习平台，课程聚焦 JavaScript 和 Ruby Web 开发。
  * [W3Schools](https://www.w3schools.com/) - 提供 HTML、CSS、JavaScript 等 Web 开发技术的免费教程。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="email"></a>
## 邮件

<details>
<summary>展开 / 收起服务列表</summary>

  * [10minutemail](https://10minutemail.com) - 用于测试的免费临时邮箱。
  * [AhaSend](https://ahasend.com) - 事务邮件服务，每月免费 1,000 封，免费方案中的域名、团队成员、Webhook 和消息路由不限。
  * [AnonAddy](https://anonaddy.com) - 开源匿名邮件转发，可免费创建无限邮件别名。
  * [anon.li Alias](https://anon.li/alias) - 开源匿名邮件别名/转发方案，支持 PGP 加密和回复。免费方案含 10 个随机别名和 1 个自定义别名，并提供开发者 API 与 CLI。
  * [Antideo](https://www.antideo.com) - 免费套餐每小时 10 次 API 请求，可用于邮件、IP 和电话号码验证，无需信用卡。
  * [Anypost](https://anypost.com) - 事务和群发邮件 API，每月免费 3,000 封，之后最低每 1,000 封 0.08 美元。
  * [Atomic Mail](https://atomicmail.ai) - 为 AI agents 设计的邮箱服务，完全免费。支持程序化创建 inbox、自定义域名，以及基于开放 JMAP 标准（RFC 8620/8621）的完整收发；提供托管 MCP server。它是真实邮箱服务，并非一次性或临时邮箱。
  * [Brevo](https://www.brevo.com/) - 每月免费 9,000 封，每天 300 封。
  * [Bump](https://bump.email/) - 免费 10 个 Bump 邮箱地址和 1 个自定义域名。
  * [Burnermail](https://burnermail.io/) - 免费 5 个 Burner 邮箱地址、1 个收件箱和 7 天收件箱历史。
  * [Buttondown](https://buttondown.email/) - Newsletter 服务，最多 100 名订阅者免费。
  * [Canny Pigeons](https://cannypigeons.com/) - DMARC 监控平台，支持 DNS 漂移告警、IP 威胁情报和无限用户。首个域名免费，无需信用卡。
  * [Conduit](https://conduit.email/) - 将入站邮件转换为 Webhook，以便通过邮件触发 API，服务完全免费。
  * [Contact.do](https://contact.do/) - 将联系表单做成链接，类似联系表单版 Bitly。
  * [debugmail.io](https://debugmail.io/) - 面向开发者的易用测试邮件服务器。
  * [dkimvalidator.com](https://dkimvalidator.com/) - 测试邮件 DNS/SPF/DKIM/DMARC 配置是否正确，由 roundsphere.com 免费提供。
  * [DNSExit](https://dnsexit.com/) - 可在自定义域名下免费创建最多 2 个邮箱地址，含 100MB 存储，支持 IMAP、POP3、SMTP 和 SPF/DKIM。
  * [EmailGuard](https://emailguard.lazrek.net/) - 通过简单 API 屏蔽一次性邮箱、捕获拼写错误并验证 MX 记录，每月 100 次免费请求。
  * [EmailJS](https://www.emailjs.com/) - 并非完整邮件服务器，而是可在不暴露凭据的情况下从客户端直接发信的邮件客户端。免费套餐每月 200 次请求、2 个邮件模板、单请求最大 50KB，并提供有限联系人历史。
  * [EmailLabs.io](https://emaillabs.io/en) - 每月免费发送最多 9,000 封，每天最多 300 封。
  * [EmailQo Email Infrastructure Grader](https://emailqo.com/email-grader) - 免费邮件基础设施评分工具，检查 SPF、DKIM、DMARC 和邮件服务器配置，并为任意域名给出 100 分制评分，无需注册。
  * [EmailOctopus](https://emailoctopus.com) - 免费支持最多 2,500 名订阅者和每月 10,000 封邮件。
  * [Emailvalidation.io](https://emailvalidation.io) - 每月 100 次免费邮箱验证。
  * [Emitlo](https://emitlo.com) - 每月免费 12,000 封，支持邮件 API、SMTP 及 SPF/DKIM/DMARC，无需信用卡。
  * [EtherealMail](https://ethereal.email) - 虚假 SMTP 服务，主要面向 Nodemailer 和 EmailEngine 用户但不限于此。完全免费的反事务邮件服务，消息不会真正投递。
  * [forwardemail.net](https://forwardemail.net) - 自定义域名免费邮件转发，可创建并转发无限邮箱地址（**注意**：由于垃圾邮件问题，使用 .casa、.cf、.click、.email、.fit、.ga、.gdn、.gq、.lat、.loan、.london、.men、.ml、.pl、.rest、.ru、.tk、.top、.work TLD 时需要付费）。
  * [Imitate Email](https://imitate.email) - 用于开发、QA 和 CI/CD 测试邮件功能的沙箱邮件服务器，免费账号每天 15 封，永久有效。
  * [ImprovMX](https://improvmx.com) - 免费邮件转发。
  * [Inboxes App](https://inboxesapp.com) - 每天最多创建 3 个临时邮箱，使用后可在 Chrome 扩展中删除，非常适合测试注册流程。
  * [inboxkitten.com](https://inboxkitten.com/) - 免费临时/一次性邮箱，邮件最多 3 天自动删除，开源且可自托管。
  * [KaiMail](https://kaimail.net) - 为自定义域名提供带 ARC/DKIM 签名的邮件转发。免费方案含 1 个域名、1 个邮箱、每月 300 封邮件和最大 1MB 邮件大小；也提供邮件接收 Webhook，并为开源项目提供特殊方案。
  * [mail-tester.com](https://www.mail-tester.com) - 测试邮件 DNS/SPF/DKIM/DMARC 配置是否正确，每月免费 20 次。
  * [Maileroo](https://maileroo.com) - 面向开发者的 SMTP Relay 和邮件 API，每月 5,000 封、无限域名，并提供免费邮件验证、黑名单监控和邮件测试等。
  * [mailcatcher.me](https://mailcatcher.me/) - 捕获邮件并通过 Web 界面展示。
  * [mailchannels.com](https://www.mailchannels.com) - 提供 REST API 和 SMTP 集成的邮件 API，每月最多 3,000 封免费。
  * [Mailcheck.ai](https://www.mailcheck.ai/) - 防止用户使用临时邮箱注册，每小时 120 次请求（约每月 86,400 次）。
  * [Maildroppa](https://maildroppa.com) - 最多 100 名订阅者，邮件和自动化数量不限且免费。
  * [MailerLite.com](https://www.mailerlite.com) - 免费支持 1,000 名订阅者、每月 12,000 封邮件。
  * [MailerSend.com](https://www.mailersend.com) - 事务邮件 API 与 SMTP，每月 500 封免费，每天 100 次 API 请求。
  * [mailinator.com](https://www.mailinator.com/) - 免费公开邮件系统，可使用任意收件箱。
  * [Mailjet](https://www.mailjet.com/) - 每月免费 6,000 封，每天最多发送 200 封。
  * [mailsac.com](https://mailsac.com) - 用于临时邮件测试的免费 API、公开邮箱托管、出站邮件捕获，以及邮件转 Slack/WebSocket/Webhook，每月 API 上限 1,500 次。
  * [Mailtrap.io](https://mailtrap.io/) - 邮件 API 和 SMTP 每月免费 4,000 封，每天最多 150 封。Email Marketing 含 500 个联系人和每月 1,500 封；Email Sandbox 含每月 50 封测试邮件、1 个 Sandbox 和最多保存 10 封邮件。
  * [Mutant Mail](https://www.mutantmail.com/) - 免费 10 个邮箱 ID、1 个域名、1 个邮箱，所有邮箱 ID 共用一个收件箱。
  * [OneSignal](https://onesignal.com/) - 每月 10,000 封邮件，无需信用卡。
  * [Orbisearch](https://orbisearch.com) - 免费批量邮件验证器，每天 100 次验证，无需注册。
  * [Parsio.io](https://parsio.io) - 免费邮件解析器，可转发邮件、提取数据并发送到你的服务器。
  * [Plunk](https://useplunk.com) - 每月 3,000 封邮件免费。
  * [Postmark](https://postmarkapp.com/) - 每月 100 封邮件免费，DMARC 每周摘要不限。
  * [Proton Mail](https://proton.me/mail) - 内置端到端加密的免费安全邮件账号服务，免费 1GB 存储。
  * [Reloop](https://reloop.sh) - 面向开发者的事务邮件 API 和 SMTP。免费计划每月 3000 封、每天 200 封，包含 1 个自定义域名和 1 个 agent inbox。
  * [Resend](https://resend.com) - 面向开发者的事务邮件 API，每月 3,000 封、每天 100 封免费，含 1 个自定义域名。
  * [SendBridge Mail Tester](https://sendbridge.com/mail-tester) — 无需注册的免费邮件送达率测试。生成唯一收件箱地址后，分析 SPF、DKIM、DMARC、Rspamd 垃圾分、23 个以上 RBL 黑名单、反向 DNS 和内容质量。测试次数不限，几秒出结果，并提供可分享报告页。
  * [Sender](https://www.sender.net) - 每月最多 15,000 封邮件、2,500 名订阅者。
  * [Sendpulse](https://sendpulse.com) - 每月 500 名订阅者和 15,000 封邮件免费。
  * [SendStreak](https://www.sendstreak.com/) - 邮件框架即服务，可在自有 SMTP（如 AWS、Maileroo、Gmail）上增加模板、自动化、历史等。每天最多 100 封免费，无时间限制。
  * [SimpleLogin](https://simplelogin.io/) - 开源可自托管的邮件别名/转发方案，免费 10 个别名、无限带宽和无限回复/发送；教育人员（学生、研究者等）免费。
  * [Substack](https://substack.com) - 无限免费的 Newsletter 服务，开始收费后才需要向平台付费。
  * [Suped](https://www.suped.com/) - 易用的 DMARC 监控平台，免费方案支持 1 个域名和每月最多 1,000 封邮件。
  * [Sweego](https://www.sweego.io/) - 面向开发者的欧洲事务邮件 API，每天 100 封免费。
  * [temp-mail.io](https://temp-mail.io) - 免费一次性临时邮件服务，可同时使用多个邮箱并支持转发。
  * [Temp-Mail.org](https://temp-mail.org/en/) - 使用多种域名生成临时/一次性邮箱，每次刷新页面都会更换邮箱地址，完全免费且无付费服务。
  * [TempMailDetector.com](https://tempmaildetector.com/) - 每月免费验证最多 200 个邮箱，判断是否为临时邮箱。
  * [trashmail.com](https://www.trashmail.com) - 免费一次性邮箱地址，支持转发和地址自动过期。
  * [Tuta](https://tuta.com/) - 内置端到端加密、无广告和无跟踪的免费安全邮件服务，免费 1GB 存储和 1 个日历（另有[paid plan](https://tuta.com/pricing)）。Tuta 部分[open source](https://github.com/tutao/tutanota)，可自行托管。
  * [Verifalia](https://verifalia.com/email-verification-api) - 实时邮件验证 API，支持邮箱确认和一次性邮箱检测，每天 25 次免费验证。
  * [verimail.io](https://verimail.io/) - 批量与 API 邮件验证服务，每月 100 次免费验证。
  * [Waitlio](https://waitlio.com/) - 产品发布候补名单管理软件，可创建品牌化候补页面、收集和验证订阅邮箱，并通过标签与分析管理注册。免费方案含每月 100 名订阅者、1 个候补名单和 API 访问。
  * [Wraps](https://wraps.dev) - 邮件自动化工作流，免费含 5,000 个跟踪事件和无限联系人。
  * [ZeroSMTP](https://github.com/msgwing/ZeroSMTP) - 基于 msgwing.com 域名的免费 SMTP relay，每天最多 200 封，无付费层。只能从共享的 @msgwing.com 地址发送（不支持自定义域名）。提供 15 种语言的可运行代码示例，以及 Windows Server、Linux 和网络打印机配置指南。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="feature-toggles-management-platforms"></a>
## 功能开关管理平台

<details>
<summary>展开 / 收起服务列表</summary>

  * [Abby](https://www.tryabby.com) - 开源功能开关与 A/B 测试，配置即代码并提供完整类型的 TypeScript SDK，与 Next.js、React 等框架深度集成，免费套餐慷慨且扩展价格低。
  * [ConfigCat](https://configcat.com) - 以开发者为中心的功能开关服务，团队规模不限、支持出色且价格合理。免费方案最多 10 个 Flag、2 个环境、1 个产品和每月 500 万次请求。
  * [Flagsmith](https://flagsmith.com) - 安全发布功能，在 Web、移动和服务端应用中管理功能开关；可使用托管 API、部署到私有云或本地运行。
  * [GrowthBook](https://growthbook.io) - 开源功能开关与 A/B 测试平台，内置贝叶斯统计分析引擎。最多 3 名用户免费，功能开关和实验不限。
  * [Rollgate](https://rollgate.io) - 托管于欧盟的功能开关管理，支持计划发布、即时回滚和 A/B 测试，并包含 12 个 SDK。免费方案每月最多 500,000 次 API 请求、无限 Flag、3 名团队成员，无需信用卡。
  * [Hypertune](https://www.hypertune.com) - 类型安全的功能开关、A/B 测试、分析和应用配置，支持 Git 式版本控制及同步、内存、本地 Flag 评估。最多 5 名团队成员免费，功能开关和 A/B 测试不限。
  * [Statsig](https://www.statsig.com) - 强大的功能管理、A/B 测试和分析平台。免费方案席位、Flag、实验和动态配置不限，每月最多 100 万个事件。
  * [Toggled.dev](https://www.toggled.dev) - 企业级可扩展多区域功能开关管理平台。免费方案最多 10 个 Flag、2 个环境，请求不限；SDK、分析仪表板、发布日历、Slack 通知等所有功能均包含在永久免费方案中。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="font"></a>
## 字体

<details>
<summary>展开 / 收起服务列表</summary>

  * [Befonts](https://befonts.com/) - 提供多种可用于个人或商业用途的独特字体。
  * [Bunny](https://fonts.bunny.net) - 注重隐私的 Google Fonts 替代服务。
  * [dafont](https://www.dafont.com/) - 网站字体归各自作者所有，可能是免费软件、共享软件、演示版或公共领域字体。
  * [Everything Fonts](https://everythingfonts.com/) - 提供多种工具，包括 @font-face、单位转换器、字体 Hint 和字体提交。
  * [Font of web](https://fontofweb.com/) - 识别网站使用的所有字体及其使用方式。
  * [Font Squirrel](https://www.fontsquirrel.com/) - 获得商业使用许可的免费字体，经过人工筛选并以易用格式展示。
  * [FontGet](https://www.fontget.com/) - 提供多种可下载字体，并通过标签整齐分类。
  * [fonts.xz.style](https://fonts.xz.style/) - 使用 CSS 向网站交付字体家族的免费开源服务。
  * [Fontsensei](https://fontsensei.com/) - 用户标注的开源 Google Fonts，包含 CJK（中文、日文、韩文）字体标签。
  * [Fontshare](https://www.fontshare.com/) - 免费字体服务，持续扩充专业级字体，个人和商业用途均 100% 免费。
  * [Google Fonts](https://fonts.google.com/) - 提供大量免费字体，可通过下载或 Google CDN 链接轻松快速安装到网站。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="forms"></a>
## 表单

<details>
<summary>展开 / 收起服务列表</summary>

  * [FabForm](https://fabform.io/) - 面向开发者的表单后端平台，免费方案每月 250 次表单提交，提供友好的现代 GUI，并可集成 Google Sheets、Airtable、Slack、邮件等。
  * [Feathery](https://feathery.io) - 强大且开发者友好的表单构建器，可创建注册登录、用户引导、支付流程、复杂金融应用等。免费方案每月最多 250 次提交和 5 个活跃表单。
  * [feedback.fish](https://feedback.fish/) - 免费方案总共可收集 25 条反馈，并提供易于集成的 React 和 Vue 组件。
  * [FluidForms](https://fluidforms.ai/) - 带 AI 逻辑的表单构建器与后端。免费方案每月 100 条响应、无限表单（含 AI 创建）、Webhook 和嵌入功能。
  * [Form.taxi](https://form.taxi/) - HTML 表单提交端点，提供通知、垃圾拦截和符合 GDPR 的数据处理，基础用途免费。
  * [Formcarry.com](https://formcarry.com) - HTTP POST 表单端点，免费方案每月 100 次提交。
  * [Formester.com](https://formester.com) - 在网站上分享和嵌入外观独特的表单，创建数量和功能不受套餐限制，每月免费 100 次提交。
  * [Forminit](https://forminit.com/) - 面向开发者的无头表单后端，免费方案每月 100 次提交，包含文件上传、服务端字段验证、邮件通知、垃圾防护和 Zapier。
  * [FormKeep.com](https://www.formkeep.com/) - 无限表单、每月 50 次提交、垃圾防护、邮件通知和可导出 HTML 的拖放设计器。还包含自定义字段规则、团队，以及 Google Sheets、Slack、ActiveCampaign 和 Zapier 集成。
  * [Form Plume](https://formplume.com) - 面向 HTML 和 JavaScript 表单的后端，只需一个端点即可获得垃圾过滤、邮件通知、文件上传、Webhook 和整洁收件箱，每月 500 次提交免费。
  * [formlets.com](https://formlets.com/) - 在线表单，每月单页表单数量不限、100 次提交，并提供邮件通知。
  * [forms.app](https://forms.app/) - 创建带条件逻辑、自动评分和 AI 等强大功能的在线表单。免费方案最多收集 100 条响应，可嵌入网站或通过链接使用。
  * [formspark.io](https://formspark.io/) - 表单转邮件服务，免费方案含无限表单、每月 250 次提交和客户支持团队服务。
  * [Formspree.io](https://formspree.io/) - 通过 HTTP POST 请求发送邮件，免费套餐每个表单每月最多 50 次提交。
  * [Formsubmit.co](https://formsubmit.co/) - 简单的 HTML 表单端点，永久免费，无需注册。
  * [Formware.io](https://formware.io/) - 无需编码即可在数秒内创建响应式、美观表单，并免费收集无限响应。
  * [HeroTofu.com](https://herotofu.com/) - 带机器人检测和加密归档的表单后端，可通过 UI 将提交转发至邮件、Slack 或 Zapier，并使用自有前端，无需服务端代码。免费方案含无限表单和每月 100 次提交。
  * [HeyForm.net](https://heyform.net/) - 拖放式在线表单构建器，免费套餐可创建无限表单并收集无限提交，含预置模板、反垃圾和 100MB 文件存储。
  * [Jotform.com](https://jotform.com/) - 免费创建在线表单、收集提交、接受付款、自动化工作流并通过内置电子签名签署文档。免费方案含 5 个表单、每月 100 次提交、10 份电子签名文档、10 笔支付提交等。
  * [Kwes.io](https://kwes.io/) - 功能丰富的表单端点，非常适合静态站点。免费方案最多支持 1 个网站和每月 50 次提交。
  * [Pageclip](https://pageclip.co/) - 免费方案支持 1 个站点、1 个表单和每月 1,000 次提交。
  * [SimplePDF.eu](https://simplepdf.eu/embed) - 在网站嵌入 PDF 编辑器，将任意 PDF 转为可填写表单。免费方案 PDF 数量不限，每个 PDF 可提交 3 次。
  * [smartforms.dev](https://smartforms.dev/) - 强大易用的网站表单后端，永久免费方案每月 50 次提交、250MB 文件存储、Zapier 集成、CSV/JSON 导出、自定义跳转、自定义响应页、Telegram/Slack Bot 和单封邮件通知。
  * [staticforms.xyz](https://www.staticforms.xyz/) - 无需任何服务端代码即可免费集成 HTML 表单；用户提交后，表单内容会通过邮件发送至注册地址。
  * [Survicate](https://survicate.com/) - 使用一个工具从所有来源收集反馈并发送后续调查，通过 AI 自动分析并提取洞察。免费提供邮件、网站、产品内或移动调查、AI 调查创建器和每月 25 条响应。
  * [Tally.so](https://tally.so/) - 99% 功能免费，包括无限表单、无限提交、邮件通知、表单逻辑、收款、文件上传、自定义感谢页等。
  * [Typeform.com](https://www.typeform.com/) - 在网站嵌入设计精美的表单，免费方案每个表单仅 10 个字段和每月 100 条响应。
  * [Vidhook](https://vidhook.io/) - 通过高响应率的精美调查收集反馈。免费方案含 1 个活跃调查、每个调查 25 条响应和可自定义模板。
  * [WaiverStevie.com](https://waiverstevie.com) - 带 REST API 的电子签名平台，可通过 Webhook 接收通知。免费方案会在签署文档上加水印，但信封和签名数量不限。
  * [Web3Forms](https://web3forms.com) - 无需编写后端代码即可为静态和 JAMStack 网站提供联系表单，免费方案含无限表单、无限域名和每月 250 次提交。
  * [Wufoo](https://www.wufoo.com/) - 快速创建网站表单，免费方案每月最多 100 次提交。
  * [FormNX](https://FormNX.com/) - 免费创建无限表单并获得无限提交，可使用 1,000 多个专业模板或从零创建，并支持邮件通知、表单逻辑、收款、文件上传、自定义感谢页等。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="generative-ai"></a>
## 生成式 AI

<details>
<summary>展开 / 收起服务列表</summary>

  * [Arize AX](https://arize.com) - AI 工程平台，帮助 AI 工程师和产品经理评估、观测 AI 应用与 Agent，并内置 Alyx Agent。免费产品每月含 25,000 个 Span 和 1GB 写入量。
  * [Audio Enhancer](https://voice-clone.org/tools/audio-enhancer) - AI 音频增强 SaaS，可去除噪声和回声并保留自然人声清晰度。完全免费：一键增强不限次数，无需登录，支持 MP3/WAV/FLAC。
  * [Braintrust](https://www.braintrustdata.com/) - 面向生成式 AI 的评估、Prompt Playground 和数据管理，免费方案每周最多 1,000 行私有评估数据。
  * [Clair](https://askclair.ai/) - 临床 AI 参考工具，学生可免费使用专业工具套件，包括 Open Search、Clinical Summary、Med Review、Drug Interactions、ICD-10 Codes 和 Stewardship，另提供专业套件免费试用。
  * [Comet Opik](https://www.comet.com/site/products/opik/) - 在开发与生产生命周期中评估、测试和发布 LLM 应用。[#opensource](https://github.com/comet-ml/opik/)
  * [Future AGI](https://futureagi.com) - 用于评估、观测和改进 LLM 与 AI Agent 应用的开源平台，提供 Trace、评估、模拟和 Guardrail。免费套餐含 50GB 存储、2,000 个评估积分、每月 100,000 次 AI Gateway 请求、100 万 Token 文本 Agent 模拟和 60 分钟语音模拟，并提供无限项目/席位；使用 BYOK LLM-as-judge 时平台费用为 0。[#opensource](https://github.com/future-agi/future-agi)
  * [Gonka Broker](https://gonkabroker.com/) - 基于去中心化 Gonka.ai GPU 网络提供开源模型的 OpenAI-compatible API。每月提供 100 万+ 免费 tokens，可轻松集成多种 AI 工具。
  * [Keywords AI](https://keywordsai.co) - LLM 监控平台，只需两行代码即可用统一格式调用 200 多个 LLM。每月 10,000 次免费请求，平台功能免费。
  * [Langfuse](https://langfuse.com/) - 开源 LLM 工程平台，帮助团队协作调试、分析和迭代 LLM 应用。永久免费方案每月 50,000 次 Observation，并包含所有平台功能。[#opensource](https://github.com/langfuse/langfuse)
  * [LangWatch](https://langwatch.ai) - LLMOps 平台，帮助 AI 团队衡量、监控和优化 LLM 应用的可靠性、成本效率和性能。通过 DSPy 组件促进工程师与非技术团队协作，微调并生产化生成式 AI 产品。免费方案含所有平台功能、每月 1,000 条 Trace 和 1 个工作流 DSPy Optimizer。[#opensource](https://github.com/langwatch/langwatch)
  * [Latitude](https://latitude.so) - 开源（MIT）LLM 可观测性与评估平台，可追踪、监控并评估生产环境中的 AI Agent。免费 Starter 方案每月 20,000 积分、30 天数据保留和无限席位。[#opensource](https://github.com/latitude-dev/latitude-llm)
  * [Lumenfall.ai](https://lumenfall.ai/) - AI 媒体网关，通过兼容 OpenAI 的 API 统一访问主流图片生成模型。平台本身免费使用，无加价、无订阅费；大多数模型推理按供应商原价计费，但注册用户可永久免费无限使用 FLUX.1 [schnell] FP8，并内置故障转移和供应商韧性。
  * [Maxim](https://www.getmaxim.ai) - LLM 评估与可观测性平台，提供 Agent 模拟和 Prompt Playground。免费套餐每月 10,000 条日志，并可通过 BYOK 使用 Playground、模拟和评估。
  * [Mediaworkbench.ai](https://mediaworkbench.ai) - 为 Azure OpenAI、DeepSeek 和 Google Gemini 模型提供 100,000 个免费单词，可使用代码生成、深度研究和图片创作等工具。
  * [OpenRouter](https://openrouter.ai/models?q=free) - 提供 DeepSeek R1、V3、Llama、Moonshot AI 等多种免费 AI 模型，适合自然语言处理和多种开发需求。免费模型受速率限制；另提供 Claude、OpenAI、Grok、Gemini、Nova 等付费模型。
  * [Pollinations.AI](https://pollinations.ai/) - 易用的免费图片生成 AI，并提供免费 API，无需注册或 API Key，可通过多种方式集成到网站或工作流。[#opensource](https://github.com/pollinations/pollinations)
  * [Portkey](https://portkey.ai/) - 生成式 AI 应用控制台，包含可观测性套件和 AI Gateway，每月可免费发送并记录 10,000 次请求。
  * [ReportGPT](https://ReportGPT.app) - AI 写作助手，只要自带 API Key，整个平台均可免费使用。
  * [telemetry.dev](https://telemetry.dev) - 基于 OpenTelemetry 的 AI/LLM 应用可观测性服务。跟踪模型调用和工具步骤的 tokens、成本、延迟和错误；可从任意语言通过 HTTP 发送 OTLP，或使用 TypeScript SDKs。免费计划每月 10000 spans、保留 7 天、1 个项目和 2 个席位，无需信用卡。
  * [Transcript LOL](https://transcript.lol/) - 使用 AI 将音频或视频转为文本，并通过 LLM 生成摘要和其他洞察。免费套餐每天 2 次转录，可上传文件、录制语音或使用 YouTube、Instagram 等链接；免费版还支持 WhatsApp、Telegram，以及直接从 Google Drive、Dropbox、Box 和 OneDrive 导入文件。无需 API Key，注册即可使用，并提供移动端、桌面端和 Chromebook 应用。
  * [Zenable](https://zenable.io) - 使用基于 Policy as Code 的 Guardrail，自动修复 Cursor、Windsurf 和 Copilot 等工具输出，使其符合公司质量与合规标准。免费套餐每天可调用 MCP 服务器 100 次，并可通过 GitHub App 每天执行 25 次自动 Pull Request 审查。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="cdn-and-protection"></a>
## CDN 与防护

<details>
<summary>展开 / 收起服务列表</summary>

  * [bootstrapcdn.com](https://www.bootstrapcdn.com/) - 面向 Bootstrap、Bootswatch 和 fontawesome.io 的 CDN。
  * [CacheFly](https://portal.cachefly.com/signup/free2023) - 每月最多 5TB 免费 CDN 流量、19 个核心 PoP、1 个域名和通用 SSL。
  * [cdnjs.com](https://cdnjs.com/) - 简单、快速、可靠的内容分发服务。cdnjs 是由 Cloudflare 驱动的免费开源 CDN，受到超过 11% 网站的信任。
  * [developers.google.com](https://developers.google.com/speed/libraries/) - Google Hosted Libraries 是面向热门开源 JavaScript 库的内容分发网络。
  * [Gcore](https://gcorelabs.com/) - 全球内容分发网络，每月免费 1TB 和 100 万次请求，并提供免费 DNS 托管。
  * [jsdelivr.com](https://www.jsdelivr.com/) - 免费、快速、可靠的开源 CDN，支持 npm、GitHub、WordPress、Deno 等。
  * [Microsoft Ajax](https://docs.microsoft.com/en-us/aspnet/ajax/cdn/overview) - Microsoft Ajax CDN 托管 jQuery 等常用第三方 JavaScript 库，便于将其加入 Web 应用。
  * [Namecheap Supersonic](https://www.namecheap.com/supersonic-cdn/#free-plan) - 免费 DDoS 防护。
  * [ovh.ie](https://www.ovh.ie/ssl-gateway/) - 免费 DDoS 防护和 SSL 证书。
  * [PromoProxy](https://promoproxy.net/) - 免费云端安全 Web Gateway，免费方案最多 5 名用户和每天 1GB。
  * [raw.githack.com](https://raw.githack.com/) - **rawgit.com** 的现代替代品，使用 Cloudflare 托管文件。
  * [Skypack](https://www.skypack.dev/) - 100% 原生 ES Module JavaScript CDN，每个域名每月 100 万次请求免费。
  * [statically.io](https://statically.io/) - 面向 Git 仓库（GitHub、GitLab、Bitbucket）、WordPress 资源和图片的 CDN。
  * [Stellate](https://stellate.co/) - 快速可靠的 GraphQL API CDN，2 个服务免费。
  * [toranproxy.com](https://toranproxy.com/) - Packagist 和 GitHub 代理，避免 CD 失败。个人使用免费，限 1 名开发者且不含支持。
  * [UNPKG](https://unpkg.com/) - npm 上所有内容的 CDN。
  * [weserv](https://images.weserv.nl/) - 图片缓存和缩放服务，可借助全球缓存实时处理图片。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="paas"></a>
## PaaS（平台即服务）

<details>
<summary>展开 / 收起服务列表</summary>

  * [ampt.dev](https://getampt.com/) - 让团队无需复杂配置或基础设施管理即可在 AWS 上构建、部署和扩展 JavaScript 应用。免费 Preview 方案每小时 500 次、每天 2,500 次、每月 50,000 次调用；自定义域名仅付费方案可用。
  * [anvil.works](https://anvil.works) - 只用 Python 开发 Web 应用，免费套餐应用数量不限，超时 30 秒。
  * [Apply.build](https://apply.build/) - 免费构建和部署 GitHub 应用，提供 0.5 vCPU/512MiB RAM、欧洲服务器、自动防火墙和实时性能指标。支持 Node.js、Python、Go、Java、静态站点、微服务等。
  * [appwrite](https://appwrite.io) - 项目数量不限且不会暂停（支持 WebSocket），并提供身份认证服务。免费套餐每项目含 1 个数据库、3 个 Bucket 和 5 个 Function。
  * [Clever Cloud](https://clever.cloud) - 欧洲 PaaS，提供自动部署、自动扩缩容、托管数据库和 Git 工作流。注册含 20 欧元免费额度，有限 DEV 方案提供免费 MySQL/PostgreSQL 数据库，并为 Heptapod 和 FS Bucket 等服务提供免费额度。
  * [Choreo](https://wso2.com/choreo/) - AI 原生内部开发者平台即服务，免费套餐最多 5 个组件和每月 100 美元额度。
  * [codenameone.com](https://www.codenameone.com/) - 面向 Java/Kotlin 开发者的开源跨平台移动应用开发工具链，商业用途免费，项目数量不限。
  * [Cohesivity](https://cohesivity.ai) - 为 AI agents 专门构建的 headless backend 和服务，包含托管、数据库、存储、LLMs 与第三方 APIs，并支持 agentic signup。免费层包含 10 个项目、100K edge requests、10GB 对象存储、100 封邮件，以及每月 $5 的 AI 和 search credits。
  * [Daestro](https://daestro.com) - 在云服务商与本地环境中运行计算作业。免费套餐最多 10 个并发作业运行、2 个计算 Spawn、自托管计算、1 个云服务商、1 个容器注册表和 1 个 Cron Job。
  * [Deno Deploy](https://deno.com/deploy) - 在全球边缘运行 JavaScript、TypeScript 和 WebAssembly 的分布式系统，免费套餐每天 100,000 次请求和每月 100GiB 数据传输。
  * [domcloud.co](https://domcloud.co) - Linux 托管服务，提供 GitHub CI/CD、SSH 和 MariaDB/Postgres。免费版含 1GB 存储、每月 1GB 网络流量，并仅可使用免费域名。
  * [encore.dev](https://encore.dev/) - 使用静态分析自动提供基础设施、免样板代码等能力的后端框架，并为业余项目提供免费云托管。
  * [flightcontrol.dev](https://flightcontrol.dev/) - 通过类似 Git Push 的工作流在自己的 AWS 账号中部署 Web 服务、数据库等。个人 GitHub 仓库且仅 1 名开发者时免费；AWS 成本由 AWS 收取，可使用额度和 AWS 免费套餐。
  * [gigalixir.com](https://gigalixir.com/) - 为 Elixir/Phoenix 应用提供 1 个永不休眠的免费实例和免费 PostgreSQL 数据库，限 2 个连接、10,000 行且无备份。
  * [Northflank](https://northflank.com) - 通过强大的 UI、API 和 CLI 构建部署微服务、作业和托管数据库，并可从版本控制和外部 Docker 注册表无缝扩展容器。免费套餐含 2 个服务、2 个 Cron Job 和 1 个数据库。
  * [Ownkube](https://ownkube.io) - 在自己的 AWS 账号中免费运行单节点 k3s，通过 Git Push 运行应用、数据库和 Worker，并高效利用 AWS 额度。
  * [pipedream.com](https://pipedream.com) - 面向开发者的集成平台，可基于任意触发器开发工作流。工作流以代码形式运行并可[for free](https://docs.pipedream.com/pricing/)，无需管理服务器或云资源。
  * [pythonanywhere.com](https://www.pythonanywhere.com/) - 云端 Python 应用托管。初学者账号免费，含 1 个位于 your-username.pythonanywhere.com 的 Python Web 应用、512MB 私有文件存储和 1 个 MySQL 数据库。
  * [Runsite](https://runsite.app/) - 欧洲 PaaS，可从 GitHub 自动部署 Web services 或静态站点（免费 1 个 Web 实例，0.1 vCPU/256MB），托管 PostgreSQL 和 Valkey(Redis) 可免费使用 30 天，事务邮件每月 3000 封免费，S3-compatible storage 5GB 免费。服务器位于德国。
  * [Val Town](https://www.val.town) - 用于脚本、HTTP 端点和 Cron Job 的协作式 TypeScript/JavaScript 无服务器平台。免费方案含无限公开 Val、15 分钟 Cron 间隔、每次运行 1 分钟墙钟时间和 3 天日志保留；免费版不支持自定义域名。
  * [WunderGraph](https://cloud.wundergraph.com) - 可快速构建、发布和管理现代 API 的开源平台，内置 CI/CD、GitHub 集成和自动 HTTPS。[free plan](https://wundergraph.com/pricing)最多 3 个项目、每月 1GB 出站和 300 分钟构建时间。
  * [YepCode](https://yepcode.io) - 在无服务器环境连接 API 和服务的一体化平台，兼具无代码工具的敏捷性和编程语言的能力。免费套餐含 [1.000 yeps](https://yepcode.io/pricing/)。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="baas"></a>
## BaaS（后端即服务）

<details>
<summary>展开 / 收起服务列表</summary>

  * [Activepieces](https://www.activepieces.com) - 在应用后端构建自动化流程连接多个应用，例如应用事件触发时发送 Slack 消息或新增 Google Sheet 行。每月最多 5,000 个任务免费。
  * [back4app.com](https://www.back4app.com) - 基于 Parse Platform 的易用、灵活、可扩展后端。
  * [backendless.com](https://backendless.com/) - 移动和 Web BaaS，免费含 1GB 文件存储、每月 50,000 次推送通知和表中 1,000 个数据对象。
  * [connectycube.com](https://connectycube.com) - 无限聊天消息、点对点音视频通话、文件附件和推送通知，最多 1,000 名用户的应用免费。
  * [convex.dev](https://convex.dev/) - 响应式后端即服务，托管数据（含关系和可序列化 ACID 事务的文档）、无服务器函数及向多客户端流式更新的 WebSocket。小型项目免费，最多 100 万条记录和每月 500 万次函数调用。
  * [ETLR](https://etlr.io) - 使用 YAML 定义、版本化和部署自动化脚本，是拖放工具的开发者优先替代品，可用于计划任务、AI Agent 和基础设施监控。免费套餐每月 100 积分。
  * [Flutter Flow](https://flutterflow.io) - 无需编写代码即可构建 Flutter 应用 UI，并提供 Firebase 集成。免费方案可完整使用 UI Builder 和免费模板。
  * [getstream.io](https://getstream.io/) - 用几小时而非几周构建可扩展的应用内聊天、消息、视频、音频和 Feed。
  * [IFTTT](https://ifttt.com) - 自动化常用应用和设备，免费 2 个 Applet。
  * [Integrately](https://integrately.com) - 一键自动化繁琐任务，免费 100 个任务，最短 15 分钟间隔。
  * [LeanCloud](https://leancloud.app/) - 移动后端，免费含 1GB 数据存储、256MB 实例、每天 3,000 次 API 请求和 10,000 次推送（API 与 Parse Platform 很相似）。
  * [nhost.io](https://nhost.io) - 面向 Web 和移动应用的无服务器后端，免费方案含 PostgreSQL、GraphQL（Hasura）、身份认证、存储和无服务器函数。
  * [onesignal.com](https://onesignal.com/) - 无限免费推送通知，每月 10,000 封邮件，联系人不限，并可使用 Auto Warm Up。
  * [paraio.com](https://paraio.com) - 后端服务 API，提供灵活身份认证、全文搜索和缓存。1 个应用和 1GB 应用数据免费。
  * [pubnub.com](https://www.pubnub.com/) - 每月最多 100 万条消息和每天 100 台活跃设备的推送通知免费。
  * [pusher.com](https://pusher.com/beams) - 为 2,000 MAU 提供免费无限推送通知，单一 API 支持 iOS 和 Android。
  * [simperium.com](https://simperium.com/) - 即时自动在各平台间移动数据，结构化数据发送和存储不限，每月最多 2,500 名用户。
  * [snill.ai](https://snill.ai) - AI 无代码平台，可将自然语言描述转换为包含关系数据库、仪表板、工作流、REST API 和 Webhook 的完整业务系统。面向个人使用者的免费方案含 2 个应用、1,000 条记录和每天 10 次 AI 请求。
  * [Supabase](https://supabase.com) - 用于构建后端的开源 Firebase 替代品，免费方案提供身份认证、实时数据库和对象存储。
  * [tyk.io](https://tyk.io/) - 提供身份认证、配额、监控和分析的 API 管理，云端提供免费方案。
  * [zapier.com](https://zapier.com/) - 连接常用应用以自动化任务，每 15 分钟运行 5 个 Zap，每月 100 个任务；还包含更新时间、5 个活跃自动化和 Webhook。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="low-code-platform"></a>
## 低代码平台

<details>
<summary>展开 / 收起服务列表</summary>

  * [appsmith](https://www.appsmith.com/) - 用于构建管理面板、内部工具和仪表板的低代码项目，可集成 15 种以上数据库和任意 API。
  * [BudiBase](https://budibase.com/) - 可在数分钟内创建内部应用的开源低代码平台，支持 PostgreSQL、MySQL、MSSQL、MongoDB、REST API、Docker 和 K8s。
  * [Clappia](https://www.clappia.com) - 用于构建业务流程应用的低代码平台，提供可自定义移动和 Web 应用、拖放界面、离线支持、实时位置跟踪及多种第三方集成。
  * [lil'bots](https://www.lilbots.io/) - 在线编写和运行脚本，可使用 OpenAI、Anthropic、Firecrawl 等内置免费 API，适合构建 AI Agent、内部工具并与团队分享。免费套餐可完整访问 API、AI 编程助手和每月 10,000 个执行积分。
  * [manubes](https://www.manubes.com) - 专注工业生产管理的强大无代码云平台，1 名用户免费，每月支持 100 万次工作流活动（[also available in german](https://www.manubes.de)）。
  * [Mendix](https://www.mendix.com/) - 企业快速应用开发平台，可使用无限可访问 Sandbox 环境，每个应用支持全部用户、0.5GB 存储和 1GB RAM，免费套餐也允许使用 Studio 和 Studio Pro IDE。
  * [outsystems.com](https://www.outsystems.com/) - 面向本地或云端的企业 Web 开发 PaaS，免费“个人环境”支持无限代码和最多 1GB 数据库。
  * [ReTool](https://retool.com/) - 构建内部应用的低代码平台，可高度定制；凡是能用 JavaScript 和 API 编写的内容都能在 Retool 中实现。免费套餐每月最多 5 名用户，应用和 API 连接不限。
  * [ToolJet](https://www.tooljet.com/) - 可扩展的业务应用低代码框架，可连接数据库、云存储、GraphQL、API 端点、Airtable 等，并通过拖放构建应用。
  * [UI Bakery](https://uibakery.io) - 用于快速构建自定义 Web 应用的低代码平台，可拖放构建 UI，并通过 JavaScript、Python 和 SQL 深度定制。提供云端与自托管方案，最多 5 名用户免费。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="web-hosting"></a>
## Web 托管

<details>
<summary>展开 / 收起服务列表</summary>

  * [Alwaysdata](https://www.alwaysdata.com/) - 1GB 免费 Web 托管，支持 MySQL、PostgreSQL、RabbitMQ、.NET、Deno、Elixir、Go、Java、Lua、Node.js、PHP、Python、Ruby、Rust；支持自定义 Web 服务器以及 FTP、WebDAV 和 SSH 访问，并包含邮箱、邮件列表和应用安装器。免费方案不支持自定义域名。
  * [Awardspace.com](https://www.awardspace.com) - 免费 Web 托管和免费短域名，支持 PHP、MySQL、应用安装器和邮件发送，无广告。
  * [boomurl](https://boomurl.com) - 无需账号即可将静态站点（HTML/Markdown/图片/PDF 或整个文件夹）发布到即时 HTTPS URL，免费套餐显示小型横幅，并支持自定义域名。
  * [Bubble](https://bubble.io/) - 无代码构建 Web 和移动应用的可视化编程工具，免费版带 Bubble 品牌。
  * [dAppling Network](https://www.dappling.network/) - 面向 Web3 前端的去中心化 Web 托管平台，专注提高可用性与安全性，并为用户提供额外访问入口。
  * [DigitalOcean](https://www.digitalocean.com/pricing) - 在 App Platform Starter 套餐上免费构建和部署 3 个静态站点。
  * [FreeFlarum](https://freeflarum.com/) - 社区驱动的免费 Flarum 托管，最多 250 名用户（捐赠可移除页脚水印）。
  * [Harvis.dev](https://harvis.dev) - 通过 CLI（`npx harvis`）提供静态站点托管，无需配置文件或构建步骤。包含免费子域名、免费表单提交收集、GitHub Actions 集成、CloudFlare CDN 和免费 SSL。
  * [Kinsta Static Site Hosting](https://kinsta.com/static-site-hosting/) - 免费部署最多 100 个静态站点，支持带 SSL 的自定义域名、每月 100GB 带宽和 260 多个 Cloudflare CDN 节点。
  * [Koyeb](https://www.koyeb.com/) - Serverless 平台，免费 Hobby 计划提供每月 550 小时 compute（512MB RAM 免费层）、1 个免费 PostgreSQL 数据库和自定义域名 SSL。
  * [MDB GO](https://mdbgo.com/) - 1 个项目免费托管，容器 TTL 两周，每项目 500MB RAM，SFTP 磁盘空间 1GB。
  * [Mirin](https://mirin.com) - 面向开发者构建的 React、Vue 或 Svelte 组件网站平台，提供可视化编辑、表单、分析和全球 CDN 托管。免费套餐含 1 个站点，页面和提交不限。
  * [Neocities](https://neocities.org) - 静态托管，免费 1GB 存储和 200GB 带宽。
  * [Netlify](https://www.netlify.com/) - 免费构建、部署和托管静态站点/应用，每月 300 积分（相当于 30GB 带宽）。
  * [PandaStack](https://www.pandastack.io/) - 面向开发者的生态系统，提供静态托管、容器托管、WordPress 和其他可一键部署的托管应用。免费含 1 个 Web 托管（静态或容器）、1 个数据库、100GB 带宽和每月 300 构建分钟。
  * [pantheon.io](https://pantheon.io/) - Drupal 和 WordPress 托管、自动化 DevOps 和可扩展基础设施，开发者和代理机构免费，不支持自定义域名。
  * [Qoddi](https://qoddi.com) - 类似 Heroku、以开发者为中心且功能完整的 PaaS，静态资源、预发布和开发者应用可用免费套餐。
  * [readthedocs.org](https://readthedocs.org/) - 免费文档托管，支持版本控制、PDF 生成等。
  * [render.com](https://render.com) - 用于构建和运行应用与网站的统一云平台，提供免费 SSL、全球 CDN、私有网络、Git 自动部署，以及针对 Web 服务、数据库和静态网页的完全免费方案。
  * [Revdoku](https://revdoku.com/) — 直接从 ChatGPT、Claude、Codex 和其他 AI Agent 将文件、报告和自定义微站发布为公开或密码保护网站。免费套餐含 2GB 存储、2 个在线站点/应用、1 个数据库（25MB）、3 个 AI 连接、每 Bucket 1,000 个文件（每文件 100MB）和基础分析。
  * [ShipStatic](https://shipstatic.com) - AI agent 可自行驱动的静态托管：`npx @shipstatic/ship ./dist` 即可上线，无需安装、注册、仓库或构建。也提供 MCP、SDK 和 API。免费账户可永久保留站点，包含自动 HTTPS、全球 edge delivery 和不计量 bandwidth；自定义域名为付费功能。
  * [SourceForge](https://sourceforge.net/) - 免费查找、创建和发布开源软件。
  * [surge.sh](https://surge.sh/) - 面向前端开发者的静态 Web 发布，站点数量不限，并支持自定义域名。
  * [tilda.cc](https://tilda.cc/) - 1 个站点、50 个页面、50MB 存储，仅可使用 170 多个区块中的主要预定义区块，不支持字体、Favicon 和自定义域名。
  * [Vercel](https://vercel.com/) - 构建、部署和托管 Web 应用，提供免费 SSL、全球 CDN 和每次 `git push` 的唯一预览 URL，非常适合 Next.js 和其他静态站点生成器。
  * [Versoly](https://versoly.com/) - 面向 SaaS 的网站构建器，支持无限网站、70 多个区块、5 个模板、自定义 CSS、Favicon、SEO 和表单，不支持自定义域名。
  * [Stormkit](https://www.stormkit.io) - 可自托管的 Vercel alternative，用于构建、托管和部署现代前端及 JavaScript 应用。免费计划包含 1 个 app、50GB bandwidth、无限自定义域名和免费 SSL。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="dns"></a>
## DNS

<details>
<summary>展开 / 收起服务列表</summary>

  * [1.1.1.1](https://developers.cloudflare.com/1.1.1.1/) - Cloudflare 提供的免费公共 DNS Resolver，快速且安全（加密 DNS 查询）。可绕过网络服务商 DNS 封锁、防止 DNS 查询被监视，并可[to block adult & malware content](https://developers.cloudflare.com/1.1.1.1/1.1.1.1-for-families)，也可[via API](https://developers.cloudflare.com/1.1.1.1/encrypted-dns/dns-over-https/make-api-requests)。注意：它只是 DNS 解析器，不是 DNS 托管服务。
  * [1984.is](https://www.1984.is/product/freedns/) - 免费 DNS 服务，含 API 和多种其他免费 DNS 功能。
  * [cloudns.net](https://www.cloudns.net/) - 免费托管 1 个域名，最多 50 条 DNS 记录。
  * [deSEC](https://desec.io) - 注重安全、支持 API 的免费 DNS 托管，运行于开源软件并由 [SSE](https://www.securesystems.de/) 支持。
  * [dns.he.net](https://dns.he.net/) - 支持动态 DNS 的免费 DNS 托管服务。
  * [dnspod.com](https://www.dnspod.com/) - 免费 DNS 托管。
  * [duckdns.org](https://www.duckdns.org/) - 免费 DDNS，最多 5 个域名，并提供多种环境配置指南。
  * [Dynv6.com](https://dynv6.com/) - 免费 DDNS 服务，支持 [API support](https://dynv6.com/docs/apis)，可管理 CNAME、MX、SPF、SRV、TXT 等多种 DNS 记录。
  * [freedns.afraid.org](https://freedns.afraid.org/) - 免费 DNS 托管，并基于大量用户贡献的[contributed domains](https://freedns.afraid.org/domain/registry/)提供免费子域名。注册后可在“Subdomains”菜单领取。
  * [Glauca](https://docs.glauca.digital/hexdns/) - 最多 3 个域名的免费 DNS 托管，并支持 DNSSEC。
  * [Hetzner](https://www.hetzner.com/dns-console) - Hetzner 提供的免费 DNS 托管，支持 API。
  * [huaweicloud.com](https://www.huaweicloud.com/intl/en-us/product/dns.html) - 华为云提供的免费 DNS 托管。
  * [LocalCert](https://localcert.net) - 免费 `.localcert.net` 子域名，兼容公共 CA，可用于私有网络。
  * [luadns.com](https://www.luadns.com/) - 免费 DNS 托管，支持 3 个域名，所有功能均提供合理额度。
  * [namecheap.com](https://www.namecheap.com/domains/freedns/) - 免费 DNS，域名数量不限。
  * [nextdns.io](https://nextdns.io) - 基于 DNS 的防火墙，每月 300,000 次免费查询。
  * [noip.at](https://noip.at/) - 无需注册、跟踪、日志或广告的免费 DDNS，域名数量不限。
  * [noip](https://www.noip.com/) - 动态 DNS 服务，最多 3 个免费主机名，每 30 天需确认一次。
  * [sslip.io](https://sslip.io/) - 免费 DNS 服务，查询包含内嵌 IP 地址的主机名时会返回该 IP。
  * [zilore.com](https://zilore.com/en/dns) - 最多 5 个域名的免费 DNS 托管。
  * [zoneedit.com](https://www.zoneedit.com/free-dns/) - 支持动态 DNS 的免费 DNS 托管。
  * [Zonomi](https://zonomi.com/) - 支持即时 DNS 传播的免费 DNS 托管，免费方案含 1 个 DNS Zone（域名）和最多 10 条 DNS 记录。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="domain"></a>
## 域名

<details>
<summary>展开 / 收起服务列表</summary>

  * [DigitalPlat](https://domain.digitalplat.org) - 免费子域名。
  * [DNSHE](https://www.dnshe.com/) - 在多个域名后缀下免费注册子域名，并支持自定义 Nameserver。
  * [isroot.in](https://isroot.in) - 免费 isroot.in 子域名。
  * [pp.ua](https://nic.ua/) - 免费 pp.ua 子域名。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="iaas"></a>
## IaaS（基础设施即服务）

<details>
<summary>展开 / 收起服务列表</summary>

  * [4EVERLAND](https://www.4everland.org/) - 兼容 AWS S3 API、界面操作、CLI 等上传方式，可安全、便捷、高效地从 IPFS 和 Arweave 网络上传并存储文件。注册用户免费获得 6GB IPFS 存储和 300MB Arweave 存储；小于 150KB 的 Arweave 文件上传免费。
  * [backblaze.com](https://www.backblaze.com/b2/) - Backblaze B2 云存储，永久免费 10GB 类 Amazon S3 对象存储。
  * [filebase.com](https://filebase.com/) - 由区块链驱动、兼容 S3 的对象存储，永久提供 5GB 免费空间。
  * [Modal](https://modal.com) - AI 驱动的 IaaS，提供慷慨计算和存储额度；每月免费 30 美元额度（部分账号可能仅 5 美元）。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="managed-data-services"></a>
## 托管数据服务

<details>
<summary>展开 / 收起服务列表</summary>

  * [8base.com](https://www.8base.com/) - 面向 JavaScript 开发者、构建于 MySQL、GraphQL 和无服务器 BaaS 之上的全栈低代码开发平台，可通过 UI 应用构建器快速创建并扩展 Web 应用。免费套餐含 2,500 行、500MB 存储、1GB/小时无服务器计算和 5 名客户端应用用户。
  * [airtable.com](https://airtable.com/) - 外观类似电子表格但实为关系数据库，Base 数量不限，每个 Base 1,200 行，每月 1,000 次 API 请求。
  * [Aiven](https://aiven.io/) - 在开源数据平台上提供免费 PostgreSQL、MySQL 和 Valkey（兼容 Redis）方案：单节点、1 CPU、1GB RAM，PostgreSQL 和 MySQL 另含 1GB 存储，可轻松迁移到更大方案或跨云迁移。
  * [BackupDrill](https://backupdrill.com) - 将 Supabase 项目备份到你自己的 S3/R2/B2 Bucket，并定期执行恢复演练验证备份可用性。免费方案支持 1 个项目每周备份，并在首次备份时执行 1 次恢复演练。
  * [CockroachDB Cloud](https://www.cockroachlabs.com/pricing/) - 免费套餐每月提供 5,000 万 RU 和 10GiB 存储（相当于 15 美元）。([What's the Request Units](https://www.cockroachlabs.com/docs/cockroachcloud/metrics-request-units.html))
  * [codehooks.io](https://codehooks.io/) - 易用的 JavaScript 无服务器 API/后端和 NoSQL 数据库服务，支持函数、类似 MongoDB 的查询、键值查找、作业系统、实时消息、Worker Queue、强大 CLI 和 Web 数据管理器。免费方案含 5GB 存储、每分钟 60 次 API 调用、2 名开发者，无需信用卡。
  * [Couchbase Capella](https://www.couchbase.com/products/capella/) - 部署永久免费、完全托管的数据库集群，含 1 个节点和 8GB 存储，面向开发者构建从 IoT 到 AI 的下一代应用。
  * [CrateDB](https://crate.io/) - 用于实时分析的分布式开源 SQL 数据库。[Free Tier CRFREE](https://crate.io/lp-crfree) 提供 1 个节点、2 CPU、2GiB 内存和 8GiB 存储；每个组织 1 个集群，无需支付方式。
  * [filess.io](https://filess.io) - 可免费创建 2 个数据库，每个数据库最多 10MB，支持 MySQL、MariaDB、MongoDB 和 PostgreSQL。
  * [InfluxDB](https://www.influxdata.com/) - 时序数据库，每 5 分钟免费写入 3MB、读取 30MB，并支持 10,000 个序列基数。
  * [Layerbase](https://layerbase.com/) - 提供 2 个免费托管数据库，可选 Postgres、MariaDB、Redis、Valkey、DuckDB、SQLite、libSQL 和 TypeDB，全部支持 TLS。8 种免费引擎中有 7 种支持 branch，每个数据库 1 个 branch；免费层吞吐限制为 10GB/天、50GB/周、150GB/月。更高套餐另有 10 种引擎且不计量。
  * [MemCachier](https://www.memcachier.com/) - 托管 Memcache 服务，免费最多 25MB、1 个 Proxy Server 和基础分析。
  * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - 免费套餐提供 512MB。
  * [Neo4j Aura](https://neo4j.com/cloud/aura/) - 托管原生图数据库/分析平台，使用 Cypher 查询语言和 REST API，图规模上限为 200,000 个节点和 400,000 条关系。
  * [Neon](https://neon.tech/) - 托管 PostgreSQL，每项目 0.5GB 存储、100 个项目、每项目 10 个分支、无限数据库；主分支始终可用（5 分钟后自动挂起），非主分支计算每月总计 20 小时活跃时间。
  * [Nile](https://www.thenile.dev/) - 面向 B2B 应用的 Postgres 平台，数据库不限且始终在线不关停，含总计 1GB 存储、5,000 万查询 Token、自动扩缩容和无限向量嵌入。
  * [Prisma Postgres](https://prisma.io/postgres) - 基于 Unikernel、运行于裸金属的高速托管 Postgres，含总计 500MB 存储、5 个数据库，并集成 Prisma ORM。
  * [Qdrant](https://qdrant.tech/) - 用于嵌入数据的向量数据库，单节点集群配备 0.5 vCPU、1GB RAM 和 4GB 磁盘。
  * [restdb.io](https://restdb.io/) - 快速简洁的 NoSQL 云数据库，提供 Schema、关系、自动 REST API（类似 MongoDB 查询）和高效多用户管理 UI。免费方案允许 3 名用户、2,500 条记录和每秒 1 次 API 请求。
  * [SeaTable](https://seatable.io/) - Seafile 团队构建的灵活类电子表格数据库，表数量不限、2,000 行、1 个月版本记录，最多 25 名团队成员。
  * [skyvia.com](https://skyvia.com/) - 云数据平台提供免费套餐，Beta 期间所有方案完全免费。
  * [StackBy](https://stackby.com/) - 将电子表格灵活性、数据库能力和常用业务应用集成结合于一个工具。免费方案含无限用户、10 个 Stack，每个 Stack 2GB 附件。
  * [Tinybird](https://tinybird.co) - 无服务器托管 ClickHouse，可通过 HTTP 无连接写入数据，并将 SQL 查询发布为托管 HTTP API。免费套餐无时间限制，含 10GB 存储和每天 1,000 次 API 请求。
  * [Turso by ChiselStrike](https://turso.tech/) - 面向 SQLite 开发者体验的边缘数据库。永久免费 Starter 方案含总计 9GB 存储、最多 500 个数据库、3 个位置、每月 10 亿行读取，并支持 SQLite 本地开发。
  * [Upstash](https://upstash.com/) - 无服务器 Redis，免费套餐每月最多 500,000 条命令、数据库最大 256MB 和 20 个并发连接。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="tunneling-webrtc-web-socket-servers-and-other-routers"></a>
## 隧道、WebRTC、WebSocket 服务器与其他路由

<details>
<summary>展开 / 收起服务列表</summary>

  * [cname.dev](https://cname.dev/) - 免费且安全的动态反向代理服务。
  * [conveyor.cloud](https://conveyor.cloud/) - Visual Studio 扩展，可将 IIS Express 暴露到本地网络，或通过隧道暴露为公开 URL。
  * [Expose](https://expose.dev/) - 通过安全隧道公开本地站点，免费方案含欧洲服务器、随机子域名和单用户。
  * [Hamachi](https://www.vpn.net/) - 托管 VPN 服务，可将分布式团队安全扩展为类似局域网的网络；免费方案可创建无限网络，每个网络最多 5 人。
  * [Hookdeck](https://hookdeck.com/pricing) - 在任意位置开发、测试和监控 Webhook，每月 100,000 次请求和 100,000 次尝试，保留 3 天。
  * [localhost.run](https://localhost.run/) - 通过隧道将本地运行的服务器暴露为公开 URL。
  * [localtonet](https://localtonet.com/) - 面向 HTTP、TLS、TCP、UDP、文件服务器（Default、SFTP、WebDAV）和代理隧道（HTTP、SOCKS5、Shadowsocks、VLESS）的多协议隧道。免费方案含 1 条隧道、每月 1GB 带宽和 30 分钟超时（HTTP 隧道除外）。
  * [localtunnel](https://theboroer.github.io/localtunnel-www/) - 通过隧道将本地服务器暴露为公开 URL，提供免费托管版本并且[open source](https://github.com/localtunnel/localtunnel)。
  * [LocalXpose](https://localxpose.io) - 可将 localhost 服务器暴露到互联网的反向代理，免费方案隧道最长 15 分钟。
  * [ngrok.com](https://ngrok.com/) - 通过隧道将本地服务器暴露为公开 URL。
  * [Pinggy](https://pinggy.io) - 只需一条命令即可为 localhost 创建公开 URL，无需下载，支持 HTTPS/TCP/TLS 隧道。免费方案隧道最长 60 分钟。
  * [Radmin VPN](https://www.radmin-vpn.com/) - 通过 VPN 将多台电脑连接为类似局域网的网络，对等端数量不限。（Hamachi 替代品）
  * [serveo](https://serveo.net/) - 将本地服务器暴露到互联网，无需安装或注册，提供免费子域名且不限使用。
  * [stun:global.stun.twilio.com:3478?transport=udp](stun:global.stun.twilio.com:3478?transport=udp) - Twilio STUN
  * [stun:stun.l.google.com:19302](stun:stun.l.google.com:19302) - Google STUN
  * [Tailscale](https://tailscale.com/) - 使用开源 WireGuard 协议的零配置 VPN，可安装在 macOS、iOS、Windows、Linux 和 Android。个人免费方案支持 100 台设备和 3 名用户。
  * [webhookrelay.com](https://webhookrelay.com) - 管理、调试、扇出并代理所有 Webhook 到公开或内部（如 localhost）目标；也可通过获取公开 HTTP 端点，将私有网络服务器经隧道暴露（`https://yoursubdomain.webrelay.io <----> http://localhost:8080`）。
  * [Xirsys](https://www.xirsys.com/pricing/) - STUN 无限使用，每月 500MB TURN 带宽，带宽限速且仅限 1 个地理区域。
  * [ZeroTier](https://www.zerotier.com) - FOSS 托管虚拟以太网即服务。免费方案可创建无限端到端加密网络，每个网络 25 个客户端；提供桌面/移动/NA 客户端及 Web 界面，用于配置自定义路由规则和批准私有网络新节点。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="issue-tracking-and-project-management"></a>
## 问题跟踪与项目管理

<details>
<summary>展开 / 收起服务列表</summary>

  * [acunote.com](https://www.acunote.com/) - 最多 5 名团队成员的免费项目管理和 Scrum 软件。
  * [asana.com](https://asana.com/) - 带协作者的私有项目可免费使用。
  * [Backlog](https://backlog.com) - 在单一平台提供团队发布优质项目所需的一切。免费方案含 1 个项目、10 名用户和 100MB 存储。
  * [Basecamp](https://basecamp.com/personal) - 提供待办列表、里程碑管理、论坛式消息、文件共享和时间跟踪，最多 3 个项目、20 名用户和 1GB 存储。
  * [bitrix24.com](https://www.bitrix24.com/) - 内联网和项目管理工具，免费方案为无限用户提供 5GB。
  * [cacoo.com](https://cacoo.com/) - 在线实时图表，包括流程图、UML 和网络图。每张图最多 15 名用户、25 张 Sheet 免费。
  * [clickup.com](https://clickup.com/) - 项目管理，提供免费版和带云存储的高级版，并有移动应用和 Git 集成。
  * [Clockify](https://clockify.me) - 时间跟踪和工时表应用，可跨项目记录工作时长，用户数量不限，永久免费。
  * [Cloudcraft](https://cloudcraft.co/) - 通过 Cloudcraft 可视化设计器在数分钟内创建专业架构图，针对 AWS 优化并可用智能组件显示实时数据。免费方案单用户可创建无限私有图表。
  * [Confluence](https://www.atlassian.com/software/confluence) - Atlassian 内容协作工具，帮助团队高效协作和分享知识，最多 10 名用户免费。
  * [Crosswork](https://crosswork.app/) - 多功能项目管理平台，最多 3 个项目、无限用户和 1GB 存储免费。
  * [diagrams.net](https://app.diagrams.net/) - 在线图表工具，可将文件存储在本地、Google Drive、OneDrive 或 Dropbox，所有功能和存储层级均免费。
  * [easyretro.io](https://www.easyretro.io/) - 简单直观的 Sprint 回顾工具，免费方案含 3 个公开看板，每个看板每月 1 次调查。
  * [freedcamp.com](https://freedcamp.com/) - 提供任务、讨论、里程碑、时间跟踪、日历、文件和密码管理。免费方案项目、用户和文件存储不限。
  * [GForge](https://gforge.com) - 面向复杂项目的项目管理和问题跟踪工具集，提供本地与 SaaS 方案。SaaS 免费方案前 5 名用户免费，开源项目免费。
  * [gleek.io](https://www.gleek.io) - 面向开发者的免费“描述生成图表”工具，可用关键字创建非正式 UML 类图、对象图或实体关系图。
  * [GraphQL Inspector](https://github.com/marketplace/graphql-inspector) - 输出两个 GraphQL Schema 之间的变更列表，精确解释每项差异并标记为破坏性、非破坏性或危险。
  * [Helploom](https://helploom.com) - 客户支持软件，永久免费方案提供实时聊天。简单、轻量、美观，只需复制粘贴脚本即可配置，由开发者独立构建。
  * [HeyRetro](https://heyretro.io/) - 实时 Sprint 回顾平台，支持投票、计时器、调查、访客协作和破冰游戏。永久免费方案每月 1 个看板、匿名调查和访客链接分享。
  * [Hygger](https://hygger.io/) - 项目管理平台，免费方案用户、项目和看板不限，含 100MB 存储。
  * [Ilograph](https://www.ilograph.com/) - 交互式图表，可从多个视角和详细层级查看基础设施，图表可用代码表示。免费套餐可创建无限私有图，最多 3 名查看者。
  * [Jira](https://www.atlassian.com/software/jira) - 广泛用于企业环境的高级软件开发项目管理工具，最多 10 名用户免费。
  * [kan.bn](https://kan.bn/) - 强大灵活的看板应用，可在一处组织工作、跟踪进度并交付成果。免费方案限 1 名用户，但看板、列表和卡片不限。
  * [kanbanflow.com](https://kanbanflow.com/) - 基于看板的项目管理，提供免费版和功能更多的高级版。
  * [kanbantool.com](https://kanbantool.com/) - 基于看板的项目管理，免费方案含 2 个看板和 2 名用户，不支持附件或文件。
  * [Kitemaker.co](https://kitemaker.co) - 在产品开发各阶段协作，并跨 Slack、Discord、Figma 和 GitHub 跟踪工作。用户和空间不限，免费方案最多 250 个工作项。
  * [Kiter.app](https://www.kiter.app/) - 帮助任何人组织求职并跟踪面试、机会和人脉，提供强大的 Web 应用和 Chrome 扩展，完全免费。
  * [Kumu.io](https://kumu.io/) - 支持动画、装饰、过滤、聚类和电子表格导入等的关系图。免费套餐可创建无限公开项目，图规模不限；学生可用免费私有项目。若不想公开文件，可使用 Sandbox 模式进行上传、编辑、下载和丢弃。
  * [leiga.com](https://www.leiga.com/) - 使用 AI 自动管理项目，帮助团队保持专注并确保项目按计划推进。最多 10 名用户、20 个自定义字段、2GB 存储免费；AI 视频录制每段限 5 分钟，自动化运行每用户每月 20 次。
  * [Linear](https://linear.app/) - 界面精简的问题跟踪器，成员不限，单文件上传上限 10MB，最多 250 个 Issue（归档除外）免费。
  * [Lucidchart](https://www.lucidchart.com/) - 带协作功能的在线图表工具，免费方案含 3 份可编辑文档、100 个专业模板和基础协作功能。
  * [MeisterTask](https://www.meistertask.com/) - 面向团队的在线任务管理，最多 3 个项目免费，项目成员不限。
  * [MeuScrum](https://www.meuscrum.com/en) - 带看板的免费在线 Scrum 工具。
  * [nTask](https://www.ntaskmanager.com/) - 帮助团队协作、规划、分析和管理日常任务的项目管理软件。Essential 方案永久免费，含 100MB 存储和 5 名用户/团队；工作区、会议、任务、工时表和问题跟踪不限。
  * [Plane](https://plane.so/) - 简单、可扩展、开源的项目和产品管理工具，成员不限，单文件上传最大 5MB，最多 1,000 个 Issue 免费。
  * [planitpoker.com](https://www.planitpoker.com/) - 免费在线 Planning Poker（估算工具）。
  * [point.poker](https://www.point.poker/) - 在线 Planning Poker（基于共识的估算工具），用户、团队、会话、轮次和投票不限，无需注册。
  * [Pulse.red](https://pulse.red/) - 面向项目的免费极简时间跟踪和工时表应用。
  * [ScrumFast](https://www.scrumfast.com) - 界面直观的 Scrum 看板，最多 5 名用户免费。
  * [Sflow](https://sflow.io) - 面向敏捷软件开发、营销、销售和客户支持的项目管理工具，尤其适合外包和跨组织协作项目。免费方案最多 3 个项目和 5 名成员。
  * [Shake](https://www.shakebugs.com/) - 移动应用内缺陷报告和反馈工具，免费方案每个应用每月 10 份缺陷报告。
  * [Shortcut](https://shortcut.com/) - 项目管理平台，最多 10 名用户永久免费。
  * [taiga.io](https://taiga.io/) - 面向创业公司和敏捷开发者的项目管理平台，开源项目免费。
  * [taskade.com](https://www.taskade.com/) - 实时协作任务列表和团队大纲。免费方案含 1 个工作区、无限任务和项目、1GB 文件存储、1 周项目历史，以及每次视频会议 5 名参与者。
  * [Teaminal](https://www.teaminal.com) - 面向远程团队的站会、回顾和 Sprint 规划工具，最多 15 名用户免费。
  * [teamwork.com](https://teamwork.com/) - 项目管理和团队聊天，5 名用户及 2 个项目免费，另有高级方案。
  * [teleretro.com](https://www.teleretro.com/) - 简单有趣的回顾工具，带破冰、GIF 和 Emoji。免费方案含 3 次回顾和无限成员。
  * [Tenzu](https://tenzu.net/) - 面向敏捷团队的轻量项目管理工具。SaaS 依靠自愿贡献，用户始终可选择支付 0，且没有功能付费墙。{[more details](https://tenzu.net/pricing/)}
  * [titanapps.io](https://titanapps.io/) - 面向 Jira 和 monday.com 的生产力工具，在 Issue/任务中提供结构化清单、模板和审批，小团队可用免费方案。
  * [todoist.com](https://todoist.com/) - 协作与个人任务管理。免费方案含 5 个活跃项目、每项目 5 名用户、最大 5MB 文件上传、3 个过滤器和 1 周活动历史。
  * [Toggl](https://toggl.com/) - 提供两款免费生产力工具：[Toggl Track](https://toggl.com/track/) 用于时间管理和跟踪，免费方案面向自由职业者，提供无缝时间记录和报告，跟踪记录、项目、客户、标签和报告等不限；[Toggl Plan](https://toggl.com/plan/) 用于任务规划，个人开发者免费方案的任务、里程碑和时间线不限。
  * [trello.com](https://trello.com/) - 基于看板的项目管理，无限个人看板和 10 个团队看板。
  * [Tweek](https://tweek.so/) - 简单的每周待办日历和任务管理。
  * [Wikifactory](https://wikifactory.com/) - 提供项目、版本控制和 Issue 的产品设计服务，免费方案项目和协作者不限，含 3GB 存储。
  * [Yodiz](https://www.yodiz.com/) - 敏捷开发和问题跟踪，最多 3 名用户免费，项目不限。
  * [YouTrack](https://www.jetbrains.com/youtrack/buy/#edition=incloud) - 为 FOSS 项目和私有项目提供免费托管 YouTrack（InCloud），私有项目最多 3 名用户，包含时间跟踪和敏捷看板。
  * [zenhub.com](https://www.zenhub.com) - GitHub 内的项目管理解决方案，公开仓库、OSS 和非营利组织免费。
  * [zenkit.com](https://zenkit.com) - 项目管理与协作工具，最多 5 名成员和 5GB 附件免费。
  * [Zube](https://zube.io) - 项目管理，免费方案含 4 个项目和 4 名用户，并可集成 GitHub。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="storage-and-media-processing"></a>
## 存储与媒体处理

<details>
<summary>展开 / 收起服务列表</summary>

  * [AndroidFileHost](https://androidfilehost.com/) - 免费文件分享平台，速度、带宽、文件数和下载次数等不限。主要面向 APK 构建、定制 ROM 和修改包等 Android 开发文件，但似乎也接受其他文件。
  * [anon.li Drop](https://anon.li/drop) - 零知识端到端加密文件分享，使用客户端 AES-256-GCM 加密，服务器无法访问数据。通过网站、CLI 或 API 免费上传最大 5GB 文件，最长 3 天过期。
  * [borgbase.com](https://www.borgbase.com/) - 简单安全的 Borg Backup 异地备份托管，免费 10GB 备份空间和 2 个仓库。
  * [cloudinary.com](https://cloudinary.com/) - 为网站和应用提供图片上传、强大处理、存储和分发，并提供 Ruby、Python、Java、PHP、Objective-C 等库。免费套餐每月 25 积分；1 积分等于 1,000 次图片转换、1GB 存储或 1GB CDN 用量。
  * [degoo.com](https://degoo.com/) - AI 云存储，最多免费 20GB、3 台设备和 5GB 推荐奖励（账号 90 天不活跃会受限）。
  * [dlvr.sh](https://dlvr.sh/) - 面向 Agent 和自动化的临时文件投递，免费套餐每 24 小时 10 次投递，并提供 API、MCP 和 CLI。
  * [Dropshare](https://dropsha.re) - 零知识文件分享，使用 AES-256-GCM 端到端加密、客户端处理，服务器无法访问数据。单文件最大 1GB 免费上传且不收集数据。
  * [embed.ly](https://embed.ly/) - 提供网页媒体嵌入、响应式图片缩放和网页元素提取 API，每月最多 5,000 个 URL、每秒 15 次请求免费。
  * [Ente](https://ente.io/) - 用于照片、视频和 2FA Secret 的端到端加密云，也可自托管，并提供 10GB 永久免费套餐。免费用户的数据只保留 1 份副本。
  * [FileShot.io](https://fileshot.io) - 零知识加密文件分享，浏览器端 AES-256-GCM 加密确保上传前已加密，发送者和接收者均无需账号。可自托管（MIT 开源），免费套餐上传次数和文件大小均不限。
  * [file.io](https://www.file.io) - 2GB 文件存储，文件下载一次后自动删除，并提供 REST API，速率限制为每分钟 1 次请求。
  * [freetools.site](https://freetools.site/) - 免费在线工具，可转换或编辑文档、图片、音频、视频等。
  * [getpantry.cloud](https://getpantry.cloud/) - 简单 JSON 数据存储 API，非常适合个人项目、黑客松和移动应用。
  * [GoFile.io](https://gofile.io/) - 可通过 Web UI 和 API 使用的免费文件分享与存储平台，文件大小、带宽和下载次数不限；文件超过 10 天无下载会被删除。
  * [gumlet.com](https://www.gumlet.com/) - 通过 CDN 托管、处理和流式传输图片与视频，免费套餐每月提供 250GB 视频和 30GB 图片额度。
  * [hyperserve.io](https://hyperserve.io/) - 面向开发者的视频后端 API：接受用户上传的任意格式，转码为 MP4 并通过 CDN 全球分发。免费层包含 50 个视频、单文件 1GB，以及每月 250GB bandwidth。
  * [icedrive.net](https://www.icedrive.net/) - 简单云存储服务，免费 10GB。
  * [image-charts.com](https://www.image-charts.com/) - 可无限生成带水印的图片图表。
  * [ImageEngine](https://imageengine.io/) - 易用的全球图片 CDN，60 秒内即可配置，支持 AVIF、JPEG XL，以及 WordPress、Magento、React、Vue 等插件。可在[here](https://imageengine.io/developer-program/)申请免费开发者账号。
  * [imagekit.io](https://imagekit.io) - 图片 CDN，支持自动优化、实时转换和存储，可在数分钟内集成现有系统。免费方案每月最多 20GB 带宽。
  * [ImgBB](https://imgbb.com/) - 无限图片托管服务，可拖放上传，单图上限 32MB。上传后可获得图片直链、BBCode 和 HTML 缩略图，登录后可查看上传历史。
  * [Imgbot](https://github.com/marketplace/imgbot) - 自动优化图片并节省时间，在不损失质量的前提下减小文件体积，开源项目免费。
  * [imgen](https://www.jitbit.com/imgen/) - 实时图片生成 API，可在背景上添加文字和 Logo，适合 Open Graph 图片，免费、无水印并提供 CDN。
  * [imgix](https://www.imgix.com/) - 图片缓存、管理和 CDN，免费方案含 1,000 张源图片、无限转换和 100GB 带宽。
  * [internxt.com](https://internxt.com) - 基于绝对隐私和严格安全的零知识文件存储服务，注册后永久免费获得 10GB。
  * [kraken.io](https://kraken.io/) - 网站性能图片优化即服务，免费方案单文件最大 1MB。
  * [LibreQR](https://libreqr.com) - 注重隐私且无跟踪的免费二维码生成器，不收集数据。
  * [MConverter](https://mconverter.eu/) - 批量转换文件，支持包括 [AVIF](https://mconverter.eu/convert/to/avif/) 和 JXL 在内的多种格式，可从视频提取帧并压缩 PDF。每 24 小时免费处理 15 个文件，每个最大 100MB，每批最多 8 个。
  * [nitropack.io](https://nitropack.io/) - 通过缓存、图片与代码优化和 CDN 自动完成前端优化以加速网站，每月最多 5,000 次页面浏览免费。
  * [npoint.io](https://www.npoint.io/) - 支持协作式 Schema 编辑的 JSON 存储。
  * [MantleDB](https://mantledb.sh) - 面向脚本和小型应用的匿名 JSON 存储，无需注册；使用 Master AID 更新，使用只读 RID 公开获取。免费套餐含 1 个 Bucket（1MB 上限），72 小时不活跃后清理。
  * [otixo.com](https://www.otixo.com/) - 在一个位置加密、分享、复制和移动所有云存储文件。基础方案文件传输不限，单文件最大 250MB，并允许 5 个加密文件。
  * [packagecloud.io](https://packagecloud.io/) - 面向 YUM、APT、RubyGem 和 PyPI 的托管软件包仓库，可申请有限免费方案和开源方案。
  * [pcloud.com](https://www.pcloud.com/) - 云存储服务，最多 10GB 免费空间。
  * [Pinata IPFS](https://pinata.cloud) - 简单的 IPFS 文件上传和管理服务，通过友好 UI 和 IPFS API 为平台、创作者和收藏者提供易用 Pinning。免费 1GB 存储并可访问 API。
  * [plot.ly](https://plot.ly/) - 绘图并分享数据，免费套餐含无限公开文件和 10 个私有文件。
  * [podio.com](https://podio.com/) - 最多 5 人团队可使用 Podio 并试用 Basic 方案功能，但不含用户管理。
  * [Proton Drive](https://proton.me/drive) - 用于文件和重要文档的高安全云存储，免费方案含 5GB。
  * [QRtracer](https://qrtracer.io) - 免费二维码生成器，内置扫描分析、批量生成和品牌自定义，注重可靠性且无广告。
  * [QuickChart](https://quickchart.io) - 生成可嵌入的图片图表、曲线图和二维码。
  * [redbooth.com](https://redbooth.com) - P2P 文件同步，最多 2 名用户免费。
  * [resmush.it](https://resmush.it) - 免费图片优化 API，已应用于 WordPress、Drupal、Magento 等常用 CMS，累计处理超过 70 亿张图片，仍完全免费。
  * [sirv.com](https://sirv.com/) - 智能图片 CDN，可实时优化和缩放图片，免费套餐含 500MB 存储和 2GB 带宽。
  * [SlingSite](https://slingsite.github.io) - 免费批量生成图片和视频的优化版本。每张图片输出桌面、平板、手机三种分辨率的 AVIF、WEBP、JPG；视频输出 WebM（VP9）、MP4（HEVC/H.265）、MP4（AVC/H.264），并从首帧生成封面。
  * [sync.com](https://www.sync.com/) - 端到端加密云存储，免费 5GB。
  * [tinypng.com](https://tinypng.com/) - PNG 和 JPEG 压缩与缩放 API，每月免费 500 次压缩。
  * [transloadit.com](https://transloadit.com/) - 处理文件上传及视频、音频、图片、文档编码。通过 GitHub Student Developer Pack 为开源项目、慈善机构和学生免费；商业应用可免费试用 2GB。
  * [twicpics.com](https://www.twicpics.com) - 响应式图片即服务，提供图片 CDN、媒体处理 API 和前端库以自动优化图片，每月最多 3GB 流量免费。
  * [uploadcare.com](https://uploadcare.com/hub/developers/) - 基于先进算法的媒体处理流水线，为开发者免费提供文件上传 API/UI、图片 CDN 与源站服务、自适应交付和智能压缩。免费套餐含 3,000 次上传、3GB 流量和 3GB 存储。
  * [VaocherApp QR Code Generator](https://www.vaocherapp.com/qr-code-generator) - 轻松为礼品卡、礼券和促销创建自定义二维码，支持自定义样式、颜色和 Logo 等。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="design-and-ui"></a>
## 设计与 UI

<details>
<summary>展开 / 收起服务列表</summary>

  * [Beste](https://beste.co) - 基于 shadcn/ui blocks、以 composition-first 为理念的网站构建器。免费计划可连接自定义域名，并包含无限页面、多语言支持、博客、表单和托管。
  * [BoxySVG](https://boxy-svg.com) - 可安装的免费 Web SVG 绘图应用，支持导出 SVG、PNG、JPEG 等格式。
  * [BrandIcons](https://brandicons.dev) - Favicon API；对没有图标甚至没有 Web server 的域名也可通过 AI 发现图标。免费层每月 500000 次请求，需 attribution。
  * [Calendar Icons Generator](https://calendariconsgenerator.app/) - 一键生成整整一年的独特图标，完全免费。
  * [Canva](https://canva.com) - 用于创建视觉内容的免费在线设计工具。
  * [CodedThemes](https://codedthemes.com/) - 提供精心制作的管理仪表板和 UI Kit，简化并加速现代 Web 开发。
  * [Excalidraw](https://excalidraw.com/) - 免费在线绘图页面，支持免费保存到本地和导出。
  * [figma.com](https://www.figma.com) - 面向团队的在线协作设计工具，免费套餐文件和查看者不限，最多 2 名编辑者和 3 个项目。
  * [Flows](https://flows.sh/) - 完全可自定义的产品采用平台，用于构建用户引导和互动体验，最多每月 250 名跟踪用户免费。
  * [landen.co](https://www.landen.co) - 无需代码即可为创业公司生成、编辑和发布美观网站与落地页。免费套餐允许创建 1 个完全可自定义并发布到互联网的网站。
  * [lensdump.com](https://lensdump.com/) - 免费云端图片托管。
  * [Logo.dev](https://www.logo.dev) - 覆盖 4,400 多万个品牌的公司 Logo API，像调用 URL 一样简单，前 10,000 次 API 调用免费。
  * [marvelapp.com](https://marvelapp.com/) - 设计、原型和协作，免费方案限 1 名用户和 1 个项目。
  * [Mindmup.com](https://www.mindmup.com/) - 免费创建无限思维导图并存储在云端，可随时从任意设备访问。
  * [Mockplus iDoc](https://www.mockplus.com/idoc) - 强大的设计协作与交付工具，免费方案含 3 名用户和 5 个项目，所有功能均可用。
  * [photopea.com](https://www.photopea.com) - 免费高级在线设计编辑器，采用 Adobe Photoshop 风格 UI，支持 PSD、XCF 和 Sketch 格式。
  * [Plasmic](https://www.plasmic.app/) - 快速、易用、可靠的 Web 设计和页面构建工具，可集成到代码库，构建响应式页面或复杂组件、用代码扩展，并发布到生产站点和应用。
  * [Proto.io](https://www.proto.io) - 无需编码创建完全交互式 UI 原型，免费试用结束后可使用免费套餐，含 1 名用户、1 个项目、5 个原型、100MB 在线存储和 Proto.io 应用预览。
  * [Quant Ux](https://quant-ux.com/) - 原型与设计工具，完全免费且开源。
  * [Shadcn Studio](https://shadcnstudio.com/theme-editor) - 在不同组件和布局中预览主题更改。
  * [smartmockups.com](https://smartmockups.com/) - 创建产品 Mockup，含 200 个免费 Mockup。
  * [SVGicons.com](https://svgicons.com/) - 免费 SVG 图标搜索引擎，收录 312K+ 开源 SVG 图标，并提供可直接使用的 SVG、React、Vue、HTML 和 CSS 代码。
  * [TeleportHQ](https://teleporthq.io/) - 低代码前端设计与开发平台，可协作即时创建和发布无头静态网站。免费含 3 个项目、无限协作者和免费代码导出。
  * [Unicorn Platform](https://unicornplatform.com/) - 带托管的便捷落地页构建器，1 个网站免费。
  * [Updrafts.app](https://updrafts.app) - 面向 Tailwind CSS 设计的 WYSIWYG 网站构建器，非商业用途免费。
  * [Webflow](https://webflow.com) - 带动画和网站托管的 WYSIWYG 网站构建器，2 个项目免费。
  * [Webstudio](https://webstudio.is/) - Webflow 的开源替代品。免费方案可在平台域名上创建无限网站，并支持 5 个自定义域名网站、每月 10,000 次页面浏览和 2GB 资源存储。
  * [whimsical.com](https://whimsical.com/) - 协作式流程图、线框图、便签和思维导图，最多创建 4 个免费看板。
  * [Zeplin](https://zeplin.io/) - 设计师和开发者协作平台，用于展示设计、资源和样式指南，1 个项目免费。
  * [WrapPixel](https://www.wrappixel.com/) - 下载使用 Angular、React、Vue.js、Next.js 和 Nuxt.js 创建的高质量免费及付费管理仪表板模板、HTML 主题和 UI Kit，加快应用开发。
  * [Themeselection](https://themeselection.com/) - 精选高质量、现代、专业且易用的免费管理仪表板模板。
  * [AdminMart](https://adminmart.com/) - 使用 Angular、Bootstrap、React、Vue.js、Next.js 和 Nuxt.js 创建的高质量免费及付费管理仪表板和网站模板。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="data-visualization-on-maps"></a>
## 地图数据可视化

<details>
<summary>展开 / 收起服务列表</summary>

  * [Clockwork Micro](https://clockworkmicro.com/) - 稳定可靠的地图工具，每月 50,000 次免费查询（地图瓦片、db2vector、海拔）。
  * [Foursquare](https://developer.foursquare.com/) - 通过 Places API 和 Pilgrim SDK 提供地点发现、场所搜索和上下文感知内容。
  * [geoapify.com](https://www.geoapify.com/) - 提供矢量/栅格地图瓦片、地理编码、地点、路线和等值线 API，每天 3,000 次免费请求。
  * [geocod.io](https://www.geocod.io/) - 通过 API 或 CSV 上传进行地理编码，每天 2,500 次免费查询。
  * [geocodify.com](https://geocodify.com/) - 通过 API 或 CSV 上传进行地理编码和地理解析，每月 10,000 次免费查询。
  * [geojs.io](https://www.geojs.io/) - 高可用 REST/JSON/JSONP IP 地理位置查询 API。
  * [Geokeo api](https://geokeo.com) - 支持语言纠正等功能的地理编码 API，覆盖全球，每天 2,500 次免费查询。
  * [graphhopper.com](https://www.graphhopper.com/) - 为路线规划、路线优化、距离矩阵、地理编码和地图匹配提供免费开发者套餐。
  * [here](https://developer.here.com/) - 面向地图和位置感知应用的 API 与 SDK，每月 250,000 次事务免费。
  * [IP Geolocation](https://ipgeolocation.io/) - 免费 DEVELOPER 方案每月 30,000 次请求。
  * [ipstack](https://ipstack.com/) - 通过 IP 地址定位和识别网站访客。
  * [LatLng](https://www.latlng.work) - 地理编码、反向地理编码、地点、静态地图和矢量瓦片 API。免费套餐每天含 3,000 次地理编码、300 次反向地理编码和 100 张静态地图图片。
  * [locationiq.com](https://locationiq.com/) - 地理编码、地图和路线 API，每天 5,000 次免费请求。
  * [mapbox.com](https://www.mapbox.com/) - 用于显示地图数据的地图、地理空间服务和 SDK。
  * [maps.stamen.com](https://maps.stamen.com/) - 免费地图瓦片和瓦片托管。
  * [maptiler.com](https://www.maptiler.com/cloud/) - 地图可视化的矢量地图、地图服务和 SDK，免费矢量瓦片每周更新并提供 4 种地图样式。
  * [nominatim.org](https://nominatim.org/) - OpenStreetMap 的免费地理编码服务，提供全球地址搜索和反向地理编码。
  * [opencagedata.com](https://opencagedata.com) - 聚合 OpenStreetMap 和其他开放地理数据源的地理编码 API，每天 2,500 次免费查询。
  * [osmnames](https://osmnames.org/) - 地理编码，搜索结果按相关 Wikipedia 页面的热度排序。
  * [positionstack](https://positionstack.com/) - 全球地点和坐标免费地理编码，个人使用每月 25,000 次请求。
  * [stadiamaps.com](https://stadiamaps.com/) - 地图瓦片、路线、导航和其他地理空间 API，非商业用途和测试每天 2,500 次免费地图浏览/API 请求。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="package-build-system"></a>
## 软件包构建系统

<details>
<summary>展开 / 收起服务列表</summary>

  * [build.opensuse.org](https://build.opensuse.org/) - 面向多个发行版（SUSE、EL、Fedora、Debian 等）的软件包构建服务。
  * [copr.fedorainfracloud.org](https://copr.fedorainfracloud.org) - 面向 Fedora 和 EL、基于 Mock 的 RPM 构建服务。
  * [help.launchpad.net](https://help.launchpad.net/Packaging) - Ubuntu 和 Debian 构建服务。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="ide-and-code-editing"></a>
## IDE 与代码编辑

<details>
<summary>展开 / 收起服务列表</summary>

  * [Android Studio](https://developer.android.com/studio) - 为各类 Android 设备构建应用提供快速工具。开源 IDE 对所有人免费，是 Android 应用开发的主流选择，支持 Windows、Mac、Linux 和 ChromeOS。
  * [AndroidIDE](https://m.androidide.com/) - 在 Android 设备上开发真实、基于 Gradle 的 Android 应用的开源 IDE。
  * [Apache Netbeans](https://netbeans.apache.org/) - 开发环境、工具平台和应用框架。
  * [apiary.io](https://apiary.io/) - 协作式 API 设计，提供即时 API Mock 和自动生成文档；免费支持无限 API Blueprint、无限用户、1 个管理员账号和托管文档。
  * [BBEdit](https://www.barebones.com/) - 流行且可扩展的 macOS 编辑器，免费模式提供[powerful core feature set](https://www.barebones.com/products/bbedit/comparison.html)，并可升级使用高级功能。
  * [Binder](https://mybinder.org/) - 将 Git 仓库转换为一组交互式 Notebook，是免费公共服务。
  * [BlueJ](https://bluej.org) - 面向初学者的免费 Java 开发环境，全球数百万人使用，由 Oracle 支持，并提供帮助入门的简洁 GUI。
  * [Brackets](https://brackets.io/) - 专为 Web 开发设计的开源文本编辑器，轻量、易用且高度可定制。
  * [cacher.io](https://www.cacher.io) - 支持标签和 100 多种编程语言的代码片段整理工具。
  * [cocalc.com](https://cocalc.com/) - 云端协作计算平台，可在浏览器中访问完整 Ubuntu，内置协作以及大量数学、科学和数据科学软件，包括 Python、LaTeX、Jupyter Notebooks、SageMath、scikit-learn 等。
  * [Code::Blocks](https://codeblocks.org) - 免费 Fortran 和 C/C++ IDE，开源并支持 Windows、macOS 和 Linux。
  * [Codeground](https://codeground.ai/) - 免费浏览器 IDE 和 Playground，支持 15 种以上语言以及 Postgres、MySQL、MongoDB、Redis，并提供可分享片段、编程面试和云工作区。免费 Playground 无需安装。
  * [codiga.io](https://www.codiga.io) - 可直接在 IDE 中搜索、定义和复用代码片段的编程助手，个人和小型组织免费。
  * [Components.studio](https://webcomponents.dev/) - 隔离编写组件、在 Story 中可视化、测试并发布到 npm。
  * [Eclipse Che](https://www.eclipse.org/che/) - 面向开发团队、基于 Web 且原生 Kubernetes 的多语言 IDE，开源并由社区驱动。Red Hat 托管的在线实例位于 [workspaces.openshift.com](https://workspaces.openshift.com/)。
  * [ForgeCode](https://forgecode.dev/) - 面向 Claude、GPT-4 系列、Grok、DeepSeek、Gemini 等前沿模型的 AI 结对编程工具，可原生运行于 CLI 并无缝集成任意 IDE。免费套餐提供基础 AI 模型访问和本地处理。
  * [GetVM](https://getvm.io) - Chrome 侧边栏中的即时免费 Linux 和 IDE，免费套餐每天 5 台 VM。
  * [JDoodle](https://www.jdoodle.com) - 支持 60 多种编程语言的在线编译器和编辑器，REST API 免费方案每天最多 200 积分。
  * [jetbrains.com](https://jetbrains.com/products.html) - 生产力工具、IDE 和部署工具（如 [IntelliJ IDEA](https://www.jetbrains.com/idea/)、[PyCharm](https://www.jetbrains.com/pycharm/) 等），学生、教师、开源项目和用户组可获得免费许可证。
  * [JSONPlaceholder](https://jsonplaceholder.typicode.com/) - 返回 JSON 模拟数据的若干 REST API 端点，也提供源码，可在本地运行服务器。
  * [Lazarus](https://www.lazarus-ide.org/) - 兼容 Delphi 的跨平台快速应用开发 IDE。
  * [MarsCode](https://www.marscode.com/) - 免费 AI 云 IDE。
  * [micro-jaymock](https://micro-jaymock.now.sh/) - 用于生成虚假 JSON 数据的小型 API Mock 微服务。
  * [mockaroo](https://mockaroo.com/) - 生成 CSV、JSON、SQL 和 Excel 格式的真实测试数据，也可为后端 API 创建 Mock。
  * [Mocklets](https://mocklets.com) - 基于 HTTP 的模拟 API 工具，可加快并行开发并实现更全面测试，提供终身免费套餐。
  * [OneCompiler](https://onecompiler.com/) - 免费在线编译器，支持 Java、Python、C++、JavaScript 等 70 多种语言。
  * [OnlineGDB](https://onlinegdb.com) - 免费在线 IDE，支持 40 多种语言并预装大量库，还提供调试、编译 Flag、教程和问答页面。
  * [pterocos](https://pterocos.eu.org) - 面向前端开发者的免费开源浏览器编程环境，使用 VS Code 级 Monaco 编辑器编写 HTML、CSS 和 JS，支持实时预览、SCSS/TypeScript/Babel 和用于调试及建议的 AI 聊天助手。所有项目保存在本地存储，永久免费且无需账号。
  * [Paiza](https://paiza.cloud/en/) - 无需配置即可在浏览器中开发 Web 应用。免费方案提供 1 台生命周期 24 小时的服务器，每天运行 4 小时，配备 2 CPU 核心、2GB RAM 和 1GB 存储。
  * [PHPSandbox](https://phpsandbox.io/) - PHP 在线开发环境。
  * [Replit](https://replit.com/) - 支持多种编程语言的云端编程环境。
  * [RunMat](https://runmat.com/sandbox) - 浏览器中的 GPU 加速数值计算 IDE，可编写和运行 MATLAB 语法 `.m` 文件，并通过 WebAssembly 和 WebGPU 自动 GPU 加速。无需安装、账号或许可证费用；运行时开源，并支持 CLI、NPM 包和 Jupyter Kernel。
  * [SoloLearn](https://code.sololearn.com) - 适合运行代码片段的云端编程 Playground，支持多种语言。运行代码无需注册，保存代码时需要账号；也提供面向初中级开发者的免费课程。
  * [stackblitz.com](https://stackblitz.com/) - 在线/云端代码 IDE，用于创建、编辑和部署全栈应用，支持常见 Node.js 前后端框架。新建项目短链接：[https://node.new](https://node.new)。
  * [Sublime Text](https://www.sublimetext.com/) - 流行、多用途且高度可定制的文本编辑器，用于编程和文本编辑。
  * [Visual Studio Code](https://code.visualstudio.com/) - 为构建和调试现代 Web 与云应用优化的代码编辑器，由 Microsoft 开发。
  * [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) - 功能完整的 IDE，提供数千扩展，支持跨平台应用开发（可下载 Microsoft iOS/Android 扩展）、桌面、Web 和云开发，以及 C#、C++、JavaScript、Python、PHP 等多语言。
  * [VSCodium](https://vscodium.com/) - 社区驱动、无遥测/跟踪且采用自由许可证的 Microsoft VS Code 二进制发行版。
  * [wakatime.com](https://wakatime.com/) - 通过文本编辑器插件量化编程活动，提供有限免费方案。
  * [Wave Terminal](https://waveterm.dev/) - 开源跨平台终端，可流畅处理工作流、内联渲染内容并保存会话与历史，基于开放 Web 标准，支持 macOS 和 Linux。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="analytics-events-and-statistics"></a>
## 分析、事件与统计

<details>
<summary>展开 / 收起服务列表</summary>

  * [amplitude.com](https://amplitude.com/) - 每月 100 万个事件，最多 2 个应用。
  * [AppFit](https://appfit.io) - 综合分析和产品管理工具，用于无缝跨平台管理分析及产品更新。免费方案每月含 10,000 个事件、产品日志和每周洞察。
  * [Aptabase](https://aptabase.com) - 开源、隐私友好且简单的移动和桌面应用分析，提供 Swift、Kotlin、React Native、Flutter、Electron 等 SDK，每月最多 20,000 个事件免费。
  * [Avo](https://avo.app/) - 简化分析发布工作流，提供单一事实来源的跟踪计划、类型安全分析库、应用内调试和数据可观测性，在发布前发现数据问题。2 名工作区成员和 1 小时数据可观测回溯免费。
  * [Beampipe.io](https://beampipe.io) - 简单、注重隐私的 Web 分析，最多 5 个域名和每月 10,000 次页面浏览免费。
  * [Census](https://www.getcensus.com/) - 反向 ETL 与运营分析平台，可将数据仓库中的 10 个字段同步到 Salesforce、Zendesk、Amplitude 等 60 多种 SaaS。
  * [Clicky](https://clicky.com) - 网站分析平台，免费方案支持 1 个网站和 3,000 次浏览分析。
  * [counter.dev](https://counter.dev) - 简单且隐私友好的 Web 分析，可免费使用或自愿捐赠。
  * [DocBeacon](https://docbeacon.io) - 带文档跟踪和互动分析的安全文档分享。免费方案最多支持 20 份 PDF（单份最大 10MB）、10 个联系人、每份文档分享 2 次，并提供浏览、下载、停留时间和互动的基础分析。
  * [Dwh.dev](https://dwh.dev) - 数据云可观测性解决方案（Snowflake），个人使用免费。
  * [Expensify](https://www.expensify.com/) - 费用报告，个人报销审批工作流免费。
  * [getinsights.io](https://getinsights.io) - 注重隐私、无 Cookie 的分析，每月最多 3,000 个事件免费。
  * [Gizmo Analytics](https://gizmoanalytics.io/) - 面向管理大量站点用户的简单分析，可手动安装或让 Claude/Cursor 安装。每月最多 10,000 个事件免费。
  * [GoatCounter](https://www.goatcounter.com/) - 开源 Web 分析平台，可使用托管服务（非商业用途免费）或自托管，旨在提供易用、有意义、隐私友好的 Google Analytics/Matomo 替代方案。非商业免费套餐含无限站点、6 个月数据保留和每月 100,000 次页面浏览。
  * [Google Analytics](https://analytics.google.com/) - Google Analytics。
  * [heap.io](https://heap.io) - 自动捕获 iOS 或 Web 应用中的每个用户操作，每月最多 10,000 个会话免费。
  * [Hightouch](https://hightouch.com/) - 反向 ETL 平台，可将数据仓库中的客户数据同步到 CRM、营销和支持工具，免费套餐允许同步到 1 个目标。
  * [HitKeep](https://hitkeep.com/) - 注重隐私的开源 Web 与产品分析平台，免费云方案支持 3 个网站、3 名团队成员、60 天数据保留，并提供 AI 分析、目标、漏斗、事件和 Hit。
  * [Hotjar](https://hotjar.com) - 网站分析和报告。免费方案每天 2,000 次页面浏览、每天 100 个快照（最多 300），3 个快照热力图可保存 365 天，团队成员不限。另提供应用内和独立调查、带截图的反馈组件；免费套餐可创建 3 个调查和 3 个反馈组件，每月收集 20 条响应。
  * [LogSpot](https://logspot.io) - 统一 Web 与产品分析平台，包含可嵌入分析组件和自动机器人（Slack、Telegram、Webhook）。免费方案每月 10,000 个事件。
  * [Mixpanel](https://mixpanel.com/) - 每月跟踪 100,000 名用户，数据历史和席位不限，可选择美国或欧盟数据驻留。
  * [Moesif](https://www.moesif.com) - REST 和 GraphQL API 分析，每月最多 500,000 次 API 调用免费。
  * [PostHog](https://posthog.com) - 完整产品分析套件，每月最多 100 万个跟踪事件免费，并提供无限应用内调查和每月 250 条响应。
  * [Repohistory](https://repohistory.com) - 美观仪表板，可跟踪超过 14 天的 GitHub 仓库流量历史，免费方案支持监控 1 个仓库。
  * [Row Zero](https://rowzero.io) - 极速连接式电子表格，可直接连接数据库、S3 和 API，即时导入、分析、绘图和分享数百万行数据，永久提供 3 个免费工作簿。
  * [Rybbit](https://rybbit.io) - 开源无 Cookie 的 Google Analytics 替代品，更直观易用。免费方案每月 3,000 个事件。
  * [Seline](https://seline.so) - 简单私密的网站和产品分析，无 Cookie、轻量、独立。免费方案每月 3,000 个事件，并可使用仪表板、用户旅程、漏斗等全部功能。
  * [StatCounter](https://statcounter.com/) - 网站访客分析，免费方案分析最近 500 名访客。
  * [Statsig](https://statsig.com) - 集分析、功能开关和 A/B 测试于一体，每月最多 100 万个计量事件免费。
  * [TraceLog](https://tracelog.io/) - 面向电商的 AI 分析，可用自然语言查询分析数据、获得可执行建议，并通过 AI 洞察提升收入。每月最多 10,000 个事件免费。
  * [Trackingplan](https://www.trackingplan.com/) - 自动检测数字分析、营销数据和 Pixel 问题，维护最新跟踪计划并促进协作。可部署到有真实流量的生产环境，也可无需代码为回归测试增加分析覆盖。
  * [TrackWith Dicloud](https://dicloud.net/trackwith-privacy-focused-analytics/) - 轻量、注重隐私的 Google Analytics 免费替代品，页面浏览、访客、热力图和目标跟踪不限。最多 3 个域名免费，每域名 600 次会话回放。
  * [Umami](https://umami.is/) - 简单、快速、注重隐私的开源 Google Analytics 替代品。
  * [usabilityhub.com](https://usabilityhub.com/) - 在真实用户上测试设计与 Mockup 并跟踪访客，1 名用户免费，测试不限。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="visitor-session-recording"></a>
## 访客会话录制

<details>
<summary>展开 / 收起服务列表</summary>

  * [FullStory.com](https://www.fullstory.com) - 每月 1,000 个会话，数据保留 1 个月，含 3 个用户席位。更多信息见[here](https://help.fullstory.com/hc/en-us/articles/360020623354-FullStory-Free-Edition)。
  * [howuku.com](https://howuku.com) - 跟踪用户交互、参与度和事件，每月最多 5,000 次访问免费。
  * [inspectlet.com](https://www.inspectlet.com/) - 1 个网站每月 2,500 个会话免费。
  * [LogRocket.com](https://www.logrocket.com) - 每月 1,000 个会话，保留 30 天，含错误跟踪和实时模式。
  * [Microsoft Clarity](https://clarity.microsoft.com/) - 完全免费的会话录制，无流量限制、无项目限制且不抽样。
  * [mouseflow.com](https://mouseflow.com/) - 1 个网站每月 500 个会话免费。
  * [OpenReplay.com](https://www.openreplay.com) - 开源会话回放，提供缺陷复现开发工具、实时支持会话和产品分析套件。每月 1,000 个会话，可使用全部功能并保留 7 天。
  * [Reactflow.com](https://www.reactflow.com/) - 每个站点每天 1,000 次页面浏览、3 个热力图、3 个组件和免费缺陷跟踪。
  * [smartlook.com](https://www.smartlook.com/) - Web 和移动应用免费套餐，每月 1,500 个会话、3 个热力图、1 个漏斗和 1 个月数据历史。
  * [UXtweak.com](https://www.uxtweak.com/) - 记录并查看访客如何使用网站或应用，小型项目可永久免费使用。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="international-mobile-number-verification-api-and-sdk"></a>
## 国际手机号码验证 API 与 SDK

<details>
<summary>展开 / 收起服务列表</summary>

  * [numverify](https://numverify.com/) - 全球电话号码验证和查询 JSON API，每月 100 次 API 请求。
  * [veriphone](https://veriphone.io/) - 免费、快速、可靠的全球电话号码验证 JSON API，每月 1,000 次请求。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="payment-and-billing-integration"></a>
## 支付与计费集成

<details>
<summary>展开 / 收起服务列表</summary>

  * [Adapty.io](https://adapty.io/) - 一站式方案，提供开源 SDK，可在 iOS、Android、React Native、Flutter、Unity 或 Web 应用中集成移动应用内订阅。每月收入不超过 10,000 美元时免费。
  * [AllRatesToday](https://allratestoday.com) - 150 多种货币的实时中间市场汇率，提供官方 JavaScript、Python 和 PHP SDK。免费套餐每月 300 次 HTTPS 请求。
  * [Codex](https://www.codex.io) - 实时加密货币和预测市场数据 API，提供价格、图表、交易、钱包余额和趋势数据。免费层每月提供 10000 次请求，需要使用信用卡或加密货币进行验证。
  * [Churnkey](https://churnkey.co) - 面向订阅业务的取消流程（开源）、流失指标和收入分析，永久免费。
  * [CoinMarketCap](https://coinmarketcap.com/api/) - 提供加密货币市场数据，包括最新加密货币与法币汇率，免费套餐每月 10,000 调用积分。
  * [Currencyapi](https://currencyapi.com) - 免费货币转换和汇率数据 API，个人使用每月 300 次请求，每分钟 10 次。
  * [CurrencyApi](https://currencyapi.net/) - 以 JSON 和 XML 提供法币与加密货币实时汇率，免费套餐每月 1,250 次 API 请求。
  * [CurrencyFreaks](https://currencyfreaks.com/) - 提供当前和历史汇率，免费 DEVELOPER 方案每月 1,000 次请求。
  * [currencylayer](https://currencylayer.com/) - 面向企业的可靠汇率和货币转换服务，每月 100 次 API 请求免费。
  * [exchangerate-api.com](https://www.exchangerate-api.com) - 易用的货币转换 JSON API，免费套餐每天更新一次，每月最多 1,500 次请求。
  * [Exchange Rate API](https://exchange-rateapi.com) - 160 多种货币的实时汇率，60 秒更新并提供官方 SDK，免费套餐每月 300 次请求。
  * [FraudLabsPRO](https://www.fraudlabspro.com) - 帮助商家防止支付欺诈和拒付，免费 Micro 方案每月 500 次查询。
  * [FxRatesAPI](https://fxratesapi.com) - 提供实时和历史汇率，免费套餐要求署名。
  * [Moesif API Monetization](https://www.moesif.com/) - 通过按用量计费从 API 创收，可连接 Stripe、Chargebee 等，免费套餐每月 30,000 个事件。
  * [ParityVend](https://www.ambeteco.com/ParityVend/) - 根据访客位置自动调整价格，利用购买力平价拓展全球业务和新市场。免费方案每月 7,500 次 API 请求。
  * [Qonversion](https://qonversion.io/) - 一体化跨平台订阅管理，提供分析、A/B 测试、Apple Search Ads、远程配置和增长工具，以优化应用内购买与商业化。兼容 iOS、Android、React Native、Flutter、Unity、Cordova、Stripe 和 Web；每月跟踪收入不超过 10,000 美元时免费。
  * [RevenueCat](https://www.revenuecat.com/) - 面向 iOS 和 Android 应用内购买及订阅的托管后端，每月跟踪收入不超过 2,500 美元时免费。
  * [vatlayer](https://vatlayer.com/) - 即时 VAT 号码验证和欧盟 VAT 税率 API，每月 100 次 API 请求免费。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="docker-related"></a>
## Docker 相关

<details>
<summary>展开 / 收起服务列表</summary>

  * [Appish](https://appi.sh/) - 只需 Docker Push 即可托管演示容器，免费套餐含 1 个 Slot，每次会话 2 小时。
  * [Container Registry Service](https://container-registry.com/) - 基于 Harbor 的容器管理方案，免费套餐为私有仓库提供 1GB 存储。
  * [Docker Hub](https://hub.docker.com) - 1 个免费私有仓库和无限公开仓库，用于构建和存储 Docker 镜像。
  * [quay.io](https://quay.io/) - 构建和存储容器镜像，免费公开仓库数量不限。
  * [ttl.sh](https://ttl.sh/) - 匿名且临时的 Docker 镜像注册表。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="dev-blogging-sites"></a>
## 开发者博客平台

<details>
<summary>展开 / 收起服务列表</summary>

  * [AyeDot](https://ayedot.com/) - 以现代多媒体短篇 Miniblog 形式免费向世界分享想法、知识和故事。
  * [BearBlog](https://bearblog.dev/) - 极简、由 Markdown 驱动的博客和网站构建器。
  * [Dev.to](https://dev.to/) - 程序员分享想法并互相帮助成长的平台。
  * [Hashnode](https://hashnode.com/) - 面向开发者的省心博客软件。
  * [Medium](https://medium.com/) - 更深入地思考和分享你在意的主题。
  * [JustBlogged](https://justblogged.com) - 免费博客平台，支持自定义域名并提供快速全球访问。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="commenting-platforms"></a>
## 评论平台

<details>
<summary>展开 / 收起服务列表</summary>

  * [GraphComment](https://graphcomment.com/) - 评论平台，帮助你从网站受众中建立活跃社区。
  * [IntenseDebate](https://intensedebate.com/) - 面向 WordPress、Tumblr、Blogger 等多种网站平台的功能丰富评论系统。
  * [Remarkbox](https://www.remarkbox.com/) - 开源托管评论平台，可按能力付费，基础方案为“由 1 名管理员完全控制少量域名的行为与外观”。
  * [Utterances](https://utteranc.es/) - 基于 GitHub Issue 构建的轻量评论组件，可将 GitHub Issue 用作博客评论、Wiki 页面评论等。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="screenshot-apis"></a>
## 截图 API

<details>
<summary>展开 / 收起服务列表</summary>

  * [ApiFlash](https://apiflash.com) - 基于 AWS Lambda 和 Chrome 的截图 API，支持整页截图、捕获时机和视口尺寸设置。
  * [microlink.io](https://microlink.io/) - 将任意网站转换为元标签规范化、美观链接预览、抓取或截图即服务等数据，每天免费 50 次请求。
  * [PhantomJsCloud](https://PhantomJsCloud.com) - 浏览器自动化和页面渲染，免费套餐每天最多 500 页，自 2017 年起提供免费套餐。
  * [screenshotbase.com](https://screenshotbase.com) - 每月 300 张免费截图，可从任意 URL 截图，快速、免费且可扩展。
  * [screenshotlayer.com](https://screenshotlayer.com/) - 高度自定义地捕获任意网站快照，每月 100 张免费。
  * [screenshotmachine.com](https://www.screenshotmachine.com/) - 每月捕获 100 张快照，支持 PNG、GIF 和 JPG，也支持整页而非仅首页截图。
  * [Screenshot Scout](https://screenshotscout.com/) - 面向开发者的截图 API，只需一次请求即可从任意 URL 获得干净、可用于生产的截图。免费方案每月 200 张，永久有效。
  * [Shotpipe](https://shotpipe.io) - 面向静态站点的截图和 Open Graph 图片 API，免费套餐每月 100 次渲染，无需信用卡，缓存渲染免费。
  * [SnapAPI](https://snapapi.pics) - 截图、视频录制、PDF 生成和 Web 数据提取 API，免费方案每月 200 张截图。
  * [thumbnail.ws](https://thumbnail.ws) - 生成网站缩略图的 API，每月 1,000 次免费请求。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="flutter-related-and-building-ios-apps-without-mac"></a>
## Flutter 相关及无 Mac 构建 iOS 应用

<details>
<summary>展开 / 收起服务列表</summary>

  * [CodeMagic](https://codemagic.io/) - 完全托管和管理的移动应用 CI/CD，可通过 GUI 构建、测试和部署。免费套餐每月 500 分钟，并提供 2.3GHz、8GB RAM 的 Mac Mini 实例。
  * [FlutLab](https://flutlab.io/) - 现代 Flutter 在线 IDE，用于创建、调试和构建跨平台项目，可使用 Flutter 构建 iOS（无需 Mac）和 Android 应用。
  * [FlutterFlow](https://flutterflow.io/) - 基于浏览器的拖放界面，用 Flutter 构建移动应用。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="privacy-management"></a>
## 隐私管理

<details>
<summary>展开 / 收起服务列表</summary>

  * [Bearer](https://www.bearer.sh/) - 通过审计和持续工作流实施隐私设计，帮助组织遵守 GDPR 等法规。免费套餐仅限小团队和 SaaS 版本。
  * [Concord](https://www.concord.tech/) - 完整数据隐私平台，包含同意管理、隐私请求处理（DSAR）和数据映射。免费套餐含核心同意管理功能，并为经验证的开源项目免费提供更高级方案。
  * [Cookiefirst](https://cookiefirst.com/) - Cookie 横幅、审计和多语言同意管理方案，免费套餐含 1 次扫描和 1 个横幅。
  * [Iubenda](https://www.iubenda.com/) - 隐私/Cookie 政策及同意管理，免费套餐提供有限隐私政策、Cookie 政策和 Cookie 横幅。
  * [Ketch](https://www.ketch.com/) - 同意管理和隐私框架工具，免费套餐提供大多数功能，但访客数量有限。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="miscellaneous"></a>
## 其他

<details>
<summary>展开 / 收起服务列表</summary>

  * [BinShare.net](https://binshare.net) - 创建并分享代码或二进制文件，可生成适合 Twitter/Facebook 发布的美观图片，也可生成供聊天或论坛使用的链接。
  * [Blynk](https://blynk.io) - 用于控制、构建和评估 IoT 设备的 SaaS 与 API。免费 Developer 方案含 5 台设备、免费云和数据存储，并提供移动应用。
  * [cron-job.org](https://cron-job.org) - 在线 Cron Job 服务，作业数量不限且免费。
  * [Cronhooks](https://cronhooks.io/) - 安排一次性或重复 Webhook，免费方案允许 5 个临时计划。
  * [datelist.io](https://datelist.io) - 在线预订/预约排期系统，每月最多 5 次预订免费，含 1 个日历。
  * [FOSSA](https://fossa.com/) - 面向第三方代码、许可证合规和漏洞的可扩展端到端管理。
  * [Hook Relay](https://www.hookrelay.dev/) - 无需处理队列、退避重试和日志即可为应用添加 Webhook 支持。免费方案每天 100 次投递、14 天保留和 3 个 Hook 端点。
  * [Hosting Checker](https://hostingchecker.co) - 查询任意域名、网站或 IP 的 ASN、ISP、位置等托管信息，并提供多种托管及 DNS 工具。
  * [newreleases.io](https://newreleases.io/) - 通过邮件、Slack、Telegram、Discord 和自定义 Webhook 接收 GitHub、GitLab、Bitbucket、Python PyPI、Java Maven、Node.js NPM/Yarn、Ruby Gems、PHP Packagist、.NET NuGet、Rust Cargo 和 Docker Hub 新版本通知。
  * [PDFMonkey](https://www.pdfmonkey.io/) - 在仪表板中管理 PDF 模板，通过 API 传入动态数据并下载 PDF，每月免费 300 份文档。
  * [Pika Code Screenshots](https://pika.style/templates/code-image) - 通过扩展从代码片段和 VS Code 创建美观、可自定义的截图。
  * [QuickType.io](https://quicktype.io/) - 从 JSON、Schema 和 GraphQL 快速自动生成 Model/Class/Type/Interface 和序列化器，便于在任意语言中快速安全地处理数据，将 JSON 转换为美观、类型安全的代码。
  * [readme.com](https://readme.com/) - 轻松创建美观文档，开源项目免费。
  * [redirect.pizza](https://redirect.pizza/) - 轻松管理支持 HTTPS 的重定向，免费方案含 10 个来源和每月 100,000 次访问。
  * [redirection.io](https://redirection.io/) - 面向企业、营销和 SEO 的 HTTP 重定向管理 SaaS。
  * [redirs.com](https://www.redirs.com/) — 简单域名重定向，支持自动 SSL、分析和 URL 路径转发，基础使用免费（最多 5 个域名）。
  * [RedirHub](https://www.redirhub.com/) - API 优先的 URL 重定向基础设施，提供自定义 Nameserver、边缘网络、HTTPS 和主动链接监控。免费方案含 2 个主机名、每月 100,000 次请求、自动 SSL、路径转发和 REST API。
  * [ReqBin](https://reqbin.com/) - 在线发送 HTTP 请求，支持 GET、POST、PUT、DELETE、HEAD 等常用方法、Header 和 Token 认证，并提供基础登录系统保存请求。
  * [Smartcar API](https://smartcar.com) - 车辆 API，可获取位置、油箱、电量、里程，并执行车门解锁/上锁等操作。
  * [Sunrise and Sunset](https://sunrisesunset.io/api/) - 根据经纬度获取日出和日落时间。
  * [superfeedr.com](https://superfeedr.com/) - 实时兼容 PubSubHubbub 的 Feed、导出和分析，免费版自定义能力较少。
  * [SurveyMonkey.com](https://www.surveymonkey.com) - 创建在线调查并在线分析结果，免费方案每个调查仅支持 10 个问题和 100 条响应。
  * [SYNCDATE](https://syncdate.app) - 双向 Google Calendar 同步，免费套餐支持 2 个账号和无限事件。
  * [UUID Generator](https://newuuid.com/) - 即时生成企业级 UUID v1、UUID v4、UUID v7、GUID、Nil UUID、CUID v1/v2、NanoID 和 ULID。
  * [Versionfeeds](https://versionfeeds.com) - 为常用软件版本创建自定义 RSS Feed，将编程语言、库和工具的最新版本集中到一个 Feed，前 3 个 Feed 免费。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="remote-desktop-tools"></a>
## 远程桌面工具

<details>
<summary>展开 / 收起服务列表</summary>

  * [Parsec](https://parsec.app/) - 个人使用可免费安装在无限数量的设备上，单台设备同时最多允许 20 个连接（适合游戏或低延迟工作）。
  * [AnyDesk](https://anydesk.com) - 3 台设备免费，会话数量和时长不限。
  * [Getscreen.me](https://getscreen.me) - 2 台设备免费，会话数量和时长不限。
  * [RemSupp](https://remsupp.com) - 按需支持和设备永久访问，每天 2 个会话免费。
  * [RustDesk](https://rustdesk.com/) - 面向所有人的开源虚拟/远程桌面基础设施。

**[⬆️ 返回顶部](#table-of-contents)**

</details>

<a id="other-free-resources"></a>
## 其他免费资源

<details>
<summary>展开 / 收起服务列表</summary>

  * [get.localhost.direct](https://get.localhost.direct) - 更好用的 `*.localhost.direct` 通配符公共 CA 签名 SSL 证书，适合支持子域名的 localhost 开发。
  * [GitHub Education](https://education.github.com/pack) - 面向学生的免费服务集合，需要注册。
  * [Glob tester](https://globster.xyz/) - 用于设计和测试 Glob Pattern 的网站，并提供学习资源。
  * [Killer Coda](https://killercoda.com/) - 浏览器中的交互式 Playground，用于学习 Linux、Kubernetes、容器、编程、DevOps 和网络。
  * [Microsoft 365 Developer Program](https://developer.microsoft.com/microsoft-365/dev-program) - 免费获得构建 Microsoft 365 平台解决方案所需的 Sandbox、工具和其他资源。订阅为 90 天的 [Microsoft 365 E5 Subscription](https://www.microsoft.com/microsoft-365/enterprise/e5)（不含 Windows），可续期；若持续活跃开发（通过遥测数据和算法衡量）会自动续订。
  * [MySQL Visual Explain](https://mysqlexplain.com) - 易于理解的免费 MySQL EXPLAIN 输出可视化工具，用于优化慢查询。
  * [RedHat for Developers](https://developers.redhat.com) - 仅面向开发者免费访问 RHEL、OpenShift、CodeReady 等 Red Hat 产品，仅提供个人方案，并有免费电子书参考。
  * [sandbox.httpsms.com](https://sandbox.httpsms.com) - 免费收发测试短信。
  * [SimpleBackups.com](https://simplebackups.com/) - 服务器和数据库（MySQL、PostgreSQL、MongoDB）备份自动化服务，直接存储到 AWS、DigitalOcean、Backblaze 等云存储，免费方案支持 1 个备份。
  * [SimpleRestore](https://simplerestore.io) - 轻松恢复 MySQL 备份，无需代码或服务器即可还原到任意远程数据库。
  * [SnapShooter](https://snapshooter.com/) - 面向 DigitalOcean、AWS、LightSail、Hetzner 和 Exoscale 的备份方案，并支持将数据库、文件系统和应用直接备份到 S3 兼容存储。免费方案每天备份 1 个资源。

**[⬆️ 返回顶部](#table-of-contents)**

</details>
