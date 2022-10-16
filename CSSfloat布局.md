**float布局**  

步骤:  
1.子元素上加float:left和width  
2.在父元素上加.clearfix  

经验:  
* 有经验者会留一些空间或者最后一个不设width  
* 不需要做响应式,因为手机上没有IE,而这个布局是专门为IE准备的  
* IE6/7存在双倍margin bug,解决办法有两个  
* 一是将错就错,针对IE6/7把magrin减半  
* 二是神来一笔,再加一个display:inline-block

当发现border影响布局时,可将border改为outline,不占空间  

实践  
**不同布局**  
* 用float做两栏布局(如顶部条)  
* 用float做三栏布局(如内容区)  
* 用float做四栏布局(如导航)  
* 用float做平均布局(如产品展示区)  

**经验**  
* 加上头尾,即可满足所有PC页面需求  
* 手机页面不需要用float  
* float要自己计算宽度,不灵活  
* float用来应付IE足以  
