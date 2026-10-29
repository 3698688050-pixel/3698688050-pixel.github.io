# 工作台

自建小工具的索引页，每件工具都是一个独立的 `index.html`，没有框架、没有后端，断网也能跑。

**在线使用**：https://3698688050-pixel.github.io/

## 收录的工具

| 分组 | 工具 | 仓库 |
|---|---|---|
| 粉体与材料 | 粉体设备预选型 | [powder-equipment-selector](https://github.com/3698688050-pixel/powder-equipment-selector) |
| 粉体与材料 | 材料硬度对比 | [hardness-comparator](https://github.com/3698688050-pixel/hardness-comparator) |
| 粉体与材料 | 目数与微米换算 | [mesh-micron-converter](https://github.com/3698688050-pixel/mesh-micron-converter) |
| 3D 与图像 | 3D 创作工作台 | [3d-workbench](https://github.com/3698688050-pixel/3d-workbench) |
| 阅读与自测 | 《纳瓦尔宝典》读解 | [naval](https://github.com/3698688050-pixel/naval) |
| 阅读与自测 | 邓宁-克鲁格效应自测 | [dunning-kruger-test](https://github.com/3698688050-pixel/dunning-kruger-test) |
| 阅读与自测 | 元素词源卡片 | [element-origin-cards](https://github.com/3698688050-pixel/element-origin-cards) |
| 阅读与自测 | 日常任务清单 | [daily-tasks](https://github.com/3698688050-pixel/daily-tasks) |

## 已归档

功能已并入上面的合并版，旧网址仍然能打开，不再单独维护。

| 旧仓库 | 并入 |
|---|---|
| `pre` 复合配方加权版 | powder-equipment-selector |
| `Pre-selector` 物料自动匹配版 | powder-equipment-selector |
| `syg` GLB 在线预览 | 3d-workbench |
| `painter` GLB 上色材质编辑 | 3d-workbench |

## 加新工具

1. 建一个同名仓库，放一个 `index.html`，开 Pages
2. 在 `index.html` 里对应分组加一行，在本文档的表格里加一行
3. 如果新工具取代了某个旧工具：旧仓库改成 archived，描述写明「已并入 xxx」，并挪到「已归档」表里

## 本地运行

双击 `index.html`。页面不请求任何外部资源，字体走系统栈。
