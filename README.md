# 二维正方体展开图转三维展示模型

## 项目简介
输入一张二维正方体展开图和一句自然语言，自动生成三维正方体盒子并渲染展示图。

## 环境要求
- Blender 3.0+
- Trae
- Blender MCP 插件
- uv（pip install uv）

## 使用方法
1. 打开 Blender，启动 MCP 服务（connected on port 9876）。
2. 打开 Trae，连接 blender MCP。
3. 在 Trae 中输入自然语言指令，例如：
   “创建一个 100mm 的正方体，用 assets/input/box_design.png 贴图，渲染到 outputs/render.png。”
4. 渲染结果在 outputs/ 下。

## 输入输出
- 输入：assets/input/box_design.png（二维展开图）
- 输出：outputs/render.png（三维渲染图）、outputs/model.glb（模型）

## 已知问题
- UV 方向需要人工核对
- 复杂曲面支持有限