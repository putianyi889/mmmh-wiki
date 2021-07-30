# 基本概念

3BV是完成一张图所需最少左键点击数。IOE是3BV和实际点击数的比值。要提高IOE，就要以尽量少的点击数完成局面。

# 大原则和小技巧

- 禁止双击只开一格。
- 标一开二和两下左键相比：标一开二多的一个雷可能产生后续收益，两下左键第一下若直接破空则可以省一下。绝大多数时候标一开二都赚，少数例外需要通过大量实践总结。
- 可以两侧双击的时候，还有一个选项是双击一下在两侧各开一格。要通过大量实践总结不同局部的最优策略。
  
  ![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/5.gif)
  ![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/7.gif)
- 慎重下手，左键能不点就不点。刚开始刷IOE的玩家很讨厌毛刺，总是会像竞速时那样把表面补平整。刷IOE的时候能不补左键就不补左键，因为后续的双击可能会把这些空位顺便补上。下图中产生的大量毛刺，大多数都被后续双击补上了。
  
  ![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/1.gif)

- 连续双击的时候尽量双击斜角，产生的毛刺后续大概率可以补上：

  ![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/3.gif)
- 空间狭窄的时候要利用双侧信息：
  
  ![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/10.png)
- 标雷尽量标外侧，能产生更多后续收益：
  
  ![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/2.gif)

  这个例子后续还有利用双侧信息的油水，你发现了吗？
- 往远处多看几步：
  
  ![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/6.gif)

# 大局思路

刷IOE时主要处理两种局部：开放局部和封闭局部。

开放局部指非前沿区很大，前沿区有大量可以下手的地方：

![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/1.png)

有些地方看起来封闭，但是仍符合非前沿区很大和机会很多的特点，属于开放局部：

![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/2.png)

处理开放局部主要靠定式。初学者还是要慢慢扫，仔细研究每个局部的最优解，经过一段时间可以总结出开放局部常用的定式，然后可逐渐提速。

封闭局部指非前沿区几乎全部都能判出来，要统筹规划找出最优解：

![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/3.png)
![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/4.png)
![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/5.png)

下图中展示了开放局部和封闭局部的不同处理风格。开放局部大量用标一开多的定式，而封闭局部只能慢慢分析。

![](https://github.com/putianyi889/Minesweeper-makes-me-happy/blob/main/wiki/images/ioe/4.gif)