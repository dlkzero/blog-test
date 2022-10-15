**a标签的用法:**  
属性有:  
* href 超链接  
 
**href的取值:**  
* 网址： 可以简写//xxxx.com 因为最高级  
* 路径:/a/b/c以及a/b/c index.html以及 ./index.html  

**伪协议:**  
* JavaScript:代码;  
* mailto:邮箱;  
* tel:手机号  

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
  

**img标签的用法**:
img标签 图片(永远不要让图片变形)  
作用:发出get请求,展示一张图片  
属性:alt(可选的)/height(高度)/width(宽度)/src(路径)  
事件:onload/onerror  
响应式:max-width:100%  
可替换元素  

```
<img width="400" src="https://www.img.xz95.top/img/wikipedia/zh/9/98/KamenRiderKuuga-title.jpg" alt="">图片
```
**table标签的用法**:
table标签 表格  
table标签里面只能有三个标签:thead tbody tfoot  
tr = table row (行标签)  
th 表头  
td 数据  
相关的样式  
table-layout  
border-collapse 控制边框是否合并  
border-spacing 边框间隙  
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
