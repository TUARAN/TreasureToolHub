# 《新宣【宝藏工具】，别重复造轮子！优秀工具帮你提效》

## 🧭 写在前面：

"人类的伟大，不仅在于思考，更在于创造工具与善用工具。"对程序员来说，这句话尤为真实——很多你想造的轮子，别人已经造过、甚至打磨得非常成熟。整理这份宝藏工具推荐，就是为了帮你少踩坑、多提效，把时间花在真正创造价值的地方。

这期推荐的工具，涵盖了插件开发、系统消息推送、词库采集、图像识番、文本处理等多个方向，不论你是前端、后端、AI 工程师还是 DevOps，都能找到对口的效率神器。

📌 **推荐大家 Star 项目仓库：**  
👉 [https://github.com/TUARAN/TreasureToolHub](https://github.com/TUARAN/TreasureToolHub)

📚 **查看往期推荐合集专栏：**  
👉 掘金专栏地址：[https://juejin.cn/column/7516429208533499931](https://juejin.cn/column/7516429208533499931)

---

## 🔧 宝藏工具推荐

### 🥬 Excel-Plugin-Template - Excel 插件开发模板，内置 AI 批量标注功能

![Excel 插件模板项目展示](https://raw.githubusercontent.com/tuaran/TreasureToolHub/master/images/2025/06/photo_excel_plugin.png)

🔗 GitHub 地址：[Excel-Plugin-Template](https://github.com/90le/Excel-Plugin-Template)

一个专为 Excel 插件开发设计的模板工程，基于 DTI_Tool.AddIn 框架，集成插件生命周期管理、日志系统、自动更新机制等功能，开发者拿来就能上手构建自己的 Office 助手。内置 50+ AI 提示词示例，支持批量数据清洗、标注与比对，特别适合需要处理大量表格或构建自动化插件的工程师。

---

### 💬 WePush - 企业微信消息推送机器人，FastAPI 构建，稳定可靠

![WePush 推送展示图](https://raw.githubusercontent.com/tuaran/TreasureToolHub/master/images/2025/06/photo_wepush.jpg)

🔗 GitHub 地址：[WePush](https://github.com/friend-nicen/wepush)

WePush 利用 PC 微信窗口模拟点击方式，实现对个人微信好友、群聊自动发送消息。后端基于 FastAPI + Redis 消息队列，支持异步并发推送，可作为系统告警或通知中台。相比第三方企业微信接口，它无须申请服务号或 API 权限，部署即用，极大降低接入门槛，尤其适合中小企业或个人开发者。

---

### 📖 vocabulary-corpus - 超 4 万条英语词汇，结构化 JSON 输出

![词库工具展示](https://raw.githubusercontent.com/tuaran/TreasureToolHub/master/images/2025/06/photo_vocab.jpg)

🔗 GitHub 地址：[vocabulary-corpus](https://github.com/hubingkang/vocabulary-corpus)

这是一个面向教育类工具开发者、英语学习软件作者的语料采集工具。支持从词表中自动提取音标、释义、词源、搭配等字段，输出标准化 JSON。支持滑动限速、断点续传等功能，适合构建单词卡片、AI 学习引擎或 NLP 训练语料。

---

### 💤 AnimeTrace - 动漫图像识别神器，在线识番即用

![AnimeTrace 在线识图](https://raw.githubusercontent.com/tuaran/TreasureToolHub/master/images/2025/06/photo_anime.jpg)

🔗 项目地址：[AnimeTrace](https://www.animetrace.com/)

只需上传一张动漫或 Galgame 图片，AnimeTrace 就能识别出图中角色、作品名，甚至相关 CP。这背后集成了多种 AI 模型（低精度 + 高精度双通道），响应快、准确率高，是二次元开发者、爬虫工程师、动画平台做图文匹配的得力工具。

---

### 📂 FolderSize - Windows 文件夹体积可视化工具，直观又高效

![FolderSize 可视化效果](https://raw.githubusercontent.com/tuaran/TreasureToolHub/master/images/2025/06/photo_folder.jpg)

🔗 GitHub 地址：[FolderSize](https://github.com/mrange/FolderSize)

在整理磁盘空间时，有没有感觉"到底哪个文件夹占得多"一头雾水？FolderSize 用树状结构图展示各目录大小占比，像极了 WinDirStat 的现代简洁版本。适合开发者、运维人员在本地磁盘或代码仓库清理时高效判断"罪魁祸首"。

---


### 🛠️ better-commits - Git Commit 提示词增强器，提升协作规范

![Better Commits 提交展示](https://raw.githubusercontent.com/tuaran/TreasureToolHub/master/images/2025/06/photo_commit.png)

🔗 GitHub 地址：[better-commits](https://github.com/Everduin94/better-commits)

你还在随便写 commit 吗？这个 CLI 工具让你在提交代码前，通过交互式提示选择类型（fix/feat/docs）、范围、描述等信息，生成符合 Conventional Commits 规范的提交说明。适用于团队协作、CI 自动化流程，提升代码仓库可读性与一致性。

---

### 🧮 jq - 命令行 JSON 处理神器，DevOps 必备

![jq 使用示意](https://raw.githubusercontent.com/tuaran/TreasureToolHub/master/images/2025/06/photo_jq.png)

🔗 GitHub 地址：[stedolan/jq](https://github.com/stedolan/jq)

jq 是一款轻量、强大的命令行 JSON 解析工具，几乎是所有 DevOps 和后端开发的标配。不论你是处理日志数据、分析接口返回、还是提取结构字段，jq 都可以用简洁语法完成过滤、排序、映射等任务。一次配置，终身提效！

---

## 📘 写在最后

上面这些项目，都是开源社区不断演进出的智慧结晶，适合每一个想要"少走弯路"的开发者。


📬 **获取更多工具推荐与项目实践，请加微信 atar24！** 