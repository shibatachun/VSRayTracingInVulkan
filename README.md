# NoCmakeOneClickBuildVSRayTracingInVulkan

## RayTracingInVulkan-Windows

> 本项目修改自 [GPSnoopy/RayTracingInVulkan](https://github.com/GPSnoopy/RayTracingInVulkan)，主要面向在 Windows 平台上不想手动配置 CMake 的开发者，提供开箱即用的体验。

### 🎯 特性

- 预配置好的 Visual Studio 解决方案／项目文件  
- 零 CMake 配置：下载、编译、运行，一步到位  
- 完整的光线追踪示例，基于 Vulkan API

### 🚀 未来计划

- 集成 Qt ：提供跨平台 GUI 支持  
- 参数可视化：实时调节渲染参数并观察效果  
- 光栅化 + 光线追踪混合渲染：实现柔和阴影和精确反射  
- 融入自研 D3DEngine：在自有引擎中复用光追模块
- 加入英伟达DLSS4 (only support in RTX40x)
- 试图继承MFG(Multiframe generation)
