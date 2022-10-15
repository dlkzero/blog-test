**a标签的用法:** 
属性有:  
href 超链接  
href的取值:  
网址： 可以简写//xxxx.com 因为最高级  
路径:/a/b/c以及a/b/c index.html以及 ./index.html  
伪协议:  
JavaScript:代码;  
mailto:邮箱; tel:手机号  
target 在每个新窗口打开超链接  
download  
rel=noopener  
作用:  
跳转外部页面  
跳转内部锚点  
跳转到邮箱或电话等  
  
```html
<a href="www.baidu.com">百度</a>
<a href="mailto:313405510@qq.com">邮箱</a>
<a href="tel:13479097715">手机号</a>
```  
a的target的取值 内置名字  
_blank 新的页面打开  
_top 在最顶层页面打开  
_parent 在父级窗口打开  
_self 在默认页面打开   
  

**img标签的用法**:发出get请求,展示一张图片  
```
<img width="400" src="https://www.img.xz95.top/img/wikipedia/zh/9/98/KamenRiderKuuga-title.jpg" alt="">图片
```
**table标签的用法**:用来展示数据
```
    <table>
        <thead>
            <tr>
                <th></th>
                <th>小红</th>
                <th>小明</th>
                <th>小颖</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>数学</th>
                <td>61</td>
                <td>91</td>
                <td>85</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>总分</th>
                <td>200</td>
                <td>200</td>
                <td>200</td>
            </tr>
        </tfoot>
    </table>
```
