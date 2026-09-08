# Kimi Work 插件封装说明

本仓库是 [mattpocock/skills](https://github.com/mattpocock/skills) 的 **Kimi Work 插件封装**。
原作者 Matt Pocock，MIT 开源许可（见 LICENSE），25 个 agent skills 原样收录于 `skills/` 目录。

## 在 Kimi Work 中安装

方式一（个人市场登记）：
```bash
kimi-daimon kimi-plugin register-personal <本仓库目录>
```
然后到 Kimi 桌面版插件页「个人」页签点 ＋ 安装，免重启生效。

方式二（手动）：把 `skills/` 下各技能目录复制到 Kimi 的 skills 根目录。

## 内容

- `kimi.plugin.json` —— Kimi 插件清单（25 个技能接线）
- `icon.png` —— 插件图标
- `skills/engineering/` —— 18 个工程技能（tdd、code-review、implement、to-spec 等）
- `skills/productivity/` —— 7 个效率技能（grill-me、handoff、teach 等）

上游更新：拉取 github.com/mattpocock/skills 最新代码同步 `skills/` 即可。
