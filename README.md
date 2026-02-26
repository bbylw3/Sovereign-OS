# 💻 Sovereign OS | Knowledge is Power

> "They can burn the archives, they can filter the network, but they cannot erase an idea."

**Sovereign OS** is an interactive web storytelling experience built on a pure frontend stack (HTML / Tailwind CSS / Vanilla JS). By replicating the classic MS-DOS boot sequence and Windows 95/98-style graphical interface, it invites users to step into the shoes of a "hacker" penetrating the system to dismantle the global information censorship firewall codenamed **DIRECTIVE_77**.

---

## ✨ Features

### 📱 Full Mobile & Touch Optimization

- **Double Tap Support**: All desktop icons support "Double Tap" on mobile devices to open applications.
- **Fluid Drag & Resize**: Windows utilize native Pointer Events and overflow prevention mechanisms, ensuring smooth interaction on mobile screens.
- **Responsive Layout**: Automatic window scaling prevents content overflow on small-screen devices.

### 💾 Immersive DOS Boot Sequence

- **BIOS Emulation**: Realistic BIOS POST (Power-On Self-Test) and memory allocation simulation.
- **Visual Effects**: Automatic `WIN` command execution triggers a vintage CRT "flicker" transition effect.

### 🪟 Classic Win9x Desktop Environment

- **Authentic Aesthetics**: Iconic Teal background and pixel-art icons.
- **Interactive Window System**: Full support for dragging, stacking (focus), maximizing, minimizing, and closing.
- **Dynamic Taskbar**: Includes the classic "Start" button and a real-time system clock.

### 🌐 ZH_CN.BAT Localization Mechanism

- **In-System Patching**: A dedicated language pack script is built directly into the desktop.
- **Soft Reboot**: Triggering the script simulates a System Soft Reboot, mimicking the DOS boot process of loading language drivers to seamlessly transition into a full Chinese environment.

### 📊 System Monitor (SYS_MONITOR.EXE)

- **Intercept Logs**: Simulates real-time refreshing of low-level system interception logs.
- **Live Status**: Displays firewall status, data flow, and system uptime.

### ⌨️ Hidden Terminal Overwrite (SOVEREIGN.EXE)

- **MS-DOS Parser**: A lightweight built-in command-line interpreter.
- **Standard Commands**: Supports `help`, `cls`, `ver`, and more.
- **Narrative Progression**: Includes a hidden `override` command to advance the story.
- **Thematic Climax**: Executing the override automatically triggers the hidden "Manifesto of Truth" (TRUTH.TXT), revealing the ultimate theme: **"Knowledge is Power."**

---

## 🚀 How to Play

This is a micro-piece of interactive art with a complete narrative arc. Follow these steps to experience it:

1. **System Boot**: Open `index.html` and wait for the pitch-black DOS interface to complete its boot sequence and self-test.
2. **Language Switch (Optional)**: If you prefer a Chinese environment, double-click the `ZH_CN.BAT` icon on the desktop. The system will reboot to load the localization patch.
3. **Read the Context**: Open `DIRECTIVE_77.TXT` (Notepad). Read these "terms and conditions" to understand the draconian censorship of this world.
4. **Monitor the Censorship**: Open `SYS_MONITOR.EXE` to observe the system's aggressive real-time packet interception.
5. **Reclaim Control (Main Goal)**:
   - Double-click the black `SOVEREIGN.EXE` icon to open the MS-DOS terminal.
   - Type `help` to see available commands.
   - Type the ultimate command: `override` and press **Enter** (or the confirm button on mobile).
6. **Witness the Liberation**:
   - Watch as censored words (_Knowledge, Power, Freedom, Speech_) in the `DIRECTIVE_77.TXT` notepad are restored with blood-red highlights.
   - The firewall in the System Monitor will collapse, and the data flow will shift to "Decentralized."
   - Finally, a true **"TRUTH.TXT"** manifesto will appear, proclaiming the complete liberation of the sovereign node.

---

## 🛠️ Tech Stack

- **HTML5 & CSS3**: Layout and core animations (CRT scanlines, flicker effects, terminal cursor).
- **Tailwind CSS**: Rapidly building classic UI elements (extensive use of `inset` shadows to simulate 3D embossed effects).
- **Vanilla JavaScript (ES6+)**:
  - **Pointer Event API**: Mobile interaction optimization and touch-action handling.
  - **Window Management**: Custom logic for Z-index control, coordinate calculation, and drag listeners.
  - **Virtual File System**: IO parsing for the terminal and file interactions.
  - **State Machine**: Narrative timeline, state control, and dynamic i18n switching.
- **Google Fonts**: Utilizing `VT323` for that authentic DOS terminal look.

---

## 📦 Deployment

This is a pure frontend, single-page project with zero dependencies and no build tools required.

1. Download `index.html` locally.
2. Open it directly in any modern desktop browser (Chrome, Firefox, Safari) or mobile browser (iOS Safari, Chrome for Android).

> "Submit to the silence... or break the firewall."

---

# 💻 Sovereign OS | 知识就是力量

> "They can burn the archives, they can filter the network, but they cannot erase an idea."

