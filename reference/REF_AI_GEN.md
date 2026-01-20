# Reference: AI Video Generation (Gen-2/Sora/Luma/NanoBanana)
**适用场景**: AI 视频生成、Prompt Engineering、风格化视频。

## 核心原则: "Prompt Control" (提示词控制)
AI 视频不仅需要描述画面，更需要描述**变化**。输出必须包含**首尾帧**和**运动描述**。

### 1. 提示词结构 (Prompt Structure)
*   **Subject (主体)**: 核心物体或人物。
*   **Environment (环境)**: 光照、天气、背景。
*   **Style (风格)**: 胶片感、3D 渲染、油画、赛博朋克。
*   **Camera Movement (运镜)**: 必须明确摄像机的运动轨迹。

### 2. 镜头运动指令 (Motion Prompts)
*   **Pan Left/Right**: 镜头左右摇。
*   **Tilt Up/Down**: 镜头上下摇。
*   **Zoom In/Out**: 镜头推拉。
*   **Truck Left/Right**: 镜头左右平移（视差效果）。
*   **Pedestal Up/Down**: 镜头升降。
*   **Tracking Shot**: 跟随主体移动。
*   **FPV Drone**: 第一人称无人机视角（高速、穿梭）。

### 3. 首尾帧逻辑 (Start/End Frame)
为了控制 AI 视频的连贯性，建议同时定义开始和结束的画面状态。

## 4. Output Format (Script Template)
请严格使用以下表头输出分镜：
| Shot# | Time | Scene Description | Prompts (Start/End) | Camera Motion | Audio |
| :--- | :--- | :--- | :--- | :--- | :--- |

---
**Example Entry**:

| Time | Action Description | AI Visual Prompts (Keywords) |
| :--- | :--- | :--- |
| **01** | **描述**: 女孩转身回眸，长发在风中飘起，背景是东京雨夜。 | **Start Frame**: Young Asian woman, back view, black leather jacket, Tokyo street, raining, neon lights, 8k, photorealistic.<br>**End Frame**: Woman turning head, looking at camera, hair blowing in wind, smiling slightly.<br>**Camera Motion**: Pan Right, Slow Motion, High FPS. |
