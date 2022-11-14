**新属性positiion**  
position  
 * static默认值,待在文档流  
 * relative相对定位,升起来,但不脱离文档流  
 * absolute绝对定位,定位基准是祖先里的非static  
 * fixed固定定位,定位基准是viewport(有炸)  
 * sticky粘滞定位  

**经验**  
 * 如果写了absolute,一般都得补一个relative  
 * 如果写了absolute或fixed,一定要补top和left  
 * sticky兼容性很差,主要用于装逼  

**position:relative**  
使用场景  
  * 用于做位移(很少用)  
  * 用于做absolute元素做父元素  

配合z-index  
  * z-index：auto默认值，不创建新叠层上下文  
  * z-index：0/1/2  
  * z-index：-1/-2

经验  
* 写z-index：9999的都是彩笔  
* 学会管理z-index  

**position:absolute**  
使用场景  
* 脱离原来的位置，另起一层，比如对话框的关闭  
* 按钮  
* 鼠标提示  

**配合z-index**  

经验  
* 很多人都以为absolute是相对于relative定位的  
* 某些浏览器上如果不写top/left会位置错乱  
* 善用left:100%  
* 善用left:50%;加负margin

**white-space：nowrap 文字不换行**

**position:fixed**  
使用场景  
* 烦人的广告  
* 回到顶部按钮  

**配合z-index**  

经验  
* 手机上尽量不要用这个属性，坑很多  
* 手机上可以搜索[移动端fixed]
