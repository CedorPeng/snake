# Snake

## 功能分析

- 蛇
- 食物
- 游戏画布
- 可以控制游戏难度
- 开始游戏

- 游戏初始化
  + 蛇会被初始化渲染到画布上
  + 食物随机显示在游戏画布的某一个位置
    * 横轴
    * 纵轴
- 用户点击开始游戏
  + 蛇默认朝右方向运动
  + 用户可以在蛇运动的过程中通过键盘上的控制按钮：上下左右 控制蛇运动的方向
  + 无论是哪个方向，蛇头永远朝前
  + 蛇在运动的过程中，如果蛇头完全于食物重合，则证明食物被蛇吃掉了
  + 当蛇每吃掉一个食物，蛇本身的都会长大一点：一个像素块，
  +   同时该食物消失，然后在游戏画布上随机出现一个新的食物
  + 如果蛇头碰到游戏画布边缘，则游戏结束

## 第三方模块介绍

### jQuery

- 专注于操作 DOM，用来提高 DOM 操作效率

### underscore

- 专注于原生 JavaScript 功能扩展，和 DOM、BOM 没有任何关系
  + 说白了就是提供了一堆的工具函数让你使用更方便
- Array
- Function
- Object
- 常用验证方法
- 使用工具函数
  + 随机数
  + 模板引擎

## 具体代码实现