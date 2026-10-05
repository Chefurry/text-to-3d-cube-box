# 开发日志

## 2026-10-05
- 画好正方体展开图和六色测试图。
- 安装 Blender、Trae、uv。
- 配置 Blender MCP，连接成功。
- 创建 100mm 正方体，完成立方体投影 UV 展开。
- 贴图时发现整张图被拉伸，原因是材质节点未连接 UV 贴图节点。
- 添加 UV 贴图节点后，六个面正确显示对应图案。
- 渲染输出 outputs/render.png，导出 outputs/model.glb。