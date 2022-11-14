**动画**  
定义  
* 由许多静止的画面(帧)  
* 以一定的速度(如每秒30张)连续播放时  
* 肉眼因视觉残像产生错觉  
* 而误以为是活动的画面  

**概念**  
* 帧：每个静止的画面都叫做帧  
* 播放速度：每秒24帧(影视)或者每秒30帧(游戏)


**不用left做动画**  
用transform(变形)  
原理  
* transform:translateX(0=>300px)  
* 直接修改会被合成，需要等一会修改  
* transition过渡属性可以自动脑补中间帧  

注意性能  
* 并没有repaint(重新绘制)  
* 比改left性能好  

**动画优化**  
JS优化  
 * 使用requestAnimationFrame代替setTimeout或setInterval  

CSS优化  
 * 使用will-change或translate  
 * 完全就是死记硬背  
