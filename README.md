# inventory-graphic
Graphical inventory display for LCD by Space Engineers Script.

太空工程师，图形化显示库存脚本。

# 如何使用

进这个网址 [Program.cs](Program.cs)

复制代码到SE的编程块里

区域是上下两行大括号

开始行
![image](https://github.com/se-scripts/inventory-graphic/assets/46225881/c9da6269-6c71-4e49-b25e-9e928ebe86c4)

结束行
![image](https://github.com/se-scripts/inventory-graphic/assets/46225881/c54d10d9-b706-4ffd-aebf-6e9426e11925)


# 来源

- [游戏《太空工程师》图形化物料显示界面](https://www.bilibili.com/read/cv27778300/)
- <https://github.com/malware-dev/MDK-SE/wiki>

# 作者

- [Hi.James](https://space.bilibili.com/368005035)
- [li-guohao](https://github.com/li-guohao)

# 功能

- 图形化显示物料。
- 图形化显示库存使用量，并带进度条展示。
- 图形化显示氢、氧气罐余量，并带进度条显示。
- [新]图形化显示电池余量，并带进度条显示。


# 配置

和原始的脚本关于这块的配置相同：[游戏《太空工程师》图形化物料显示界面](https://www.bilibili.com/read/cv27778300/)


- 单独显示和混合显示功能不冲突，可同时使用。
- 同样的名称可以命名多块屏，这些屏会显示同样的内容。
- X从1开始，代表显示LCD的顺序。例如， LCD_Inventory_Display:1 表示是第一块屏, LCD_Inventory_Display:2 表示是第二块屏……


|  LCD名称   | 功能  |
|  ----  | ----  |
| LCD_Overall_Display  | 总览屏 |
| LCD_Inventory_Display:X  | 物料显示屏 |
| LCD_Ore_Inventory_Display:X  | 单独显示矿石 |
| LCD_Ingot_Inventory_Display:X  | 单独显示矿锭 |
| LCD_Component_Inventory_Display:X  | 单独显示零件 |
| LCD_AmmoMagazine_Inventory_Display:X  | 单独显示弹药 |



