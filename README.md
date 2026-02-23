# Mac Studio AI Stack - Thunderbolt 5 Cluster

A highly realistic Mac Studio vertical stack visualization with Thunderbolt 5 interconnects, built with Three.js.

[中文文档](#中文文档)

## Features

### 3D Visualization
- 6× Mac Studio M3 Ultra vertical stack
- Realistic rounded aluminum chassis (195mm × 91mm × 195mm)
- Top ventilation with concentric hole pattern (~80 holes)
- Apple logo with bite mark and leaf
- Front ports: SDXC slot, 2× Thunderbolt 5, power LED
- Rear ports: Power, Ethernet, 2× HDMI, 4× USB-A, 4× Thunderbolt 5, 3.5mm audio
- Gold-plated port contacts
- Red Thunderbolt 5 accent rings

### Thunderbolt 5 Interconnects
- 5 dual-channel TB5 cables (10 total connections)
- 80 Gb/s per channel × 5 = 400 Gb/s total bandwidth
- Red cable visualization with connectors
- Data flow particle animation

### Interactive Controls
- **Rotate** - Auto rotation display
- **Top** - Top-down view of the stack
- **Front** - Front ports view
- **TB5 Links** - Toggle Thunderbolt 5 cables and data particles
- **Reset** - Reset camera position

### Navigation Links
- AI Navigator - AI tools and resources navigation
- ChatGPT - OpenAI conversational AI assistant
- Gemini - Google multimodal AI model
- Google - World's largest search engine
- Grok - xAI intelligent conversational assistant

## Tech Stack

- **Three.js** - 3D rendering engine
- **RoundedBoxGeometry** - Realistic rounded corners
- **TubeGeometry** - TB5 cable paths with Bezier curves
- **OrbitControls** - Orbit camera controller
- **WebGLRenderer** - WebGL renderer with shadows and tone mapping

## M3 Ultra Specifications

| Component | Per Unit | Cluster (6×) |
|-----------|----------|--------------|
| CPU | 32 cores | 192 cores |
| GPU | 80 cores | 480 cores |
| Neural Engine | 32 cores | 192 cores |
| Unified Memory | 512 GB | 3 TB |
| Memory Bandwidth | 819 GB/s | 4.9 TB/s |
| Interconnect | Thunderbolt 5 | 80 Gb/s × 5 |

## Getting Started

Simply open `index.html` in a modern browser.

Or use a local server:

```bash
# Python
python -m http.server 8080

# Node.js
npx serve
```

Then visit `http://localhost:8080`

## File Structure

```
StepFun/
├── index.html    # Main page (HTML, CSS, JS)
└── README.md     # Documentation
```

## Color Scheme

| Purpose | Color Code |
|---------|------------|
| Background | `#000000` |
| Aluminum Body | `#cbcbce` |
| Dark Aluminum | `#9a9a9e` |
| Thunderbolt 5 Red | `#ff3b30` |
| Gold Contacts | `#d4af37` |
| Green LED | `#30d158` |
| Port Inner | `#050505` |

## Browser Support

- Chrome (Recommended)
- Firefox
- Safari
- Edge

Requires modern browsers with WebGL and ES Modules support.

## License

MIT License

---

# 中文文档

一个基于 Three.js 的高度仿真 Mac Studio 竖排堆叠可视化，通过 Thunderbolt 5 互联。

## 功能特性

### 3D 可视化
- 6 台 Mac Studio M3 Ultra 竖排堆叠
- 逼真的圆角铝金属机身 (195mm × 91mm × 195mm)
- 顶部散热孔阵列（约 80 个孔，同心圆排列）
- Apple Logo（带咬痕和叶子）
- 前置端口：SDXC 卡槽、2× Thunderbolt 5、电源 LED
- 后置端口：电源、以太网、2× HDMI、4× USB-A、4× Thunderbolt 5、3.5mm 音频
- 端口内部金色触点
- 红色 Thunderbolt 5 端口光圈

### Thunderbolt 5 互联
- 5 组双通道 TB5 线缆（共 10 条连接）
- 80 Gb/s × 5 = 400 Gb/s 总带宽
- 红色线缆可视化（带连接器）
- 数据流粒子动画

### 交互功能
- **Rotate** - 自动旋转展示
- **Top** - 俯视堆叠视角
- **Front** - 正面端口视角
- **TB5 Links** - 开关 Thunderbolt 5 线缆和数据粒子
- **Reset** - 重置视角

### 导航链接
- AI Navigator - AI 工具与资源导航平台
- ChatGPT - OpenAI 对话式 AI 助手
- Gemini - Google 多模态 AI 模型
- Google - 全球最大搜索引擎
- Grok - xAI 智能对话助手

## 技术栈

- **Three.js** - 3D 渲染引擎
- **RoundedBoxGeometry** - 逼真圆角几何体
- **TubeGeometry** - TB5 线缆贝塞尔曲线路径
- **OrbitControls** - 轨道相机控制器
- **WebGLRenderer** - WebGL 渲染器（支持阴影和色调映射）

## M3 Ultra 规格

| 组件 | 单机 | 集群 (6×) |
|------|------|----------|
| CPU | 32 核心 | 192 核心 |
| GPU | 80 核心 | 480 核心 |
| 神经引擎 | 32 核心 | 192 核心 |
| 统一内存 | 512 GB | 3 TB |
| 内存带宽 | 819 GB/s | 4.9 TB/s |
| 互联 | Thunderbolt 5 | 80 Gb/s × 5 |

## 本地运行

直接在现代浏览器中打开 `index.html` 文件。

或使用本地服务器：

```bash
# Python
python -m http.server 8080

# Node.js
npx serve
```

然后访问 `http://localhost:8080`

## 文件结构

```
StepFun/
├── index.html    # 主页面（包含 HTML、CSS、JS）
└── README.md     # 项目文档
```

## 配色方案

| 用途 | 颜色代码 |
|------|----------|
| 背景色 | `#000000` |
| 铝金属机身 | `#cbcbce` |
| 深色铝金属 | `#9a9a9e` |
| Thunderbolt 5 红 | `#ff3b30` |
| 金色触点 | `#d4af37` |
| 绿色 LED | `#30d158` |
| 端口内部 | `#050505` |

## 浏览器支持

- Chrome（推荐）
- Firefox
- Safari
- Edge

需要支持 WebGL 和 ES Modules 的现代浏览器。

## 许可证

MIT License
