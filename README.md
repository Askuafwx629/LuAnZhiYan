# 路安智眼

基于安路 FPGA 与瑞芯微 RK3576 的多源智能视觉监控系统源码归档。

## 下载源码压缩包

[下载 FPGA + RK3576 + 上位机源码（RAR，4.44 MB）](https://github.com/Askuafwx629/LuAnZhiYan/releases/download/source-20261104/LuAnZhiYan_FPGA_RK_Host_Source_20261104_155957.rar)

[查看 Release](https://github.com/Askuafwx629/LuAnZhiYan/releases/tag/source-20261104)

## 包含内容

- `FPGA_ISP_JPEG/src`：FPGA RTL、IP HDL 及必要的 ROM 初始化文件。
- `RK3576/isp_jpeg_demo/deploy`：RK 视频采集、PCIe 驱动、解码、HDMI 显示和原生运行服务源码。
- `RK3576/isp_jpeg_demo/ai`：模型推理与后处理源码。
- `RK3576/isp_jpeg_demo/host`：Qt 上位机、视频显示与控制、辅助推理代码、构建脚本和界面资源。
- `FPGA_ISP_JPEG/host`：万兆视频发送工具源码与脚本。
- `RK3576/isp_jpeg_demo/tools`：相关构建与部署工具。

源码包保留原目录结构，共 898 个源码及必要资源文件，另附说明和逐文件清单。
不包含模型权重、SDK、虚拟环境、可执行程序、动态库、编译产物、录像或完整 TD 工程。
编译和运行所需的第三方依赖及模型需另行准备，具体见包内 README 和构建脚本。

## 文件校验

归档日期：2026-11-04  
文件大小：4,436,901 字节

SHA-256：

```text
3f85c0e6650cc8665339b4adbfc865eaae740fdfa624ad0294429d9d07d845da
```
