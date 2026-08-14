# source-collection

把我曾经 fork 过的上游项目做成一份公开收藏：说明每个项目是什么、有什么价值，并对适合归档的上游做浅克隆（`git clone --depth=1`，使用上游默认分支）后打成 zip。

仓库：https://github.com/suifei/source-collection

## 怎么用

- 目录见下方。每条都有上游地址、默认分支、一句话说明。
- 体积合适的项目在 [`archives/`](archives/) 里有 zip（上游默认分支、depth=1）。
- 太大的项目不放 zip（GitHub 单文件 100MB 限制），直接用上游官方打包地址。
- 敏感仓库**不放进本仓库的 zip**，fork 也保留在账号上，不删除。

## 保留不删的 forks

这些 fork 继续留在 [suifei](https://github.com/suifei?tab=repositories&type=fork)，不归档 zip，也不取消 fork：

| Fork | 原因 |
| --- | --- |
| [claude-code](https://github.com/suifei/claude-code) | 标注为 Anthropic 专有源码快照 |
| [idc_70_client](https://github.com/suifei/idc_70_client) | 疑似游戏客户端源码 |
| [EggShell](https://github.com/suifei/EggShell) | 远程管理 / RAT 类工具 |
| [FiddlerEverywhereMockScripts](https://github.com/suifei/FiddlerEverywhereMockScripts) | 破解 / 绕过类脚本 |
| [bagbak](https://github.com/suifei/bagbak) | iOS 应用解密 |
| [SuperDllHijack](https://github.com/suifei/SuperDllHijack) | DLL 劫持 |

私有 fork `henduohao` 也不放进这个公开仓库。

## 目录

### AI / LLM

| 项目 | 上游默认分支 | 是什么 | 价值 |
| --- | --- | --- | --- |
| [langflow](https://github.com/suifei/langflow) | 上游现为 `main`（fork 当时是 `dev`） | LangChain 可视化编排 UI | 快速搭 Agent / RAG 流程，不用先写一堆胶水代码 |
| [ColossalAI](https://github.com/suifei/ColossalAI) | main | 大模型训练推理加速框架 | 把大模型训练成本打下来 |
| [gpt_academic](https://github.com/suifei/gpt_academic) | master | 论文阅读/润色向的 LLM 图形界面 | 学术场景开箱即用 |
| [WebGLM](https://github.com/suifei/WebGLM) | main | 联网增强问答（KDD 2023） | 研究检索增强问答 |
| [RWKV-Runner](https://github.com/suifei/RWKV-Runner) | master | RWKV 一键启动，兼容 OpenAI API | 本地跑 RWKV 最省事的方式之一 |
| [fastllm](https://github.com/suifei/fastllm) | master | 纯 C++ 全平台 LLM 推理 | 端侧 / 低资源部署 |
| [chatglm.cpp](https://github.com/suifei/chatglm.cpp) | main | ChatGLM 的 C++ 实现 | 本地推理 ChatGLM |
| [chatglm-6b-api](https://github.com/suifei/chatglm-6b-api) | main | ChatGLM-6B HTTP API | 把本地 GLM 接到现有工具 |
| [chatglm-openai-api](https://github.com/suifei/chatglm-openai-api) | main | ChatGLM 的 OpenAI 风格 API | 复用已有 OpenAI 客户端 |
| [DocumentSearch](https://github.com/suifei/DocumentSearch) | main | sentence-transformers + ChatGLM 文档搜索 | 本地知识库检索 |
| [vector-vein](https://github.com/suifei/vector-vein) | main | 无代码 AI 工作流 | 可视化搭流水线 |
| [Vicuna-LangChain](https://github.com/suifei/Vicuna-LangChain) | main | Vicuna + 本地知识库 | 中英文档问答 |
| [obsidian-ollama](https://github.com/suifei/obsidian-ollama) | main | Obsidian 里接 Ollama | 笔记软件本地 LLM |
| [OpenSource-Ai-Glasses](https://github.com/suifei/OpenSource-Ai-Glasses) | main | 开源 AI 眼镜 | 硬件 + 模型一体参考 |
| [auto-phone-scheduler](https://github.com/suifei/auto-phone-scheduler) | main | 基于 Open-AutoGLM 的手机定时任务 | 让 AI 重复做手机操作 |
| [autoglm-go](https://github.com/suifei/autoglm-go) | master | Open-AutoGLM 的 Go 重写 | 同一套自动化，Go 实现 |
| [gpt4free](https://github.com/suifei/gpt4free) | main | 聚合第三方模型接口 | **不提供 zip**（未授权接口聚合） |

### 中文 NLP / OCR

| 项目 | 上游默认分支 | 是什么 | 价值 |
| --- | --- | --- | --- |
| [JioNLP](https://github.com/suifei/JioNLP) | master | 中文 NLP 工具包 | 分词、信息抽取等日常中文处理 |
| [ddddocr](https://github.com/suifei/ddddocr) | master | 通用验证码 OCR | 验证码识别库（公开上游，目录收录，zip 从简） |
| [ocr_api_server](https://github.com/suifei/ocr_api_server) | main | ddddocr 的最简 API / Docker | 把 OCR 变成服务 |
| [DdddOcrLib](https://github.com/suifei/DdddOcrLib) | master | ddddocr 的 C++ 静态库 | 非 Python 环境接入 |

### 编辑器 / 字体 / 资料

| 项目 | 上游默认分支 | 是什么 | 价值 |
| --- | --- | --- | --- |
| [marktext](https://github.com/suifei/marktext) | develop | 跨平台 Markdown 编辑器 | 轻量、所见即所得 |
| [LxgwWenKai](https://github.com/suifei/LxgwWenKai) | main | 霞鹜文楷（开源中文字体） | 免费可商用中文字体 |
| [free-programming-books](https://github.com/suifei/free-programming-books) | master | 免费编程书清单 | 找书入口 |
| [ChinaTextbook](https://github.com/suifei/ChinaTextbook) | master | 人教版数学教材整理 | 教材检索（体积大，只给上游链接） |
| [dynamic-analysis](https://github.com/suifei/dynamic-analysis) | master | 动态分析工具清单 | 按语言找工具 |
| [awesome-monogame](https://github.com/suifei/awesome-monogame) | master | MonoGame 资源列表 | 做 MonoGame 时少搜一轮 |
| [acore_doc](https://github.com/suifei/acore_doc) | master | AzerothCore 中文文档 | 魔兽私服开发文档 |

### 游戏 / 嵌入式 / 工业

| 项目 | 上游默认分支 | 是什么 | 价值 |
| --- | --- | --- | --- |
| [jynew](https://github.com/suifei/jynew) | main | 金庸群侠传 3D 重制 | 开源武侠 RPG 参考 |
| [jynew_art](https://github.com/suifei/jynew_art) | main | 上述项目的美术工程 | 配套资源 |
| [ArrowLegend](https://github.com/suifei/ArrowLegend) | master | 弓箭传说类项目 | 小游戏参考 |
| [rathena_npc_translate](https://github.com/suifei/rathena_npc_translate) | master | rAthena NPC 脚本汉化 | RO 私服中文脚本 |
| [eptaora](https://github.com/suifei/eptaora) | main | ATtiny84 双步进时钟驱动 | 自制时钟固件 |
| [holo_clock](https://github.com/suifei/holo_clock) | master | 无表面全息钟 | 硬件玩具 |
| [PyBot_Scara](https://github.com/suifei/PyBot_Scara) | main | 廉价 Arduino 的 SCARA 机械臂 | 桌面机械臂 |
| [matiec](https://github.com/suifei/matiec) | default | IEC 61131-3 编译器 | PLC 语言工具链 |

### 网络 / 下载 / 通讯

| 项目 | 上游默认分支 | 是什么 | 价值 |
| --- | --- | --- | --- |
| [annie](https://github.com/suifei/annie) | master | 视频下载器（现多称 lux） | 命令行下视频 |
| [xdm](https://github.com/suifei/xdm) | master | 下载加速 / 视频下载 | 桌面下载器 |
| [mirai](https://github.com/suifei/mirai) | master | QQ 机器人 / 协议库 | 做 QQ 机器人 |
| [wecom](https://github.com/suifei/wecom) | master | 企业微信（fork 自 LinkWeChat） | 企微 SCRM 参考 |
| [new-pac](https://github.com/suifei/new-pac) | master | PAC / 代理相关 | 代理配置 |
| [Xray_onekey](https://github.com/suifei/Xray_onekey) | main | Xray 一键安装 | 快速搭节点 |
| [V2rayU](https://github.com/suifei/V2rayU) | rm | macOS V2Ray 客户端 | Mac 上用 |
| [V2Ray-Desktop](https://github.com/suifei/V2Ray-Desktop) | master | 跨平台代理客户端 | 桌面 GUI |
| [IOS_SSR_SS_V2RAY](https://github.com/suifei/IOS_SSR_SS_V2RAY) | master | iOS 小火箭离线包说明 | 仅作记录 |
| [miner-proxy](https://github.com/suifei/miner-proxy) | master | 矿机与矿池中转 | 挖矿链路加密 |
| [ios-bash-streaming](https://github.com/suifei/ios-bash-streaming) | master | 几行 bash 做 iOS 投屏 | 快速投屏 |

### 开发工具

| 项目 | 上游默认分支 | 是什么 | 价值 |
| --- | --- | --- | --- |
| [gox](https://github.com/suifei/gox) | master | Go 交叉编译 | 一条命令出多平台二进制 |
| [libc](https://github.com/suifei/libc) | musl-c | 把流行 libc 迁到 Go | Go 里用 C 库接口 |
| [bootout](https://github.com/suifei/bootout) | master | layoutit.com 离线中文版 | Bootstrap 可视化布局 |
| [orly](https://github.com/suifei/orly) | master | O'RLY 动物书封面生成 | 恶搞封面 |
| [frida_go](https://github.com/suifei/frida_go) | main | Frida 的 Go 绑定 | 用 Go 写 Frida |
| [PbdViewer](https://github.com/suifei/PbdViewer) | main | PowerBuilder 反编译 | 看老 PB 工程 |
| [powerrebuilder](https://github.com/suifei/powerrebuilder) | main | PB 应用迁到现代 Web | 遗产系统迁移 |
| [Il2CppDumper](https://github.com/suifei/Il2CppDumper) | master | Unity il2cpp 分析 | 游戏逆向入门常见工具 |
| [Grapefruit](https://github.com/suifei/Grapefruit) | master | iOS 运行时观察（原 Passionfruit） | 看 iOS 进程 |
| [aurora](https://github.com/suifei/aurora) | master | 基于 Frida 的 Web PoC | Frida 网页壳 |
| [frida-snippets](https://github.com/suifei/frida-snippets) | master | Frida 示例片段 | 抄例子 |
| [r0chrome](https://github.com/suifei/r0chrome) | master | Chrome 相关研究 | 浏览器研究 |
| [iOS](https://github.com/suifei/iOS) | master | iOS 渗透常用工具清单 | 工具索引 |
| [mystrong](https://github.com/suifei/mystrong) | main | （页面描述为空，待补） | 待补 |

### 其它脚本 / 活动向

| 项目 | 上游默认分支 | 是什么 | 价值 |
| --- | --- | --- | --- |
| [jd_seckill](https://github.com/suifei/jd_seckill) | master | 京东茅台抢购脚本 | 历史项目，仅作记录 |
| [dm-ticket](https://github.com/suifei/dm-ticket) | main | 大麦网自动购票 | 历史项目，仅作记录 |

## 归档约定

1. 只克隆**上游**默认分支，`git clone --depth=1`。
2. 去掉 `.git` 后打 zip，文件名：`{owner}__{repo}__{branch}.zip`。
3. 下列仓库不提供 zip：保留的敏感 forks、私有仓库、以及体积明显超过 GitHub 单文件限制的项目。
4. 归档完成后，除「保留不删」名单外，其余 forks 会从账号上删除。

上游精确地址和 zip 清单会随抓取结果继续补全。
