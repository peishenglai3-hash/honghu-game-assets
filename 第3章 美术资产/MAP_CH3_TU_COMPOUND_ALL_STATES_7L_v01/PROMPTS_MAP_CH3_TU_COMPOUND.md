# MAP_CH3_TU_COMPOUND｜最终提示词摘要

## 基础母图

1927 年中秋夜的洪湖农村富户大院，1664×936，俯视三分之四正交视角，高分辨率像素/HD-2D 叙事 RPG。下方为土路、高院墙和铁皮双门；左下为低墙、成熟大树和残食隐蔽区；左上为宴饮生活区；右上为与大院相连的封闭式湖北传统榨房；中央为大院与后院通路；右侧为物资/武器区。人物不烘焙。

榨房内部固定为横置整木榨床、竖排草圈油饼、木楔、屋架绳索悬吊撞杆、接油槽与陶缸、石碾、蒸/炒料灶、草圈和油料筐。榨房实体封闭，屋顶归 L06 做剖切显示。

## 状态修改锁

- `STATE_WAITING`：铁门开，榨房无火。
- `STATE_GATE_CLOSED`：只关闭门叶；门楼完整。
- `STATE_FIRE_STARTED`：封闭榨房猛烈燃烧，火经门缝/气窗/檐口外泄，浓烟与飞灰增强；前门完整关闭。
- `STATE_GATE_ATTACK`：门外一根无绳、无金属、无轮架的天然粗木撞击门板中心；不改变屋檐、瓦片、门柱或院墙。
- `STATE_GATE_BROKEN`：只让门闩、门叶和地面五金失效；屋顶、屋檐、瓦片、门柱完全不损坏。
- `STATE_AFTER_BATTLE`：火势转弱；右侧武器/财物分区集中；左侧伤员区；中央清点区留空。
- `STATE_DEPARTURE`：余烬；物资捆扎；伤员区收拢；前门通路清空。

## 连续性硬锁

七态必须保持同一建筑坐标、同一左下成熟大树、同一门楼、同一宴饮区、同一封闭榨房和同一后院路径。火光可以改变颜色和阴影，不能改变树、屋顶、瓦片或固定建筑形制。

## 通用负面词

no characters baked in, no modern objects, no electric lights, no CCTV graphics, no text, no UI, no fantasy fortress, no wuxia, no modern oil press, no open-shed oil room, no seesaw press, no rope on gate battering log, no damaged gatehouse roof, no missing tree, no bare roots replacing tree.

