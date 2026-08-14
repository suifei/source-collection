# source-collection

曾经 fork 过的项目的**上游**收藏：每条链接都指向源仓库，不是我账号下的 fork。

适合归档的上游已做 `git clone --depth=1`（默认分支）并打成 zip，放在 [`archives/`](archives/)。

完整对照：[UPSTREAMS.md](UPSTREAMS.md) · 打包清单：[archives/MANIFEST.md](archives/MANIFEST.md)

## AI / LLM

| 上游 | 说明 | zip |
| --- | --- | --- |
| [langflow-ai/langflow](https://github.com/langflow-ai/langflow) | LangChain 可视化编排 UI。快速搭 Agent / RAG 流程 | 过大，未收录 |
| [hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI) | 大模型训练推理加速。降低训练成本 | [`hpcaitech__ColossalAI__main.zip`](archives/hpcaitech__ColossalAI__main.zip) |
| [binary-husky/gpt_academic](https://github.com/binary-husky/gpt_academic) | 论文阅读/润色向 LLM 界面。学术场景开箱即用 | [`binary-husky__gpt_academic__master.zip`](archives/binary-husky__gpt_academic__master.zip) |
| [THUDM/WebGLM](https://github.com/THUDM/WebGLM) | 联网增强问答（KDD 2023）。检索增强问答研究 | [`THUDM__WebGLM__main.zip`](archives/THUDM__WebGLM__main.zip) |
| [josStorer/RWKV-Runner](https://github.com/josStorer/RWKV-Runner) | RWKV 一键启动，兼容 OpenAI API。本地跑 RWKV | [`josStorer__RWKV-Runner__master.zip`](archives/josStorer__RWKV-Runner__master.zip) |
| [ztxz16/fastllm](https://github.com/ztxz16/fastllm) | 纯 C++ 全平台 LLM 推理。端侧 / 低资源部署 | [`ztxz16__fastllm__master.zip`](archives/ztxz16__fastllm__master.zip) |
| [li-plus/chatglm.cpp](https://github.com/li-plus/chatglm.cpp) | ChatGLM 的 C++ 实现。本地推理 ChatGLM | [`li-plus__chatglm.cpp__main.zip`](archives/li-plus__chatglm.cpp__main.zip) |
| [xingkaixin/chatglm-6b-api](https://github.com/xingkaixin/chatglm-6b-api) | ChatGLM-6B HTTP API。把本地 GLM 接到现有工具 | [`xingkaixin__chatglm-6b-api__main.zip`](archives/xingkaixin__chatglm-6b-api__main.zip) |
| [ninehills/chatglm-openai-api](https://github.com/ninehills/chatglm-openai-api) | ChatGLM 的 OpenAI 风格 API。复用已有 OpenAI 客户端 | [`ninehills__chatglm-openai-api__main.zip`](archives/ninehills__chatglm-openai-api__main.zip) |
| [yuanzhoulvpi2017/DocumentSearch](https://github.com/yuanzhoulvpi2017/DocumentSearch) | sentence-transformers + ChatGLM 文档搜索。本地知识库检索 | [`yuanzhoulvpi2017__DocumentSearch__main.zip`](archives/yuanzhoulvpi2017__DocumentSearch__main.zip) |
| [AndersonBY/vector-vein](https://github.com/AndersonBY/vector-vein) | 无代码 AI 工作流。可视化搭流水线 | [`AndersonBY__vector-vein__main.zip`](archives/AndersonBY__vector-vein__main.zip) |
| [HaxyMoly/Vicuna-LangChain](https://github.com/HaxyMoly/Vicuna-LangChain) | Vicuna + 本地知识库。中英文档问答 | [`HaxyMoly__Vicuna-LangChain__main.zip`](archives/HaxyMoly__Vicuna-LangChain__main.zip) |
| [hinterdupfinger/obsidian-ollama](https://github.com/hinterdupfinger/obsidian-ollama) | Obsidian 接 Ollama。笔记软件本地 LLM | [`hinterdupfinger__obsidian-ollama__main.zip`](archives/hinterdupfinger__obsidian-ollama__main.zip) |
| [Iam5tillLearning/OpenSource-Ai-Glasses](https://github.com/Iam5tillLearning/OpenSource-Ai-Glasses) | 开源 AI 眼镜。硬件 + 模型参考 | 过大，未收录 |
| [lxzagent/auto-phone-scheduler](https://github.com/lxzagent/auto-phone-scheduler) | 基于 Open-AutoGLM 的手机定时任务。重复手机操作自动化 | [`lxzagent__auto-phone-scheduler__main.zip`](archives/lxzagent__auto-phone-scheduler__main.zip) |
| [ZoroSpace/autoglm-go](https://github.com/ZoroSpace/autoglm-go) | Open-AutoGLM 的 Go 重写。同一套自动化的 Go 实现 | [`ZoroSpace__autoglm-go__master.zip`](archives/ZoroSpace__autoglm-go__master.zip) |
| [xtekky/gpt4free](https://github.com/xtekky/gpt4free) | 聚合第三方模型接口 | 未打包 |
| [ultraworkers/claw-code](https://github.com/ultraworkers/claw-code) | Claude Code 相关源码快照 | 未打包 |

## 中文 NLP / OCR

| 上游 | 说明 | zip |
| --- | --- | --- |
| [dongrixinyu/JioNLP](https://github.com/dongrixinyu/JioNLP) | 中文 NLP 工具包。分词、信息抽取 | [`dongrixinyu__JioNLP__master.zip`](archives/dongrixinyu__JioNLP__master.zip) |
| [sml2h3/ddddocr](https://github.com/sml2h3/ddddocr) | 通用验证码 OCR。公开 OCR 库 | [`sml2h3__ddddocr__master.zip`](archives/sml2h3__ddddocr__master.zip) |
| [sml2h3/ddddocr-fastapi](https://github.com/sml2h3/ddddocr-fastapi) | ddddocr 最简 API / Docker。把 OCR 变成服务 | [`sml2h3__ddddocr-fastapi__main.zip`](archives/sml2h3__ddddocr-fastapi__main.zip) |
| [sml2h3/DdddOcrLib](https://github.com/sml2h3/DdddOcrLib) | ddddocr 的 C++ 静态库。非 Python 环境接入 | [`sml2h3__DdddOcrLib__master.zip`](archives/sml2h3__DdddOcrLib__master.zip) |

## 编辑器 / 字体 / 资料

| 上游 | 说明 | zip |
| --- | --- | --- |
| [marktext/marktext](https://github.com/marktext/marktext) | 跨平台 Markdown 编辑器。轻量所见即所得 | [`marktext__marktext__develop.zip`](archives/marktext__marktext__develop.zip) |
| [lxgw/LxgwWenKai](https://github.com/lxgw/LxgwWenKai) | 霞鹜文楷（开源中文字体）。免费可商用中文字体 | 过大，未收录 |
| [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 免费编程书清单。找书入口 | [`EbookFoundation__free-programming-books__main.zip`](archives/EbookFoundation__free-programming-books__main.zip) |
| [TapXWorld/ChinaTextbook](https://github.com/TapXWorld/ChinaTextbook) | 人教版数学教材整理 | 未打包 |
| [analysis-tools-dev/dynamic-analysis](https://github.com/analysis-tools-dev/dynamic-analysis) | 动态分析工具清单。按语言找工具 | [`analysis-tools-dev__dynamic-analysis__master.zip`](archives/analysis-tools-dev__dynamic-analysis__master.zip) |
| [aloisdeniel/awesome-monogame](https://github.com/aloisdeniel/awesome-monogame) | MonoGame 资源列表。做 MonoGame 时少搜一轮 | [`aloisdeniel__awesome-monogame__master.zip`](archives/aloisdeniel__awesome-monogame__master.zip) |
| [najoast/acore_doc](https://github.com/najoast/acore_doc) | AzerothCore 中文文档。魔兽私服开发文档 | [`najoast__acore_doc__master.zip`](archives/najoast__acore_doc__master.zip) |

## 游戏 / 嵌入式 / 工业

| 上游 | 说明 | zip |
| --- | --- | --- |
| [jynew/jynew](https://github.com/jynew/jynew) | 金庸群侠传 3D 重制。体积过大，只给上游 | 过大，未收录 |
| [jynew/jynew_art](https://github.com/jynew/jynew_art) | 上述项目的美术工程。体积过大，只给上游 | 过大，未收录 |
| [Lee7goal/ArrowLegend](https://github.com/Lee7goal/ArrowLegend) | 弓箭传说类项目。小游戏参考 | [`Lee7goal__ArrowLegend__master.zip`](archives/Lee7goal__ArrowLegend__master.zip) |
| [najoast/rathena_npc_translate](https://github.com/najoast/rathena_npc_translate) | rAthena NPC 脚本汉化。RO 私服中文脚本 | [`najoast__rathena_npc_translate__master.zip`](archives/najoast__rathena_npc_translate__master.zip) |
| [ukhov79/eptaora](https://github.com/ukhov79/eptaora) | ATtiny84 双步进时钟驱动。自制时钟固件 | [`ukhov79__eptaora__main.zip`](archives/ukhov79__eptaora__main.zip) |
| [ekaggrat/holo_clock](https://github.com/ekaggrat/holo_clock) | 无表面全息钟。硬件玩具 | [`ekaggrat__holo_clock__master.zip`](archives/ekaggrat__holo_clock__master.zip) |
| [somorastik/PyBot_Scara](https://github.com/somorastik/PyBot_Scara) | 廉价 Arduino 的 SCARA 机械臂。桌面机械臂 | [`somorastik__PyBot_Scara__main.zip`](archives/somorastik__PyBot_Scara__main.zip) |
| [beremiz/matiec](https://github.com/beremiz/matiec) | IEC 61131-3 编译器。PLC 语言工具链 | [`beremiz__matiec__default.zip`](archives/beremiz__matiec__default.zip) |
| [android-crack/idc_70_client](https://github.com/android-crack/idc_70_client) | 游戏客户端相关源码 | 未打包 |

## 网络 / 下载 / 通讯

| 上游 | 说明 | zip |
| --- | --- | --- |
| [iawia002/lux](https://github.com/iawia002/lux) | 视频下载器（现名 lux）。命令行下视频 | [`iawia002__lux__master.zip`](archives/iawia002__lux__master.zip) |
| [subhra74/xdm](https://github.com/subhra74/xdm) | 下载加速 / 视频下载。桌面下载器 | [`subhra74__xdm__master.zip`](archives/subhra74__xdm__master.zip) |
| [mamoe/mirai](https://github.com/mamoe/mirai) | QQ 机器人 / 协议库。做 QQ 机器人 | [`mamoe__mirai__dev.zip`](archives/mamoe__mirai__dev.zip) |
| [reilf/wecom](https://github.com/reilf/wecom) | 企业微信（源自 LinkWeChat）。企微 SCRM 参考 | [`reilf__wecom__master.zip`](archives/reilf__wecom__master.zip) |
| [Alvin9999/new-pac](https://github.com/Alvin9999/new-pac) | PAC / 代理相关。上游可能已失效 | 上游克隆失败 |
| [WUT12/Actions-OpenWrt](https://github.com/WUT12/Actions-OpenWrt) | GitHub Actions 自动编译 OpenWrt 固件（B70/x86/小米 AX 系列） | 克隆失败 |
| [wulabing/Xray_onekey](https://github.com/wulabing/Xray_onekey) | Xray 一键安装。快速搭节点 | [`wulabing__Xray_onekey__main.zip`](archives/wulabing__Xray_onekey__main.zip) |
| [yanue/V2rayU](https://github.com/yanue/V2rayU) | macOS V2Ray 客户端。Mac 上用 | [`yanue__V2rayU__rm.zip`](archives/yanue__V2rayU__rm.zip) |
| [Dr-Incognito/V2Ray-Desktop](https://github.com/Dr-Incognito/V2Ray-Desktop) | 跨平台代理客户端。桌面 GUI | [`Dr-Incognito__V2Ray-Desktop__master.zip`](archives/Dr-Incognito__V2Ray-Desktop__master.zip) |
| [caovps/IOS_SSR_SS_V2RAY](https://github.com/caovps/IOS_SSR_SS_V2RAY) | iOS 小火箭离线包说明 | 未打包 |
| [perrornet/miner-proxy](https://github.com/perrornet/miner-proxy) | 矿机与矿池中转。挖矿链路 | [`perrornet__miner-proxy__master.zip`](archives/perrornet__miner-proxy__master.zip) |
| [mobileboxlab/ios-bash-streaming](https://github.com/mobileboxlab/ios-bash-streaming) | 几行 bash 做 iOS 投屏。快速投屏 | [`mobileboxlab__ios-bash-streaming__master.zip`](archives/mobileboxlab__ios-bash-streaming__master.zip) |

## 开发工具

| 上游 | 说明 | zip |
| --- | --- | --- |
| [mitchellh/gox](https://github.com/mitchellh/gox) | Go 交叉编译。一条命令出多平台二进制 | [`mitchellh__gox__master.zip`](archives/mitchellh__gox__master.zip) |
| [goplus/libc](https://github.com/goplus/libc) | 把流行 libc 迁到 Go。Go 里用 C 库接口 | [`goplus__libc__musl-go.zip`](archives/goplus__libc__musl-go.zip) |
| [dodgepudding/bootout](https://github.com/dodgepudding/bootout) | layoutit.com 离线中文版。Bootstrap 可视化布局 | [`dodgepudding__bootout__master.zip`](archives/dodgepudding__bootout__master.zip) |
| [nanmu42/orly](https://github.com/nanmu42/orly) | O'RLY 动物书封面生成。恶搞封面 | [`nanmu42__orly__master.zip`](archives/nanmu42__orly__master.zip) |
| [nullswan/frida_go](https://github.com/nullswan/frida_go) | Frida 的 Go 绑定。用 Go 写 Frida | [`nullswan__frida_go__main.zip`](archives/nullswan__frida_go__main.zip) |
| [Hucxy/PbdViewer](https://github.com/Hucxy/PbdViewer) | PowerBuilder 反编译。看老 PB 工程 | [`Hucxy__PbdViewer__main.zip`](archives/Hucxy__PbdViewer__main.zip) |
| [michaelprowacki/powerrebuilder](https://github.com/michaelprowacki/powerrebuilder) | PB 应用迁到现代 Web。遗产系统迁移 | [`michaelprowacki__powerrebuilder__main.zip`](archives/michaelprowacki__powerrebuilder__main.zip) |
| [Perfare/Il2CppDumper](https://github.com/Perfare/Il2CppDumper) | Unity il2cpp 分析。游戏逆向常见工具 | [`Perfare__Il2CppDumper__master.zip`](archives/Perfare__Il2CppDumper__master.zip) |
| [ChiChou/grapefruit](https://github.com/ChiChou/grapefruit) | iOS 运行时观察。看 iOS 进程 | [`ChiChou__grapefruit__main.zip`](archives/ChiChou__grapefruit__main.zip) |
| [frida/aurora](https://github.com/frida/aurora) | 基于 Frida 的 Web PoC。Frida 网页壳 | [`frida__aurora__master.zip`](archives/frida__aurora__master.zip) |
| [iddoeldor/frida-snippets](https://github.com/iddoeldor/frida-snippets) | Frida 示例片段。抄例子 | [`iddoeldor__frida-snippets__master.zip`](archives/iddoeldor__frida-snippets__master.zip) |
| [CrackerCat/r0chrome](https://github.com/CrackerCat/r0chrome) | Chrome 相关研究。浏览器研究 | [`CrackerCat__r0chrome__master.zip`](archives/CrackerCat__r0chrome__master.zip) |
| [ansjdnakjdnajkd/iOS](https://github.com/ansjdnakjdnajkd/iOS) | iOS 渗透常用工具清单。工具索引 | [`ansjdnakjdnajkd__iOS__master.zip`](archives/ansjdnakjdnajkd__iOS__master.zip) |
| [guanyu7778/mystrong](https://github.com/guanyu7778/mystrong) | （描述为空）。见上游仓库 | [`guanyu7778__mystrong__main.zip`](archives/guanyu7778__mystrong__main.zip) |
| [lucasjacks0n/EggShell](https://github.com/lucasjacks0n/EggShell) | iOS/macOS/Linux 远程管理工具 | 未打包 |
| [p1s1lver/FiddlerEverywhereMockScripts](https://github.com/p1s1lver/FiddlerEverywhereMockScripts) | Fiddler Everywhere 相关脚本 | 未打包 |
| [ChiChou/bagbak](https://github.com/ChiChou/bagbak) | 基于 Frida 的 iOS 应用导出 | 未打包 |
| [anhkgg/SuperDllHijack](https://github.com/anhkgg/SuperDllHijack) | Windows DLL 加载相关工具 | 未打包 |

## 其它

| 上游 | 说明 | zip |
| --- | --- | --- |
| [andyzys/jd_seckill](https://github.com/andyzys/jd_seckill) | 京东茅台抢购脚本。历史项目 | [`andyzys__jd_seckill__master.zip`](archives/andyzys__jd_seckill__master.zip) |
| [ff522/dm-ticket](https://github.com/ff522/dm-ticket) | 大麦网自动购票。历史项目 | [`ff522__dm-ticket__main.zip`](archives/ff522__dm-ticket__main.zip) |

## 归档约定

1. 只克隆上游默认分支，`git clone --depth=1`。
2. zip 文件名：`{owner}__{repo}__{branch}.zip`。
3. 超过约 80MB 的不放 zip。
