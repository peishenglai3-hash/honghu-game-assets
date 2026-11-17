# MAP_CH3_TU_COMPOUND_STATE_GATE_BROKEN

- 地图：`MAP_CH3_TU_COMPOUND`
- 状态：`STATE_GATE_BROKEN`
- 状态说明：门闩失效、门叶向内歪开；屋檐瓦面保持完整；前门可进入。
- 画布：1664×936px
- Tile 基准：48×48px
- 原点：左上

## 七层

1. `L01_GROUND`：土路、院地、砖地、室内地面。
2. `L02_GROUND_DETAIL`：裂纹、污渍、残食、地面细节。
3. `L03_STRUCTURE_LOW`：墙体下部、铁门/门叶、台阶、柱基。
4. `L04_PROP_INTERACT`：宴饮桌椅、湖北木榨设备、撞木、武器、包裹、伤员用品。
5. `L05_COLLISION_TRIGGER`：编辑器预览 PNG；运行时读取同名 JSON。
6. `L06_OCCLUSION_HIGH`：屋顶、檐口、院墙瓦面、树冠；榨房屋顶可按进入状态隐藏。
7. `L07_LIGHT_FX`：煤油灯、火焰、烟雾、余烬和夜色光效。

人物、守卫、攻门队、伤员与清点人群均由 Phaser/运行时按出生点生成，不烘焙。
