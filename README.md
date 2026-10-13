# 谢霏 · Fei Xie

**3D Vision · Gaussian Splatting · Real-Time Rendering**

清华大学自动化系在读研究生，关注**三维重建、动态场景表示与具身视觉感知**。我的工作覆盖重建算法、模型轻量化、实时渲染与交互工具，尝试把研究方法做成可以运行和体验的系统。

Graduate student in Automation at Tsinghua University, working on 3D reconstruction, dynamic Gaussian representations, and interactive rendering.

[代表论文](https://yzxqh.github.io/DirectFisheye-GS/) · [4DGS 编辑器](https://github.com/forgrabbit/supersplat4d/tree/splat4d) · [动态场景演示](https://forgrabbit.github.io/splat4d-viewer-pages/)

## 代表研究 · Research

### DirectFisheye-GS · CVPR 2026 Highlight

**Enabling Native Fisheye Input in Gaussian Splatting with Cross-View Joint Optimization**

Zhengxian Yang\*, **Fei Xie\***, et al. · \* Equal contribution / 共同第一作者

面向大视场三维重建，将原生鱼眼相机模型引入 3D Gaussian Splatting，并通过跨视角联合优化增强几何与光度一致性，减少去畸变引起的信息损失和边缘伪影。

**我的贡献：**核心算法开发、完整训练系统构建、文献调研及论文部分撰写。

[项目主页](https://yzxqh.github.io/DirectFisheye-GS/) · [论文](https://arxiv.org/abs/2604.00648) · [CVPR 论文集](https://openaccess.thecvf.com/content/CVPR2026/html/Yang_DirectFisheye-GS_Enabling_Native_Fisheye_Input_in_Gaussian_Splatting_with_Cross-View_CVPR_2026_paper.html) · [团队代码](https://github.com/Metaverse-AI-Lab-THU/DirectFisheye-GS)

## 代表工程 · Selected Projects

| 项目 | 工作内容 | 技术与入口 |
| :--- | :--- | :--- |
| **[SuperSplat 4D](https://github.com/forgrabbit/supersplat4d)** | 基于 PlayCanvas SuperSplat 扩展动态高斯加载、播放、编辑与导出；实现 `.sog4d` 压缩及网页端交互。 | TypeScript · PlayCanvas · Python · [4D 源码](https://github.com/forgrabbit/supersplat4d/tree/splat4d) · [在线编辑器](https://supersplat4d.netlify.app/) |
| **[THUAI8](https://github.com/forgrabbit/thuai-8)** | 牵头游戏框架及技术方案设计，参与前后端与 SDK 开发，支持智能体对战与赛事运行。团队协作项目。 | C# · Unity · C++ / Python SDK · [团队仓库](https://github.com/thuasta/thuai-8) |
| **[EDCViewer3D](https://github.com/forgrabbit/EDCViewer3D-new)** | 参与电子设计竞赛三维可视化客户端开发，包括场景对象、角色状态与交互展示。团队协作项目。 | Unity · C# · WebSocket |

更早的研究实验：[Gaussian Splatting Depth](https://github.com/forgrabbit/gaussian-splatting-depth)，基于原始 3DGS 的深度渲染扩展。

## 研发经历 · Experience

- **京东 XR 研发组 · 4DGS 算法研发实习**（2025.06–2026.09）：参与动态三维重建、长序列训练、模型压缩与渲染加速，并构建网页端编辑与展示工具。
- **清华大学自动化系学生科协 · 软件部部长**：统筹软件项目与技术协作，参与赛事平台、互动游戏和网站建设。

## 技术方向 · Technical Focus

- **三维视觉：**原生鱼眼重建、跨视角优化、3D/4D Gaussian Splatting。
- **模型与渲染：**Python、PyTorch、CUDA；模型压缩、动态场景表示与实时呈现。
- **交互与工程：**TypeScript、PlayCanvas、Unity / C#；网页端工具、三维可视化与团队开发。
