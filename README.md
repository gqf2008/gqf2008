# 高庆丰 · gqf2008

**系统软件工程师 · Rust · 上海**

一个人 + 代码智能体，做可信的系统软件：Rust 写内核、写输入法、写语音——全部开源、全部可复现。

---

## 精选项目

### ⚙️ Xtask — 用 Rust 从零写可移植 RTOS 内核

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![CI](https://github.com/gqf2008/Xtask/actions/workflows/main-gate.yml/badge.svg)
![MIT](https://img.shields.io/badge/license-MIT-green)

2022 年起维护的可移植抢占式多任务内核，参考 FreeRTOS 设计：

- **11+ 目标**：RISC-V（GD32VF103 / CH32V1·V2·V3 / ESP32C3 / CM32M4 / QEMU virt）+ Cortex-M3/M4/M7/RP2040 + Cortex-R5F（无 PendSV 架构原创方案）
- **QEMU 执行级验证**：24 项内核自测全绿自退出，无开发板可复现；SMP 在 `-smp 2..8` 全绿；CI 门禁每次提交自动跑
- **测试文化**：host 回归 157 项（全特征实测）+ 踩坑回归全部阳性对照（先红后绿）

[查看仓库 →](https://github.com/gqf2008/Xtask) ｜ 配套专著《用 Rust 手写 RTOS 内核》31 章完稿、三审三校完成，**出版中**

### ⌨️ verba-ime — 开源多模态 AI 输入法

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![MIT](https://img.shields.io/badge/license-MIT-green)

OCR / ASR / LLM / TTS 全本地的跨平台 AI 输入法（Windows / macOS / Linux）：截图识字上屏、语音转字、AI 润色——**数据不上云**。

[查看仓库 →](https://github.com/gqf2008/verba-ime)

### 🎵 Xmusic-splitter — 桌面音轨分离器

Tauri 2 + Demucs AI 模型，本地推理、无遥测：分离伴奏/人声，支持试听、独奏、静音与导出。

[查看仓库 →](https://github.com/gqf2008/Xmusic-splitter)

### 🔌 abb — 消息桥：飞书 / 微信 / 钉钉 ↔ 本地 Claude/Codex agent

Rust + Slint 菜单栏应用，把 IM 消息路由给本地 AI agent（本项目正运行在你看到的这个对话里）。

[查看仓库 →](https://github.com/gqf2008/abb)

---

## 📖 当前在做

- 出版《用 Rust 手写 RTOS 内核》——31 章完稿，三审三校完成（2026-09）
- 基于内核与书稿的系列技术内容（"Rust 手写 RTOS"主题），边写边发——关注仓库即关注进度
- 深耕语音/音频产品线：分离 → 生成 → 场景应用

## 🧰 技术栈

Rust（内核/系统/应用） · 嵌入式（RISC-V / Cortex-M） · C/汇编 · FreeSWITCH / WebRTC / SIP · Tauri · Python · Go · AI Agent / LLM 工程化

## ✉️ 联系

- GitHub Issues（任何仓库，优先）
- ✉️ gao.qingfeng@gmail.com
- 𝕏 [@gqf25044395](https://x.com/gqf25044395)

---

> 💡 这个页面本身也是"一个人 + 代码智能体"产出的——从仓库到书稿到文章，欢迎到 [Xtask](https://github.com/gqf2008/Xtask) 看完整过程。
