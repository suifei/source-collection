# 上游仓库浅克隆归档清单

对公开上游做 `git clone --depth=1`，去掉 `.git` 后打 zip。单个 zip 超过 80 MiB 不保留。

## 汇总

- 成功: **54**（约 330 MiB）
- 过大未保留: **5**（jynew、jynew_art、LxgwWenKai、langflow、OpenSource-Ai-Glasses）
- 克隆失败: **1**（Alvin9999/new-pac，仓库可能已私有或删除）
- 跳过: **10**（敏感 / 私有 / 教材 / 未授权接口，不放进公开 zip）

zip 文件将放在 `archives/` 目录（需 GitHub CLI 登录后推送）。

完整对照见 [UPSTREAMS.md](UPSTREAMS.md)。
