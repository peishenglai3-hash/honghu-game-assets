# 第二章·陈家祠堂七层地图交付索引

统一规格：1664×936 PNG，正交俯视三分之四视角，48×48 基础格。

## 场景包

1. `MAP_CH2_ANCESTRAL_HALL_MAIN`：带院子的正厅总图（确认版 v05）
2. `MAP_CH2_ANCESTRAL_HALL_SIDEWALL`：祠堂侧墙与物资集中区
3. `MAP_CH2_ANCESTRAL_HALL_MAINHALL_CLOSE`：正厅局部镜头推进场景

## 每个场景包含

- `*_L01_GROUND.png`
- `*_L02_GROUND_DETAIL.png`
- `*_L03_STRUCTURE_LOW.png`
- `*_L04_PROP_INTERACT.png`
- `*_L05_COLLISION_TRIGGER.png`（编辑器可视化，运行时隐藏）
- `*_L05_COLLISION_TRIGGER.json`（碰撞、交互、出生、镜头与出口对象）
- `*_L06_OCCLUSION_HIGH.png`
- `*_L07_LIGHT_FX.png`
- `*_manifest.json`
- `*_PREVIEW_COMPOSITE.png`
- `*_PREVIEW_EDITOR.png`
- `README.md`

七张 PNG 使用相同画布和左上角坐标原点。运行时按照 `manifest.json` 的 `render_order` 载入；`L05` PNG 仅供编辑器检查，实际逻辑读取同名 JSON。
