# 旅行 Vlog 自动初剪

一个 Codex Skill。把旅行多机位素材、同期声和已有配音整理成一条可编辑的达芬奇粗剪时间线。先用精彩合集开场，再按旅行顺序剪正文。

## 安装

克隆仓库，把其中的 `travel-vlog-rough-cut` 技能目录复制到 Codex 的技能目录。macOS 示例：

```sh
git clone https://github.com/versense84-cmd/travel-vlog-rough-cut.git
mkdir -p ~/.codex/skills
cp -R travel-vlog-rough-cut/travel-vlog-rough-cut ~/.codex/skills/
```

## 使用

> 用 `$travel-vlog-rough-cut` 帮我初剪这趟旅行。优先用我录好的旁白，开头做精彩合集，正文按拍摄行程展开。请把字幕、地点介绍和一级还原都落到达芬奇时间线上。

实际剪辑需要素材可读、达芬奇可用，并配置可访问项目的连接或脚本接口。需要生成旁白时使用可用的语音工具。标题动效默认使用 HyperFrames。云盘下载和远程控制使用各自已配置的环境。

[查看 Skill 说明](travel-vlog-rough-cut/SKILL.md)
