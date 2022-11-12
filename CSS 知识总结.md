**浏览器渲染原理**  
1. 根据HTML构建HTML树(DOM)  
2. 根据CSS构建CSS树(CSSOM)  
3. 将两棵树合成一颗渲染树(render tree)  
4. Layout布局(文档流、盒模型、计算大小和位置)  
5. Paint绘制(把边框颜色、文字颜色、阴影等画出来)  
6. Compose合成(根据层叠关系展示画面)  

**CSS 动画的两种做法（transition 和 animation）**  

**transition**  
  * 作用:补充中间帧  
  * transition:属性名 时长 过渡方式 延迟  

**animation**  
  * animation:时长 | 过渡方式 | 延迟 | 次数 | 方向 | 填充模式 | 是否暂停 | 动画名; 这些属性都有对应的单独属性

CSS是需要多练以及多积累
