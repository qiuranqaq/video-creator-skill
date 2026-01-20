# Video Creator / 全能视频创作大师 (Gemini CLI Extension)

这是一个为 Gemini CLI 设计的高级视频创作 Skill。它集成了编剧、导演、剪辑思维，支持多种视频类型的脚本策划与分镜生成。

## 🌟 核心功能 (Features)

*   **多模态支持**:
    *   🎬 **Live Action**: 实拍 TVC/短片 (含器材清单/布光方案)。
    *   🎨 **2D Animation**: MG 动画/扁平风格 (含旁白与视觉节奏)。
    *   🧊 **3D Animation**: 角色表演/场景氛围/产品渲染 (含动作捕捉/体积光)。
    *   🤖 **AI Gen**: 适配 Gen-2/Sora 的提示词工程 (Start/End Prompts)。
    *   🎮 **Game PV**: 游戏版本/角色/剧情预告 (含顿帧/打击感设计)。
    *   🎵 **Music PV**: 歌词 PV/MV (含音画同步/BPM分析)。
*   **合规性审查**: 内置中国广告法合规逻辑，自动规避违禁词。
*   **专业导出**: 支持一键导出 HTML 格式的专业分镜脚本。

## 📂 目录结构

```text
video-creator/
├── GEMINI.md           # 核心指令集 (大脑)
├── gemini-extension.json # 扩展元数据
├── reference/          # 专业知识库 (Reference)
│   ├── REF_2D_ANIMATION.md
│   ├── REF_3D_ANIMATION.md
│   ├── REF_AI_GEN.md
│   ├── REF_GAME_PV.md
│   ├── REF_LIVE_ACTION.md
│   └── REF_MUSIC_PV.md
└── README.md           # 本说明文件
```

## 🚀 如何安装 (Installation)

1. **一键安装**: 在 Gemini CLI 中运行以下命令：
   ```bash
   /extension install https://github.com/QiuranQAQ/Video-Creator-Skill.git
   ```

2. **启用 Skill**: 安装完成后，请前往 Gemini CLI 的 **Settings** 中手动开启该 Skill，确保其处于激活状态。

安装并开启后，你可以通过以下指令激活：
> "激活 video-creator" 或直接说 "帮我写个视频脚本..."

---

## 🛠️ 使用示例

*   **生成游戏 PV**: "帮我策划一个《黑神话》风格的 BOSS 战演示 PV。"
*   **生成 AI 视频**: "做一个赛博朋克雨夜的 AI 视频脚本，要首尾帧 Prompt。"
*   **生成 TVC**: "写一个高端咖啡机的 30秒 实拍广告，要电影级制作清单。"

## 📄 License
MIT
