# Reference: Music PV & Visualizer
**适用场景**: 歌曲宣传、VOCALOID PV、Live 背景视频、纯音乐可视化。
**核心逻辑**: **Atmosphere (氛围)** + **Rhythm (节奏)** + **Lyrics (歌词表现)**。

## 1. 四大核心流派 (The 4 Archetypes)

### A. 歌词排版流 (Lyric Video / Kinetic Type)
*   **重点**: **文字即视觉**。
*   **技法**:
    *   **节奏踩点**: 每一个字出现的时机必须精准对齐人声。
    *   **情绪字体**: 悲伤时用极细衬线体 (Serif)，愤怒时用粗狂笔刷体 (Brush)，科技感用无衬线 (Sans-serif)。
    *   **动态构图**: 文字倾斜、旋转、拆解、重组，填满画面负空间。
    *   **背景**: 纯色、动态渐变、或极其模糊的循环视频。

### B. 一图流/立绘流 (Static/Illustration PV)
*   **重点**: **美术插画的动态化** (类似 Live2D 或 After Effects 简单的 Puppet Pin)。
*   **技法**:
    *   **Camera Drift**: 摄像机永远在缓慢移动（推/拉/摇），避免画面静止。
    *   **Particle Effects**: 叠加灰尘、光斑、花瓣、雨滴等粒子效果增加层次。
    *   **Glitch/Aberration**: 配合鼓点做色散或故障效果。
    *   **局部动态**: 头发飘动、眼睛眨动、背景云层流动。

### C. 剧情叙事流 (Narrative MV)
*   **重点**: **用画面讲一个与歌词互补的故事**。
*   **技法**:
    *   **非线性剪辑**: 过去与现在的穿插，利用间奏 (Bridge) 进行闪回。
    *   **情绪蒙太奇**: 不追求动作连贯，追求情绪连贯。
    *   **Lip Sync (口型同步)**: 角色（2D/3D/真人）对口型演唱的特写镜头。

### D. 抽象视觉流 (Abstract Visualizer)
*   **重点**: **通感 (Synesthesia)** —— 听觉的视觉化。
*   **技法**:
    *   **Audio Reactive**: 图形随着频谱 (Spectrum) 跳动。
    *   **Fractals/Tunnel**: 无限循环的隧道、万花筒、流体。
    *   **Color Shift**: 颜色随着和弦走向 (Chord Progression) 变化。

## 2. 剪辑节奏法则 (Editing On The Beat)
*   **On Beat (正拍)**: 画面切换点落在 Kick (底鼓) 或 Snare (军鼓) 上。
*   **Off Beat (反拍)**: 在弱拍切镜，制造不适或悬念。
*   **Drop (高潮)**: 副歌进来的瞬间，必须有视觉上的爆发（如：全屏闪白、极速推拉、色彩反转）。
*   **BPM Analysis**: 制作前先确认歌曲 BPM，计算每一拍的帧数（例如 120 BPM = 每 0.5秒一拍）。

## 3. Output Format (Script Template)
请严格使用以下表头输出分镜：
| Time | Visuals (Typography/Motion) | Lyrics | Audio Sync (Beat/Instrument) |
| :--- | :--- | :--- | :--- |

---
**Example Entry**:
| Time | Visuals (Typography & Motion) | Lyrics (Content) | Audio Sync |
| :--- | :--- | :--- | :--- |
| 00:15 | 黑色背景。白色的“孤独”二字极细，位于画面右下角，微弱呼吸。 | "孤独像野草" | 弱起，人声低沉。 |
| 00:18 | “野草”二字瞬间变大，占据全屏，边缘呈现锯齿状抖动。背景闪红一帧。 | "疯狂生长" | 重音 Kick 踩点。 |
