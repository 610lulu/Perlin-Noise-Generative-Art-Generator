# Perlin Noise Generative Art Generator

一个基于 **Perlin Noise Flow Field** 的交互式生成艺术工具。粒子会沿噪声构成的无形力场持续运动，形成流动、叠加且不断演化的视觉轨迹。

> 柏林噪声流场 · 追踪无形力场中的粒子轨迹

[![Live Site](https://img.shields.io/badge/Live%20Site-Open%20Generator-3b82f6?style=for-the-badge)](https://610lulu.github.io/Perlin-Noise-Generative-Art-Generator/Perlin-Noise-Generative-Art-Generator.html)

## Live Site

**[打开在线生成器 →](https://610lulu.github.io/Perlin-Noise-Generative-Art-Generator/Perlin-Noise-Generative-Art-Generator.html)**

无需安装依赖，使用现代浏览器即可直接体验。

## 功能介绍

- **实时噪声流场**：粒子沿动态噪声方向持续运动，生成独一无二的轨迹。
- **六套视觉配色**：午夜档案、雨夜霓虹、黑白胶片、迷雾蓝调、血迹线索和冷钢。
- **自由调整参数**：控制粒子数量、噪声尺度、流动速度、时间演化、粒子大小和透明度。
- **鼠标交互扰动**：在画布上按住并拖动，为附近粒子施加排斥力。
- **播放与画布控制**：支持暂停、播放、重置和清空。
- **PNG 图片导出**：点击“存档”即可保存当前生成作品。

## 参数说明

| 参数 | 作用 |
| --- | --- |
| Particles | 调整画布中的粒子数量 |
| Scale | 控制噪声场的空间尺度 |
| Speed | 调整粒子的流动速度 |
| Time | 控制噪声场随时间演化的速度 |
| Size | 调整粒子的绘制尺寸 |
| Alpha | 调整粒子与轨迹的透明度 |

## 使用方法

1. 打开 [Live Site](https://610lulu.github.io/Perlin-Noise-Generative-Art-Generator/Perlin-Noise-Generative-Art-Generator.html)。
2. 点击画布下方的色块切换配色。
3. 拖动参数滑块，观察流场实时变化。
4. 在画布上按住鼠标并拖动，扰动粒子轨迹。
5. 点击“存档”将当前画面导出为 PNG。

## 本地运行

项目是一个独立 HTML 文件，不需要构建工具或第三方 JavaScript 依赖。

1. 下载或克隆本仓库。
2. 使用浏览器打开 `Perlin-Noise-Generative-Art-Generator.html`。

## 技术实现

- HTML5
- CSS3
- JavaScript
- Canvas 2D API
- 多层噪声采样与粒子流场动画
