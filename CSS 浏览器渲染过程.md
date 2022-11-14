**浏览器渲染过程**  
步骤  
* 根据HTML构建HTML树(DOM)  
* 根据CSS构建CSS树(CSSOM)  
* 将两棵树合并成一颗渲染树(render tree)  
* Layout布局(文档流、盒模型、计算大小和位置)  
* Paint绘制(把边框颜色、文字颜色、阴影等画出来)  
* Compose合成(根据叠层关系展示画面)  

**三种更新方式**  
* 第一种，全走  
* div.remove()会触发当前消失,其他元素relayout  
* 第二种,跳过layout  
* 改变背景颜色,直接repaint + composite  
* 第三种，跳过layout和paint  
* 注意必须全屏查看效果,在iframe里看有问题  
