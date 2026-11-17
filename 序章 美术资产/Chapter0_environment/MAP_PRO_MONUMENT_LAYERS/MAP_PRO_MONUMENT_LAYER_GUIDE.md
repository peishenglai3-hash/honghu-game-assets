# MAP_PRO_MONUMENT 分层说明

所有图层均为 `1664×936` RGBA PNG，画布原点一致。导入 Tiled 或游戏引擎时使用 Point/Nearest 采样，关闭纹理过滤与抗锯齿。

可见图层自下而上：

1. `L01_GROUND.png`
2. `L02_GROUND_DETAIL.png`
3. `L03_STRUCTURE_LOW.png`
4. `L04_PROP_INTERACT.png`
5. `L06_OCCLUSION_HIGH.png`
6. `L07_LIGHT_FX.png`

`L05_COLLISION_TRIGGER.png` 为数据遮罩，不参与画面合成：

- 红色：碰撞区
- 黄色：纪念碑交互触发区
- 绿色：出生点
- 蓝色：镜头/主要活动区域

`MAP_PRO_MONUMENT_COMPOSITE_VERIFY.png` 是六个可见图层的重组校验图，与源图逐像素一致。

原始文件是已合并的单张 PNG，不包含被树木、房屋和纪念碑遮住的像素；`L01_GROUND.png` 的隐藏区域使用无物体地面参考进行了补全，其余可见像素均直接来自源图。
