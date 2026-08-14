# 上游仓库浅克隆归档清单

对 `suifei/source-collection` 对应的公开上游仓库做 `git clone --depth=1`，去掉 `.git` 后打 zip。
单个 zip 超过 80 MiB（83886080 字节）则删除并记为 `too_large`。
硬跳过（泄露 / 恶意软件 / 破解 / 私有）未克隆。

## 汇总

- 成功 (ok): **54**
- 过大已删除 (too_large): **5**
- 克隆失败 (clone_failed): **1**
- 跳过 (skipped): **10**
- 条目合计: **70**
- 保留 zip 合计: **345824259** 字节（329.80 MiB）

## 明细

| fork | 上游 | 默认分支 | 提交 | zip | 大小 | 状态 | 备注 |
| --- | --- | --- | --- | --- | ---: | --- | --- |
| `suifei/orly` | `nanmu42/orly` | master | `39e4bdadba` | nanmu42__orly__master.zip | 713840（697.1 KiB） | 成功 | — |
| `suifei/gpt4free` | `xtekky/gpt4free` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/henduohao` | `—` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/bootout` | `dodgepudding/bootout` | master | `6be804d81e` | dodgepudding__bootout__master.zip | 9659（9.4 KiB） | 成功 | — |
| `suifei/aurora` | `frida/aurora` | master | `1156f1d940` | frida__aurora__master.zip | 534978（522.4 KiB） | 成功 | — |
| `suifei/new-pac` | `Alvin9999/new-pac` | — | — | — | — | 克隆失败 | Cloning into '/workspace/clones/Alvin9999__new-pac'... remote: Invalid username or toke... |
| `suifei/claude-code` | `ultraworkers/claw-code` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/DdddOcrLib` | `sml2h3/DdddOcrLib` | master | `afc8373fba` | sml2h3__DdddOcrLib__master.zip | 38539（37.6 KiB） | 成功 | — |
| `suifei/JioNLP` | `dongrixinyu/JioNLP` | master | `a15c176ddb` | dongrixinyu__JioNLP__master.zip | 20436558（19.49 MiB） | 成功 | — |
| `suifei/IOS_SSR_SS_V2RAY` | `caovps/IOS_SSR_SS_V2RAY` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/free-programming-books` | `EbookFoundation/free-programming-books` | main | `fc45800748` | EbookFoundation__free-programming-books__main.zip | 855039（835.0 KiB） | 成功 | — |
| `suifei/jynew` | `jynew/jynew` | — | — | — | 2791728742（2.60 GiB） | 过大已删除 | clone aborted at ~2.6GiB uncompressed (would exceed 80MB zip); deleted |
| `suifei/libc` | `goplus/libc` | musl-go | `850b0b0780` | goplus__libc__musl-go.zip | 5448928（5.20 MiB） | 成功 | — |
| `suifei/ArrowLegend` | `Lee7goal/ArrowLegend` | master | `609502ef89` | Lee7goal__ArrowLegend__master.zip | 23593378（22.50 MiB） | 成功 | — |
| `suifei/LxgwWenKai` | `lxgw/LxgwWenKai` | main | `50f4b18241` | — | 92040403（87.78 MiB） | 过大已删除 | zip exceeds 80MB; deleted |
| `suifei/r0chrome` | `CrackerCat/r0chrome` | master | `3c49666ed4` | CrackerCat__r0chrome__master.zip | 389996（380.9 KiB） | 成功 | — |
| `suifei/OpenSource-Ai-Glasses` | `Iam5tillLearning/OpenSource-Ai-Glasses` | main | `bbe576ecfc` | — | 654012392（623.71 MiB） | 过大已删除 | clone uncompressed exceeds 400MB; skipped zip |
| `suifei/bagbak` | `ChiChou/bagbak` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/mystrong` | `guanyu7778/mystrong` | main | `34e0149291` | guanyu7778__mystrong__main.zip | 414220（404.5 KiB） | 成功 | — |
| `suifei/obsidian-ollama` | `hinterdupfinger/obsidian-ollama` | main | `92bf82392c` | hinterdupfinger__obsidian-ollama__main.zip | 29003（28.3 KiB） | 成功 | — |
| `suifei/Xray_onekey` | `wulabing/Xray_onekey` | main | `160644708a` | wulabing__Xray_onekey__main.zip | 2451384（2.34 MiB） | 成功 | — |
| `suifei/jd_seckill` | `andyzys/jd_seckill` | master | `0e5c535758` | andyzys__jd_seckill__master.zip | 11978（11.7 KiB） | 成功 | — |
| `suifei/chatglm-6b-api` | `xingkaixin/chatglm-6b-api` | main | `fb8510945f` | xingkaixin__chatglm-6b-api__main.zip | 781335（763.0 KiB） | 成功 | — |
| `suifei/annie` | `iawia002/lux` | master | `dd00f6d258` | iawia002__lux__master.zip | 216836（211.8 KiB） | 成功 | — |
| `suifei/frida_go` | `nullswan/frida_go` | main | `013fc35608` | nullswan__frida_go__main.zip | 690344（674.2 KiB） | 成功 | — |
| `suifei/WebGLM` | `THUDM/WebGLM` | main | `dd03d8fe05` | THUDM__WebGLM__main.zip | 6613440（6.31 MiB） | 成功 | — |
| `suifei/wecom` | `reilf/wecom` | master | `e082e6bd90` | reilf__wecom__master.zip | 7443914（7.10 MiB） | 成功 | — |
| `suifei/ocr_api_server` | `sml2h3/ddddocr-fastapi` | main | `a40a6b96d7` | sml2h3__ddddocr-fastapi__main.zip | 8185（8.0 KiB） | 成功 | — |
| `suifei/V2rayU` | `yanue/V2rayU` | rm | `43b709fdbf` | yanue__V2rayU__rm.zip | 1549（1.5 KiB） | 成功 | — |
| `suifei/FiddlerEverywhereMockScripts` | `p1s1lver/FiddlerEverywhereMockScripts` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/mirai` | `mamoe/mirai` | dev | `283f8840d4` | mamoe__mirai__dev.zip | 11371169（10.84 MiB） | 成功 | — |
| `suifei/miner-proxy` | `perrornet/miner-proxy` | master | `5756f6c862` | perrornet__miner-proxy__master.zip | 311740（304.4 KiB） | 成功 | — |
| `suifei/DocumentSearch` | `yuanzhoulvpi2017/DocumentSearch` | main | `e700e06389` | yuanzhoulvpi2017__DocumentSearch__main.zip | 1270496（1.21 MiB） | 成功 | — |
| `suifei/langflow` | `langflow-ai/langflow` | main | `976ec789d2` | — | 137669273（131.29 MiB） | 过大已删除 | zip exceeds 80MB; deleted |
| `suifei/EggShell` | `lucasjacks0n/EggShell` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/eptaora` | `ukhov79/eptaora` | main | `6bc525c9d3` | ukhov79__eptaora__main.zip | 3978950（3.79 MiB） | 成功 | — |
| `suifei/auto-phone-scheduler` | `lxzagent/auto-phone-scheduler` | main | `5222d81534` | lxzagent__auto-phone-scheduler__main.zip | 3096275（2.95 MiB） | 成功 | — |
| `suifei/dm-ticket` | `ff522/dm-ticket` | main | `a78d4f85a0` | ff522__dm-ticket__main.zip | 999514（976.1 KiB） | 成功 | — |
| `suifei/PbdViewer` | `Hucxy/PbdViewer` | main | `b46fd3e42b` | Hucxy__PbdViewer__main.zip | 1754722（1.67 MiB） | 成功 | — |
| `suifei/SuperDllHijack` | `anhkgg/SuperDllHijack` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/dynamic-analysis` | `analysis-tools-dev/dynamic-analysis` | master | `4105634965` | analysis-tools-dev__dynamic-analysis__master.zip | 68495（66.9 KiB） | 成功 | — |
| `suifei/chatglm-openai-api` | `ninehills/chatglm-openai-api` | main | `f9e068c252` | ninehills__chatglm-openai-api__main.zip | 1679360（1.60 MiB） | 成功 | — |
| `suifei/RWKV-Runner` | `josStorer/RWKV-Runner` | master | `3e10340342` | josStorer__RWKV-Runner__master.zip | 59449315（56.70 MiB） | 成功 | — |
| `suifei/marktext` | `marktext/marktext` | develop | `e52106fd1c` | marktext__marktext__develop.zip | 26112145（24.90 MiB） | 成功 | — |
| `suifei/gpt_academic` | `binary-husky/gpt_academic` | master | `d6bde0fa54` | binary-husky__gpt_academic__master.zip | 3113796（2.97 MiB） | 成功 | — |
| `suifei/V2Ray-Desktop` | `Dr-Incognito/V2Ray-Desktop` | master | `6f00169933` | Dr-Incognito__V2Ray-Desktop__master.zip | 269996（263.7 KiB） | 成功 | — |
| `suifei/PyBot_Scara` | `somorastik/PyBot_Scara` | main | `aead6d9318` | somorastik__PyBot_Scara__main.zip | 38936（38.0 KiB） | 成功 | — |
| `suifei/autoglm-go` | `ZoroSpace/autoglm-go` | master | `b117363b6e` | ZoroSpace__autoglm-go__master.zip | 46788（45.7 KiB） | 成功 | — |
| `suifei/fastllm` | `ztxz16/fastllm` | master | `af23441b5b` | ztxz16__fastllm__master.zip | 19112526（18.23 MiB） | 成功 | — |
| `suifei/ColossalAI` | `hpcaitech/ColossalAI` | main | `4f9953be33` | hpcaitech__ColossalAI__main.zip | 4803653（4.58 MiB） | 成功 | — |
| `suifei/matiec` | `beremiz/matiec` | default | `7949c0bda1` | beremiz__matiec__default.zip | 895389（874.4 KiB） | 成功 | — |
| `suifei/idc_70_client` | `android-crack/idc_70_client` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/ios-bash-streaming` | `mobileboxlab/ios-bash-streaming` | master | `06537324e4` | mobileboxlab__ios-bash-streaming__master.zip | 1518806（1.45 MiB） | 成功 | — |
| `suifei/acore_doc` | `najoast/acore_doc` | master | `2b142b8ecd` | najoast__acore_doc__master.zip | 64634（63.1 KiB） | 成功 | — |
| `suifei/awesome-monogame` | `aloisdeniel/awesome-monogame` | master | `c6210d600b` | aloisdeniel__awesome-monogame__master.zip | 5836（5.7 KiB） | 成功 | — |
| `suifei/frida-snippets` | `iddoeldor/frida-snippets` | master | `773f89ce8f` | iddoeldor__frida-snippets__master.zip | 6851344（6.53 MiB） | 成功 | — |
| `suifei/Il2CppDumper` | `Perfare/Il2CppDumper` | master | `4741d46ba9` | Perfare__Il2CppDumper__master.zip | 112988（110.3 KiB） | 成功 | — |
| `suifei/vector-vein` | `AndersonBY/vector-vein` | main | `8177b3a453` | AndersonBY__vector-vein__main.zip | 23254280（22.18 MiB） | 成功 | — |
| `suifei/jynew_art` | `jynew/jynew_art` | main | `2e46ffb9d2` | — | 2696711497（2.51 GiB） | 过大已删除 | clone uncompressed exceeds 400MB; skipped zip |
| `suifei/iOS` | `ansjdnakjdnajkd/iOS` | master | `7e7f75b79b` | ansjdnakjdnajkd__iOS__master.zip | 150018（146.5 KiB） | 成功 | — |
| `suifei/holo_clock` | `ekaggrat/holo_clock` | master | `210cb650a5` | ekaggrat__holo_clock__master.zip | 989553（966.4 KiB） | 成功 | — |
| `suifei/powerrebuilder` | `michaelprowacki/powerrebuilder` | main | `cf003a6aef` | michaelprowacki__powerrebuilder__main.zip | 5275197（5.03 MiB） | 成功 | — |
| `suifei/ChinaTextbook` | `TapXWorld/ChinaTextbook` | — | — | — | — | 已跳过 | hard skip: leaked/malware/crack/private |
| `suifei/Vicuna-LangChain` | `HaxyMoly/Vicuna-LangChain` | main | `026056c2d9` | HaxyMoly__Vicuna-LangChain__main.zip | 2405321（2.29 MiB） | 成功 | — |
| `suifei/ddddocr` | `sml2h3/ddddocr` | master | `c40f56f954` | sml2h3__ddddocr__master.zip | 76316986（72.78 MiB） | 成功 | — |
| `suifei/Grapefruit` | `ChiChou/grapefruit` | main | `d16322fb74` | ChiChou__grapefruit__main.zip | 6825667（6.51 MiB） | 成功 | — |
| `suifei/xdm` | `subhra74/xdm` | master | `1ca5a25aae` | subhra74__xdm__master.zip | 6012719（5.73 MiB） | 成功 | — |
| `suifei/gox` | `mitchellh/gox` | master | `9f712387e2` | mitchellh__gox__master.zip | 24020（23.5 KiB） | 成功 | — |
| `suifei/chatglm.cpp` | `li-plus/chatglm.cpp` | main | `60c89b7ea7` | li-plus__chatglm.cpp__main.zip | 1827225（1.74 MiB） | 成功 | — |
| `suifei/rathena_npc_translate` | `najoast/rathena_npc_translate` | master | `cf610799f4` | najoast__rathena_npc_translate__master.zip | 5133297（4.90 MiB） | 成功 | — |

## 过大仓库（未保留 zip）

- `suifei/jynew` ← `jynew/jynew`：clone aborted at ~2.6GiB uncompressed (would exceed 80MB zip); deleted（记录大小 2791728742 字节）
- `suifei/LxgwWenKai` ← `lxgw/LxgwWenKai`：zip exceeds 80MB; deleted（记录大小 92040403 字节）
- `suifei/OpenSource-Ai-Glasses` ← `Iam5tillLearning/OpenSource-Ai-Glasses`：clone uncompressed exceeds 400MB; skipped zip（记录大小 654012392 字节）
- `suifei/langflow` ← `langflow-ai/langflow`：zip exceeds 80MB; deleted（记录大小 137669273 字节）
- `suifei/jynew_art` ← `jynew/jynew_art`：clone uncompressed exceeds 400MB; skipped zip（记录大小 2696711497 字节）

## 克隆失败

- `suifei/new-pac` ← `Alvin9999/new-pac`：Cloning into '/workspace/clones/Alvin9999__new-pac'... remote: Invalid username or token. Password authentication is not supported for Git operations. fatal: Authentication failed for 'https://github.com/Alvin9999/new-pac.git/' 

## 硬跳过

- `suifei/gpt4free`
- `suifei/henduohao`
- `suifei/claude-code`
- `suifei/IOS_SSR_SS_V2RAY`
- `suifei/bagbak`
- `suifei/FiddlerEverywhereMockScripts`
- `suifei/EggShell`
- `suifei/SuperDllHijack`
- `suifei/idc_70_client`
- `suifei/ChinaTextbook`
