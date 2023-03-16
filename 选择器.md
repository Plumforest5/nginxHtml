# 基本选择器
## 1.元素选择器  
&emsp;通过元素的名字进行定位，它会获取页面上所有这个元素，无论藏多深都能获取到  
``` html
<style type="text/css">
        h2{
            color: blueviolet;
            font-family: '黑体';
        }
</style>
<h2>这是一个二级标题</h2>
```
## 2.类(Class)选择器  
&emsp;应用场合：不同类型的标签使用相同的样式
``` html
    <style type="text/css">
        .mycls{
            color: brown;
        }
    </style>
    <h2 class="mycls">这是一个二级标题</h2>
    <h3 class="mycls">这是一个三级标题</h3>
```

## 3.ID选择器  
&emsp;应用场合：可以定位唯一的一个元素，虽然可以不同类型的标签使用相同的样式，但我们一般只会让其定位到一个唯一的元素
``` html
    <style type="text/css">
        #myid{
            color: green;
        }
    </style>
    <h4 id="myid">这是一个四级标题</h4>
```
<br/>

### 注意：基本选择器的优先级  
ID选择器>Class选择器>元素选择器  
<br/><br/><br/><br/><br/>



# 关系选择器  
## div
&emsp;div是块级元素  

## span
&emsp;span是块级元素
<br/><br/>

区别效果如下：
``` html
    <style type="text/css">
        div{
            border: 1px red solid;
        }
        span{
            border: 1px green solid;
        }
    </style>

   <div>关系选择器</div> 
   <div>关系选择器</div><br/>

   <span>关系选择器</span>
   <span>关系选择器</span>
```

![](http://121.37.118.53/images/choice.png)

![](http://wmdbd.top/zb_users/upload/2023/01/202301081673167426545584.jpg)
