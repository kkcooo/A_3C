# A_3C

### 接方块小游戏


#### 3C简单说明
- board：方形区域，触碰方形区域边缘将导致角色“死亡”; 方形区域上空会随机落下方块
- character:玩家控制的角色是方形平台
- control: WASD控制角色前后左右移动，qe控制角色旋转; 鼠标左键点击地面会触发方块下落
- camara: 摄像始终机跟随角色


#### 游戏简介
- 玩法：鼠标点击地面生成从天而降的方块，在方块落地消失前接住它
- 重新开始：按r
- 退出游戏：按Esc

#### 技术细节
- 玩家的移动、退出游戏及重新开始游戏均通过按键检测实现
- 方块下落的触发通过射线碰撞检测实现
- 方块随机生成通过取随机数实现


#### 相较于第一次开发作业
- 设定了主角的重心位置
- 增加了角色的旋转运动
- 设定了多余方块的消失机制
- 通过新加入的3个平行光，使得方块的下落位置更加清晰，优化了游戏体验
