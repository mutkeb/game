# game
2048小游戏

利用前端技术html、css、js完成的前端小游戏。

项目有以下需求：

1.游戏是一个4*4的方格，每个方格我们称作为一个Tile或者Cell
2.游戏开始能随机出现2个Tile，每个值90%可能为2，10%可能为4
3.可以通过上、下、左、右键盘操作，每个Tile按照方向移动到不可移动为止
4.如果移动以后两个Tile的内容值一样，则进行合并
5.每个Tile以动会有100ms的移动动画
6.每个Tile的出现有个短暂的放大效果
7.每个Tile的合并有个短暂的放大回弹效果
8.顶部Score记录当前分数，BestScore记录有史以来最高分，每次合并都会产生分数的变化，分数计算规则为：分数 = 原来分数 + 合并后的值
9. 游戏将时时刻刻记录进度，刷新页面重现游戏进度
10.当每个Tile的值为2048，游戏胜利
11.当每个方格都有值，并且相邻两个方格无法再进行合并，则游戏结束

技术点：

1.静态页面渲染：需要HTML、CSS基础知识，包括SCSS知识
2.开始游戏等事件处理：需要使用DOM监听事件
3.Tile移动处理：需要监听键盘事件
4.Tile动态随机添加：需要使用DOM动态操作
5.Tile移动，合并：需要使用Javascript列标，对象，方法等数据结构和常用技巧
6.Tile动画：需要使用CSS的transform和animation等动画效果
7.本地缓存：需要使用Javascript的localStorage浏览器缓存


功能包括重新开始，计分、史上最高分等

![image](https://user-images.githubusercontent.com/103638902/226092290-331eba35-dd0e-4c20-8e39-e8b30de6a501.png)
