# Gesture Beauty Cam · 美颜手势相机

A browser webcam toy: slim your face, enlarge your eyes and apply soft filters in
real time — all controlled with hand gestures. Built with MediaPipe FaceMesh + Hands,
in a single self-contained HTML file.

一个网页摄像头小玩具：实时**瘦脸、大眼**、叠加**柔光滤镜**，而且全程用**手势隔空控制**。
基于 MediaPipe FaceMesh + Hands，整个程序就一个 HTML 文件。

## 使用 / Usage

下载 `beauty.html`，用浏览器打开即可（需要授予摄像头权限）。

> 提示：部分浏览器只在 `https://` 或 `localhost` 下允许使用摄像头。直接双击本地文件
> 若摄像头被拦截，可用一个本地服务器打开，或开启本仓库的 GitHub Pages 在线访问。

## 技术 / Built with

- MediaPipe FaceMesh（468 个人脸关键点 → 瘦脸 / 大眼变形）
- MediaPipe Hands（手势识别 → 隔空控制面板）
- 原生 Canvas 实时渲染

---

Made by **Albus Snape（追风君子）** · https://github.com/AlbusSnape77