**Sovereign OS** 是一个基于纯前端技术栈（HTML / Tailwind CSS / Vanilla JS）构建的交互式网页叙事体验。它通过复刻经典的 MS-DOS 启动序列和 Windows 95/98 风格的图形界面，让用户扮演一名“黑客”，深入系统内部，打破代号为 DIRECTIVE_77 的全球信息审查防火墙。

---

## ✨ 核心特色 (Features)

### 📱 全面移动端与触摸适配 (Mobile Optimized)

- **双击轻触 (Double Tap)**：重构了所有桌面图标事件，支持手机端双击打开应用。
- **流畅拖拽与缩放**：窗口引入了原生的 Pointer Event 与防页面滚动机制，手机端同样可以流畅拖拽和调整窗口。
- **响应式布局**：自动响应式窗口尺寸，防止在小屏幕设备上内容溢出。

### 💾 沉浸式 DOS 引导序列

- **BIOS 模拟**：逼真的 BIOS 自检与内存分配模拟。
- **视觉特效**：自动敲击 `WIN` 命令触发老式 CRT 显示器的“闪屏”过渡效果。

### 🪟 经典 Win9x 桌面环境

- **复古美学**：标志性的 Teal (蓝绿色) 桌面背景与像素风图标。
- **交互式窗口系统**：完全可交互的窗口系统：支持拖拽、聚焦置顶、最大化、最小化和关闭。
- **动态任务栏**：包含经典的“开始”按钮与实时系统时钟。

### 🌐 沉浸式汉化重启机制 (ZH_CN.BAT)

- **语言包补丁**：桌面内置语言包补丁脚本。
- **软重启模拟**：双击触发系统软重启（Soft Reboot），模拟读取并加载语言包的 DOS 引导过程，随后无缝进入全中文的操作系统环境。

### 📊 实时系统监视器 (SYS_MONITOR.EXE)

- **拦截日志**：模拟不断刷新的系统底层拦截日志。
- **实时状态**：实时显示防火墙状态、信息流向和系统运行时间。

### ⌨️ 隐藏的终端覆写机制 (SOVEREIGN.EXE)

- **DOS 解析器**：内置轻量级 MS-DOS 命令行解析器。
- **基础命令**：支持 `help`, `cls`, `ver` 等基础命令。
- **剧情推进**：包含用于推进剧情的隐藏 `override` 终极指令。
- **叙事升华**：成功执行覆写后，系统将自动弹出隐藏的《自由宣言》(TRUTH.TXT)，揭示 **“知识就是力量”** 的最终主题。

---

## 🚀 游玩指南 (How to Play)

这是一个包含完整起承转合的微型交互艺术品，请按照以下步骤体验：

1. **系统启动**：打开 `index.html`，等待纯黑的 DOS 引导界面完成加载与自检。
2. **切换语言 (可选)**：如果需要中文环境，双击桌面的 `ZH_CN.BAT` 图标，系统将经历一次重启并加载汉化补丁。
3. **阅读背景**：进入桌面后，双击打开 `DIRECTIVE_77.TXT` (记事本)。阅读这份“霸王条款”，了解当前世界观下的严苛审查制度。
4. **监控状态**：双击打开 `SYS_MONITOR.EXE`，观察系统正在进行的高强度数据包拦截与审查动作。
5. **夺回控制权 (核心目标)**：
   - 双击桌面上黑色的 `SOVEREIGN.EXE` 图标，打开 MS-DOS 终端。
   - 在终端中输入指令 `help` 查看可用命令。
   - 输入终极覆写指令：`override` 并按下回车（移动端点击键盘确认/回车）。
6. **见证解放**：
   - 观察 `DIRECTIVE_77.TXT` 记事本中被审查的词汇（_知识, 力量, 自由, 言论_）如何被鲜血般的红色高亮还原。
   - 系统监视器中的防火墙将被彻底击溃，信息流向变为“去中心化”。
   - 最终，系统会自动弹出一份真正的 **《真相.TXT》(TRUTH.TXT)** 宣言，宣告主权节点的彻底解放。

---

## 🛠️ 技术栈 (Tech Stack)

- **HTML5 & CSS3**：布局与核心动画（CRT扫描线、闪屏、光标闪烁）。
- **Tailwind CSS**：快速构建经典 UI 元素的颜色与边框（大量使用了经典的 `inset` 阴影来模拟 3D 浮雕效果）。
- **Vanilla JavaScript (ES6+)**：
  - **Pointer Event API**：与 `touch-action` 进行移动端交互优化。
  - **窗口管理**：自定义窗口管理逻辑（层级控制、坐标计算、拖拽监听）。
  - **虚拟文件系统**：命令行输入输出解析。
  - **状态机**：动态时间线控制与多语言 (i18n) 动态切换。
- **Google Fonts**：使用 `VT323` 还原 DOS 终端字体。

---

## 📦 部署与运行

本项目为完全纯前端的单文件项目，零依赖，无需构建工具。

1. 将 `index.html` 下载到本地。
2. 直接使用任何现代桌面浏览器（Chrome, Firefox, Safari）或手机浏览器（iOS Safari, 手机 Chrome）打开该文件即可体验。

> "Submit to the silence... or break the firewall."
