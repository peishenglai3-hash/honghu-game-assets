# MAP_CH4_WANGYE_TEMPLE_EARLY_MORNING_SHOT_MEDIUM

- Parent map ID: `MAP_CH4_WANGYE_TEMPLE`
- Shot: `SHOT_MEDIUM`
- State: `SCENE_01_EARLY_MORNING`
- Canvas: 1664×936px
- Tile: 48×48px
- Camera: 正交俯视；几何、透明边界、道具坐标继承自已验证的破晓前版本。
- Time: 1927-09-11 清晨，日出后不久。
- Characters: 不烘焙，全部由 L05 运行时生成。

## Seven layers

1. `L01_GROUND` — 清晨院地及外围地面。
2. `L02_GROUND_DETAIL` — 晨光下的泥痕、水洼、脚印和碎石。
3. `L03_STRUCTURE_LOW` — 台基、台阶、柱体、庙墙、侧门和入口。
4. `L04_PROP_INTERACT` — 原始对联、农会标识、缴获物资和侧方道具的清晨调色实例。
5. `L05_COLLISION_TRIGGER` — 完整继承原版本的 PNG 编辑器预览及 JSON 数据。
6. `L06_OCCLUSION_HIGH` — 屋顶、檐口、树冠与高墙瓦面。
7. `L07_LIGHT_FX` — 保留原透明边界并采用统一清晨曲线的光效及院地补充分区。

原始道具源文件保存在总包 `SourceProps/`，SHA-256 不变；本场景仅对实例进行确定性调色，不重绘文字。
